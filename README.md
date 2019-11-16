Cloudformation templates for LINE bot and LIFF app
===

## LINE bot
Webhookは、下記の3つに対応する必要があります。API GatewayとLambdaで構築します。

* HTTPS
* HTTP POST
* Validate signature using X-Line-Signature

## LIFF app
LIFF appは、下記に対応する必要があります。CloudfrontとS3で構築します。

* HTTPS