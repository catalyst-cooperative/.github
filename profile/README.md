[Catalyst Cooperative](https://catalyst.coop) is a data engineering and analysis
consultancy, specializing in energy system and utility financial data. Our current
focus is on the US electricity and natural gas sectors. We primarily serve
non-profit organizations, academic researchers, journalists, climate policy advocates,
public policymakers, and occasionally smaller business users.

We believe public data should be freely available and easy to use by those working in
the public interest. Whenever possible, we release our software under the [MIT
License](https://opensource.org/licenses/MIT), and our data products under the [Creative
Commons Attribution 4.0 License](https://creativecommons.org/licenses/by/4.0/)

If you're interested in [hiring us](https://catalyst.coop/hire-catalyst)
email [hello@catalyst.coop](mailto:hello@catalyst.coop). We can often make acommodations
for smaller/grassroots organizations and frequently collaborate with open source contributors.

## Contact Us :love_letter:

- For general support, questions, or other conversations about our work
  that might be of interest to others, head over to our
  [GitHub Discussions](https://github.com/orgs/catalyst-cooperative/discussions)
- If you'd like to get (very) occasional updates about our work
  [sign up for our email list](https://catalyst.coop/updates/).
- Want to schedule a time to chat with us one-on-one about our software or data? Have
  ideas for improvement, or need to get some personalized support? [Join us for Office
  Hours](https://calend.ly/catalyst-cooperative/pudl-office-hours)
- Follow us on BlueSky: [@catalyst.coop](https://bsky.app/profile/catalyst.coop)
- Connect with us [on LinkedIn](https://www.linkedin.com/company/catalyst-cooperative/)
- Follow us on Mastodon: [@CatalystCoop@mastodon.energy](https://mastodon.energy/@CatalystCoop)
- Subscribe to [our channel on YouTube](https://youtube.com/@CatalystCooperative)
- Play with our data and notebooks [on Kaggle](https://www.kaggle.com/catalystcooperative)
- Preview, filter, and download our data via web using the [PUDL Data Viewer](https://viewer.catalyst.coop/)
- Combine our data with ML models [on HuggingFace](https://huggingface.co/catalystcooperative)
- Learn more about us on our website: https://catalyst.coop

## Services We Provide

- Programmatic acquisition, cleaning, and integration of public data sources.
- Data-oriented software development.
- Compilation of new machine-readable data sources from regulatory filings, legislation, and other public information.
- Data warehousing and dashboard development.
- Both ad-hoc and replicable production data analysis.
- Translation of existing ad-hoc data wrangling workflows into replicable data pipelines written in Python.
- Reproducible data pipeline design, implementation, and ongoing maintenance.

## Tools We Use :hammer: :wrench:

- [Python](https://www.python.org/) is our primary language for everything.
- [Pandas](https://pandas.pydata.org/) the swiss army knife of tabular data manipulation in Python.
- [Dagster](https://dagster.io) for orchestrating and parallelizing our data pipelines.
- [DuckDB](https://duckdb.org/) as a performant, columnar, analysis oriented embedded database. The SQLite of analytical databases.
- [Flask](https://flask.palletsprojects.com/) for building web-apps like the [PUDL Data Viewer](https://data.catalyst.coop)
- [Pixi](https://github.com/prefix-dev/pixi), a fast, ergonomic conda package management command line tool.
- [Marimo Notebooks](https://docs.marimo.io/) for interactive dashboads and data exploration.
- [Polars Dataframes](https://docs.pola.rs/) for working with larger data tables that don't fit into memory, or are computationally intensive.
- [Apache Parquet](https://parquet.apache.org/) to persist larger data tables to disk.
- [Pydantic](https://pydantic-docs.helpmanual.io/) for managing and validating settings and our collection of metadata.
- [Pandera](https://pandera.readthedocs.io/) to specifiy dataframe schemas and data validations in conjunction with Dagster.
- [Pyodide](https://pyodide.org) to let users access and play with our data in-browser.
- [SQLite](https://www.sqlite.org/) for local storage and distribution of tabular, relational data.
- [JupyterLab](https://jupyter.org/) for interactive data wrangling, exploration, and visualizations.
- [Scikit Learn](https://scikit-learn.org/) to construct machine learning pipelines.
- [Splink](https://github.com/moj-analytical-services/splink) for fast, generalized entity matching / record linkage.
- [MLFlow](https://mlflow.org/) for ML experiment and artifact tracking, mostly in the context of our entity matching / record linkage work.
- [Google Batch](https://cloud.google.com/batch/) to minimize the infrastructure we need to manage for our nightly builds.
- [Hypothesis](https://hypothesis.readthedocs.io/) for more robust data-oriented unit testing.
- [Zenodo](https://zenodo.org/communities/catalyst-cooperative/) provides long-term, programmatically accessible, versioned archives of all our raw inputs.
- [Sphinx](https://www.sphinx-doc.org/) for building [our documentation](https://catalystcoop-pudl.readthedocs.io/), incorporating much of our structured metadata directly using Jinja templates.
- The [Frictionless Framework](https://framework.frictionlessdata.io/) as a standard interchange model for tabular data.
- [VS Code](https://code.visualstudio.com/) is our primary main code editor, ever more deeply integrated with GitHub.
- [prek](https://github.com/j178/prek) & [pre-commit](https://pre-commit.com/) to enforce code formatting and style standards.
- [GitHub Actions](https://docs.github.com/en/actions) to run our continuous integration and coordinate our nightly builds and data scraping jobs.

## Tools We're Studying :construction:

- [Agent Skills](https://agentskills.io) to give LLM-based coding agents dynamic, specialized context.
- [Zensical](https://zensical.org/) a beautiful, blazing fast static site generator written in Rust.
- [OpenSearch](https://docs.opensearch.org/docs/latest/) for processing, indexing, and programmatically managing large troves of unstructrured documents.
- [HuggingFace Hub](https://huggingface.co/docs/hub/) as another platform for distributing larger datasets and pre-trained machine-learning models specific to energy system data.

## Adjacent Projects :brain:

- [GridStatus](https://github.com/kmax12/gridstatus)
- [Interconnection.fyi](https://www.interconnection.fyi/)
- [GridEmissions](https://gridemissions.jdechalendar.su.domains/#/about)
- [PowerGenome](https://github.com/PowerGenome/PowerGenome) from [@gschivley](https://github.com/gschivley)
- [The Open Grid Emissions Initiative](https://github.com/singularity-energy/open-grid-emissions) from [@grgmiller](https://github.com/grgmiller) & [Singularity Energy](https://singularity.energy/)
- [Map Your Grid](https://mapyourgrid.org/) a project of @open-energy-transition and the @openstreetmap to crowdsource a map of the world's electricity infrastructure for use in open modeling.
  
## Organizational Friends & Allies :revolving_hearts:

- [The Open Energy Modeling Initiative](https://openmod-initiative.org/)
- [Open Energy Transition](https://openenergytransition.org/)
- [CarbonPlan](https://carbonplan.org/)
- The [Public Environmental Data Partnership](https://screening-tools.com/)
- [The Open Knowledge Foundation](https://okfn.org/)
- [2i2c: The International Interactive Computing Consortium](https://2i2c.org/)
- [The Open Energy Outlook](https://github.com/TemoaProject/oeo)
- [Code for Science & Society](https://codeforscience.org/)
- [The US Research Software Engineering Association](https://us-rse.org)
- [Diagonal Works](https://diagonal.works/)
- [The Environmental and Data Governance Initiative](https://envirodatagov.org/) (EDGI)
- [Technology Cooperatives Everywhere!](https://tech-coops.xyz/)

## Funders & Clients :moneybag: :dollar:

- [The PUDL Sustainers](https://opencollective.com/pudl)
- [The Alfred P. Sloan Foundation Energy & Environment Program](https://sloan.org/programs/research/energy-and-environment)
- [RMI](https://rmi.org/)
- [GridLab](https://gridlab.org/)
- [Climate Change AI](https://www.climatechange.ai/)
- [The Mozilla Foundation](https://foundation.mozilla.org/en/)
- [Carbon Tracker](https://carbontracker.org)
- [Climate Policy Initiative](https://www.climatepolicyinitiative.org/)
- [Energy Innovation](https://energyinnovation.org/)
- [Lawrence Berkeley Lab Energy Technologies Area](https://eta.lbl.gov/)
- [Invenia Labs](https://www.invenia.ca/)
- [Western Interstate Energy Board](https://www.westernenergyboard.org/)
- [Flora Family Foundation](https://www.florafamily.org/)
- [The Deployment Gap Education Fund](https://www.deploymentgap.fund/)

## Business & Employment :evergreen_tree: :evergreen_tree:

Catalyst is a [democratic workplace](https://institute.coop/) and a member of the [US
Federation of Worker Cooperatives](https://usworker.coop). We exist to help our members
earn a decent living while working for a more just, livable, and sustainable world. Our
income comes from a mix of grant funding and client work. We only work with
mission-aligned clients.

We are an entirely remote organization, and have been since well before the coronavirus
pandemic. Our members are scattered all across North America from Alaska to Mexico. We
enjoy a great deal of autonomy and flexibility in determining our own work-life balance
and schedules. Membership entails working a minimum of 1000 hours each year for the
co-op.

As a small 100% employee-owned cooperative, we are able to compensate members through an
unusual mix of wages and profit sharing, including:

- An hourly wage (currently $36.75/hr)
- Tax-deferred employer retirement plan contributions (proportional to wages, up to 25% of wages)
- Tax-advantaged patronage dividends (proportional to hours worked, unlimited but subject to profitability)

We also reimburse ourselves for expenses related to maintaining a home office, and
provide a monthly health insurance stipend.

Candidates must do at least 500 hours of contract work for the cooperative within over
six months, at which point they will be considered for membership.

**[Check our website to see if we're recruiting new
members](https://catalyst.coop/work-with-us/)**.
