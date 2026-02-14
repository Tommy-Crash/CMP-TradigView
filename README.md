# CMP METODOLOOGIA

## Ülevaatlik Raamistik -- Täisversioon (v1.0)

------------------------------------------------------------------------

# 1. STRATEEGIA OLEMUS

**Fookus:** Price action Support ja Resistance alade vahel\
**Eesmärk:** Mõista: - Kus hind on - Kust ta tuli - Mis põhjustas
reaktsiooni

> Hind liigub S/R tasemeid testides.\
> Me ei ennusta --- me loeme reaktsiooni.

------------------------------------------------------------------------

# 2. AJARAAMIDE HIERARHIA

  Kiht         TF            Roll
  ------------ ------------- ------------------------------
  Story Line   D -- W -- M   Suur pilt (swing narratiiv)
  Direction    H1 -- H4      Päevasisene suund
  CMP          M1 -- M15     Hetke struktuur ja execution

Ülemine kiht annab konteksti.\
Alumine kiht annab täpsuse.

------------------------------------------------------------------------

# 3. CMP KINNITUSE AHELG

CMP töötab järjestusena:

    M1 BO → M5 EG → M5 BO → M15 EG → M15 BO → H1 EG → H1 BO

### Reeglid

-   BO on valid ainult siis, kui 1 TF kõrgemal on värske EG
-   EG on valid ainult siis, kui 1 TF madalamal toimub BO
-   TF-id kinnitavad teineteist

------------------------------------------------------------------------

# 4. OHLC SUPPORT & RESISTANCE (ALUS)

S/R põhineb alati OHLC-l.\
S/R ei ole joon --- see on ala.

## Bullish Küünal → Support

Support = Low → Open

-   Alumine wick = likviidsus
-   Keha = aktsepteerimine
-   Close = tugevam kui wick

## Bearish Küünal → Resistance

Resistance = High → Open

-   Ülemine wick = likviidsus
-   Keha = aktsepteerimine
-   Close = tugevam kui wick

------------------------------------------------------------------------

# 5. EXTENDED OHLC S/R

Ala laieneb, kui "õige suunaline" küünal:

1.  Läbib ala\
2.  Sulgub tsooni sees

### Resistance laieneb kui:

-   Kõrgem bearish küünal teeb uue High
-   Body close jääb resistance tsooni sisse

### Support laieneb kui:

-   Madalam bullish küünal teeb uue Low
-   Body close jääb support tsooni sisse

Õige suund + sulgumine tsoonis = ala laieneb.

Laieneda võivad:\
EH, EL, IH, IL, HH, LL, IntH, IntL

------------------------------------------------------------------------

# 6. STRUKTUUR

## A. External Struktuur

  Trend       Aktiivne   Loodav
  ----------- ---------- --------
  Uptrend     EL         HH
  Downtrend   EH         LL

**Reegel:**\
L/H, mis tekitab BO ja loob uue HH/LL, muutub EH/EL-iks.

HH/LL = ajaloolised BO-jooned ja likviidsuse markerid.

------------------------------------------------------------------------

## B. Internal Struktuur

Internal ei ole vähem tähtis kui external.

  Kontekst   Aktiivne   Loodav
  ---------- ---------- --------
  UP         IL         IntH
  DOWN       IH         IntL

**Reegel:**\
L/H, mis tekitab internal BO ja loob uue IntH/IntL, muutub IH/IL-iks.

HL/LH termineid ei kasutata.

------------------------------------------------------------------------

# 7. ENGULFING (EG)

EG = OHLC + struktuuri kombinatsioon.

## Bearish EG (EH / IH / SEG)

-   Bullish küünal engulfed
-   Bearish body close \< bullish Low

## Bullish EG (EL / IL / BEG)

-   Bearish küünal engulfed
-   Bullish body close \> bearish High

### EG roll

-   Testib olemasolevaid tasemeid
-   Kui external puudub → loob uue
-   Võimaldab varajast MS märkamist
-   Aitab määrata targeti

EG ei ole entry signaal.\
EG on eeltingimus.

------------------------------------------------------------------------

# 8. ROAD BLOCK (RB)

