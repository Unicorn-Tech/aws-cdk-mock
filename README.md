# AWS CDK Mock

This project provides the mock AWS CDK implementation used by aws-cdk-project.

It mirrors the communication API so the project can test the same handler flow against a local mock service. Examples include:

- `check-mock-handler` for the `check-handler` flow
- `initiate-mock-handler` for the `initiate-handler` flow
- `status-mock-handler` for the `status-handler` flow
- `submission-mock-handler` for the `submission-handler` flow

## Useful commands

* `npm run build`   type-check the project
* `npm run watch`   watch for changes and type-check
* `npm run test`    perform the jest unit tests
* `npx cdk deploy`  deploy this stack to your default AWS account/region
* `npx cdk diff`    compare deployed stack with current state
* `npx cdk synth`   emits the synthesized CloudFormation template
# aws-cdk-mock
