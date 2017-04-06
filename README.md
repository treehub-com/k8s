# Treehub Kubernetes Resources

For MySQL setup follow [this guide](https://cloud.google.com/sql/docs/mysql/connect-container-engine) to setup credentials

For Cloud Storage create a service account and place the credentials.json file in the secret

## Secrets

**cloudsql-oauth-credentials**

- `credentials.json`

**storage-oauth-credentials**

- `credentials.json`

**www**

- `mailgun_api_key`
- `mysql_pwd`
- `mysql_user`
- `gcloud_project_id` - Google cloud project ID used by the SDK
