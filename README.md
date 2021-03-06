# JIRA-to-Database Import

![Python](https://img.shields.io/badge/Python-3.7.2-blue.svg?logo=python&longCache=true&logoColor=white&colorB=23a8e2&style=flat-square&colorA=36363e)
![Pandas](https://img.shields.io/badge/Pandas-0.23.0-blue.svg?logo=python&longCache=true&logoColor=white&colorB=23a8e2&style=flat-square&colorA=36363e)
![SQLAlchemy](https://img.shields.io/badge/SQLAlchemy-1.3.1-red.svg?longCache=true&style=flat-square&logo=scala&logoColor=white&colorA=36363e)
![psycopg2](https://img.shields.io/badge/psycopg2-2.7.7-red.svg?longCache=true&logo=delicious&longCache=true&style=flat-square&logoColor=white&colorA=36363e)
![Requests](https://img.shields.io/badge/Requests-2.21.0-red.svg?longCache=true&logo=delicious&longCache=true&style=flat-square&logoColor=white&colorA=36363e)
![GitHub Last Commit](https://img.shields.io/github/last-commit/google/skia.svg?style=flat-square&colorA=36363e)
[![GitHub Issues](https://img.shields.io/github/issues/toddbirchard/jira-database-etl.svg?style=flat-square&colorA=36363e)](https://github.com/toddbirchard/jira-database-etl/issues)
[![GitHub Stars](https://img.shields.io/github/stars/toddbirchard/jira-database-etl.svg?style=flat-square&colorB=e3bb18&colorA=36363e)](https://github.com/toddbirchard/jira-database-etl/stargazers)
[![GitHub Forks](https://img.shields.io/github/forks/toddbirchard/jira-database-etl.svg?style=flat-square&colorA=36363e)](https://github.com/toddbirchard/sjira-database-etl/network)
![Serverless JIRA](https://github.com/toddbirchard/jira-database-etl/blob/master/assets/jira-serverless-import.jpg)

Python script triggered by a nightly CRON job. Extracts issues from a JIRA instance via the JIRA REST API, transforms the data, and uploads said data to a database. Useful for creating widgets such as public-facing Kanban boards, or doing analysis.
