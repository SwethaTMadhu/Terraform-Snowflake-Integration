# Task Description:

# As part of this task, you are to create a series of Terraform scripts/modules that will provision the following Snowflake resources:
1. Warehouse: A compute warehouse suitable for processing queries and data manipulation tasks.
2. Database: A dedicated database to house various schemas and tables.
3. Schema: Within the database, create a specific schema intended for the tables.
4. Table: A table within the schema that includes at least four columns of varying data types.
5. Role: A role with permissions that allow for database, schema, and warehouse access, and select privileges on the table.

# Prerequisites
Terraform Installation
https://developer.hashicorp.com/terraform/install
Snowflake Account creation
https://signup.snowflake.com/

# To use this  code
1. CLone this repository
2. Find your Snowflake details in your mail from snowflake received while account creation
3. Modify ```terraform.tfvars``` file accordingly.

# Commands to perform
1. terraform init
2. terraform plan
3. terraform applpy

