# gcp_secrets

An Ansible role to:
- Install the Google Cloud SDK (if not already installed)
- Authenticate a service account
- Fetch secrets from GCP Secret Manager
- Store secrets as Ansible facts in `secrets_dict`
