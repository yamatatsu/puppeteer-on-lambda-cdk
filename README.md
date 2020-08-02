# puppeteer on lambda cdk

## Preparation

You can use `aws` command.

## Usage

```sh
yarn

push packages/bot/
yarn build
popd

push packages/bot/
yarn deploy

# And you can see lambdaFunctionName as
# Outputs:
# BotStack.lambdaFunctionName = BotStack-XXXXXX

aws lambda invoke --function-name {Your lambdaFunctionName} /dev/stdout
```
