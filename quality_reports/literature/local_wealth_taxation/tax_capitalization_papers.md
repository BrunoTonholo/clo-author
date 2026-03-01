# Tax Capitalization Literature: Annotated Entries

**Project:** Local Wealth and Taxation
**Date:** 2026-03-01
**Purpose:** Fill the "capitalization literature" gap flagged by Editor (see `lit_review_editor_report.md`, Issue 2)
**Category:** Theoretical Foundations / Same Context, Different Method

---

## Why Tax Capitalization Matters for This Project

The capitalization literature establishes that property tax differences are reflected (capitalized) into property values. This has two critical implications for our study of Brazilian mayors' local wealth and taxation:

1. **Mechanism:** If a wealthy mayor suppresses IPTU rates, local property values should rise, directly benefiting the mayor's own real estate holdings. Capitalization provides the economic channel through which "skin in the game" operates -- it is the reason a mayor with local real estate cares about local tax policy in the first place.

2. **Identification threat:** If tax policy capitalizes into property values, then the mayor's measured wealth (from TSE asset declarations) is endogenous to their own tax decisions. A mayor who cuts IPTU sees their own declared real estate values increase. This creates reverse causality: we want to study how wealth affects taxes, but taxes also affect wealth. The RDD design (comparing barely-winning vs. barely-losing candidates) addresses this by using pre-election wealth, but post-election wealth dynamics require careful discussion.

---

## Paper 1: Oates (1969)

### Full Citation

Wallace E. Oates, "The Effects of Property Taxes and Local Public Spending on Property Values: An Empirical Study of Tax Capitalization and the Tiebout Hypothesis," *Journal of Political Economy*, Vol. 77, No. 6 (November/December 1969), pp. 957-971.

### Summary

Oates (1969) provided the first systematic empirical test of whether local property taxes and public expenditures capitalize into residential property values. Working within the Tiebout (1956) framework, Oates argued that if households sort across jurisdictions based on tax-service bundles, then differences in local fiscal packages should be reflected in housing prices. Using cross-sectional data from 53 municipalities in northeastern New Jersey, he regressed median residential property values on effective property tax rates, per-pupil school expenditure, and community characteristics. He found that higher property tax rates are associated with lower property values while higher school expenditures are associated with higher values, consistent with capitalization. The estimated tax coefficient implied roughly full capitalization of tax differentials.

### Identification Strategy

Cross-sectional OLS regression of property values on tax rates and expenditures across municipalities, controlling for community characteristics (median family income, distance to New York City, percentage of population commuting, and other demographics). No quasi-experimental design -- relies on conditional-on-observables assumption. Oates acknowledged potential simultaneity (high property values expand the tax base, allowing lower rates) and attempted to address it through the choice of controls and by noting the direction of bias.

### Key Data Source

U.S. Census data on housing values and community characteristics for 53 residential communities in the New Jersey portion of the New York metropolitan area (1960 Census). Effective tax rates from the New Jersey Division of Tax Appeals.

### Main Result

- **Sign:** Negative effect of taxes on property values; positive effect of school spending on values.
- **Magnitude:** A $1 increase in the effective property tax rate per $1,000 of market value was associated with a decrease in median property values of approximately $1,500 (on a mean of approximately $20,000), broadly consistent with full capitalization at prevailing discount rates. School expenditures of $100 per pupil were associated with roughly $1,500 higher property values.
- **Interpretation:** Local fiscal differentials are reflected in house prices, supporting the Tiebout hypothesis.

### Proximity Score: 2

**Relevance to our project:** Foundational. Oates (1969) established the theoretical and empirical basis for why a mayor with local real estate holdings should care about local tax policy. If IPTU rate changes capitalize into Brazilian property values, then a mayor with real estate concentrated in their municipality has a direct financial stake in tax-rate decisions. We do not replicate Oates's approach, but his result provides the economic logic underlying our "skin in the game" mechanism. Must be cited in the paper's motivation section and in the discussion of the capitalization channel. Also relevant for acknowledging the identification threat: if we observe higher property values in municipalities with wealthy-local mayors, this could reflect capitalization of their tax policies, not just pre-existing wealth.

---

## Paper 2: Brueckner (1979)

### Full Citation

Jan K. Brueckner, "Property Values, Local Public Expenditure and Economic Efficiency," *Journal of Public Economics*, Vol. 11, No. 2 (April 1979), pp. 223-245.

### Summary

