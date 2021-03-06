# Go API client for openapi

No description provided (generated by Openapi Generator https://github.com/openapitools/openapi-generator)

## Overview
This API client was generated by the [OpenAPI Generator](https://openapi-generator.tech) project.  By using the [OpenAPI-spec](https://www.openapis.org/) from a remote server, you can easily generate an API client.

- API version: 513
- Package version: 1.0.0
- Build package: org.openapitools.codegen.languages.GoClientCodegen

## Installation

Install the following dependencies:

```shell
go get github.com/stretchr/testify/assert
go get golang.org/x/oauth2
go get golang.org/x/net/context
go get github.com/antihax/optional
```

Put the package under your project folder and add the following in import:

```golang
import "./openapi"
```

## Documentation for API Endpoints

All URIs are relative to *http://localhost*

Class | Method | HTTP request | Description
------------ | ------------- | ------------- | -------------
*DefaultApi* | [**GetAccount**](docs/DefaultApi.md#getaccount) | **Get** /v0a977/reg/{sourceDeviceId}/account | GetAccount
*DefaultApi* | [**GetBoundDevices**](docs/DefaultApi.md#getbounddevices) | **Get** /v0a977/reg/{sourceDeviceId}/account/devices | GetBoundDevices
*DefaultApi* | [**GetClientConfig**](docs/DefaultApi.md#getclientconfig) | **Get** /v0a977/client_config | GetClientConfig
*DefaultApi* | [**GetSourceDevice**](docs/DefaultApi.md#getsourcedevice) | **Get** /v0a977/reg/{sourceDeviceId} | GetSourceDevice
*DefaultApi* | [**Register**](docs/DefaultApi.md#register) | **Post** /v0a977/reg | Register
*DefaultApi* | [**ResetAccountLicense**](docs/DefaultApi.md#resetaccountlicense) | **Post** /v0a977/reg/{sourceDeviceId}/account/license | ResetAccountLicense
*DefaultApi* | [**UpdateAccount**](docs/DefaultApi.md#updateaccount) | **Put** /v0a977/reg/{sourceDeviceId}/account | UpdateAccount
*DefaultApi* | [**UpdateBoundDevice**](docs/DefaultApi.md#updatebounddevice) | **Patch** /v0a977/reg/{sourceDeviceId}/account/reg/{boundDeviceId} | UpdateBoundDevice
*DefaultApi* | [**UpdateSourceDevice**](docs/DefaultApi.md#updatesourcedevice) | **Patch** /v0a977/reg/{sourceDeviceId} | UpdateSourceDevice


## Documentation For Models

 - [GetAccount200Response](docs/GetAccount200Response.md)
 - [GetBoundDevices200Response](docs/GetBoundDevices200Response.md)
 - [GetClientConfig200Response](docs/GetClientConfig200Response.md)
 - [GetClientConfig200ResponseDenylist](docs/GetClientConfig200ResponseDenylist.md)
 - [GetClientConfig200ResponseNetworks](docs/GetClientConfig200ResponseNetworks.md)
 - [GetClientConfig200ResponseNetworksV4](docs/GetClientConfig200ResponseNetworksV4.md)
 - [GetClientConfig200ResponseNetworksV6](docs/GetClientConfig200ResponseNetworksV6.md)
 - [GetSourceDevice200Response](docs/GetSourceDevice200Response.md)
 - [GetSourceDevice200ResponseAccount](docs/GetSourceDevice200ResponseAccount.md)
 - [GetSourceDevice200ResponseConfig](docs/GetSourceDevice200ResponseConfig.md)
 - [GetSourceDevice200ResponseConfigEndpoint](docs/GetSourceDevice200ResponseConfigEndpoint.md)
 - [GetSourceDevice200ResponseConfigInterface](docs/GetSourceDevice200ResponseConfigInterface.md)
 - [GetSourceDevice200ResponseConfigInterfaceAddresses](docs/GetSourceDevice200ResponseConfigInterfaceAddresses.md)
 - [GetSourceDevice200ResponseConfigPeers](docs/GetSourceDevice200ResponseConfigPeers.md)
 - [GetSourceDevice200ResponseConfigServices](docs/GetSourceDevice200ResponseConfigServices.md)
 - [Register200Response](docs/Register200Response.md)
 - [Register200ResponseAccount](docs/Register200ResponseAccount.md)
 - [RegisterRequest](docs/RegisterRequest.md)
 - [ResetAccountLicense200Response](docs/ResetAccountLicense200Response.md)
 - [UpdateAccount200Response](docs/UpdateAccount200Response.md)
 - [UpdateAccountRequest](docs/UpdateAccountRequest.md)
 - [UpdateBoundDevice200Response](docs/UpdateBoundDevice200Response.md)
 - [UpdateBoundDeviceRequest](docs/UpdateBoundDeviceRequest.md)
 - [UpdateSourceDevice200Response](docs/UpdateSourceDevice200Response.md)
 - [UpdateSourceDeviceRequest](docs/UpdateSourceDeviceRequest.md)


## Documentation For Authorization

 Endpoints do not require authorization.



## Author



