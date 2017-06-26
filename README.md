# Additionall resources

* https://github.com/raulconti/symfony-3-certification-guide
* https://github.com/ThomasBerends/symfony-certification-preparation-list



# PHP and Web Security

## PHP 5.3 to PHP 5.6 API

* http://php.net/manual/en/migration54.php
* http://php.net/manual/en/migration55.php
* http://php.net/manual/en/migration56.php

## Object Oriented Programming

* http://php.net/manual/en/language.oop5.php

## Namespaces

* http://php.net/manual/en/language.namespaces.php

## Interfaces

* http://php.net/manual/en/language.oop5.interfaces.php

## Anonymous functions and closures

* http://php.net/manual/en/functions.anonymous.php
* http://php.net/manual/en/class.closure.php

## Abstract classes

* http://php.net/manual/en/language.oop5.abstract.php

## Exception and error handling

* http://php.net/manual/en/language.exceptions.php
* http://php.net/manual/en/class.exception.php

## Traits

* http://php.net/manual/en/language.oop5.traits.php

## PHP extensions

* http://php.net/manual/en/extensions.membership.php
* http://php.net/manual/en/function.extension-loaded.php
* http://php.net/manual/en/function.get-loaded-extensions.php
* http://php.net/manual/en/function.get-extension-funcs.php

## SPL

* http://php.net/book.spl

## Web security (XSS, CSRF, etc.)

* http://php.net/manual/en/security.php
* http://www.phptherightway.com/#security

# HTTP

## Client / Server interaction

* https://en.wikibooks.org/wiki/Communication_Networks/HTTP_Protocol
* https://en.wikipedia.org/wiki/Hypertext_Transfer_Protocol

## Status codes

* https://github.com/for-GET/know-your-http-well/blob/master/status-codes.md

## HTTP request

* https://www.w3.org/Protocols/rfc2616/rfc2616-sec5.html

## HTTP response

* https://www.w3.org/Protocols/rfc2616/rfc2616-sec6.html#sec6

## HTTP methods

* https://www.w3.org/Protocols/rfc2616/rfc2616-sec9.html

## Cookies

* https://en.wikipedia.org/wiki/HTTP_cookie

## Caching

* http://symfony.com/doc/current/http_cache.html
* http://symfony.com/doc/current/http_cache/cache_invalidation.html
* http://symfony.com/doc/current/http_cache/cache_vary.html
* http://symfony.com/doc/current/http_cache/esi.html
* http://symfony.com/doc/current/http_cache/expiration.html
* http://symfony.com/doc/current/http_cache/form_csrf_caching.html
* http://symfony.com/doc/current/http_cache/validation.html

## Content negotiation

* https://en.wikipedia.org/wiki/Content_negotiation
* https://developer.mozilla.org/en-US/docs/Web/HTTP/Content_negotiation

## Language detection

* https://developer.mozilla.org/en-US/docs/Web/HTTP/Headers/Accept-Language


# Symfony Architecture

## Symfony Standard Edition

* http://symfony.com/distributions
* https://github.com/symfony/symfony-standard

## License

* https://symfony.com/doc/current/contributing/code/license.html

## Components

* http://symfony.com/doc/current/components/asset.html
* http://symfony.com/doc/current/components/browser_kit.html
* http://symfony.com/doc/current/components/cache.html
* http://symfony.com/doc/current/components/class_loader.html
* http://symfony.com/doc/current/components/config.html
* http://symfony.com/doc/current/components/console.html
* http://symfony.com/doc/current/components/css_selector.html
* http://symfony.com/doc/current/components/debug.html
* http://symfony.com/doc/current/components/dependency_injection.html
* http://symfony.com/doc/current/components/dotenv.html
* http://symfony.com/doc/current/components/dom_crawler.html
* http://symfony.com/doc/current/components/event_dispatcher.html
* http://symfony.com/doc/current/components/expression_language.html
* http://symfony.com/doc/current/components/filesystem.html
* http://symfony.com/doc/current/components/finder.html
* http://symfony.com/doc/current/components/form.html
* http://symfony.com/doc/current/components/http_foundation.html
* http://symfony.com/doc/current/components/http_kernel.html
* http://symfony.com/doc/current/components/intl.html
* http://symfony.com/doc/current/components/ldap.html
* http://symfony.com/doc/current/components/options_resolver.html
* http://symfony.com/doc/current/components/process.html
* http://symfony.com/doc/current/components/property_access.html
* http://symfony.com/doc/current/components/property_info.html
* http://symfony.com/doc/current/components/routing.html
* http://symfony.com/doc/current/components/security.html
* http://symfony.com/doc/current/components/serializer.html
* http://symfony.com/doc/current/components/stopwatch.html
* http://symfony.com/doc/current/components/templating.html
* http://symfony.com/doc/current/components/translation.html
* http://symfony.com/doc/current/components/validator.html
* http://symfony.com/doc/current/components/var_dumper.html
* http://symfony.com/doc/current/components/workflow.html
* http://symfony.com/doc/current/components/yaml.html
* http://symfony.com/doc/current/components/phpunit_bridge.html

