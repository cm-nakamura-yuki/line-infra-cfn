Cloudformation templates for LINE bot and LIFF app
===

## LINE bot
Webhookは、下記の3つに対応する必要があります。API GatewayとLambdaで構築します。

* HTTPS
* HTTP POST
* Validate signature using X-Line-Signature

![webhook](https://github.com/cm-nakamura-yuki/line-infra-cfn/blob/images/Webhook.png)

## LIFF app
LIFF appは、下記に対応する必要があります。CloudfrontとS3で構築します。

* HTTPS

![liff](https://github.com/cm-nakamura-yuki/line-infra-cfn/blob/images/LIFF_app.png)