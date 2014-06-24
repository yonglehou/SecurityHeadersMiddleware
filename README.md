Security Headers Middleware
===========

[![Build status](https://ci.appveyor.com/api/projects/status/6n9xkyyvox9uw2up)](https://ci.appveyor.com/project/StefanOssendorf/securityheadersmiddleware)

Middlewares to set useful security-related HTTP headers in your OWIN application. (From [OWASP list](https://www.owasp.org/index.php/List_of_useful_HTTP_headers "OWASP list"))

**Already implemented**
- Strict-Transport-Security incl. options
- X-Frame-Options incl. supporting multiple origins
- X-XSS-Protection inlc. disabling (but I don't know why).
- X-Content-Type-Options

**Outstanding**
- Content-Security-Policy
- Content-Security-Policy-Report-Only

#### Using
See the tests as examples of usage:
- [Strict-Transport-Security](https://github.com/StefanOssendorf/OwinContrib.SecurityHeaders/blob/master/src/OwinContrib.SecurityHeaders.Tests/StrictTransportSecurityMiddlewareSpecs.cs)
- [X-Frame-Options](https://github.com/StefanOssendorf/OwinContrib.SecurityHeaders/blob/master/src/OwinContrib.SecurityHeaders.Tests/AntiClickJackingMiddlewareSpecs.cs)
- [X-XSS-Protection](https://github.com/StefanOssendorf/OwinContrib.SecurityHeaders/blob/master/src/OwinContrib.SecurityHeaders.Tests/XssProtectionHeaderMiddlewareSpecs.cs)
- [X-Content-Type-Options](https://github.com/StefanOssendorf/OwinContrib.SecurityHeaders/blob/master/src/OwinContrib.SecurityHeaders.Tests/ContentTypeOptionsMiddleware.cs) 

#### Developed with
[MarkdownPad 2](http://markdownpad.com/ "MarkdownPad 2")
[JetBrains ReSharper](http://www.jetbrains.com/resharper/ "R#")