## Bundles

* http://symfony.com/doc/current/bundles.html

## Bridges

Vendor

In general, vendor are the dependencies of your project (aka third party libraries). It's the same meaning in Symfony2.

Bundle

From the documentation about bundles:

A bundle is a directory that has a well-defined structure and can host anything from classes to controllers and web resources.
In other words, it's a part of your application which owns a logic (controllers, views, models). Bundles can also wrap a library. For example, the BazingaGeocoderBundle wraps the Geocoder library. It provides Symfony2 oriented features to ease the use of a library in a Symfony2 project. Also, it can be a glue between components.

Bridge

A bridge is a set of classes that aims at extending a library into Symfony2. A bridge is part of the core. You can find a bridge for the third libraries that could be in the core (Twig, Doctrine, Propel, Monolog, etc.). If you don't want to use Doctrine as ORM, then you don't care about the EntityType. That's why this class is in the bridge.

To sum up, a bridge extends some components and a bundle adds features to the application.

## Configuration

* http://symfony.com/doc/current/configuration.html
* http://symfony.com/doc/current/best_practices/configuration.html

## Code organization

* http://symfony.com/doc/current/best_practices/business-logic.html

## Request handling

* http://symfony.com/doc/3.0/introduction/http_fundamentals.html

## Exception handling

* https://symfony.com/doc/current/components/http_kernel.html#handling-exceptions-the-kernel-exception-event

## Event dispatcher and kernel events

* https://symfony.com/doc/current/components/event_dispatcher.html
* https://symfony.com/doc/current/event_dispatcher.html
* http://api.symfony.com/3.3/Symfony/Component/HttpKernel/KernelEvents.html
* https://symfony.com/doc/current/components/http_kernel.html#component-http-kernel-event-table

## Official best practices

* https://symfony.com/doc/current/best_practices/index.html

## Release management

* https://symfony.com/doc/current/contributing/community/releases.html

## Backward compatibility promise

* https://symfony.com/doc/current/contributing/code/bc.html

## Deprecations best practices

* http://symfony.com/doc/3.0/contributing/code/conventions.html#deprecations

# Standardization

## Release management and roadmap schedule

* https://symfony.com/doc/current/contributing/community/releases.html

## Framework interoperability and PSRs

* http://symfony.com/doc/current/request/psr7.html

## Naming conventions

* http://symfony.com/doc/current/contributing/code/conventions.html

## Coding standards

* http://symfony.com/doc/current/contributing/code/standards.html

## Third-party libraries integration

* http://symfony.com/doc/current/bundles/installation.html

## Composer packages handling

* https://getcomposer.org/doc/

## Development best practices

* http://symfony.com/doc/current/best_practices/index.html

## Framework overloading

* http://symfony.com/doc/current/bundles/override.html
* http://symfony.com/doc/current/templating/overriding.html
* http://symfony.com/doc/current/bundles/inheritance.html

## Semantic versioning

* http://symfony.com/doc/current/contributing/code/bc.html
* http://symfony.com/doc/current/contributing/community/releases.html
* http://semver.org/


# Bundles

## Naming conventions

* http://symfony.com/doc/3.0/bundles/best_practices.html#bundle-name

## Code organization

