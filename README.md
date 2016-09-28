# Vault CA CLI
Generate certificates in Hashicorp Vault and store to file

# Usage
vaultcacli --token xxx-xxx-xxx-xxx --url https://my.vault.server:8200 --path pki --role generate --ca ca.pem --cert cert.pem --key key.pem --name my.new.server --ttl 8760h

# Environment variables
You can set the URL and Token with environment variables:  
```
export VAULT_URL=https://my.vault.server:8200
export VAULT_TOKEN=xxx-xxx-xxx-xxx
```
