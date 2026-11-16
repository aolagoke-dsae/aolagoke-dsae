# Dr. Adewole Olagoke

Data scientist with a doctorate in quantitative ecology and ecological
modelling, and over ten years of statistical modelling, machine learning,
time-series analysis and uncertainty analysis, in Python, R and SQL. I coordinated data harmonisation and quality assurance across an EU
consortium of 19 partners in 10 countries, and now build tested, documented
data products with dbt, DuckDB and Databricks.

Open to data science, analytics engineering and environmental data
roles in Germany, from January 2027.

## Projects

- [grid-carbon-intensity](https://github.com/aolagoke-dsae/grid-carbon-intensity):
  a load-shifting decision model for industrial electricity users, on ENTSO-E
  and SMARD data for Germany and France, 2021–2025. A dbt and DuckDB warehouse
  with 65 models and tests; hourly carbon intensity with a 90% Monte Carlo
  interval (Germany 2025: 352 g CO₂e/kWh, 338–399), correlating at r = 0.9995
  with the independent Fraunhofer ISE series. In build; the capstone of my
  training
- [grid-carbon-intensity-mlops](https://github.com/aolagoke-dsae/grid-carbon-intensity-mlops):
  probabilistic 24-hour forecasts of carbon intensity on Databricks. LightGBM
  quantile models with conformal calibration, run as serverless jobs with an
  MLflow promotion gate. Evaluated once on a held-out period under a plan
  fixed in advance; all three pre-registered hypotheses were falsified and are
  reported as such
- [eudr-geojson-validator](https://github.com/aolagoke-dsae/eudr-geojson-validator):
  the European Commission's GeoJSON file description for the EU Deforestation
  Regulation as executable rules, with a command-line tool and a browser demo.
  v1.3.0 on PyPI; 91 tests on Python 3.10–3.14
- [soil-carbon-kriging](https://github.com/aolagoke-dsae/soil-carbon-kriging):
  soil carbon stocks mapped with their uncertainty. Bayesian kriging at 1,163
  sites in eight US fields, whose 90% prediction intervals contain 84–91% of
  held-out values; quantile regression forests for the German Agricultural
  Soil Inventory (3,104 sites), 13% better than land use alone, with a 1 km
  map of Germany. Reviewed adversarially before release, with the headline
  results corrected where they did not hold. v1.2
- [heat-risk-hessen](https://github.com/aolagoke-dsae/heat-risk-hessen): heat,
  mortality and who lives where it is hottest in Hessen, 2000–2025. Hypotheses
  and data rules are fixed before the data; the build is planned for
  February 2027
- [eu-soil-crop-allocation](https://github.com/aolagoke-dsae/eu-soil-crop-allocation):
  which crop is grown where in EU agriculture, and what do lab-measured soil
  N, P, K and pH add beyond climate and terrain? A crop-allocation model on
  about 10,000 LUCAS 2018 points, tested against pre-registered hypotheses
  with spatial cross-validation. In progress

## Skills

Python · R · SQL · dbt · DuckDB · Databricks (Spark, MLflow) · machine
learning (scikit-learn, LightGBM, quantile regression forests) · geostatistics
and Bayesian kriging · Monte Carlo and global sensitivity analysis ·
agent-based modelling · geospatial data · Tableau · Power BI

## Contact

adewoleolagoke@gmail.com ·
[LinkedIn](https://www.linkedin.com/in/adewole-olagoke) ·
[ORCID 0000-0002-0869-329X](https://orcid.org/0000-0002-0869-329X) ·
[Tableau Public](https://public.tableau.com/app/profile/adewole.olagoke1268)