* http://symfony.com/doc/3.0/bundles/best_practices.html#directory-structure 
* https://symfony.com/doc/current/bundles.html#bundle-directory-structure


## Controllers

* https://symfony.com/doc/current/bundles/best_practices.html#classes
* http://symfony.com/doc/current/controller.html

## The views

* http://symfony.com/doc/current/quick_tour/the_view.html

## The resources

* http://symfony.com/doc/current/best_practices/web-assets.html

## Overriding default error pages

* https://symfony.com/doc/current/controller/error_pages.html

## Bundle inheritance

* http://symfony.com/doc/current/bundles/inheritance.html

## Event dispatcher and kernel events

* https://symfony.com/doc/current/reference/events.html
* http://symfony.com/doc/current/event_dispatcher.html

## Semantic configuration and compiler passes

* http://symfony.com/doc/current/service_container/compiler_passes.html
* http://symfony.com/doc/current/components/dependency_injection/compilation.html

# Controllers

## Naming conventions

* http://symfony.com/doc/current/routing.html#controller-string-syntax

## The base Controller class

* http://symfony.com/doc/current/controller.html#the-base-controller-classes-services

## The request

* http://symfony.com/doc/current/controller.html#the-request-object-as-a-controller-argument
* http://symfony.com/doc/current/controller.html#the-request-and-response-object

## The response

* http://symfony.com/doc/current/controller.html#the-request-and-response-object
* http://symfony.com/doc/current/components/http_foundation.html#response

## The cookies

* http://symfony.com/doc/current/components/http_foundation.html#accessing-request-data
* http://symfony.com/doc/current/components/http_foundation.html#setting-cookies

## The session

* http://symfony.com/doc/current/controller.html#managing-the-session
* http://symfony.com/doc/current/components/http_foundation/sessions.html

## The flash messages

* http://symfony.com/doc/current/controller.html#flash-messages
* http://symfony.com/doc/current/components/http_foundation/sessions.html#flash-messages

## HTTP redirects

* http://symfony.com/doc/current/controller.html#redirecting

## Internal redirects

* http://symfony.com/doc/current/controller/forwarding.html

## Generate 404 pages

* http://symfony.com/doc/current/controller.html#managing-errors-and-404-pages
* http://symfony.com/doc/current/controller/error_pages.html

## File upload

* https://symfony.com/doc/current/controller/upload_file.html

## Built-in internal controllers

* http://symfony.com/doc/current/controller.html#the-base-controller-classes-services

# Routing

## Configuration (YAML, XML, PHP & annotations)

* http://symfony.com/doc/current/routing.html#routing-examples

## Restrict URL parameters

* http://symfony.com/doc/current/routing.html#adding-wildcard-requirements

## Set default values to URL parameters

* http://symfony.com/doc/current/routing.html#giving-placeholders-a-default-value

## Generate URL parameters

* http://symfony.com/doc/current/routing.html#generating-urls

## Trigger redirects

* http://symfony.com/doc/current/routing/redirect_in_config.html
* http://symfony.com/doc/current/routing/redirect_trailing_slash.html
* http://symfony.com/doc/current/controller.html#redirecting

## Special internal routing attributes

* https://symfony.com/doc/current/routing/extra_information.html

## Domain name matching

* https://symfony.com/doc/current/routing/hostname_pattern.html

## Conditional request matching

* http://symfony.com/doc/current/routing/conditions.html

## HTTP methods matching

* http://symfony.com/doc/current/routing/requirements.html#adding-http-method-requirements
* http://symfony.com/doc/current/components/routing.html

## User's locale guessing

* http://symfony.com/doc/current/routing.html#advanced-routing-example

## Router debugging

* https://symfony.com/doc/current/routing/debug.html

# Templating with Twig

## Auto escaping

* http://symfony.com/doc/current/templating.html#output-escaping

## Template inheritance

* http://symfony.com/doc/current/templating/inheritance.html
* https://twig.sensiolabs.org/doc/2.x/templates.html#template-inheritance

## Global variables

* http://symfony.com/doc/current/templating/app_variable.html
* http://symfony.com/doc/current/templating/global_variables.html

## Filters and functions

