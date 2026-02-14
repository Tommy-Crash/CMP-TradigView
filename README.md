# CMP Trading System

### Formal Strategy Specification (v1.0)

------------------------------------------------------------------------

## Overview

  -----------------------------------------------------------------------
  Item                   Description
  ---------------------- ------------------------------------------------
  Method Type            Price Action --- Multi-Timeframe Structural
                         Model

  Core Logic             OHLC Support/Resistance Zones + Engulfing (EG) +
                         Break of Structure (BO)

  Goal                   Read structural reactions between zones (not
                         prediction)

  Key Rule               **Body close is decisive**
  -----------------------------------------------------------------------

------------------------------------------------------------------------

## Timeframe Architecture

  Layer        Timeframes      Purpose
  ------------ --------------- --------------------------
  Story Line   D / W / M       Macro structural context
  Direction    H1 / H4         Intraday bias
  Execution    M1 / M5 / M15   Confirmation & entry

Hierarchy:

    Story Line (D/W/M)
            ↓
        Direction (H1/H4)
            ↓
        Execution (M1/M5/M15)

------------------------------------------------------------------------

## CMP Confirmation Chain

    M1 BO → M5 EG → M5 BO → M15 EG → M15 BO → H1 EG → H1 BO

Rules: - BO valid only if fresh EG exists 1 TF higher - EG valid only if
BO occurs 1 TF lower - No isolated signals

------------------------------------------------------------------------

## OHLC Support & Resistance

Support and Resistance are zones --- not lines.

### Support (Bullish Candle)

Zone = Low → Open

### Resistance (Bearish Candle)

Zone = High → Open

------------------------------------------------------------------------

## Structure Model

### External Structure

  Trend       Active   Creating
  ----------- -------- ----------
  Uptrend     EL       HH
  Downtrend   EH       LL

### Internal Structure

  Context   Active   Creating
  --------- -------- ----------
  UP        IL       IntH
  DOWN      IH       IntL

------------------------------------------------------------------------

## Engulfing (EG)

Bearish EG: - Bullish candle engulfed - Bearish close \< bullish Low

Bullish EG: - Bearish candle engulfed - Bullish close \> bearish High

EG is a structural prerequisite --- not an entry trigger.

------------------------------------------------------------------------

## Break of Structure (BO)

Only body close counts.

UP: Bullish close \> HH zone highest bearish High

DOWN: Bearish close \< LL zone lowest bullish Low

------------------------------------------------------------------------

## Road Block (RB)

RB = previous EH / EL / IH / IL

Higher TF RB → Target Lower TF confirmation → Entry

------------------------------------------------------------------------

## Core Principles

1.  Price moves between OHLC zones
2.  Body close is decisive
3.  EG + BO build structure
4.  TFs must confirm
5.  Bias alone is not edge --- cycle positioning is

------------------------------------------------------------------------

## Version

CMP Trading System --- Specification v1.0
