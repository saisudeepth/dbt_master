Welcome to the new dbt-postgres project!

### Installation Steps

  - Python: https://www.python.org/downloads/
  - PostgreSQL: https://www.postgresql.org/download/
  - DBT: https://docs.getdbt.com/docs/core/pip-install
      -- python3 -m venv dbt-env 
      -- dbt-env\Scripts\activate
      -- pip install dbt-postgres
  - git clone https://github.com/saisudeepth/dbt_master.git

### Checking the dbt-postgres connection

Try running the following commands:
- dbt debug(assuming you have copied the profiles.yml to your %USERPROFILE%/.dbt folder and edited the file as per your postgres configuration)

### Creating the tables under the respective schema

Try running the following commands:
- dbt seed --select tag:map
- dbt seed --select tag:demart


### Resources:
- Learn more about dbt [in the docs](https://docs.getdbt.com/docs/introduction)
- Check out [Discourse](https://discourse.getdbt.com/) for commonly asked questions and answers
- Join the [chat](https://community.getdbt.com/) on Slack for live discussions and support
- Find [dbt events](https://events.getdbt.com) near you
- Check out [the blog](https://blog.getdbt.com/) for the latest news on dbt's development and best practices