* https://twig.sensiolabs.org/doc/2.x/filters/index.html
* https://twig.sensiolabs.org/doc/2.x/functions/index.html

## Template includes

## Loops and conditions

* https://twig.sensiolabs.org/doc/2.x/tags/for.html
* https://twig.sensiolabs.org/doc/2.x/tags/for.html#adding-a-condition

## URLs generation

## Controller rendering

## Translations and pluralization

## String interpolation

## Assets management

## Debugging variables

* http://symfony.com/doc/current/templating/debug.html

# Forms

## Forms creation

* https://symfony.com/doc/current/forms.html#creating-a-simple-form

## Forms handling

* https://symfony.com/doc/current/forms.html#handling-form-submissions

## Form types

* https://symfony.com/doc/current/form/create_custom_field_type.html

## Forms rendering with Twig

* https://symfony.com/doc/current/forms.html#rendering-the-form
* https://symfony.com/doc/current/form/rendering.html
* https://symfony.com/doc/current/form/form_customization.html

## Forms theming

* https://symfony.com/doc/current/form/form_themes.html

## CSRF protection

* https://symfony.com/doc/current/form/csrf_protection.html

## Handling file upload

* https://symfony.com/doc/current/controller/upload_file.html

## Built-in form types

* https://symfony.com/doc/current/reference/forms/types.html

## Data transformers

* https://symfony.com/doc/current/form/data_transformers.html

## Form events

* https://symfony.com/doc/current/form/events.html

## Form type extensions

* https://symfony.com/doc/current/form/create_form_type_extension.html

# Data Validation

## PHP object validation

* https://symfony.com/doc/current/validation.html#the-basics-of-validation

## Built-in validation constraints

* https://symfony.com/doc/current/validation.html#constraints

## Validation scopes

* http://symfony.com/doc/current/validation.html

## Validation groups

* http://symfony.com/doc/current/validation/groups.html

## Group sequence

* https://symfony.com/doc/current/validation/sequence_provider.html

## Custom callback validators

* https://symfony.com/doc/current/reference/constraints/Callback.html

## Violations builder

* http://symfony.com/doc/current/validation/custom_constraint.html

# Dependency Injection

* http://symfony.com/doc/current/components/dependency_injection.html

## Service container

* http://symfony.com/doc/current/service_container.html#

## Built-in services

* https://symfony.com/doc/current/service_container/debug.html

## Configuration parameters

* http://symfony.com/doc/current/service_container/parameters.html

## Services registration

* https://symfony.com/doc/current/components/dependency_injection.html#basic-usage

## Tags

* http://symfony.com/doc/current/service_container/tags.html

## Semantic configuration

* http://symfony.com/doc/current/service_container/import.html

## Factories

* http://symfony.com/doc/current/service_container/factories.html

## Compiler passes

* http://symfony.com/doc/current/components/dependency_injection/compilation.html

## Services autowiring

* http://symfony.com/doc/current/service_container.html#the-autowire-option

# Security

* http://symfony.com/doc/current/components/security.html

## Authentication

* http://symfony.com/doc/current/components/security/authentication.html

## Authorization

* http://symfony.com/doc/current/components/security/authorization.html

## Configuration

* http://symfony.com/doc/current/reference/configuration/security.html

## Providers

* http://symfony.com/doc/current/security/custom_authentication_provider.html

## Firewalls

* http://symfony.com/doc/current/components/security/firewall.html

## Users

* http://symfony.com/doc/current/security/custom_provider.html
* http://symfony.com/doc/current/security/entity_provider.html
* http://symfony.com/doc/current/security/impersonating_user.html
* http://symfony.com/doc/current/security/multiple_user_providers.html
* http://symfony.com/doc/current/security/user_checkers.html
* http://symfony.com/doc/current/reference/constraints/UserPassword.html

## Passwords encoders

* http://symfony.com/doc/current/security.html#c-encoding-the-user-s-password
* http://symfony.com/doc/current/security/named_encoders.html
* http://symfony.com/doc/current/security/password_encoding.html

## Roles

* http://symfony.com/doc/current/security.html#roles

## Access Control Rules

* http://symfony.com/doc/current/security/acl.html
* http://symfony.com/doc/current/security/acl_advanced.html

