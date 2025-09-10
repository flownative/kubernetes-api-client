[![MIT license](http://img.shields.io/badge/license-MIT-brightgreen.svg)](http://opensource.org/licenses/MIT)
[![Maintenance level: Love](https://img.shields.io/badge/maintenance-%E2%99%A1%E2%99%A1%E2%99%A1-ff69b4.svg)](https://www.flownative.com/en/products/open-source.html)

# Kubernetes OpenAPI client

This package provides a client for [Kubernetes](https://kubernetes.io/). It was 
auto-generated with [Jane](https://github.com/janephp/janephp). 

## Feature coverage

This library only provides subset of the resources provided by the Kubernetes 
API. The included API paths are defined in `.jane-openapi`. If further 
resources are needed, you can adjust the configuration as needed and rebuild 
the client library.

## Rebuilding the client library

Jane provides commands for generating the client code. Switch to this 
package's directory and install Composer dependencies. You can then run a 
command for generating the code: 

```bash
composer update
bin/jane-openapi-generate
```

## Usage

The client is instantiated using the `create()` factory method. The 
following example shows how to FIXME, authenticating with 
FIXME of a Kubernetes service account: 

```php
...
```
