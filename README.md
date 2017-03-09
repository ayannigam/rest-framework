# rest-framework
A simple REST testing framework developed using Java and Selenium

There are three classes for the framework (in packagecom.axatrikx.controller)

RestExecutor : Performs the HTTP operations using Apache Http Client
RestResponse : A javabean class to hold our response values (code, message, headers, body)
RestValidator : Validates the response with the expected values

The package com.axatrikx.test holds the test scripts.


