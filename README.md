# Demo on DBT Core + Snowflake

This demo was created to familiarize with the DBT Core command line tool and the Snowflake platform with the aim of
developing templates, macros, tests and documentation, including using the Jinga templating language and the dbt-utils
library.

The database used is made available on Snowflake (Snowsight), after registering an account.

Dataset documentation: https://docs.snowflake.com/en/user-guide/sample-data-tpch

## Setup
* Clone the repository
* Create a [Trial Account](https://signup.snowflake.com/) in Snowflake
* [Setup](https://docs.getdbt.com/docs/core/connect-data-platform/snowflake-setup) the connection with the data platform
  with the method you prefer
* `dbt deps` to install packages specified in `packages.yml`

## Usage

Try running the following commands:
- `dbt run`
- `dbt test`
- `dbt build`
- `dbt build --select <model_name>`
- `dbt docs generate`