Brueckner (1979) developed a theoretical framework connecting property value maximization by local governments to economic efficiency in public goods provision, and then tested this framework empirically. The key theoretical insight is that if a local government maximizes aggregate property values, it will provide the efficient level of public services -- because capitalization ensures that the marginal benefit of public spending is reflected in property value changes. The empirical test uses data from 54 communities in the Boston SMSA. If governments are efficient (maximizing property values), then property values should be at a maximum with respect to public expenditure, implying that the first derivative of property values with respect to spending is zero in equilibrium. Brueckner found evidence broadly consistent with this prediction, suggesting that local governments approximate efficient public goods provision.

### Identification Strategy

Cross-sectional regression using an inverted-U test. If local governments maximize aggregate property values, the relationship between property values and public expenditures should be hump-shaped, with the observed expenditure level near the peak. Brueckner estimated a quadratic specification of property values as a function of per-pupil school expenditure and tested whether the implied maximum was close to observed expenditure levels. Controls included community income, tax rate, and demographic characteristics. Like Oates, this is a cross-sectional correlational approach, not a causal design by modern standards.

### Key Data Source

Data from 54 communities in the Boston Standard Metropolitan Statistical Area (SMSA). Housing values from the 1970 Census. School expenditure data from the Massachusetts Department of Education.

### Main Result

- **Sign:** Property values follow an inverted-U relationship with public expenditures, peaking near observed expenditure levels.
- **Magnitude:** The estimated peak was close to the median observed expenditure, consistent with approximate efficiency. The results suggested that local governments in the sample were not far from the property-value-maximizing level of public spending.
- **Interpretation:** Local governments behave approximately as property value maximizers, which -- combined with full capitalization -- implies approximately efficient provision of local public goods.

### Proximity Score: 2

**Relevance to our project:** Brueckner's framework provides the theoretical link between property value maximization and efficient local public goods provision. For our paper, this creates a testable prediction: if wealthy-local mayors maximize their own property values (self-interest), do they incidentally improve public goods provision (efficiency)? Or do they distort provision away from efficiency to benefit their specific asset portfolio? This paper should be cited when discussing whether the "skin in the game" channel leads to better or worse outcomes. It also matters for the welfare analysis: if capitalization operates as Brueckner suggests, then a mayor who manipulates taxes to increase their property value might nonetheless be moving toward efficiency. This is important for interpreting our results.

---

## Paper 3: Palmon and Smith (1998)

### Full Citation

Oded Palmon and Barton A. Smith, "New Evidence on Property Tax Capitalization," *Journal of Political Economy*, Vol. 106, No. 5 (October 1998), pp. 1099-1111.

### Summary

Palmon and Smith (1998) exploited a natural experiment to provide cleaner evidence on property tax capitalization than the cross-sectional studies that preceded it. They studied housing transactions along the boundaries of school districts in Houston, Texas, where adjacent houses on the same street but in different school districts faced different property tax rates while being otherwise nearly identical in characteristics and access to amenities. By comparing homes that differ essentially only in their tax jurisdiction, the authors isolated the capitalization effect from the confounding influences (differences in neighborhood quality, public service levels, and household sorting) that plagued earlier cross-sectional studies. They found evidence of full (or very close to full) capitalization of property tax differentials into home prices.

### Identification Strategy

Boundary discontinuity design (a spatial regression discontinuity, though they did not use that terminology). Compared sale prices of homes on opposite sides of school district boundaries within the same neighborhood, same street, or same subdivision. This holds constant neighborhood amenities, location attributes, and most public services (since municipal services were the same -- only school district affiliation differed). The identifying assumption is that homes immediately on either side of the boundary are identical in all respects except their tax-service jurisdiction, so price differences reflect capitalization. This is a far more credible identification strategy than Oates (1969) or Brueckner (1979) because it eliminates cross-community sorting and amenity differences.

### Key Data Source

Houston, Texas housing transactions data. Sales of single-family homes near school district boundaries. Tax rate data from Harris County (Texas) tax records. The sample focused on areas where school district boundaries did not coincide with natural boundaries (rivers, highways) or with meaningful changes in neighborhood characteristics.

### Main Result

- **Sign:** Higher property tax rates are associated with lower home sale prices (negative capitalization).
- **Magnitude:** The estimated capitalization rate was approximately 100% -- that is, the present discounted value of the tax differential was fully reflected in the price differential between homes on opposite sides of the boundary. A $1 increase in the present value of future tax obligations was associated with approximately a $1 decrease in home price.
- **Interpretation:** Under clean identification, property tax differentials are fully capitalized, consistent with the Tiebout prediction and resolving some of the ambiguity from earlier cross-sectional studies that found varying degrees of capitalization.

