# Naming Conventions

## Repository naming policy
Repositories should be named as `[TENANT_NAME|platform]-[PRODUCT]-[COMPONENT]`, where:
- `TENANT_NAME` is currently one of [`cdaio`, `james`, `nzcbi`] or `platform` if it's a piece of shared infrastructure 
- `PRODUCT` is the feature or product on the platform the repository contains
- `COMPONENT` is the package or microservice that supports that product, such as `iac`, `api` or `web`

All repositories should be named only using lowercase letters for compatibility with both case-sensitive and case-insensitive file systems.

## Account naming policy
Accounts should be named as `[TENANT_NAME|Platform] [ENVIRONMENT] [PRODUCT] [OPTIONAL_DESCRIPTOR]`, where:
- `TENANT_NAME` is currently one of [`CDAIO`, `JAMES`, `NZCBI`] or `Platform` if it's a piece of shared infrastructure 
- `ENVIRONMENT` is currently one of [`PROD`, `UAT`, `TEST`, `SBX`]
- `PRODUCT` is the feature or product on the platform the account contains
- `OPTIONAL_DESCRIPTOR` is for helping users differentiate subparts