## Guard authenticators

* http://symfony.com/doc/current/security/guard_authentication.html
* http://symfony.com/doc/current/security/multiple_guard_authenticators.html

## Voters and voting strategies

* http://symfony.com/doc/current/security/voters.html

# HTTP Caching

* http://symfony.com/doc/current/http_cache.html#http-cache-introduction

## Cache types (browser, proxies and reverse-proxies)

* http://symfony.com/doc/current/http_cache.html#caching-on-the-shoulders-of-giants

## Expiration (Expires, Cache-Control)

* http://symfony.com/doc/current/http_cache/expiration.html

## Validation (ETag, Last-Modified)

* http://symfony.com/doc/current/http_cache/validation.html

## Client side caching

## Server side caching

* http://symfony.com/doc/current/http_cache/varnish.html

## Edge Side Includes

* http://symfony.com/doc/current/http_cache/esi.html

# Console

## Built-in commands

* http://symfony.com/doc/current/components/console/usage.html#built-in-commands

## Custom commands

* http://symfony.com/doc/current/console.html

## Configuration

* http://symfony.com/doc/current/console.html#configuring-the-command

## Options and arguments

* http://symfony.com/doc/current/console/input.html

## Input and Output objects

* http://symfony.com/doc/current/console.html#console-input
* http://symfony.com/doc/current/console/input.html
* http://symfony.com/doc/current/console/coloring.html

## Built-in helpers

* http://symfony.com/doc/current/components/console/helpers/formatterhelper.html
* http://symfony.com/doc/current/components/console/helpers/processhelper.html
* http://symfony.com/doc/current/components/console/helpers/progressbar.html
* http://symfony.com/doc/current/components/console/helpers/questionhelper.html
* http://symfony.com/doc/current/components/console/helpers/table.html
* http://symfony.com/doc/current/components/console/helpers/debug_formatter.html

## Console events

* http://symfony.com/doc/current/components/console/events.html

## Verbosity levels

* http://symfony.com/doc/current/console/verbosity.html

# Automated Tests

## Unit tests with PHPUnit

* http://symfony.com/doc/current/testing.html#unit-tests

## Functional tests with PHPUnit

* http://symfony.com/doc/current/testing.html#functional-tests

## Client object

* http://symfony.com/doc/current/testing.html#working-with-the-test-client
* http://symfony.com/doc/current/components/browser_kit.html

## Crawler object

* http://symfony.com/doc/current/testing.html#the-crawler

## Profile object

* http://symfony.com/doc/current/testing.html#accessing-the-profiler-data
* http://symfony.com/doc/current/testing/profiling.html

## Framework objects access

* http://symfony.com/doc/current/testing.html#accessing-internal-objects

## Client configuration

* http://symfony.com/doc/current/components/browser_kit.html

## Request and response objects introspection

* http://symfony.com/doc/current/testing.html#accessing-internal-objects

## PHPUnit bridge

* http://symfony.com/doc/current/components/phpunit_bridge.html

## Handling legacy deprecated code

* https://symfony.com/doc/current/components/phpunit_bridge.html#usage

# Miscellaneous

## Error handling

* http://symfony.com/doc/current/event_dispatcher.html

## Code debugging

* http://symfony.com/doc/current/debug/debugging.html

## Deployment best practices

* http://symfony.com/doc/current/deployment.html

## Process and Serializer components

* http://symfony.com/doc/current/components/process.html
* http://symfony.com/doc/current/components/serializer.html

## Data collectors

* http://symfony.com/doc/current/profiler/data_collector.html

## Web Profiler and Web Debug Toolbar

* http://symfony.com/doc/current/profiler.html
* http://symfony.com/doc/current/profiler/matchers.html
* http://symfony.com/doc/current/profiler/profiling_data.html
* http://symfony.com/doc/current/profiler/storage.html
* https://knpuniversity.com/screencast/micro-symfony/web-debug-toolbar
* http://symfony.com/doc/current/reference/configuration/web_profiler.html
* http://symfony.com/doc/current/reference/configuration/debug.html

## Internationalization and localization

* http://symfony.com/doc/current/translation.html