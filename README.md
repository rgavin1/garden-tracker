## DynamoDB Local

#### How to install


#### How to create a table
#### How to view tables in dynamodb-local
 In the terminal paste this command: 
```bash
aws dynamodb list-tables --endpoint-url http://localhost:8000 --output json
```

Note: Please use the `--output json`, if you to chance this you're going to get a error `Unknown output type: aws-ecr` which means you're output is incorrect. 

<br />
Output: 

```json
{
    "TableNames": [
        "demo-customer-info"
    ]
}
```