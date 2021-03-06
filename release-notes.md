<!--
This file contains the in progress release notes during the cycle.
It should not be considered the final announcement for any release at any time.
-->


# v1.6.0
* Upgrade to Jackson 2.9.5
* Upgrade to Caffeine 2.6.2
* Upgrade to Netty 4.1.31.Final
* Upgrade to Snake Yaml 1.20
* `ServerConfigBuilder.registerShutdownHook(boolean)` defaults to `true`
* `HttpClient` request/response interceptors
* Expose `HttpClient` pool queue size
* `Promise.flatOp`
* `Promise.mapError(Predicate,Function)` 
* `RatpackServer.getRegistry()`
* Fix for URL paths when serving files
* Fix to not allow any empty string as the session id.
* Configure `HttpClient` for Retrofit builders
* Check for null content-type in retrofit request
* `ByteBuf` metrics in `DropwizardMetricsMetrics`
* Added rx2 Module
* Added thymeleaf3 Module
* Enhance RequestFixture with multipart form and file upload capabilities
* Added reactor module 

 
