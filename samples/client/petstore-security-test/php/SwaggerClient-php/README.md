# SwaggerClient-php
This spec is mainly for testing Petstore server and contains fake endpoints, models. Please do not use this for any other purpose. Special characters: \" \\   ' \" =end

This PHP package is automatically generated by the [Swagger Codegen](https://github.com/swagger-api/swagger-codegen) project:

- API version: 1.0.0  &#39; \&quot; &#x3D;end
- Build date: 2016-06-30T07:09:53.488+02:00
- Build package: class io.swagger.codegen.languages.PhpClientCodegen

## Requirements

PHP 5.4.0 and later

## Installation & Usage
### Composer

To install the bindings via [Composer](http://getcomposer.org/), add the following to `composer.json`:

```
{
  "repositories": [
    {
      "type": "git",
      "url": "https://github.com/GIT_USER_ID/GIT_REPO_ID.git"
    }
  ],
  "require": {
    "GIT_USER_ID/GIT_REPO_ID": "*@dev"
  }
}
```

Then run `composer install`

### Manual Installation

Download the files and include `autoload.php`:

```php
    require_once('/path/to/SwaggerClient-php/autoload.php');
```

## Tests

To run the unit tests:

```
composer install
./vendor/bin/phpunit lib/Tests
```

## Getting Started

Please follow the [installation procedure](#installation--usage) and then run the following:

```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');

$api_instance = new Swagger\Client\Api\FakeApi();
$test_code_inject____end = "test_code_inject____end_example"; // string | To test code injection  ' \" =end

try {
    $api_instance->testCodeInjectEnd($test_code_inject____end);
} catch (Exception $e) {
    echo 'Exception when calling FakeApi->testCodeInjectEnd: ', $e->getMessage(), PHP_EOL;
}

?>
```

## Documentation for API Endpoints

All URIs are relative to *https://petstore.swagger.io  &#39; \&quot; &#x3D;end/v2  &#39; \&quot; &#x3D;end*

Class | Method | HTTP request | Description
------------ | ------------- | ------------- | -------------
*FakeApi* | [**testCodeInjectEnd**](docs/Api/FakeApi.md#testcodeinjectend) | **PUT** /fake | To test code injection  &#39; \&quot; &#x3D;end


## Documentation For Models

 - [ModelReturn](docs/Model/ModelReturn.md)


## Documentation For Authorization


## petstore_auth

- **Type**: OAuth
- **Flow**: implicit
- **Authorization URL**: http://petstore.swagger.io/api/oauth/dialog
- **Scopes**: 
 - **write:pets**: modify pets in your account  */ ' " =end
 - **read:pets**: read your pets  */ ' " =end

## api_key

- **Type**: API key
- **API key parameter name**: api_key  */ ' " =end
- **Location**: HTTP header


## Author

apiteam@swagger.io  &#39; \&quot; &#x3D;end


