# CMP METODOLOOGIA

## Struktureeritud ja Parandatud Versioon (v1.1)

------------------------------------------------------------------------

# 1. STRATEEGIA OLEMUS

**Fookus:** Price action Support- ja Resistance-alade vahel.

**Eesmärk:**\
- Mõista, kus hind asub\
- Mõista, kust hind tuli\
- Mõista, mis põhjustas viimase reaktsiooni

> Hind liigub S/R-alade vahel neid testides.\
> Me ei ennusta --- me loeme reaktsiooni.

------------------------------------------------------------------------

# 2. AJARAAMIDE HIERARHIA

  Kiht         Ajaraam       Roll
  ------------ ------------- -----------------------------------
  Story Line   D -- W -- M   Suur pilt (swing-narratiiv)
  Direction    H1 -- H4      Päevasisene suund
  CMP          M1 -- M15     Hetkestruktuur ja tehingu teostus

**Põhimõte:**\
Ülemine kiht annab konteksti.\
Alumine kiht annab täpsuse.

------------------------------------------------------------------------

# 3. CMP KINNITUSE AHELG

CMP toimib järjestusena, mitte üksiksündmusena.

    M1 BO → M5 EG → M5 BO → M15 EG → M15 BO → H1 EG → H1 BO

## Reeglid

1.  BO on kehtiv ainult siis, kui 1 TF kõrgemal on värske EG.\
2.  EG on kehtiv ainult siis, kui 1 TF madalamal toimub BO.\
3.  Ajaraamid peavad üksteist kinnitama.\
4.  Iseseisvaid signaale ei kasutata.

------------------------------------------------------------------------

# 4. OHLC SUPPORT & RESISTANCE (ALUS)

S/R põhineb alati OHLC-andmetel.\
S/R ei ole joon --- see on ala.

## 4.1 Support (Bullish küünal)

**Support-ala = Low → Open**

-   Alumine wick = likviidsus\
-   Keha = aktsepteerimine\
-   Close = tugevam kui wick

## 4.2 Resistance (Bearish küünal)

**Resistance-ala = High → Open**

-   Ülemine wick = likviidsus\
-   Keha = aktsepteerimine\
-   Close = tugevam kui wick

------------------------------------------------------------------------

# 5. EXTENDED OHLC S/R

Ala laieneb, kui „õige suunaline" küünal:

1.  Läbib ala\
2.  Sulgub tsooni sees

## 5.1 Resistance laieneb, kui:

-   Bearish küünal teeb uue kõrgema High\
-   Body close jääb resistance-tsooni sisse

## 5.2 Support laieneb, kui:

-   Bullish küünal teeb uue madalama Low\
-   Body close jääb support-tsooni sisse

**Reegel:**\
Õige suund + sulgumine tsoonis = ala laieneb.

Laieneda võivad: EH, EL, IH, IL, HH, LL, IntH, IntL.

------------------------------------------------------------------------

# 6. STRUKTUUR

## 6.1 External Struktuur

  Trend       Aktiivne   Loodav
  ----------- ---------- --------
  Uptrend     EL         HH
  Downtrend   EH         LL

**Reegel:**\
L/H, mis tekitab BO ja loob uue HH/LL, muutub EH/EL-iks.

HH/LL tähistavad ajaloolisi BO-jooni ja likviidsuspiirkondi.

------------------------------------------------------------------------

## 6.2 Internal Struktuur

Internal struktuur on sama oluline kui external.

  Kontekst   Aktiivne   Loodav
  ---------- ---------- --------
  UP         IL         IntH
  DOWN       IH         IntL

**Reegel:**\
L/H, mis tekitab internal BO ja loob uue IntH/IntL, muutub IH/IL-iks.

HL/LH termineid ei kasutata.

------------------------------------------------------------------------

# 7. ENGULFING (EG)

EG on OHLC ja struktuuri kombinatsioon.

## 7.1 Bearish EG (EH / IH / SEG)

-   Bullish küünal engulfed\
-   Bearish body close \< bullish Low

## 7.2 Bullish EG (EL / IL / BEG)

-   Bearish küünal engulfed\
-   Bullish body close \> bearish High

