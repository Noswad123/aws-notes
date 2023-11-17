## AWS Lambda
- run code without provisioning or managing servers.

```
https://<url-id>.lambda-url.<region>.on.aws
```

```
curl -v 'https://abcdefg.lambda-url.us-east-1.on.aws/?message=HelloWorld' \ -H 'content-type: application/json' \ -d '{ "example": "test" }'
```


arn:aws:lambda:us-east-2:636157384170:function:test_function:1


curl -v  'https://ozihblak6xmjmm4dl2nukn4nb40tsdne.lambda-url.us-east-2.on.aws/' \ -H 'content-type: application/json' \ -d '{ "example": "test" }'