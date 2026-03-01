# Frontier Map: Local Wealth and Taxation

**Project:** Local Wealth and Taxation
**Date:** 2026-03-01
**Phase:** Discovery

---

## What Is Established

### 1. Politician Characteristics Causally Affect Policy
A large body of evidence using close-election RDD shows that who governs matters: gender (Chattopadhyay and Duflo 2004; Brollo and Troiano 2016), education (Besley, Montalvo, and Reynal-Querol 2011), criminal background (Prakash et al. 2019), business experience (Szakonyi 2018, 2020), and party affiliation all causally shape policy and economic outcomes.

### 2. Politicians Derive Private Financial Returns from Office
Fisman et al. (2014) show winners' assets grow 3-5 pp/year faster than losers in India. Eggers and Hainmueller (2009) show Conservative MPs doubled their wealth in the UK. Szakonyi (2018) shows connected firms increase revenue by 60% in Russia. The private returns to office are substantial and well-documented.

### 3. Politicians' Personal Financial Interests Influence Policy Votes
Tahoun and van Lent (2019) show a direct link between U.S. congresspeople's financial exposure and their bailout votes. Folke et al. (2024) show politicians with governing power reduce building permits in their own neighborhoods. The "skin in the game" channel is empirically supported.

### 4. Brazilian Municipal Politics Is a Well-Studied Laboratory
Close-election RDD has been extensively validated in Brazilian mayoral races. The data infrastructure (TSE, CGU, RAIS, FINBRA) is mature. Multiple top-5 and top-field journal papers use this setting.

### 5. Property Taxation in Brazil Is Politically Determined
Christensen and Garfias (2021) show cadastre investment depends on electoral incentives. Hollenbach and Silva (2019) show inequality suppresses property tax collection. IPTU under-collection is well-documented (~0.5% GDP vs. 0.9-1.2% potential). Property tax under-collection is a global developing-country phenomenon (Bahl and Martinez-Vazquez 2007; Norregaard 2013; Bird and Slack 2004), with political elite resistance identified as a key barrier.

### 6. Tax Competition Creates Baseline Distortions in Local Taxation
Wilson (1986) and Zodrow and Mieszkowski (1986) establish that interjurisdictional competition for mobile capital leads to inefficiently low property tax rates. Keen and Konrad (2013) survey three decades of evidence showing strategic interaction (reaction function slopes 0.3-0.7). Agrawal (2015) finds spatial tax gradients; Parchet (2019) shows naive estimates are biased and reveals strategic substitutability via income sorting.

### 7. Tax Capitalization Links Property Values to Tax Policy
Oates (1969) first showed property taxes capitalize into property values. Palmon and Smith (1998) confirm ~100% capitalization using boundary discontinuity. Brueckner (1979) shows property-value-maximizing governments provide efficient public goods. Capitalization is the mechanism that makes "skin in the game" operative for mayors with local real estate.

### 8. Politicians' Connections Enable Self-Dealing
Khwaja and Mian (2005) show government banks lend 45% more to politically connected firms. Fisman and Wang (2015) show connected firms circumvent safety regulations. These canonical conflict-of-interest papers establish that politicians use public institutions for private benefit -- the self-dealing channel we hypothesize.

---

## What Is Debated

### 1. Selection vs. Incentive Mechanisms
Does positive selection of wealthy politicians improve governance, or does it create self-dealing opportunities? The direction is theoretically ambiguous.

### 2. Direction of Wealth Effect on Taxation
Wealthy mayors could suppress taxes (self-dealing), improve administration (competence), or show no effect (ideology dominates).

### 3. External Validity of Close-Election RDD for Politician Characteristics
Methodological debate about what close-election RDD estimates capture when applied to politician characteristics (LATE interpretation). de Magalhães et al. (2025) use lottery-resolved ties as experimental benchmarks; Marshall (2022) discusses identification of politician-characteristic effects.

### 4. Tax Competition: Strategic Complements or Substitutes?
Parchet (2019) overturns the naive finding of strategic complementarity, showing income sorting produces strategic substitutability. Whether neighboring municipalities respond to IPTU changes with complementary or substitute behavior has different welfare implications.

### 5. Tiebout Sorting as Confound or Channel
Epple and Sieg (1999) show sorting is quantitatively important. Banzhaf and Walsh (2008) confirm households move in response to local amenity changes. Whether sorting in response to IPTU differences is a confound (endogeneity) or channel (mechanism) depends on the research question.

---

## The Gap Our Paper Fills

**No paper examines whether the geographic concentration of a politician's personal wealth in their own jurisdiction affects fiscal policy.**

Existing work either:
- Studies private returns TO office (reverse direction)
- Studies business politicians without distinguishing local vs. non-local assets
- Studies neighborhood effects without fiscal outcomes
- Studies Brazilian property taxation without politician-level variation

We bridge the politician-wealth literature with the Brazilian municipal fiscal policy literature using close-election RDD.

---

## Visual Map of Literature Streams

```
POLITICIAN WEALTH & GOVERNANCE          BRAZILIAN MUNICIPAL POLITICS
  Fisman et al. 2014 (India)             Ferraz & Finan 2008, 2011
  Eggers & Hainmueller 2009 (UK)         Brollo et al. 2013
  Szakonyi 2018, 2020 (Russia)           Brollo & Troiano 2016
  Tahoun & van Lent 2019 (US)            Colonnelli et al. 2020
  Potrafke 2024 (Survey)                 Arvate et al. 2018
            \                               /
             \                             /
              \                           /
               === OUR PAPER ===
               Local Wealth of Brazilian
               Mayors and Taxation
              /           |               \
             /            |                \
            /             |                 \
  POLITICIAN NEIGHBORHOODS   |          PROPERTY TAX IN BRAZIL
  & PLACE-BASED INTERESTS   |           Christensen & Garfias 2021
  Folke et al. 2024         |           Hollenbach & Silva 2019
  Hall & Thompson 2022      |           Dahis et al. 2025 (MiDES)
                             |           Monteiro & Ferraz 2012
                             |
              +--------------+--------------+
              |              |              |
    TAX COMPETITION    TAX CAPITALIZATION   CONFLICT OF INTEREST
    Wilson 1986        Oates 1969           Khwaja & Mian 2005
    Zodrow & M. 1986   Brueckner 1979       Fisman & Wang 2015
    Keen & Konrad 2013  Palmon & Smith 1998
    Agrawal 2015
    Parchet 2019
              |              |              |
    TIEBOUT/SORTING    PROPERTY TAX DEV.   RDD METHODOLOGY
    Epple & Sieg 1999  Bahl & M-V 2007    de Magalhães+ 2025
    Banzhaf & Walsh 08 Norregaard 2013     Marshall 2022
                       Bird & Slack 2004
```

---

## Scooping Risk: LOW

No working paper or published article directly studies Brazilian mayors' local wealth concentration and fiscal/taxation outcomes. The combination of TSE asset data + close-election RDD + IPTU/ISS/ITBI fiscal outcomes appears to be novel.

**Portuguese-language check (2026-03-01):** Searched ANPEC proceedings, IPEA Discussion Papers, SciELO Brazil, FGV working papers, and SSRN (Portuguese terms). No competing paper found. IPEA papers study IPTU at the municipality level without linking to individual mayor wealth. ANPEC papers using TSE data focus on wealth accumulation (returns to office), not the wealth-to-policy channel. Scooping risk confirmed LOW in both English and Portuguese literatures.
