---
title:  Symfony Certification Preparation List
permalink: /
---

# Symfony Certification Preparation List
When looking for a guide to prepare myself for a Symfony certification, I couldn't find a lot. So I've decided to start this project to help people find everything they need.

If you're looking for other people who are interested (or have) certification. Please check the #certification channel at the Symfony Devs Slack. [Request an invite here](https://symfony.com/slack-invite)

Please help add new links/info. We currently have not all topics covered. For more information refer to the [Contributing page](contributing.md).

The exam topics are copied from the [official exam topics](https://sensiolabs.com/en/symfony/certification.html). The master branch contains information for the 4.0 certification. For 3.0, check the 3.0 branch. We do not have a list for 2.3 certification.

## Table of Contents ✅ ❌ 🌈 ⏩ 🤡

- [PHP](/topics/php-and-web-security.md) 
    - [PHP API up to PHP 7.2 version](/topics/php-and-web-security.md#php-api-up-to-php-72-version) 
    - [Object Oriented Programming](/topics/php-and-web-security.md#object-oriented-programming) 
    - [Namespaces](/topics/php-and-web-security.md#namespaces) 
    - [Interfaces](/topics/php-and-web-security.md#interfaces) 
    - [Anonymous functions and closures](/topics/php-and-web-security.md#anonymous-functions-and-closures) 
    - [Abstract classes](/topics/php-and-web-security.md#abstract-classes) 
    - [Exception and error handling](/topics/php-and-web-security.md#exception-and-error-handling) 
    - [Traits](/topics/php-and-web-security.md#traits) 
    - [PHP extensions](/topics/php-and-web-security.md#php-extensions) 
    - [SPL](/topics/php-and-web-security.md#spl) 

- [HTTP](/topics/http.md) 
    - [Client / Server interaction](/topics/http.md#client--server-interaction) 
    - [Status codes](/topics/http.md#status-codes) 
    - [HTTP request](/topics/http.md#http-request) 
    - [HTTP response](/topics/http.md#http-response) 
    - [HTTP methods](/topics/http.md#http-methods)  
    - [Cookies](/topics/http.md#cookies) 
    - [Caching](/topics/http.md#caching) 
    - [Content negotiation](/topics/http.md#content-negotiation) 
    - [Language detection](/topics/http.md#language-detection)  
    - [Symfony HttpClient component](https://symfony.com/doc/5.0/http_client.html) 
    
- [Symfony Architecture](/topics/symfony-architecture.md) ✅
    - [Symfony Flex](/topics/symfony-architecture.md#symfony-flex) ✅
    - [License](/topics/symfony-architecture.md#license) ✅
    - [Components](/topics/symfony-architecture.md#components) ✅
    - [Bridges](/topics/symfony-architecture.md#bridges) ✅
    - [Configuration](/topics/symfony-architecture.md#configuration) ✅
    - [Code organization](/topics/symfony-architecture.md#code-organization)  ✅
    - [Request handling](/topics/symfony-architecture.md#request-handling) ✅ 
    - [Exception handling](/topics/symfony-architecture.md#exception-handling) ✅ 
    - [Event dispatcher and kernel events](/topics/symfony-architecture.md#event-dispatcher-and-kernel-events) ✅ 
    - [Official best practices](/topics/symfony-architecture.md#official-best-practices) ✅
    - [Release management](/topics/symfony-architecture.md#release-management) ✅
    - [Backward compatibility promise](/topics/symfony-architecture.md#backward-compatibility-promise) ✅
    - [Deprecations best practices](/topics/symfony-architecture.md#deprecations-best-practices) ✅

- [Standardization](/topics/standardization.md) (not in 5.0 list antmore) ❌
    - [Release management and roadmap schedule](/topics/standardization.md#release-management-and-roadmap-schedule) ❌
    - [Framework interoperability and PSRs](/topics/standardization.md#framework-interoperability-and-psrs) ❌
    - [Naming conventions](/topics/standardization.md#naming-conventions) ❌
    - [Coding standards](/topics/standardization.md#coding-standards) ❌
    - [Third-party libraries integration](/topics/standardization.md#third-party-libraries-integration) ❌
    - [Composer packages handling](/topics/standardization.md#composer-packages-handling) ❌
    - [Development best practices](/topics/standardization.md#development-best-practices) ❌
    - [Framework overloading](/topics/standardization.md#framework-overloading) ❌
    - [Semantic versioning](/topics/standardization.md#semantic-versioning) ❌

- [Controllers](/topics/controllers.md) ✅
    - [The base Controller class](/topics/controllers.md#the-base-controller-class) ✅
    - [The request](/topics/controllers.md#the-request) ✅
    - [The response](/topics/controllers.md#the-response) ✅
    - [The cookies](/topics/controllers.md#the-cookies) ✅
    - [The session](/topics/controllers.md#the-session) ✅
    - [The flash messages](/topics/controllers.md#the-flash-messages) ✅
    - [HTTP redirects](/topics/controllers.md#http-redirects) ✅
    - [Internal redirects](/topics/controllers.md#internal-redirects) ✅
    - [Generate 404 pages](/topics/controllers.md#generate-404-pages) ✅
    - [File upload](/topics/controllers.md#file-upload) ✅
    - [Built-in internal controllers](/topics/controllers.md#built-in-internal-controllers) ✅

- [Routing](/topics/routing.md) ✅
    - [Configuration (YAML, XML, PHP & annotations)](/topics/routing.md#configuration-yaml-xml-php--annotations)  ✅
    - [Restrict URL parameters](/topics/routing.md#restrict-url-parameters) ✅
    - [Set default values to URL parameters](/topics/routing.md#set-default-values-to-url-parameters) ✅
    - [Generate URL parameters](/topics/routing.md#generate-url-parameters) ✅
    - [Trigger redirects](/topics/routing.md#trigger-redirects) ✅
    - [Special internal routing attributes](/topics/routing.md#special-internal-routing-attributes) ✅
    - [Domain name matching](/topics/routing.md#domain-name-matching) ✅
    - [Conditional request matching](/topics/routing.md#conditional-request-matching) ✅
    - [HTTP methods matching](/topics/routing.md#http-methods-matching) ✅
    - [User's locale guessing](/topics/routing.md#users-locale-guessing) ✅
    - [Router debugging](/topics/routing.md#router-debugging) ✅

- [Templating with Twig](/topics/templating-with-twig.md) ✅
    - [Auto escaping](/topics/templating-with-twig.md#auto-escaping) ✅
    - [Template inheritance](/topics/templating-with-twig.md#template-inheritance) ✅
    - [Global variables](/topics/templating-with-twig.md#global-variables) ✅
    - [Filters and functions](/topics/templating-with-twig.md#filters-and-functions) ✅
    - [Template includes](/topics/templating-with-twig.md#template-includes) ✅
    - [Loops and conditions](/topics/templating-with-twig.md#loops-and-conditions) ✅
    - [URLs generation](/topics/templating-with-twig.md#urls-generation) ✅
    - [Controller rendering](/topics/templating-with-twig.md#controller-rendering) ✅
    - [Translations and pluralization](/topics/templating-with-twig.md#translations-and-pluralization) 
    - [String interpolation](/topics/templating-with-twig.md#string-interpolation) ✅
    - [Assets management](/topics/templating-with-twig.md#assets-management) ✅
    - [Debugging variables](/topics/templating-with-twig.md#debugging-variables) ✅

- [Forms](/topics/forms.md) ✅
    - [Forms creation](/topics/forms.md#forms-creation) ✅
    - [Forms handling](/topics/forms.md#forms-handling) ✅
    - [Form types](/topics/forms.md#form-types) ✅
    - [Forms rendering with Twig](/topics/forms.md#forms-rendering-with-twig) ✅
    - [Forms theming](/topics/forms.md#forms-theming) ✅
    - [CSRF protection](/topics/forms.md#csrf-protection) ✅
    - [Handling file upload](/topics/forms.md#handling-file-upload) ✅
    - [Built-in form types](/topics/forms.md#built-in-form-types)  ✅
    - [Data transformers](/topics/forms.md#data-transformers) ✅
    - [Form events](/topics/forms.md#form-events) ✅
    - [Form type extensions](/topics/forms.md#form-type-extensions) ✅

- [Data Validation](/topics/data-validation.md) ✅ 
    - [PHP object validation](/topics/data-validation.md#php-object-validation) ✅ 
    - [Built-in validation constraints](/topics/data-validation.md#built-in-validation-constraints) ✅ 
    - [Validation scopes](/topics/data-validation.md#validation-scopes) ✅ 
    - [Validation groups](/topics/data-validation.md#validation-groups) ✅ 
    - [Group sequence](/topics/data-validation.md#group-sequence) ✅ 
    - [Custom callback validators](/topics/data-validation.md#custom-callback-validators) ✅ 
    - [Violations builder](/topics/data-validation.md#violations-builder) ✅ 

- [Dependency Injection](/topics/dependency-injection.md) ✅
    - [Service container](/topics/dependency-injection.md#service-container) ✅
    - [Built-in services](/topics/dependency-injection.md#built-in-services) ✅
    - [Configuration parameters](/topics/dependency-injection.md#configuration-parameters) ✅
    - [Services registration](/topics/dependency-injection.md#services-registration) ✅
    - [Tags](/topics/dependency-injection.md#tags) ✅
    - [Semantic configuration](/topics/dependency-injection.md#semantic-configuration) ✅ 
    - [Factories](/topics/dependency-injection.md#factories) ✅
    - [Compiler passes](/topics/dependency-injection.md#compiler-passes) ✅
    - [Services autowiring](/topics/dependency-injection.md#services-autowiring) ✅ 

- [Security](/topics/security.md) ✅ 
    - [Authentication](/topics/security.md#authentication) ✅ 
    - [Authorization](/topics/security.md#authorization) ✅ 
    - [Configuration](/topics/security.md#configuration) ✅ 
    - [Providers](/topics/security.md#providers) ✅ 
    - [Firewalls](/topics/security.md#firewalls) ✅ 
    - [Users](/topics/security.md#users) ✅ 
    - [Passwords encoders](/topics/security.md#passwords-encoders) ✅ 
    - [Roles](/topics/security.md#roles) ✅ 
    - [Access Control Rules](/topics/security.md#access-control-rules) ✅ 
    - [Guard authenticators](/topics/security.md#guard-authenticators) ✅ 
    - [Voters and voting strategies](/topics/security.md#voters-and-voting-strategies) ✅ 

- [HTTP Caching](/topics/http-caching.md) 
    - [Cache types (browser, proxies and reverse-proxies)](/topics/http-caching.md#cache-types-browser-proxies-and-reverse-proxies) 
    - [Expiration (Expires, Cache-Control)](/topics/http-caching.md#expiration-expires-cache-control) 
    - [Validation (ETag, Last-Modified)](/topics/http-caching.md#validation-etag-last-modified) 
    - [Client side caching](/topics/http-caching.md#client-side-caching) 
    - [Server side caching](/topics/http-caching.md#server-side-caching) 
    - [Edge Side Includes](/topics/http-caching.md#edge-side-includes) 

- [Console](/topics/console.md) ✅
    - [Built-in commands](/topics/console.md#built-in-commands) ✅
    - [Custom commands](/topics/console.md#custom-commands) ✅
    - [Configuration](/topics/console.md#configuration) ✅
    - [Options and arguments](/topics/console.md#options-and-arguments) ✅
    - [Input and Output objects](/topics/console.md#input-and-output-objects) ✅
    - [Built-in helpers](/topics/console.md#built-in-helpers) ✅
    - [Console events](/topics/console.md#console-events) ✅
    - [Verbosity levels](/topics/console.md#verbosity-levels) ✅

- [Automated Tests](/topics/automated-tests.md) 
    - [Unit tests with PHPUnit](/topics/automated-tests.md#unit-tests-with-phpunit) 
    - [Functional tests with PHPUnit](/topics/automated-tests.md#functional-tests-with-phpunit) 
    - [Client object](/topics/automated-tests.md#client-object) 
    - [Crawler object](/topics/automated-tests.md#crawler-object) 
    - [Profile object](/topics/automated-tests.md#profile-object) 
    - [Framework objects access](/topics/automated-tests.md#framework-objects-access) 
    - [Client configuration](/topics/automated-tests.md#client-configuration) 
    - [Request and response objects introspection](/topics/automated-tests.md#request-and-response-objects-introspection) 
    - [PHPUnit bridge](/topics/automated-tests.md#phpunit-bridge) 
    - [Handling legacy deprecated code](/topics/automated-tests.md#handling-legacy-deprecated-code) 

- [Miscellaneous](/topics/miscellaneous.md) 🌈
    - [Configuration (including DotEnv and ExpressionLanguage components)](/topics/miscellaneous.md#configuration-including-dotenv-and-expressionlanguage-components)
    - [Error handling](/topics/miscellaneous.md#error-handling) 
    - [Code debugging](/topics/miscellaneous.md#code-debugging) 
    - [Deployment best practices](/topics/miscellaneous.md#deployment-best-practices) 
    - [Process and Serializer components](/topics/miscellaneous.md#process-and-serializer-components) �
    - [Messenger component](/topics/miscellaneous.md#messenger-component)
    - [Mime and Mailer components](/topics/miscellaneous.md#mime-and-mailer-components)
    - [Filesystem and Finder components](/topics/miscellaneous.md#filesystem-and-finder-components)
    - [Lock component](/topics/miscellaneous.md#lock-component)
    - [Web Profiler and Web Debug Toolbar](/topics/miscellaneous.md#web-profiler-and-web-debug-toolbar)
    - [Internationalization and localization](/topics/miscellaneous.md#internationalization-and-localization)
    
