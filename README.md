# Marketing_research

Good day, this research was made while I was studying in Yandex.

**Purpose**: 
- understand the cause of Procrastinate Pro+'s losses;
- give recommendations to correct the situation

**Stages**: 
1) data loading, EDA
2) LTV, ROI calculations
3) conclusions

**Stack**: pandas, numpy, seaborn, matplotlib, plotly, scipy, datetime

**Conclusions**:
1) It was determined that advertising does not pay off (in general, for the advertising company ROI = 0.8. The situation is better if you look separately by region or device type). It has been established that the following channels for attracting users require optimization of the advertising campaign:
    - FaceBoom (low hold);
    - AdNonSense (low retention);
    - TipTop (the most significant dynamics in the cost of attracting users, while retention is “average”, that is, a lot of money is spent, and the result for user retention is the same as that of an average channel with lower investments);
2) It has been determined that users can have a negative impact on advertising payback:
    - from the USA (low retention and most acquisition channels; stopped paying off since June, while the costs of attracting users from this region have increased sharply);
    - devices: PC and Android (lowest conversion).
3) Reasons for ineffective user acquisition:
     - possible unadapted advertising campaign for US residents/technical shortcomings;
     - an outdated advertising campaign (media personalities were involved who discredited themselves in some way in June 2019);
4) Following recommendations were given:
    - redistribute/optimize the marketing budget between channels in the United States (the least profitable channels are: TipTop, FaceBoom) and in Europe (AdNonSense);
    - perhaps it makes sense to study the “experience/model” of the lambdaMediaAds channel (the most significant LTV and LTV dynamics);
    - pay attention to the European market (AdNonSense, LeapBob, OppleCreativeMedia, WahooNetBanner, lambdaMediaAds);
    - it makes sense to take a closer look at the organic referral source (it has a high revenue level, taking into account the fact that this source is completely free);
    - check for technical errors that allow you to fully open advertising on PC and Andriod devices in the United States.
