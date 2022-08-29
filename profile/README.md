[Catalyst Cooperative](https://catalyst.coop) is a data engineering and analysis
consultancy, specializing in energy system and utility financial data. Our current
focus is on the US electricity and natural gas sectors. We primarily serve 
non-profit organizations, academic researchers, journalists, climate policy advocates,
public policymakers, and occasionally smaller business users.

We believe public data should be freely available and easy to use by those working in
the public interest.  Whenever possible, we release our software under the [MIT
License](https://opensource.org/licenses/MIT), and our data products under the [Creative
Commons Attribution 4.0 License](https://creativecommons.org/licenses/by/4.0/)

If you're interested in [hiring us](https://catalyst.coop/hire-catalyst)
Email [hello@catalyst.coop](mailto:hello@catalyst.coop). Our current rate is
**$150/hr**. We can often make acommodations for smaller/grassroots organizations and
frequently collaborate with open source contributors.

## Contact Us :love_letter:
* For general support, questions, or other conversations about our work
  that might be of interest to others, head over to our
  [GitHub Discussions](https://github.com/orgs/catalyst-cooperative/discussions)
* If you'd like to get (very) occasional updates about our work
  [sign up for our email list](https://catalyst.coop/updates/).
* Want to schedule a time to chat with us one-on-one about our software or data? Have
  ideas for improvement, or need to get some personalized support? [Join us for Office
  Hours](https://calend.ly/catalyst-cooperative/pudl-office-hours)
* Follow us on Twitter: [@CatalystCoop](https://twitter.com/CatalystCoop)
* More info on our website: https://catalyst.coop

## Services
* Programmatic acquisition, cleaning, and integration of public data sources.
* Data oriented software development.
* Compilation of new machine-readable data sources from regulatory filings, legislation,
  and other public information.
* Data warehousing and dashboard development.
* Both ad-hoc and replicable production data analysis.
* Translation of existing ad-hoc data wrangling workflows into replicable data pipelines
  written in Python.

## Tools we use :hammer: :wrench:
* [Python](https://www.python.org/) is our primary language for everything.
* [Pandas](https://pandas.pydata.org/) the swiss army knife of tabular data manipulation
  in Python.
* [Dask](https://www.dask.org/) to scale up data wrangling tasks we do with Pandas
  beyond what can be done in memory.
* [Dagster](https://dagster.io) for orchestrating and parellelizing our data pipelines.
* [SQLite](https://www.sqlite.org/) for local storage and distribution of 
* [Apache Parquet](https://parquet.apache.org/) to persist larger data tables to disk.
* [JupyterLab](https://jupyter.org/) for interactive data wrangling, exploration, and
  visualizations.
* [Pydantic](https://pydantic-docs.helpmanual.io/) for managing and validating settings
  and our collection of metadata.
* [Scikit Learn](https://scikit-learn.org/) for entity matching between datasets and
  imputation of missing of missing data.
* [Intake Data Catalogs](https://github.com/intake/intake) allows users to install our
  versioned data products like software, with their own data and software dependencies.
* [Google BigQuery](https://cloud.google.com/bigquery) to warehouse finished data
  products for live access.
* [Zenodo](https://zenodo.org/communities/catalyst-cooperative/) provides long-term,
  programmatically accessible, versioned archives of all our raw inputs.
* [Sphinx](https://www.sphinx-doc.org/) for building [our
  documentation](https://catalystcoop-pudl.readthedocs.io/en/latest/), incorporating
  much of our structured metadata directly using Jinja templates.
* [Tox](https://tox.wiki/) and [pytest](https://docs.pytest.org) manage our testing
  environment and define our unit, integration, and data validation tests.
* The [Frictionless Framework](https://framework.frictionlessdata.io/) as a standard
  interchange model for tabular data.
* [Tableau](https://www.tableau.com/) for producing dashboards and interactive data
  visualizations for client projects.
* [VS Code](https://code.visualstudio.com/) our primary main code editor, ever more
  deeply integrated with GitHub.
* [pre-commit](https://pre-commit.com/) to enforce code formatting and style standards.
* [GitHub Actions](https://docs.github.com/en/actions) runs our continuous integration,
  and coordinates our nightly builds and data scraping jobs.

## Tools we're studying :construction:
* [duckdb](https://duckdb.org/) as a performant, columnar, analysis oriented alternative
  to SQLite.
* [dbt](https://www.getdbt.com/) to manage pure SQL data transformations where
  appropriate within our larger Python based workflows.
* [Pandera](https://pandera.readthedocs.io/) to specifiy dataframe schemas and data
  validations in conjunction with Dagster.
* [Hypothesis](https://hypothesis.readthedocs.io/) for more robust data-oriented unit
  testing.
* [Apache Superset](https://superset.apache.org/) as an open source alternative to
  Tableau.
* [SQLModel](https://sqlmodel.tiangolo.com/) to more easily unify our metadata and
  database schema definitions with [SQLAlchemy](https://www.sqlalchemy.org/).

## Research Collaborators :brain:
* @gschivley and the [PowerGenome](https://github.com/PowerGenome/PowerGenome) project.
* @grgmiller at UC Davis through the EPA's [EmPOWER Air Data Challenge](https://www.epa.gov/airmarkets/empower-air-data-challenge).
* @raininthesun and the [Chu Data Lab](https://chu-data-lab.cc.gatech.edu/) at Georgia Tech.
* [DSIRE at North Carolina State University](https://www.dsireusa.org/)

## Some of our organizational friends :revolving_hearts:

* [The Environmental and Data Governance Initiative](https://envirodatagov.org/) (EDGI)
* [CarbonPlan](https://carbonplan.org/)
* [Diagonal Works](https://diagonal.works/)
* [The Open Knowledge Foundation](https://okfn.org/)
* [2i2c: The International Interactive Computing Consortium](https://2i2c.org/)
* [The Open Collective Foundation](https://opencollective.foundation/)
* [GridLab](https://gridlab.org/)
* [Energy Innovation, LLC](https://energyinnovation.org/)
* [The Open Energy Modeling Initiative](https://openmod-initiative.org/)
* [The Open Energy Outlook](https://github.com/TemoaProject/oeo)
* [Code for Science & Society](https://codeforscience.org/)
* [The Fiqus Cooperative](https://github.com/fiqus)

## Current & Past Funders and Clients :moneybag: :dollar:

* [The Alfred P. Sloan Foundation Energy & Environment Program](https://sloan.org/programs/research/energy-and-environment)
* [Climate Change AI](https://www.climatechange.ai/)
* [Flora Family Foundation](https://www.florafamily.org/)
* [RMI](https://rmi.org/)
* [Invenia Labs](https://www.invenia.ca/)
* [Western Interstate Energy Board](https://www.westernenergyboard.org/)

## Business and Employment :evergreen_tree: :evergreen_tree:

Catalyst is a [democratically goverened worker cooperative](https://institute.coop/) and
a member of the [US Federation of Worker Cooperatives](https://usworker.coop).
We exist to help our members earn a decent living while working for a more just,
livable, and sustainable world. Members have a high degree of autonomy and flexibility
to determine their own work-life balance. Catalyst is an entirely remote organization,
with members scattered across North America from Alaska to Mexico. Our income comes
from a mix of grant funding and client work.

Members are compensated through:

* An hourly wage
* Employer contributions to our retirement plan (proportional to annual wages)
* Annual patronage dividends (proportional to hours worked)

We also reimburse members for expenses related to maintaining their home office, and
provide a monthly health insurance stipend.

Candidates must do at least 500 hours of contract work for the cooperative over
six months prior to being considered for membership.

[Check if we're recruiting new members](https://catalyst.coop/work-with-us/).
