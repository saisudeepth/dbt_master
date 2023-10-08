Welcome to my GitHub profile for the dbt-postgres project!

### Installation Steps

  - To install Python, visit: https://www.python.org/downloads/
  - To install PostgreSQL, visit: https://www.postgresql.org/download/
  - To install DBT, follow the steps outlined in the documentation: https://docs.getdbt.com/docs/core/pip-installl
      -- python3 -m venv dbt-env 
      -- dbt-env\Scripts\activate
      -- pip install dbt-postgres
  - After installing the above 3 please clone my dbt_master repository, use the command: git clone https://github.com/saisudeepth/dbt_master.git

### Checking the dbt-postgres connection

To confirm the connection, try running the following commands::
- dbt debug(assuming you have copied my profiles.yml to your %USERPROFILE%/.dbt folder and edited the file as per your postgresql configurations)

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
