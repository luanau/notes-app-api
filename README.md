Might need to change the region in the serverless.yml file.
My region is eu-west-2



```
$ serverless invoke local --function create --path mocks/create-event.json

{
    "statusCode": 200,
    "headers": {
        "Access-Control-Allow-Origin": "*",
        "Access-Control-Allow-Credentials": true
    },
    "body": "{\"userId\":\"USER-SUB-1234\",\"noteId\":\"8da601f0-b126-11e7-baa3-3137f38e52de\",\"content\":\"hello world\",\"attachment\":\"hello.jpg\",\"createdAt\":1508016480143}"
}
```

