# Fork

This is fork of apparently abandoned BeSimple/BeSimpleSoap library to make it work with Symfony 3.

# BeSimpleSoap

Build SOAP and WSDL based web services.

# Components

BeSimpleSoap consists of five components ...

## BeSimpleSoapBundle

The BeSimpleSoapBundle is a Symfony2 bundle to build WSDL and SOAP based web services.
For further information see the [README](https://github.com/dgreda/BeSimpleSoap/blob/master/src/BeSimple/SoapBundle/README.md).

## BeSimpleSoapClient

The BeSimpleSoapClient is a component that extends the native PHP SoapClient with further features like SwA, MTOM and WS-Security.
For further information see the [README](https://github.com/dgreda/BeSimpleSoap/blob/master/src/BeSimple/SoapClient/README.md).

## BeSimpleSoapCommon

The BeSimpleSoapCommon component contains functionylity shared by both the server and client implementations.
For further information see the [README](https://github.com/dgreda/BeSimpleSoap/blob/master/src/BeSimple/SoapCommon/README.md).

## BeSimpleSoapServer

The BeSimpleSoapServer is a component that extends the native PHP SoapServer with further features like SwA, MTOM and WS-Security.
For further information see the [README](https://github.com/dgreda/BeSimpleSoap/blob/master/src/BeSimple/SoapServer/README.md).

## BeSimpleSoapWsdl

For further information see the [README](https://github.com/dgreda/BeSimpleSoap/blob/master/src/BeSimple/SoapWsdl/README.md).

# Installation with composer

If you do not yet have composer, install it like this:

```sh
composer require dgreda/soap v0.3.1
```
