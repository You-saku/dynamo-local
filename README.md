# dynamo-local

## Requirement
- install aws-cli [Doc](https://docs.aws.amazon.com/cli/latest/userguide/cli-chap-getting-started.html)

## Setup
1. git clone
2. cd dynamo-local
3. docker-compose up -d
4. ```aws dynamodb create-table --cli-input-json file://dynamodb/schema.json --endpoint-url=http://localhost:8000```
5. access http://localhost:8001
