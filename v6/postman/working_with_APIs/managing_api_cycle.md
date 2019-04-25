---
title: "Managing API Cycle"
page_id: "managing_api_cycle"
warning: false
---
## Manage API Cycle 

Once you create an API in Postman, you can link it with other entities, create/import a schema, and be able to perform many other useful tasks. For instance, you will be able to link mock servers, documentation and environments to an API and even be able to version them. You will also be able to link test suites, integration tests, and contract tests to specific versions of an API.

Once you create an API, you can perform the following tasks:

* [Define an API](#define-an-api)
* [Develop an API](#develop-an-api)
* [Test an API](#test-an-api)
* [Observe an API](#observe-an-api)

### Define an API

You can outline the structure of the API and define other important elements in Postman. As a part of this, you can create or import a schema in an API. The following section describes two topics:

* [Creating a new schema](#creating-a-new-schema)
* [Importing a file](#importing-a-file)

#### Creating a new schema

To create a new schema, click 'Add Schema' and select **Create New**. The following screen opens the schema editor with default options selected:

[![api schema add](https://s3.amazonaws.com/postman-static-getpostman-com/postman-docs/API-Schema-Editor1a.png)](https://s3.amazonaws.com/postman-static-getpostman-com/postman-docs/API-Schema-Editor1a.png)

The default schema is 'Open API 3.0' and JSON the default language. To select a different schema, click the down arrow and select from the list. Since the sample schema is in Swagger 2.0 specification, click the down arrow head and select Swagger 2.0, as illustrated below: 

[![api schema add](https://s3.amazonaws.com/postman-static-getpostman-com/postman-docs/API-Schema-Editor1b.png)](https://s3.amazonaws.com/postman-static-getpostman-com/postman-docs/API-Schema-Editor1b.png)

The schema editor provides you options to beautify the content, wrap text, copy text and search. Once you're done creating your schema, click **Save**. Soon after you save the changes, the **Generate Collection** button is enabled, as illustrated below: 

[![api schema add](https://s3.amazonaws.com/postman-static-getpostman-com/postman-docs/API-Schema-Editor2.png)](https://s3.amazonaws.com/postman-static-getpostman-com/postman-docs/API-Schema-Editor2.png)

Currently, there is no option to delete the schema. 


#### Importing a file

To import an existing schema, click **Add Schema** and select *Import file*. Navigate to the location, select the file, and click open. The schema populates in the editor. You can now edit the schema and save the changes. 

Other supported schemas are:

* OpenAPI 3.0
* Swagger 2.0
* Swagger 1.0
* RAML 0.8
* RAML 1.0

Languages supported:

* JSON
* YAML
* XML

**Note:** Multi-file variants of schemas are not supported. 


### Develop an API

After adding a schema to your API, you can develop your API by linking it with mock servers, documentation and environments to specific versions of your API. This section describes the following topics:

* [Add a mock server](#add-a-mock-server)
* [Add documentation](#add-documentation)
* [Add an environment](#add-an-environment)

#### Add a mock server

You can link mock servers running on a collection to an API. In the **Develop** tab, click **Add a mock server**. The following screen opens:

[![api add mock](https://s3.amazonaws.com/postman-static-getpostman-com/postman-docs/API-AddMock1.png)](https://s3.amazonaws.com/postman-static-getpostman-com/postman-docs/API-AddMock1.png)

In the above screen, select a mock server from the list and click **Add Mock Server**. The mock server is now added to the API with the current version tag and appears as illustrated below:

[![api add mock](https://s3.amazonaws.com/postman-static-getpostman-com/postman-docs/API-AddMock1-VersionTag.png)](https://s3.amazonaws.com/postman-static-getpostman-com/postman-docs/API-AddMock1-VersionTag.png)


### Add documentation

You can link your private and public documentation on collections with an API. In the **Develop** tab, click **Add documentation**. The following screen opens:

[![api add doc](https://s3.amazonaws.com/postman-static-getpostman-com/postman-docs/API-Add-Documentation1.png)](https://s3.amazonaws.com/postman-static-getpostman-com/postman-docs/API-Add-Documentation1.png)

In the above screen, select a corresponding collection from the list whose documentation you want to link and click **Add Documentation**. The documentation is now added to the API. 


### Add an environment

You can link specific environments in your workspaces to an API. 
In the **Develop** tab, click **Add an environment**. The following screen opens:

[![api add env](https://s3.amazonaws.com/postman-static-getpostman-com/postman-docs/API-Add-Environment1.png)](https://s3.amazonaws.com/postman-static-getpostman-com/postman-docs/API-Add-Environment1.png)

In the above screen, select an environment from the list and click **Add an environment**. The environment is now added to the API.


### Test an API

You can link your test suites, integration tests, and contract tests to the API as relations under this category to specific versions of an API. This section describes the following topics:

* [Add a test suite](#add-a-test-suite)
* [Add integration tests](#add-integration-tests)
* [Add contract tests](#add-contract-tests)

#### Add a test suite

As testing is an integral part of API life cycle, Postman lets you add your test suites to an API. 

In the **Test** tab, click **Add a test suite**. The following screen opens:

[![api add test suite](https://s3.amazonaws.com/postman-static-getpostman-com/postman-docs/API-Add-Test-Suite1.png)](https://s3.amazonaws.com/postman-static-getpostman-com/postman-docs/API-Add-Test-Suite1.png)

In the above screen, select a corresponding collection from the list and click **Add Test Suite**. The test suite attached to the collection is now added to the API. 


#### Add an integration test

In the **Test** tab, click **Add integration tests**. The following screen opens:

[![api add integration test](https://s3.amazonaws.com/postman-static-getpostman-com/postman-docs/API-Add-Integration-Test1.png)](https://s3.amazonaws.com/postman-static-getpostman-com/postman-docs/API-Add-Integration-Test1.png)

In the above screen, select a corresponding collection from the list and click **Add Integration Test**. The integration test attached to the collection is now added to the API. 


#### Add a contract test

In the **Test** tab, click **Add contract tests**. The following screen opens:

[![api add contract test](https://s3.amazonaws.com/postman-static-getpostman-com/postman-docs/API-Add-Contract-Test1.png)](https://s3.amazonaws.com/postman-static-getpostman-com/postman-docs/API-Add-Contract-Test1.png)

In the above screen, select a corresponding collection from the list and click **Add Contract Test**. The contract test attached to the collection is now added to the API. 


### Observe an API

You can link your monitors running on collections in specific workspaces with an API. 

In the **Observe** tab, click **Add a monitor**. The following screen opens:

[![api add monitor](https://s3.amazonaws.com/postman-static-getpostman-com/postman-docs/API-Add-Monitor1.png)](https://s3.amazonaws.com/postman-static-getpostman-com/postman-docs/API-Add-Monitor1.png)

In the above screen, select a corresponding monitor from the list and click **Add Monitor**. The monitor attached to the collection is now linked to the API. 