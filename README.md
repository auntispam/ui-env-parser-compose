# How to use
- Please check [this blog for the instructions](https://medium.com/absoroute-io/passing-dynamic-environment-variables-to-vuejs-application-at-run-time-45918162bbaf?sk=1b00248c6867778867a3d5a3c883ef30).
- Usually, you will need to modifiy "docker-compose.yml" to add your static ENV variables into "ui-env-parser" service.
- For the dynamic variables, add them into ".env" file and parse to "docker-compose.yml" by using ${VAR_NAME}