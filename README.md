# CMP Institutional Manual

## Version 2.2 -- Professional Edition

------------------------------------------------------------------------

## Document Control

  Field            Value
  ---------------- -------------------------------------------------------
  System Name      CMP (Candle Model Process)
  Version          2.2
  Classification   Institutional Structural Price Action Framework
  Architecture     Multi-Timeframe Reaction Model
  Core Modules     Structure / Execution / Risk / Psychology
  Edge Formula     HTF Location + Correct Cycle Start + MTF Confirmation

------------------------------------------------------------------------

## System Philosophy

CMP is a reaction-based structural framework built on OHLC-defined
zones.

Price moves between validated Support and Resistance areas.\
Liquidity is taken before continuation or reversal.\
Acceptance is confirmed only by body close.

CMP does not predict direction.\
CMP reads structural transitions between liquidity zones.

### Market Behavior Law

-   Price oscillates between confirmed OHLC zones\
-   Liquidity is swept before structural continuation\
-   Body close confirms structural validity

------------------------------------------------------------------------

## Master Flow Model

HTF Context (Story Line)\
↓\
Directional Bias (H1/H4)\
↓\
Location at Valid S/R\
↓\
Engulfing Event (EG)\
↓\
Break of Structure (BO)\
↓\
Execution\
↓\
Risk Control\
↓\
Target = Next RB

------------------------------------------------------------------------

# Module I --- Structure

## 1. Timeframe Architecture

  Layer        Timeframe       Function
  ------------ --------------- ----------------------------
  Story Line   D / W / M       Macro structural narrative
  Direction    H1 / H4         Intraday bias
  Execution    M1 / M5 / M15   Structural precision

Upper timeframe defines context.\
Lower timeframe defines confirmation.

## 2. OHLC Zone Model

Support Zone = Low → Open (bullish candle)\
Resistance Zone = High → Open (bearish candle)

-   Wick = liquidity\
-   Body close = acceptance\
-   Zones are areas, not lines

## 3. Extended OHLC Logic

Zone expands when:

1.  Candle breaks the zone\
2.  Candle closes inside the zone

**Resistance expansion** - Bearish candle forms new High\
- Body close remains inside resistance zone

**Support expansion** - Bullish candle forms new Low\
- Body close remains inside support zone

Applies to: EH, EL, IH, IL, HH, LL, IntH, IntL.

## 4. Structural Hierarchy

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

Rule:\
High/Low that creates BO and produces new HH/LL becomes EH/EL.\
Internal structure follows identical logic (IH/IL).

## 5. Structural Events

### Engulfing (EG)

**Bearish EG**\
Body close \< bullish Low

**Bullish EG**\
Body close \> bearish High

**EG Role** - Tests structural zones\
- Creates new external if missing\
- Establishes directional pressure toward next RB\
- Enables early Market Shift detection

EG is a prerequisite, not an entry trigger.

### Break of Structure (BO)

**UP**\
Bullish close \> HH zone highest bearish High

**DOWN**\
Bearish close \< LL zone lowest bullish Low

  Type   Meaning
  ------ --------------
  BOS    Continuation
  MS     Market Shift

#### BO Strength Model

Strength increases when: - Close depth extends beyond zone width\
- Follow-through candle confirms momentum\
- Impulse range exceeds recent average range

------------------------------------------------------------------------

# Module II --- Execution

## 1. CMP Confirmation Chain

M1 BO → M5 EG → M5 BO → M15 EG → M15 BO → H1 EG → H1 BO

Rules: 1. BO valid only if fresh EG exists one TF higher\
2. EG valid only if BO occurs one TF lower\
3. No isolated signals

## 2. Road Block (RB)

RB = previous EH / EL / IH / IL

**Functions** - Reaction area\
- Target location\
- Potential reversal zone

**MTF Principle** Higher TF RB = Target\
Lower TF confirmation = Entry

Maximum focus: 3 active RBs.

## 3. Execution Flow

Identify HTF context\
↓\
Confirm direction\
↓\
Wait for price at valid S/R\
↓\
Wait for EG\
↓\
Confirm BO\
↓\
Execute\
↓\
Place stop beyond structural invalidation

------------------------------------------------------------------------

# Module III --- Risk Management

## 1. Risk Philosophy

Risk is structural.\
Invalidation equals break of structural premise.

## 2. Stop Placement

Stop must be: - Beyond EH/EL/IH/IL invalidation\
- Outside liquidity sweep zone\
- Outside extended zone expansion

## 3. Target Logic

Primary target = Next higher timeframe RB\
Secondary target = Extended zone objective

Risk-to-Reward must justify structural clarity.

## 4. Trade Lifecycle

Entry\
↓\
Structural confirmation\
↓\
Risk protected\
↓\
Approach next RB\
↓\
Exit or trail

------------------------------------------------------------------------

# Module IV --- Trader Psychology

## Core Principles

1.  No prediction bias\
2.  Wicks do not confirm structure\
3.  Only body close confirms structure\
4.  Patience until full CMP chain forms\
5.  No trades between zones without confirmation

## Discipline Flow

Context\
↓\
Location\
↓\
Structure\
↓\
Confirmation\
↓\
Execution\
↓\
Management

------------------------------------------------------------------------

## CMP Edge Equation

Edge = HTF Location + Correct CMP Cycle Start + MTF Confirmation

Without correct location, no edge exists.\
Without full chain confirmation, no execution.

------------------------------------------------------------------------

CMP Institutional Manual --- Version 2.2
