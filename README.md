# Terraform Tutorial

Project source code for Level ups Terraform Tutorial.

Check out the full list of DevOps and Big Data courses.

https://www.level-up.one/courses/

## Supplying database credentials

The RDS examples read the database master password from the sensitive `db_password` input. Supply it at plan/apply time with `TF_VAR_db_password` from a secret manager or your local environment. Do not commit `.tfvars` files or password values.
