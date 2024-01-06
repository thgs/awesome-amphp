# awesome-amphp

A curated list of [amphp](https://amphp.org/) packages.


## Anti-virus

- [Pato05/amphp-clamav](https://github.com/Pato05/amphp-clamav) - A ClamAV wrapper
- [PeeHaa/async-virus-scan](https://github.com/PeeHaa/async-virus-scan) -  Async library for querying online virus scanners


## Arduino

- [kelunik/amphp-arduino](https://github.com/kelunik/amphp-arduino) - Demo for controlling an Arduino with PHP


## Bots

- [PeeHaa/async-chatter-bot](https://github.com/PeeHaa/async-chatter-bot) - It's like regular chatter-bot, only async.
- [naftali100/async_tgbot](https://github.com/naftali100/async_tgbot) - async telegram bot library based on amphp
- [Room-11/jeeves](https://github.com/Room-11/Jeeves) - Chatbot for Stack Overflow
- [danog/MadelineProto](https://github.com/danog/MadelineProto) - Client/Server API for the telegram MTProto protocol
- [kelunik/mellon](https://github.com/kelunik/mellon) - Mellon is a bot based on Amp


## Cache

- [amphp/cache](https://github.com/amphp/cache) - A fiber-aware cache API
- [HarmonyIO/cache](https://github.com/HarmonyIO/Cache) - Async caching library


## CSV

- [webgriffe/amp-csv](https://github.com/webgriffe/amp-csv) - CSV library to use with Amp PHP framework


## Database

- [amphp/mysql](https://github.com/amphp/mysql) - Async MySQL client
- [amphp/mysql-dbal](https://github.com/amphp/mysql-dbal) - Doctrine MySQL driver
- [amphp/postgres](https://github.com/amphp/postgres) - Async Postgres client
- [amp-sqlite](https://github.com/vajexal/amp-sqlite) - SQLite client
- [spacetab-io/rdb-php](https://github.com/spacetab-io/rdb-php) - Dead-simple async PHP migrations controlled from code
- [dbalabka/doctrine-mysql-fiber-driver](https://github.com/dbalabka/doctrine-mysql-fiber-driver) - Doctrine MySQL driver with Fiber support based on Amphp 


## Dependency Injection

- [amphp/injector](https://github.com/amphp/injector) - A recursive dependency injector used to bootstrap and wire together S.O.L.I.D., object-oriented PHP applications
- [tncrazvan/catpaw-core](https://github.com/tncrazvan/catpaw-core) - An opinionated dependency injection library for AMPHP


## Docker

- [spacetab-io/docker-amphp-php](https://github.com/spacetab-io/docker-amphp-php) - Docker image configured for amphp in production use
- [caseycs/php-alpine-event](https://github.com/caseycs/php-alpine-event) -  Minimalistic (60Mb!) docker image based on php:7.1-cli-alpine with event extension 


## DNS

- [amphp/dns](https://github.com/amphp/dns) - Async DNS resolution
- [danog/dns-over-https](https://github.com/danog/dns-over-https) - Async DNS-over-HTTPS resolution


## ElasticSearch

- [webgriffe/amp-elasticsearch](https://github.com/webgriffe/amp-elasticsearch) - A non-blocking ElasticSearch client


## Enterprise Service Bus

- [webgriffe/esb](https://github.com/webgriffe/esb) - Simple, beanstalkd powered, ESB framework


## Events

- [labrador-kennel/async-event](https://github.com/labrador-kennel/async-event) -  Triggering semantic application events within Amp's Event Loop
- [prooph/event-store-client](https://github.com/prooph/event-store-client) - Event Store Client 
- [prooph/micro](https://github.com/prooph/micro) - Functional prooph for microservices


## Event loop

- [async-interop/event-loop](https://github.com/async-interop/event-loop) - An event loop interface for interoperability in PHP.
- [danog/loop](https://github.com/danog/loop) - Loop abstraction for AMPHP
- [kelunik/loop-block](https://github.com/kelunik/loop-block) - Detect blocking ticks in event loops
- [revoltphp/event-loop](https://github.com/revoltphp/event-loop) - Revolt is a rock-solid event loop for concurrent PHP applications


## Examples / Demos

- [n1215/grpc-web-chat](https://github.com/n1215/grpc-web-chat) - A simple chat application example using gRPC-Web. Including a PHP gRPC Server Streaming implementation with Amp.
- [kelunik/demo-chat](https://github.com/kelunik/demo-chat) - A small demo chat based on Aerys.
- [kelunik/rpc-demo](https://github.com/kelunik/rpc-demo) - Simple RPC demo to handle socket input in worker processes.


## Filesystem

- [amphp/file](https://github.com/amphp/file) - Access to the filesystem
- [phpactor/amp-fswatch](https://github.com/phpactor/amp-fswatch) - Filesystem watcher supporting multiple strategies


## Framework

- [labrador-kennel/http](https://github.com/labrador-kennel/http) - An HTTP microframework written on top of Labrador.


## HTTP


### Client


- [amphp/http-client](https://github.com/amphp/http-client) - Async HTTP/1.1+2 client
- [amphp/http-client-cookies](https://github.com/amphp/http-client-cookies) - Automatic cookie handling for amphp/http-client
- [amphp/http-client-cache](https://github.com/amphp/http-client-cache) - Async HTTP cache for amphp/http-client
- [amphp/http-client-psr7](https://github.com/amphp/http-client-psr7) - PSR-7 adapter for amphp/http-client
- [noerosell/awsyncronic](https://github.com/noerosell/awsyncronic) -  amphp/artax client http handler for Guzzle.
- [HarmonyIO/http-client](https://github.com/HarmonyIO/Http-Client) - Async caching aware http client


### Proxy

- [xtrime-ru/http-proxy](https://github.com/xtrime-ru/http-proxy) - Forward http proxy server built with async amphp framework. 


### Routing

- [amphp/http-server-router](https://github.com/amphp/http-server-router) - A router
- [mnavarrocarter/amp-http-router](https://github.com/mnavarrocarter/amp-http-router) - An asynchronous HTTP routing engine for Amp based applications


### Server

- [amphp/http-server](https://github.com/amphp/http-server) - A non-blocking HTTP application server. 
- [amphp/http-server-form-parser](https://github.com/http-server-form-parser) - A form parser
- [amphp/http-server-session](https://github.com/amphp/http-server-session) - Session management 
- [amphp/http-server-static-content](https://github.com/amphp/http-server-static-content) - A static content responder for amphp/http-server
- [labrador-kennel/http-cors](https://github.com/labrador-kennel/http-cors) - Middleware for amphp/http-server to handle CORS requests


### Tunnel

- [amphp/http-tunnel](https://github.com/amphp/http-tunnel) - Provides an HTTP CONNECT tunnel


## IRC

- [PeeHaa/async-irc-server](https://github.com/PeeHaa/async-irc-server) - An IRC server written using amphp components


## Importing

- [ScriptFUSION/Porter](https://github.com/ScriptFUSION/Porter) - calable and durable all-purpose data import abstraction for publishing testable APIs and SDKs.


## Jira

- [spacetab-io/jira-tempo-sdk-php](https://github.com/spacetab-io/jira-tempo-sdk-php) - Asynchronous PHP Jira Tempo SDK
- [spacetab-io/jira-sdk-php](https://github.com/spacetab-io/jira-sdk-php) - Asynchronous PHP Jira SDK


## Kafka

- [weiboad/kafka-php](https://github.com/weiboad/kafka-php) - Kafka client


## Logging

- [amphp/log](https://github.com/amphp/log) - Non-blocking logging for PHP based on Amp and Monolog
- [spacetab-io/logger-php](https://github.com/spacetab-io/logger-php) -  Simple pre-configured non-blocking logging based on Amp and Monolog


## Magento

- [webgriffe/amp-magento](https://github.com/webgriffe/amp-magento) - Magento REST Api wrapper


## Multiprocessing

- [amphp/process](https://github.com/amphp/process) - Async process dispatcher
- [amphp/parallel](https://github.com/amphp/parallel) - Parallel processing
- [amphp/parallel-functions](https://github.com/amphp/parallel-functions) - Simplified parallel processing
- [amphp/cluster](https://github.com/amphp/cluster) - Building multi-core network applications
- [danog/ipc](https://github.com/danog/ipc) - Async IPC component


## Synchronisation

- [amphp/sync](https://github.com/amphp/sync) - Mutex, Semaphore, Parcel, Channel implementations
- [php-service-bus/mutex](https://github.com/php-service-bus/mutex) - PHP Mutex implementation
- [DaveRandom/Mutex](https://github.com/DaveRandom/Mutex) - Basic common mutex framework for amp


## Music

- [ekinhbayar/gitamp](https://github.com/ekinhbayar/gitamp) - Listen to music generated by events across github


## OAuth

- [kelunik/oauth](https://github.com/kelunik/oauth) - Async OAuth client
- [kelunik/oauth-cli](https://github.com/kelunik/oauth-cli) - A small wrapper around kelunik/oauth to make OAuth for CLI applications simple.


## PDF

- [spacetab-io/wkhtmltopdf-php](https://github.com/spacetab-io/wkhtmltopdf-php) - Non-blocking PHP wrapper for wkhtmltopdf

## QUIC

- [amphp/quic](https://github.com/amphp/quic) - An implementation of QUIC using FFI and [Quiche](https://github.com/cloudflare/quiche)


## Redis

- [amphp/redis](https://github.com/amphp/redis) - Redis Client
- [charlesportwoodii/rpq-server](https://github.com/charlesportwoodii/rpq-server) - RPQ: Simple, efficient, prioritized background processing for PHP
- [kelunik/redis-mutex](https://github.com/kelunik/redis-mutex) - Mutex implementation using Redis.


## Retrying

- [kelunik/retry](https://github.com/kelunik/retry) - A tiny library for retrying failed operations
- [ScriptFUSION/retry](https://github.com/ScriptFUSION/Retry) - Retries failing operations.


## RPC

- [kelunik/rpc-demo](https://github.com/kelunik/rpc-demo) - Simple RPC demo to handle socket input in worker processes


## Pipeline

- [amphp/pipeline](https://packagist.org/packages/amphp/pipeline) - Asynchronous iterators and operators


## Socket

- [amphp/socket](https://github.com/amphp/socket) - Non-blocking socket and TLS functionality


## SMTP

- [HarmonyIO/smtp-client](https://github.com/HarmonyIO/Smtp-Client) - Async SMTP client


## SSH

- [amphp/ssh](https://github.com/amphp/ssh) - Async SSH client


## Streams

- [amphp/byte-stream](https://github.com/amphp/byte-stream) - A non-blocking stream abstraction
- [kelunik/streaming-base64](https://github.com/kelunik/streaming-base64) - On the fly Base64 encoding for Amp's streams. 
- [kelunik/streaming-hash](https://github.com/kelunik/streaming-hash) - On the fly hashing for Amp's streams. 
- [kelunik/streaming-json](https://github.com/kelunik/streaming-json) - A streaming JSON parser
- [labrador-kennel/styled-byte-stream](https://github.com/labrador-kennel/styled-byte-stream) - Write styled output to a terminal using amphp OutputStream! 


## Throttling

- [ScriptFUSION/async-throttle](https://github.com/ScriptFUSION/Async-Throttle) - Throttles async work throughput
- [kelunik/rate-limit](https://github.com/kelunik/rate-limit) - Rate Limiting


## Testing

- [amphp/php-unit-util](https://github.com/amphp/phpunit-util) - Helper package to ease testing with PHPUnit
- [labrador-kennel/async-unit](https://github.com/labrador-kennel/async-unit) - A PHP8 unit and integration testing framework with first-class support for the amphp Loop
- [jolicode/asynit](https://github.com/jolicode/asynit) - Asynchronous HTTP Request Testing Library for API or more
- [HarmonyIO/PHPUnit-Extension](https://github.com/HarmonyIO/PHPUnit-Extension) - Extends PHPUnit with async helpers 
- [JBZoo/Mock-Server](https://github.com/JBZoo/Mock-Server) - Flexible HTTP mocking application for testing and fast prototyping
- [cspray/http-client-test-interceptor](https://github.com/cspray/http-client-test-interceptor) - A testing framework to mock Requests sent with amphp/http-client


## Validation

- [spacetab-io/body-validator-php](https://github.com/spacetab-io/body-validator-php) - Package to simplify validation of request body


## Websocket

- [amphp/websocket-server](https://github.com/amphp/websocket-server) - WebSocket component for amphp/http-server
- [amphp/websocket-client](https://github.com/amphp/websocket-client) - Async WebSocket client
- [cspray/websocket-commands](https://github.com/cspray/websocket-commands) - A micro-framework to facilitate building Websocket powered applications


## Windows

- [amphp/windows-registry](https://github.com/amphp/windows-registry) - Windows Registry reader


## Integration & adapters

- [danog/php-tokio](https://github.com/danog/php-tokio) - Use any async Rust library from PHP
- [amphp/react-adapter](https://github.com/amphp/react-adapter) - Adapter to make any ReactPHP library compatible with Amp v2
- [revoltphp/event-loop-adapter-react](https://github.com/revoltphp/event-loop-adapter-react) - Adapter to be used with Amp v3
- [amphp/react-stream-adapter](https://github.com/amphp/react-stream-adapter) - Adapters to make React's and Amp's streams compatible


## Unsorted yet

- [amphp/beanstalk](https://github.com/amphp/beanstalk) - Beanstalk client
- [php-service-bus/service-bus](https://github.com/php-service-bus/service-bus) - Service Bus (publish-subscribe pattern) implementation
- [kelunik/ACME](https://github.com/kelunik/acme) - Async ACME library
- [phpinnacle/ridge](https://github.com/phpinnacle/ridge) - Pure asynchronous PHP implementation of the AMQP 0-9-1 protocol
- [phpinnacle/cassis](https://github.com/phpinnacle/cassis) - Pure PHP asynchronous implementation of the Cassandra V4 binary protocol
- [wind-framework/wind-framework](https://github.com/wind-framework/wind-framework) - Pure PHP Coroutine Framework based on Workerman and Amphp
- [PeeHaa/AsyncTwitter](https://github.com/PeeHaa/AsyncTwitter) - Just like regular Twitter, but async
- [darkwood-fr/railway-fbp](https://github.com/darkwood-fr/railway-fbp) - Railway Flow Based Programming
- [darkwood-fr/railway-fbp-symfony](https://github.com/darkwood-fr/railway-fbp-symfony) - Railway Flow Based Programming implementation for Symfony
- [dbalabka/dag](https://github.com/dbalabka/dag) - Directed acyclic graph of tasks implementation based on Amphp promises
- [spacetab-io/paginate-php](https://github.com/spacetab-io/paginate-php) - Simple async paginator 
- [pact-foundation/pact-php](https://github.com/pact-foundation/pact-php) - Enables consumer driven contract testing, following the PACT foundation principles
- [JustBlackBird/amphp-priority-emitter](https://github.com/JustBlackBird/amphp-priority-emitter) -  AMP Emitter with priority queue inside 
- [amphp/serialization](https://github.com/amphp/serialization) - Serialization tools for IPC and data storage in PHP. 
- [labrador-kennel/core](https://github.com/labrador-kennel/core) - A foundation for building async applications on top of amphp
- [spacetab-io/amphp-support-php](https://github.com/spacetab-io/amphp-support-php) - Package to reduce code duplication across services.
- [andrew-ld/TokenSnitch](https://github.com/andrew-ld/TokenSnitch) - find leaked tokens from files
- [Mirocow/yii2-queue](https://github.com/Mirocow/yii2-queue) - Yii 2.0 Non blocking queue extension.
- [markkimsal/amphp-mqtt](https://github.com/markkimsal/amphp-mqtt) - MQTT client for Amp
- [amphp/aerys-reverse](https://github.com/amphp/aerys-reverse) - Reverse HTTP proxy handler for Aerys
- [kelunik/link-check](https://github.com/kelunik/link-check) - A small script to check one or several URLs for broken links.
- [pensiero/artax-composer](https://github.com/pensiero/artax-composer) - ZF2 service wrapper around amphp/artax client
- [tuefekci/blkhole](https://github.com/tuefekci/blkhole) - download management tool for AllDebrid cloud downloads, which allows automatic downloads to your local network.
- [labrador-kennel/composite-future](https://github.com/labrador-kennel/composite-future) - Compose @amphp Futures and await them however you want with a type-safe CompositeFuture object
- [flow-php/etl-adapter-amphp](https://github.com/flow-php/etl-adapter-amphp) - AMP asynchronous processing provider for [Flow PHP](https://github.com/flow-php/flow)


## Projects using amphp

- [Aspectus-PHP/terminal](https://github.com/Aspectus-PHP/terminal) - A terminal device abstraction based on Amphp
- [Aspectus-PHP/aspectus](https://github.com/Aspectus-PHP/aspectus) - A TUI framework based on Amphp
- [phpro/grumphp](https://github.com/phpro/grumphp) - A composer plugin that enables source code quality checks
- [PeeHaa/mailgrab](https://github.com/PeeHaa/mailgrab) - Simple and easy to use catch-all SMTP mail server and debugging tool
- [vimeo/psalm](https://github.com/vimeo/psalm) - A static analysis tool for finding errors in PHP applications
- [PeeHaa/socket-inspect](https://github.com/PeeHaa/socket-inspect) - Reverse engineering and socket inspection tool
- [spacetab-io/roastmap-php](https://github.com/spacetab-io/roastmap-php) - The purpose of the utility is preheating up Nginx cache through sitemap.xml
- [ostrolucky/stdinho](https://github.com/ostrolucky/stdinho) - Turn any STDIN/STDOUT into HTTP server
- [pact-foundation/pact-php](https://github.com/pact-foundation/pact-php) - PHP SDK for [Pact](https://pact.io)


## Guides / Tutorials

- [amphp/getting-started](https://github.com/amphp/getting-started) - A getting started guide for Amp


## Alternative libraries

- [reactphp/reactphp](https://github.com/reactphp/reactphp) - Event-driven, non-blocking I/O
- [BedrockStreaming/Tornado](https://github.com/BedrockStreaming/Tornado) - A library for asynchronous programming
- [logicalsteps/async](https://github.com/logicalsteps/async) - A compatible async implementation