## EG roll

-   Testib olemasolevaid tasemeid\
-   Loob uue external taseme (kui puudub)\
-   Võimaldab varajast Market Shift (MS) tuvastamist\
-   Aitab määrata targetit

EG ei ole entry-signaal.\
EG on eeltingimus.

------------------------------------------------------------------------

# 8. ROAD BLOCK (RB)

RB = iga eelnev EH/EL või IH/IL.

## Roll

-   Reaktsiooniala\
-   Entry või target\
-   Potentsiaalne pöördekoht

## MTF põhimõte

-   1 TF kõrgem RB = tavaliselt target\
-   Entry tuleb madalamalt TF-lt\
-   Target leitakse kõrgemalt

Olulised on maksimaalselt 3 RB-d.

------------------------------------------------------------------------

# 9. BREAK OF STRUCTURE (BO)

CMP arvestab ainult body close'i.

## 9.1 UP

Bullish close \> HH-ala kõrgeim bearish High

## 9.2 DOWN

Bearish close \< LL-ala madalaim bullish Low

## BO tüübid

  Tüüp   Tähendus
  ------ ------------------------------------
  BOS    Struktuuri murdumine trendi suunas
  MS     EH/EL murdumine (suunamuutus)

## BO tugevus sõltub

-   Body close'i ulatus\
-   Momentum\
-   Jätkuvus

------------------------------------------------------------------------

# 10. CMP JA BIAS

Bias on oluline, kuid otsustav on:

> Kas uus CMP-tsükkel algab õiges HTF-asukohas?

Oluline ei ole ainult suund ---\
oluline on tsükli alguspositsioon kõrgema ajaraami kontekstis.

------------------------------------------------------------------------

# 11. MÄNGUPLAAN

Enne entry't küsi:

1.  Mis on Story Line?\
2.  Mis on Direction?\
3.  Kus hind asub S/R suhtes?\
4.  Mis põhjustas viimase reaktsiooni?\
5.  Kus asub järgmine RB / HTF target?

  Küsimus                     Vastus
  --------------------------- -----------------------------------------
  Story Line                  D-W-M kontekst
  Direction                   H1-H4 suund
  Kust hind tuli              Eelmine S/R ja viimane reaktsioon
  Mis põhjustas reaktsiooni   EG, RB-test, HTF-tase, Extended S/R
  Kus hind on                 Praeguse S/R-ala suhtes
  Kuhu võib minna             Järgmine RB / HTF target / Extended ala

------------------------------------------------------------------------

# 12. VÕTMEPUNKTID

  \#   Põhimõte
  ---- --------------------------------------------------
  1    Kolm kihti: Story Line → Direction → CMP
  2    CMP kinnituse ahel töötab järjestusena
  3    OHLC määrab alad
  4    S/R on ala, mitte joon
  5    Extended OHLC S/R laieneb tsoonis sulgumisel
  6    Body close on otsustav
  7    EG + BO loovad struktuuri
  8    External ja Internal järgivad sama loogikat
  9    RB on reaktsiooniala
  10   Bias ilma õigesti algava tsüklita ei anna eelist

------------------------------------------------------------------------

# 13. TÄIENDAVAD TUVASTAMISED (TULEVIKU MUDEL)

  -----------------------------------------------------------------------
  Nähtus                              Märkus
  ----------------------------------- -----------------------------------
  Stop Hunt / Liquidity Sweep         Wick läbib taseme, body close jääb
                                      tsooni

  OHLC-ala kinnitamine                Hind sulgub S/R-alas
                                      (aktsepteerimine)

  OHLC-ala testimine                  Wick puudutab ala, sulgub
                                      vastassuunas

  Extended OHLC S/R                   Ala laieneb õige suunaga sulgumisel

  Pullback'i sügavus                  Mõõdetav

  Protected H/L murdumine või sweep   Mõõdetav

  AOI                                 Area of Interest -- viimase
                                      aktiivse external range
                                      reaktsioonialad
  -----------------------------------------------------------------------

------------------------------------------------------------------------

CMP Metodoloogia v1.1 -- Struktureeritud ja Parandatud Dokumentatsioon
