# Go code for AWS Lambda

## 1. Download Lambda package
`go get github.com/aws/aws-lambda-go/lambda`

## 2. Build linux binary
`GOOS=linux go build main.go`

## 3. Zip up binary
`zip func.zip main`