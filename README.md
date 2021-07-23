# ESMT-Thesis

This repository is created for the Master's Thesis requirement at ESMT Berlin.

The following research questions are examined:

1. **Does the overabundance of information via digital technology today affect consumer eWOM sentiment?**

2. **Does information overload increase polarization among consumers?**


Specifically, the research intends to study the correlation between different volumes of information input and user extreme sentiment. The following hypotheses will be tested:

**H1A: A high quantity of prior news articles published on a specific keyword is expected to render the current sentiment of eWOM on that keyword more positive.**

**H1B: A high quantity of prior news articles published on a specific keyword is expected to render the current sentiment of eWOM on that keyword more negative.**

**H1C: A high quantity of prior news articles published on a specific keyword is expected to render the current polarity of eWOM on that keyword higher.**

**H2A: A higher volume of prior eWOM is expected to render the sentiment of current eWOM on that keyword more positive.**

**H2B: A higher volume of prior eWOM is expected to render the sentiment of current eWOM on that keyword more negative.**

**H2C: A higher volume of prior eWOM is expected to render the polarity of current eWOM on that keyword stronger.**


The testing of the two sets of hypotheses requires the examination of two factors: the level of information load and the level of eWOM polarity. For **H1A**, **H1B**, and **H1C**, information overload is measured by the total count of articles on a topic (AL1 & AL2) as the independent variable. For **H2A**, **H2B**, and **H2C**, information overload is measured by the total count of tweets on a topic (TL1 & TL2) as the independent variable. For both sets of hypotheses, eWOM polarity is measured by tweet polarity (POL), tweet positivity (POS), and tweet negativity (NEG) as the dependent variable. Both types of independent variables are measured via two separate time lags: on the day preceding the dependent tweet and on the day of the dependent tweet. To account for geographic influences on tweet sentiment, confounding variables are added in the form of dummy values: the number 1 is assigned to one of the regions West (W), Midwest (MW), or Northeast (NE), or absent in all three variables, which indicates the Southern region. For a description of the research variables, see **Table 1**.

**Table 1:            Summary of research variables**

| Variable | Name                   | Category    | Measurement                                              |
|----------|------------------------|-------------|----------------------------------------------------------|
| POL      | Tweet polarity         | Dependent   | Continuous values between 0 (negative) and 1 (positive)  |
| POS      | Tweet positivity       | Dependent   | Continuous values between 0 (low) and 1 (high)           |
| NEG      | Tweet negativity       | Dependent   | Continuous values between 0 (low) and 1 (high)           |
| AL1      | Article count (Lag 1)  | Independent | Count of total articles on day preceding measured tweets |
| AL2      | Article count (Lag 2)  | Independent | Count of total articles during day of measured tweets    |
| TL1      | Tweet count (Lag 1)    | Independent | Count of total tweets on day preceding measured tweets   |
| TL2      | Tweet count (Lag 2)    | Independent | Count of total tweets during day of measured tweets      |
| W        | West region            | Confounding | Dummy value (0 = false, 1 = true)                        |
| MW       | Midwest region         | Confounding | Dummy value (0 = false, 1 = true)                        |
| NE       | Northeast region       | Confounding | Dummy value (0 = false, 1 = true)                        