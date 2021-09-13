# API Designing, Prototyping, and Testing

This learning repo is part of [Bootcamp 2021](https://panacloud.github.io/bootcamp-2021/)

[The Future of Software Development and APIs, with Postman CTO Ankit Sobti](https://www.youtube.com/watch?v=qIgnVczcFgY)

[REST vs GraphQL](https://www.youtube.com/watch?v=eqnjWkVGvYw)

[What is GraphQL?](https://www.youtube.com/watch?v=pkqBe4SduYk)

You can follow a number of differnt workflows in developing an API.

We suggest that you should follow this workflow when designing and developing an API and a application:

1. Start by [define an API specification](https://learning.postman.com/docs/designing-and-developing-your-api/defining-an-api/) (Step 04)
2. [Generate a collection](https://learning.postman.com/docs/designing-and-developing-your-api/defining-an-api/#generating-a-collection) from it.
3. Once you have a collection, you can [create a mock server from it](https://learning.postman.com/docs/designing-and-developing-your-api/mocking-data/setting-up-mock/#creating-a-mock-from-a-collection) (step 05)
4. Your UI Application team can now start developing an UI application by using the mock server.
5. Your API developing team can now start developing the actual API implementation in the parallel to the UI application. There are many options, we recommend that you do develop serverless APIs. In case of REST implementation by using [AWS Gateway and Lambda Functions](https://github.com/panacloud-modern-global-apps/full-stack-serverless-cdk/tree/main/step01_hello_lambda) and GrpahQL using [AWS App Sync and Lambda Functions](https://github.com/panacloud-modern-global-apps/full-stack-serverless-cdk/tree/main/step03_appsync_lambda_as_datasource) using AWS CDK in TypeScript.
6. Once the API implementation and development implementation is complete you can change the URL in your UI application and test collections from the mock URL to the implementation URL.
7. During development you can run collections on the command line with [Newman](https://learning.postman.com/docs/running-collections/using-newman-cli/command-line-integration-with-newman/) and integrate it with your CI/CD e.g. [Google Actions](https://github.com/marketplace/actions/newman-cli-postman-action).

Note:

To Learn how to develop the Serverless Cloud APIs visit the [Panacloud Serverless CDK Repo](https://github.com/panacloud-modern-global-apps/full-stack-serverless-cdk)

If you want to learn to develop SaaS and UI applications using APIs visit [Bootcamp 2020](https://panacloud.github.io/bootcamp-2020/)
