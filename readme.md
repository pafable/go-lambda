# Go code for AWS Lambda

## 1. Download Lambda package
`go get github.com/aws/aws-lambda-go/lambda`

## 2. Build linux binary
`GOOS=linux go build main.go`

## 3. Zip up binary
`zip func.zip main`

## 4. Testing
In lambda create a test that will be passed in as a request.

```
{
    "name": "your name",
    "age": 1000
}
```