# serverless-sample

## Project setup

```
npm install
```

## Deploy

```
serverless deploy -v
```

## Curl

```
curl -X POST -kv https://XXXXXXXXX.execute-api.ap-northeast-1.amazonaws.com/dev/clients -d "{\"body\": {\"name\":\"neko\",\"redirectUri\":\"https://example.com\"}}"
curl -kv https://XXXXXXXXX.execute-api.ap-northeast-1.amazonaws.com/dev/clients/YYYYYYYYYYYYYYYYYYYYYYYYYYYY
```

## Remove resources

```
serverless remove -v
```
