CMP TRADING SYSTEM
Formal Strategy Specification
Version 1.0
0. Document Control
Field	Value
System Name	CMP (Candle Model Process)
Version	1.0
Method Type	Price Action – Multi-Timeframe Structural Model
Core Logic	OHLC-Based Support & Resistance + Engulfing + Break of Structure
Market Type	Any liquid market (FX, Indices, Crypto, Futures)
Timeframe Architecture	HTF → ITF → LTF Hierarchy
1. System Philosophy

CMP is a reaction-based structural model, not a prediction model.

The market moves between defined OHLC-based Support and Resistance areas.
Structure is formed through Engulfing (EG) and confirmed through Break of Structure (BO).

The objective is not to forecast direction.
The objective is to read structural transitions between zones.

2. Timeframe Architecture (Hierarchical Model)
2.1 Layered Structure
Layer	Timeframes	Function
Story Line	D – W – M	Macro structural bias
Direction	H1 – H4	Intraday directional context
CMP Execution	M1 – M15	Structural confirmation & entry
2.2 Hierarchical Principle
[ Story Line ]
        ↓
[ Direction ]
        ↓
[ CMP Execution ]


Upper layer = Context
Lower layer = Precision

Lower TF signals are invalid without higher TF structural alignment.

3. CMP Confirmation Chain

CMP functions as a sequential structural validation model.

3.1 Structural Chain
M1 BO
   ↓
M5 EG
   ↓
M5 BO
   ↓
M15 EG
   ↓
M15 BO
   ↓
H1 EG
   ↓
H1 BO

3.2 Validation Rules

A BO is valid only if a fresh EG exists one timeframe higher.

An EG is valid only if a BO occurs one timeframe lower.

Timeframes confirm each other.

No isolated signals.

4. OHLC-Based Support & Resistance Model

CMP defines S/R strictly using OHLC.

4.1 Support Definition (Bullish Candle)
High
 │
 │
Open  ← Upper body boundary
 │
 │
Low   ← Support boundary


Support Zone = Low → Open

Components:

Lower wick = liquidity

Body = acceptance

Close > wick significance

4.2 Resistance Definition (Bearish Candle)
High  ← Resistance boundary
 │
 │
Open  ← Lower body boundary
 │
 │
Low


Resistance Zone = High → Open

Structural Rule

Support & Resistance are zones — not lines.

5. Extended OHLC S/R Model

A zone expands when a directional candle:

Breaks the zone

Closes inside the zone

5.1 Resistance Extension Condition

New Higher High formed by bearish candle

Body close remains inside resistance zone

5.2 Support Extension Condition

New Lower Low formed by bullish candle

Body close remains inside support zone

Zone Expansion Logic
Break → Close Inside → Zone Expands


Expandable Structures:
EH, EL, IH, IL, HH, LL, IntH, IntL

6. Structural Framework

CMP operates with dual structure:

• External Structure
• Internal Structure

Both follow identical logic.

6A. External Structure
Trend	Active	Creating
Uptrend	EL	HH
Downtrend	EH	LL
Structural Rule

When a High/Low:

Creates a BO

Produces a new HH/LL

It becomes EH or EL.

HH/LL = historical BO lines & liquidity markers.

External Diagram
Uptrend Example:

EL → HH → EL → HH → EL → HH

Downtrend Example:

EH → LL → EH → LL → EH → LL

6B. Internal Structure

Internal structure is equally important.

Context	Active	Creating
UP	IL	IntH
DOWN	IH	IntL

HL/LH terminology is not used.

7. Engulfing (EG)

EG = Structural + OHLC event.

7.1 Bearish EG (EH / IH / SEG)

Condition:

Bullish candle engulfed
AND
Bearish body close < bullish Low

7.2 Bullish EG (EL / IL / BEG)

Condition:

Bearish candle engulfed
AND
Bullish body close > bearish High

7.3 Functional Role of EG

Tests zones

Creates new external if none exists

Enables early Market Shift detection

Defines target direction

EG is NOT an entry trigger.
EG is a structural prerequisite.

8. Road Block (RB)

RB = Any previous EH / EL / IH / IL.

Functional Role

Reaction zone

Entry location

Target level

Reversal probability area

MTF Rule
Higher TF RB → Target
Lower TF confirmation → Entry


Maximum relevance: 3 active RBs.

9. Break of Structure (BO)

CMP counts body close only.

9.1 Upward BO
Bullish close >
Highest bearish High of HH zone

9.2 Downward BO
Bearish close <
Lowest bullish Low of LL zone

9.3 BO Types
Type	Meaning
BOS	Trend continuation
MS	Break of EH/EL (bias shift)
BO Strength Factors

Body close depth

Momentum

Continuation

10. Bias & Cycle Positioning

Bias alone is insufficient.

Critical Question:

Is the new CMP cycle starting
in the correct HTF structural location?


Edge exists only when:

Cycle start + HTF alignment = Valid.

11. Operational Checklist (Execution Protocol)

Before entry, validate:

Structural Context

Story Line (D/W/M)?

Direction (H1/H4)?

Current S/R position?

What caused last reaction?

Where is next RB?

Execution Table
Question	Required Answer
Story Line?	HTF structure
Direction?	Intraday bias
Where did price come from?	Previous S/R
Reaction cause?	EG / RB / HTF touch / Extended
Current position?	Inside / Above / Below S/R
Next objective?	RB / HTF target
12. System Principles Summary

Price moves between OHLC zones

Body close is decisive

EG + BO build structure

External & Internal follow identical logic

RB defines reaction areas

Timeframes must confirm

Bias without structure = no edge

Cycle positioning inside HTF context is critical

13. Advanced Detection Layer (Future Model Integration)
Phenomenon	Definition
Stop Hunt / Liquidity Sweep	Wick breaks level, body closes inside
OHLC Confirmation	Close inside zone (acceptance)
OHLC Test	Wick touch, close opposite
Extended Zone	Directional expansion inside zone
Pullback Depth	Measurable
Protected H/L Sweep	Measurable
AOI	Historical external reaction zones
14. System Identity Summary

CMP is:

• A structural reaction model
• OHLC-driven
• Multi-timeframe validated
• Cycle-dependent
• Non-predictive
• Context-first
