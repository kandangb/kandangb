# configuration.yml file
data_source aws_postgres_retail:
  type: snowflake
  host: soda-demo
  username: ${KREXPLEO0502}
  password: ${151200@Mpwd}
  database: KANDAN
  schema: public
# Refer to https://go.soda.io/api-keys
soda_cloud:
  host: cloud.us.soda.io
  api_key_id: ${7841a074-4625-4461-a9d8-d33445ab43df}
  api_key_secret: ${m8SGMWD-aEeGhU5Eg9OSNrHhf_Am6MqaC4MxCY9bbE4gPDEoIlFQEA }
