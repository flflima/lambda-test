# Lambda-test

## Running localstack

```shell
docker compose up
```

## Running terraform

```shell
terraform init
terraform plan
terraform apply --auto-approve
```

### Output

```shell
Changes to Outputs:
  + main_url = "http://localhost:4566/restapis/{gateway_id}/{gateway_stage_name}/_user_request_/{path_part}"
```
