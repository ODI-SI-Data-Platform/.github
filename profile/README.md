# Welcome to the SCDP Github Organization

We're glad you're here.

## Repository naming policy
Repositories should be named as `[TENANT_NAME|platform]-[PRODUCT]-[COMPONENT], where:
- `TENANT_NAME` is currently one of [`cdaio`, `james`, `nzcbi`] or `platform` if it's a piece of shared infrastructure 
- `PRODUCT` is the feature or product on the platform the repository contains
- `COMPONENT` is the package or microservice that supports that product, such as `iac`, `api` or `web`

All repositories should be named only using lowercase letters for compatibility with both case-sensitive and case-insensitive file systems.

In addition to naming the repository, the repo should be tagged with the `TENANT_NAME` property.