RB = iga vana EH/EL või IH/IL.

### Roll

-   Reaktsiooniala
-   Entry või target
-   Potentsiaalne reversal koht

### MTF põhimõte

-   1 TF kõrgem RB on tavaliselt target
-   Entry tuleb madalamalt TF-lt
-   Target leitakse kõrgemalt
-   Olulised on kuni 3 RB-d

------------------------------------------------------------------------

# 9. BREAK OF STRUCTURE (BO)

CMP arvestab ainult body close'i.

## UP

Bullish close \> HH ala kõrgeim bearish High

## DOWN

Bearish close \< LL ala madalaim bullish Low

### BO tüübid

  Tüüp   Tähendus
  ------ ------------------------------------
  BOS    Struktuuri murdumine trendi suunas
  MS     EH/EL murdumine (suuna muutus)

### BO tugevus sõltub:

-   Body close ulatusest
-   Momentumist
-   Jätkuvusest

------------------------------------------------------------------------

# 10. CMP JA BIAS

Bias on oluline, kuid otsustav on:

> Kas uus CMP tsükkel algab õiges kohas?

Oluline pole lihtsalt suund ---\
oluline on tsükli alguspositsioon HTF kontekstis.

------------------------------------------------------------------------

# 11. MÄNGUPLAAN

Enne entryt küsi alati:

-   Story Line?
-   Direction?
-   Kus hind on S/R suhtes?
-   Mis põhjustas viimase reaktsiooni?
-   Kus on järgmine RB / HTF target?

  -----------------------------------------------------------------------
  Küsimus                                 Vastus
  --------------------------------------- -------------------------------
  Story Line?                             D-W-M kontekst

  Direction?                              H1-H4 suund

  Kust hind tuli?                         Eelmine S/R tase, viimane
                                          reaktsioon

  Mis põhjustas reaktsiooni?              EG, RB test, HTF tase puudutus,
                                          Extended S/R

  Kus hind on?                            Praeguse S/R ala suhtes

  Kuhu võib minna?                        Järgmine RB / HTF target /
                                          Extended ala
  -----------------------------------------------------------------------

------------------------------------------------------------------------

# 12. VÕTMEPUNKTID

  -----------------------------------------------------------------------
  \#               Põhimõte
  ---------------- ------------------------------------------------------
  1                Kolm kihti: Story Line → Direction → CMP

  2                CMP kinnituse ahel töötab järjestusena

  3                OHLC Support: Bullish küünal Low → Open

  4                OHLC Resistance: Bearish küünal High → Open

  5                Extended OHLC S/R: Ala laieneb tsoonis sulgumisel

  6                Price action S/R vahel --- body close on kuningas

  7                EG + OHLC loovad alad

  8                EH/IH/SEG = Bearish EG

  9                EL/IL/BEG = Bullish EG

  10               RB = iga vana EH/EL/IH/IL

  11               BO reegel: body close \> HH high / \< LL low

  12               BOS vs MS

  13               Bias peab olema toetatud CMP tsükliga

  14               Tea alati: Story Line, Direction, Extended S/R, kust
                   hind tuli, kus ta on
  -----------------------------------------------------------------------

------------------------------------------------------------------------

# 13. TÄIENDAVAD TUVASTAMISED TULEVIKU MUDELISSE

  -----------------------------------------------------------------------
  Nähtus                              Märkus
  ----------------------------------- -----------------------------------
  Stop Hunt / Liq Sweep               Wick läbib taseme, body close jääb
                                      tsooni

  OHLC Ala Kinnitamine                Hind sulgub S/R alas
                                      (aktsepteerimine)

  OHLC Ala Testimine                  Wick puudutab ala, sulgub
                                      vastassuunas

  Extended OHLC S/R                   Ala laieneb tsoonis sulgumisel

  Pullback'i sügavus                  Mõõdetav

  Protected H/L murdumine või sweep   Mõõdetav

  AOI                                 Area of Interest --- viimase
                                      aktiivse external range
                                      reaktsioonialad
  -----------------------------------------------------------------------

------------------------------------------------------------------------

CMP Metodoloogia -- Täielik Dokumentatsioon v1.0