### Proximity Score: 2

**Relevance to our project:** Palmon and Smith (1998) provides the strongest evidence that property tax differences are fully capitalized into property values. For our project, full capitalization implies maximum "skin in the game" for locally-wealthy mayors: a 1 Real increase in the present value of IPTU obligations reduces property values by 1 Real. This means a mayor with, say, R$1 million in local real estate has a direct, dollar-for-dollar financial interest in local IPTU rates. Full capitalization also maximizes the identification threat: post-election wealth changes fully reflect policy-induced property value changes. This paper should be cited (a) to establish the magnitude of the capitalization channel, (b) to motivate why we use pre-election rather than post-election wealth measures, and (c) to note that their boundary-discontinuity approach is methodologically related to our close-election RDD in spirit (both exploit "as-if random" assignment near a threshold). The Houston boundary design is also a useful reference for any robustness checks involving Brazilian municipality boundaries.

---

## BibTeX Entries

```bibtex
@article{Oates1969_tax_capitalization,
  author  = {Oates, Wallace E.},
  title   = {The Effects of Property Taxes and Local Public Spending on Property Values: An Empirical Study of Tax Capitalization and the {T}iebout Hypothesis},
  journal = {Journal of Political Economy},
  volume  = {77},
  number  = {6},
  pages   = {957--971},
  year    = {1969}
}

@article{Brueckner1979_property_values,
  author  = {Brueckner, Jan K.},
  title   = {Property Values, Local Public Expenditure and Economic Efficiency},
  journal = {Journal of Public Economics},
  volume  = {11},
  number  = {2},
  pages   = {223--245},
  year    = {1979}
}

@article{PalmonSmith1998_tax_capitalization,
  author  = {Palmon, Oded and Smith, Barton A.},
  title   = {New Evidence on Property Tax Capitalization},
  journal = {Journal of Political Economy},
  volume  = {106},
  number  = {5},
  pages   = {1099--1111},
  year    = {1998}
}
```

---

## How These Papers Connect to Each Other

```
Oates (1969)
  |  First empirical test: taxes capitalize into property values
  |  Limitation: cross-sectional OLS, endogeneity concerns
  |
  v
Brueckner (1979)
  |  Theoretical extension: property value max => efficient public goods
  |  Empirical test: inverted-U relationship confirmed
  |  Limitation: still cross-sectional
  |
  v
Palmon & Smith (1998)
  |  Identification improvement: boundary discontinuity design
  |  Result: full (100%) capitalization confirmed
  |  Resolution: earlier mixed results were due to identification, not economics
```

## How They Connect to Our Paper

```
TAX CAPITALIZATION LITERATURE          OUR PAPER
  Oates (1969) -----> Mechanism: WHY mayors with local wealth care about IPTU
  Brueckner (1979) -> Efficiency: Does self-interest lead to better outcomes?
  Palmon & Smith (1998) -> Magnitude: FULL capitalization => maximum incentive
                     \
                      --> Identification: Pre-election wealth needed (post is endogenous)
```

---

## Additional Capitalization Papers to Consider

The following papers are also part of the capitalization literature and may be relevant. I have not prepared full annotations, but they are worth noting:

1. **Yinger et al. (1988)** -- "Property Taxes and House Values: The Theory and Estimation of Intrajurisdictional Property Tax Capitalization" (Academic Press). Book-length treatment.
2. **Epple, Zelenitz, and Visscher (1978)** -- "A Search for Testable Implications of the Tiebout Hypothesis" (JPE). Early extension of Oates.
3. **Ross and Yinger (1999)** -- "Sorting and Voting: A Review of the Literature on Urban Public Finance" (Handbook of Regional and Urban Economics). Comprehensive survey chapter.
4. **Hilber and Mayer (2009)** -- "Why Do Households Without Children Support Local Public Schools?" (AEJ: Economic Policy). Tests capitalization as a mechanism for voting behavior.
5. **Lutz (2015)** -- "The Effect of Property Taxes on Home Values" (AEJ: Economic Policy). Modern quasi-experimental evidence from tax limit overrides in Massachusetts.

---

*Generated by Librarian agent. Phase: Discovery. Addresses Editor Issue 2 (capitalization literature absent, -3 deduction). For integration into `lit_review_annotated.md` and `references.bib`.*
