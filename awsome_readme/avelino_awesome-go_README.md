# Awesome Go

[![Build Status](https://travis-ci.org/avelino/awesome-go.svg?branch=master)](https://travis-ci.org/avelino/awesome-go) [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome) [![Slack Widget](https://img.shields.io/badge/join-us%20on%20slack-gray.svg?longCache=true&logo=slack&colorB=red)](http://gophers.slack.com/messages/awesome) [![Netlify Status](https://api.netlify.com/api/v1/badges/83a6dcbe-0da6-433e-b586-f68109286bd5/deploy-status)](https://app.netlify.com/sites/awesome-go/deploys) 【🌟Star 123837】


[![patreon avelino](https://c5.patreon.com/external/logo/become_a_patron_button@2x.png)](https://www.patreon.com/avelinosource) financial support to Awesome Go

A curated list of awesome Go frameworks, libraries and software. Inspired by [awesome-python](https://github.com/vinta/awesome-python). 【🌟Star 78232】


### Contributing

Please take a quick gander at the [contribution guidelines](https://github.com/avelino/awesome-go/blob/master/CONTRIBUTING.md) first. Thanks to all [contributors](https://github.com/avelino/awesome-go/graphs/contributors); you rock!

#### *If you see a package or project here that is no longer maintained or is not a good fit, please submit a pull request to improve this file. Thank you!*

### Contents

- [Awesome Go](#awesome-go)
    - [Audio and Music](#audio-and-music)
    - [Authentication and OAuth](#authentication-and-oauth)
    - [Bot Building](#bot-building)
    - [Command Line](#command-line)
    - [Configuration](#configuration)
    - [Continuous Integration](#continuous-integration)
    - [CSS Preprocessors](#css-preprocessors)
    - [Data Structures](#data-structures)
    - [Database](#database)
    - [Database Drivers](#database-drivers)
    - [Date and Time](#date-and-time)
    - [Distributed Systems](#distributed-systems)
    - [Dynamic DNS](#dynamic-dns)
    - [Email](#email)
    - [Embeddable Scripting Languages](#embeddable-scripting-languages)
    - [Error Handling](#error-handling)
    - [Files](#files)
    - [Financial](#financial)
    - [Forms](#forms)
    - [Functional](#functional)
    - [Game Development](#game-development)
    - [Generation and Generics](#generation-and-generics)
    - [Geographic](#geographic)
    - [Go Compilers](#go-compilers)
    - [Goroutines](#goroutines)
    - [GUI](#gui)
    - [Hardware](#hardware)
    - [Images](#images)
    - [IoT](#iot-internet-of-things)
    - [Job Scheduler](#job-scheduler)
    - [JSON](#json)
    - [Logging](#logging)
    - [Machine Learning](#machine-learning)
    - [Messaging](#messaging)
    - [Microsoft Office](#microsoft-office)
        - [Microsoft Excel](#microsoft-excel)
    - [Miscellaneous](#miscellaneous)
        - [Dependency Injection](#dependency-injection)
        - [Project Layout](#project-layout)
        - [Strings](#strings)
    - [Natural Language Processing](#natural-language-processing)
    - [Networking](#networking)
        - [HTTP Clients](#http-clients)
    - [OpenGL](#opengl)
    - [ORM](#orm)
    - [Package Management](#package-management)
    - [Performance](#performance)
    - [Query Language](#query-language)
    - [Resource Embedding](#resource-embedding)
    - [Science and Data Analysis](#science-and-data-analysis)
    - [Security](#security)
    - [Serialization](#serialization)
    - [Server Applications](#server-applications)
    - [Stream Processing](#stream-processing)
    - [Template Engines](#template-engines)
    - [Testing](#testing)
    - [Text Processing](#text-processing)
    - [Third-party APIs](#third-party-apis)
    - [Utilities](#utilities)
    - [UUID](#uuid)
    - [Validation](#validation)
    - [Version Control](#version-control)
    - [Video](#video)
    - [Web Frameworks](#web-frameworks)
        - [Middlewares](#middlewares)
            - [Actual middlewares](#actual-middlewares)
            - [Libraries for creating HTTP middlewares](#libraries-for-creating-http-middlewares)
        - [Routers](#routers)
    - [Windows](#windows)
    - [XML](#xml)

- [Tools](#tools)
    - [Code Analysis](#code-analysis)
    - [Editor Plugins](#editor-plugins)
    - [Go Generate Tools](#go-generate-tools)
    - [Go Tools](#go-tools)
    - [Software Packages](#software-packages)
        - [DevOps Tools](#devops-tools)
        - [Other Software](#other-software)

- [Resources](#resources)
    - [Benchmarks](#benchmarks)
    - [Conferences](#conferences)
    - [E-Books](#e-books)
    - [Gophers](#gophers)
    - [Meetups](#meetups)
    - [Twitter](#twitter)
    - [Websites](#websites)
        - [Tutorials](#tutorials)

## Audio and Music

*Libraries for manipulating audio.*

* [EasyMIDI](https://github.com/algoGuy/EasyMIDI) - EasyMidi is a simple and reliable library for working with standard midi file (SMF). 【🌟Star 26】

* [flac](https://github.com/mewkiz/flac) - Native Go FLAC encoder/decoder with support for FLAC streams. 【🌟Star 111】

* [gaad](https://github.com/Comcast/gaad) - Native Go AAC bitstream parser. 【🌟Star 63】

* [go-sox](https://github.com/krig/go-sox) - libsox bindings for go. 【🌟Star 102】

* [go_mediainfo](https://github.com/zhulik/go_mediainfo) - libmediainfo bindings for go. 【🌟Star 28】

* [gosamplerate](https://github.com/dh1tw/gosamplerate) - libsamplerate bindings for go. 【🌟Star 9】

* [id3v2](https://github.com/bogem/id3v2) - Fast and stable ID3 parsing and writing library for Go. 【🌟Star 132】

* [malgo](https://github.com/gen2brain/malgo) - Mini audio library. 【🌟Star 90】

* [minimp3](https://github.com/tosone/minimp3) - Lightweight MP3 decoder library. 【🌟Star 34】

* [mix](https://github.com/go-mix/mix) - Sequence-based Go-native audio mixer for music apps. 【🌟Star 106】

* [mp3](https://github.com/tcolgate/mp3) - Native Go MP3 decoder. 【🌟Star 104】

* [music-theory](https://github.com/go-music-theory/music-theory) - Music theory models in Go. 【🌟Star 274】

* [Oto](https://github.com/hajimehoshi/oto) - A low-level library to play sound on multiple platforms. 【🌟Star 507】

* [PortAudio](https://github.com/gordonklaus/portaudio) - Go bindings for the PortAudio audio I/O library. 【🌟Star 331】

* [portmidi](https://github.com/rakyll/portmidi) - Go bindings for PortMidi. 【🌟Star 222】

* [taglib](https://github.com/wtolson/go-taglib) - Go bindings for taglib. 【🌟Star 72】

* [vorbis](https://github.com/mccoyst/vorbis) - "Native" Go Vorbis decoder (uses CGO, but has no dependencies). 【🌟Star 24】

* [waveform](https://github.com/mdlayher/waveform) - Go package capable of generating waveform images from audio streams. 【🌟Star 269】


## Authentication and OAuth

*Libraries for implementing authentications schemes.*

* [authboss](https://github.com/volatiletech/authboss) - Modular authentication system for the web. It tries to remove as much boilerplate and "hard things" as possible so that each time you start a new web project in Go, you can plug it in, configure, and start building your app without having to build an authentication system each time. 【🌟Star 2089】

* [branca](https://github.com/hako/branca) - Golang implementation of Branca Tokens. 【🌟Star 99】

* [casbin](https://github.com/hsluoyz/casbin) - Authorization library that supports access control models like ACL, RBAC, ABAC. 【🌟Star 5914】

* [cookiestxt](https://github.com/mengzhuo/cookiestxt) - provides parser of cookies.txt file format. 【🌟Star 2】

* [go-jose](https://github.com/square/go-jose) - Fairly complete implementation of the JOSE working group's JSON Web Token, JSON Web Signatures, and JSON Web Encryption specs. 【🌟Star 1441】

* [go-oauth2-server](https://github.com/RichardKnop/go-oauth2-server) - Standalone, specification-compliant,  OAuth2 server written in Golang. 【🌟Star 1416】

* [gologin](https://github.com/dghubble/gologin) - chainable handlers for login with OAuth1 and OAuth2 authentication providers. 【🌟Star 1141】

* [gorbac](https://github.com/mikespook/gorbac) - provides a lightweight role-based access control (RBAC) implementation in Golang. 【🌟Star 972】

* [goth](https://github.com/markbates/goth) - provides a simple, clean, and idiomatic way to use OAuth and OAuth2. Handles multiple providers out of the box. 【🌟Star 2500】

* [httpauth](https://github.com/goji/httpauth) - HTTP Authentication middleware. 【🌟Star 190】

* [jeff](https://github.com/abraithwaite/jeff) - Simple, flexible, secure and idiomatic web session management with pluggable backends. 【🌟Star 183】

* [jwt](https://github.com/robbert229/jwt) - Clean and easy to use implementation of JSON Web Tokens (JWT). 【🌟Star 78】

* [jwt](https://github.com/pascaldekloe/jwt) - Lightweight JSON Web Token (JWT) library. 【🌟Star 141】

* [jwt-auth](https://github.com/adam-hanna/jwt-auth) - JWT middleware for Golang http servers with many configuration options. 【🌟Star 165】

* [jwt-go](https://github.com/dgrijalva/jwt-go) - Golang implementation of JSON Web Tokens (JWT). 【🌟Star 6883】

* [loginsrv](https://github.com/tarent/loginsrv) - JWT login microservice with plugable backends such as OAuth2 (Github), htpasswd, osiam. 【🌟Star 884】

* [oauth2](https://github.com/golang/oauth2) - Successor of goauth2. Generic OAuth 2.0 package that comes with JWT, Google APIs, Compute Engine and App Engine support. 【🌟Star 2666】

* [osin](https://github.com/openshift/osin) - Golang OAuth2 server library. 【🌟Star 1576】

* [paseto](https://github.com/o1egl/paseto) - Golang implementation of Platform-Agnostic Security Tokens (PASETO). 【🌟Star 288】

* [permissions2](https://github.com/xyproto/permissions2) - Library for keeping track of users, login states and permissions. Uses secure cookies and bcrypt. 【🌟Star 382】

* [rbac](https://github.com/zpatrick/rbac) - Minimalistic RBAC package for Go applications. 【🌟Star 44】

* [scope](https://github.com/SonicRoshan/scope) - Easily Manage OAuth2 Scopes In Go. 【🌟Star 3】

* [scs](https://github.com/alexedwards/scs) - Session Manager for HTTP servers. 【🌟Star 656】

* [securecookie](https://github.com/chmike/securecookie) - Efficient secure cookie encoding/decoding. 【🌟Star 34】

* [session](https://github.com/icza/session) - Go session management for web servers (including support for Google App Engine - GAE). 【🌟Star 95】

* [sessiongate-go](https://github.com/f0rmiga/sessiongate-go) - Go session management using the SessionGate Redis module. 【🌟Star 8】

* [sessions](https://github.com/adam-hanna/sessions) - Dead simple, highly performant, highly customizable sessions service for go http servers. 【🌟Star 49】

* [sessionup](https://github.com/swithek/sessionup) - Simple, yet effective HTTP session management and identification package. 【🌟Star 76】

* [signedvalue](https://github.com/sashka/signedvalue) - Signed and timestamped strings compatible with [Tornado's](https://github.com/tornadoweb/tornado) `create_signed_value`, `decode_signed_value`, and therefore `set_secure_cookie` and `get_secure_cookie`. 【🌟Star 8】

* [sjwt](https://github.com/brianvoe/sjwt) - Simple jwt generator and parser. 【🌟Star 51】


## Bot Building

*Libraries for building and working with bots.*

* [go-chat-bot](https://github.com/go-chat-bot/bot) - IRC, Slack & Telegram bot written in Go. 【🌟Star 535】

* [go-joe](https://joe-bot.net) - A general-purpose bot library inspired by Hubot but written in Go.
* [go-sarah](https://github.com/oklahomer/go-sarah) - Framework to build bot for desired chat services including LINE, Slack, Gitter and more. 【🌟Star 152】

* [go-tgbot](https://github.com/olebedev/go-tgbot) - Pure Golang Telegram Bot API wrapper, generated from swagger file, session-based router and middleware. 【🌟Star 91】

* [Golang CryptoTrading Bot](https://github.com/saniales/golang-crypto-trading-bot) - A golang implementation of a console-based trading bot for cryptocurrency exchanges. 【🌟Star 273】

* [govkbot](https://github.com/nikepan/govkbot) - Simple Go [VK](https://vk.com) bot library. 【🌟Star 30】

* [hanu](https://github.com/sbstjn/hanu) - Framework for writing Slack bots. 【🌟Star 116】

* [Kelp](https://github.com/stellar/kelp) - official trading and market-making bot for the [Stellar](https://www.stellar.org/) DEX. Works out-of-the-box, written in Golang, compatible with centralized exchanges and custom trading strategies. 【🌟Star 250】

* [margelet](https://github.com/zhulik/margelet) - Framework for building Telegram bots. 【🌟Star 60】

* [micha](https://github.com/onrik/micha) - Go Library for Telegram bot api. 【🌟Star 12】

* [slacker](https://github.com/shomali11/slacker) - Easy to use framework to create Slack bots. 【🌟Star 345】

* [slackscot](https://github.com/alexandre-normand/slackscot) - Another framework for building Slack bots. 【🌟Star 21】

* [tbot](https://github.com/yanzay/tbot) - Telegram bot server with API similar to net/http. 【🌟Star 243】

* [telebot](https://github.com/tucnak/telebot) - Telegram bot framework written in Go. 【🌟Star 1078】

* [telegram-bot-api](https://github.com/Syfaro/telegram-bot-api) - Simple and clean Telegram bot client. 【🌟Star 1866】

* [Tenyks](https://github.com/kyleterry/tenyks) - Service oriented IRC bot using Redis and JSON for messaging. 【🌟Star 169】


## Command Line

### Standard CLI

*Libraries for building standard or basic Command Line applications.*

* [1build](https://github.com/gopinath-langote/1build) - Command line tool to frictionlessly manage project-specific commands. 【🌟Star 45】

* [argparse](https://github.com/akamensky/argparse) - Command line argument parser inspired by Python's argparse module. 【🌟Star 150】

* [argv](https://github.com/cosiner/argv) - Go library to split command line string as arguments array using the bash syntax. 【🌟Star 19】

* [cli](https://github.com/mkideal/cli) - Feature-rich and easy to use command-line package based on golang struct tags. 【🌟Star 511】

* [cli](https://github.com/teris-io/cli) - Simple and complete API for building command line interfaces in Go. 【🌟Star 59】

* [cli-init](https://github.com/tcnksm/gcli) - The easy way to start building Golang command line applications. 【🌟Star 888】

* [climax](http://github.com/tucnak/climax) - Alternative CLI with "human face", in spirit of Go command.
* [clîr](https://github.com/leaanthony/clir) - A Simple and Clear CLI library. Dependency free. 【🌟Star 3】

* [cmd](https://github.com/posener/cmd) - Extends the standard `flag` package to support sub commands and more in idomatic way. 【🌟Star 3】

* [cmdr](https://github.com/hedzr/cmdr) - A POSIX/GNU style, getopt-like command-line UI Go library. 【🌟Star 27】

* [cobra](https://github.com/spf13/cobra) - Commander for modern Go CLI interactions. 【🌟Star 15429】

* [commandeer](https://github.com/jaffee/commandeer) - Dev-friendly CLI apps: sets up flags, defaults, and usage based on struct fields and tags. 【🌟Star 105】

* [complete](https://github.com/posener/complete) - Write bash completions in Go + Go command bash completion. 【🌟Star 662】

* [Dnote](https://github.com/dnote/dnote) - A simple and end-to-end encrypted notebook for developers. 【🌟Star 1416】

* [docopt.go](https://github.com/docopt/docopt.go) - Command-line arguments parser that will make you smile. 【🌟Star 1209】

* [env](https://github.com/codingconcepts/env) - Tag-based environment configuration for structs. 【🌟Star 46】

* [flag](https://github.com/cosiner/flag) - Simple but powerful command line option parsing library for Go supporting subcommand. 【🌟Star 103】

* [flaggy](https://github.com/integrii/flaggy) - A robust and idiomatic flags package with excellent subcommand support. 【🌟Star 533】

* [flagvar](https://github.com/sgreben/flagvar) - A collection of flag argument types for Go's standard `flag` package. 【🌟Star 33】

* [go-arg](https://github.com/alexflint/go-arg) - Struct-based argument parsing in Go. 【🌟Star 813】

* [go-commander](https://github.com/yitsushi/go-commander) - Go library to simplify CLI workflow. 【🌟Star 15】

* [go-flags](https://github.com/jessevdk/go-flags) - go command line option parser. 【🌟Star 1604】

* [go-getoptions](https://github.com/DavidGamba/go-getoptions) - Go option parser inspired on the flexibility of Perl’s GetOpt::Long. 【🌟Star 19】

* [gocmd](https://github.com/devfacet/gocmd) - Go library for building command line applications. 【🌟Star 37】

* [hiboot cli](https://github.com/hidevopsio/hiboot/tree/master/pkg/app/cli) - cli application framework with auto configuration and dependency injection.
* [job](https://github.com/liujianping/job) - JOB, make your short-term command as a long-term job. 【🌟Star 67】

* [kingpin](https://github.com/alecthomas/kingpin) - Command line and flag parser supporting sub commands. 【🌟Star 2779】

* [liner](https://github.com/peterh/liner) - Go readline-like library for command-line interfaces. 【🌟Star 632】

* [mitchellh/cli](https://github.com/mitchellh/cli) - Go library for implementing command-line interfaces. 【🌟Star 1069】

* [mow.cli](https://github.com/jawher/mow.cli) - Go library for building CLI applications with sophisticated flag and argument parsing and validation. 【🌟Star 650】

* [ops](https://github.com/nanovms/ops) - Unikernel Builder/Orchestrator. 【🌟Star 341】

* [pflag](https://github.com/spf13/pflag) - Drop-in replacement for Go's flag package, implementing POSIX/GNU-style --flags. 【🌟Star 964】

* [readline](https://github.com/chzyer/readline) - Pure golang implementation that provides most features in GNU-Readline under MIT license. 【🌟Star 1439】

* [sand](https://github.com/Zaba505/sand) - Simple API for creating interpreters and so much more. 【🌟Star 9】

* [sflags](https://github.com/octago/sflags) - Struct based flags generator for flag, urfave/cli, pflag, cobra, kingpin and other libraries. 【🌟Star 103】

* [strumt](https://github.com/antham/strumt) - Library to create prompt chain. 【🌟Star 32】

* [ts](https://github.com/liujianping/ts) - Timestamp convert & compare tool. 【🌟Star 7】

* [ukautz/clif](https://github.com/ukautz/clif) - Small command line interface framework. 【🌟Star 98】

* [urfave/cli](https://github.com/urfave/cli) - Simple, fast, and fun package for building command line apps in Go (formerly codegangsta/cli). 【🌟Star 12897】

* [wlog](https://github.com/dixonwille/wlog) - Simple logging interface that supports cross-platform color and concurrency. 【🌟Star 40】

* [wmenu](https://github.com/dixonwille/wmenu) - Easy to use menu structure for cli applications that prompts users to make choices. 【🌟Star 95】


### Advanced Console UIs

*Libraries for building Console Applications and Console User Interfaces.*

* [asciigraph](https://github.com/guptarohit/asciigraph) - Go package to make lightweight ASCII line graph ╭┈╯ in command line apps with no other dependencies. 【🌟Star 1240】

* [aurora](https://github.com/logrusorgru/aurora) - ANSI terminal colors that supports fmt.Printf/Sprintf. 【🌟Star 761】

* [cfmt](https://github.com/mingrammer/cfmt) - Contextual fmt inspired by bootstrap color classes. 【🌟Star 70】

* [chalk](https://github.com/ttacon/chalk) - Intuitive package for prettifying terminal/console output. 【🌟Star 325】

* [colourize](https://github.com/TreyBastian/colourize) - Go library for ANSI colour text in terminals. 【🌟Star 17】

* [ctc](https://github.com/wzshiming/ctc) - The non-invasive cross-platform terminal color library does not need to modify the Print method. 【🌟Star 13】

* [go-ataman](https://github.com/workanator/go-ataman) - Go library for rendering ANSI colored text templates in terminals. 【🌟Star 8】

* [go-colorable](https://github.com/mattn/go-colorable) - Colorable writer for windows. 【🌟Star 403】

* [go-colortext](https://github.com/daviddengcn/go-colortext) - Go library for color output in terminals. 【🌟Star 200】

* [go-isatty](https://github.com/mattn/go-isatty) - isatty for golang. 【🌟Star 387】

* [go-prompt](https://github.com/c-bata/go-prompt) - Library for building a powerful interactive prompt, inspired by [python-prompt-toolkit](https://github.com/jonathanslenders/python-prompt-toolkit). 【🌟Star 2753】

* [gocui](https://github.com/jroimartin/gocui) - Minimalist Go library aimed at creating Console User Interfaces. 【🌟Star 5876】

* [gommon/color](https://github.com/labstack/gommon/tree/master/color) - Style terminal text.
* [gookit/color](https://github.com/gookit/color) - Terminal color rendering tool library, support 16 colors, 256 colors, RGB color rendering output, compatible with Windows. 【🌟Star 298】

* [mpb](https://github.com/vbauerster/mpb) - Multi progress bar for terminal applications. 【🌟Star 820】

* [progressbar](https://github.com/schollz/progressbar) - Basic thread-safe progress bar that works in every OS. 【🌟Star 834】

* [simpletable](https://github.com/alexeyco/simpletable) - Simple tables in terminal with Go. 【🌟Star 184】

* [tabby](https://github.com/cheynewallace/tabby) - A tiny library for super simple Golang tables. 【🌟Star 259】

* [tabular](https://github.com/InVisionApp/tabular) - Print ASCII tables from command line utilities without the need to pass large sets of data to the API. 【🌟Star 36】

* [termbox-go](https://github.com/nsf/termbox-go) - Termbox is a library for creating cross-platform text-based interfaces. 【🌟Star 3637】

* [termdash](https://github.com/mum4k/termdash) - Go terminal dashboard based on **termbox-go** and inspired by [termui](https://github.com/gizak/termui). 【🌟Star 908】

* [termui](https://github.com/gizak/termui) - Go terminal dashboard based on **termbox-go** and inspired by [blessed-contrib](https://github.com/yaronn/blessed-contrib). 【🌟Star 9418】

* [uilive](https://github.com/gosuri/uilive) - Library for updating terminal output in realtime. 【🌟Star 1068】

* [uiprogress](https://github.com/gosuri/uiprogress) - Flexible library to render progress bars in terminal applications. 【🌟Star 1612】

* [uitable](https://github.com/gosuri/uitable) - Library to improve readability in terminal apps using tabular data. 【🌟Star 537】


## Configuration

*Libraries for configuration parsing.*

* [cleanenv](https://github.com/ilyakaznacheev/cleanenv) - Minimalistic configuration reader (from files, ENV, and wherever you want). 【🌟Star 31】

* [config](https://github.com/golobby/config) - A lightweight yet powerful config package for Go projects. 【🌟Star 38】

* [config](https://github.com/JeremyLoy/config) - Cloud native application configuration. Bind ENV to structs in only two lines. 【🌟Star 223】

* [config](https://github.com/olebedev/config) - JSON or YAML configuration wrapper with environment variables and flags parsing. 【🌟Star 222】

* [configure](https://github.com/paked/configure) - Provides configuration through multiple sources, including JSON, flags and environment variables. 【🌟Star 53】

* [confita](https://github.com/heetch/confita) - Load configuration in cascade from multiple backends into a struct. 【🌟Star 287】

* [conflate](https://github.com/the4thamigo-uk/conflate) - Library/tool to merge multiple JSON/YAML/TOML files from arbitrary URLs, validation against a JSON schema, and application of default values defined in the schema. 【🌟Star 11】

* [env](https://github.com/caarlos0/env) - Parse environment variables to Go structs (with defaults). 【🌟Star 1385】

* [envcfg](https://github.com/tomazk/envcfg) - Un-marshaling environment variables to Go structs. 【🌟Star 90】

* [envconf](https://github.com/ian-kent/envconf) - Configuration from environment. 【🌟Star 8】

* [envconfig](https://github.com/vrischmann/envconfig) - Read your configuration from environment variables. 【🌟Star 171】

* [envh](https://github.com/antham/envh) - Helpers to manage environment variables. 【🌟Star 92】

* [gcfg](https://github.com/go-gcfg/gcfg) - read INI-style configuration files into Go structs; supports user-defined types and subsections. 【🌟Star 123】

* [genv](https://github.com/sakirsensoy/genv) - Read environment variables easily with dotenv support. 【🌟Star 8】

* [go-ssm-config](https://github.com/ianlopshire/go-ssm-config) - Go utility for loading configuration parameters from AWS SSM (Parameter Store). 【🌟Star 3】

* [go-up](https://github.com/ufoscout/go-up) - A simple configuration library with recursive placeholders resolution and no magic. 【🌟Star 26】

* [goConfig](https://github.com/crgimenes/goConfig) - Parses a struct as input and populates the fields of this struct with parameters from command line, environment variables and configuration file. 【🌟Star 121】

* [godotenv](https://github.com/joho/godotenv) - Go port of Ruby's dotenv library (Loads environment variables from `.env`). 【🌟Star 2514】

* [gofigure](https://github.com/ian-kent/gofigure) - Go application configuration made easy. 【🌟Star 58】

* [gone/jconf](https://github.com/One-com/gone/tree/master/jconf) - Modular JSON configuration. Keep you config structs along with the code they configure and delegate parsing to submodules without sacrificing full config serialization.
* [gookit/config](https://github.com/gookit/config) - application config manage(load,get,set). support JSON, YAML, TOML, INI, HCL. multi file load, data override merge. 【🌟Star 129】

* [harvester](https://github.com/beatlabs/harvester) - Harvester, a easy to use static and dynamic configuration package supportig seeding, env vars and Consul integration. 【🌟Star 49】

* [hjson](https://github.com/hjson/hjson-go) - Human JSON, a configuration file format for humans. Relaxed syntax, fewer mistakes, more comments. 【🌟Star 184】

* [ingo](https://github.com/schachmat/ingo) - Flags persisted in an ini-like config file. 【🌟Star 26】

* [ini](https://github.com/go-ini/ini) - Go package to read and write INI files. 【🌟Star 1856】

* [joshbetz/config](https://github.com/joshbetz/config) - Small configuration library for Go that parses environment variables, JSON files, and reloads automatically on SIGHUP. 【🌟Star 198】

* [kelseyhightower/envconfig](https://github.com/kelseyhightower/envconfig) - Go library for managing configuration data from environment variables. 【🌟Star 2716】

* [koanf](https://github.com/knadh/koanf) - Light weight, extensible library for reading config in Go applications. Built in support for JSON, TOML, YAML, env, command line. 【🌟Star 148】

* [konfig](https://github.com/lalamove/konfig) - Composable, observable and performant config handling for Go for the distributed processing era. 【🌟Star 546】

* [mini](https://github.com/sasbury/mini) - Golang package for parsing ini-style configuration files. 【🌟Star 20】

* [nasermirzaei89/env](https://github.com/nasermirzaei89/env) - Simple useful package for read environment variables. 【🌟Star 2】

* [onion](http://github.com/goraz/onion) - Layer based configuration for Go, Supports JSON, TOML, YAML, properties, etcd, env, and encryption using PGP.
* [sprbox](https://github.com/oblq/sprbox) - Build-environment aware toolbox factory and agnostic config parser (YAML, TOML, JSON and Environment vars). 【🌟Star 5】

* [store](https://github.com/tucnak/store) - Lightweight configuration manager for Go. 【🌟Star 248】

* [viper](https://github.com/spf13/viper) - Go configuration with fangs. 【🌟Star 10910】

* [xdg](https://github.com/OpenPeeDeeP/xdg) - Cross platform package that follows the [XDG Standard](https://standards.freedesktop.org/basedir-spec/basedir-spec-latest.html). 【🌟Star 44】


## Continuous Integration

*Tools for help with continuous integration.*

* [CDS](https://github.com/ovh/cds) - Enterprise-Grade CI/CD and DevOps Automation Open Source Platform. 【🌟Star 2602】

* [drone](https://github.com/drone/drone) - Drone is a Continuous Integration platform built on Docker, written in Go. 【🌟Star 20299】

* [duci](https://github.com/duck8823/duci) - A simple ci server no needs domain specific languages. 【🌟Star 50】

* [gomason](https://github.com/nikogura/gomason) - Test, Build, Sign, and Publish your go binaries from a clean workspace. 【🌟Star 41】

* [goveralls](https://github.com/mattn/goveralls) - Go integration for Coveralls.io continuous code coverage tracking system. 【🌟Star 623】

* [overalls](https://github.com/go-playground/overalls) - Multi-Package go project coverprofile for tools like goveralls. 【🌟Star 99】

* [roveralls](https://github.com/LawrenceWoodman/roveralls) - Recursive coverage testing tool. 【🌟Star 12】


## CSS Preprocessors

*Libraries for preprocessing CSS files.*

* [gcss](https://github.com/yosssi/gcss) - Pure Go CSS Preprocessor. 【🌟Star 427】

* [go-libsass](https://github.com/wellington/go-libsass) - Go wrapper to the 100% Sass compatible libsass project. 【🌟Star 147】


## Data Structures

*Generic datastructures and algorithms in Go.*

* [algorithms](https://github.com/shady831213/algorithms) - Algorithms and data structures.CLRS study. 【🌟Star 340】

* [binpacker](https://github.com/zhuangsirui/binpacker) - Binary packer and unpacker helps user build custom binary stream. 【🌟Star 132】

* [bit](https://github.com/yourbasic/bit) - Golang set data structure with bonus bit-twiddling functions. 【🌟Star 76】

* [bitset](https://github.com/willf/bitset) - Go package implementing bitsets. 【🌟Star 531】

* [bloom](https://github.com/zhenjl/bloom) - Bloom filters implemented in Go. 【🌟Star 131】

* [bloom](https://github.com/yourbasic/bloom) - Golang Bloom filter implementation. 【🌟Star 47】

* [boomfilters](https://github.com/tylertreat/BoomFilters) - Probabilistic data structures for processing continuous, unbounded streams. 【🌟Star 1226】

* [concurrent-writer](https://github.com/free/concurrent-writer) - Highly concurrent drop-in replacement for `bufio.Writer`. 【🌟Star 26】

* [conjungo](https://github.com/InVisionApp/conjungo) - A small, powerful and flexible merge library. 【🌟Star 84】

* [count-min-log](https://github.com/seiflotfy/count-min-log) - Go implementation Count-Min-Log sketch: Approximately counting with approximate counters (Like Count-Min sketch but using less memory). 【🌟Star 46】

* [crunch](https://github.com/superwhiskers/crunch) - Go package implementing buffers for handling various datatypes easily. 【🌟Star 23】

* [cuckoofilter](https://github.com/seiflotfy/cuckoofilter) - Cuckoo filter: a good alternative to a counting bloom filter implemented in Go. 【🌟Star 572】

* [deque](https://github.com/edwingeng/deque) - A highly optimized double-ended queue. 【🌟Star 14】

* [deque](https://github.com/gammazero/deque) - Fast ring-buffer deque (double-ended queue). 【🌟Star 98】

* [dict](https://github.com/srfrog/dict) - Python-like dictionaries (dict) for Go. 【🌟Star 12】

* [encoding](https://github.com/zhenjl/encoding) - Integer Compression Libraries for Go. 【🌟Star 97】

* [go-adaptive-radix-tree](https://github.com/plar/go-adaptive-radix-tree) - Go implementation of Adaptive Radix Tree. 【🌟Star 126】

* [go-datastructures](https://github.com/Workiva/go-datastructures) - Collection of useful, performant, and thread-safe data structures. 【🌟Star 5403】

* [go-ef](https://github.com/amallia/go-ef) - A Go implementation of the Elias-Fano encoding. 【🌟Star 11】

* [go-geoindex](https://github.com/hailocab/go-geoindex) - In-memory geo index. 【🌟Star 317】

* [go-mcache](https://github.com/OrlovEvgeny/go-mcache) - Fast in-memory key:value store/cache library. Pointer caches. 【🌟Star 43】

* [go-rquad](https://github.com/aurelien-rainone/go-rquad) - Region quadtrees with efficient point location and neighbour finding. 【🌟Star 101】

* [gocache](https://github.com/eko/gocache) - A complete Go cache library with mutiple stores (memory, memcache, redis, ...), chainable, loadable, metrics cache and more. 【🌟Star 341】

* [goconcurrentqueue](https://github.com/enriquebris/goconcurrentqueue) - Concurrent FIFO queue. 【🌟Star 56】

* [gods](https://github.com/emirpasic/gods) - Go Data Structures. Containers, Sets, Lists, Stacks, Maps, BidiMaps, Trees, HashSet etc. 【🌟Star 7613】

* [gofal](https://github.com/xxjwxc/gofal) - fractional api for Go. 【🌟Star 5】

* [golang-set](https://github.com/deckarep/golang-set) - Thread-Safe and Non-Thread-Safe high-performance sets for Go. 【🌟Star 1375】

* [goset](https://github.com/zoumo/goset) - A useful Set collection implementation for Go. 【🌟Star 19】

* [goskiplist](https://github.com/ryszard/goskiplist) - Skip list implementation in Go. 【🌟Star 215】

* [gota](https://github.com/kniren/gota) - Implementation of dataframes, series, and data wrangling methods for Go. 【🌟Star 1053】

* [hide](https://github.com/emvi/hide) - ID type with marshalling to/from hash to prevent sending IDs to clients. 【🌟Star 11】

* [hilbert](https://github.com/google/hilbert) - Go package for mapping values to and from space-filling curves, such as Hilbert and Peano curves. 【🌟Star 193】

* [hyperloglog](https://github.com/axiomhq/hyperloglog) - HyperLogLog implementation with Sparse, LogLog-Beta bias correction and TailCut space reduction. 【🌟Star 680】

* [iter](https://github.com/disksing/iter) - Go implementation of C++ STL iterators and algorithms. 【🌟Star 105】

* [levenshtein](https://github.com/agext/levenshtein) - Levenshtein distance and similarity metrics with customizable edit costs and Winkler-like bonus for common prefix. 【🌟Star 37】

* [levenshtein](https://github.com/agnivade/levenshtein) - Implementation to calculate levenshtein distance in Go. 【🌟Star 65】

* [mafsa](https://github.com/smartystreets/mafsa) - MA-FSA implementation with Minimal Perfect Hashing. 【🌟Star 281】

* [merkletree](https://github.com/cbergoon/merkletree) - Implementation of a merkle tree providing an efficient and secure verification of the contents of data structures. 【🌟Star 174】

* [mspm](https://github.com/BlackRabbitt/mspm) - Multi-String Pattern Matching Algorithm for information retrieval. 【🌟Star 8】

* [null](https://github.com/emvi/null) - Nullable Go types that can be marshalled/unmarshalled to/from JSON. 【🌟Star 8】

* [parsefields](https://github.com/MonaxGT/parsefields) - Tools for parse JSON-like logs for collecting unique fields and events. 【🌟Star 3】

* [pipeline](https://github.com/hyfather/pipeline) - An implementation of pipelines with fan-in and fan-out. 【🌟Star 19】

* [ptrie](https://github.com/viant/ptrie) - An implementation of prefix tree. 【🌟Star 3】

* [remember-go](https://github.com/rocketlaunchr/remember-go) - A universal interface for caching slow database queries (backed by redis, memcached, ristretto, or in-memory). 【🌟Star 33】

* [ring](https://github.com/TheTannerRyan/ring) - Go implementation of a high performance, thread safe bloom filter. 【🌟Star 99】

* [roaring](https://github.com/RoaringBitmap/roaring) - Go package implementing compressed bitsets. 【🌟Star 771】

* [set](https://github.com/StudioSol/set) - Simple set data structure implementation in Go using LinkedHashMap. 【🌟Star 7】

* [skiplist](https://github.com/MauriceGit/skiplist) - Very fast Go Skiplist implementation. 【🌟Star 111】

* [skiplist](https://github.com/gansidui/skiplist) - Skiplist implementation in Go. 【🌟Star 67】

* [timedmap](https://github.com/zekroTJA/timedmap) - Map with expiring key-value pairs. 【🌟Star 6】

* [treap](https://github.com/perdata/treap) - Persistent, fast ordered map using tree heaps. 【🌟Star 7】

* [trie](https://github.com/derekparker/trie) - Trie implementation in Go. 【🌟Star 449】

* [ttlcache](https://github.com/diegobernardes/ttlcache) - In-memory LRU string-interface{} map with expiration for golang. 【🌟Star 122】

* [typ](https://github.com/gurukami/typ) - Null Types, Safe primitive type conversion and fetching value from complex structures. 【🌟Star 15】

* [willf/bloom](https://github.com/willf/bloom) - Go package implementing Bloom filters. 【🌟Star 736】


## Database

*Databases implemented in Go.*

* [badger](https://github.com/dgraph-io/badger) - Fast key-value store in Go. 【🌟Star 7178】

* [bcache](https://github.com/iwanbk/bcache) - Eventually consistent distributed in-memory  cache Go library. 【🌟Star 41】

* [BigCache](https://github.com/allegro/bigcache) - Efficient key/value cache for gigabytes of data. 【🌟Star 3517】

* [Bitcask](https://github.com/prologic/bitcask) - Bitcask is an embeddable, persistent and fast key-value (KV) database written in pure Go with predictable read/write performance, low latency and high throughput thanks to the bitcask on-disk layout (LSM+WAL). 【🌟Star 259】

* [bolt](https://github.com/boltdb/bolt) - Low-level key/value database for Go. 【🌟Star 10421】

* [buntdb](https://github.com/tidwall/buntdb) - Fast, embeddable, in-memory key/value database for Go with custom indexing and spatial support. 【🌟Star 2596】

* [cache](https://github.com/akyoto/cache) - In-memory key:value store with expiration time, 0 dependencies, <100 LoC, 100% coverage. 【🌟Star 30】

* [cache2go](https://github.com/muesli/cache2go) - In-memory key:value cache which supports automatic invalidation based on timeouts. 【🌟Star 1189】

* [clusteredBigCache](https://github.com/oaStuff/clusteredBigCache) - BigCache with clustering support and individual item expiration. 【🌟Star 32】

* [cockroach](https://github.com/cockroachdb/cockroach) - Scalable, Geo-Replicated, Transactional Datastore. 【🌟Star 17619】

* [Coffer](https://github.com/claygod/coffer) - Simple ACID key-value database that supports transactions. 【🌟Star 18】

* [couchcache](https://github.com/codingsince1985/couchcache) - RESTful caching micro-service backed by Couchbase server. 【🌟Star 46】

* [CovenantSQL](https://github.com/CovenantSQL/CovenantSQL) - CovenantSQL is a SQL database on blockchain. 【🌟Star 975】

* [dgraph](https://github.com/dgraph-io/dgraph) - Scalable, Distributed, Low Latency, High Throughput Graph Database. 【🌟Star 12188】

* [diskv](https://github.com/peterbourgon/diskv) - Home-grown disk-backed key-value store. 【🌟Star 842】

* [eliasdb](https://github.com/krotik/eliasdb) - Dependency-free, transactional graph database with REST API, phrase search and SQL-like query language. 【🌟Star 555】

* [fastcache](https://github.com/VictoriaMetrics/fastcache) - fast thread-safe inmemory cache for big number of entries. Minimizes GC overhead. 【🌟Star 667】

* [GCache](https://github.com/bluele/gcache) - Cache library with support for expirable Cache, LFU, LRU and ARC. 【🌟Star 1036】

* [go-cache](https://github.com/pmylund/go-cache) - In-memory key:value store/cache (similar to Memcached) library for Go, suitable for single-machine applications. 【🌟Star 3406】

* [goleveldb](https://github.com/syndtr/goleveldb) - Implementation of the [LevelDB](https://github.com/google/leveldb) key/value database in Go. 【🌟Star 3506】

* [gorocksdb](https://github.com/kapitan-k/gorocksdb) - Gorocksdb is a wrapper for [RocksDB](https://rocksdb.org) written in Go. 【🌟Star 12】

* [groupcache](https://github.com/golang/groupcache) - Groupcache is a caching and cache-filling library, intended as a replacement for memcached in many cases. 【🌟Star 8156】

* [influxdb](https://github.com/influxdb/influxdb) - Scalable datastore for metrics, events, and real-time analytics. 【🌟Star 18155】

* [Kivik](https://github.com/go-kivik/kivik) - Kivik provides a common Go and GopherJS client library for CouchDB, PouchDB, and similar databases. 【🌟Star 140】

* [ledisdb](https://github.com/siddontang/ledisdb) - Ledisdb is a high performance NoSQL like Redis based on LevelDB. 【🌟Star 3200】

* [levigo](https://github.com/jmhodges/levigo) - Levigo is a Go wrapper for LevelDB. 【🌟Star 377】

* [moss](https://github.com/couchbase/moss) - Moss is a simple LSM key-value storage engine written in 100% Go. 【🌟Star 745】

* [nutsdb](https://github.com/xujiajun/nutsdb) - Nutsdb is a simple, fast, embeddable, persistent key/value store written in pure Go. It supports fully serializable transactions and many data structures such as  list, set, sorted set. 【🌟Star 1072】

* [piladb](https://github.com/fern4lvarez/piladb) - Lightweight RESTful database engine based on stack data structures. 【🌟Star 172】

* [prometheus](https://github.com/prometheus/prometheus) - Monitoring system and time series database. 【🌟Star 28706】

* [pudge](https://github.com/recoilme/pudge) - Fast and simple  key/value store written using Go's standard library. 【🌟Star 237】

* [rqlite](https://github.com/rqlite/rqlite) - The lightweight, distributed, relational database built on SQLite. 【🌟Star 5418】

* [Scribble](https://github.com/nanobox-io/golang-scribble) - Tiny flat file JSON store. 【🌟Star 82】

* [slowpoke](https://github.com/recoilme/slowpoke) - Key-value store with persistence. 【🌟Star 93】

* [tempdb](https://github.com/rafaeljesus/tempdb) - Key-value store for temporary items. 【🌟Star 14】

* [tidb](https://github.com/pingcap/tidb) - TiDB is a distributed SQL database. Inspired by the design of Google F1. 【🌟Star 22277】

* [tiedot](https://github.com/HouzuoGuo/tiedot) - Your NoSQL database powered by Golang. 【🌟Star 2431】

* [tracedb](https://github.com/unit-io/tracedb) - Fast timeseries database for IoT, realtime messaging  applications. Access tracedb with pubsub over tcp or websocket using github.com/unit-io/trace application. 【🌟Star 6】

* [Vasto](https://github.com/chrislusf/vasto) - A distributed high-performance key-value store. On Disk. Eventual consistent. HA. Able to grow or shrink without service interruption. 【🌟Star 167】

* [VictoriaMetrics](https://github.com/VictoriaMetrics/VictoriaMetrics) - fast, resource-effective and scalable open source time series database. May be used as long-term remote storage for Prometheus. Supports PromQL. 【🌟Star 1651】


*Database schema migration.*

* [avro](https://github.com/khezen/avro) - Discover SQL schemas and convert them to AVRO schemas. Query SQL records into AVRO bytes. 【🌟Star 10】

* [darwin](https://github.com/GuiaBolso/darwin) - Database schema evolution library for Go. 【🌟Star 96】

* [go-fixtures](https://github.com/RichardKnop/go-fixtures) - Django style fixtures for Golang's excellent built-in database/sql library. 【🌟Star 22】

* [go-pg-migrations](https://github.com/robinjoseph08/go-pg-migrations) - A Go package to help write migrations with go-pg/pg. 【🌟Star 38】

* [gondolier](https://github.com/emvi/gondolier) - Database migration library using struct decorators. 【🌟Star 26】

* [goose](https://github.com/steinbacher/goose) - Database migration tool. You can manage your database's evolution by creating incremental SQL or Go scripts. 【🌟Star 130】

* [gormigrate](https://github.com/go-gormigrate/gormigrate) - Database schema migration helper for Gorm ORM. 【🌟Star 394】

* [migrate](https://github.com/golang-migrate/migrate) - Database migrations. CLI and Golang library. 【🌟Star 3496】

* [migrator](https://github.com/lopezator/migrator) - Dead simple Go database migration library. 【🌟Star 84】

* [pravasan](https://github.com/pravasan/pravasan) - Simple Migration tool - currently for MySQL but planning to soon support Postgres, SQLite, MongoDB, etc. 【🌟Star 24】

* [schema](https://github.com/adlio/schema) - Library to embed schema migrations for database/sql-compatible databases inside your Go binaries. 【🌟Star 4】

* [skeema](https://github.com/skeema/skeema) - Pure-SQL schema management system for MySQL, with support for sharding and external online schema change tools. 【🌟Star 502】

* [soda](https://github.com/gobuffalo/pop/tree/master/soda) - Database migration, creation, ORM, etc... for MySQL, PostgreSQL, and SQLite.
* [sql-migrate](https://github.com/rubenv/sql-migrate) - Database migration tool. Allows embedding migrations into the application using go-bindata. 【🌟Star 1573】


*Database tools.*

* [bucket](https://github.com/PumpkinSeed/bucket) - Optimized data structure framework for Couchbase specialized on one bucket usage. 【🌟Star 6】

* [chproxy](https://github.com/Vertamedia/chproxy) - HTTP proxy for ClickHouse database. 【🌟Star 355】

* [clickhouse-bulk](https://github.com/nikepan/clickhouse-bulk) - Collects small insterts and sends big requests to ClickHouse servers. 【🌟Star 166】

* [datagen](https://github.com/codingconcepts/datagen) - A fast data generator that's multi-table aware and supports multi-row DML. 【🌟Star 13】

* [dbbench](https://github.com/sj14/dbbench) - Database benchmarking tool with support for several databases and scripts. 【🌟Star 32】

* [go-mysql](https://github.com/siddontang/go-mysql) - Go toolset to handle MySQL protocol and replication. 【🌟Star 2174】

* [go-mysql-elasticsearch](https://github.com/siddontang/go-mysql-elasticsearch) - Sync your MySQL data into Elasticsearch automatically. 【🌟Star 2743】

* [kingshard](https://github.com/flike/kingshard) - kingshard is a high performance proxy for MySQL powered by Golang. 【🌟Star 4967】

* [myreplication](https://github.com/2tvenom/myreplication) - MySql binary log replication listener. Supports statement and row based replication. 【🌟Star 155】

* [octillery](https://github.com/knocknote/octillery) - Go package for sharding databases ( Supports every ORM or raw SQL ). 【🌟Star 71】

* [orchestrator](https://github.com/github/orchestrator) - MySQL replication topology manager & visualizer. 【🌟Star 3310】

* [pgweb](https://github.com/sosedoff/pgweb) - Web-based PostgreSQL database browser. 【🌟Star 6228】

* [prep](https://github.com/hexdigest/prep) - Use prepared SQL statements without changing your code. 【🌟Star 25】

* [pREST](https://github.com/nuveo/prest) - Serve a RESTful API from any PostgreSQL database. 【🌟Star 2177】

* [rwdb](https://github.com/andizzle/rwdb) - rwdb provides read replica capability for multiple database servers setup. 【🌟Star 10】

* [vitess](https://github.com/youtube/vitess) - vitess provides servers and tools which facilitate scaling of MySQL databases for large scale web services. 【🌟Star 9377】


*SQL query builder, libraries for building and using SQL.*

* [dbq](https://github.com/rocketlaunchr/dbq) - Zero boilerplate database operations for Go. 【🌟Star 89】

* [Dotsql](https://github.com/gchaincl/dotsql) - Go library that helps you keep sql files in one place and use them with ease. 【🌟Star 493】

* [gendry](https://github.com/didi/gendry) - Non-invasive SQL builder and powerful data binder. 【🌟Star 930】

* [godbal](https://github.com/xujiajun/godbal) - Database Abstraction Layer (dbal) for go. Support SQL builder and get result easily. 【🌟Star 50】

* [goqu](https://github.com/doug-martin/goqu) - Idiomatic SQL builder and query library. 【🌟Star 714】

* [igor](https://github.com/galeone/igor) - Abstraction layer for PostgreSQL that supports advanced functionality and uses gorm-like syntax. 【🌟Star 78】

* [jet](https://github.com/go-jet/jet) - Framework for writing type-safe SQL queries in Go, with ability to easily convert database query result into desired arbitrary object structure. 【🌟Star 191】

* [ormlite](https://github.com/pupizoid/ormlite) - Lightweight package containing some ORM-like features and helpers for sqlite databases. 【🌟Star 0】

* [ozzo-dbx](https://github.com/go-ozzo/ozzo-dbx) - Powerful data retrieval methods as well as DB-agnostic query building capabilities. 【🌟Star 454】

* [qry](https://github.com/HnH/qry) - Tool that generates constants from files with raw SQL queries. 【🌟Star 4】

* [scaneo](https://github.com/variadico/scaneo) - Generate Go code to convert database rows into arbitrary structs. 【🌟Star 0】

* [sqlf](https://github.com/leporo/sqlf) - Fast SQL query builder. 【🌟Star 7】

* [sqrl](https://github.com/elgris/sqrl) - SQL query builder, fork of Squirrel with improved performance. 【🌟Star 197】

* [Squalus](https://gitlab.com/qosenergy/squalus) - Thin layer over the Go SQL package that makes it easier to perform queries.
* [Squirrel](https://github.com/Masterminds/squirrel) - Go library that helps you build SQL queries. 【🌟Star 2666】

* [xo](https://github.com/knq/xo) - Generate idiomatic Go code for databases based on existing schema definitions or custom queries supporting PostgreSQL, MySQL, SQLite, Oracle, and Microsoft SQL Server. 【🌟Star 2350】


## Database Drivers

*Libraries for connecting and operating databases.*

* Relational Databases
    * [avatica](https://github.com/apache/calcite-avatica-go) - Apache Avatica/Phoenix SQL driver for database/sql. 【🌟Star 46】

    * [bgc](https://github.com/viant/bgc) - Datastore Connectivity for BigQuery for go. 【🌟Star 12】

    * [firebirdsql](https://github.com/nakagami/firebirdsql) - Firebird RDBMS SQL driver for Go. 【🌟Star 114】

    * [go-adodb](https://github.com/mattn/go-adodb) - Microsoft ActiveX Object DataBase driver for go that uses database/sql. 【🌟Star 97】

    * [go-mssqldb](https://github.com/denisenkom/go-mssqldb) - Microsoft MSSQL driver for Go. 【🌟Star 1126】

    * [go-oci8](https://github.com/mattn/go-oci8) - Oracle driver for go that uses database/sql. 【🌟Star 429】

    * [go-sql-driver/mysql](https://github.com/go-sql-driver/mysql) - MySQL driver for Go. 【🌟Star 8903】

    * [go-sqlite3](https://github.com/mattn/go-sqlite3) - SQLite3 driver for go that uses database/sql. 【🌟Star 3746】

    * [gofreetds](https://github.com/minus5/gofreetds) - Microsoft MSSQL driver. Go wrapper over [FreeTDS](http://www.freetds.org). 【🌟Star 94】

    * [goracle](https://github.com/go-goracle/goracle) - Oracle driver for Go, using the ODPI-C driver. 【🌟Star 279】

    * [pgx](https://github.com/jackc/pgx) - PostgreSQL driver supporting features beyond those exposed by database/sql. 【🌟Star 2286】

    * [pq](https://github.com/lib/pq) - Pure Go Postgres driver for database/sql. 【🌟Star 5582】


* NoSQL Databases
    * [aerospike-client-go](https://github.com/aerospike/aerospike-client-go) - Aerospike client in Go language. 【🌟Star 315】

    * [arangolite](https://github.com/solher/arangolite) - Lightweight golang driver for ArangoDB. 【🌟Star 66】

    * [asc](https://github.com/viant/asc) - Datastore Connectivity for Aerospike for go. 【🌟Star 4】

    * [dynago](https://github.com/underarmour/dynago) - Dynago is a principle of least surprise client for DynamoDB. 【🌟Star 66】

    * [forestdb](https://github.com/couchbase/goforestdb) - Go bindings for ForestDB. 【🌟Star 28】

    * [go-couchbase](https://github.com/couchbase/go-couchbase) - Couchbase client in Go. 【🌟Star 297】

    * [go-pilosa](https://github.com/pilosa/go-pilosa) - Go client library for Pilosa. 【🌟Star 34】

    * [go-rejson](https://github.com/nitishm/go-rejson) - Golang client for redislabs' ReJSON module using Redigo golang client. Store and manipulate structs as JSON objects in redis with ease. 【🌟Star 109】

    * [gocb](https://github.com/couchbase/gocb) - Official Couchbase Go SDK. 【🌟Star 307】

    * [gocql](http://gocql.github.io) - Go language driver for Apache Cassandra.
    * [godis](https://github.com/piaohao/godis) - redis client implement by golang, inspired by jedis. 【🌟Star 67】

    * [godscache](https://github.com/defcronyke/godscache) - A wrapper for the Google Cloud Platform Go Datastore package that adds caching using memcached. 【🌟Star 6】

    * [gomemcache](https://github.com/bradfitz/gomemcache/) - memcache client library for the Go programming language. 【🌟Star 0】

    * [gorethink](https://github.com/dancannon/gorethink) - Go language driver for RethinkDB. 【🌟Star 1495】

    * [goriak](https://github.com/zegl/goriak) - Go language driver for Riak KV. 【🌟Star 24】

    * [mgm](https://github.com/kamva/mgm) - MongoDB model-based ODM for Go (based on official MongoDB driver). 【🌟Star 40】

    * [mgo](https://github.com/globalsign/mgo) - (unmaintained) MongoDB driver for the Go language that implements a rich and well tested selection of features under a very simple API following standard Go idioms. 【🌟Star 1736】

    * [mongo-go-driver](https://github.com/mongodb/mongo-go-driver) - Official MongoDB driver for the Go language. 【🌟Star 3908】

    * [neo4j](https://github.com/cihangir/neo4j) - Neo4j Rest API Bindings for Golang. 【🌟Star 25】

    * [Neo4j-GO](https://github.com/davemeehan/Neo4j-GO) - Neo4j REST Client in golang. 【🌟Star 74】

    * [neoism](https://github.com/jmcvetta/neoism) - Neo4j client for Golang. 【🌟Star 362】

    * [redeo](https://github.com/bsm/redeo) - Redis-protocol compatible TCP servers/services. 【🌟Star 362】

    * [redigo](https://github.com/gomodule/redigo) - Redigo is a Go client for the Redis database. 【🌟Star 6911】

    * [redis](https://github.com/go-redis/redis) - Redis client for Golang. 【🌟Star 7801】

    * [xredis](https://github.com/shomali11/xredis) - Typesafe, customizable, clean & easy to use Redis client. 【🌟Star 10】


* Search and Analytic Databases.
    * [bleve](https://github.com/blevesearch/bleve) - Modern text indexing library for go. 【🌟Star 6248】

    * [elastic](https://github.com/olivere/elastic) - Elasticsearch client for Go. 【🌟Star 4660】

    * [elasticsql](https://github.com/cch123/elasticsql) - Convert sql to elasticsearch dsl in Go. 【🌟Star 480】

    * [elastigo](https://github.com/mattbaird/elastigo) - Elasticsearch client library. 【🌟Star 954】

    * [go-elasticsearch](https://github.com/elastic/go-elasticsearch) - Official Elasticsearch client for Go. 【🌟Star 2102】

    * [goes](https://github.com/OwnLocal/goes) - Library to interact with Elasticsearch. 【🌟Star 24】

    * [riot](https://github.com/go-ego/riot) - Go Open Source, Distributed, Simple and efficient Search Engine. 【🌟Star 5009】

    * [skizze](https://github.com/seiflotfy/skizze) - probabilistic data-structures service and storage. 【🌟Star 69】


* Multiple Backends.
    * [cachego](https://github.com/fabiorphp/cachego) - Golang Cache component for multiple drivers. 【🌟Star 113】

    * [cayley](https://github.com/google/cayley) - Graph database with support for multiple backends. 【🌟Star 13120】

    * [dsc](https://github.com/viant/dsc) - Datastore connectivity for SQL, NoSQL, structured files. 【🌟Star 14】

    * [gokv](https://github.com/philippgille/gokv) - Simple key-value store abstraction and implementations for Go (Redis, Consul, etcd, bbolt, BadgerDB, LevelDB, Memcached, DynamoDB, S3, PostgreSQL, MongoDB, CockroachDB and many more). 【🌟Star 155】


## Date and Time

*Libraries for working with dates and times.*

* [carbon](https://github.com/uniplaces/carbon) - Simple Time extension with a lot of util methods, ported from PHP Carbon library. 【🌟Star 383】

* [cronrange](https://github.com/1set/cronrange) - Parses Cron-style time range expressions, checks if the given time is within any ranges. 【🌟Star 6】

* [date](https://github.com/rickb777/date) - Augments Time for working with dates, date ranges, time spans, periods, and time-of-day. 【🌟Star 34】

* [dateparse](https://github.com/araddon/dateparse) - Parse date's without knowing format in advance. 【🌟Star 962】

* [durafmt](https://github.com/hako/durafmt) - Time duration formatting library for Go. 【🌟Star 273】

* [feiertage](https://github.com/wlbr/feiertage) - Set of functions to calculate public holidays in Germany, incl. specialization on the states of Germany (Bundesländer). Things like Easter, Pentecost, Thanksgiving... 【🌟Star 24】

* [go-persian-calendar](https://github.com/yaa110/go-persian-calendar) - The implementation of the Persian (Solar Hijri) Calendar in Go (golang). 【🌟Star 66】

* [go-sunrise](https://github.com/nathan-osman/go-sunrise) - Calculate the sunrise and sunset times for a given location. 【🌟Star 17】

* [go-week](https://github.com/stoewer/go-week) - An efficient package to work with ISO8601 week dates. 【🌟Star 2】

* [iso8601](https://github.com/relvacode/iso8601) - Efficiently parse ISO8601 date-times without regex. 【🌟Star 69】

* [kair](https://github.com/GuilhermeCaruso/kair) - Date and Time - Golang Formatting Library. 【🌟Star 12】

* [now](https://github.com/jinzhu/now) - Now is a time toolkit for golang. 【🌟Star 2366】

* [NullTime](https://github.com/kirillDanshin/nulltime) - Nullable `time.Time`. 【🌟Star 9】

* [strftime](https://github.com/awoodbeck/strftime) - C99-compatible strftime formatter. 【🌟Star 4】

* [timespan](https://github.com/SaidinWoT/timespan) - For interacting with intervals of time, defined as a start time and a duration. 【🌟Star 67】

* [timeutil](https://github.com/leekchan/timeutil) - Useful extensions (Timedelta, Strftime, ...) to the golang's time package. 【🌟Star 174】

* [tuesday](https://github.com/osteele/tuesday) - Ruby-compatible Strftime function. 【🌟Star 7】


## Distributed Systems

*Packages that help with building Distributed Systems.*

* [celeriac](https://github.com/svcavallar/celeriac.v1) - Library for adding support for interacting and monitoring Celery workers, tasks and events in Go. 【🌟Star 59】

* [consistent](https://github.com/buraksezer/consistent) - Consistent hashing with bounded loads. 【🌟Star 258】

* [dht](https://github.com/anacrolix/dht) - BitTorrent Kademlia DHT implementation. 【🌟Star 145】

* [digota](https://github.com/digota/digota) - grpc ecommerce microservice. 【🌟Star 322】

* [dot](https://github.com/dotchain/dot/) - distributed sync using operational transformation/OT. 【🌟Star 0】

* [doublejump](https://github.com/edwingeng/doublejump) - A revamped Google's jump consistent hash. 【🌟Star 47】

* [dragonboat](https://github.com/lni/dragonboat) - A feature complete and high performance multi-group Raft library in Go. 【🌟Star 2853】

* [drmaa](https://github.com/dgruber/drmaa) - Job submission library for cluster schedulers based on the DRMAA standard. 【🌟Star 28】

* [dynamolock](https://cirello.io/dynamolock) - DynamoDB-backed distributed locking implementation.
* [dynatomic](https://github.com/tylfin/dynatomic) - A library for using DynamoDB as an atomic counter. 【🌟Star 10】

* [emitter-io](https://github.com/emitter-io/emitter) - High performance, distributed, secure and low latency publish-subscribe platform built with MQTT, Websockets and love. 【🌟Star 2188】

* [flowgraph](https://github.com/vectaport/flowgraph) - flow-based programming package. 【🌟Star 25】

* [gleam](https://github.com/chrislusf/gleam) - Fast and scalable distributed map/reduce system written in pure Go and Luajit, combining Go's high concurrency with Luajit's high performance, runs standalone or distributed. 【🌟Star 2367】

* [glow](https://github.com/chrislusf/glow) - Easy-to-Use scalable distributed big data processing, Map-Reduce, DAG execution, all in pure Go. 【🌟Star 2730】

* [go-health](https://github.com/InVisionApp/go-health) - Library for enabling asynchronous dependency health checks in your service. 【🌟Star 522】

* [go-jump](https://github.com/dgryski/go-jump) - Port of Google's "Jump" Consistent Hash function. 【🌟Star 278】

* [go-kit](https://github.com/go-kit/kit) - Microservice toolkit with support for service discovery, load balancing, pluggable transports, request tracking, etc. 【🌟Star 16039】

* [go-sundheit](https://github.com/AppsFlyer/go-sundheit) - A library built to provide support for defining async service health checks for golang services. 【🌟Star 280】

* [gorpc](https://github.com/valyala/gorpc) - Simple, fast and scalable RPC library for high load. 【🌟Star 575】

* [grpc-go](https://github.com/grpc/grpc-go) - The Go language implementation of gRPC. HTTP/2 based RPC. 【🌟Star 10479】

* [hprose](https://github.com/hprose/hprose-golang) - Very newbility RPC Library, support 25+ languages now. 【🌟Star 1062】

* [jsonrpc](https://github.com/osamingo/jsonrpc) - The jsonrpc package helps implement of JSON-RPC 2.0. 【🌟Star 118】

* [jsonrpc](https://github.com/ybbus/jsonrpc) - JSON-RPC 2.0 HTTP client implementation. 【🌟Star 111】

* [KrakenD](https://github.com/devopsfaith/krakend) - Ultra performant API Gateway framework with middlewares. 【🌟Star 2269】

* [liftbridge](https://github.com/liftbridge-io/liftbridge) - Lightweight, fault-tolerant message streams for NATS. 【🌟Star 1430】

* [micro](https://github.com/micro/micro) - Pluggable microservice toolkit and distributed systems platform. 【🌟Star 7426】

* [NATS](https://github.com/nats-io/gnatsd) - Lightweight, high performance messaging system for microservices, IoT, and cloud native systems. 【🌟Star 7141】

* [outboxer](https://github.com/italolelis/outboxer) - Outboxer is a go library that implements the outbox pattern. 【🌟Star 23】

* [pglock](https://cirello.io/pglock) - PostgreSQL-backed distributed locking implementation.
* [raft](https://github.com/hashicorp/raft) - Golang implementation of the Raft consensus protocol, by HashiCorp. 【🌟Star 3189】

* [raft](https://github.com/coreos/etcd/tree/master/raft) - Go implementation of the Raft consensus protocol, by CoreOS.
* [rain](https://github.com/cenkalti/rain) - BitTorrent client and library. 【🌟Star 391】

* [redis-lock](https://github.com/bsm/redislock) - Simplified distributed locking implementation using Redis. 【🌟Star 84】

* [resgate](https://resgate.io/) - Realtime API Gateway for building REST, real time, and RPC APIs, where all clients are synchronized seamlessly.
* [ringpop-go](https://github.com/uber/ringpop-go) - Scalable, fault-tolerant application-layer sharding for Go applications. 【🌟Star 599】

* [rpcx](https://github.com/smallnest/rpcx) - Distributed pluggable RPC service framework like alibaba Dubbo. 【🌟Star 4265】

* [sleuth](https://github.com/ursiform/sleuth) - Library for master-less p2p auto-discovery and RPC between HTTP services (using [ZeroMQ](https://github.com/zeromq/libzmq)). 【🌟Star 312】

* [tendermint](https://github.com/tendermint/tendermint) - High-performance middleware for transforming a state machine written in any programming language into a Byzantine Fault Tolerant replicated state machine using the Tendermint consensus and blockchain protocols. 【🌟Star 3462】

* [torrent](https://github.com/anacrolix/torrent) - BitTorrent client package. 【🌟Star 3279】


## Dynamic DNS

*Tools for updating dynamic DNS records.*

* [DDNS](https://github.com/skibish/ddns) - Personal DDNS client with Digital Ocean Networking DNS as backend. 【🌟Star 122】

* [dyndns](https://gitlab.com/alcastle/dyndns) - Background Go process to regularly and automatically check your IP Address and make updates to (one or many) Dynamic DNS records for Google domains whenever your address changes.
* [GoDNS](https://github.com/timothyye/godns) - A dynamic DNS client tool, supports DNSPod & HE.net, written in Go. 【🌟Star 519】


## Email

*Libraries and tools that implement email creation and sending.*

* [chasquid](https://blitiri.com.ar/p/chasquid) - SMTP server written in Go.
* [douceur](https://github.com/aymerick/douceur) - CSS inliner for your HTML emails. 【🌟Star 167】

* [email](https://github.com/jordan-wright/email) - A robust and flexible email library for Go. 【🌟Star 1190】

* [go-dkim](https://github.com/toorop/go-dkim) - DKIM library, to sign & verify email. 【🌟Star 52】

* [go-imap](https://github.com/emersion/go-imap) - IMAP library for clients and servers. 【🌟Star 861】

* [go-message](https://github.com/emersion/go-message) - Streaming library for the Internet Message Format and mail messages. 【🌟Star 131】

* [go-premailer](https://github.com/vanng822/go-premailer) - Inline styling for HTML mail in Go. 【🌟Star 43】

* [go-simple-mail](https://github.com/xhit/go-simple-mail) - Very simple package to send emails with SMTP Keep Alive and two timeouts: Connect and Send. 【🌟Star 13】

* [Hectane](https://github.com/hectane/hectane) - Lightweight SMTP client providing an HTTP API. 【🌟Star 173】

* [hermes](https://github.com/matcornic/hermes) - Golang package that generates clean, responsive HTML e-mails. 【🌟Star 1749】

* [mailchain](https://github.com/mailchain/mailchain) - Send encrypted emails to blockchain addresses written in Go. 【🌟Star 32】

* [mailgun-go](https://github.com/mailgun/mailgun-go) - Go library for sending mail with the Mailgun API. 【🌟Star 425】

* [MailHog](https://github.com/mailhog/MailHog) - Email and SMTP testing with web and API interface. 【🌟Star 5790】

* [SendGrid](https://github.com/sendgrid/sendgrid-go) - SendGrid's Go library for sending email. 【🌟Star 555】

* [smtp](https://github.com/mailhog/smtp) - SMTP server protocol state machine. 【🌟Star 53】


## Embeddable Scripting Languages

*Embedding other languages inside your go code.*

* [anko](https://github.com/mattn/anko) - Scriptable interpreter written in Go. 【🌟Star 977】

* [binder](https://github.com/alexeyco/binder) - Go to Lua binding library, based on [gopher-lua](https://github.com/yuin/gopher-lua). 【🌟Star 34】

* [cel-go](https://github.com/google/cel-go) - Fast, portable, non-Turing complete expression evaluation with gradual typing. 【🌟Star 357】

* [expr](https://github.com/antonmedv/expr) - an engine that can evaluate expressions. 【🌟Star 1053】

* [gentee](https://github.com/gentee/gentee) - Embeddable scripting programming language. 【🌟Star 40】

* [gisp](https://github.com/jcla1/gisp) - Simple LISP in Go. 【🌟Star 432】

* [go-duktape](https://github.com/olebedev/go-duktape) - Duktape JavaScript engine bindings for Go. 【🌟Star 678】

* [go-lua](https://github.com/Shopify/go-lua) - Port of the Lua 5.2 VM to pure Go. 【🌟Star 1766】

* [go-php](https://github.com/deuill/go-php) - PHP bindings for Go. 【🌟Star 724】

* [go-python](https://github.com/sbinet/go-python) - naive go bindings to the CPython C-API. 【🌟Star 986】

* [golua](https://github.com/aarzilli/golua) - Go bindings for Lua C API. 【🌟Star 457】

* [gopher-lua](https://github.com/yuin/gopher-lua) - Lua 5.1 VM and compiler written in Go. 【🌟Star 3226】

* [gval](https://github.com/PaesslerAG/gval) - A highly customizable expression language written in Go. 【🌟Star 174】

* [ngaro](https://github.com/db47h/ngaro) - Embeddable Ngaro VM implementation enabling scripting in Retro. 【🌟Star 19】

* [otto](https://github.com/robertkrimen/otto) - JavaScript interpreter written in Go. 【🌟Star 5059】

* [purl](https://github.com/ian-kent/purl) - Perl 5.18.2 embedded in Go. 【🌟Star 29】

* [tengo](https://github.com/d5/tengo) - Bytecode compiled script language for Go. 【🌟Star 1523】


## Error Handling

*Libraries for handling errors.*

* [emperror](https://github.com/emperror/emperror) - Error handling tools and best practices for Go libraries and applications. 【🌟Star 96】

* [eris](https://github.com/rotisserie/eris) - A better way to handle, trace, and log errors in Go. Compatible with the standard error library and github.com/pkg/errors. 【🌟Star 442】

* [errlog](https://github.com/snwfdhmp/errlog) - Hackable package that determines responsible source code for an error (and some other fast-debugging features). Pluggable to any logger in-place. 【🌟Star 275】

* [errors](https://github.com/emperror/errors) - Drop-in replacement for the standard library errors package and github.com/pkg/errors. Provides various error handling primitives. 【🌟Star 37】

* [errors](https://github.com/pkg/errors) - Package that provides simple error handling primitives. 【🌟Star 5454】

* [errors](https://github.com/neuronlabs/errors) - Simple golang error handling with classification primitives. 【🌟Star 4】

* [errorx](https://github.com/joomcode/errorx) - A feature rich error package with stack traces, composition of errors and more. 【🌟Star 602】

* [Falcon](https://github.com/SonicRoshan/falcon) - A Simple Yet Highly Powerful Package For Error Handling. 【🌟Star 2】

* [go-multierror](https://github.com/hashicorp/go-multierror) - Go (golang) package for representing a list of errors as a single error. 【🌟Star 800】

* [tracerr](https://github.com/ztrue/tracerr) - Golang errors with stack trace and source fragments. 【🌟Star 578】

* [werr](https://github.com/txgruppi/werr) - Error Wrapper creates an wrapper for the error type in Go which captures the File, Line and Stack of where it was called. 【🌟Star 12】


## Files

*Libraries for handling files and file systems.*

* [afero](https://github.com/spf13/afero) - FileSystem Abstraction System for Go. 【🌟Star 2506】

* [afs](https://github.com/viant/afs) - Abstract File Storage (mem, scp, zip, tar, cloud: s3, gs) for Go. 【🌟Star 28】

* [bigfile](https://github.com/bigfile/bigfile) - A file transfer system, support to manage files with http api, rpc call and ftp client. 【🌟Star 98】

* [checksum](https://github.com/codingsince1985/checksum) - Compute message digest, like MD5 and SHA256, for large files. 【🌟Star 15】

* [flop](https://github.com/homedepot/flop) - File operations library which aims to mirror feature parity with [GNU cp](https://www.gnu.org/software/coreutils/manual/html_node/cp-invocation.html). 【🌟Star 14】

* [go-csv-tag](https://github.com/artonge/go-csv-tag) - Load csv file using tag. 【🌟Star 61】

* [go-decent-copy](https://github.com/hugocarreira/go-decent-copy) - Copy files for humans. 【🌟Star 14】

* [go-exiftool](https://github.com/barasher/go-exiftool) - Go bindings for ExifTool, the well-known library used to extract as much metadata as possible (EXIF, IPTC, ...) from files (pictures, PDF, office, ...). 【🌟Star 21】

* [go-gtfs](https://github.com/artonge/go-gtfs) - Load gtfs files in go. 【🌟Star 18】

* [notify](https://github.com/rjeczalik/notify) - File system event notification library with simple API, similar to os/signal. 【🌟Star 520】

* [opc](https://github.com/qmuntal/opc) - Load Open Packaging Conventions (OPC) files for Go. 【🌟Star 63】

* [parquet](https://github.com/parsyl/parquet) - Read and write [parquet](https://parquet.apache.org) files. 【🌟Star 5】

* [pdfcpu](https://github.com/hhrutter/pdfcpu) - PDF processor. 【🌟Star 1285】

* [skywalker](https://github.com/dixonwille/skywalker) - Package to allow one to concurrently go through a filesystem with ease. 【🌟Star 54】

* [stl](https://gitlab.com/russoj88/stl) - Modules to read and write STL (stereolithography) files.  Concurrent algorithm for reading.
* [tarfs](https://github.com/posener/tarfs) - Implementation of the [`FileSystem` interface](https://godoc.org/github.com/kr/fs#FileSystem) for tar files. 【🌟Star 39】

* [vfs](https://github.com/C2FO/vfs) - A pluggable, extensible, and opinionated set of filesystem functionality for Go across a number of filesystem types such as os, S3, and GCS. 【🌟Star 40】


## Financial

*Packages for accounting and finance.*

* [accounting](https://github.com/leekchan/accounting) - money and currency formatting for golang. 【🌟Star 531】

* [currency](https://github.com/bnkamalesh/currency) - High performant & accurate currency computation package. 【🌟Star 18】

* [decimal](https://github.com/shopspring/decimal) - Arbitrary-precision fixed-point decimal numbers. 【🌟Star 1878】

* [go-finance](https://github.com/FlashBoys/go-finance) - Comprehensive financial markets data in Go. 【🌟Star 537】

* [go-finance](https://github.com/alpeb/go-finance) - Library of financial functions for time value of money (annuities), cash flow, interest rate conversions, bonds and depreciation calculations. 【🌟Star 47】

* [go-finance](https://github.com/pieterclaerhout/go-finance) - Module to fetch exchange rates, check VAT numbers via VIES and check IBAN bank account numbers. 【🌟Star 2】

* [go-money](https://github.com/rhymond/go-money) - Implementation of Fowler's Money pattern. 【🌟Star 686】

* [ofxgo](https://github.com/aclindsa/ofxgo) - Query OFX servers and/or parse the responses (with example command-line client). 【🌟Star 71】

* [orderbook](https://github.com/i25959341/orderbook) - Matching Engine for Limit Order Book in Golang. 【🌟Star 116】

* [techan](https://github.com/sdcoffey/techan) - Technical analysis library with advanced market analysis and trading strategies. 【🌟Star 213】

* [transaction](https://github.com/claygod/transaction) - Embedded transactional database of accounts, running in multithreaded mode. 【🌟Star 62】

* [vat](https://github.com/dannyvankooten/vat) - VAT number validation & EU VAT rates. 【🌟Star 64】


## Forms

*Libraries for working with forms.*

* [bind](https://github.com/robfig/bind) - Bind form data to any Go values. 【🌟Star 24】

* [binding](https://github.com/mholt/binding) - Binds form and JSON data from net/http Request to struct. 【🌟Star 761】

* [conform](https://github.com/leebenson/conform) - Keeps user input in check. Trims, sanitizes & scrubs data based on struct tags. 【🌟Star 183】

* [form](https://github.com/go-playground/form) - Decodes url.Values into Go value(s) and Encodes Go value(s) into url.Values. Dual Array and Full map support. 【🌟Star 387】

* [formam](https://github.com/monoculum/formam) - decode form's values into a struct. 【🌟Star 135】

* [forms](https://github.com/albrow/forms) - Framework-agnostic library for parsing and validating form/JSON data which supports multipart forms and files. 【🌟Star 106】

* [gorilla/csrf](https://github.com/gorilla/csrf) - CSRF protection for Go web applications & services. 【🌟Star 488】

* [nosurf](https://github.com/justinas/nosurf) - CSRF protection middleware for Go. 【🌟Star 1021】

* [queryparam](https://github.com/tomwright/queryparam) - Decode `url.Values` into usable struct values of standard or custom types. 【🌟Star 1】


## Functional

*Packages to support functional programming in Go.*

* [fpGo](https://github.com/TeaEntityLab/fpGo) - Monad, Functional Programming features for Golang. 【🌟Star 133】

* [fuego](https://github.com/seborama/fuego) - Functional Experiment in Go. 【🌟Star 60】

* [go-underscore](https://github.com/tobyhede/go-underscore) - Useful collection of helpfully functional Go collection utilities. 【🌟Star 1112】


## Game Development

*Awesome game development libraries.*

* [Azul3D](https://github.com/azul3d/engine) - 3D game engine written in Go. 【🌟Star 441】

* [Ebiten](https://github.com/hajimehoshi/ebiten) - dead simple 2D game library in Go. 【🌟Star 2422】

* [engo](https://github.com/EngoEngine/engo) - Engo is an open-source 2D game engine written in Go. It follows the Entity-Component-System paradigm. 【🌟Star 1143】

* [g3n](https://github.com/g3n/engine) - Go 3D Game Engine. 【🌟Star 917】

* [GarageEngine](https://github.com/vova616/GarageEngine) - 2d game engine written in Go working on OpenGL. 【🌟Star 318】

* [glop](https://github.com/runningwild/glop) - Glop (Game Library Of Power) is a fairly simple cross-platform game library. 【🌟Star 76】

* [go-astar](https://github.com/beefsack/go-astar) - Go implementation of the A\* path finding algorithm. 【🌟Star 348】

* [go-collada](https://github.com/GlenKelley/go-collada) - Go package for working with the Collada file format. 【🌟Star 15】

* [go-sdl2](https://github.com/veandco/go-sdl2) - Go bindings for the [Simple DirectMedia Layer](https://www.libsdl.org/). 【🌟Star 1256】

* [go3d](https://github.com/ungerik/go3d) - Performance oriented 2D/3D math package for Go. 【🌟Star 171】

* [gonet](https://github.com/xtaci/gonet) - Game server skeleton implemented with golang. 【🌟Star 1080】

* [goworld](https://github.com/xiaonanln/goworld) - Scalable game server engine, featuring space-entity framework and hot-swapping. 【🌟Star 1365】

* [Leaf](https://github.com/name5566/leaf) - Lightweight game server framework. 【🌟Star 3354】

* [nano](https://github.com/lonng/nano) - Lightweight, facility, high performance golang based game server framework. 【🌟Star 1166】

* [Oak](https://github.com/oakmound/oak) - Pure Go game engine. 【🌟Star 696】

* [Pitaya](https://github.com/topfreegames/pitaya) - Scalable game server framework with clustering support and client libraries for iOS, Android, Unity and others through the C SDK. 【🌟Star 438】

* [Pixel](https://github.com/faiface/pixel) - Hand-crafted 2D game library in Go. 【🌟Star 2686】

* [raylib-go](https://github.com/gen2brain/raylib-go) - Go bindings for [raylib](http://www.raylib.com/), a simple and easy-to-use library to learn videogames programming. 【🌟Star 426】

* [termloop](https://github.com/JoelOtter/termloop) - Terminal-based game engine for Go, built on top of Termbox. 【🌟Star 1076】


## Generation and Generics

*Tools to enhance the language with features like generics via code generation.*

* [efaceconv](https://github.com/t0pep0/efaceconv) - Code generation tool for high performance conversion from interface{} to immutable type without allocations. 【🌟Star 44】

* [gen](https://github.com/clipperhouse/gen) - Code generation tool for ‘generics’-like functionality. 【🌟Star 1073】

* [generis](https://github.com/senselogic/GENERIS) - Code generation tool providing generics, free-form macros, conditional compilation and HTML templating. 【🌟Star 20】

* [go-enum](https://github.com/abice/go-enum) - Code generation for enums from code comments. 【🌟Star 94】

* [go-linq](https://github.com/ahmetalpbalkan/go-linq) - .NET LINQ-like query methods for Go. 【🌟Star 1943】

* [go-xray](https://github.com/pieterclaerhout/go-xray) - Helpers for making the use of reflection easier. 【🌟Star 5】

* [goderive](https://github.com/awalterschulze/goderive) - Derives functions from input types. 【🌟Star 778】

* [gotype](https://github.com/wzshiming/gotype) - Golang source code parsing, usage like reflect package. 【🌟Star 28】

* [GoWrap](https://github.com/hexdigest/gowrap) - Generate decorators for Go interfaces using simple templates. 【🌟Star 309】

* [interfaces](https://github.com/rjeczalik/interfaces) - Command line tool for generating interface definitions. 【🌟Star 200】

* [jennifer](https://github.com/dave/jennifer) - Generate arbitrary Go code without templates. 【🌟Star 1423】

* [pkgreflect](https://github.com/ungerik/pkgreflect) - Go preprocessor for package scoped reflection. 【🌟Star 91】


## Geographic

*Geographic tools and servers*

* [geocache](https://github.com/melihmucuk/geocache) - In-memory cache that is suitable for geolocation based applications. 【🌟Star 117】

* [geoserver](https://github.com/hishamkaram/geoserver) - geoserver Is a Go Package For Manipulating a GeoServer Instance via the GeoServer REST API. 【🌟Star 27】

* [gismanager](https://github.com/hishamkaram/gismanager) - Publish Your GIS Data(Vector Data) to PostGIS and Geoserver. 【🌟Star 22】

* [osm](https://github.com/paulmach/osm) - Library for reading, writing and working with OpenStreetMap data and APIs. 【🌟Star 93】

* [pbf](https://github.com/maguro/pbf) - OpenStreetMap PBF golang encoder/decoder. 【🌟Star 19】

* [S2 geometry](https://github.com/golang/geo) - S2 geometry library in Go. 【🌟Star 984】

* [Tile38](https://github.com/tidwall/tile38) - Geolocation DB with spatial index and realtime geofencing. 【🌟Star 6613】

* [WGS84](https://github.com/wroge/wgs84) - Library for Coordinate Conversion and Transformation (ETRS89, OSGB36, NAD83, RGF93, Web Mercator, UTM). 【🌟Star 43】


## Go Compilers

*Tools for compiling Go to other languages.*

* [c4go](https://github.com/Konstantin8105/c4go) - Transpile C code to Go code. 【🌟Star 188】

* [f4go](https://github.com/Konstantin8105/f4go) - Transpile FORTRAN 77 code to Go code. 【🌟Star 23】

* [gopherjs](https://github.com/gopherjs/gopherjs) - Compiler from Go to JavaScript. 【🌟Star 9057】

* [llgo](https://github.com/go-llvm/llgo) - LLVM-based compiler for Go. 【🌟Star 1026】

* [tardisgo](https://github.com/tardisgo/tardisgo) - Golang to Haxe to CPP/CSharp/Java/JavaScript transpiler. 【🌟Star 394】


## Goroutines

*Tools for managing and working with Goroutines.*

* [ants](https://github.com/panjf2000/ants) - A high-performance and low-cost goroutine pool in Go. 【🌟Star 2925】

* [artifex](https://github.com/borderstech/artifex) - Simple in-memory job queue for Golang using worker-based dispatching. 【🌟Star 22】

* [async](https://github.com/studiosol/async) - A safe way to execute functions asynchronously, recovering them in case of panic. 【🌟Star 29】

* [breaker](https://github.com/kamilsk/breaker) - Flexible mechanism to make execution flow interruptible. 【🌟Star 50】

* [conexec](https://github.com/ITcathyh/conexec) - A concurrent toolkit to help execute funcs concurrently in an efficient and safe way.It supports specifying the overall timeout to avoid blocking and uses goroutine pool to improve efficiency. 【🌟Star 2】

* [cyclicbarrier](https://github.com/marusama/cyclicbarrier) - CyclicBarrier for golang. 【🌟Star 43】

* [go-floc](https://github.com/workanator/go-floc) - Orchestrate goroutines with ease. 【🌟Star 175】

* [go-flow](https://github.com/kamildrazkiewicz/go-flow) - Control goroutines execution order. 【🌟Star 121】

* [go-tools/multithreading](https://github.com/nikhilsaraf/go-tools) - Manage a pool of goroutines using this lightweight library with a simple API. 【🌟Star 5】

* [go-trylock](https://github.com/subchen/go-trylock) - TryLock support on read-write lock for Golang. 【🌟Star 5】

* [go-waitgroup](https://github.com/pieterclaerhout/go-waitgroup) - Like `sync.WaitGroup` with error handling and concurrency control. 【🌟Star 3】

* [gohive](https://github.com/loveleshsharma/gohive) - A highly performant and easy to use Goroutine pool for Go. 【🌟Star 10】

* [gollback](https://github.com/vardius/gollback) - asynchronous simple function utilities, for managing execution of closures and callbacks. 【🌟Star 30】

* [GoSlaves](https://github.com/themester/GoSlaves) - Simple and Asynchronous Goroutine pool library. 【🌟Star 88】

* [goworker](https://github.com/benmanns/goworker) - goworker is a Go-based background worker. 【🌟Star 2324】

* [gowp](https://github.com/xxjwxc/gowp) - gowp is concurrency limiting goroutine pool. 【🌟Star 127】

* [gpool](https://github.com/Sherifabdlnaby/gpool) - manages a resizeable pool of context-aware goroutines to bound concurrency. 【🌟Star 61】

* [grpool](https://github.com/ivpusic/grpool) - Lightweight Goroutine pool. 【🌟Star 537】

* [Hunch](https://github.com/AaronJan/Hunch) - Hunch provides functions like: `All`, `First`, `Retry`, `Waterfall` etc., that makes asynchronous flow control more intuitive. 【🌟Star 21】

* [oversight](https://cirello.io/oversight) - Oversight is a complete implementation of the Erlang supervision trees.
* [parallel-fn](https://github.com/rafaeljesus/parallel-fn) - Run functions in parallel. 【🌟Star 26】

* [pool](https://github.com/go-playground/pool) - Limited consumer goroutine or unlimited goroutine pool for easier goroutine handling and cancellation. 【🌟Star 536】

* [queue](https://github.com/AnikHasibul/queue) - Gives you a `sync.WaitGroup` like queue group accessibility. Helps you to throttle and limit goroutines, wait for the end of the all goroutines and much more. 【🌟Star 3】

* [routine](https://github.com/x-mod/routine) - go routine control with context, support: Main, Go, Pool and some useful Executors. 【🌟Star 6】

* [semaphore](https://github.com/kamilsk/semaphore) - Semaphore pattern implementation with timeout of lock/unlock operations based on channel and context. 【🌟Star 82】

* [semaphore](https://github.com/marusama/semaphore) - Fast resizable semaphore implementation based on CAS (faster than channel-based semaphore implementations). 【🌟Star 80】

* [stl](https://github.com/ssgreg/stl) - Software transactional locks based on Software Transactional Memory (STM) concurrency control mechanism. 【🌟Star 11】

* [threadpool](https://github.com/shettyh/threadpool) - Golang threadpool implementation. 【🌟Star 25】

* [tunny](https://github.com/Jeffail/tunny) - Goroutine pool for golang. 【🌟Star 1525】

* [worker-pool](https://github.com/vardius/worker-pool) - goworker is a Go simple async worker pool. 【🌟Star 51】

* [workerpool](https://github.com/gammazero/workerpool) - Goroutine pool that limits the concurrency of task execution, not the number of tasks queued. 【🌟Star 237】


## GUI

*Libraries for building GUI Applications.*

*Toolkits*

* [app](https://github.com/murlokswarm/app) - Package to create apps with GO, HTML and CSS. Supports: MacOS, Windows in progress. 【🌟Star 3239】

* [fyne](https://github.com/fyne-io/fyne) - Cross platform native GUIs designed for Go based on Material Design. Supports: Linux, macOS, Windows, BSD, iOS and Android. 【🌟Star 7555】

* [go-astilectron](https://github.com/asticode/go-astilectron) - Build cross platform GUI apps with GO and HTML/JS/CSS (powered by Electron). 【🌟Star 2965】

* [go-gtk](http://mattn.github.io/go-gtk/) - Go bindings for GTK.
* [go-sciter](https://github.com/sciter-sdk/go-sciter) - Go bindings for Sciter: the Embeddable HTML/CSS/script engine for modern desktop UI development. Cross platform. 【🌟Star 1613】

* [gotk3](https://github.com/gotk3/gotk3) - Go bindings for GTK3. 【🌟Star 888】

* [gowd](https://github.com/dtylman/gowd) - Rapid and simple desktop UI development with GO, HTML, CSS and NW.js. Cross platform. 【🌟Star 235】

* [qt](https://github.com/therecipe/qt) - Qt binding for Go (support for Windows / macOS / Linux / Android / iOS / Sailfish OS / Raspberry Pi). 【🌟Star 6871】

* [ui](https://github.com/andlabs/ui) - Platform-native GUI library for Go. Cross platform. 【🌟Star 7299】

* [Wails](https://wails.app) - Mac, Windows, Linux desktop apps with HTML UI using built-in OS HTML renderer.
* [walk](https://github.com/lxn/walk) - Windows application library kit for Go. 【🌟Star 4183】

* [webview](https://github.com/zserge/webview) - Cross-platform webview window with simple two-way JavaScript bindings (Windows / macOS / Linux). 【🌟Star 5251】


*Interaction*

* [go-appindicator](https://github.com/dawidd6/go-appindicator) - Go bindings for libappindicator3 C library. 【🌟Star 4】

* [gosx-notifier](https://github.com/deckarep/gosx-notifier) - OSX Desktop Notifications library for Go. 【🌟Star 503】

* [mac-activity-tracker](https://github.com/prashantgupta24/activity-tracker) - OSX library to notify about any (pluggable) activity on your machine. 【🌟Star 2】

* [mac-sleep-notifier](https://github.com/prashantgupta24/mac-sleep-notifier) - OSX Sleep/Wake notifications in golang. 【🌟Star 1】

* [robotgo](https://github.com/go-vgo/robotgo) - Go Native cross-platform GUI system automation. Control the mouse, keyboard and other. 【🌟Star 4792】

* [systray](https://github.com/getlantern/systray) - Cross platform Go library to place an icon and menu in the notification area. 【🌟Star 946】

* [trayhost](https://github.com/shurcooL/trayhost) - Cross-platform Go library to place an icon in the host operating system's taskbar. 【🌟Star 168】



## Hardware

*Libraries, tools, and tutorials for interacting with hardware.*

See [go-hardware](https://github.com/rakyll/go-hardware) for a comprehensive list. 【🌟Star 976】


## Images

*Libraries for manipulating images.*

* [bild](https://github.com/anthonynsimon/bild) - Collection of image processing algorithms in pure Go. 【🌟Star 2743】

* [bimg](https://github.com/h2non/bimg) - Small package for fast and efficient image processing using libvips. 【🌟Star 868】

* [cameron](https://github.com/aofei/cameron) - An avatar generator for Go. 【🌟Star 36】

* [canvas](https://github.com/tdewolff/canvas) - Vector graphics to PDF, SVG or rasterized image. 【🌟Star 392】

* [darkroom](https://github.com/gojek/darkroom) - An image proxy with changeable storage backends and image processing engines with focus on speed and resiliency. 【🌟Star 109】

* [geopattern](https://github.com/pravj/geopattern) - Create beautiful generative image patterns from a string. 【🌟Star 1041】

* [gg](https://github.com/fogleman/gg) - 2D rendering in pure Go. 【🌟Star 2092】

* [gift](https://github.com/disintegration/gift) - Package of image processing filters. 【🌟Star 1286】

* [gltf](https://github.com/qmuntal/gltf) - Efficient and robust glTF 2.0 reader, writer and validator. 【🌟Star 57】

* [go-cairo](https://github.com/ungerik/go-cairo) - Go binding for the cairo graphics library. 【🌟Star 90】

* [go-gd](https://github.com/bolknote/go-gd) - Go binding for GD library. 【🌟Star 53】

* [go-nude](https://github.com/koyachi/go-nude) - Nudity detection with Go. 【🌟Star 296】

* [go-opencv](https://github.com/lazywei/go-opencv) - Go bindings for OpenCV. 【🌟Star 1139】

* [go-webcolors](https://github.com/jyotiska/go-webcolors) - Port of webcolors library from Python to Go. 【🌟Star 24】

* [gocv](https://github.com/hybridgroup/gocv) - Go package for computer vision using OpenCV 3.3+. 【🌟Star 2875】

* [goimagehash](https://github.com/corona10/goimagehash) - Go Perceptual image hashing package. 【🌟Star 260】

* [goimghdr](https://github.com/corona10/goimghdr) - The imghdr module determines the type of image contained in a file for Go. 【🌟Star 31】

* [govatar](https://github.com/o1egl/govatar) - Library and CMD tool for generating funny avatars. 【🌟Star 333】

* [image2ascii](https://github.com/qeesung/image2ascii) - Convert image to ASCII. 【🌟Star 351】

* [imagick](https://github.com/gographics/imagick) - Go binding to ImageMagick's MagickWand C API. 【🌟Star 1087】

* [imaginary](https://github.com/h2non/imaginary) - Fast and simple HTTP microservice for image resizing. 【🌟Star 2799】

* [imaging](https://github.com/disintegration/imaging) - Simple Go image processing package. 【🌟Star 2864】

* [img](https://github.com/hawx/img) - Selection of image manipulation tools. 【🌟Star 132】

* [ln](https://github.com/fogleman/ln) - 3D line art rendering in Go. 【🌟Star 2585】

* [mergi](https://github.com/noelyahan/mergi) - Tool & Go library for image manipulation (Merge, Crop, Resize, Watermark, Animate). 【🌟Star 86】

* [mort](https://github.com/aldor007/mort) - Storage and image processing server written in Go. 【🌟Star 381】

* [mpo](https://github.com/donatj/mpo) - Decoder and conversion tool for MPO 3D Photos. 【🌟Star 6】

* [picfit](https://github.com/thoas/picfit) - An image resizing server written in Go. 【🌟Star 1169】

* [pt](https://github.com/fogleman/pt) - Path tracing engine written in Go. 【🌟Star 1825】

* [resize](https://github.com/nfnt/resize) - Image resizing for Go with common interpolation methods. 【🌟Star 2249】

* [rez](https://github.com/bamiaux/rez) - Image resizing in pure Go and SIMD. 【🌟Star 194】

* [smartcrop](https://github.com/muesli/smartcrop) - Finds good crops for arbitrary images and crop sizes. 【🌟Star 1307】

* [steganography](https://github.com/auyer/steganography) - Pure Go Library for LSB steganography. 【🌟Star 36】

* [stegify](https://github.com/DimitarPetrov/stegify) - Go tool for LSB steganography, capable of hiding any file within an image. 【🌟Star 590】

* [svgo](https://github.com/ajstarks/svgo) - Go Language Library for SVG generation. 【🌟Star 1411】

* [tga](https://github.com/ftrvxmtrx/tga) - Package tga is a TARGA image format decoder/encoder. 【🌟Star 25】


## IoT (Internet of Things)

*Libraries for programming devices of the IoT.*

* [connectordb](https://github.com/connectordb/connectordb) - Open-Source Platform for Quantified Self & IoT. 【🌟Star 191】

* [devices](https://github.com/goiot/devices) - Suite of libraries for IoT devices, experimental for x/exp/io. 【🌟Star 229】

* [eywa](https://github.com/xcodersun/eywa) - Project Eywa is essentially a connection manager that keeps track of connected devices. 【🌟Star 43】

* [flogo](https://github.com/tibcosoftware/flogo) - Project Flogo is an Open Source Framework for IoT Edge Apps & Integration. 【🌟Star 1317】

* [gatt](https://github.com/paypal/gatt) - Gatt is a Go package for building Bluetooth Low Energy peripherals. 【🌟Star 866】

* [gobot](https://github.com/hybridgroup/gobot/) - Gobot is a framework for robotics, physical computing, and the Internet of Things. 【🌟Star 0】

* [huego](https://github.com/amimof/huego) - An extensive Philips Hue client library for Go. 【🌟Star 129】

* [iot](https://github.com/vaelen/iot/) - IoT is a simple framework for implementing a Google IoT Core device. 【🌟Star 0】

* [mainflux](https://github.com/Mainflux/mainflux) - Industrial IoT Messaging and Device Management Server. 【🌟Star 755】

* [periph](https://periph.io/) - Peripherals I/O to interface with low-level board facilities.
* [sensorbee](https://github.com/sensorbee/sensorbee) - Lightweight stream processing engine for IoT. 【🌟Star 187】


## Job Scheduler

*Libraries for scheduling jobs.*

* [clockwerk](http://github.com/onatm/clockwerk) - Go package to schedule periodic jobs using a simple, fluent syntax.
* [clockwork](https://github.com/whiteShtef/clockwork) - Simple and intuitive job scheduling library in Go. 【🌟Star 95】

* [go-cron](https://github.com/rk/go-cron) - Simple Cron library for go that can execute closures or functions at varying intervals, from once a second to once a year on a specific date and time. Primarily for web applications and long running daemons. 【🌟Star 178】

* [gron](https://github.com/roylee0704/gron) - Define time-based tasks using a simple Go API and Gron’s scheduler will run them accordingly. 【🌟Star 680】

* [JobRunner](https://github.com/bamzi/jobrunner) - Smart and featureful cron job scheduler with job queuing and live monitoring built in. 【🌟Star 640】

* [jobs](https://github.com/albrow/jobs) - Persistent and flexible background jobs library. 【🌟Star 461】

* [leprechaun](https://github.com/kilgaloon/leprechaun) - Job scheduler that supports webhooks, crons and classic scheduling. 【🌟Star 50】

* [scheduler](https://github.com/carlescere/scheduler) - Cronjobs scheduling made easy. 【🌟Star 313】


## JSON

*Libraries for working with JSON.*

* [ajson](https://github.com/spyzhov/ajson) - Abstract JSON for golang with JSONPath support. 【🌟Star 19】

* [ej](https://github.com/lucassscaravelli/ej) - Write and read JSON from different sources succinctly. 【🌟Star 3】

* [gjo](https://github.com/skanehira/gjo) - Small utility to create JSON objects. 【🌟Star 71】

* [GJSON](https://github.com/tidwall/gjson) - Get a JSON value with one line of code. 【🌟Star 5707】

* [go-jsonerror](https://github.com/ddymko/go-jsonerror) - Go-JsonError is ment to allow us to easily create json response errors that follow the JsonApi spec. 【🌟Star 9】

* [go-respond](https://github.com/nicklaw5/go-respond) - Go package for handling common HTTP JSON responses. 【🌟Star 29】

* [gojq](https://github.com/elgs/gojq) - JSON query in Golang. 【🌟Star 142】

* [gojson](https://github.com/ChimeraCoder/gojson) - Automatically generate Go (golang) struct definitions from example JSON. 【🌟Star 2129】

* [JayDiff](https://github.com/yazgazan/jaydiff) - JSON diff utility written in Go. 【🌟Star 60】

* [jettison](https://github.com/wI2L/jettison) - High performance, reflection-less JSON encoder for Go. 【🌟Star 60】

* [JSON-to-Go](https://mholt.github.io/json-to-go/) - Convert JSON to Go struct.
* [json2go](https://github.com/m-zajac/json2go) - Advanced JSON to Go struct conversion. Provides package that can parse multiple JSON documents and create struct to fit them all. 【🌟Star 27】

* [jsonapi-errors](https://github.com/AmuzaTkts/jsonapi-errors) - Go bindings based on the JSON API errors reference. 【🌟Star 6】

* [jsonf](https://github.com/miolini/jsonf) - Console tool for highlighted formatting and struct query fetching JSON. 【🌟Star 54】

* [jsongo](https://github.com/ricardolonga/jsongo) - Fluent API to make it easier to create Json objects. 【🌟Star 94】

* [jsonhal](https://github.com/RichardKnop/jsonhal) - Simple Go package to make custom structs marshal into HAL compatible JSON responses. 【🌟Star 9】

* [kazaam](https://github.com/Qntfy/kazaam) - API for arbitrary transformation of JSON documents. 【🌟Star 143】

* [mp](https://github.com/sanbornm/mp) - Simple cli email parser. It currently takes stdin and outputs JSON. 【🌟Star 37】


## Logging

*Libraries for generating and working with log files.*

* [distillog](https://github.com/amoghe/distillog) - distilled levelled logging (think of it as stdlib + log levels). 【🌟Star 21】

* [glg](https://github.com/kpango/glg) - glg is simple and fast leveled logging library for Go. 【🌟Star 60】

* [glo](https://github.com/lajosbencz/glo) - PHP Monolog inspired logging facility with identical severity levels. 【🌟Star 8】

* [glog](https://github.com/golang/glog) - Leveled execution logs for Go. 【🌟Star 2450】

* [go-cronowriter](https://github.com/utahta/go-cronowriter) - Simple writer that rotate log files automatically based on current date and time, like cronolog. 【🌟Star 24】

* [go-log](https://github.com/pieterclaerhout/go-log) - A logging library with strack traces, object dumping and optional timestamps. 【🌟Star 1】

* [go-log](https://github.com/subchen/go-log) - Simple and configurable Logging in Go, with level, formatters and writers. 【🌟Star 9】

* [go-log](https://github.com/siddontang/go-log) - Log lib supports level and multi handlers. 【🌟Star 26】

* [go-log](https://github.com/ian-kent/go-log) - Log4j implementation in Go. 【🌟Star 34】

* [go-logger](https://github.com/apsdehal/go-logger) - Simple logger of Go Programs, with level handlers. 【🌟Star 247】

* [gologger](https://github.com/sadlil/gologger) - Simple easy to use log lib for go, logs in Colored Console, Simple Console, File or Elasticsearch. 【🌟Star 38】

* [gomol](https://github.com/aphistic/gomol) - Multiple-output, structured logging for Go with extensible logging outputs. 【🌟Star 15】

* [gone/log](https://github.com/One-com/gone/tree/master/log) - Fast, extendable, full-featured, std-lib source compatible log library.
* [journald](https://github.com/ssgreg/journald) - Go implementation of systemd Journal's native API for logging. 【🌟Star 22】

* [log](https://github.com/aerogo/log) - An O(1) logging system that allows you to connect one log to multiple writers (e.g. stdout, a file and a TCP connection). 【🌟Star 6】

* [log](https://github.com/apex/log) - Structured logging package for Go. 【🌟Star 775】

* [log](https://github.com/go-playground/log) - Simple, configurable and scalable Structured Logging for Go. 【🌟Star 270】

* [log](https://github.com/teris-io/log) - Structured log interface for Go cleanly separates logging facade from its implementation. 【🌟Star 23】

* [log-voyage](https://github.com/firstrow/logvoyage) - Full-featured logging saas written in golang. 【🌟Star 84】

* [log15](https://github.com/inconshreveable/log15) - Simple, powerful logging for Go. 【🌟Star 945】

* [logdump](https://github.com/ewwwwwqm/logdump) - Package for multi-level logging. 【🌟Star 9】

* [logex](https://github.com/chzyer/logex) - Golang log lib, supports tracking and level, wrap by standard log lib. 【🌟Star 34】

* [logger](https://github.com/azer/logger) - Minimalistic logging library for Go. 【🌟Star 137】

* [logmatic](https://github.com/borderstech/logmatic) - Colorized logger for Golang with dynamic log level configuration. 【🌟Star 6】

* [logo](https://github.com/mbndr/logo) - Golang logger to different configurable writers. 【🌟Star 5】

* [logrus](https://github.com/Sirupsen/logrus) - Structured logger for Go. 【🌟Star 13627】

* [logrusiowriter](https://github.com/cabify/logrusiowriter) - `io.Writer` implementation using [logrus](https://github.com/sirupsen/logrus) logger. 【🌟Star 7】

* [logrusly](https://github.com/sebest/logrusly) - [logrus](https://github.com/sirupsen/logrus) plug-in to send errors to a [Loggly](https://www.loggly.com/). 【🌟Star 25】

* [logutils](https://github.com/hashicorp/logutils) - Utilities for slightly better logging in Go (Golang) extending the standard logger. 【🌟Star 265】

* [logxi](https://github.com/mgutz/logxi) - 12-factor app logger that is fast and makes you happy. 【🌟Star 340】

* [lumberjack](https://github.com/natefinch/lumberjack) - Simple rolling logger, implements io.WriteCloser. 【🌟Star 1731】

* [mlog](https://github.com/jbrodriguez/mlog) - Simple logging module for go, with 5 levels, an optional rotating logfile feature and stdout/stderr output. 【🌟Star 19】

* [onelog](https://github.com/francoispqt/onelog) - Onelog is a dead simple but very efficient JSON logger. It is the fastest JSON logger out there in all scenario. Also, it is one of the logger with the lowest allocation. 【🌟Star 358】

* [ozzo-log](https://github.com/go-ozzo/ozzo-log) - High performance logging supporting log severity, categorization, and filtering. Can send filtered log messages to various targets (e.g. console, network, mail). 【🌟Star 110】

* [rollingwriter](https://github.com/arthurkiller/rollingWriter) - RollingWriter is an auto-rotate `io.Writer` implementation with multi policies to provide log file rotation. 【🌟Star 128】

* [seelog](https://github.com/cihub/seelog) - Logging functionality with flexible dispatching, filtering, and formatting. 【🌟Star 1420】

* [spew](https://github.com/davecgh/go-spew) - Implements a deep pretty printer for Go data structures to aid in debugging. 【🌟Star 3653】

* [stdlog](https://github.com/alexcesaro/log) - Stdlog is an object-oriented library providing leveled logging. It is very useful for cron jobs. 【🌟Star 42】

* [tail](https://github.com/hpcloud/tail) - Go package striving to emulate the features of the BSD tail program. 【🌟Star 1684】

* [xlog](https://github.com/xfxdev/xlog) - Plugin architecture and flexible log system for Go, with level ctrl, multiple log target and custom log format. 【🌟Star 6】

* [xlog](https://github.com/rs/xlog) - Structured logger for `net/context` aware HTTP handlers with flexible dispatching. 【🌟Star 131】

* [zap](https://github.com/uber-go/zap) - Fast, structured, leveled logging in Go. 【🌟Star 8805】

* [zerolog](https://github.com/rs/zerolog) - Zero-allocation JSON logger. 【🌟Star 2837】


## Machine Learning

*Libraries for Machine Learning.*

* [bayesian](https://github.com/jbrukh/bayesian) - Naive Bayesian Classification for Golang. 【🌟Star 648】

* [CloudForest](https://github.com/ryanbressler/CloudForest) - Fast, flexible, multi-threaded ensembles of decision trees for machine learning in pure Go. 【🌟Star 661】

* [eaopt](https://github.com/MaxHalford/eaopt) - An evolutionary optimization library. 【🌟Star 655】

* [evoli](https://github.com/khezen/evoli) - Genetic Algorithm and Particle Swarm Optimization library. 【🌟Star 10】

* [fonet](https://github.com/Fontinalis/fonet) - A Deep Neural Network library written in Go. 【🌟Star 35】

* [go-cluster](https://github.com/e-XpertSolutions/go-cluster) - Go implementation of the k-modes and k-prototypes clustering algorithms. 【🌟Star 21】

* [go-deep](https://github.com/patrikeh/go-deep) - A feature-rich neural network library in Go. 【🌟Star 248】

* [go-fann](https://github.com/white-pony/go-fann) - Go bindings for Fast Artificial Neural Networks(FANN) library. 【🌟Star 103】

* [go-galib](https://github.com/thoj/go-galib) - Genetic Algorithms library written in Go / golang. 【🌟Star 176】

* [go-pr](https://github.com/daviddengcn/go-pr) - Pattern recognition package in Go lang. 【🌟Star 57】

* [gobrain](https://github.com/goml/gobrain) - Neural Networks written in go. 【🌟Star 419】

* [godist](https://github.com/e-dard/godist) - Various probability distributions, and associated methods. 【🌟Star 25】

* [goga](https://github.com/tomcraven/goga) - Genetic algorithm library for Go. 【🌟Star 81】

* [GoLearn](https://github.com/sjwhitworth/golearn) - General Machine Learning library for Go. 【🌟Star 6921】

* [golinear](https://github.com/danieldk/golinear) - liblinear bindings for Go. 【🌟Star 39】

* [GoMind](https://github.com/surenderthakran/gomind) - A simplistic Neural Network Library in Go. 【🌟Star 7】

* [goml](https://github.com/cdipaolo/goml) - On-line Machine Learning in Go. 【🌟Star 1054】

* [Goptuna](https://github.com/c-bata/goptuna) - Bayesian optimization framework for black-box functions written in Go. Everything will be optimized. 【🌟Star 104】

* [goRecommend](https://github.com/timkaye11/goRecommend) - Recommendation Algorithms library written in Go. 【🌟Star 152】

* [gorgonia](https://github.com/gorgonia/gorgonia) - graph-based computational library like Theano for Go that provides primitives for building various machine learning and neural network algorithms. 【🌟Star 3070】

* [gorse](https://github.com/zhenghaoz/gorse) - An offline recommender system backend based on collaborative filtering written in Go. 【🌟Star 883】

* [goscore](https://github.com/asafschers/goscore) - Go Scoring API for PMML. 【🌟Star 43】

* [gosseract](https://github.com/otiai10/gosseract) - Go package for OCR (Optical Character Recognition), by using Tesseract C++ library. 【🌟Star 1024】

* [libsvm](https://github.com/datastream/libsvm) - libsvm golang version derived work based on LIBSVM 3.14. 【🌟Star 64】

* [neat](https://github.com/jinyeom/neat) - Plug-and-play, parallel Go framework for NeuroEvolution of Augmenting Topologies (NEAT). 【🌟Star 56】

* [neural-go](https://github.com/schuyler/neural-go) - Multilayer perceptron network implemented in Go, with training via backpropagation. 【🌟Star 61】

* [ocrserver](https://github.com/otiai10/ocrserver) - A simple OCR API server, seriously easy to be deployed by Docker and Heroku. 【🌟Star 261】

* [onnx-go](https://github.com/owulveryck/onnx-go) - Go Interface to Open Neural Network Exchange (ONNX). 【🌟Star 233】

* [probab](https://github.com/ThePaw/probab) - Probability distribution functions. Bayesian inference. Written in pure Go. 【🌟Star 11】

* [randomforest](https://github.com/malaschitz/randomForest) - Easy to use Random Forest library for Go. 【🌟Star 2】

* [regommend](https://github.com/muesli/regommend) - Recommendation & collaborative filtering engine. 【🌟Star 263】

* [shield](https://github.com/eaigner/shield) - Bayesian text classifier with flexible tokenizers and storage backends for Go. 【🌟Star 129】

* [tfgo](https://github.com/galeone/tfgo) - Easy to use Tensorflow bindings: simplifies the usage of the official Tensorflow Go bindings. Define computational graphs in Go, load and execute models trained in Python. 【🌟Star 1283】

* [Varis](https://github.com/Xamber/Varis) - Golang Neural Network. 【🌟Star 26】


## Messaging

*Libraries that implement messaging systems.*

* [APNs2](https://github.com/sideshow/apns2) - HTTP/2 Apple Push Notification provider for Go — Send push notifications to iOS, tvOS, Safari and OSX apps. 【🌟Star 2231】

* [Beaver](https://github.com/Clivern/Beaver) - A real time messaging server to build a scalable in-app notifications, multiplayer games, chat apps in web and mobile apps. 【🌟Star 777】

* [Benthos](https://github.com/Jeffail/benthos) - A message streaming bridge between a range of protocols. 【🌟Star 2188】

* [Bus](https://github.com/mustafaturan/bus) - Minimalist message bus implementation for internal communication. 【🌟Star 131】

* [Centrifugo](https://github.com/centrifugal/centrifugo) - Real-time messaging (Websockets or SockJS) server in Go. 【🌟Star 4008】

* [Commander](https://github.com/jeroenrinzema/commander) - A high-level event driven consumer/producer supporting various "dialects" such as Apache Kafka. 【🌟Star 38】

* [dbus](https://github.com/godbus/dbus) - Native Go bindings for D-Bus. 【🌟Star 406】

* [drone-line](https://github.com/appleboy/drone-line) - Sending [Line](https://at.line.me/en) notifications using a binary, docker or Drone CI. 【🌟Star 65】

* [emitter](https://github.com/olebedev/emitter) - Emits events using Go way, with wildcard, predicates, cancellation possibilities and many other good wins. 【🌟Star 331】

* [event](https://github.com/agoalofalife/event) - Implementation of the pattern observer. 【🌟Star 32】

* [EventBus](https://github.com/asaskevich/EventBus) - The lightweight event bus with async compatibility. 【🌟Star 633】

* [gaurun-client](https://github.com/osamingo/gaurun-client) - Gaurun Client written in Go. 【🌟Star 8】

* [Glue](https://github.com/desertbit/glue) - Robust Go and Javascript Socket Library (Alternative to Socket.io). 【🌟Star 325】

* [go-notify](https://github.com/TheCreeper/go-notify) - Native implementation of the freedesktop notification spec. 【🌟Star 47】

* [go-nsq](https://github.com/nsqio/go-nsq) - the official Go package for NSQ. 【🌟Star 1568】

* [go-socket.io](https://github.com/googollee/go-socket.io) - socket.io library for golang, a realtime application framework. 【🌟Star 3205】

* [go-vitotrol](https://github.com/maxatome/go-vitotrol) - Client library to Viessmann Vitotrol web service. 【🌟Star 12】

* [Gollum](https://github.com/trivago/gollum) - A n:m multiplexer that gathers messages from different sources and broadcasts them to a set of destinations. 【🌟Star 824】

* [golongpoll](https://github.com/jcuga/golongpoll) - HTTP longpoll server library that makes web pub-sub simple. 【🌟Star 439】

* [gopush-cluster](https://github.com/Terry-Mao/gopush-cluster) - gopush-cluster is a go push server cluster. 【🌟Star 1883】

* [gorush](https://github.com/appleboy/gorush) - Push notification server using [APNs2](https://github.com/sideshow/apns2) and google [GCM](https://github.com/google/go-gcm). 【🌟Star 4083】

* [guble](https://github.com/smancke/guble) - Messaging server using push notifications (Google Firebase Cloud Messaging, Apple Push Notification services, SMS) as well as websockets, a REST API, featuring distributed operation and message-persistence. 【🌟Star 142】

* [hub](https://github.com/leandro-lugaresi/hub) - A Message/Event Hub for Go applications, using publish/subscribe pattern with support for alias like rabbitMQ exchanges. 【🌟Star 34】

* [jazz](https://github.com/socifi/jazz) - A simple RabbitMQ abstraction layer for queue administration and publishing and consuming of messages. 【🌟Star 8】

* [machinery](https://github.com/RichardKnop/machinery) - Asynchronous task queue/job queue based on distributed message passing. 【🌟Star 3772】

* [mangos](https://github.com/go-mangos/mangos) - Pure go implementation of the Nanomsg ("Scalable Protocols") with transport interoperability. 【🌟Star 1544】

* [melody](https://github.com/olahol/melody) - Minimalist framework for dealing with websocket sessions, includes broadcasting and automatic ping/pong handling. 【🌟Star 1709】

* [Mercure](https://github.com/dunglas/mercure) - Server and library to dispatch server-sent updates using the Mercure protocol (built on top of Server-Sent Events). 【🌟Star 1812】

* [messagebus](https://github.com/vardius/message-bus) - messagebus is a Go simple async message bus, perfect for using as event bus when doing event sourcing, CQRS, DDD. 【🌟Star 79】

* [NATS Go Client](https://github.com/nats-io/nats) - Lightweight and high performance publish-subscribe and distributed queueing messaging system - this is the Go library. 【🌟Star 2626】

* [nsq-event-bus](https://github.com/rafaeljesus/nsq-event-bus) - A tiny wrapper around NSQ topic and channel. 【🌟Star 57】

* [oplog](https://github.com/dailymotion/oplog) - Generic oplog/replication system for REST APIs. 【🌟Star 100】

* [pubsub](https://github.com/tuxychandru/pubsub) - Simple pubsub package for go. 【🌟Star 306】

* [rabbus](https://github.com/rafaeljesus/rabbus) - A tiny wrapper over amqp exchanges and queues. 【🌟Star 68】

* [rabtap](https://github.com/jandelgado/rabtap) - RabbitMQ swiss army knife cli app. 【🌟Star 97】

* [RapidMQ](https://github.com/sybrexsys/RapidMQ) - RapidMQ is a lightweight and reliable library for managing of the local messages queue. 【🌟Star 57】

* [redisqueue](https://github.com/robinjoseph08/redisqueue) - redisqueue provides a producer and consumer of a queue that uses Redis streams. 【🌟Star 8】

* [rmqconn](https://github.com/sbabiv/rmqconn) - RabbitMQ Reconnection. Wrapper over amqp.Connection and amqp.Dial. Allowing to do a reconnection when the connection is broken before forcing the call to the Close () method to be closed. 【🌟Star 2】

* [sarama](https://github.com/Shopify/sarama) - Go library for Apache Kafka. 【🌟Star 5299】

* [Uniqush-Push](https://github.com/uniqush/uniqush-push) - Redis backed unified push service for server-side notifications to mobile devices. 【🌟Star 1129】

* [zmq4](https://github.com/pebbe/zmq4) - Go interface to ZeroMQ version 4. Also available for [version 3](https://github.com/pebbe/zmq3) and [version 2](https://github.com/pebbe/zmq2). 【🌟Star 821】


## Microsoft Office

* [unioffice](https://github.com/unidoc/unioffice) - Pure go library for creating and processing Office Word (.docx), Excel (.xlsx) and Powerpoint (.pptx) documents. 【🌟Star 2031】


### Microsoft Excel

*Libraries for working with Microsoft Excel.*

* [excelize](https://github.com/360EntSecGroup-Skylar/excelize) - Golang library for reading and writing Microsoft Excel™ (XLSX) files. 【🌟Star 5292】

* [go-excel](https://github.com/szyhf/go-excel) - A simple and light reader to read a relate-db-like excel as a table. 【🌟Star 59】

* [goxlsxwriter](https://github.com/fterrag/goxlsxwriter) - Golang bindings for libxlsxwriter for writing XLSX (Microsoft Excel) files. 【🌟Star 14】

* [xlsx](https://github.com/tealeg/xlsx) - Library to simplify reading the XML format used by recent version of Microsoft Excel in Go programs. 【🌟Star 3837】

* [xlsx](https://github.com/plandem/xlsx) - Fast and safe way to read/update your existing Microsoft Excel files in Go programs. 【🌟Star 102】


## Miscellaneous

### Dependency Injection

*Libraries for working with dependency injection.*

* [alice](https://github.com/magic003/alice) - Additive dependency injection container for Golang. 【🌟Star 36】

* [container](https://github.com/golobby/container) - A powerful IoC Container with fluent and easy-to-use interface. 【🌟Star 63】

* [dig](https://github.com/uber-go/dig) - A reflection based dependency injection toolkit for Go. 【🌟Star 1198】

* [dingo](https://github.com/i-love-flamingo/dingo) - A dependency injection toolkit for Go, based on Guice. 【🌟Star 36】

* [fx](https://github.com/uber-go/fx) - A dependency injection based application framework for Go (built on top of dig). 【🌟Star 1115】

* [gocontainer](https://github.com/vardius/gocontainer) - Simple Dependency Injection Container. 【🌟Star 11】

* [inject](https://github.com/defval/inject) - A reflection based dependency injection container with simple interface. 【🌟Star 49】

* [linker](https://github.com/logrange/linker) - A reflection based dependency injection and inversion of control library with components lifecycle support. 【🌟Star 18】

* [wire](https://github.com/Fs02/wire) - Strict Runtime Dependency Injection for Golang. 【🌟Star 23】


### Project Layout

*Unofficial set of patterns for structuring projects.*

* [cookiecutter-golang](https://github.com/lacion/cookiecutter-golang) - A Go application boilerplate template for quick starting projects following production best practices. 【🌟Star 309】

* [go-restful-api](https://github.com/qiangxue/go-restful-api) - An idiomatic Go RESTful API starter kit following SOLID principles and Clean Architecture with a common project layout. 【🌟Star 1001】

* [go-sample](https://github.com/zitryss/go-sample) - A sample layout for Go application projects with the real code. 【🌟Star 41】

* [golang-standards/project-layout](https://github.com/golang-standards/project-layout) - Set of common historical and emerging project layout patterns in the Go ecosystem. 【🌟Star 12546】

* [modern-go-application](https://github.com/sagikazarmark/modern-go-application) - Go application boilerplate and example applying modern practices. 【🌟Star 473】

* [scaffold](https://github.com/catchplay/scaffold) - Scaffold generates starter Go project layout. Lets you focus on business logic implemeted. 【🌟Star 50】


### Strings

*Libraries for working with strings.*

* [strutil](https://github.com/ozgio/strutil) - String utilities. 【🌟Star 82】

* [xstrings](https://github.com/huandu/xstrings) - Collection of useful string functions ported from other languages. 【🌟Star 698】


*These libraries were placed here because none of the other categories seemed to fit.*

* [anagent](https://github.com/mudler/anagent) - Minimalistic, pluggable Golang evloop/timer handler with dependency-injection. 【🌟Star 11】

* [antch](https://github.com/antchfx/antch) - A fast, powerful and extensible web crawling & scraping framework. 【🌟Star 165】

* [archiver](https://github.com/mholt/archiver) - Library and command for making and extracting .zip and .tar.gz archives. 【🌟Star 2684】

* [autoflags](https://github.com/artyom/autoflags) - Go package to automatically define command line flags from struct fields. 【🌟Star 25】

* [avgRating](https://github.com/kirillDanshin/avgRating) - Calculate average score and rating based on Wilson Score Equation. 【🌟Star 10】

* [banner](https://github.com/dimiro1/banner) - Add beautiful banners into your Go applications. 【🌟Star 246】

* [base64Captcha](https://github.com/mojocn/base64Captcha) - Base64captch supports digit, number, alphabet, arithmetic, audio and digit-alphabet captcha. 【🌟Star 741】

* [battery](https://github.com/distatus/battery) - Cross-platform, normalized battery information library. 【🌟Star 138】

* [bitio](https://github.com/icza/bitio) - Highly optimized bit-level Reader and Writer for Go. 【🌟Star 110】

* [browscap_go](https://github.com/digitalcrab/browscap_go) - GoLang Library for [Browser Capabilities Project](http://browscap.org/). 【🌟Star 31】

* [captcha](https://github.com/steambap/captcha) - Package captcha provides an easy to use, unopinionated API for captcha generation. 【🌟Star 48】

* [conv](https://github.com/cstockton/go-conv) - Package conv provides fast and intuitive conversions across Go types. 【🌟Star 347】

* [datacounter](https://github.com/miolini/datacounter) - Go counters for readers/writer/http.ResponseWriter. 【🌟Star 30】

* [ffmt](https://github.com/go-ffmt/ffmt) - Beautify data display for Humans. 【🌟Star 147】

* [ghorg](https://github.com/gabrie30/ghorg) - Quickly clone an entire org/users repositories into one directory - Supports GitHub, GitLab, and Bitbucket. 【🌟Star 95】

* [go-commons-pool](https://github.com/jolestar/go-commons-pool) - Generic object pool for Golang. 【🌟Star 754】

* [go-openapi](https://github.com/go-openapi) - Collection of packages to parse and utilize open-api schemas.
* [go-resiliency](https://github.com/eapache/go-resiliency) - Resiliency patterns for golang. 【🌟Star 947】

* [go-unarr](https://github.com/gen2brain/go-unarr) - Decompression library for RAR, TAR, ZIP and 7z archives. 【🌟Star 81】

* [gofakeit](https://github.com/brianvoe/gofakeit) - Random data generator written in go. 【🌟Star 796】

* [gommit](https://github.com/antham/gommit) - Analyze git commit messages to ensure they follow defined patterns. 【🌟Star 83】

* [gopsutil](https://github.com/shirou/gopsutil) - Cross-platform library for retrieving process and system utilization(CPU, Memory, Disks, etc). 【🌟Star 4451】

* [gosh](https://github.com/osamingo/gosh) - Provide Go Statistics Handler, Struct, Measure Method. 【🌟Star 19】

* [gosms](https://github.com/haxpax/gosms) - Your own local SMS gateway in Go that can be used to send SMS. 【🌟Star 1262】

* [gotoprom](https://github.com/cabify/gotoprom) - Type-safe metrics builder wrapper library for the official Prometheus client. 【🌟Star 30】

* [gountries](https://github.com/pariz/gountries) - Package that exposes country and subdivision data. 【🌟Star 228】

* [health](https://github.com/dimiro1/health) - Easy to use, extensible health check library. 【🌟Star 376】

* [healthcheck](https://github.com/etherlabsio/healthcheck) - An opinionated and concurrent health-check HTTP handler for RESTful services. 【🌟Star 95】

* [hostutils](https://github.com/Wing924/hostutils) - A golang library for packing and unpacking FQDNs list. 【🌟Star 8】

* [indigo](https://github.com/osamingo/indigo) - Distributed unique ID generator of using Sonyflake and encoded by Base58. 【🌟Star 58】

* [lk](https://github.com/hyperboloide/lk) - A simple licensing library for golang. 【🌟Star 142】

* [llvm](https://github.com/llir/llvm) - Library for interacting with LLVM IR in pure Go. 【🌟Star 474】

* [metrics](https://github.com/pascaldekloe/metrics) - Library for metrics instrumentation and Prometheus exposition. 【🌟Star 6】

* [morse](https://github.com/alwindoss/morse) - Library to convert to and from morse code. 【🌟Star 55】

* [numa](https://github.com/lrita/numa) - NUMA is a utility library, which is written in go. It help us to write some NUMA-AWARED code. 【🌟Star 2】

* [pdfgen](https://github.com/hyperboloide/pdfgen) - HTTP service to generate PDF from Json requests. 【🌟Star 36】

* [persian](https://github.com/mavihq/persian) - Some utilities for Persian language in go. 【🌟Star 37】

* [sandid](https://github.com/aofei/sandid) - Every grain of sand on earth has its own ID. 【🌟Star 14】

* [shellwords](https://github.com/Wing924/shellwords) - A Golang library to manipulate strings according to the word parsing rules of the UNIX Bourne shell. 【🌟Star 7】

* [shortid](https://github.com/teris-io/shortid) - Distributed generation of super short, unique, non-sequential, URL friendly IDs. 【🌟Star 507】

* [stateless](https://github.com/qmuntal/stateless) - A fluent library for creating state machines. 【🌟Star 140】

* [stats](https://github.com/go-playground/stats) - Monitors Go MemStats + System stats such as Memory, Swap and CPU and sends via UDP anywhere you want for logging etc... 【🌟Star 129】

* [turtle](https://github.com/hackebrot/turtle) - Emojis for Go. 【🌟Star 91】

* [url-shortener](https://github.com/pantrif/url-shortener) - A modern, powerful, and robust URL shortener microservice with mysql support. 【🌟Star 18】

* [VarHandler](https://github.com/azr/generators/tree/master/varhandler) - Generate boilerplate http input and output handling.
* [xdg](https://github.com/rkoesters/xdg) - FreeDesktop.org (xdg) Specs implemented in Go. 【🌟Star 21】

* [xkg](https://github.com/go-xkg/xkg) - X Keyboard Grabber. 【🌟Star 45】


## Natural Language Processing

*Libraries for working with human languages.*

* [detectlanguage](https://github.com/detectlanguage/detectlanguage-go) - Language Detection API Go Client. Supports batch requests, short phrase or single word language detection. 【🌟Star 1】

* [getlang](https://github.com/rylans/getlang) - Fast natural language detection package. 【🌟Star 78】

* [go-i18n](https://github.com/nicksnyder/go-i18n/) - Package and an accompanying tool to work with localized text. 【🌟Star 0】

* [go-localize](https://github.com/m1/go-localize) - Simple and easy to use i18n (Internationalization and localization) engine - used for translating locale strings. 【🌟Star 2】

* [go-mystem](https://github.com/dveselov/mystem) - CGo bindings to Yandex.Mystem - russian morphology analyzer. 【🌟Star 23】

* [go-nlp](https://github.com/nuance/go-nlp) - Utilities for working with discrete probability distributions and other tools useful for doing NLP work. 【🌟Star 82】

* [go-pinyin](https://github.com/mozillazg/go-pinyin) - CN Hanzi to Hanyu Pinyin converter. 【🌟Star 634】

* [go-stem](https://github.com/agonopol/go-stem) - Implementation of the porter stemming algorithm. 【🌟Star 54】

* [go-unidecode](https://github.com/mozillazg/go-unidecode) - ASCII transliterations of Unicode text. 【🌟Star 64】

* [go2vec](https://github.com/danieldk/go2vec) - Reader and utility functions for word2vec embeddings. 【🌟Star 33】

* [gojieba](https://github.com/yanyiwu/gojieba) - This is a Go implementation of [jieba](https://github.com/fxsjy/jieba) which a Chinese word splitting algorithm. 【🌟Star 951】

* [golibstemmer](https://github.com/rjohnsondev/golibstemmer) - Go bindings for the snowball libstemmer library including porter 2. 【🌟Star 16】

* [gotokenizer](https://github.com/xujiajun/gotokenizer) - A tokenizer based on the dictionary and Bigram language models for Golang. (Now only support chinese segmentation) 【🌟Star 6】

* [gounidecode](https://github.com/fiam/gounidecode) - Unicode transliterator (also known as unidecode) for Go. 【🌟Star 68】

* [gse](https://github.com/go-ego/gse) - Go efficient text segmentation; support english, chinese, japanese and other. 【🌟Star 1197】

* [icu](https://github.com/goodsign/icu) - Cgo binding for icu4c C library detection and conversion functions. Guaranteed compatibility with version 50.1. 【🌟Star 19】

* [kagome](https://github.com/ikawaha/kagome) - JP morphological analyzer written in pure Go. 【🌟Star 470】

* [libtextcat](https://github.com/goodsign/libtextcat) - Cgo binding for libtextcat C library. Guaranteed compatibility with version 2.2. 【🌟Star 10】

* [MMSEGO](https://github.com/awsong/MMSEGO) - This is a GO implementation of [MMSEG](http://technology.chtsai.org/mmseg/) which a Chinese word splitting algorithm. 【🌟Star 59】

* [nlp](https://github.com/Shixzie/nlp) - Extract values from strings and fill your structs with nlp. 【🌟Star 358】

* [nlp](https://github.com/james-bowman/nlp) - Go Natural Language Processing library supporting LSA (Latent Semantic Analysis). 【🌟Star 236】

* [paicehusk](https://github.com/rookii/paicehusk) - Golang implementation of the Paice/Husk Stemming Algorithm. 【🌟Star 26】

* [petrovich](https://github.com/striker2000/petrovich) - Petrovich is the library which inflects Russian names to given grammatical case. 【🌟Star 27】

* [porter](https://github.com/a2800276/porter) - This is a fairly straightforward port of Martin Porter's C implementation of the Porter stemming algorithm. 【🌟Star 8】

* [porter2](https://github.com/zhenjl/porter2) - Really fast Porter 2 stemmer. 【🌟Star 35】

* [prose](https://github.com/jdkato/prose) - Library for text processing that supports tokenization, part-of-speech tagging, named-entity extraction, and more. English only. 【🌟Star 2405】

* [RAKE.go](https://github.com/Obaied/RAKE.go) - Go port of the Rapid Automatic Keyword Extraction Algorithm (RAKE). 【🌟Star 52】

* [segment](https://github.com/blevesearch/segment) - Go library for performing Unicode Text Segmentation as described in [Unicode Standard Annex #29](http://www.unicode.org/reports/tr29/) 【🌟Star 46】

* [sentences](https://github.com/neurosnap/sentences) - Sentence tokenizer:  converts text into a list of sentences. 【🌟Star 264】

* [shamoji](https://github.com/osamingo/shamoji) - The shamoji is word filtering package written in Go. 【🌟Star 11】

* [snowball](https://github.com/goodsign/snowball) - Snowball stemmer port (cgo wrapper) for Go. Provides word stem extraction functionality [Snowball native](http://snowball.tartarus.org/). 【🌟Star 24】

* [stemmer](https://github.com/dchest/stemmer) - Stemmer packages for Go programming language. Includes English and German stemmers. 【🌟Star 48】

* [textcat](https://github.com/pebbe/textcat) - Go package for n-gram based text categorization, with support for utf-8 and raw text. 【🌟Star 62】

* [whatlanggo](https://github.com/abadojack/whatlanggo) - Natural language detection package for Go. Supports 84 languages and 24 scripts (writing systems e.g. Latin, Cyrillic, etc). 【🌟Star 388】

* [when](https://github.com/olebedev/when) - Natural EN and RU language date/time parser with pluggable rules. 【🌟Star 1050】


## Networking

*Libraries for working with various layers of the network.*

* [arp](https://github.com/mdlayher/arp) - Package arp implements the ARP protocol, as described in RFC 826. 【🌟Star 211】

* [buffstreams](https://github.com/stabbycutyou/buffstreams) - Streaming protocolbuffer data over TCP made easy. 【🌟Star 236】

* [canopus](https://github.com/zubairhamed/canopus) - CoAP Client/Server implementation (RFC 7252). 【🌟Star 137】

* [cidranger](https://github.com/yl2chen/cidranger) - Fast IP to CIDR lookup for Go. 【🌟Star 431】

* [dhcp6](https://github.com/mdlayher/dhcp6) - Package dhcp6 implements a DHCPv6 server, as described in RFC 3315. 【🌟Star 64】

* [dns](https://github.com/miekg/dns) - Go library for working with DNS. 【🌟Star 4259】

* [ether](https://github.com/songgao/ether) - Cross-platform Go package for sending and receiving ethernet frames. 【🌟Star 64】

* [ethernet](https://github.com/mdlayher/ethernet) - Package ethernet implements marshaling and unmarshaling of IEEE 802.3 Ethernet II frames and IEEE 802.1Q VLAN tags. 【🌟Star 193】

* [fasthttp](https://github.com/valyala/fasthttp) - Package fasthttp is a fast HTTP implementation for Go, up to 10 times faster than net/http. 【🌟Star 11214】

* [fortio](https://github.com/fortio/fortio) - Load testing library and command line tool, advanced echo server and web UI. Allows to specify a set query-per-second load and record latency histograms and other useful stats and graph them. Tcp, Http, gRPC. 【🌟Star 1111】

* [ftp](https://github.com/jlaffaye/ftp) - Package ftp implements a FTP client as described in [RFC 959](http://tools.ietf.org/html/rfc959). 【🌟Star 602】

* [gev](https://github.com/Allenxuxu/gev) - gev is a lightweight, fast non-blocking TCP network library based on Reactor mode. 【🌟Star 763】

* [gmqtt](https://github.com/DrmagicE/gmqtt) - Gmqtt is a flexible, high-performance MQTT broker library that fully implements the MQTT protocol V3.1.1. 【🌟Star 119】

* [gnet](https://github.com/panjf2000/gnet) - `gnet` is a high-performance, lightweight, non-blocking, event-driven networking framework written in pure Go. 【🌟Star 1631】

* [gNxI](https://github.com/google/gnxi) - A collection of tools for Network Management that use the gNMI and gNOI protocols. 【🌟Star 114】

* [go-getter](https://github.com/hashicorp/go-getter) - Go library for downloading files or directories from various sources using a URL. 【🌟Star 834】

* [go-powerdns](https://github.com/joeig/go-powerdns) - PowerDNS API bindings for Golang. 【🌟Star 10】

* [go-stun](https://github.com/ccding/go-stun) - Go implementation of the STUN client (RFC 3489 and RFC 5389). 【🌟Star 339】

* [gobgp](https://github.com/osrg/gobgp) - BGP implemented in the Go Programming Language. 【🌟Star 1797】

* [golibwireshark](https://github.com/sunwxg/golibwireshark) - Package golibwireshark use libwireshark library to decode pcap file and analyse dissection data. 【🌟Star 17】

* [gopacket](https://github.com/google/gopacket) - Go library for packet processing with libpcap bindings. 【🌟Star 3204】

* [gopcap](https://github.com/akrennmair/gopcap) - Go wrapper for libpcap. 【🌟Star 373】

* [goshark](https://github.com/sunwxg/goshark) - Package goshark use tshark to decode IP packet and create data struct to analyse packet. 【🌟Star 9】

* [gosnmp](https://github.com/soniah/gosnmp) - Native Go library for performing SNMP actions. 【🌟Star 483】

* [gosocsvr](https://github.com/rakeki/gosocsvr) - Socket server made simple. 【🌟Star 4】

* [gotcp](https://github.com/gansidui/gotcp) - Go package for quickly writing tcp applications. 【🌟Star 448】

* [grab](https://github.com/cavaliercoder/grab) - Go package for managing file downloads. 【🌟Star 624】

* [graval](https://github.com/koofr/graval) - Experimental FTP server framework. 【🌟Star 25】

* [HTTPLab](https://github.com/gchaincl/httplab) - HTTPLabs let you inspect HTTP requests and forge responses. 【🌟Star 3505】

* [httpproxy](https://github.com/wzshiming/httpproxy) - HTTP proxy handler and dialer. 【🌟Star 1】

* [iplib](https://github.com/c-robinson/iplib) - Library for working with IP addresses (net.IP, net.IPNet), inspired by python [ipaddress](https://docs.python.org/3/library/ipaddress.html) and ruby [ipaddr](https://ruby-doc.org/stdlib-2.5.1/libdoc/ipaddr/rdoc/IPAddr.html) 【🌟Star 27】

* [jazigo](https://github.com/udhos/jazigo) - Jazigo is a tool written in Go for retrieving configuration for multiple network devices. 【🌟Star 139】

* [kcp-go](https://github.com/xtaci/kcp-go) - KCP - Fast and Reliable ARQ Protocol. 【🌟Star 2426】

* [kcptun](https://github.com/xtaci/kcptun) - Extremely simple & fast udp tunnel based on KCP protocol. 【🌟Star 11370】

* [lhttp](https://github.com/fanux/lhttp) - Powerful websocket framework, build your IM server more easily. 【🌟Star 544】

* [linkio](https://github.com/ian-kent/linkio) - Network link speed simulation for Reader/Writer interfaces. 【🌟Star 47】

* [llb](https://github.com/kirillDanshin/llb) - It's a very simple but quick backend for proxy servers. Can be useful for fast redirection to predefined domain with zero memory allocation and fast response. 【🌟Star 10】

* [mdns](https://github.com/hashicorp/mdns) - Simple mDNS (Multicast DNS) client/server library in Golang. 【🌟Star 609】

* [mqttPaho](https://eclipse.org/paho/clients/golang/) - The Paho Go Client provides an MQTT client library for connection to MQTT brokers via TCP, TLS or WebSockets.
* [NFF-Go](https://github.com/intel-go/nff-go) - Framework for rapid development of performant network functions for cloud and bare-metal (former YANFF). 【🌟Star 755】

* [packet](https://github.com/aerogo/packet) - Send packets over TCP and UDP. It can buffer messages and hot-swap connections if needed. 【🌟Star 42】

* [peerdiscovery](https://github.com/schollz/peerdiscovery) - Pure Go library for cross-platform local peer discovery using UDP multicast. 【🌟Star 394】

* [portproxy](https://github.com/aybabtme/portproxy) - Simple TCP proxy which adds CORS support to API's which don't support it. 【🌟Star 42】

* [publicip](https://github.com/polera/publicip) - Package publicip returns your public facing IPv4 address (internet egress). 【🌟Star 18】

* [quic-go](https://github.com/lucas-clemente/quic-go) - An implementation of the QUIC protocol in pure Go. 【🌟Star 3682】

* [raw](https://github.com/mdlayher/raw) - Package raw enables reading and writing data at the device driver level for a network interface. 【🌟Star 337】

* [sftp](https://github.com/pkg/sftp) - Package sftp implements the SSH File Transfer Protocol as described in https://filezilla-project.org/specs/draft-ietf-secsh-filexfer-02.txt. 【🌟Star 819】

* [ssh](https://github.com/gliderlabs/ssh) - Higher-level API for building SSH servers (wraps crypto/ssh). 【🌟Star 1275】

* [sslb](https://github.com/eduardonunesp/sslb) - It's a Super Simples Load Balancer, just a little project to achieve some kind of performance. 【🌟Star 122】

* [stun](https://github.com/go-rtc/stun) - Go implementation of RFC 5389 STUN protocol. 【🌟Star 330】

* [tcp_server](https://github.com/firstrow/tcp_server) - Go library for building tcp servers faster. 【🌟Star 308】

* [tspool](https://github.com/two/tspool) - A TCP Library use worker pool to improve performance and protect your server. 【🌟Star 6】

* [utp](https://github.com/anacrolix/utp) - Go uTP micro transport protocol implementation. 【🌟Star 153】

* [water](https://github.com/songgao/water) - Simple TUN/TAP library. 【🌟Star 943】

* [webrtc](https://github.com/pions/webrtc) - A pure Go implementation of the WebRTC API. 【🌟Star 2938】

* [winrm](https://github.com/masterzen/winrm) - Go WinRM client to remotely execute commands on Windows machines. 【🌟Star 234】

* [xtcp](https://github.com/xfxdev/xtcp) - TCP Server Framework with simultaneous full duplex communication,graceful shutdown,custom protocol. 【🌟Star 92】


### HTTP Clients

*Libraries for making HTTP requests.*

* [gentleman](https://github.com/h2non/gentleman) - Full-featured plugin-driven HTTP client library. 【🌟Star 719】

* [grequests](https://github.com/levigross/grequests) - A Go "clone" of the great and famous Requests library. 【🌟Star 1507】

* [heimdall](https://github.com/gojektech/heimdall) - An enchanced http client with retry and hystrix capabilities. 【🌟Star 1204】

* [pester](https://github.com/sethgrid/pester) - Go HTTP client calls with retries, backoff, and concurrency. 【🌟Star 348】

* [resty](https://github.com/go-resty/resty) - Simple HTTP and REST client for Go inspired by Ruby rest-client. 【🌟Star 2470】

* [rq](https://github.com/ddo/rq) - A nicer interface for golang stdlib HTTP client. 【🌟Star 33】

* [sling](https://github.com/dghubble/sling) - Sling is a Go HTTP client library for creating and sending API requests. 【🌟Star 1082】

* [sreq](https://github.com/winterssy/sreq) - A simple, user-friendly and concurrent safe HTTP request library for Go. 【🌟Star 48】


## OpenGL

*Libraries for using OpenGL in Go.*

* [gl](https://github.com/go-gl/gl) - Go bindings for OpenGL (generated via glow). 【🌟Star 679】

* [glfw](https://github.com/go-gl/glfw) - Go bindings for GLFW 3. 【🌟Star 835】

* [goxjs/gl](https://github.com/goxjs/gl) - Go cross-platform OpenGL bindings (OS X, Linux, Windows, browsers, iOS, Android). 【🌟Star 131】

* [goxjs/glfw](https://github.com/goxjs/glfw) - Go cross-platform glfw library for creating an OpenGL context and receiving events. 【🌟Star 59】

* [mathgl](https://github.com/go-gl/mathgl) - Pure Go math package specialized for 3D math, with inspiration from GLM. 【🌟Star 312】


## ORM

*Libraries that implement Object-Relational Mapping or datamapping techniques.*

* [beego orm](https://github.com/astaxie/beego/tree/master/orm) - Powerful orm framework for go. Support: pq/mysql/sqlite3.
* [go-firestorm](https://github.com/jschoedt/go-firestorm) - A simple ORM for Google/Firebase Cloud Firestore. 【🌟Star 7】

* [go-pg](https://github.com/go-pg/pg) - PostgreSQL ORM with focus on PostgreSQL specific features and performance. 【🌟Star 3432】

* [go-queryset](https://github.com/jirfag/go-queryset) - 100% type-safe ORM with code generation and MySQL, PostgreSQL, Sqlite3, SQL Server support based on GORM. 【🌟Star 481】

* [go-sqlbuilder](https://github.com/huandu/go-sqlbuilder) - A flexible and powerful SQL string builder library plus a zero-config ORM. 【🌟Star 341】

* [go-store](https://github.com/gosuri/go-store) - Simple and fast Redis backed key-value store library for Go. 【🌟Star 100】

* [GORM](https://github.com/jinzhu/gorm) - The fantastic ORM library for Golang, aims to be developer friendly. 【🌟Star 16859】

* [gormt](https://github.com/xxjwxc/gormt) - Mysql database to golang gorm struct. 【🌟Star 282】

* [gorp](https://github.com/go-gorp/gorp) - Go Relational Persistence, ORM-ish library for Go. 【🌟Star 3267】

* [grimoire](https://github.com/Fs02/grimoire) - Grimoire is a database access layer and validation for golang. (Support: MySQL, PostgreSQL and SQLite3). 【🌟Star 123】

* [lore](https://github.com/abrahambotros/lore) - Simple and lightweight pseudo-ORM/pseudo-struct-mapping environment for Go. 【🌟Star 5】

* [Marlow](https://github.com/dadleyy/marlow) - Generated ORM from project structs for compile time safety assurances. 【🌟Star 73】

* [pop/soda](https://github.com/gobuffalo/pop) - Database migration, creation, ORM, etc... for MySQL, PostgreSQL, and SQLite. 【🌟Star 791】

* [QBS](https://github.com/coocood/qbs) - Stands for Query By Struct. A Go ORM. 【🌟Star 544】

* [reform](https://github.com/go-reform/reform) - Better ORM for Go, based on non-empty interfaces and code generation. 【🌟Star 836】

* [rel](https://github.com/Fs02/rel) - Golang SQL Repository Layer for Clean (Onion) Architecture. 【🌟Star 41】

* [SQLBoiler](https://github.com/volatiletech/sqlboiler) - ORM generator. Generate a featureful and blazing-fast ORM tailored to your database schema. 【🌟Star 2600】

* [upper.io/db](https://github.com/upper/db) - Single interface for interacting with different data sources through the use of adapters that wrap mature database drivers. 【🌟Star 2041】

* [Xorm](https://github.com/go-xorm/xorm) - Simple and powerful ORM for Go. 【🌟Star 5728】

* [Zoom](https://github.com/albrow/zoom) - Blazing-fast datastore and querying engine built on Redis. 【🌟Star 247】


## Package Management

*Official tooling for dependency and package management*

* [go modules](https://golang.org/cmd/go/#hdr-Modules__module_versions__and_more) - Modules are the unit of source code interchange and versioning. The go command has direct support for working with modules, including recording and resolving dependencies on other modules.

*Official experimental tooling for package management*

* [dep](https://github.com/golang/dep) - Go dependency tool. 【🌟Star 13046】

* [vgo](https://go.googlesource.com/vgo/) - Versioned Go.

*Unofficial libraries for package and dependency management.*

* [gigo](https://github.com/LyricalSecurity/gigo) - PIP-like dependency tool for golang, with support for private repositories and hashes. 【🌟Star 198】

* [glide](https://github.com/Masterminds/glide) - Manage your golang vendor and vendored packages with ease. Inspired by tools like Maven, Bundler, and Pip. 【🌟Star 7919】

* [godep](https://github.com/tools/godep) - dependency tool for go, godep helps build packages reproducibly by fixing their dependencies. 【🌟Star 5648】

* [gom](https://github.com/mattn/gom) - Go Manager - bundle for go. 【🌟Star 1367】

* [goop](https://github.com/nitrous-io/goop) - Simple dependency manager for Go (golang), inspired by Bundler. 【🌟Star 779】

* [gop](https://github.com/lunny/gop) - Build and manage your Go applications out of GOPATH. 【🌟Star 50】

* [gopm](https://github.com/gpmgo/gopm) - Go Package Manager. 【🌟Star 2455】

* [govendor](https://github.com/kardianos/govendor) - Go Package Manager. Go vendor tool that works with the standard vendor file. 【🌟Star 4980】

* [gpm](https://github.com/pote/gpm) - Barebones dependency manager for Go. 【🌟Star 1204】

* [johnny-deps](https://github.com/VividCortex/johnny-deps) - Minimal dependency version using Git. 【🌟Star 214】

* [mvn-golang](https://github.com/raydac/mvn-golang) - plugin that provides way for auto-loading of Golang SDK, dependency management and start build environment in Maven project infrastructure. 【🌟Star 95】

* [nut](https://github.com/jingweno/nut) - Vendor Go dependencies. 【🌟Star 244】

* [VenGO](https://github.com/DamnWidget/VenGO) - create and manage exportable isolated go virtual environments. 【🌟Star 116】


## Performance

* [jaeger](https://github.com/jaegertracing/jaeger) - A distributed tracing system. 【🌟Star 10020】

* [profile](https://github.com/pkg/profile) - Simple profiling support package for Go. 【🌟Star 1162】

* [tracer](https://github.com/kamilsk/tracer) - Simple, lightweight tracing. 【🌟Star 19】


## Query Language

* [gojsonq](https://github.com/thedevsaddam/gojsonq) - A simple Go package to Query over JSON Data. 【🌟Star 1103】

* [graphql](https://github.com/tmc/graphql) - graphql parser + utilities. 【🌟Star 52】

* [graphql](https://github.com/neelance/graphql-go) - GraphQL server with a focus on ease of use. 【🌟Star 3124】

* [graphql-go](https://github.com/graphql-go/graphql) - Implementation of GraphQL for Go. 【🌟Star 5883】

* [jsonql](https://github.com/elgs/jsonql) - JSON query expression library in Golang. 【🌟Star 216】

* [jsonslice](https://github.com/bhmj/jsonslice) - Jsonpath queries with advanced filters. 【🌟Star 32】

* [rql](https://github.com/a8m/rql) - Resource Query Language for REST API. 【🌟Star 130】

* [straf](https://github.com/SonicRoshan/straf) - Easily Convert Golang structs to GraphQL objects. 【🌟Star 8】


## Resource Embedding

* [esc](https://github.com/mjibson/esc) - Embeds files into Go programs and provides http.FileSystem interfaces to them. 【🌟Star 517】

* [fileb0x](https://github.com/UnnoTed/fileb0x) - Simple tool to embed files in go with focus on "customization" and ease to use. 【🌟Star 495】

* [go-embed](https://github.com/pyros2097/go-embed) - Generates go code to embed resource files into your library or executable. 【🌟Star 18】

* [go-resources](https://github.com/omeid/go-resources) - Unfancy resources embedding with Go. 【🌟Star 161】

* [go.rice](https://github.com/GeertJohan/go.rice) - go.rice is a Go package that makes working with resources such as html,js,css,images and templates very easy. 【🌟Star 1814】

* [packr](https://github.com/gobuffalo/packr) - The simple and easy way to embed static files into Go binaries. 【🌟Star 2575】

* [statics](https://github.com/go-playground/statics) - Embeds static resources into go files for single binary compilation + works with http.FileSystem + symlinks. 【🌟Star 54】

* [statik](https://github.com/rakyll/statik) - Embeds static files into a Go executable. 【🌟Star 2449】

* [templify](https://github.com/wlbr/templify) - Embed external template files into Go code to create single file binaries. 【🌟Star 22】

* [vfsgen](https://github.com/shurcooL/vfsgen) - Generates a vfsdata.go file that statically implements the given virtual filesystem. 【🌟Star 777】


## Science and Data Analysis

*Libraries for scientific computing and data analyzing.*

* [assocentity](https://github.com/ndabAP/assocentity) - Package assocentity returns the average distance from words to a given entity. 【🌟Star 6】

* [bradleyterry](https://github.com/seanhagen/bradleyterry) - Provides a Bradley-Terry Model for pairwise comparisons. 【🌟Star 2】

* [chart](https://github.com/vdobler/chart) - Simple Chart Plotting library for Go. Supports many graphs types. 【🌟Star 619】

* [dataframe-go](https://github.com/rocketlaunchr/dataframe-go) - Dataframes for machine-learning and statistics (similar to pandas). 【🌟Star 133】

* [evaler](https://github.com/soniah/evaler) - Simple floating point arithmetic expression evaluator. 【🌟Star 40】

* [ewma](https://github.com/VividCortex/ewma) - Exponentially-weighted moving averages. 【🌟Star 283】

* [geom](https://github.com/skelterjohn/geom) - 2D geometry for golang. 【🌟Star 43】

* [go-dsp](https://github.com/mjibson/go-dsp) - Digital Signal Processing for Go. 【🌟Star 658】

* [go-gt](https://github.com/ThePaw/go-gt) - Graph theory algorithms written in "Go" language. 【🌟Star 5】

* [goent](https://github.com/kzahedi/goent) - GO Implementation of Entropy Measures. 【🌟Star 15】

* [gohistogram](https://github.com/VividCortex/gohistogram) - Approximate histograms for data streams. 【🌟Star 136】

* [gonum](https://github.com/gonum/gonum) - Gonum is a set of numeric libraries for the Go programming language. It contains libraries for matrices, statistics, optimization, and more. 【🌟Star 3439】

* [gonum/plot](https://github.com/gonum/plot) - gonum/plot provides an API for building and drawing plots in Go. 【🌟Star 1340】

* [goraph](https://github.com/gyuho/goraph) - Pure Go graph theory library(data structure, algorith visualization). 【🌟Star 618】

* [gosl](https://github.com/cpmech/gosl) - Go scientific library for linear algebra, FFT, geometry, NURBS, numerical methods, probabilities, optimisation, differential equations, and more. 【🌟Star 1380】

* [GoStats](https://github.com/OGFris/GoStats) - GoStats is an Open Source GoLang library for math statistics mostly used in Machine Learning domains, it covers most of the Statistical measures functions. 【🌟Star 10】

* [graph](https://github.com/yourbasic/graph) - Library of basic graph algorithms. 【🌟Star 285】

* [ode](https://github.com/ChristopherRabotin/ode) - Ordinary differential equation (ODE) solver which supports extended states and channel-based iteration stop conditions. 【🌟Star 11】

* [orb](https://github.com/paulmach/orb) - 2D geometry types with clipping, GeoJSON and Mapbox Vector Tile support. 【🌟Star 245】

* [pagerank](https://github.com/alixaxel/pagerank) - Weighted PageRank algorithm implemented in Go. 【🌟Star 53】

* [piecewiselinear](https://github.com/sgreben/piecewiselinear) - Tiny linear interpolation library. 【🌟Star 10】

* [PiHex](https://github.com/claygod/PiHex) - Implementation of the "Bailey-Borwein-Plouffe" algorithm for the hexadecimal number Pi. 【🌟Star 8】

* [rootfinding](https://github.com/khezen/rootfinding) - root-finding algorithms library for finding roots of quadratic functions. 【🌟Star 3】

* [sparse](https://github.com/james-bowman/sparse) - Go Sparse matrix formats for linear algebra supporting scientific and machine learning applications, compatible with gonum matrix libraries. 【🌟Star 81】

* [stats](https://github.com/montanaflynn/stats) - Statistics package with common functions missing from the Golang standard library. 【🌟Star 1431】

* [streamtools](https://github.com/nytlabs/streamtools) - general purpose, graphical tool for dealing with streams of data. 【🌟Star 1316】

* [TextRank](https://github.com/DavidBelicza/TextRank) - TextRank implementation in Golang with extendable features (summarization, weighting, phrase extraction) and multithreading (goroutine) support. 【🌟Star 89】

* [triangolatte](https://github.com/tchayen/triangolatte) - 2D triangulation library. Allows translating lines and polygons (both based on points) to the language of GPUs. 【🌟Star 12】


## Security

*Libraries that are used to help make your application more secure.*

* [acmetool](https://github.com/hlandau/acme) - ACME (Let's Encrypt) client tool with automatic renewal. 【🌟Star 1730】

* [acra](https://github.com/cossacklabs/acra) - Network encryption proxy to protect database-based applications from data leaks: strong selective encryption, SQL injections prevention, intrusion detection system. 【🌟Star 526】

* [argon2pw](https://github.com/raja/argon2pw) - Argon2 password hash generation with constant-time password comparison. 【🌟Star 80】

* [autocert](https://godoc.org/golang.org/x/crypto/acme/autocert) - Auto provision Let's Encrypt certificates and start a TLS server.
* [BadActor](https://github.com/jaredfolkins/badactor) - In-memory, application-driven jailer built in the spirit of fail2ban. 【🌟Star 261】

* [Cameradar](https://github.com/Ullaakut/cameradar) - Tool and library to remotely hack RTSP streams from surveillance cameras. 【🌟Star 2009】

* [certificates](https://github.com/mvmaasakkers/certificates) - An opinionated tool for generating tls certificates. 【🌟Star 10】

* [go-generate-password](https://github.com/m1/go-generate-password) - Password generator that can be used on the cli or as a library. 【🌟Star 5】

* [go-yara](https://github.com/hillu/go-yara) - Go Bindings for [YARA](https://github.com/plusvic/yara), the "pattern matching swiss knife for malware researchers (and everyone else)". 【🌟Star 146】

* [goArgonPass](https://github.com/dwin/goArgonPass) - Argon2 password hash and verification designed to be compatible with existing Python and PHP implementations. 【🌟Star 12】

* [goSecretBoxPassword](https://github.com/dwin/goSecretBoxPassword) - A probably paranoid package for securely hashing and encrypting passwords. 【🌟Star 34】

* [Interpol](https://bitbucket.org/vahidi/interpol) - Rule-based data generator for fuzzing and penetration testing.
* [lego](https://github.com/xenolf/lego) - Pure Go ACME client library and CLI tool (for use with Let's Encrypt). 【🌟Star 3774】

* [memguard](https://github.com/awnumar/memguard) - A pure Go library for handling sensitive values in memory. 【🌟Star 1695】

* [nacl](https://github.com/kevinburke/nacl) - Go implementation of the NaCL set of API's. 【🌟Star 463】

* [passlib](https://github.com/hlandau/passlib) - Futureproof password hashing library. 【🌟Star 232】

* [secure](https://github.com/unrolled/secure) - HTTP middleware for Go that facilitates some quick security wins. 【🌟Star 1397】

* [simple-scrypt](https://github.com/elithrar/simple-scrypt) - Scrypt package with a simple, obvious API and automatic cost calibration built-in. 【🌟Star 162】

* [ssh-vault](https://github.com/ssh-vault/ssh-vault) - encrypt/decrypt using ssh keys. 【🌟Star 215】

* [sslmgr](https://github.com/adrianosela/sslmgr) - SSL certificates made easy with a high level wrapper around acme/autocert. 【🌟Star 8】


## Serialization

*Libraries and tools for binary serialization.*

* [asn1](https://github.com/PromonLogicalis/asn1) - Asn.1 BER and DER encoding library for golang. 【🌟Star 43】

* [bambam](https://github.com/glycerine/bambam) - generator for Cap'n Proto schemas from go. 【🌟Star 60】

* [bel](https://github.com/32leaves/bel) - Generate TypeScript interfaces from Go structs/interfaces. Useful for JSON RPC. 【🌟Star 8】

* [binstruct](https://github.com/ghostiam/binstruct) - Golang binary decoder for mapping data into the structure. 【🌟Star 14】

* [cbor](https://github.com/fxamacker/cbor) - Small, safe, and easy CBOR encoding and decoding library. 【🌟Star 100】

* [colfer](https://github.com/pascaldekloe/colfer) - Code generation for the Colfer binary format. 【🌟Star 507】

* [csvutil](https://github.com/jszwec/csvutil) - High Performance, idiomatic CSV record encoding and decoding to native Go structures. 【🌟Star 341】

* [fixedwidth](https://github.com/huydang284/fixedwidth) - Fixed-width text formatting (UTF-8 supported). 【🌟Star 4】

* [fwencoder](https://github.com/o1egl/fwencoder) - Fixed width file parser (encoding and decoding library) for Go. 【🌟Star 10】

* [go-capnproto](https://github.com/glycerine/go-capnproto) - Cap'n Proto library and parser for go. 【🌟Star 276】

* [go-codec](https://github.com/ugorji/go) - High Performance, feature-Rich, idiomatic encode, decode and rpc library for msgpack, cbor and json, with runtime-based OR code-generation support. 【🌟Star 1341】

* [gogoprotobuf](https://github.com/gogo/protobuf) - Protocol Buffers for Go with Gadgets. 【🌟Star 3434】

* [goprotobuf](https://github.com/golang/protobuf) - Go support, in the form of a library and protocol compiler plugin, for Google's protocol buffers. 【🌟Star 6034】

* [jsoniter](https://github.com/json-iterator/go) - High-performance 100% compatible drop-in replacement of "encoding/json". 【🌟Star 7020】

* [mapstructure](https://github.com/mitchellh/mapstructure) - Go library for decoding generic map values into native Go structures. 【🌟Star 2981】

* [php_session_decoder](https://github.com/yvasiyarov/php_session_decoder) - GoLang library for working with PHP session format and PHP Serialize/Unserialize functions. 【🌟Star 133】

* [pletter](https://github.com/vimeda/pletter) - A standard way to wrap a proto message for message brokers. 【🌟Star 7】

* [structomap](https://github.com/tuvistavie/structomap) - Library to easily and dynamically generate maps from static structures. 【🌟Star 107】


## Server Applications

* [algernon](https://github.com/xyproto/algernon) - HTTP/2 web server with built-in support for Lua, Markdown, GCSS and Amber. 【🌟Star 1655】

* [Caddy](https://github.com/mholt/caddy) - Caddy is an alternative, HTTP/2 web server that's easy to configure and use. 【🌟Star 25914】

* [consul](https://www.consul.io/) - Consul is a tool for service discovery, monitoring and configuration.
* [devd](https://github.com/cortesi/devd) - Local webserver for developers. 【🌟Star 2925】

* [discovery](https://github.com/Bilibili/discovery) - A registry for resilient mid-tier load balancing and failover. 【🌟Star 828】

* [dudeldu](https://github.com/krotik/dudeldu) - A simple SHOUTcast server. 【🌟Star 108】

* [etcd](https://github.com/coreos/etcd) - Highly-available key value store for shared configuration and service discovery. 【🌟Star 29193】

* [Fider](https://github.com/getfider/fider) - Fider is an open platform to collect and organize customer feedback. 【🌟Star 938】

* [Flagr](https://github.com/checkr/flagr) - Flagr is an open-source feature flagging and A/B testing service. 【🌟Star 970】

* [flipt](https://github.com/markphelps/flipt) - A self contained feature flag solution written in Go and Vue.js 【🌟Star 1139】

* [jackal](https://github.com/ortuman/jackal) - An XMPP server written in Go. 【🌟Star 769】

* [minio](https://github.com/minio/minio) - Minio is a distributed object storage server. 【🌟Star 19861】

* [nginx-prometheus](https://github.com/blind-oracle/nginx-prometheus) - Nginx log parser and exporter to Prometheus. 【🌟Star 9】

* [nsq](http://nsq.io/) - A realtime distributed messaging platform.
* [psql-streamer](https://github.com/blind-oracle/psql-streamer) - Stream database events from PostgreSQL to Kafka. 【🌟Star 12】

* [riemann-relay](https://github.com/blind-oracle/riemann-relay) - Relay to load-balance Riemann events and/or convert them to Carbon. 【🌟Star 0】

* [RoadRunner](https://github.com/spiral/roadrunner) - High-performance PHP application server, load-balancer and process manager. 【🌟Star 3870】

* [SFTPGo](https://github.com/drakkan/sftpgo) - Full featured and highly configurable SFTP server software. 【🌟Star 1189】

* [yakvs](https://git.sci4me.com/sci4me/yakvs) - Small, networked, in-memory key-value store.


## Stream Processing

*Libraries and tools for stream processing and reactive programming.*

* [go-streams](https://github.com/reugn/go-streams) - Go stream processing library. 【🌟Star 265】


## Template Engines

*Libraries and tools for templating and lexing.*

* [ace](https://github.com/yosssi/ace) - Ace is an HTML template engine for Go, inspired by Slim and Jade. Ace is a refinement of Gold. 【🌟Star 778】

* [amber](https://github.com/eknkc/amber) - Amber is an elegant templating engine for Go Programming Language It is inspired from HAML and Jade. 【🌟Star 836】

* [damsel](https://github.com/dskinner/damsel) - Markup language featuring html outlining via css-selectors, extensible via pkg html/template and others. 【🌟Star 21】

* [ego](https://github.com/benbjohnson/ego) - Lightweight templating language that lets you write templates in Go. Templates are translated into Go and compiled. 【🌟Star 424】

* [extemplate](https://github.com/dannyvankooten/extemplate) - Tiny wrapper around html/template to allow for easy file-based template inheritance. 【🌟Star 17】

* [fasttemplate](https://github.com/valyala/fasttemplate) - Simple and fast template engine. Substitutes template placeholders up to 10x faster than [text/template](http://golang.org/pkg/text/template/). 【🌟Star 335】

* [gofpdf](https://github.com/jung-kurt/gofpdf) - PDF document generator with high level support for text, drawing and images. 【🌟Star 3453】

* [gospin](https://github.com/m1/gospin) - Article spinning and spintax/spinning syntax engine, useful for A/B, testing pieces of text/articles and creating more natural conversations. 【🌟Star 5】

* [goview](https://github.com/foolin/goview) - Goview is a lightweight, minimalist and idiomatic template library based on golang html/template for building Go web application. 【🌟Star 90】

* [hero](https://github.com/shiyanhui/hero) - Hero is a handy, fast and powerful go template engine. 【🌟Star 1263】

* [jet](https://github.com/CloudyKit/jet) - Jet template engine. 【🌟Star 614】

* [kasia.go](https://github.com/ziutek/kasia.go) - Templating system for HTML and other text documents - go implementation. 【🌟Star 71】

* [liquid](https://github.com/osteele/liquid) - Go implementation of Shopify Liquid templates. 【🌟Star 92】

* [maroto](https://github.com/johnfercher/maroto) - A maroto way to create PDFs. Maroto is inspired in Bootstrap and uses gofpdf. Fast and simple. 【🌟Star 93】

* [mustache](https://github.com/hoisie/mustache) - Go implementation of the Mustache template language. 【🌟Star 977】

* [pongo2](https://github.com/flosch/pongo2) - Django-like template-engine for Go. 【🌟Star 1589】

* [quicktemplate](https://github.com/valyala/quicktemplate) - Fast, powerful, yet easy to use template engine. Converts templates into Go code and then compiles it. 【🌟Star 1591】

* [raymond](https://github.com/aymerick/raymond) - Complete handlebars implementation in Go. 【🌟Star 359】

* [Razor](https://github.com/sipin/gorazor) - Razor view engine for Golang. 【🌟Star 727】

* [Soy](https://github.com/robfig/soy) - Closure templates (aka Soy templates) for Go, following the [official spec](https://developers.google.com/closure/templates/). 【🌟Star 146】

* [velvet](https://github.com/gobuffalo/velvet) - Complete handlebars implementation in Go. 【🌟Star 70】


## Testing

*Libraries for testing codebases and generating test data.*

* Testing Frameworks
    * [apitest](https://apitest.dev) - Simple and extensible behavioural testing library for REST based services or HTTP handlers that supports mocking external http calls and rendering of sequence diagrams.
    * [assert](https://github.com/go-playground/assert) - Basic Assertion Library used along side native go testing, with building blocks for custom assertions. 【🌟Star 17】

    * [badio](https://github.com/cavaliercoder/badio) - Extensions to Go's `testing/iotest` package. 【🌟Star 9】

    * [baloo](https://github.com/h2non/baloo) - Expressive and versatile end-to-end HTTP API testing made easy. 【🌟Star 667】

    * [biff](https://github.com/fulldump/biff) - Bifurcation testing framework, BDD compatible. 【🌟Star 7】

    * [charlatan](https://github.com/percolate/charlatan) - Tool to generate fake interface implementations for tests. 【🌟Star 192】

    * [commander](https://github.com/SimonBaeumer/commander) - Tool for testing cli applications on windows, linux and osx. 【🌟Star 58】

    * [cupaloy](https://github.com/bradleyjkemp/cupaloy) - Simple snapshot testing addon for your test framework. 【🌟Star 98】

    * [dbcleaner](https://github.com/khaiql/dbcleaner) - Clean database for testing purpose, inspired by `database_cleaner` in Ruby. 【🌟Star 97】

    * [dsunit](https://github.com/viant/dsunit) - Datastore testing for SQL, NoSQL, structured files. 【🌟Star 27】

    * [embedded-postgres](https://github.com/fergusstrange/embedded-postgres) - Run a real Postgres database locally on Linux, OSX or Windows as part of another Go application or test. 【🌟Star 8】

    * [endly](https://github.com/viant/endly) - Declarative end to end functional testing. 【🌟Star 120】

    * [flute](https://github.com/suzuki-shunsuke/flute) - HTTP client testing framework. 【🌟Star 11】

    * [frisby](https://github.com/verdverm/frisby) - REST API testing framework. 【🌟Star 255】

    * [ginkgo](http://onsi.github.io/ginkgo/) - BDD Testing Framework for Go.
    * [go-carpet](https://github.com/msoap/go-carpet) - Tool for viewing test coverage in terminal. 【🌟Star 201】

    * [go-cmp](https://github.com/google/go-cmp) - Package for comparing Go values in tests. 【🌟Star 1477】

    * [go-mutesting](https://github.com/zimmski/go-mutesting) - Mutation testing for Go source code. 【🌟Star 323】

    * [go-testdeep](https://github.com/maxatome/go-testdeep) - Extremely flexible golang deep comparison, extends the go testing package. 【🌟Star 75】

    * [go-vcr](https://github.com/dnaeon/go-vcr) - Record and replay your HTTP interactions for fast, deterministic and accurate tests. 【🌟Star 366】

    * [goblin](https://github.com/franela/goblin) - Mocha like testing framework fo Go. 【🌟Star 651】

    * [gocheck](http://labix.org/gocheck) - More advanced testing framework alternative to gotest.
    * [GoConvey](https://github.com/smartystreets/goconvey/) - BDD-style framework with web UI and live reload. 【🌟Star 0】

    * [gocrest](https://github.com/corbym/gocrest) - Composable hamcrest-like matchers for Go assertions. 【🌟Star 9】

    * [godog](https://github.com/DATA-DOG/godog) - Cucumber or Behat like BDD framework for Go. 【🌟Star 887】

    * [gofight](https://github.com/appleboy/gofight) - API Handler Testing for Golang Router framework. 【🌟Star 291】

    * [gogiven](https://github.com/corbym/gogiven) - YATSPEC-like BDD testing framework for Go. 【🌟Star 8】

    * [gomatch](https://github.com/jfilipczyk/gomatch) - library created for testing JSON against patterns. 【🌟Star 32】

    * [gomega](http://onsi.github.io/gomega/) - Rspec like matcher/assertion library.
    * [GoSpec](https://github.com/orfjackal/gospec) - BDD-style testing framework for the Go programming language. 【🌟Star 112】

    * [gospecify](https://github.com/stesla/gospecify) - This provides a BDD syntax for testing your Go code. It should be familiar to anybody who has used libraries such as rspec. 【🌟Star 53】

    * [gosuite](https://github.com/pavlo/gosuite) - Brings lightweight test suites with setup/teardown facilities to `testing` by leveraging Go1.7's Subtests. 【🌟Star 9】

    * [gotest.tools](https://github.com/gotestyourself/gotest.tools) - A collection of packages to augment the go testing package and support common patterns. 【🌟Star 141】

    * [Hamcrest](https://github.com/rdrdr/hamcrest) - fluent framework for declarative Matcher objects that, when applied to input values, produce self-describing results. 【🌟Star 27】

    * [httpexpect](https://github.com/gavv/httpexpect) - Concise, declarative, and easy to use end-to-end HTTP and REST API testing. 【🌟Star 1253】

    * [jsonassert](https://github.com/kinbiko/jsonassert) - Package for verifying that your JSON payloads are serialized correctly. 【🌟Star 30】

    * [restit](https://github.com/yookoala/restit) - Go micro framework to help writing RESTful API integration test. 【🌟Star 50】

    * [schema](https://github.com/jgroeneveld/schema) - Quick and easy expression matching for JSON schemas used in requests and responses. 【🌟Star 8】

    * [testcase](https://github.com/adamluzsi/testcase) - Idiomatic testing framework for Behavior Driven Development. 【🌟Star 12】

    * [testfixtures](https://github.com/go-testfixtures/testfixtures) - A helper for Rails' like test fixtures to test database applications. 【🌟Star 425】

    * [Testify](https://github.com/stretchr/testify) - Sacred extension to the standard go testing package. 【🌟Star 9465】

    * [testmd](https://godoc.org/github.com/tvastar/test/cmd/testmd) - Convert markdown snippets into testable go code.
    * [testsql](https://github.com/zhulongcheng/testsql) - Generate test data from SQL files before testing and clear it after finished. 【🌟Star 7】

    * [trial](https://github.com/jgroeneveld/trial) - Quick and easy extendable assertions without introducing much boilerplate. 【🌟Star 4】

    * [Tt](https://github.com/vcaesar/tt) - Simple and colorful test tools. 【🌟Star 6】

    * [wstest](https://github.com/posener/wstest) - Websocket client for unit-testing a websocket http.Handler. 【🌟Star 71】


* Mock
    * [counterfeiter](https://github.com/maxbrunsfeld/counterfeiter) - Tool for generating self-contained mock objects. 【🌟Star 390】

    * [go-sqlmock](https://github.com/DATA-DOG/go-sqlmock) - Mock SQL driver for testing database interactions. 【🌟Star 2167】

    * [go-txdb](https://github.com/DATA-DOG/go-txdb) - Single transaction based database driver mainly for testing purposes. 【🌟Star 216】

    * [gock](https://github.com/h2non/gock) - Versatile HTTP mocking made easy. 【🌟Star 940】

    * [gomock](https://github.com/golang/mock) - Mocking framework for the Go programming language. 【🌟Star 3542】

    * [govcr](https://github.com/seborama/govcr) - HTTP mock for Golang: record and replay HTTP interactions for offline testing. 【🌟Star 87】

    * [hoverfly](https://github.com/SpectoLabs/hoverfly) - HTTP(S) proxy for recording and simulating REST/SOAP APIs with extensible middleware and easy-to-use CLI. 【🌟Star 1510】

    * [httpmock](https://github.com/jarcoal/httpmock) - Easy mocking of HTTP responses from external resources. 【🌟Star 690】

    * [minimock](https://github.com/gojuno/minimock) - Mock generator for Go interfaces. 【🌟Star 288】

    * [mockhttp](https://github.com/tv42/mockhttp) - Mock object for Go http.ResponseWriter. 【🌟Star 22】

    * [timex](https://github.com/cabify/timex) - A test-friendly replacement for the native `time` package. 【🌟Star 23】


* Fuzzing and delta-debugging/reducing/shrinking.
    * [go-fuzz](https://github.com/dvyukov/go-fuzz) - Randomized testing system. 【🌟Star 3279】

    * [gofuzz](https://github.com/google/gofuzz) - Library for populating go objects with random values. 【🌟Star 692】

    * [Tavor](https://github.com/zimmski/tavor) - Generic fuzzing and delta-debugging framework. 【🌟Star 218】


* Selenium and browser control tools.
    * [cdp](https://github.com/mafredri/cdp) - Type-safe bindings for the Chrome Debugging Protocol that can be used with browsers or other debug targets that implement it. 【🌟Star 399】

    * [chromedp](https://github.com/knq/chromedp) - a way to drive/test Chrome, Safari, Edge, Android Webviews, and other browsers supporting the Chrome Debugging Protocol. 【🌟Star 4206】

    * [ggr](https://github.com/aerokube/ggr) - a lightweight server that routes and proxies Selenium WebDriver requests to multiple Selenium hubs. 【🌟Star 234】

    * [selenoid](https://github.com/aerokube/selenoid) - alternative Selenium hub server that launches browsers within containers. 【🌟Star 1454】


* Fail injection
    * [failpoint](https://github.com/pingcap/failpoint) - An implementation of [failpoints](http://www.freebsd.org/cgi/man.cgi?query=fail) for Golang. 【🌟Star 471】


## Text Processing

*Libraries for parsing and manipulating texts.*

* Specific Formats
    * [align](https://github.com/Guitarbum722/align) - A general purpose application that aligns text. 【🌟Star 61】

    * [allot](https://github.com/sbstjn/allot) - Placeholder and wildcard text parsing for CLI tools and bots. 【🌟Star 38】

    * [bbConvert](https://github.com/CalebQ42/bbConvert) - Converts bbCode to HTML that allows you to add support for custom bbCode tags. 【🌟Star 5】

    * [blackfriday](https://github.com/russross/blackfriday) - Markdown processor in Go. 【🌟Star 4195】

    * [bluemonday](https://github.com/microcosm-cc/bluemonday) - HTML Sanitizer. 【🌟Star 1381】

    * [codetree](https://github.com/aerogo/codetree) - Parses indented code (python, pixy, scarlet, etc.) and returns a tree structure. 【🌟Star 14】

    * [colly](https://github.com/asciimoo/colly) - Fast and Elegant Scraping Framework for Gophers. 【🌟Star 9819】

    * [commonregex](https://github.com/mingrammer/commonregex) - A collection of common regular expressions for Go. 【🌟Star 573】

    * [dataflowkit](https://github.com/slotix/dataflowkit) - Web scraping Framework to turn websites into structured data. 【🌟Star 340】

    * [did](https://github.com/ockam-network/did) - DID (Decentralized Identifiers) Parser and Stringer in Go. 【🌟Star 26】

    * [doi](https://github.com/hscells/doi) - Document object identifier (doi) parser in Go. 【🌟Star 4】

    * [editorconfig-core-go](https://github.com/editorconfig/editorconfig-core-go) - Editorconfig file parser and manipulator for Go. 【🌟Star 53】

    * [enca](https://github.com/endeveit/enca) - Minimal cgo bindings for [libenca](http://cihar.com/software/enca/). 【🌟Star 8】

    * [encdec](https://github.com/mickep76/encdec) - Package provides a generic interface to encoders and decodersa. 【🌟Star 3】

    * [genex](https://github.com/alixaxel/genex) - Count and expand Regular Expressions into all matching Strings. 【🌟Star 57】

    * [github_flavored_markdown](https://godoc.org/github.com/shurcooL/github_flavored_markdown) - GitHub Flavored Markdown renderer (using blackfriday) with fenced code block highlighting, clickable header anchor links.
    * [go-fixedwidth](https://github.com/ianlopshire/go-fixedwidth) - Fixed-width text formatting (encoder/decoder with reflection). 【🌟Star 33】

    * [go-humanize](https://github.com/dustin/go-humanize) - Formatters for time, numbers, and memory size to human readable format. 【🌟Star 2070】

    * [go-nmea](https://github.com/adrianmo/go-nmea) - NMEA parser library for the Go language. 【🌟Star 108】

    * [go-runewidth](https://github.com/mattn/go-runewidth) - Functions to get fixed width of the character or string. 【🌟Star 239】

    * [go-slugify](https://github.com/mozillazg/go-slugify) - Make pretty slug with multiple languages support. 【🌟Star 57】

    * [go-toml](https://github.com/pelletier/go-toml) - Go library for the TOML format with query support and handy cli tools. 【🌟Star 688】

    * [go-vcard](https://github.com/emersion/go-vcard) - Parse and format vCard. 【🌟Star 32】

    * [go-zero-width](https://github.com/trubitsyn/go-zero-width) - Zero-width character detection and removal for Go. 【🌟Star 45】

    * [gofeed](https://github.com/mmcdole/gofeed) - Parse RSS and Atom feeds in Go. 【🌟Star 1179】

    * [gographviz](https://github.com/awalterschulze/gographviz) - Parses the Graphviz DOT language. 【🌟Star 339】

    * [gommon/bytes](https://github.com/labstack/gommon/tree/master/bytes) - Format bytes to string.
    * [gonameparts](https://github.com/polera/gonameparts) - Parses human names into individual name parts. 【🌟Star 30】

    * [goq](https://github.com/andrewstuart/goq) - Declarative unmarshaling of HTML using struct tags with jQuery syntax (uses GoQuery). 【🌟Star 158】

    * [GoQuery](https://github.com/PuerkitoBio/goquery) - GoQuery brings a syntax and a set of features similar to jQuery to the Go language. 【🌟Star 8261】

    * [goregen](https://github.com/zach-klippenstein/goregen) - Library for generating random strings from regular expressions. 【🌟Star 38】

    * [goribot](https://github.com/zhshch2002/goribot) - A simple golang spider/scraping framework,build a spider in 3 lines. 【🌟Star 57】

    * [gotext](https://github.com/leonelquinteros/gotext) - GNU gettext utilities for Go. 【🌟Star 247】

    * [guesslanguage](https://github.com/endeveit/guesslanguage) - Functions to determine the natural language of a unicode text. 【🌟Star 45】

    * [htmlquery](https://github.com/antchfx/htmlquery) - An XPath query package for HTML, lets you extract data or evaluate from HTML documents by an XPath expression. 【🌟Star 183】

    * [inject](https://github.com/facebookgo/inject) - Package inject provides a reflect based injector. 【🌟Star 1189】

    * [ltsv](https://github.com/Wing924/ltsv) - High performance [LTSV (Labeled Tab Separeted Value)](http://ltsv.org/) reader for Go. 【🌟Star 3】

    * [mxj](https://github.com/clbanning/mxj) - Encode / decode XML as JSON or map[string]interface{}; extract values with dot-notation paths and wildcards. Replaces x2j and j2x packages. 【🌟Star 353】

    * [sdp](https://github.com/gortc/sdp) - SDP: Session Description Protocol [[RFC 4566](https://tools.ietf.org/html/rfc4566)]. 【🌟Star 80】

    * [sh](https://github.com/mvdan/sh) - Shell parser and formatter. 【🌟Star 2384】

    * [slug](https://github.com/gosimple/slug) - URL-friendly slugify with multiple languages support. 【🌟Star 489】

    * [Slugify](https://github.com/avelino/slugify) - Go slugify application that handles string. 【🌟Star 27】

    * [syndfeed](https://github.com/zhengchun/syndfeed) - A syndication feed for Atom 1.0 and RSS 2.0. 【🌟Star 7】

    * [toml](https://github.com/BurntSushi/toml) - TOML configuration format (encoder/decoder with reflection). 【🌟Star 3015】

* Utility
    * [gofuckyourself](https://github.com/JoshuaDoes/gofuckyourself) - A sanitization-based swear filter for Go. 【🌟Star 19】

    * [gotabulate](https://github.com/bndr/gotabulate) - Easily pretty-print your tabular data with Go. 【🌟Star 222】

    * [kace](https://github.com/codemodus/kace) - Common case conversions covering common initialisms. 【🌟Star 12】

    * [parseargs-go](https://github.com/nproc/parseargs-go) - string argument parser that understands quotes and backslashes. 【🌟Star 7】

    * [parth](https://github.com/codemodus/parth) - URL path segmentation parsing. 【🌟Star 34】

    * [radix](https://github.com/yourbasic/radix) - fast string sorting algorithm. 【🌟Star 153】

    * [Tagify](https://github.com/zoomio/tagify) - Produces a set of tags from given source. 【🌟Star 3】

	* [textwrap](https://github.com/isbm/textwrap) - Implementation of `textwrap` module from Python. 【🌟Star 1】

    * [TySug](https://github.com/Dynom/TySug) - Alternative suggestions with respect to keyboard layouts. 【🌟Star 3】

    * [xj2go](https://github.com/stackerzzq/xj2go) - Convert xml or json to go struct. 【🌟Star 18】

    * [xurls](https://github.com/mvdan/xurls) - Extract urls from text. 【🌟Star 570】


## Third-party APIs

*Libraries for accessing third party APIs.*

* [amazon-product-advertising-api](https://github.com/ngs/go-amazon-product-advertising-api) - Go Client Library for [Amazon Product Advertising API](https://affiliate-program.amazon.com/gp/advertising/api/detail/main.html). 【🌟Star 38】

* [anaconda](https://github.com/ChimeraCoder/anaconda) - Go client library for the Twitter 1.1 API. 【🌟Star 1011】

* [aws-sdk-go](https://github.com/aws/aws-sdk-go) - The official AWS SDK for the Go programming language. 【🌟Star 5475】

* [brewerydb](https://github.com/naegelejd/brewerydb) - Go library for accessing the BreweryDB API. 【🌟Star 16】

* [cachet](https://github.com/andygrunwald/cachet) - Go client library for [Cachet (open source status page system)](https://cachethq.io/). 【🌟Star 78】

* [circleci](https://github.com/jszwedko/go-circleci) - Go client library for interacting with CircleCI's API. 【🌟Star 46】

* [clarifai](https://github.com/samuelcouch/clarifai) - Go client library for interfacing with the Clarifai API. 【🌟Star 57】

* [codeship-go](https://github.com/codeship/codeship-go) - Go client library for interacting with Codeship's API v2. 【🌟Star 16】

* [coinpaprika-go](https://github.com/coinpaprika/coinpaprika-api-go-client) - Go client library for interacting with Coinpaprika's API. 【🌟Star 12】

* [discordgo](https://github.com/bwmarrin/discordgo) - Go bindings for the Discord Chat API. 【🌟Star 1101】

* [ethrpc](https://github.com/onrik/ethrpc) - Go bindings for Ethereum JSON RPC API. 【🌟Star 181】

* [facebook](https://github.com/huandu/facebook) - Go Library that supports the Facebook Graph API. 【🌟Star 826】

* [fcm](https://github.com/maddevsio/fcm) - Go library for Firebase Cloud Messaging. 【🌟Star 34】

* [gads](https://github.com/emiddleton/gads) - Google Adwords Unofficial API. 【🌟Star 47】

* [gami](https://github.com/bit4bit/gami) - Go library for Asterisk Manager Interface. 【🌟Star 27】

* [gcm](https://github.com/Aorioli/gcm) - Go library for Google Cloud Messaging. 【🌟Star 29】

* [geo-golang](https://github.com/codingsince1985/geo-golang) - Go Library to access [Google Maps](https://developers.google.com/maps/documentation/geocoding/intro), [MapQuest](http://open.mapquestapi.com/geocoding/), [Nominatim](https://developer.mapquest.com/documentation/open/nominatim-search), [OpenCage](http://geocoder.opencagedata.com/api.html), [Bing](https://msdn.microsoft.com/en-us/library/ff701715.aspx), [Mapbox](https://www.mapbox.com/developers/api/geocoding/), and [OpenStreetMap](https://wiki.openstreetmap.org/wiki/Nominatim) geocoding / reverse geocoding APIs. 【🌟Star 335】

* [github](https://github.com/google/go-github) - Go library for accessing the GitHub REST API v3. 【🌟Star 5409】

* [githubql](https://github.com/shurcooL/githubql) - Go library for accessing the GitHub GraphQL API v4. 【🌟Star 585】

* [go-chronos](https://github.com/axelspringer/go-chronos) - Go library for interacting with the [Chronos](https://mesos.github.io/chronos/) Job Scheduler 【🌟Star 3】

* [go-hacknews](https://github.com/PaulRosset/go-hacknews) - Tiny Go client for HackerNews API. 【🌟Star 10】

* [go-here](https://github.com/abdullahselek/go-here) - Go client library around the HERE location based APIs. 【🌟Star 6】

* [go-imgur](https://github.com/koffeinsource/go-imgur) - Go client library for [imgur](https://imgur.com) 【🌟Star 14】

* [go-jira](https://github.com/andygrunwald/go-jira) - Go client library for [Atlassian JIRA](https://www.atlassian.com/software/jira) 【🌟Star 665】

* [go-marathon](https://github.com/gambol99/go-marathon) - Go library for interacting with Mesosphere's Marathon PAAS. 【🌟Star 192】

* [go-myanimelist](https://github.com/nstratos/go-myanimelist) - Go client library for accessing the [MyAnimeList API](http://myanimelist.net/modules.php?go=api). 【🌟Star 15】

* [go-sophos](https://github.com/esurdam/go-sophos) - Go client library for the [Sophos UTM REST API](https://www.sophos.com/en-us/medialibrary/PDFs/documentation/UTMonAWS/Sophos-UTM-RESTful-API.pdf?la=en) with zero dependencies. 【🌟Star 5】

* [go-sptrans](https://github.com/sergioaugrod/go-sptrans) - Go client library for the SPTrans Olho Vivo API. 【🌟Star 7】

* [go-telegraph](https://gitlab.com/toby3d/telegraph) - Telegraph publishing platform API client.
* [go-trending](https://github.com/andygrunwald/go-trending) - Go library for accessing [trending repositories](https://github.com/trending) and [developers](https://github.com/trending/developers) at Github. 【🌟Star 105】

* [go-twitch](https://github.com/knspriggs/go-twitch) - Go client for interacting with the Twitch v3 API. 【🌟Star 18】

* [go-twitter](https://github.com/dghubble/go-twitter) - Go client library for the Twitter v1.1 APIs. 【🌟Star 886】

* [go-unsplash](https://github.com/hbagdi/go-unsplash) - Go client library for the [Unsplash.com](https://unsplash.com) API. 【🌟Star 25】

* [go-xkcd](https://github.com/nishanths/go-xkcd) - Go client for the xkcd API. 【🌟Star 40】

* [golyrics](https://github.com/mamal72/golyrics) - Golyrics is a Go library to fetch music lyrics data from the Wikia website. 【🌟Star 33】

* [gomalshare](https://github.com/MonaxGT/gomalshare) - Go library MalShare API [malshare.com](http://www.malshare.com/) 【🌟Star 4】

* [GoMusicBrainz](https://github.com/michiwend/gomusicbrainz) - Go MusicBrainz WS2 client library. 【🌟Star 37】

* [google](https://github.com/google/google-api-go-client) - Auto-generated Google APIs for Go. 【🌟Star 2092】

* [google-analytics](https://github.com/chonthu/go-google-analytics) - Simple wrapper for easy google analytics reporting. 【🌟Star 11】

* [google-cloud](https://github.com/GoogleCloudPlatform/gcloud-golang) - Google Cloud APIs Go Client Library. 【🌟Star 1983】

* [google-email-audit-api](https://github.com/ngs/go-google-email-audit-api) - Go client library for [Google G Suite Email Audit API](https://developers.google.com/admin-sdk/email-audit/). 【🌟Star 6】

* [gosip](https://github.com/koltyakov/gosip) - Go client library SharePoint API. 【🌟Star 30】

* [gostorm](https://github.com/jsgilmore/gostorm) - GoStorm is a Go library that implements the communications protocol required to write Storm spouts and Bolts in Go that communicate with the Storm shells. 【🌟Star 125】

* [hipchat](https://github.com/andybons/hipchat) - This project implements a golang client library for the Hipchat API. 【🌟Star 108】

* [hipchat (xmpp)](https://github.com/daneharrigan/hipchat) - A golang package to communicate with HipChat over XMPP. 【🌟Star 112】

* [igdb](https://github.com/Henry-Sarabia/igdb) - Go client for the [Internet Game Database API](https://api.igdb.com/). 【🌟Star 55】

* [lastpass-go](https://github.com/ansd/lastpass-go) - Go client library for the [LastPass](https://www.lastpass.com/) API. 【🌟Star 9】

* [libgoffi](https://github.com/clevabit/libgoffi) - Library adapter toolbox for native [libffi](http://sourceware.org/libffi/) integration 【🌟Star 1】

* [Medium](https://github.com/Medium/medium-sdk-go) - Golang SDK for Medium's OAuth2 API. 【🌟Star 122】

* [megos](https://github.com/andygrunwald/megos) - Client library for accessing an [Apache Mesos](http://mesos.apache.org/) cluster. 【🌟Star 57】

* [minio-go](https://github.com/minio/minio-go) - Minio Go Library for Amazon S3 compatible cloud storage. 【🌟Star 846】

* [mixpanel](https://github.com/dukex/mixpanel) - Mixpanel is a library for tracking events and sending Mixpanel profile updates to Mixpanel from your go applications. 【🌟Star 30】

* [patreon-go](https://github.com/mxpv/patreon-go) - Go library for Patreon API. 【🌟Star 19】

* [paypal](https://github.com/logpacker/PayPal-Go-SDK) - Wrapper for PayPal payment API. 【🌟Star 333】

* [playlyfe](https://github.com/playlyfe/playlyfe-go-sdk) - The Playlyfe Rest API Go SDK. 【🌟Star 1】

* [pushover](https://github.com/gregdel/pushover) - Go wrapper for the Pushover API. 【🌟Star 66】

* [rrdaclient](https://github.com/Omie/rrdaclient) - Go Library to access statdns.com API, which is in turn RRDA API. DNS Queries over HTTP. 【🌟Star 8】

* [shopify](https://github.com/rapito/go-shopify) - Go Library to make CRUD request to the Shopify API. 【🌟Star 19】

* [simples3](https://github.com/rhnvrm/simples3) - Simple no frills AWS S3 Library using REST with V4 Signing written in Go. 【🌟Star 35】

* [slack](https://github.com/nlopes/slack) - Slack API in Go. 【🌟Star 2700】

* [smite](https://github.com/sergiotapia/smitego) - Go package to wraps access to the Smite game API. 【🌟Star 10】

* [spotify](https://github.com/rapito/go-spotify) - Go Library to access Spotify WEB API. 【🌟Star 21】

* [steam](https://github.com/sostronk/go-steam) - Go Library to interact with Steam game servers. 【🌟Star 19】

* [stripe](https://github.com/stripe/stripe-go) - Go client for the Stripe API. 【🌟Star 1067】

* [textbelt](https://github.com/dietsche/textbelt) - Go client for the textbelt.com txt messaging API. 【🌟Star 16】

* [translate](https://github.com/poorny/translate) - Go online translation package. 【🌟Star 29】

* [Trello](https://github.com/adlio/trello) - Go wrapper for the Trello API. 【🌟Star 125】

* [TripAdvisor](https://github.com/mrbenosborne/tripadvisor-golang) - Go wrapper for the TripAdvisor API. 【🌟Star 1】

* [tumblr](https://github.com/mattcunningham/gumblr) - Go wrapper for the Tumblr v2 API. 【🌟Star 6】

* [uptimerobot](https://github.com/bitfield/uptimerobot) - Go wrapper and command-line client for the Uptime Robot v2 API. 【🌟Star 35】

* [vl-go](https://github.com/verifid/vl-go) - Go client library around the VerifID identity verification layer API. 【🌟Star 1】

* [webhooks](https://github.com/go-playground/webhooks) - Webhook receiver for GitHub and Bitbucket. 【🌟Star 435】

* [wit-go](https://github.com/wit-ai/wit-go) - Go client for wit.ai HTTP API. 【🌟Star 59】

* [ynab](https://github.com/brunomvsouza/ynab.go) - Go wrapper for the YNAB API. 【🌟Star 21】

* [zooz](https://github.com/gojuno/go-zooz) - Go client for the Zooz API. 【🌟Star 5】


## Utilities

*General utilities and tools to make your life easier.*

* [apm](https://github.com/topfreegames/apm) - Process manager for Golang applications with an HTTP API. 【🌟Star 133】

* [backscanner](https://github.com/icza/backscanner) - A scanner similar to bufio.Scanner, but it reads and returns lines in reverse order, starting at a given position and going backward. 【🌟Star 9】

* [beyond](https://github.com/wesovilabs/beyond) - The Go tool that will drive you to the AOP world! 【🌟Star 30】

* [blank](https://github.com/Henry-Sarabia/blank) - Verify or remove blanks and whitespace from strings. 【🌟Star 4】

* [boilr](https://github.com/tmrts/boilr) - Blazingly fast CLI tool for creating projects from boilerplate templates. 【🌟Star 1026】

* [chyle](https://github.com/antham/chyle) - Changelog generator using a git repository with multiple configuration possibilities. 【🌟Star 115】

* [circuit](https://github.com/cep21/circuit) - An efficient and feature complete Hystrix like Go implementation of the circuit breaker pattern. 【🌟Star 419】

* [circuitbreaker](https://github.com/rubyist/circuitbreaker) - Circuit Breakers in Go. 【🌟Star 840】

* [clockwork](https://github.com/jonboulle/clockwork) - A simple fake clock for golang. 【🌟Star 243】

* [cmd](https://github.com/SimonBaeumer/cmd) - Library for executing shell commands on osx, windows and linux. 【🌟Star 15】

* [command](https://github.com/txgruppi/command) - Command pattern for Go with thread safe serial and parallel dispatcher. 【🌟Star 9】

* [copy-pasta](https://github.com/jutkko/copy-pasta) - Universal multi-workstation clipboard that uses S3 like backend for the storage. 【🌟Star 38】

* [ctop](https://github.com/bcicen/ctop) - [Top-like](http://ctop.sh) interface (e.g. htop) for container metrics. 【🌟Star 9353】

* [ctxutil](https://github.com/posener/ctxutil) - A collection of utility functions for contexts. 【🌟Star 11】

* [dbt](https://github.com/nikogura/dbt) - A framework for running self-updating signed binaries from a central, trusted repository. 【🌟Star 23】

* [Death](https://github.com/vrecan/death) - Managing go application shutdown with signals. 【🌟Star 148】

* [Deepcopier](https://github.com/ulule/deepcopier) - Simple struct copying for Go. 【🌟Star 234】

* [delve](https://github.com/derekparker/delve) - Go debugger. 【🌟Star 13139】

* [dlog](https://github.com/kirillDanshin/dlog) - Compile-time controlled logger to make your release smaller without removing debug calls. 【🌟Star 15】

* [ergo](https://github.com/cristianoliveira/ergo) - The management of multiple local services running over different ports made easy. 【🌟Star 351】

* [evaluator](https://github.com/nullne/evaluator) - Evaluate an expression dynamicly based on s-expression. It's simple and easy to extend. 【🌟Star 20】

* [filetype](https://github.com/h2non/filetype) - Small package to infer the file type checking the magic numbers signature. 【🌟Star 1027】

* [filler](https://github.com/yaronsumel/filler) - small utility to fill structs using "fill" tag. 【🌟Star 14】

* [filter](https://github.com/gookit/filter) - provide filtering, sanitizing, and conversion of Go data. 【🌟Star 21】

* [fzf](https://github.com/junegunn/fzf) - Command-line fuzzy finder written in Go. 【🌟Star 26396】

* [gaper](https://github.com/maxcnunes/gaper) - Builds and restarts a Go project when it crashes or some watched file changes. 【🌟Star 41】

* [generate](https://github.com/go-playground/generate) - runs go generate recursively on a specified path or environment variable and can filter by regex. 【🌟Star 21】

* [ghokin](https://github.com/antham/ghokin) - Parallelized formatter with no external dependencies for gherkin (cucumber, behat...). 【🌟Star 13】

* [git-time-metric](https://github.com/git-time-metric/gtm) - Simple, seamless, lightweight time tracking for Git. 【🌟Star 764】

* [go-astitodo](https://github.com/asticode/go-astitodo) - Parse TODOs in your GO code. 【🌟Star 46】

* [go-bind-plugin](https://github.com/wendigo/go-bind-plugin) - go:generate tool for wrapping symbols exported by golang plugins (1.8 only). 【🌟Star 164】

* [go-bsdiff](https://github.com/gabstv/go-bsdiff) - Pure Go bsdiff and bspatch libraries and CLI tools. 【🌟Star 90】

* [go-dry](https://github.com/ungerik/go-dry) - DRY (don't repeat yourself) package for Go. 【🌟Star 444】

* [go-funk](https://github.com/thoas/go-funk) - Modern Go utility library which provides helpers (map, find, contains, filter, chunk, reverse, ...). 【🌟Star 1533】

* [go-health](https://github.com/Talento90/go-health) - Health package simplifies the way you add health check to your services. 【🌟Star 70】

* [go-httpheader](https://github.com/mozillazg/go-httpheader) - Go library for encoding structs into Header fields. 【🌟Star 15】

* [go-problemdetails](https://github.com/mvmaasakkers/go-problemdetails) - Go package for working with Problem Details. 【🌟Star 5】

* [go-rate](https://github.com/beefsack/go-rate) - Timed rate limiter for Go. 【🌟Star 295】

* [go-sitemap-generator](https://github.com/ikeikeikeike/go-sitemap-generator) - XML Sitemap generator written in Go. 【🌟Star 114】

* [go-trigger](https://github.com/sadlil/go-trigger) - Go-lang global event triggerer, Register Events with an id and trigger the event from anywhere from your project. 【🌟Star 189】

* [goback](https://github.com/carlescere/goback) - Go simple exponential backoff package. 【🌟Star 42】

* [godaemon](https://github.com/VividCortex/godaemon) - Utility to write daemons. 【🌟Star 423】

* [godropbox](https://github.com/dropbox/godropbox) - Common libraries for writing Go services/applications from Dropbox. 【🌟Star 3821】

* [gohper](https://github.com/cosiner/gohper) - Various tools/modules help for development. 【🌟Star 248】

* [golarm](https://github.com/msempere/golarm) - Fire alarms with system events. 【🌟Star 37】

* [golog](https://github.com/mlimaloureiro/golog) - Easy and lightweight CLI tool to time track your tasks. 【🌟Star 47】

* [gopencils](https://github.com/bndr/gopencils) - Small and simple package to easily consume REST APIs. 【🌟Star 428】

* [goplaceholder](https://github.com/michiwend/goplaceholder) - a small golang lib to generate placeholder images. 【🌟Star 21】

* [goreadability](https://github.com/philipjkim/goreadability) - Webpage summary extractor using Facebook Open Graph and arc90's readability. 【🌟Star 43】

* [goreleaser](https://github.com/goreleaser/goreleaser) - Deliver Go binaries as fast and easily as possible. 【🌟Star 5014】

* [goreporter](https://github.com/wgliang/goreporter) - Golang tool that does static analysis, unit testing, code review and generate code quality report. 【🌟Star 2597】

* [goseaweedfs](https://github.com/linxGnu/goseaweedfs) - SeaweedFS client library with almost full features. 【🌟Star 43】

* [gostrutils](https://github.com/ik5/gostrutils) - Collections of string manipulation and conversion functions. 【🌟Star 22】

* [gotenv](https://github.com/subosito/gotenv) - Load environment variables from `.env` or any `io.Reader` in Go. 【🌟Star 162】

* [gpath](https://github.com/tenntenn/gpath) - Library to simplify access struct fields with Go's expression in reflection. 【🌟Star 32】

* [gubrak](https://github.com/novalagung/gubrak) - Golang utility library with syntactic sugar. It's like lodash, but for golang. 【🌟Star 198】

* [handy](https://github.com/miguelpragier/handy) - Many utilities and helpers like string handlers/formatters and validators. 【🌟Star 49】

* [htcat](https://github.com/htcat/htcat) - Parallel and Pipelined HTTP GET Utility. 【🌟Star 503】

* [hub](https://github.com/github/hub) - wrap git commands with additional functionality to interact with github from the terminal. 【🌟Star 18324】

* [hystrix-go](https://github.com/afex/hystrix-go) - Implements Hystrix patterns of programmer-defined fallbacks aka circuit breaker. 【🌟Star 2305】

* [immortal](https://github.com/immortal/immortal) - \*nix cross-platform (OS agnostic) supervisor. 【🌟Star 632】

* [intrinsic](https://github.com/mengzhuo/intrinsic) - Use x86 SIMD without writing any assembly code. 【🌟Star 41】

* [jump](https://github.com/gsamokovarov/jump) - Jump helps you navigate faster by learning your habits. 【🌟Star 764】

* [koazee](https://github.com/wesovilabs/koazee) - Library inspired in Lazy evaluation and functional programming that takes the hassle out of working with arrays. 【🌟Star 352】

* [limiters](https://github.com/mennanov/limiters) - Rate limiters for distributed applications in Golang with configurable back-ends and distributed locks. 【🌟Star 8】

* [lrserver](https://github.com/jaschaephraim/lrserver) - LiveReload server for Go. 【🌟Star 105】

* [mc](https://github.com/minio/mc) - Minio Client provides minimal tools to work with Amazon S3 compatible cloud storage and filesystems. 【🌟Star 1300】

* [mergo](https://github.com/imdario/mergo) - Helper to merge structs and maps in Golang. Useful for configuration default values, avoiding messy if-statements. 【🌟Star 1010】

* [mimemagic](https://github.com/zRedShift/mimemagic) - Pure Go ultra performant MIME sniffing library/utility. 【🌟Star 50】

* [mimesniffer](https://github.com/aofei/mimesniffer) - A MIME type sniffer for Go. 【🌟Star 11】

* [mimetype](https://github.com/gabriel-vasile/mimetype) - Package for MIME type detection based on magic numbers. 【🌟Star 186】

* [minify](https://github.com/tdewolff/minify) - Fast minifiers for HTML, CSS, JS, XML, JSON and SVG file formats. 【🌟Star 1975】

* [minquery](https://github.com/icza/minquery) - MongoDB / mgo.v2 query that supports efficient pagination (cursors to continue listing documents where we left off). 【🌟Star 52】

* [mmake](https://github.com/tj/mmake) - Modern Make. 【🌟Star 1472】

* [moldova](https://github.com/StabbyCutyou/moldova) - Utility for generating random data based on an input template. 【🌟Star 148】

* [mole](https://github.com/davrodpin/mole) - cli app to easily create ssh tunnels. 【🌟Star 1347】

* [mssqlx](https://github.com/linxGnu/mssqlx) - Database client library, proxy for any master slave, master master structures. Lightweight and auto balancing in mind. 【🌟Star 67】

* [multitick](https://github.com/VividCortex/multitick) - Multiplexor for aligned tickers. 【🌟Star 61】

* [myhttp](https://github.com/inancgumus/myhttp) - Simple API to make HTTP GET requests with timeout support. 【🌟Star 33】

* [okrun](https://github.com/xta/okrun) - go run error steamroller. 【🌟Star 14】

* [olaf](https://github.com/btnguyen2k/olaf) - Twitter Snowflake implemented in Go. 【🌟Star 1】

* [onecache](https://github.com/adelowo/onecache) - Caching library with support for multiple backend stores (Redis, Memcached, filesystem etc). 【🌟Star 106】

* [panicparse](https://github.com/maruel/panicparse) - Groups similar goroutines and colorizes stack dump. 【🌟Star 2187】

* [peco](https://github.com/peco/peco) - Simplistic interactive filtering tool. 【🌟Star 5704】

* [pgo](https://github.com/arthurkushman/pgo) - Convenient functions for PHP community. 【🌟Star 34】

* [pm](https://github.com/VividCortex/pm) - Process (i.e. goroutine) manager with an HTTP API. 【🌟Star 75】

* [ptr](https://github.com/gotidy/ptr) - Package that provide functions for simplified creation of pointers from constants of basic types. 【🌟Star 3】

* [rclient](https://github.com/zpatrick/rclient) - Readable, flexible, simple-to-use client for REST APIs. 【🌟Star 31】

* [realize](https://github.com/tockins/realize) - Go build system with file watchers and live reload. Run, build and watch file changes with custom paths. 【🌟Star 3461】

* [repeat](https://github.com/ssgreg/repeat) - Go implementation of different backoff strategies useful for retrying operations and heartbeating. 【🌟Star 61】

* [request](https://github.com/mozillazg/request) - Go HTTP Requests for Humans™. 【🌟Star 370】

* [rerate](https://github.com/abo/rerate) - Redis-based rate counter and rate limiter for Go. 【🌟Star 14】

* [rerun](https://github.com/ivpusic/rerun) - Recompiling and rerunning go apps when source changes. 【🌟Star 155】

* [rest-go](https://github.com/edermanoel94/rest-go) - A package that provide many helpful methods for working with rest api. 【🌟Star 12】

* [retry](https://github.com/kamilsk/retry) - The most advanced functional mechanism to perform actions repetitively until successful. 【🌟Star 192】

* [retry](https://github.com/percolate/retry) - A simple but highly configurable retry package for Go. 【🌟Star 5】

* [retry](https://github.com/thedevsaddam/retry) - Simple and easy retry mechanism package for Go. 【🌟Star 34】

* [retry](https://github.com/shafreeck/retry) - A pretty simple library to ensure your work to be done. 【🌟Star 10】

* [retry-go](https://github.com/rafaeljesus/retry-go) - Retrying made simple and easy for golang. 【🌟Star 31】

* [robustly](https://github.com/VividCortex/robustly) - Runs functions resiliently, catching and restarting panics. 【🌟Star 140】

* [scan](https://github.com/blockloop/scan) - Scan golang `sql.Rows` directly to structs, slices, or primitive types. 【🌟Star 22】

* [serve](https://github.com/syntaqx/serve) - A static http server anywhere you need. 【🌟Star 203】

* [shutdown](https://github.com/ztrue/shutdown) - App shutdown hooks for `os.Signal` handling. 【🌟Star 8】

* [silk](https://github.com/chrispassas/silk) - Read silk netflow files. 【🌟Star 4】

* [slice](https://github.com/psampaz/slice) - Type-safe functions for common Go slice operations. 【🌟Star 16】

* [sliceconv](https://github.com/Henry-Sarabia/sliceconv) - Slice conversion between primitive types. 【🌟Star 4】

* [slicer](https://github.com/leaanthony/slicer) - Makes working with slices easier. 【🌟Star 12】

* [spinner](https://github.com/briandowns/spinner) - Go package to easily provide a terminal spinner with options. 【🌟Star 896】

* [sqlx](https://github.com/jmoiron/sqlx) - provides a set of extensions on top of the excellent built-in database/sql package. 【🌟Star 7653】

* [sslice](https://github.com/yaa110/sslice) - Create a slice which is always sorted. 【🌟Star 0】

* [Storm](https://github.com/asdine/storm) - Simple and powerful toolkit for BoltDB. 【🌟Star 1470】

* [structs](https://github.com/PumpkinSeed/structs) - Implement simple functions to manipulate structs. 【🌟Star 14】

* [Task](https://github.com/go-task/task) - simple "Make" alternative. 【🌟Star 2189】

* [tome](https://github.com/cyruzin/tome) - Tome was designed to paginate simple RESTful APIs. 【🌟Star 9】

* [toolbox](https://github.com/viant/toolbox) - Slice, map, multimap, struct, function, data conversion utilities. Service router, macro evaluator, tokenizer. 【🌟Star 115】

* [ugo](https://github.com/alxrm/ugo) - ugo is slice toolbox with concise syntax for Go. 【🌟Star 22】

* [UNIS](https://github.com/esemplastic/unis) - Common Architecture™ for String Utilities in Go. 【🌟Star 69】

* [usql](https://github.com/knq/usql) - usql is a universal command-line interface for SQL databases. 【🌟Star 5550】

* [util](https://github.com/shomali11/util) - Collection of useful utility functions. (strings, concurrency, manipulations, ...). 【🌟Star 149】

* [wuzz](https://github.com/asciimoo/wuzz) - Interactive cli tool for HTTP inspection. 【🌟Star 8509】

* [xferspdy](https://github.com/monmohan/xferspdy) - Xferspdy provides binary diff and patch library in golang. 【🌟Star 71】


## UUID

*Libraries for working with UUIDs.*

* [goid](https://github.com/jakehl/goid) - Generate and Parse RFC4122 compliant V4 UUIDs. 【🌟Star 26】

* [nanoid](https://github.com/aidarkhanov/nanoid) - A tiny and efficient Go unique string ID generator. 【🌟Star 16】

* [sno](https://github.com/muyo/sno) - Compact, sortable and fast unique IDs with embedded metadata. 【🌟Star 23】

* [ulid](https://github.com/oklog/ulid) - Go implementation of ULID (Universally Unique Lexicographically Sortable Identifier). 【🌟Star 1795】

* [uniq](https://gitlab.com/skilstak/code/go/uniq) - No hassle safe, fast unique identifiers with commands.
* [uuid](https://github.com/agext/uuid) - Generate, encode, and decode UUIDs v1 with fast or cryptographic-quality random node identifier. 【🌟Star 10】

* [uuid](https://github.com/gofrs/uuid) - Implementation of Universally Unique Identifier (UUID). Supports both creation and parsing of UUIDs. Actively maintained fork of satori uuid. 【🌟Star 642】

* [wuid](https://github.com/edwingeng/wuid) - An extremely fast unique number generator, 10-135 times faster than UUID. 【🌟Star 323】


## Validation

*Libraries for validation.*

* [checkdigit](https://github.com/osamingo/checkdigit) - Provide check digit algorithms (Luhn, Verhoeff, Damm) and calculators (ISBN, EAN, JAN, UPC, etc.). 【🌟Star 48】

* [govalidator](https://github.com/asaskevich/govalidator) - Validators and sanitizers for strings, numerics, slices and structs. 【🌟Star 3950】

* [govalidator](https://github.com/thedevsaddam/govalidator) - Validate Golang request data with simple rules. Highly inspired by Laravel's request validation. 【🌟Star 813】

* [jio](https://github.com/faceair/jio) - jio is a json schema validator similar to [joi](https://github.com/hapijs/joi). 【🌟Star 30】

* [ozzo-validation](https://github.com/go-ozzo/ozzo-validation) - Supports validation of various data types (structs, strings, maps, slices, etc.) with configurable and extensible validation rules specified in usual code constructs instead of struct tags. 【🌟Star 1233】

* [terraform-validator](https://github.com/thazelart/terraform-validator) - A norms and conventions validator for Terraform. 【🌟Star 25】

* [validate](https://github.com/gookit/validate) - Go package for data validation and filtering. support validate Map, Struct, Request(Form, JSON, url.Values, Uploaded Files) data and more features. 【🌟Star 194】

* [validate](https://github.com/gobuffalo/validate) - This package provides a framework for writing validations for Go applications. 【🌟Star 26】

* [validator](https://github.com/go-playground/validator) - Go Struct and Field validation, including Cross Field, Cross Struct, Map, Slice and Array diving. 【🌟Star 4588】


## Version Control

*Libraries for version control.*

* [gh](https://github.com/rjeczalik/gh) - Scriptable server and net/http middleware for GitHub Webhooks. 【🌟Star 72】

* [git2go](https://github.com/libgit2/git2go) - Go bindings for libgit2. 【🌟Star 1425】

* [go-git](https://github.com/src-d/go-git) - highly extensible Git implementation in pure Go. 【🌟Star 4840】

* [go-vcs](https://github.com/sourcegraph/go-vcs) - manipulate and inspect VCS repositories in Go. 【🌟Star 72】

* [hercules](https://github.com/src-d/hercules) - gaining advanced insights from Git repository history. 【🌟Star 813】

* [hgo](https://github.com/beyang/hgo) - Hgo is a collection of Go packages providing read-access to local Mercurial repositories. 【🌟Star 12】


## Video

*Libraries for manipulating video.*

* [gmf](https://github.com/3d0c/gmf) - Go bindings for FFmpeg av\* libraries. 【🌟Star 577】

* [go-astisub](https://github.com/asticode/go-astisub) - Manipulate subtitles in GO (.srt, .stl, .ttml, .webvtt, .ssa/.ass, teletext, .smi, etc.). 【🌟Star 219】

* [go-astits](https://github.com/asticode/go-astits) - Parse and demux MPEG Transport Streams (.ts) natively in GO. 【🌟Star 285】

* [go-m3u8](https://github.com/quangngotan95/go-m3u8) - Parser and generator library for Apple m3u8 playlists. 【🌟Star 44】

* [goav](https://github.com/giorgisio/goav) - Comphrensive Go bindings for FFmpeg. 【🌟Star 982】

* [gst](https://github.com/ziutek/gst) - Go bindings for GStreamer. 【🌟Star 155】

* [libgosubs](https://github.com/wargarblgarbl/libgosubs) - Subtitle format support for go. Supports .srt, .ttml, and .ass. 【🌟Star 12】

* [libvlc-go](https://github.com/adrg/libvlc-go) - Go bindings for libvlc 2.X/3.X/4.X (used by the VLC media player). 【🌟Star 82】

* [m3u8](https://github.com/grafov/m3u8) - Parser and generator library of M3U8 playlists for Apple HLS. 【🌟Star 651】

* [v4l](https://github.com/korandiz/v4l) - Video capture library for Linux, written in Go. 【🌟Star 36】


## Web Frameworks

*Full stack web frameworks.*

* [aah](https://aahframework.org) - Scalable, performant, rapid development Web framework for Go.
* [Aero](https://github.com/aerogo/aero) - High-performance web framework for Go, reaches top scores in Lighthouse. 【🌟Star 227】

* [Air](https://github.com/aofei/air) - An ideally refined web framework for Go. 【🌟Star 363】

* [Banjo](https://github.com/nsheremet/banjo) - Very simple and fast web framework for Go. 【🌟Star 11】

* [Beego](https://github.com/astaxie/beego) - beego is an open-source, high-performance web framework for the Go programming language. 【🌟Star 23042】

* [Buffalo](http://gobuffalo.io) - Bringing the productivity of Rails to Go!
* [Echo](https://github.com/labstack/echo) - High performance, minimalist Go web framework. 【🌟Star 16231】

* [Fireball](https://github.com/zpatrick/fireball) - More "natural" feeling web framework. 【🌟Star 50】

* [Flamingo](https://github.com/i-love-flamingo/flamingo) - Framework for pluggable web projects. Including a concept for modules and offering features for DI, Configareas, i18n, template engines, graphql, observability, security, events, routing & reverse routing etc. 【🌟Star 77】

* [Flamingo Commerce](https://github.com/i-love-flamingo/flamingo-commerce) - Providing e-commerce features using clean architecture like DDD and ports and adapters, that you can use to build flexible e-commerce applications. 【🌟Star 41】

* [Gin](https://github.com/gin-gonic/gin) - Gin is a web framework written in Go! It features a martini-like API with much better performance, up to 40 times faster. If you need performance and good productivity. 【🌟Star 34763】

* [Ginrpc](https://github.com/xxjwxc/ginrpc) - Gin parameter automatic binding tool,gin rpc tools. 【🌟Star 49】

* [Gizmo](https://github.com/NYTimes/gizmo) - Microservice toolkit used by the New York Times. 【🌟Star 3021】

* [go-json-rest](https://github.com/ant0ine/go-json-rest) - Quick and easy way to setup a RESTful JSON API. 【🌟Star 3386】

* [go-rest](https://github.com/ungerik/go-rest) - Small and evil REST framework for Go. 【🌟Star 116】

* [Goa](https://github.com/goadesign/goa) - Goa provides a holistic approach for developing remote APIs and microservices in Go. 【🌟Star 3683】

* [goa](https://github.com/goa-go/goa) - goa is just like koajs for golang, it is a flexible, light, high-performance and extensible web framework based on middleware. 【🌟Star 27】

* [Golax](https://github.com/fulldump/golax) - A non Sinatra fast HTTP framework with support for Google custom methods, deep interceptors, recursion and more. 【🌟Star 71】

* [Golf](https://github.com/dinever/golf) - Golf is a fast, simple and lightweight micro-web framework for Go. It comes with powerful features and has no dependencies other than the Go Standard Library. 【🌟Star 239】

* [Gondola](https://github.com/rainycape/gondola) - The web framework for writing faster sites, faster. 【🌟Star 314】

* [gongular](https://github.com/mustafaakin/gongular) - Fast Go web framework with input mapping/validation and (DI) Dependency Injection. 【🌟Star 421】

* [hiboot](https://github.com/hidevopsio/hiboot) - hiboot is a high performance web application framework with auto configuration and dependency injection support. 【🌟Star 110】

* [Macaron](https://github.com/go-macaron/macaron) - Macaron is a high productive and modular design web framework in Go. 【🌟Star 2925】

* [mango](https://github.com/paulbellamy/mango) - Mango is a modular web-application framework for Go, inspired by Rack, and PEP333. 【🌟Star 343】

* [Microservice](https://github.com/claygod/microservice) - The framework for the creation of microservices, written in Golang. 【🌟Star 69】

* [neo](https://github.com/ivpusic/neo) - Neo is minimal and fast Go Web Framework with extremely simple API. 【🌟Star 402】

* [patron](https://github.com/beatlabs/patron) - Patron is a microservice framework following best cloud practices with a focus on productivity. 【🌟Star 46】

* [Resoursea](https://github.com/resoursea/api) - REST framework for quickly writing resource based services. 【🌟Star 30】

* [REST Layer](http://rest-layer.io) - Framework to build REST/GraphQL API on top of databases with mostly configuration over code.
* [Revel](https://github.com/revel/revel) - High-productivity web framework for the Go language. 【🌟Star 11525】

* [rex](https://github.com/goanywhere/rex) - Rex is a library for modular development built upon gorilla/mux, fully compatible with `net/http`. 【🌟Star 29】

* [rux](https://github.com/gookit/rux) - Simple and fast web framework for build golang HTTP applications. 【🌟Star 19】

* [tango](https://github.com/lunny/tango) - Micro & pluggable web framework for Go. 【🌟Star 832】

* [tigertonic](https://github.com/rcrowley/go-tigertonic) - Go framework for building JSON web services inspired by Dropwizard. 【🌟Star 999】

* [uAdmin](https://github.com/uadmin/uadmin) - Fully featured web framework for Golang, inspired by Django. 【🌟Star 72】

* [utron](https://github.com/gernest/utron) - Lightweight MVC framework for Go(Golang). 【🌟Star 2153】

* [vox](https://github.com/aisk/vox) - A golang web framework for humans, inspired by Koa heavily. 【🌟Star 47】

* [WebGo](https://github.com/bnkamalesh/webgo) - A micro-framework to build web apps; with handler chaining, middleware and context injection. With standard library compliant HTTP handlers(i.e. http.HandlerFunc). 【🌟Star 84】

* [YARF](https://github.com/yarf-framework/yarf) - Fast micro-framework designed to build REST APIs and web services in a fast and simple way. 【🌟Star 54】


### Middlewares

#### Actual middlewares

* [client-timing](https://github.com/posener/client-timing) - An HTTP client for Server-Timing header. 【🌟Star 16】

* [CORS](https://github.com/rs/cors) - Easily add CORS capabilities to your API. 【🌟Star 1358】

* [formjson](https://github.com/rs/formjson) - Transparently handle JSON input as a standard form POST. 【🌟Star 34】

* [go-server-timing](https://github.com/mitchellh/go-server-timing) - Add/parse Server-Timing header. 【🌟Star 767】

* [Limiter](https://github.com/ulule/limiter) - Dead simple rate limit middleware for Go. 【🌟Star 860】

* [ln-paywall](https://github.com/philippgille/ln-paywall) - Go middleware for monetizing APIs on a per-request basis with the Lightning Network (Bitcoin). 【🌟Star 98】

* [Tollbooth](https://github.com/didip/tollbooth) - Rate limit HTTP request handler. 【🌟Star 1447】

* [XFF](https://github.com/sebest/xff) - Handle `X-Forwarded-For` header and friends. 【🌟Star 72】


#### Libraries for creating HTTP middlewares

* [alice](https://github.com/justinas/alice) - Painless middleware chaining for Go. 【🌟Star 1937】

* [catena](https://github.com/codemodus/catena) - http.Handler wrapper catenation (same API as "chain"). 【🌟Star 7】

* [chain](https://github.com/codemodus/chain) - Handler wrapper chaining with scoped data (net/context-based "middleware"). 【🌟Star 64】

* [go-wrap](https://github.com/go-on/wrap) - Small middlewares package for net/http. 【🌟Star 59】

* [gores](https://github.com/alioygur/gores) - Go package that handles HTML, JSON, XML and etc. responses. Useful for RESTful APIs. 【🌟Star 88】

* [interpose](https://github.com/carbocation/interpose) - Minimalist net/http middleware for golang. 【🌟Star 289】

* [muxchain](https://github.com/stephens2424/muxchain) - Lightweight middleware for net/http. 【🌟Star 209】

* [negroni](https://github.com/urfave/negroni) - Idiomatic HTTP middleware for Golang. 【🌟Star 6512】

* [render](https://github.com/unrolled/render) - Go package for easily rendering JSON, XML, and HTML template responses. 【🌟Star 1328】

* [renderer](https://github.com/thedevsaddam/renderer) - Simple, lightweight and faster response (JSON, JSONP, XML, YAML, HTML, File) rendering package for Go. 【🌟Star 179】

* [rye](https://github.com/InVisionApp/rye) - Tiny Go middleware library (with canned Middlewares) that supports JWT, CORS, Statsd, and Go 1.7 context. 【🌟Star 93】

* [stats](https://github.com/thoas/stats) - Go middleware that stores various information about your web application. 【🌟Star 550】


### Routers

* [alien](https://github.com/gernest/alien) - Lightweight and fast http router from outer space. 【🌟Star 109】

* [bellt](https://github.com/GuilhermeCaruso/bellt) - A simple Go HTTP router. 【🌟Star 40】

* [Bone](https://github.com/go-zoo/bone) - Lightning Fast HTTP Multiplexer. 【🌟Star 1245】

* [Bxog](https://github.com/claygod/Bxog) - Simple and fast HTTP router for Go. It works with routes of varying difficulty, length and nesting. And he knows how to create a URL from the received parameters. 【🌟Star 92】

* [chi](https://github.com/go-chi/chi) - Small, fast and expressive HTTP router built on net/context. 【🌟Star 6853】

* [fasthttprouter](https://github.com/buaazp/fasthttprouter) - High performance router forked from `httprouter`. The first router fit for `fasthttp`. 【🌟Star 810】

* [FastRouter](https://github.com/razonyang/fastrouter) - a fast, flexible HTTP router written in Go. 【🌟Star 19】

* [gocraft/web](https://github.com/gocraft/web) - Mux and middleware package in Go. 【🌟Star 1407】

* [Goji](https://github.com/goji/goji) - Goji is a minimalistic and flexible HTTP request multiplexer with support for `net/context`. 【🌟Star 793】

* [goroute](https://github.com/goroute/route) - Simple yet powerful HTTP request multiplexer. 【🌟Star 6】

* [GoRouter](https://github.com/vardius/gorouter) - GoRouter is a Server/API micro framwework, HTTP request router, multiplexer, mux that provides request router with middleware supporting `net/context`. 【🌟Star 58】

* [gowww/router](https://github.com/gowww/router) - Lightning fast HTTP router fully compatible with the net/http.Handler interface. 【🌟Star 159】

* [httprouter](https://github.com/julienschmidt/httprouter) - High performance router. Use this and the standard http handlers to form a very high performance web framework. 【🌟Star 10659】

* [httptreemux](https://github.com/dimfeld/httptreemux) - High-speed, flexible tree-based HTTP router for Go. Inspiration from httprouter. 【🌟Star 404】

* [lars](https://github.com/go-playground/lars) - Is a lightweight, fast and extensible zero allocation HTTP router for Go used to create customizable frameworks. 【🌟Star 380】

* [mux](https://github.com/gorilla/mux) - Powerful URL router and dispatcher for golang. 【🌟Star 10985】

* [ozzo-routing](https://github.com/go-ozzo/ozzo-routing) - An extremely fast Go (golang) HTTP router that supports regular expression route matching. Comes with full support for building RESTful APIs. 【🌟Star 369】

* [pure](https://github.com/go-playground/pure) - Is a lightweight HTTP router that sticks to the std "net/http" implementation. 【🌟Star 91】

* [Siesta](https://github.com/VividCortex/siesta) - Composable framework to write middleware and handlers. 【🌟Star 352】

* [vestigo](https://github.com/husobee/vestigo) - Performant, stand-alone, HTTP compliant URL Router for go web applications. 【🌟Star 258】

* [violetear](https://github.com/nbari/violetear) - Go HTTP router. 【🌟Star 96】

* [xmux](https://github.com/rs/xmux) - High performance muxer based on `httprouter` with `net/context` support. 【🌟Star 87】

* [xujiajun/gorouter](https://github.com/xujiajun/gorouter) - A simple and fast HTTP router for Go. 【🌟Star 473】


## Windows

* [d3d9](https://github.com/gonutz/d3d9) - Go bindings for Direct3D9. 【🌟Star 96】

* [go-ole](https://github.com/go-ole/go-ole) - Win32 OLE implementation for golang. 【🌟Star 597】

* [gosddl](https://github.com/MonaxGT/gosddl) - Converter from SDDL-string to user-friendly JSON. SDDL consist of four part: Owner, Primary Group, DACL, SACL. 【🌟Star 1】


## XML

*Libraries and tools for manipulating XML.*

* [XML-Comp](https://github.com/xml-comp/xml-comp) - Simple command line XML comparer that generates diffs of folders, files and tags. 【🌟Star 16】

* [xml2map](https://github.com/sbabiv/xml2map) - XML to MAP converter written Golang. 【🌟Star 19】

* [xmlwriter](https://github.com/shabbyrobe/xmlwriter) - Procedural XML generation API based on libxml2's xmlwriter module. 【🌟Star 8】

* [xpath](https://github.com/antchfx/xpath) - XPath package for Go. 【🌟Star 213】

* [xquery](https://github.com/antchfx/xquery) - XQuery lets you extract data from HTML/XML documents using XPath expression. 【🌟Star 153】

* [zek](https://github.com/miku/zek) - Generate a Go struct from XML. 【🌟Star 316】


# Tools

*Go software and plugins.*

## Code Analysis

* [apicompat](https://github.com/bradleyfalzon/apicompat) - Checks recent changes to a Go project for backwards incompatible changes. 【🌟Star 170】

* [dupl](https://github.com/mibk/dupl) - Tool for code clone detection. 【🌟Star 186】

* [errcheck](https://github.com/kisielk/errcheck) - Errcheck is a program for checking for unchecked errors in Go programs. 【🌟Star 1385】

* [gcvis](https://github.com/davecheney/gcvis) - Visualise Go program GC trace data in real time. 【🌟Star 953】

* [go-checkstyle](https://github.com/qiniu/checkstyle) - checkstyle is a style check tool like java checkstyle. This tool inspired by java checkstyle, golint. The style referred to some points in Go Code Review Comments. 【🌟Star 103】

* [go-cleanarch](https://github.com/roblaszczak/go-cleanarch) - go-cleanarch was created to validate Clean Architecture rules, like a The Dependency Rule and interaction between packages in your Go projects. 【🌟Star 302】

* [go-critic](https://github.com/go-critic/go-critic) - source code linter that brings checks that are currently not implemented in other linters. 【🌟Star 654】

* [go-mod-outdated](https://github.com/psampaz/go-mod-outdated) - An easy way to find outdated dependencies of your Go projects. 【🌟Star 252】

* [go-outdated](https://github.com/firstrow/go-outdated) - Console application that displays outdated packages. 【🌟Star 45】

* [goast-viewer](https://github.com/yuroyoro/goast-viewer) - Web based Golang AST visualizer. 【🌟Star 416】

* [GoCover.io](http://gocover.io/) - GoCover.io offers the code coverage of any golang package as a service.
* [goimports](https://godoc.org/golang.org/x/tools/cmd/goimports) - Tool to fix (add, remove) your Go imports automatically.
* [GolangCI](https://golangci.com/) - GolangCI is an automated Golang code review service for GitHub pull requests. Service is open source and it's free for open source projects.
* [golines](https://github.com/segmentio/golines) - Formatter that automatically shortens long lines in Go code. 【🌟Star 32】

* [GoLint](https://github.com/golang/lint) - Golint is a linter for Go source code. 【🌟Star 3342】

* [Golint online](http://go-lint.appspot.com/) - Lints online Go source files on GitHub, Bitbucket and Google Project Hosting using the golint package.
* [GoPlantUML](https://github.com/jfeliu007/goplantuml) - Library and CLI that generates text plantump class diagram containing information about structures and interfaces with the relationship among them. 【🌟Star 85】

* [goreturns](https://sourcegraph.com/github.com/sqs/goreturns) - Adds zero-value return statements to match the func return types.
* [gosimple](https://github.com/dominikh/go-tools/tree/master/cmd/gosimple) - gosimple is a linter for Go source code that specialises on simplifying code.
* [gostatus](https://github.com/shurcooL/gostatus) - Command line tool, shows the status of repositories that contain Go packages. 【🌟Star 242】

* [lint](https://github.com/surullabs/lint) - Run linters as part of go test. 【🌟Star 64】

* [php-parser](https://github.com/z7zmey/php-parser) - A Parser for PHP written in Go. 【🌟Star 689】

* [staticcheck](https://github.com/dominikh/go-tools/tree/master/cmd/staticcheck) - staticcheck is `go vet` on steroids, applying a ton of static analysis checks you might be used to from tools like ReSharper for C#.
* [tarp](https://github.com/verygoodsoftwarenotvirus/tarp) - tarp finds functions and methods without direct unit tests in Go source code. 【🌟Star 14】

* [tickgit](https://github.com/augmentable-dev/tickgit) - CLI and go package for surfacing code comment TODOs (in any language) and applying a `git blame`to identify the author. 【🌟Star 103】

* [unconvert](https://github.com/mdempsky/unconvert) - Remove unnecessary type conversions from Go source. 【🌟Star 276】

* [unused](https://github.com/dominikh/go-tools/tree/master/cmd/unused) - unused checks Go code for unused constants, variables, functions and types.
* [validate](https://github.com/mccoyst/validate) - Automatically validates struct fields with tags. 【🌟Star 62】


## Editor Plugins

* [Go plugin for JetBrains IDEs](https://plugins.jetbrains.com/plugin/9568-go) - Go plugin for JetBrains IDEs.
* [go-language-server](https://github.com/theia-ide/go-language-server) - A wrapper to turn the VSCode go extension into a language server supporting the language-server-protocol. 【🌟Star 33】

* [go-mode](https://github.com/dominikh/go-mode.el) - Go mode for GNU/Emacs. 【🌟Star 1023】

* [go-plus](https://github.com/joefitzgerald/go-plus) - Go (Golang) Package For Atom That Adds Autocomplete, Formatting, Syntax Checking, Linting and Vetting. 【🌟Star 1497】

* [gocode](https://github.com/nsf/gocode) - Autocompletion daemon for the Go programming language. 【🌟Star 4820】

* [goprofiling](https://marketplace.visualstudio.com/items?itemName=MaxMedia.go-prof) - This extension adds benchmark profiling support for the Go language to VS Code.
* [GoSublime](https://github.com/DisposaBoy/GoSublime) - Golang plugin collection for the text editor SublimeText 3 providing code completion and other IDE-like features. 【🌟Star 3304】

* [gounit-vim](https://github.com/hexdigest/gounit-vim) - Vim plugin for generating Go tests based on the function's or method's signature. 【🌟Star 17】

* [theia-go-extension](https://github.com/theia-ide/theia-go-extension) - Go language support for the Theia IDE. 【🌟Star 13】

* [vim-compiler-go](https://github.com/rjohnsondev/vim-compiler-go) - Vim plugin to highlight syntax errors on save. 【🌟Star 81】

* [vim-go](https://github.com/fatih/vim-go) - Go development plugin for Vim. 【🌟Star 11517】

* [vscode-go](https://github.com/Microsoft/vscode-go) - Extension for Visual Studio Code (VS Code) which provides support for the Go language. 【🌟Star 5585】

* [Watch](https://github.com/eaburns/Watch) - Runs a command in an acme win on file changes. 【🌟Star 171】


## Go Generate Tools

* [generic](https://github.com/usk81/generic) - flexible data type for Go. 【🌟Star 32】

* [genny](https://github.com/cheekybits/genny) - Elegant generics for Go. 【🌟Star 1101】

* [gocontracts](https://github.com/Parquery/gocontracts) - brings design-by-contract to Go by synchronizing the code with the documentation. 【🌟Star 55】

* [gonerics](http://github.com/bouk/gonerics) - Idiomatic Generics in Go.
* [gotests](https://github.com/cweill/gotests) - Generate Go tests from your source code. 【🌟Star 2483】

* [gounit](https://github.com/hexdigest/gounit) - Generate Go tests using your own templates. 【🌟Star 35】

* [hasgo](https://github.com/DylanMeeus/hasgo) - Generate Haskell inspired functions for your slices. 【🌟Star 31】

* [re2dfa](https://github.com/opennota/re2dfa) - Transform regular expressions into finite state machines and output Go source code. 【🌟Star 176】

* [TOML-to-Go](https://xuri.me/toml-to-go) - Translates TOML into a Go type in the browser instantly.

## Go Tools

* [colorgo](https://github.com/songgao/colorgo) - Wrapper around `go` command for colorized `go build` output. 【🌟Star 101】

* [depth](https://github.com/KyleBanks/depth) - Visualize dependency trees of any package by analyzing imports. 【🌟Star 433】

* [gb](https://getgb.io/) - An easy to use project based build tool for the Go programming language.
* [generator-go-lang](https://github.com/axelspringer/generator-go-lang) - A [Yeoman](http://yeoman.io) generator to get new Go projects started. 【🌟Star 17】

* [gilbert](https://go-gilbert.github.io) - Build system and task runner for Go projects.
* [go-callvis](https://github.com/TrueFurby/go-callvis) - Visualize call graph of your Go program using dot format. 【🌟Star 2297】

* [go-james](https://github.com/pieterclaerhout/go-james) - Go project skeleton creator, builds and tests your projects without the manual setup. 【🌟Star 8】

* [go-pkg-complete](https://github.com/skelterjohn/go-pkg-complete) - Bash completion for go and wgo. 【🌟Star 37】

* [go-swagger](https://github.com/go-swagger/go-swagger) - Swagger 2.0 implementation for go. Swagger is a simple yet powerful representation of your RESTful API. 【🌟Star 4706】

* [godbg](https://github.com/tylerwince/godbg) - Implementation of Rusts `dbg!` macro for quick and easy debugging during development. 【🌟Star 163】

* [gothanks](https://github.com/psampaz/gothanks) - GoThanks automatically stars your go.mod github dependencies, sending this way some love to their maintainers. 【🌟Star 84】

* [OctoLinker](https://github.com/OctoLinker/browser-extension) - Navigate through go files efficiently with the OctoLinker browser extension for GitHub. 【🌟Star 4068】

* [richgo](https://github.com/kyoh86/richgo) - Enrich `go test` outputs with text decorations. 【🌟Star 427】

* [rts](https://github.com/galeone/rts) - RTS: response to struct. Generates Go structs from server responses. 【🌟Star 194】


## Software Packages

*Software written in Go.*

### DevOps Tools

* [aptly](https://github.com/smira/aptly) - aptly is a Debian repository management tool. 【🌟Star 1】

* [aurora](https://github.com/xuri/aurora) - Cross-platform web-based Beanstalkd queue server console. 【🌟Star 437】

* [awsenv](https://github.com/soniah/awsenv) - Small binary that loads Amazon (AWS) environment variables for a profile. 【🌟Star 22】

* [Blast](https://github.com/dave/blast) - A simple tool for API load testing and batch jobs. 【🌟Star 174】

* [bombardier](https://github.com/codesenberg/bombardier) - Fast cross-platform HTTP benchmarking tool. 【🌟Star 1937】

* [bosun](https://github.com/bosun-monitor/bosun) - Time Series Alerting Framework. 【🌟Star 2925】

* [DepCharge](https://github.com/centerorbit/depcharge) - Helps orchestrating the execution of commands across the many dependencies in larger projects. 【🌟Star 9】

* [Dockerfile-Generator](https://github.com/ozankasikci/dockerfile-generator) - A go library and an executable that produces valid Dockerfiles using various input channels. 【🌟Star 61】

* [dogo](https://github.com/liudng/dogo) - Monitoring changes in the source file and automatically compile and run (restart). 【🌟Star 222】

* [drone-jenkins](https://github.com/appleboy/drone-jenkins) - Trigger downstream Jenkins jobs using a binary, docker or Drone CI. 【🌟Star 26】

* [drone-scp](https://github.com/appleboy/drone-scp) - Copy files and artifacts via SSH using a binary, docker or Drone CI. 【🌟Star 66】

* [Dropship](https://github.com/chrismckenzie/dropship) - Tool for deploying code via cdn. 【🌟Star 47】

* [easyssh-proxy](https://github.com/appleboy/easyssh-proxy) - Golang package for easy remote execution through SSH and SCP downloading via `ProxyCommand`. 【🌟Star 119】

* [fac](https://github.com/mkchoi212/fac) - Command-line user interface to fix git merge conflicts. 【🌟Star 1637】

* [gaia](https://github.com/gaia-pipeline/gaia) - Build powerful pipelines in any programming language. 【🌟Star 3960】

* [Gitea](https://github.com/go-gitea/gitea) - Fork of Gogs, entirely community driven. 【🌟Star 17867】

* [gitea-github-migrator](https://git.jonasfranz.software/JonasFranzDEV/gitea-github-migrator) - Migrate all your GitHub repositories, issues, milestones and labels to your Gitea instance.
* [go-furnace](https://github.com/go-furnace/go-furnace) - Hosting solution written in Go. Deploy your Application with ease on AWS, GCP or DigitalOcean. 【🌟Star 73】

* [go-selfupdate](https://github.com/sanbornm/go-selfupdate) - Enable your Go applications to self update. 【🌟Star 704】

* [gobrew](https://github.com/cryptojuice/gobrew) - gobrew lets you easily switch between multiple versions of go. 【🌟Star 176】

* [godbg](https://github.com/sirnewton01/godbg) - Web-based gdb front-end application. 【🌟Star 219】

* [Gogs](https://gogs.io/) - A Self Hosted Git Service in the Go Programming Language.
* [gonative](https://github.com/inconshreveable/gonative) - Tool which creates a build of Go that can cross compile to all platforms while still using the Cgo-enabled versions of the stdlib packages. 【🌟Star 314】

* [govvv](https://github.com/ahmetalpbalkan/govvv) - “go build” wrapper to easily add version information into Go binaries. 【🌟Star 421】

* [gox](https://github.com/mitchellh/gox) - Dead simple, no frills Go cross compile tool. 【🌟Star 3581】

* [goxc](https://github.com/laher/goxc) - build tool for Go, with a focus on cross-compiling and packaging. 【🌟Star 1641】

* [grapes](https://github.com/yaronsumel/grapes) - Lightweight tool designed to distribute commands over ssh with ease. 【🌟Star 144】

* [GVM](https://github.com/moovweb/gvm) - GVM provides an interface to manage Go versions. 【🌟Star 4902】

* [Hey](https://github.com/rakyll/hey) - Hey is a tiny program that sends some load to a web application. 【🌟Star 7389】

* [jcli](https://github.com/jenkins-zh/jenkins-cli) - Jenkins CLI allows you manage your Jenkins as an easy way. 【🌟Star 115】

* [kala](https://github.com/ajvb/kala) - Simplistic, modern, and performant job scheduler. 【🌟Star 1394】

* [kcli](https://github.com/cswank/kcli) - Command line tool for inspecting kafka topics/partitions/messages. 【🌟Star 102】

* [kubernetes](https://github.com/kubernetes/kubernetes) - Container Cluster Manager from Google. 【🌟Star 62365】

* [lstags](https://github.com/ivanilves/lstags) - Tool and API to sync Docker images across different registries. 【🌟Star 241】

* [lwc](https://github.com/timdp/lwc) - A live-updating version of the UNIX wc command. 【🌟Star 10】

* [manssh](https://github.com/xwjdsh/manssh) - manssh is a command line tool for managing your ssh alias config easily. 【🌟Star 210】

* [Moby](https://github.com/moby/moby) - Collaborative project for the container ecosystem to assemble container-based systems. 【🌟Star 56110】

* [Mora](https://github.com/emicklei/mora) - REST server for accessing MongoDB documents and meta data. 【🌟Star 268】

* [ostent](https://github.com/ostrost/ostent) - collects and displays system metrics and optionally relays to Graphite and/or InfluxDB. 【🌟Star 164】

* [Packer](https://github.com/mitchellh/packer) - Packer is a tool for creating identical machine images for multiple platforms from a single source configuration. 【🌟Star 9695】

* [Pewpew](https://github.com/bengadbois/pewpew) - Flexible HTTP command line stress tester. 【🌟Star 217】

* [Pomerium](https://github.com/pomerium/pomerium) - Pomerium is an identity-aware access proxy. 【🌟Star 942】

* [Rodent](https://github.com/alouche/rodent) - Rodent helps you manage Go versions, projects and track dependencies. 【🌟Star 30】

* [s3gof3r](https://github.com/rlmcpherson/s3gof3r) - Small utility/library optimized for high speed transfer of large objects into and out of Amazon S3. 【🌟Star 1028】

* [Scaleway-cli](https://github.com/scaleway/scaleway-cli) - Manage BareMetal Servers from Command Line (as easily as with Docker). 【🌟Star 560】

* [script](https://github.com/bitfield/script) - Making it easy to write shell-like scripts in Go for DevOps and system administration tasks. 【🌟Star 1255】

* [sg](https://github.com/ChristopherRabotin/sg) - Benchmarks a set of HTTP endpoints (like ab), with possibility to use the response code and data between each call for specific server stress based on its previous response. 【🌟Star 5】

* [skm](https://github.com/TimothyYe/skm) - SKM is a simple and powerful SSH Keys Manager, it helps you to manage your multiple SSH keys easily! 【🌟Star 578】

* [StatusOK](https://github.com/sanathp/statusok) - Monitor your Website and REST APIs.Get Notified through Slack, E-mail when your server is down or response time is more than expected. 【🌟Star 1260】

* [terraform-provider-openapi](https://github.com/dikhan/terraform-provider-openapi) - Terraform provider plugin that dynamically configures itself at runtime based on an OpenAPI document (formerly known as swagger file) containing the definitions of the APIs exposed. 【🌟Star 90】

* [traefik](https://github.com/containous/traefik) - Reverse proxy and load balancer with support for multiple backends. 【🌟Star 26949】

* [uTask](https://github.com/ovh/utask) - Automation engine that models and executes business processes declared in yaml. 【🌟Star 124】

* [Vegeta](https://github.com/tsenart/vegeta) - HTTP load testing tool and library. It's over 9000! 【🌟Star 13650】

* [webhook](https://github.com/adnanh/webhook) - Tool which allows user to create HTTP endpoints (hooks) that execute commands on the server. 【🌟Star 4808】

* [Wide](https://wide.b3log.org/login) - Web-based IDE for Teams using Golang.
* [winrm-cli](https://github.com/masterzen/winrm-cli) - Cli tool to remotely execute commands on Windows machines. 【🌟Star 82】


### Other Software

* [borg](https://github.com/crufter/borg) - Terminal based search engine for bash snippets. 【🌟Star 1453】

* [boxed](https://github.com/tejo/boxed) - Dropbox based blog engine. 【🌟Star 72】

* [Cherry](https://github.com/rafael-santiago/cherry) - Tiny webchat server in Go. 【🌟Star 207】

* [Circuit](https://github.com/gocircuit/circuit) - Circuit is a programmable platform-as-a-service (PaaS) and/or Infrastructure-as-a-Service (IaaS), for management, discovery, synchronization and orchestration of services and hosts comprising cloud applications. 【🌟Star 1814】

* [Comcast](https://github.com/tylertreat/Comcast) - Simulate bad network connections. 【🌟Star 6361】

* [confd](https://github.com/kelseyhightower/confd) - Manage local application configuration files using templates and data from etcd or consul. 【🌟Star 6771】

* [croc](https://github.com/schollz/croc) - Easily and securely send files or folders from one computer to another. 【🌟Star 2775】

* [Docker](http://www.docker.com/) - Open platform for distributed applications for developers and sysadmins.
* [Documize](https://github.com/documize/community) - Modern wiki software that integrates data from SaaS tools. 【🌟Star 970】

* [dp](https://github.com/scryinfo/dp) - Through SDK for data exchange with blockchain, developers can get easy access to DAPP development. 【🌟Star 57】

* [drive](https://github.com/odeke-em/drive) - Google Drive client for the commandline. 【🌟Star 5218】

* [Duplicacy](https://github.com/gilbertchen/duplicacy) - A cross-platform network and cloud backup tool based on the idea of lock-free deduplication. 【🌟Star 3123】

* [gfile](https://github.com/Antonito/gfile) - Securely transfer files between two computers, without any third party, over WebRTC. 【🌟Star 524】

* [Go Package Store](https://github.com/shurcooL/Go-Package-Store) - App that displays updates for the Go packages in your GOPATH. 【🌟Star 882】

* [go-peerflix](https://github.com/Sioro-Neoku/go-peerflix) - Video streaming torrent client. 【🌟Star 390】

* [GoBoy](https://github.com/Humpheh/goboy) - Nintendo Game Boy Color emulator written in Go. 【🌟Star 2179】

* [gocc](https://github.com/goccmack/gocc) - Gocc is a compiler kit for Go written in Go. 【🌟Star 373】

* [GoDocTooltip](https://github.com/diankong/GoDocTooltip) - Chrome extension for Go Doc sites, which shows function description as tooltip at function list. 【🌟Star 11】

* [GoLand](https://jetbrains.com/go) - Full featured cross-platform Go IDE.
* [Gor](https://github.com/buger/gor) - Http traffic replication tool, for replaying traffic from production to stage/dev environments in real-time. 【🌟Star 12141】

* [hugo](http://gohugo.io/) - Fast and Modern Static Website Engine.
* [ide](https://github.com/thestrukture/ide) - Browser accessible IDE. Designed for Go with Go. 【🌟Star 255】

* [ipe](https://github.com/dimiro1/ipe) - Open source Pusher server implementation compatible with Pusher client libraries written in GO. 【🌟Star 290】

* [joincap](https://github.com/assafmo/joincap) - Command-line utility for merging multiple pcap files together. 【🌟Star 128】

* [Juju](https://jujucharms.com/) - Cloud-agnostic service deployment and orchestration - supports EC2, Azure, Openstack, MAAS and more.
* [Leaps](https://github.com/jeffail/leaps) - Pair programming service using Operational Transforms. 【🌟Star 659】

* [lgo](https://github.com/yunabe/lgo) - Interactive Go programming with Jupyter. It supports code completion, code inspection and 100% Go compatibility. 【🌟Star 1940】

* [limetext](http://limetext.org/) - Lime Text is a powerful and elegant text editor primarily developed in Go that aims to be a Free and open-source software successor to Sublime Text.
* [LiteIDE](https://github.com/visualfc/liteide) - LiteIDE is a simple, open source, cross-platform Go IDE. 【🌟Star 5797】

* [mockingjay](https://github.com/quii/mockingjay-server) - Fake HTTP servers and consumer driven contracts from one configuration file. You can also make the server randomly misbehave to help do more realistic performance tests. 【🌟Star 437】

* [myLG](https://github.com/mehrdadrad/mylg) - Command Line Network Diagnostic tool written in Go. 【🌟Star 2261】

* [naclpipe](https://github.com/unix4fun/naclpipe) - Simple NaCL EC25519 based crypto pipe tool written in Go. 【🌟Star 20】

* [nes](https://github.com/fogleman/nes) - Nintendo Entertainment System (NES) emulator written in Go. 【🌟Star 4333】

* [orange-cat](https://github.com/noraesae/orange-cat) - Markdown previewer written in Go. 【🌟Star 183】

* [Orbit](https://github.com/gulien/orbit) - A simple tool for running commands and generating files from templates. 【🌟Star 133】

* [peg](https://github.com/pointlander/peg) - Peg, Parsing Expression Grammar, is an implementation of a Packrat parser generator. 【🌟Star 663】

* [restic](https://github.com/restic/restic) - De-duplicating backup program. 【🌟Star 9158】

* [scc](https://github.com/boyter/scc) - Sloc Cloc and Code, a very fast accurate code counter with complexity calculations and COCOMO estimates. 【🌟Star 1245】

* [Seaweed File System](https://github.com/chrislusf/seaweedfs) - Fast, Simple and Scalable Distributed File System with O(1) disk seek. 【🌟Star 9072】

* [shell2http](https://github.com/msoap/shell2http) - Executing shell commands via http server (for prototyping or remote control). 【🌟Star 492】

* [snap](https://github.com/intelsdi-x/snap) - Powerful telemetry framework. 【🌟Star 1804】

* [Snitch](https://github.com/lucasgomide/snitch) - Simple way to notify your team and many tools when someone has deployed any application via Tsuru. 【🌟Star 15】

* [Stack Up](https://github.com/pressly/sup) - Stack Up, a super simple deployment tool - just Unix - think of it like 'make' for a network of servers. 【🌟Star 2093】

* [syncthing](https://syncthing.net/) - Open, decentralized file synchronization tool and protocol.
* [term-quiz](https://github.com/crazcalm/term-quiz) - Quizzes for your terminal. 【🌟Star 17】

* [toxiproxy](https://github.com/shopify/toxiproxy) - Proxy to simulate network and system conditions for automated tests. 【🌟Star 4272】

* [tsuru](https://tsuru.io/) - Extensible and open source Platform as a Service software.
* [vFlow](https://github.com/VerizonDigital/vflow) - High-performance, scalable and reliable IPFIX, sFlow and Netflow collector. 【🌟Star 642】

* [wellington](https://github.com/wellington/wellington) - Sass project management tool, extends the language with sprite functions (like Compass). 【🌟Star 292】


# Resources

*Where to discover new Go libraries.*

## Benchmarks

* [autobench](https://github.com/davecheney/autobench) - Framework to compare the performance between different Go versions. 【🌟Star 90】

* [go-benchmark-app](https://github.com/mrLSD/go-benchmark-app) - Powerful HTTP-benchmark tool mixed with Аb, Wrk, Siege tools. Gathering statistics and various parameters for benchmarks and comparison results. 【🌟Star 20】

* [go-benchmarks](https://github.com/tylertreat/go-benchmarks) - Few miscellaneous Go microbenchmarks. Compare some language features to alternative approaches. 【🌟Star 130】

* [go-http-routing-benchmark](https://github.com/julienschmidt/go-http-routing-benchmark) - Go HTTP request router benchmark and comparison. 【🌟Star 1333】

* [go-web-framework-benchmark](https://github.com/smallnest/go-web-framework-benchmark) - Go web framework benchmark. 【🌟Star 1101】

* [go_serialization_benchmarks](https://github.com/alecthomas/go_serialization_benchmarks) - Benchmarks of Go serialization methods. 【🌟Star 945】

* [gocostmodel](https://github.com/PuerkitoBio/gocostmodel) - Benchmarks of common basic operations for the Go language. 【🌟Star 55】

* [golang-sql-benchmark](https://github.com/tyler-smith/golang-sql-benchmark) - Collection of benchmarks for popular Go database/SQL utilities. 【🌟Star 50】

* [gospeed](https://github.com/feyeleanor/GoSpeed) - Go micro-benchmarks for calculating the speed of language constructs. 【🌟Star 100】

* [kvbench](https://github.com/jimrobinson/kvbench) - Key/Value database benchmark. 【🌟Star 16】

* [skynet](https://github.com/atemerev/skynet) - Skynet 1M threads microbenchmark. 【🌟Star 946】

* [speedtest-resize](https://github.com/fawick/speedtest-resize) - Compare various Image resize algorithms for the Go language. 【🌟Star 186】


## Conferences

* [Capital Go](http://www.capitalgolang.com) - Washington, D.C., USA.
* [dotGo](http://www.dotgo.eu) - Paris, France.
* [GoCon](http://gocon.connpass.com/) - Tokyo, Japan.
* [GoDays](https://www.godays.io/) - Berlin, Germany.
* [GoLab](http://golab.io/) - Florence, Italy.
* [GolangUK](http://golanguk.com/) - London, UK.
* [GopherChina](http://gopherchina.org) - Shanghai, China.
* [GopherCon](http://www.gophercon.com/) - Denver, USA.
* [GopherCon Australia](https://gophercon.com.au/) - Sydney, Australia.
* [GopherCon Brazil](https://gopherconbr.org) - Florianópolis, BR.
* [GopherCon Europe](https://gophercon.is/) - Berlin, Germany.
* [GopherCon India](https://www.gophercon.in/) - Pune, India.
* [GopherCon Israel](https://www.gophercon.org.il/) - Tel Aviv, Israel.
* [GopherCon Russia](https://www.gophercon-russia.ru) - Moscow, Russia.
* [GopherCon Singapore](https://gophercon.sg) - Mapletree Business City, Singapore.
* [GopherCon Vietnam](https://gophercon.vn/) - Ho Chi Minh City, Vietnam.
* [GothamGo](http://gothamgo.com/) - New York City, USA.
* [GoWayFest](https://goway.io/) - Minsk, Belarus.

## E-Books

* [A Go Developer's Notebook](https://leanpub.com/GoNotebook/read)
* [An Introduction to Programming in Go](http://www.golang-book.com/)
* [Build Web Application with Golang](https://www.gitbook.com/book/astaxie/build-web-application-with-golang/details)
* [Building Web Apps With Go](https://www.gitbook.com/book/codegangsta/building-web-apps-with-go/details)
* [Go 101](https://go101.org) - A book focusing on Go syntax/semantics and all kinds of details.
* [Go Bootcamp](http://golangbootcamp.com)
* [Go Succinctly](https://github.com/thedevsir/gosuccinctly) - in Persian. 【🌟Star 13】

* [GoBooks](https://github.com/dariubs/GoBooks) - A curated list of Go books. 【🌟Star 7365】

* [Learning Go](https://www.miek.nl/downloads/Go/Learning-Go-latest.pdf)
* [Network Programming With Go](https://jan.newmarch.name/go/)
* [The Go Programming Language](http://www.gopl.io/)
* [The Golang Standard Library by Example (Chinese)](https://github.com/polaris1119/The-Golang-Standard-Library-by-Example) 【🌟Star 6300】

* [Web Application with Go the Anti-Textbook](https://github.com/thewhitetulip/web-dev-golang-anti-textbook/) 【🌟Star 0】

* [Writing A Compiler In Go](https://compilerbook.com)
* [Writing An Interpreter In Go](https://interpreterbook.com)

## Gophers

* [Free Gophers Pack](https://github.com/MariaLetta/free-gophers-pack) - Gopher graphics pack by Maria Letta with illustrations and emotional characters in vector and raster. 【🌟Star 1768】

* [Go-gopher-Vector](https://github.com/keygx/Go-gopher-Vector) - Go gopher Vector Data [.ai, .svg]. 【🌟Star 31】

* [gopher-logos](https://github.com/GolangUA/gopher-logos) - adorable gopher logos. 【🌟Star 69】

* [gopher-stickers](https://github.com/tenntenn/gopher-stickers) 【🌟Star 462】

* [gopher-vector](https://github.com/golang-samples/gopher-vector) 【🌟Star 351】

* [gophericons](https://github.com/shalakhin/gophericons) 【🌟Star 563】

* [gopherize.me](https://github.com/matryer/gopherize.me) - Gopherize yourself. 【🌟Star 357】

* [gophers](https://github.com/ashleymcnamara/gophers) - Gopher artworks by Ashley McNamara. 【🌟Star 2020】

* [gophers](https://github.com/egonelbre/gophers) - Free gophers. 【🌟Star 1842】

* [gophers](https://github.com/rogeralsing/gophers) - random gopher graphics. 【🌟Star 50】

* [gophers](https://github.com/sillecelik/go-gopher) - Gopher amigurumi toy pattern. 【🌟Star 42】


## Meetups

* [Basel Go Meetup](https://www.meetup.com/Basel-Go-Meetup/)
* [Berlin Golang](https://www.meetup.com/golang-users-berlin/)
* [Brisbane Gophers](https://www.meetup.com/Brisbane-Golang-Meetup/)
* [Canberra Gophers](https://www.meetup.com/Canberra-Gophers/)
* [Go Language NYC](https://www.meetup.com/golanguagenewyork/)
* [Go London User Group](https://www.meetup.com/Go-London-User-Group/)
* [Go Toronto](https://www.meetup.com/go-toronto/)
* [Go User Group Atlanta](https://www.meetup.com/Go-Users-Group-Atlanta/)
* [GoBridge, San Francisco, CA](https://www.meetup.com/gobridge/)
* [GoJakarta](https://www.meetup.com/GoJakarta/)
* [Golang Amsterdam](https://www.meetup.com/golang-amsterdam/)
* [Golang Argentina](https://www.meetup.com/Golang-Argentina/)
* [Golang Baltimore, MD](https://www.meetup.com/BaltimoreGolang/)
* [Golang Bangalore](https://www.meetup.com/Golang-Bangalore/)
* [Golang Belo Horizonte - Brazil](https://www.meetup.com/go-belo-horizonte/)
* [Golang Boston](https://www.meetup.com/bostongo/)
* [Golang Bulgaria](https://www.meetup.com/Golang-Bulgaria/)
* [Golang Cardiff, UK](https://www.meetup.com/Cardiff-Go-Meetup/)
* [Golang Copenhagen](https://www.meetup.com/Go-Cph/)
* [Golang Curitiba - Brazil](https://www.meetup.com/GolangCWB/)
* [Golang DC, Arlington, VA](https://www.meetup.com/Golang-DC/)
* [Golang Dorset, UK](https://www.meetup.com/golang-dorset/)
* [Golang Gurgaon, India](https://www.meetup.com/Gurgaon-Go-Meetup/)
* [Golang Hamburg - Germany](https://www.meetup.com/Go-User-Group-Hamburg/)
* [Golang Israel](https://www.meetup.com/Go-Israel/)
* [Golang Joinville - Brazil](https://www.meetup.com/Joinville-Go-Meetup/)
* [Golang Korea](https://www.meetup.com/GDG-Golang-Korea/)
* [Golang Lima - Peru](https://www.meetup.com/Golang-Peru/)
* [Golang Lyon](https://www.meetup.com/Golang-Lyon/)
* [Golang Marseille](https://www.meetup.com/fr-FR/Golang-Marseille/)
* [Golang Melbourne](https://www.meetup.com/golang-mel/)
* [Golang Mountain View](https://www.meetup.com/Golang-Mountain-View/)
* [Golang New York](https://www.meetup.com/nycgolang/)
* [Golang Paris](https://www.meetup.com/Golang-Paris/)
* [Golang Pune](https://www.meetup.com/Golang-Pune/)
* [Golang Singapore](https://www.meetup.com/golangsg/)
* [Golang Stockholm](https://www.meetup.com/Go-Stockholm/)
* [Golang Sydney, AU](https://www.meetup.com/golang-syd/)
* [Golang São Paulo - Brazil](https://www.meetup.com/golangbr/)
* [Golang Taipei](https://www.meetup.com/golang-taipei-meetup/)
* [Golang Vancouver, BC](https://www.meetup.com/golangvan/)
* [Golang Казань](https://www.meetup.com/GolangKazan/)
* [Golang Москва](https://www.meetup.com/Golang-Moscow/)
* [Golang Питер](https://www.meetup.com/Golang-Peter/)
* [GoSF - San Francisco, CA](https://www.meetup.com/golangsf)
* [Istanbul Golang](https://www.meetup.com/Istanbul-Golang/)
* [Seattle Go Programmers](https://www.meetup.com/golang/)
* [Ukrainian Golang User Groups](https://www.meetup.com/uagolang/)
* [Utah Go User Group](https://www.meetup.com/utahgophers/)
* [Women Who Go - San Francisco, CA](https://www.meetup.com/Women-Who-Go/)

*Add the group of your city/country here (send **PR**)*

## Twitter

* [@golang](https://twitter.com/golang)
* [@golang_news](https://twitter.com/golang_news)
* [@golangch](https://twitter.com/golangch)
* [@golangflow](https://twitter.com/golangflow)
* [@golangweekly](https://twitter.com/golangweekly)

## Websites

* [Awesome Go @LibHunt](https://go.libhunt.com) - Your go-to Go Toolbox.
* [Awesome Remote Job](https://github.com/lukasz-madon/awesome-remote-job) - Curated list of awesome remote jobs. A lot of them are looking for Go hackers. 【🌟Star 15542】

* [awesome-awesomeness](https://github.com/bayandin/awesome-awesomeness) - List of other amazingly awesome lists. 【🌟Star 25488】

* [CodinGame](https://www.codingame.com/) - Learn Go by solving interactive tasks using small games as practical examples.
* [Go Blog](http://blog.golang.org) - The official Go blog.
* [Go Challenge](http://golang-challenge.org/) - Learn Go by solving problems and getting feedback from Go experts.
* [Go Community on Hashnode](https://hashnode.com/n/go) - Community of Gophers on Hashnode.
* [Go Forum](https://forum.golangbridge.org) - Forum to discuss Go.
* [Go In 5 Minutes](https://www.goin5minutes.com/) - 5 minute screencasts focused on getting one thing done.
* [Go Projects](https://github.com/golang/go/wiki/Projects) - List of projects on the Go community wiki.
* [Go Report Card](https://goreportcard.com) - A report card for your Go package.
* [go.dev](https://go.dev/) - A hub for Go developers.
* [gocryforhelp](https://github.com/ninedraft/gocryforhelp) - Collection of Go projects that needs help. Good place to start your open-source way in Go. 【🌟Star 38】

* [godoc.org](https://godoc.org/) - Documentation for open source Go packages.
* [Golang Developer Jobs](https://golangjob.xyz) - Developer Jobs exclusivly for Golang related Roles.
* [Golang Flow](https://golangflow.io) - Post Updates, News, Packages and more.
* [Golang News](https://golangnews.com) - Links and news about Go programming.
* [golang-graphics](https://github.com/mholt/golang-graphics) - Collection of Go images, graphics, and art. 【🌟Star 142】

* [golang-nuts](https://groups.google.com/forum/#!forum/golang-nuts) - Go mailing list.
* [Google Plus Community](https://plus.google.com/communities/114112804251407510571) - The Google+ community for #golang enthusiasts.
* [Gopher Community Chat](https://invite.slack.golangbridge.org) - Join Our New Slack Community For Gophers ([Understand how it came](https://blog.gopheracademy.com/gophers-slack-community/)).
* [Gophercises](https://gophercises.com/) - Free coding exercises for budding gophers.
* [gowalker.org](https://gowalker.org) - Go Project API documentation.
* [json2go](https://m-zajac.github.io/json2go) - Advanced JSON to Go struct conversion - online tool.
* [justforfunc](https://www.youtube.com/c/justforfunc) - Youtube channel dedicated to Go programming language tips and tricks, hosted by  Francesc Campoy [@francesc](https://twitter.com/francesc).
* [Made with Golang](https://madewithgolang.com/?ref=awesome-go)
* [r/Golang](https://www.reddit.com/r/golang) - News about Go.
* [studygolang](https://studygolang.com) - The community of studygolang in China.
* [Trending Go repositories on GitHub today](https://github.com/trending?l=go) - Good place to find new Go libraries.
* [TutorialEdge - Golang](https://tutorialedge.net/course/golang/)

### Tutorials

* [50 Shades of Go](http://devs.cloudimmunity.com/gotchas-and-common-mistakes-in-go-golang/) - Traps, Gotchas, and Common Mistakes for New Golang Devs.
* [A Guide to Golang E-Commerce](https://snipcart.com/blog/golang-ecommerce-ponzu-cms-demo?utm_term=golang-ecommerce-ponzu-cms-demo) - Building a Golang site for e-commerce (demo included).
* [A Tour of Go](http://tour.golang.org/) - Interactive tour of Go.
* [Build web application with Golang](https://github.com/astaxie/build-web-application-with-golang) - Golang ebook intro how to build a web app with golang. 【🌟Star 33511】

* [Building Go Web Applications and Microservices Using Gin](https://semaphoreci.com/community/tutorials/building-go-web-applications-and-microservices-using-gin) - Get familiar with Gin and find out how it can help you reduce boilerplate code and build a request handling pipeline.
* [Caching Slow Database Queries](https://medium.com/@rocketlaunchr.cloud/caching-slow-database-queries-1085d308a0c9) - How to cache slow database queries.
* [Canceling MySQL](https://medium.com/@rocketlaunchr.cloud/canceling-mysql-in-go-827ed8f83b30) - How to cancel MySQL queries.
* [Ethereum Development with Go](https://github.com/miguelmota/ethereum-development-with-go-book) - A little e-book on Ethereum Development with Go. 【🌟Star 536】

* [Games With Go](http://gameswithgo.org/) - A video series teaching programming and game development.
* [Go By Example](https://gobyexample.com/) - Hands-on introduction to Go using annotated example programs.
* [Go Cheat Sheet](https://github.com/a8m/go-lang-cheat-sheet) - Go's reference card. 【🌟Star 4336】

* [Go database/sql tutorial](http://go-database-sql.org/) - Introduction to database/sql.
* [Go Playground for iOS](https://itunes.apple.com/us/app/go-playground/id1437518275?ls=1&mt=8) - Interactively edit & play Go snippets on your mobile device.
* [Go WebAssembly Tutorial - Building a Simple Calculator](https://tutorialedge.net/golang/go-webassembly-tutorial/)
* [go-patterns](https://github.com/tmrts/go-patterns) - Curated list of Go design patterns, recipes and idioms. 【🌟Star 11905】

* [Golang for Node.js Developers](https://github.com/miguelmota/golang-for-nodejs-developers) - Examples of Golang compared to Node.js for learning. 【🌟Star 1090】

* [Golangbot](https://golangbot.com/learn-golang-series/) - Tutorials to get started with programming in Go.
* [GolangCode](https://golangcode.com/) - Collection of code snippets and tutorials to help tackle every day issues.
* [Hackr.io](https://hackr.io/tutorials/learn-golang) - Learn Go from the best online golang tutorials submitted & voted by the golang programming community.
* [How to Use Godog for Behavior-driven Development in Go](https://semaphoreci.com/community/tutorials/how-to-use-godog-for-behavior-driven-development-in-go) - Get started with Godog — a Behavior-driven development framework for building and testing Go applications.
* [Learn Go with TDD](https://github.com/quii/learn-go-with-tests) - Learn Go with test-driven development. 【🌟Star 9810】

* [Learning Golang - From zero to hero](https://milapneupane.com.np/2019/07/06/learning-golang-from-zero-to-hero/) - Getting started with golang for beginner.
* [package main](https://www.youtube.com/packagemain) - YouTube channel about Programming in Go.
* [Programming with Google Go](https://www.coursera.org/specializations/google-golang) - Coursera Specialization to learn about Go from scratch.
* [The world’s easiest introduction to WebAssembly with Golang](https://medium.com/@martinolsansky/webassembly-with-golang-is-fun-b243c0e34f02)
* [Working with Go](https://github.com/mkaz/working-with-go) - Intro to go for experienced programmers. 【🌟Star 1149】

* [Your basic Go](http://yourbasic.org/golang) - Huge collection of tutorials and how to's.

