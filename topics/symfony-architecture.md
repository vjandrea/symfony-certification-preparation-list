---
title: Symfony Architecture - Symfony Certification Preparation List
---
[Back to index](../readme.md#table-of-contents)

# Symfony Architecture ✅ ❌ 🌈 ⏩ 🤡

## Symfony Flex ✅
- [Using Symfony Flex to Manage Symfony Applications - symfony.com](https://symfony.com/doc/5.0/setup/flex.html)  ✅

```  
    "conflict": {
         "symfony/symfony": "*"
    }
```  
Indique de ne jamais jamais réinstaller symfony/symfony car les composants sont désormais gérés par Flex.

## License ✅
- [Symfony License - symfony.com](https://symfony.com/doc/5.0/contributing/code/license.html) ✅

MIT, most used licence in GitHub, can be used in proprietary softwares.

## Components ✅
- [Symfony Components - symfony.com](https://symfony.com/components) ✅

* EventDispatcher => mediator pattern
* symfony/http-foundation => Request/Response 
* CType => ctype.h 

## Bridges ✅
- [What are symfony bridges, bundles and vendor? - stackoverflow.com](https://stackoverflow.com/q/11888522/633864) 

## Configuration ✅
- [The Config Component - symfony.com](https://symfony.com/doc/5.0/components/config.html) 🌈
  - Caching based on Resources ✅
  - Defining and Processing Configuration Values ✅
    - arrayPrototype : quand on a un tableau
  - Loading Resources ✅
  - How to Create Friendly Configuration for a Bundle ✅
  - How to Load Service Configuration inside a Bundle ✅
  - How to Simplify Configuration of Multiple Bundles ✅

## Code organization ✅
- [Organizing Your Business Logic - symfony.com](https://symfony.com/doc/5.0/best_practices#business-logic) ✅

## Request handling ✅
- [Symfony and HTTP Fundamentals - symfony.com](https://symfony.com/doc/5.0/introduction/http_fundamentals.html)  ✅
  - [Difference Between URI and URL](https://www.differencebetween.com/difference-between-uri-and-vs-url/) ✅ 

## Exception handling ✅
- [How to Customize Error Pages - symfony.com](https://symfony.com/doc/5.0/controller/error_pages.html) ✅

## Event dispatcher and kernel events 🌈
- [Symfony Framework Events - symfony.com](https://symfony.com/doc/5.0/reference/events.html) 
  - [Kernel Event table (8, RCCV-RFTE 🐘)](https://symfony.com/doc/5.0/components/http_kernel.html#component-http-kernel-event-table) 
- [The HttpKernel Component - symfony.com](https://symfony.com/doc/5.0/components/http_kernel.html) 
- [Events and event listeners - symfony.com](https://symfony.com/doc/5.0/event_dispatcher.html) 
- [The EventDispatcher Component - symfony.com](https://symfony.com/doc/5.0/components/event_dispatcher.html) 

## Official best practices
- [Symfony Best Practices - symfony.com](https://symfony.com/doc/5.0/best_practices/index.html) 

## Release management
- [The Release Process - symfony.com](https://symfony.com/doc/5.0/contributing/community/releases.html) 

## Backward compatibility promise
- [Our Backwards Compatibility Promise - symfony.com](https://symfony.com/doc/5.0/contributing/code/bc.html) 

## Deprecations best practices
- [Deprecations - symfony.com](https://symfony.com/doc/5.0/contributing/code/conventions.html#deprecations) 
