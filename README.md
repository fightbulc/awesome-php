# Awesome PHP [![Build Status](https://api.travis-ci.org/ziadoz/awesome-php.svg?branch=master)](https://travis-ci.org/ziadoz/awesome-php)

A curated list of amazingly awesome PHP libraries, resources and shiny things.

## Contributing
Please see [CONTRIBUTING](https://github.com/ziadoz/awesome-php/blob/master/CONTRIBUTING.md) and [CODE-OF-CONDUCT](https://github.com/ziadoz/awesome-php/blob/master/CODE-OF-CONDUCT.md) for details.

## Table of Contents
- [Awesome PHP](#awesome-php)
    - [Dependency Management](#dependency-management)
    - [Dependency Management Extras](#dependency-management-extras)
    - [Frameworks](#frameworks)
    - [Framework Extras](#framework-extras)
    - [Components](#components)
    - [Micro Frameworks](#micro-frameworks)
    - [Micro Framework Extras](#micro-framework-extras)
    - [Routers](#routers)
    - [Templating](#templating)
    - [Static Site Generators](#static-site-generators)
    - [HTTP](#http)
    - [Middlewares](#middlewares)
    - [URL](#url)
    - [Email](#email)
    - [Files](#files)
    - [Streams](#streams)
    - [Dependency Injection](#dependency-injection)
    - [Imagery](#imagery)
    - [Testing](#testing)
    - [Continuous Integration](#continuous-integration)
    - [Documentation](#documentation)
    - [Security](#security)
    - [Passwords](#passwords)
    - [Code Analysis](#code-analysis)
    - [Architectural](#architectural)
    - [Debugging and Profiling](#debugging-and-profiling)
    - [Build Tools](#build-tools)
    - [Task Runners](#task-runners)
    - [Navigation](#navigation)
    - [Asset Management](#asset-management)
    - [Geolocation](#geolocation)
    - [Date and Time](#date-and-time)
    - [Event](#event)
    - [Logging](#logging)
    - [E-commerce](#e-commerce)
    - [PDF](#pdf)
    - [Office](#office)
    - [Database](#database)
    - [Migrations](#migrations)
    - [NoSQL](#nosql)
    - [Queue](#queue)
    - [Search](#search)
    - [Command Line](#command-line)
    - [Authentication and Authorization](#authentication-and-authorization)
    - [Markup](#markup)
    - [Strings](#strings)
    - [Numbers](#numbers)
    - [Filtering and Validation](#filtering-and-validation)
    - [API](#api)
    - [Caching](#caching)
    - [Data Structure and Storage](#data-structure-and-storage)
    - [Notifications](#notifications)
    - [Deployment](#deployment)
    - [Internationalisation and Localisation](#internationalisation-and-localisation)
    - [Third Party APIs](#third-party-apis)
    - [Extensions](#extensions)
    - [Miscellaneous](#miscellaneous)
- [Software](#software)
    - [PHP Installation](#php-installation)
    - [Development Environment](#development-environment)
    - [Virtual Machines](#virtual-machines)
    - [Integrated Development Environment](#integrated-development-environment)
    - [Web Applications](#web-applications)
    - [Infrastructure](#infrastructure)
- [Resources](#resources)
    - [PHP Websites](#php-websites)
    - [Other Websites](#other-websites)
    - [PHP Books](#php-books)
    - [PHP Videos](#php-videos)
    - [PHP Reading](#php-reading)
    - [PHP Internals Reading](#php-internals-reading)
- [Contributing](#contributing)

## Dependency Management
*Libraries for dependency and package management.*

* [Climb](https://github.com/vinkla/climb) - A Composer version manager tool.
* [Composer Installers](https://github.com/composer/installers) - A  multi framework Composer library installer.
* [Composer](https://getcomposer.org/)/[Packagist](https://packagist.org/) - A package and dependency manager.
* [Melody](http://melody.sensiolabs.org/) - A tool to build one file Composer scripts.
* [Pickle](https://github.com/FriendsOfPHP/pickle) - A PHP extension installer.

## Dependency Management Extras
*Extras related to dependency management.*

* [Composed](https://github.com/joshdifabio/composed) - A library to parse your project's Composer environment at runtime.
* [Composer Checker](https://github.com/silpion/composer-checker) - A tool to validate Composer configurations.
* [Composer Merge Plugin](https://github.com/wikimedia/composer-merge-plugin) - A composer plugin to merge several composer.json files.
* [Composition](https://github.com/bamarni/composition) - A library to check your Composer environment at runtime.
* [NameSpacer](https://github.com/ralphschindler/Namespacer) - A library to convert from underscores to namespaces.
* [Patch Installer](https://github.com/goatherd/patch-installer) - A library to install patches using Composer.
* [Prestissimo](https://github.com/hirak/prestissimo) - A composer plugin which enables parallel install process.
* [Satis](https://github.com/composer/satis) - A static Composer repository generator.
* [Toran Proxy](https://toranproxy.com) - A static Composer repository and proxy.

## Frameworks
*Web development frameworks.*

* [Aura PHP](http://auraphp.com/) - A framework of independent components.
* [CakePHP](http://cakephp.org/) - A rapid application development framework (CP).
* [Laravel 5](https://laravel.com/) - Another PHP framework (L5).
* [Nette](https://nette.org) - Another framework comprised of individual components.
* [Phalcon](https://phalconphp.com/en/) - A framework implemented as a C extension.
* [PPI Framework 2](http://www.ppi.io) - An interoperability framework.
* [Symfony 2](http://symfony.com/) - A framework comprised of individual components (SF2).
* [Yii2](https://github.com/yiisoft/yii2/) - Another PHP framework.
* [Zend Framework 2](http://framework.zend.com) - Another framework comprised of individual components (ZF2).

## Framework Extras
*Extras related to web development frameworks.*

* [CakePHP CRUD](https://github.com/friendsofcake/crud) - A Rapid Application Development (RAD) plugin for CakePHP.
* [Knp RAD Bundle](http://rad.knplabs.com/) - A Rapid Application Development (RAD) bundle for Symfony 2.
* [Symfony CMF](https://github.com/symfony-cmf/symfony-cmf) - A Content Management Framework to create custom CMS.

## Components
*Standalone components from web development frameworks and development groups.*

* [CakePHP Plugins](http://plugins.cakephp.org/) - A directory of CakePHP plugins.
* [Hoa Project](http://hoa-project.net/En/) - Another package of PHP components.
* [League of Extraordinary Packages](https://thephpleague.com/) - A PHP package development group.
* [Symfony2 Components](http://symfony.com/doc/master/components/index.html) - The components that make Symfony 2.
* [Zend Framework 2 Components](https://packages.zendframework.com/) - The components that make Zend Framework.

## Micro Frameworks
*Micro frameworks and routers.*

* [Bullet PHP](http://bulletphp.com/) - A micro framework for building REST APIs.
* [Lumen](https://lumen.laravel.com) - A micro-framework by Laravel.
* [Proton](https://github.com/alexbilbie/Proton) - A StackPHP compatible micro framework
* [Silex](http://silex.sensiolabs.org/) - A micro framework built around Symfony2 components.
* [Slim](http://www.slimframework.com/) - Another simple micro framework.

## Micro Framework Extras
*Extras related to micro frameworks and routers.*

* [Silex Skeleton](https://github.com/silexphp/Silex-Skeleton) - A project skeleton for Silex.
* [Silex Web Profiler](https://github.com/silexphp/Silex-WebProfiler) - A web debug toolbar for Silex.
* [Slim Skeleton](https://github.com/slimphp/Slim-Skeleton) - A skeleton for Slim.
* [Slim View](https://github.com/slimphp/Slim-Views) - A collection of custom views for Slim.

## Routers
*Libraries for handling application routing.*

* [Fast Route](https://github.com/nikic/FastRoute) - A fast routing library.
* [Klein](https://github.com/klein/klein.php) - A flexible router.
* [Pux](https://github.com/c9s/Pux) - Another fast routing library.
* [Route](https://github.com/thephpleague/route) - A routing library built on top of Fast Route.

## Templating
*Libraries and tools for templating and lexing.*

* [Foil](https://github.com/FoilPHP/Foil) - Another native PHP templating library.
* [Lex](https://github.com/pyrocms/lex) - A lightweight template parser.
* [MtHaml](https://github.com/arnaud-lb/MtHaml) - A PHP implementation of the HAML template language.
* [Mustache](https://github.com/bobthecow/mustache.php) - A PHP implementation of the Mustache template language.
* [Phly Mustache](https://github.com/phly/phly_mustache) - Another PHP implementation of the Mustache template language.
* [PHPTAL](http://phptal.org/) - A PHP implementation of the [TAL](https://en.wikipedia.org/wiki/Template_Attribute_Language) templating language.
* [Plates](http://platesphp.com/) - A native PHP templating library.
* [Smarty](http://www.smarty.net/) - A template engine to complement PHP.
* [Twig](http://twig.sensiolabs.org/) - A comprehensive templating language.

## Static Site Generators
*Tools for pre-processing content to generate web pages.*

* [Couscous](http://couscous.io) - Couscous turns Markdown documentation into beautiful websites. It's GitHub Pages on steroids.
* [Phrozn](https://github.com/Pawka/phrozn) - Another tool that converts Textile, Markdown and Twig into HTML.
* [Sculpin](https://sculpin.io) - A tool that converts Markdown and Twig into static HTML.
* [Spress](http://spress.yosymfony.com) - An extensible tool that converts Markdown and Twig into HTML.

## HTTP
*Libraries for working with HTTP websites.*

* [Buzz](https://github.com/kriswallsmith/Buzz) - Another HTTP client.
* [Guzzle]( https://github.com/guzzle/guzzle) - A comprehensive HTTP client.
* [HTTPFul](https://github.com/nategood/httpful) - A chainable HTTP client.
* [PHP VCR](http://php-vcr.github.io/) - A library for recording and replaying HTTP requests.
* [Requests](https://github.com/rmccue/Requests) - A simple HTTP library.
* [Retrofit](https://github.com/tebru/retrofit-php) - A library to ease creation of REST API clients.

## Scraping
*Libraries for scraping websites.*

* [Embed](https://github.com/oscarotero/Embed) - An information extractor from any web service or page.
* [Goutte](https://github.com/FriendsOfPHP/Goutte) - A simple web scraper.
* [PHP Spider](https://github.com/mvdbos/php-spider) - A configurable and extensible PHP web spider.

## Middlewares
*Libraries for building application using middlewares.*

* [PSR7-Middlewares](https://github.com/oscarotero/psr7-middlewares) - Inspiring collection of handy middlewares.
* [Relay](https://github.com/relayphp/Relay.Relay) - A PHP 5.5 PSR-7 middleware dispatcher
* [Slim Middleware](https://github.com/slimphp/Slim-Middleware) - A collection of custom middleware for Slim.
* [Stack](https://github.com/stackphp) - A library of stackable middleware for Silex/Symfony.
* [zend-stratigility](https://github.com/zendframework/zend-stratigility) - Middleware for PHP built on top of PSR-7

## URL
*Libraries for parsing URLs.*

* [PHP Domain Parser](https://github.com/jeremykendall/php-domain-parser) - A domain suffix parser library.
* [Purl](https://github.com/jwage/purl) - A URL manipulation library.
* [sabre/uri](https://github.com/fruux/sabre-uri) - A functional URI manipulation library.
* [Uri](https://github.com/thephpleague/uri) - Another URL manipulation library.

## Email
*Libraries for sending and parsing email.*

* [CssToInlineStyles](https://github.com/tijsverkoyen/CssToInlineStyles) - A library to inline CSS in email templates.
* [Email Reply Parser](https://github.com/willdurand/EmailReplyParser) - An email reply parser library.
* [Email Validator](https://github.com/nojacko/email-validator) - A small email address validation library.
* [Fetch](https://github.com/tedious/Fetch) - An IMAP library.
* [Mautic](https://github.com/mautic/mautic) - Email marketing automation
* [PHPMailer](https://github.com/PHPMailer/PHPMailer) - Another mailer solution.
* [Stampie](https://github.com/henrikbjorn/Stampie) - A library for email services such as [SendGrid](http://sendgrid.com), [PostMark](https://postmarkapp.com), [MailGun](http://www.mailgun.com) and [Mandrill](http://www.mandrill.com).
* [SwiftMailer](http://swiftmailer.org/) - A mailer solution.

## Files
*Libraries for file manipulation and MIME type detection.*

* [Apache MIME Types](https://github.com/dflydev/dflydev-apache-mime-types) - A library that parses Apache MIME types.
* [Canal](https://github.com/dflydev/dflydev-canal) - A library to determine internet media types.
* [CSV](https://github.com/thephpleague/csv) - A CSV data manipulation library.
* [Ferret](https://github.com/versionable/Ferret) - A MIME detection library.
* [Flysystem](https://github.com/thephpleague/Flysystem) - Another filesystem abstraction layer.
* [Gaufrette](https://github.com/KnpLabs/Gaufrette) - A filesystem abstraction layer.
* [Hoa Mime](https://github.com/hoaproject/Mime) - Another MIME detection library.
* [Lurker](https://github.com/henrikbjorn/Lurker) - A resource tracking library.
* [PHP FFmpeg](https://github.com/PHP-FFmpeg/PHP-FFmpeg/) - A wrapper for the [FFmpeg](http://www.ffmpeg.org/) video library.

## Streams
*Libraries for working with streams.*

* [Streamer](https://github.com/fzaninotto/Streamer) - A simple object-orientated stream wrapper library.

## Dependency Injection
*Libraries that implement the dependency injection design pattern.*

* [Acclimate](https://github.com/jeremeamia/acclimate-container) - A common interface to dependency injection containers and service locators.
* [Auryn](https://github.com/rdlowrey/Auryn) - A recursive dependency injector.
* [Container](https://github.com/thephpleague/container) - Another flexible dependency injection container.
* [PHP-DI](http://php-di.org/) - A dependency injection container that supports autowiring.
* [Pimple](http://pimple.sensiolabs.org/) - A tiny dependency injection container.
* [Symfony DI](https://github.com/symfony/dependency-injection) - A dependency injection container component (SF2).

## Imagery
*Libraries for manipulating images.*

* [Color Extractor](https://github.com/thephpleague/color-extractor) - A library for extracting colours from images.
* [GIF Creator](https://github.com/Sybio/GifCreator) - A library to create GIF animations from multiple images.
* [GIF Frame Extractor](https://github.com/Sybio/GifFrameExtractor) - A library to extract GIF animation frame information.
* [Glide](https://github.com/thephpleague/glide) - An on-demand image manipulation library.
* [Image Hash](https://github.com/jenssegers/imagehash) - A library for generating perceptual image hashes.
* [Image Optimizer](https://github.com/psliwa/image-optimizer) - A library for optimizing images.
* [Image With Text](https://github.com/nmcteam/image-with-text) - A library for embedding text into images.
* [Imagine](http://imagine.readthedocs.org/en/latest/index.html) - An image manipulation library.
* [Intervention Image](https://github.com/Intervention/image) - Another image manipulation library.
* [PHP Image Workshop](https://github.com/Sybio/ImageWorkshop) - Another image manipulation library.

## Testing
*Libraries for testing codebases and generating test data.*

* [Alice](https://github.com/nelmio/alice) - An expressive fixture generation library.
* [AspectMock](https://github.com/Codeception/AspectMock) - A mocking framework for PHPUnit/Codeception.
* [Atoum](https://github.com/atoum/atoum) - A simple testing library.
* [Behat](http://docs.behat.org/en/v2.5/) - A behaviour driven development (BDD) testing framework.
* [Codeception](https://github.com/Codeception/Codeception) - A full stack testing framework.
* [DBUnit](https://github.com/sebastianbergmann/dbunit) - A database testing library for PHPUnit.
* [Faker](https://github.com/fzaninotto/Faker) - A fake data generator library.
* [HTTP Mock](https://github.com/InterNations/http-mock) - A library for mocking HTTP requests in unit tests.
* [Kahlan](https://github.com/crysalead/kahlan) - Full stack Unit/BDD testing framework with built-in stub, mock and code-coverage support.
* [Mink](http://mink.behat.org/en/latest/) - Web acceptance testing.
* [Mockery](https://github.com/padraic/mockery) - A mock object library for testing.
* [ParaTest](https://github.com/brianium/paratest) - A parallel testing library for PHPUnit.
* [Peridot](https://github.com/peridot-php/peridot) - An event driven test framework.
* [Phake](https://github.com/mlively/Phake) - Another mock object library for testing.
* [Pho](https://github.com/danielstjules/pho) - Another behaviour driven development testing framework.
* [PHPSpec](https://github.com/phpspec/phpspec) - A design by specification unit testing library.
* [PHPUnit](https://github.com/sebastianbergmann/phpunit) - A unit testing framework.
* [Prophecy](https://github.com/phpspec/prophecy) - A highly opinionated mocking framework.
* [Samsui](https://github.com/mauris/samsui) - Another fake data generator library.
* [VFS Stream](https://github.com/mikey179/vfsStream) - A virtual filesystem stream wrapper for testing.
* [VFS](https://github.com/adlawson/php-vfs) - Another virtual filesystem for testing.

## Continuous Integration
*Libraries and applications for continuous integration.*

* [GitlabCi](https://about.gitlab.com/gitlab-ci/) - Let GitLab CI test, build, deploy your code. TravisCi like.
* [Jenkins](https://jenkins.io/index.html) - A continous integration platform with [PHP support](http://jenkins-php.org/index.html).
* [JoliCi](https://github.com/jolicode/JoliCi) - A continuous integration client written in PHP and powered by Docker.
* [PHPCI](https://www.phptesting.org/) - An open source continuous integration platform for PHP.
* [SemaphoreCI](https://semaphoreci.com/) - A continuous integration platform for open source and private projects.
* [Shippable](https://app.shippable.com/) - A docker based continious integration platform for open source and private projects.
* [Sismo](http://sismo.sensiolabs.org/) - A continuous testing server library.
* [Travis CI](https://travis-ci.org/) - A continuous integration platform.
* [Wercker](http://wercker.com/) - A continuous integration platform

## Documentation
*Libraries for generating project documentation.*

* [APIGen](https://github.com/apigen/apigen) - Another API documentation generator.
* [daux.io](https://github.com/justinwalsh/daux.io) - A documentation generator which uses Markdown files.
* [PHP Documentor 2](https://github.com/phpDocumentor/phpDocumentor2) - A documentation generator.
* [phpDox](http://phpdox.de/) - A documentation generator for PHP projects (that is not limited to API documentation).
* [Sami](https://github.com/FriendsOfPHP/Sami) - An API documentation generator.

## Security
*Libraries for generating secure random numbers, encrypting data and scanning for vulnerabilities.*

* [Halite](https://paragonie.com/project/halite) - A simple library for encryption using [libsodium](https://github.com/jedisct1/libsodium).
* [HTML Purifier](https://github.com/ezyang/htmlpurifier) - A standards compliant HTML filter.
* [IniScan](https://github.com/psecio/iniscan) - A tool that scans PHP INI files for security.
* [Optimus](https://github.com/jenssegers/optimus) - Id obfuscation based on Knuth's multiplicative hashing method.
* [PHP Encryption](https://github.com/defuse/php-encryption) - Secure PHP Encryption Library.
* [PHP IDS](https://github.com/PHPIDS/PHPIDS) - A structured PHP security layer.
* [PHP SSH](https://github.com/Herzult/php-ssh) - An experimental object orientated SSH wrapper library.
* [PHPSecLib](http://phpseclib.sourceforge.net/) - A pure PHP secure communications library.
* [RandomLib](https://github.com/ircmaxell/RandomLib) - A library for generating random numbers and strings.
* [SecurityMultiTool](https://github.com/padraic/SecurityMultiTool) - A PHP security library.
* [SensioLabs Security Check](https://security.sensiolabs.org/) - A web tool to check your Composer dependencies for security advisories.
* [TCrypto](https://github.com/timoh6/TCrypto) - A simple encrypted key-value storage library.
* [True Random](https://github.com/pixeloution/true-random) - A library that generates random numbers using [www.random.org](https://www.random.org/).
* [VAddy](http://vaddy.net) - A continuous security testing platform for web applications.
* [Zed](https://www.owasp.org/index.php/OWASP_Zed_Attack_Proxy_Project) - An integrated penetration testing tool for web applications.

## Passwords
*Libraries and tools for working with and storing passwords.*

* [GenPhrase](https://github.com/timoh6/GenPhrase) - A library for generating secure random passphrases.
* [Password Compat](https://github.com/ircmaxell/password_compat) - A compatibility library for the new PHP 5.5 password functions.
* [Password Policy](https://github.com/ircmaxell/password-policy) - A password policy library for PHP and JavaScript.
* [Password Validator](https://github.com/jeremykendall/password-validator) - A library for validating and upgrading password hashes.
* [Password-Generator](https://github.com/hackzilla/password-generator) - PHP library to generate random passwords.
* [PHP Password Lib](https://github.com/ircmaxell/PHP-PasswordLib) - A library for generating and validating passwords.
* [phpass](http://www.openwall.com/phpass/) - A portable password hashing framework.
* [Zxcvbn PHP](https://github.com/bjeavons/zxcvbn-php) - A realistic PHP password strength estimate library based on Zxcvbn JS.

## Code Analysis
*Libraries and tools for analysing, parsing and manipulating codebases.*

* [Athletic](https://github.com/polyfractal/athletic) - An annotation based benchmark framework.
* [Code Climate](https://codeclimate.com) - An automated code review.
* [Dissect](https://github.com/jakubledl/dissect) - A set of tools for lexical and syntactical analysis.
* [Exakat](http://www.exakat.io) - A static analysis engine for PHP.
* [GrumPHP](https://github.com/phpro/grumphp) - A composer plugin to defend code quality.
* [Mondrian](https://github.com/Trismegiste/Mondrian) - A code analysis tool using Graph Theory.
* [PHP Analyser](https://github.com/scrutinizer-ci/php-analyzer) - A library for analysing PHP code to find bugs and errors.
* [PHP Code Sniffer](https://github.com/squizlabs/PHP_CodeSniffer) - A library that detects PHP, CSS and JS coding standard violations.
* [PHP CS Fixer](https://github.com/FriendsOfPHP/PHP-CS-Fixer) - A coding standards fixer library.
* [PHP Manipulator](https://github.com/schmittjoh/php-manipulator) - A library for analysing and modifying PHP Source Code.
* [PHP Mess Detector](https://phpmd.org/) - A library that scans code for bugs, sub-optimal code, unused parameters and more.
* [PHP Metrics](https://github.com/phpmetrics/PhpMetrics) - A static metric library.
* [PHP Parser](https://github.com/nikic/PHP-Parser) - A PHP parser written in PHP.
* [PHP Refactoring Browser](https://github.com/QafooLabs/php-refactoring-browser) - A command line utility for refactoring PHP code.
* [PHP Semantic Versioning Checker](https://github.com/tomzx/php-semver-checker) - A command line utility that compares two source sets and determines the appropriate semantic versioning to apply.
* [PHPCheckstyle](https://github.com/PHPCheckstyle/phpcheckstyle) - A tool to help adhere to certain coding conventions.
* [PHPCPD](https://github.com/sebastianbergmann/phpcpd) - A library that detects copied and pasted code.
* [PhpDependencyAnalysis](https://github.com/mamuz/PhpDependencyAnalysis) - A tool to create customisable dependency graphs.
* [PHPLOC](https://github.com/sebastianbergmann/phploc) - A tool for quickly measuring the size of a PHP project.
* [PHPQA](https://github.com/EdgedesignCZ/phpqa) - A tool for running QA tools (phploc, phpcpd, phpcs, pdepend, phpmd, phpmetrics).
* [PHPPHP](https://github.com/ircmaxell/PHPPHP) - A PHP VM implementation in PHP.
* [PHPSandbox](https://github.com/fieryprophet/php-sandbox) - A PHP sandbox environment.
* [Scrutinizer](https://scrutinizer-ci.com/) - A web tool to scrutinise PHP code.
* [UBench](https://github.com/devster/ubench) - A simple micro benchmark library.

## Architectural
*Libraries related to design patterns, programming approaches and ways to organize code.*

* [Compose](https://github.com/igorw/compose) - A function composition library.
* [Design Patterns PHP](https://github.com/domnikl/DesignPatternsPHP) - A repository of software patterns implemented in PHP.
* [Finite](http://yohan.giarel.li/Finite/) - A simple PHP finite state machine.
* [Functional PHP](https://github.com/lstrojny/functional-php) - A functional programming library.
* [Galapagos](https://github.com/endel/galapagos) - Evolutionary language transformation.
* [Iter](https://github.com/nikic/iter) - A library that provides iteration primitives using generators.
* [Monad PHP](https://github.com/ircmaxell/monad-php) - A simple Monad library.
* [Patchwork](http://antecedent.github.io/patchwork/) - A library for redefining userland functions.
* [PHP Option](https://github.com/schmittjoh/php-option) - An option type library.
* [Pipeline](https://github.com/thephpleague/pipeline) - A pipeline pattern implementation.
* [Ruler](https://github.com/bobthecow/Ruler) - A simple stateless production rules engine.

## Debugging and Profiling
*Libraries and tools for debugging and profiling code.*

* [APM](http://pecl.php.net/package/APM) - Monitoring extension collecting errors and statistics into SQLite/MySQL/StatsD.
* [Barbushin PHP Console](https://github.com/barbushin/php-console) - Another web debugging console using Google Chrome.
* [Blackfire.io](https://blackfire.io) - A low-overhead code profiler.
* [Kint](https://github.com/raveren/kint) - A debugging and profiling tool.
* [PHP Console](https://github.com/Seldaek/php-console) - A web debugging console.
* [PHP Debug Bar](http://phpdebugbar.com/) - A debugging toolbar.
* [PHPBench](https://github.com/phpbench/phpbench) - A benchmarking Framework.
* [PHPDBG](http://phpdbg.com/) - An interactive PHP debugger.
* [Tracy](https://github.com/nette/tracy) - A simple error detection, logging and time measuring library.
* [xDebug](https://github.com/xdebug/xdebug) - A debug and profile tool for PHP.
* [XHProf](https://github.com/phacility/xhprof) - A profiling tool originally developed by Facebook.
* [Z-Ray](http://www.zend.com/en/products/server/z-ray) - A debug and profile tool for Zend Server.

## Build Tools
*Project build and automation tools.*

* [Bob](https://github.com/CHH/bob) - A simple project automation tool.
* [Box](https://github.com/box-project/box2) - A utility to build PHAR files.
* [Phake](https://github.com/jaz303/phake) - A rake PHP clone library.
* [Phing](http://www.phing.info/) - A PHP project build system inspired by Apache Ant.

## Task Runners
*Libraries for automating and running tasks.*

* [Bldr](http://bldr.io/) - A PHP Task runner built on Symfony components.
* [Jobby](https://github.com/jobbyphp/jobby) - A PHP cron job manager without modifying crontab.
* [Robo](https://github.com/Codegyre/Robo) - A PHP Task runner with object-orientated configurations.
* [Task](http://taskphp.github.io/) - A pure PHP task runner inspired by Grunt and Gulp.

## Navigation
*Tools for building navigation structures.*

* [Cartographer](https://github.com/tackk/cartographer) - A sitemap generation library.
* [KnpMenu](https://github.com/KnpLabs/KnpMenu) - A menu library.

## Asset Management
*Tools for managing, compressing and minifying website assets.*

* [Assetic](https://github.com/kriswallsmith/assetic) - An asset manager pipeline library.
* [JShrink](https://github.com/tedious/JShrink) - A JavaScript minifier library.
* [Munee](https://github.com/meenie/munee) - An asset optimiser library.
* [Pipe](https://github.com/CHH/pipe) - Another asset manager pipeline library.
* [Puli](https://github.com/puli/repository) - A library for determining assets absolute paths.

## Geolocation
*Libraries for geocoding addresses and working with latitudes and longitudes.*

* [GeoCoder](http://geocoder-php.org/) - A geocoding library.
* [GeoJSON](https://github.com/jmikola/geojson) - A GeoJSON implementation.
* [GeoTools](https://github.com/thephpleague/geotools) - A library of geo-related tools.
* [PHPGeo](https://github.com/mjaschen/phpgeo) - A simple geo library.

## Date and Time
*Libraries for working with dates and times.*

* [CalendR](http://yohan.giarel.li/CalendR/) - A calendar management library.
* [Carbon](https://github.com/briannesbitt/Carbon) - A simple DateTime API extension.
* [ExpressiveDate](https://github.com/jasonlewis/expressive-date) - Another DateTime API extension.
* [Moment.php](https://github.com/fightbulc/moment.php) - Moment.js inspired PHP DateTime handler with i18n support.

## Event
*Libraries that are event-driven or implement non-blocking event loops.*

* [Amp](https://github.com/amphp/amp) - An event driven non-blocking I/O library.
* [Broadway](https://github.com/qandidate-labs/broadway) - An event source and CQRS library.
* [Cake Event](https://github.com/cakephp/event) - An event dispatcher library (CP).
* [Elephant.io](https://github.com/Wisembly/Elephant.io) - Yet another web socket library.
* [Evenement](https://github.com/igorw/evenement) - An event dispatcher library.
* [Event](https://github.com/thephpleague/event) - An event library with a focus on domain events.
* [Hoa EventSource](https://github.com/hoaproject/Eventsource) - An event source library.
* [Hoa WebSocket](https://github.com/hoaproject/Websocket) - Another web socket library.
* [Icicle](https://github.com/icicleio/icicle) - An asynchronous library with coroutines, non-blocking I/O, and multithreading.
* [Prooph Event Store](https://github.com/prooph/event-store) - An event source component to persist event messages
* [Ratchet](https://github.com/ratchetphp/Ratchet) - A web socket library.
* [React](https://github.com/reactphp/react) - An event driven non-blocking I/O library.
* [Rx.PHP](https://github.com/asm89/Rx.PHP) - A reactive extension library.

## Logging
*Libraries for generating and working with log files.*

* [Analog](https://github.com/jbroadway/analog) - A closure-based micro logging package.
* [KLogger](https://github.com/katzgrau/KLogger) - An easy-to-use PSR-3 compliant logging class.
* [Monolog](https://github.com/Seldaek/monolog) - A comprehensive logger.

## E-commerce
*Libraries and applications for taking payments and building online e-commerce stores.*

* [Money](https://github.com/moneyphp/money) - A PHP implementation of Fowler's money pattern.
* [OmniPay](https://github.com/thephpleague/omnipay) - A framework agnostic multi-gateway payment processing library.
* [Payum](https://github.com/payum/payum) - A payment abstraction library.
* [Sebastian Money](https://github.com/sebastianbergmann/money) - Another library for working with monetary values.
* [Shopware](https://github.com/shopware/shopware) - Highly customizable e-commerce software
* [Swap](https://github.com/florianv/swap) - An exchange rates library.
* [Sylius](http://sylius.org/) - An open source e-commerce solution.
* [Thelia](http://thelia.net/) - Another open source e-commerce solution.

## PDF
*Libraries and software for working with PDF files.*

* [Dompdf](https://github.com/dompdf/dompdf) - A HTML to PDF converter.
* [PHPPdf](https://github.com/psliwa/PHPPdf) - A library for generating PDFs and images from XML.
* [Snappy](https://github.com/KnpLabs/snappy) - A PDF and image generation library.
* [WKHTMLToPDF](https://github.com/wkhtmltopdf/wkhtmltopdf) - A tool to convert HTML to PDF.

## Office
*Libraries for working with office suite documents.*

* [ExcelAnt](https://github.com/Wisembly/ExcelAnt) - A library for manipulating Microsoft Excel documents.
* [PHPExcel](https://github.com/PHPOffice/PHPExcel) - A library for working with Microsoft Excel documents.
* [PHPPowerPoint](https://github.com/PHPOffice/PHPPresentation) - A library for working with Microsoft PowerPoint Presentations.
* [PHPWord](https://github.com/PHPOffice/PHPWord) - A library for working with Microsoft Word documents.

## Database
*Libraries for interacting with databases using object-relational mapping (ORM) or datamapping techniques.*

* [Baum](https://github.com/etrepat/baum) - A nested set implementation for Eloquent.
* [Cake ORM](https://github.com/cakephp/orm) - Object-Relational Mapper, implemented using the DataMapper pattern (CP).
* [Doctrine Extensions](https://github.com/Atlantic18/DoctrineExtensions) - A collection of Doctrine behavioural extensions.
* [Doctrine](http://www.doctrine-project.org/) - A comprehensive DBAL and ORM.
* [Eloquent](https://github.com/illuminate/database) - A simple ORM (L5).
* [LazyRecord](https://github.com/c9s/LazyRecord) - A fast ORM designed for simplicity, extendability and performance.
* [Pomm](https://github.com/chanmix51/Pomm) - An Object Model Manager for PostgreSQL.
* [Propel](http://propelorm.org/) - A fast ORM, migration library and query builder.
* [ProxyManager](https://github.com/Ocramius/ProxyManager) - A set of utilities to generate proxy objects for data mappers.
* [RedBean](http://redbeanphp.com/index.php) - A lightweight, configuration-less ORM.
* [Spot2](https://github.com/vlucas/spot2) - A MySQL datamapper ORM.

## Migrations
Libraries to help manage database schemas and migrations.

* [Doctrine Migrations](http://docs.doctrine-project.org/projects/doctrine-migrations/en/latest/toc.html) - A migration library for Doctrine.
* [Migrations](https://github.com/icomefromthenet/Migrations) - A migration management library.
* [Phinx](https://github.com/robmorgan/phinx) - Another database migration library.
* [PHPMig](https://github.com/davedevelopment/phpmig) - Another migration management library.
* [Ruckusing](https://github.com/ruckus/ruckusing-migrations) - Database migrations for PHP ala ActiveRecord Migrations with support for MySQL, Postgres, SQLite.

## NoSQL
*Libraries for working with "NoSQL" backends.*

* [Monga](https://github.com/thephpleague/monga) - A MongoDB abstraction library.
* [MongoQB](https://github.com/alexbilbie/MongoQB) - A MongoDB query builder library.
* [PHPMongo](https://github.com/sokil/php-mongo) - A MongoDB ORM.
* [Predis](https://github.com/nrk/predis) - A feature complete Redis library.

## Queue
*Libraries for working with event and task queues.*

* [Bernard](https://github.com/bernardphp/bernard) - A multibackend abstraction library.
* [Pheanstalk](https://github.com/pda/pheanstalk) - A Beanstalkd client library.
* [PHP AMQP](https://github.com/php-amqplib/php-amqplib) - A pure PHP AMQP library.
* [Tarantool Queue](https://github.com/tarantool-php/queue) - PHP bindings for Tarantool Queue.
* [Thumper](https://github.com/php-amqplib/Thumper) - A RabbitMQ pattern library.

## Search
*Libraries and software for indexing and performing search queries on data.*

* [Elastica](https://github.com/ruflin/Elastica) - A client library for ElasticSearch.
* [ElasticSearch PHP](https://github.com/elastic/elasticsearch-php) - The official client library for [ElasticSearch](https://www.elastic.co/).
* [Solarium](http://www.solarium-project.org/) - A client library for [Solr](http://lucene.apache.org/solr/).
* [Sphinx Search](https://github.com/ripaclub/sphinxsearch) - Sphinx Search library provides SphinxQL indexing and searching features
* [SphinxQL query builder](http://foolcode.github.io/SphinxQL-Query-Builder/) - A query library for the [Sphinx](http://sphinxsearch.com/) search engine.

## Command Line
*Libraries related to the command line.*

* [Boris](https://github.com/borisrepl/boris) - A tiny PHP REPL.
* [Cilex](https://github.com/Cilex/Cilex) - A micro framework for building command line tools.
* [CLI Menu](https://github.com/php-school/cli-menu) - A library for building CLI menus.
* [CLIFramework](https://github.com/c9s/CLIFramework) - A command-line framework supports zsh/bash completion generation, subcommands and option constraints. It also powers phpbrew.
* [CLImate](https://github.com/thephpleague/climate) - A library for outputting colours and special formatting.
* [Commando](https://github.com/nategood/commando) - Another simple command line opt parser.
* [Cron Expression](https://github.com/mtdowling/cron-expression) - A library to calculate cron run dates.
* [GetOpt](https://github.com/ulrichsg/getopt-php) - A command line opt parser.
* [GetOptionKit](https://github.com/c9s/GetOptionKit) - Another command line opt parser.
* [Hoa Console](https://github.com/hoaproject/Console) - Another command line library.
* [OptParse](https://github.com/CHH/optparse) - Another command line opt parser.
* [Pecan](https://github.com/mcrumm/pecan) - An event-driven, non-blocking shell.
* [PsySH](https://github.com/bobthecow/psysh) - Another PHP REPL.
* [ShellWrap](https://github.com/MrRio/shellwrap) - A simple command line wrapper library.
* [Shunt](https://github.com/thephpleague/shunt) - A library for running commands in parallel on multiple remote machines.

## Authentication and Authorization
*Libraries for implementing user authentication and authorization.*

* [Hawk](https://github.com/dflydev/dflydev-hawk) - A Hawk HTTP authentication library.
* [HybridAuth](https://github.com/hybridauth/hybridauth) - An open source social sign on library.
* [Json Web Token](https://github.com/lcobucci/jwt) - Json Tokens to authenticate and transmit information.
* [Lock](https://github.com/BeatSwitch/lock) - A library for implementing Access Control Lists (ACL) systems.
* [OAuth 1.0 Client](https://github.com/thephpleague/oauth1-client) - An OAuth 1.0 client library.
* [OAuth 2.0 Client](https://github.com/thephpleague/oauth2-client) - An OAuth 2.0 client library.
* [OAuth2 Server](http://bshaffer.github.io/oauth2-server-php-docs/) - Another OAuth2 server implementation.
* [OAuth2 Server](http://oauth2.thephpleague.com/) - An OAuth2 authentication server, resource server and client library.
* [Opauth](https://github.com/opauth/opauth) - A multi-provider authentication framework.
* [PHP oAuthLib](https://github.com/Lusitanian/PHPoAuthLib) - Another OAuth library.
* [Sentinel Social](https://cartalyst.com/manual/sentinel-social/2.0) - A library for social network authentication.
* [Sentinel](https://cartalyst.com/manual/sentinel/2.0) - A framework agnostic authentication & authorisation library.
* [TwitterOAuth](https://github.com/ruudk/twitteroauth) - A Twitter OAuth library.
* [TwitterSDK](https://github.com/lyrixx/twitter-sdk) - A fully tested Twitter SDK.

## Markup
*Libraries for working with markup.*

* [Cebe Markdown](https://github.com/cebe/markdown) - An fast and extensible Markdown parser.
* [Ciconia](https://github.com/kzykhys/Ciconia) - Another Markdown parser that supports Github flavoured Markdown.
* [CommonMark PHP](https://github.com/thephpleague/commonmark) - A Markdown parser which supports the full [CommonMark spec](http://spec.commonmark.org/).
* [Decoda](https://github.com/milesj/decoda) - A lightweight markup parser library.
* [Emoji](https://github.com/heyupdate/Emoji) - A library that converts unicode characters and names into emoji images.
* [HTML to Markdown](https://github.com/thephpleague/html-to-markdown) - Converts HTML into Markdown.
* [HTML5 PHP](https://github.com/Masterminds/html5-php) - An HTML5 parser and serializer library.
* [Parsedown](https://github.com/erusev/parsedown) - Another Markdown parser.
* [PHP Markdown](https://github.com/michelf/php-markdown) - A Markdown parser.

## Strings
*Libraries for parsing and manipulating strings.*

* [Agent](https://github.com/jenssegers/agent) - A PHP desktop/mobile user agent parser, based on Mobiledetect.
* [ANSI to HTML5](https://github.com/sensiolabs/ansi-to-html) - An ANSI to HTML5 converter library.
* [Color Jizz](https://github.com/mikeemoo/ColorJizz-PHP) - A library for manipulating and converting colours.
* [Device Detector](https://github.com/piwik/device-detector) - Another library for parsing user agent strings.
* [Hoa String](https://github.com/hoaproject/String) - Another UTF-8 string library.
* [Mobile-Detect](https://github.com/serbanghita/Mobile-Detect) - A lightweight PHP class for detecting mobile devices (including tablets).
* [Patchwork UTF-8](https://github.com/nicolas-grekas/Patchwork-UTF8) - A portable library for working with UTF-8 strings.
* [Slugify](https://github.com/cocur/slugify) - A library to convert strings to slugs.
* [SQL Formatter](https://github.com/jdorn/sql-formatter/) - A library for formatting SQL statements.
* [Stringy](https://github.com/danielstjules/Stringy) - A string manipulation library with multibyte support.
* [Text](https://github.com/kzykhys/Text) - A text manipulation library.
* [UA Parser](https://github.com/tobie/ua-parser/tree/master/php) - A library for parsing user agent strings.
* [URLify](https://github.com/jbroadway/urlify) - A PHP port of Django's URLify.js.
* [UUID](https://github.com/ramsey/uuid) - A library for generating UUIDs.

## Numbers
*Libraries for working with numbers.*

* [ByteUnits](https://github.com/gabrielelana/byte-units) - A library to parse, format and convert byte units in binary and metric systems.
* [LibPhoneNumber for PHP](https://github.com/giggsey/libphonenumber-for-php) - A PHP implementation of Google's phone number handling library.
* [Math](https://github.com/moontoast/math) - A library for working with large numbers.
* [Numbers PHP](https://github.com/powder96/numbers.php) - A library for working with numbers.
* [PHP Conversion](https://github.com/Crisu83/php-conversion) - Another library for converting between units of measure.
* [PHP Units of Measure](https://github.com/triplepoint/php-units-of-measure) - A library for converting between units of measure.

## Filtering and Validation
*Libraries for filtering and validating data.*

* [Cake Validation](https://github.com/cakephp/validation) - Another validation library (CP).
* [DMS Filter](https://github.com/rdohms/DMS-Filter) - An annotation filtering library.
* [Filterus](https://github.com/ircmaxell/filterus) - A simple PHP filtering library.
* [ISO-codes](https://github.com/ronanguilloux/IsoCodes) - A library for validating various ISO and ZIP codes (IBAN, SWIFT/BIC, BBAN, VAT, SSN, UKNIN).
* [MetaYaml](https://github.com/romaricdrigon/MetaYaml) - A schema validation library that supports YAML, JSON and XML.
* [Respect Validation](https://github.com/Respect/Validation) - A simple validation library.
* [Upload](https://github.com/brandonsavage/Upload) - A library for handling file uploads and validation.
* [Valitron](https://github.com/vlucas/valitron) - Another validation library.
* [Volan](https://github.com/serkin/Volan) - Another simplified validation library.

## API
*Libraries and web tools for developing APIs.*

* [API Platform](https://api-platform.com ) - Expose in minutes an hypermedia REST API that embraces JSON-LD, Hydra format.
* [Apigility](https://github.com/zfcampus/zf-apigility-skeleton) - An API builder built with Zend Framework 2.
* [Drest](https://github.com/leedavis81/drest) - A library for exposing Doctrine entities as REST resource endpoints.
* [HAL](https://github.com/blongden/hal) - A Hypertext Application Language (HAL) builder library.
* [Hateoas](https://github.com/willdurand/Hateoas) - A HATEOAS REST web service library.
* [Negotiation](https://github.com/willdurand/Negotiation) - A content negotiation library.
* [Restler](https://github.com/Luracast/Restler) - A lightweight framework to expose PHP methods as RESTful web API.
* [wsdl2phpgenerator](https://github.com/wsdl2phpgenerator/wsdl2phpgenerator) - A tool to generate PHP classes from SOAP WSDL files.

## Caching
*Libraries for caching data.*

* [Alternative PHP Cache (APC)](http://php.net/manual/en/book.apc.php) - Open opcode cache for PHP.
* [APIx Cache](https://github.com/frqnck/apix-cache) - A thin PSR-6 cache wrapper to various caching backends emphasising cache tagging and indexing.
* [CacheTool](https://github.com/gordalina/cachetool) - A tool to clear APC/opcode caches from the command line.
* [Cake Cache](https://github.com/cakephp/cache) - A caching library (CP).
* [Doctrine Cache](https://github.com/doctrine/cache) - A caching library.
* [Stash](https://github.com/tedious/Stash) - Another library for caching.
* [Zend Cache](https://github.com/zendframework/zend-cache) - Another caching library (ZF2).

## Data Structure and Storage
*Libraries that implement data structure or storage techniques.*

* [Ardent](https://github.com/morrisonlevi/Ardent) - A library of data structures.
* [Cake Collection](https://github.com/cakephp/collection) - A simple collections library (CP).
* [Collections](https://github.com/italolelis/collections) - Collections Abstraction library for PHP.
* [Fractal](https://github.com/thephpleague/fractal) - A library for converting complex data structures to JSON output.
* [Ginq](https://github.com/akanehara/ginq) - Another PHP library based on .NET's LINQ.
* [JsonMapper](https://github.com/netresearch/jsonmapper) - A library that maps nested JSON structures onto PHP classes.
* [PHP Collections](https://github.com/schmittjoh/php-collection) - A simple collections library.
* [PINQ](https://github.com/TimeToogo/Pinq) - A PHP library based on .NET's LINQ (Language Integrated Query).
* [Serializer](https://github.com/schmittjoh/serializer) - A library for serialising and de-serialising data.
* [Totem](https://github.com/Wisembly/Totem) - A library to manage and create data changesets.
* [YaLinqo](https://github.com/Athari/YaLinqo) - Yet Another LINQ to Objects for PHP.
* [Zend Serializer](https://github.com/zendframework/zend-serializer) - Another library for serialising and de-serialising data (ZF2).

## Notifications
*Libraries for working with notification software.*

* [JoliNotif](https://github.com/jolicode/JoliNotif) - A cross-platform library for desktop notification (support for Growl, notify-send, toaster, etc)
* [Nod](https://github.com/filp/nod) - A notification library (e.g., Growl).
* [Notification Pusher](https://github.com/Ph3nol/NotificationPusher) - A standalone library for device push notifications.
* [Notificato](https://github.com/mac-cain13/notificato) - A library for handling push notifications.
* [Notificator](https://github.com/namshi/notificator) - A lightweight notification library.

## Deployment
*Libraries for project deployment.*

* [Deployer](https://github.com/deployphp/deployer) - A deployment tool.
* [Envoy](https://github.com/laravel/envoy) - A tool to run SSH tasks with PHP.
* [Plum](https://github.com/aerialls/Plum) - A deployer library.
* [Pomander](https://github.com/tamagokun/pomander) - A deployment tool for PHP applications.
* [Rocketeer](https://github.com/rocketeers/rocketeer) - A fast and easy deployer for the PHP world.

## Internationalisation and Localisation
*Libraries for Internationalization (I18n) and Localization (L10n).*

* [Aura Intl](https://github.com/auraphp/Aura.Intl)
* [Cake I18n](https://github.com/cakephp/i18n) - Message translation and localization for dates and numbers (CP)

## Third Party APIs
*Libraries for accessing third party APIs.*

* [Amazon Web Service SDK](https://github.com/aws/aws-sdk-php) - The official PHP AWS SDK library.
* [Campaign Monitor](http://campaignmonitor.github.io/createsend-php/) - The official Campaign Monitor PHP library.
* [Digital Ocean](https://github.com/toin0u/DigitalOcean) - A library to interface with the Digital Ocean API.
* [Dropbox SDK](https://github.com/dropbox/dropbox-sdk-php) - The official PHP Dropbox SDK library.
* [Github](https://github.com/dsyph3r/github-api3-php) - A library to interface with the Github API.
* [Mailgun](https://github.com/mailgun/mailgun-php) The official Mailgun PHP API.
* [PHP Github API](https://github.com/KnpLabs/php-github-api) - Another library to interface with the Github API.
* [S3 Stream Wrapper](https://github.com/gwkunze/S3StreamWrapper) - A stream wrapper library for Amazon S3.
* [Stripe](https://github.com/stripe/stripe-php) - The official Stripe PHP library.
* [Twilio](https://github.com/twilio/twilio-php) - The official Twilio PHP REST API.
* [Twitter OAuth](https://github.com/widop/twitter-oauth) - A library to interface with Twitter's OAuth workflow.
* [Twitter REST](https://github.com/widop/twitter-rest) - A library to interact with Twitter's REST API.

## Extensions
*Libraries to help build PHP extensions.*

* [PHP CPP](http://www.php-cpp.com/) - A C++ library for developing PHP extensions.
* [Zephir](https://github.com/phalcon/zephir) - A compiled language between PHP and C++ for developing PHP extensions.

## Miscellaneous
*Useful libraries or tools that don't fit in the categories above.*

* [Alias](https://github.com/fuelphp/alias) - A class aliasing library.
* [Annotations](https://github.com/doctrine/annotations) - An annotations library (part of Doctrine).
* [Cake Utility](https://github.com/cakephp/utility) - Utility classes such as Inflector, String, Hash, Security and Xml (CP).
* [Chief](https://github.com/adamnicholson/Chief) - A command bus library.
* [ClassPreloader](https://github.com/ClassPreloader/ClassPreloader) - A library for optimising autoloading.
* [Country List](https://github.com/umpirsky/country-list) - A list of all countries with names and ISO 3166-1 codes.
* [Embera](https://github.com/mpratt/Embera) - An Oembed consumer library.
* [Essence](https://github.com/essence/essence) - A library for extracting web media.
* [Flux](https://github.com/selvinortiz/flux) - A regular expression building library.
* [Graphviz](https://github.com/alexandresalome/graphviz) - A Graphviz library.
* [Hprose-PHP](https://github.com/hprose/hprose-php) - A very newbility RPC Library, support 25+ languages now.
* [JSON Lint](https://github.com/Seldaek/jsonlint) - A JSON lint utility.
* [JSONPCallbackValidator](https://github.com/willdurand/JsonpCallbackValidator) - A library for validating JSONP callbacks.
* [Jumper](https://github.com/kakawait/Jumper) - A remote service executor library.
* [LadyBug](https://github.com/raulfraile/Ladybug) - A dumper library.
* [Lambda PHP](https://github.com/igorw/lambda-php) - A Lambda calculus interpreter in PHP.
* [LiteCQRS](https://github.com/beberlei/litecqrs-php) - A CQRS (Command Query Responsibility Separation) library.
* [Metrics](https://github.com/beberlei/metrics) - A simple metrics API library.
* [Nmap](https://github.com/willdurand/nmap) - A PHP wrapper around [Nmap](https://nmap.org/).
* [Opengraph](https://github.com/euskadi31/Opengraph) - An opengraph library.
* [Pagerfanta](https://github.com/whiteoctober/Pagerfanta) - A pagination library.
* [PHP Expression](https://github.com/Kitano/php-expression) - A PHP expression language.
* [PHP PassBook](https://github.com/eymengunay/php-passbook) - A PHP library for iOS PassBook.
* [PHP-GPIO](https://github.com/ronanguilloux/php-gpio) - A library for playing with the Raspberry PI's GPIO pins.
* [PHPCR](https://github.com/phpcr/phpcr) - A PHP port of the Java Content Repository (JCR).
* [PHPStack](http://dunkels.com/adam/phpstack/) - A TCP/IP stack proof of concept written in PHP.
* [print_o](https://github.com/koriym/print_o) - An object graph visualizer.
* [Procrastinator](https://github.com/lstrojny/Procrastinator) - A library for running time consuming tasks.
* [Prooph Service Bus](https://github.com/prooph/service-bus) - Lightweight message bus supporting CQRS and Micro Services
* [RMT](https://github.com/liip/RMT) - A library for versioning and releasing software.
* [sabre/vobject](https://github.com/fruux/sabre-vobject) - A library for parsing VCard and iCalendar objects.
* [Slimdump](https://github.com/webfactory/slimdump) - An easy dumper tool for MySQL.
* [Spork](https://github.com/kriswallsmith/spork) - A process forking library.
* [Sslurp](https://github.com/EvanDotPro/Sslurp) - A library that makes dealing with SSL suck less.
* [SuperClosure](https://github.com/jeremeamia/super_closure) - A library that allows Closures to be serialized.
* [Symfony VarDumper](http://symfony.com/doc/current/components/var_dumper/introduction.html) - A variable dumper component (SF2).
* [Underscore](http://anahkiasen.github.io/underscore-php/) - A PHP port of the Underscore JS library.
* [Whoops](https://github.com/filp/whoops) - A pretty error handling library.

# Software
*Software for creating a development environment.*

## PHP Installation
*Tools to help install and manage PHP on your computer.*

* [HomeBrew PHP](https://github.com/Homebrew/homebrew-php) - A PHP tap for HomeBrew.
* [HomeBrew](http://brew.sh/) - A package manager for OSX.
* [PHP Brew](https://github.com/phpbrew/phpbrew) - A PHP version manager and installer.
* [PHP Build](https://github.com/php-build/php-build) - Another PHP version installer.
* [PHP Env](https://github.com/CHH/phpenv) - Another PHP version manager.
* [PHP OSX](http://php-osx.liip.ch/) - A PHP installer for OSX.
* [PHP Switch](https://github.com/jubianchi/phpswitch) - Another version manager.
* [VirtPHP](http://virtphp.org/) - A tool for creating and managing isolated PHP environments.

## Development Environment
*Software and tools for creating a sandboxed development environment.*

* [Ansible](https://www.ansible.com/) - A radically simple orchestration framework.
* [Phansible](http://phansible.com/) - A web tool for building PHP development virtual machines with Ansible.
* [Protobox](http://getprotobox.com/) - Another web tool for building PHP development virtual machines.
* [PuPHPet](https://puphpet.com/) - A web tool for building PHP development virtual machines.
* [Puppet](https://puppetlabs.com/) - A server automation framework and application.
* [Vagrant](https://www.vagrantup.com/) - A portable development environment utility.

## Virtual Machines
*Alternative PHP virtual machines.*

* [Hack](http://hacklang.org/) - A programming language for HHVM that interoperates seamlessly with PHP.
* [HHVM](https://github.com/facebook/hhvm) - A Virtual Machine, Runtime and JIT for PHP by Facebook.
* [HippyVM](https://github.com/hippyvm/hippyvm) - Another PHP virtual machine.

## Integrated Development Environment
*Integrated Development Environments with support for PHP.*

* [Eclipse for PHP Developers](https://www.eclipse.org/downloads/) - A PHP IDE based on the Eclipse platform.
* [Netbeans](https://netbeans.org) - An IDE with support for PHP and HTML5.
* [PhpStorm](http://www.jetbrains.com/phpstorm/) - A commercial PHP IDE.

## Web Applications
*Web-based applications and tools.*

* [3V4L](https://3v4l.org/) - An online PHP & HHVM shell.
* [DBV](http://dbv.vizuina.com/) - A database version control application.
* [PHP Queue](https://github.com/CoderKungfu/php-queue) - An application for managing queueing backends.
* [MailCatcher](https://github.com/sj26/mailcatcher) - A web tool for capturing and viewing emails.
* [Cachet](https://github.com/cachethq/cachet) - The open source status page system.
* [phpRedisAdmin](https://github.com/ErikDubbelboer/phpRedisAdmin) - A simple web interface to manage [Redis](http://redis.io/) databases.
* [phpPgAdmin](https://github.com/phppgadmin/phppgadmin) - A web-based administration tool for PostgreSQL.
* [phpMyAdmin](https://github.com/phpmyadmin/phpmyadmin) - A web interface for MySQL/MariaDB.
* [Adminer](https://www.adminer.org/) - Database management in a single PHP file.
* [Grav](https://github.com/getgrav/grav) - A modern flat-file CMS.

## Infrastructure
*Infrastructure for providing PHP applications and services.*

* [appserver.io](http://appserver.io/) - A multithreaded application server for PHP, written in PHP.
* [php-pm](https://github.com/php-pm/php-pm) - A process manager, supercharger and load balancer for PHP applications.

# Resources
Various resources, such as books, websites and articles, for improving your PHP development skills and knowledge.

## PHP Websites
*Useful PHP-related websites.*

* [Nomad PHP](https://nomadphp.com/) - A online PHP learning resource.
* [PHP Best Practices](https://phpbestpractices.org/) - A PHP best practice guide.
* [PHP FIG](http://www.php-fig.org/) - The PHP Framework Interoperability Group.
* [PHP Mentoring](http://phpmentoring.org/) - Peer to peer PHP mentorship organization.
* [PHP School](https://www.phpschool.io/) - Open Source Learning for PHP.
* [PHP Security](http://phpsecurity.readthedocs.org/en/latest/index.html) - A guide to PHP security.
* [PHP The Right Way](http://www.phptherightway.com/) - A PHP best practice quick reference guide.
* [PHP UG](http://php.ug) - A website to help people locate their nearest PHP user group (UG).
* [PHP Versions](http://phpversions.info/) - Lists which versions of PHP are available on several popular web hosts.
* [PHP Weekly](http://www.phpweekly.com/archive.html) - A weekly PHP newsletter.
* [PHPTrends](http://phptrends.com/) - An overview of fastest growing PHP libraries.
* [Securing PHP](http://securingphp.com/) - A newsletter about PHP security and library recommendations.
* [Seven PHP](http://7php.com/) - A website that interviews members of the PHP community.

## Other Websites
*Useful websites related to web development.*

* [Atlassian Git Tutorials](https://www.atlassian.com/git/) - A series of Git tutorials.
* [Hg Init](http://hginit.com/) - A series of Mercurial tutorials.
* [Semantic Versioning](http://semver.org/) - A website explaining semantic versioning.
* [Servers for Hackers](https://serversforhackers.com/) - A newsletter about server management.
* [The Open Web Application Security Project (OWASP)](https://www.owasp.org/index.php/Main_Page) - An open software security community.
* [WebSec IO](https://websec.io/) - A web security community resource.

## PHP Books
*Fantastic PHP-related books.*

* [Functional Programming in PHP](https://www.phparch.com/books/functional-programming-in-php/) - This book will show you how to leverage these new PHP5.3+ features by understanding functional programming principles
* [Grumpy PHPUnit](https://leanpub.com/grumpy-phpunit) - A book about unit testing with PHPUnit by Chris Hartjes.
* [Mastering Object-Orientated PHP](http://www.brandonsavage.net) - A book about object-orientated PHP by Brandon Savage.
* [Modern PHP New Features and Good Practices](http://shop.oreilly.com/product/0636920033868.do) - A book about new PHP features and best practices by Josh Lockhart.
* [Modernising Legacy Applications in PHP](https://leanpub.com/mlaphp) - A book about modernising legacy PHP applications by Paul M. Jones.
* [PHP 7 Upgrade Guide](https://leanpub.com/php7) - An ebook covering all of the features and changes in PHP 7 by Colin O'Dell.
* [PHP Pandas](http://daylerees.com/php-pandas/) - A book about learning to write PHP by Dayle Rees.
* [Scaling PHP Applications](http://www.scalingphpbook.com) - An ebook about scaling PHP applications by Steve Corona.
* [Securing PHP: Core Concepts](https://leanpub.com/securingphp-coreconcepts) - A book about common security terms and practices for PHP by Chris Cornutt.
* [Signaling PHP](https://leanpub.com/signalingphp) - A book about catching PCNTL signals in CLI scripts by Cal Evans.
* [The Grumpy Programmer's Guide to Building Testable PHP Applications](https://leanpub.com/grumpy-testing) - A book about building testing PHP applications by Chris Hartjes.

## Other Books
*Books related to general computing and web development.*

* [Elasticsearch: The Definitive Guide](https://www.elastic.co/guide/index.html) - A guide to working with Elasticsearch by Clinton Gormley and Zachary Tong.
* [Eloquent JavaScript](http://eloquentjavascript.net/) - A book about JavaScript programming by Marijn Haverbeke.
* [Head First Design Patterns](http://www.headfirstlabs.com/books/hfdp/) - A book that expains software design patterns.
* [Pro Git](https://git-scm.com/book/en/v2) - A book about Git by Scott Chacon and Ben Straub.
* [The Linux Command Line](http://linuxcommand.org/tlcl.php) - A book about the Linux command line by William Shotts.
* [The Tangled Web — Securing Web Applications](http://www.amazon.com/The-Tangled-Web-Securing-Applications/dp/1593273886) - A book about securing web applications by Michal Zalewski.
* [Understanding Computation](http://computationbook.com) - A book about computation theory by Tom Stuart.
* [Vagrant Cookbook](https://leanpub.com/vagrantcookbook) - A book about creating Vagrant environments by Erika Heidi.

## PHP Videos
*Fantastic PHP-related videos.*

* [PHP Town Hall](https://phptownhall.com/) - A casual PHP podcast by Ben Edmunds and Phil Sturgeon.
* [PHP UK Conference](https://www.youtube.com/user/phpukconference/videos) - A collection of videos from the PHP UK Conference.
* [Programming with Anthony](https://www.youtube.com/playlist?list=PLM-218uGSX3DQ3KsB5NJnuOqPqc5CW2kW) - A video series by Anthony Ferrara.
* [Taking PHP Seriously](http://www.infoq.com/presentations/php-history) - A talk outlining PHP's strengths by Keith Adams of Facebook.

## PHP Reading
*PHP-releated reading materials.*

* [Composer Primer](http://daylerees.com/composer-primer/) - A Composer primer.
* [Composer Stability Flags](https://igor.io/2013/02/07/composer-stability-flags.html) - An article about Composer stability flags.
* [Composer Versioning](https://igor.io/2013/01/07/composer-versioning.html) - An article about Composer versioning.
* [Create Your Own PHP Framework](http://fabien.potencier.org/create-your-own-framework-on-top-of-the-symfony2-components-part-1.html) - A series of articles on how to make your own PHP framework by Fabien Potencier.
* [Don't Worry About BREACH](http://blog.ircmaxell.com/2013/08/dont-worry-about-breach.html) - An article about the BREACH hack and CSRF tokens.
* [On PHP 5.3, Lambda Functions and Closures](http://fabien.potencier.org/on-php-5-3-lambda-functions-and-closures.html) - An article about lambda functions and closures.
* [PHP Is Much Better Than You Think](http://fabien.potencier.org/php-is-much-better-than-you-think.html) - An article about the PHP language and ecosystem.
* [PHP Sucks! But I Like It!](http://blog.ircmaxell.com/2012/04/php-sucks-but-i-like-it.html) - An article about the pros and cons of PHP.
* [Preventing CSRF Attacks](http://blog.ircmaxell.com/2013/02/preventing-csrf-attacks.html) - An article on preventing CSRF attacks.
* [Seven Ways to Screw Up BCrypt](http://blog.ircmaxell.com/2012/12/seven-ways-to-screw-up-bcrypt.html) - An article about correct BCrypt implementation.
* [Use Env](http://seancoates.com/blogs/use-env/) - An article about using the unix environment helper.

## PHP Internals Reading
*Reading materials related to the PHP internals or performance.*

* [Disproving the Single Quotes Myth](http://nikic.github.io/2012/01/09/Disproving-the-Single-Quotes-Performance-Myth.html) - An article about performance of single and double quoted strings.
* [How Big Are PHP Arrays (And Values) Really?](http://nikic.github.io/2011/12/12/How-big-are-PHP-arrays-really-Hint-BIG.html) - An article about array internals.
* [How Foreach Works](http://stackoverflow.com/questions/10057671/how-does-foreach-actually-work/14854568#14854568) - A detailed StackOverflow answer about foreach.
* [How Long is a Piece of String](http://blog.golemon.com/2006/06/how-long-is-piece-of-string.html) - An article about string internals.
* [PHP Evaluation Order](https://gist.github.com/nikic/6699370) - An article about evaluation order in PHP.
* [PHP Internals Book](http://www.phpinternalsbook.com) - An online book about PHP internals, written by three core developers.
* [PHP RFCs](https://wiki.php.net/rfc) - The home of PHP RFCs (Request for Comments).
* [Print vs Echo, Which One is Faster?](http://fabien.potencier.org/print-vs-echo-which-one-is-faster.html) - An article about print and echo performance.
* [The PHP Ternary Operator. Fast or Not?](http://fabien.potencier.org/the-php-ternary-operator-fast-or-not.html) - An article ternary performance.
* [Understanding OpCodes](http://blog.golemon.com/2008/01/understanding-opcodes.html) - An article about opcodes.
* [When Does Foreach Copy?](http://nikic.github.io/2011/11/11/PHP-Internals-When-does-foreach-copy.html) - An article about the internals of foreach.
* [Why Objects (Usually) Use Less Memory Than Arrays](https://gist.github.com/nikic/5015323) - An article about object and array internals.
* [You're Being Lied To](http://blog.golemon.com/2007/01/youre-being-lied-to.html) - An article about internal ZVALs.
* Collecting Garbage: [1](http://php.net/manual/en/features.gc.refcounting-basics.php) [2](http://php.net/manual/en/features.gc.collecting-cycles.php) [3](http://php.net/manual/en/features.gc.performance-considerations.php) - A series about the PHP garbage collection internals.
* PHP Source Code for Developers: [1](http://blog.ircmaxell.com/2012/03/phps-source-code-for-php-developers.html) [2](http://nikic.github.io/2012/03/16/Understanding-PHPs-internal-function-definitions.html) [3](http://blog.ircmaxell.com/2012/03/phps-source-code-for-php-developers_21.html) [4](http://nikic.github.io/2012/03/28/Understanding-PHPs-internal-array-implementation.html) - A series about the PHP source code.

## PHP Magazines
*Fantastic PHP-related magazines.*

* [php[architect]](https://www.phparch.com/magazine/) - A monthly magazine dedicated to PHP.
