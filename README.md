# MrDekk Lists

Things that I've found useful and worth exploring with my humble comments if any. Some of them I've caught in GitHub explore, other in some discussions or may be just during googling for something.

## Table of Contents

* [GameDev](#gamedev)
  * [Server](#gamedev-server) 
  * [Graphics](#gamedev-graphics)
  * [Foundation](#gamedev-foundation) - fundamental things to gamedev
  * [Web](#gamedev-web)
  * [PCG](#gamedev-pcg)
  * [AI](#gamedev-ai)
  * [Engines](#gamedev-engines)
* [General AI](#ai-general)
  * [Machine Learning](#ai-general-machine-learning) 
  * [Deep Learning](#ai-general-deep-learn)
  * [Natural Language Processing](#ai-general-nlp)
* [App Dev](#app-dev) - things for application development
  * [Backends](#app-dev-backends)
  * [iOS](#app-dev-ios)   
  * [CSS](#app-dev-css)
  * [Parallel](#app-dev-parallel)
* [NodeJS](#nodejs)
  * [Libs](#nodejs-libs)  
* [JavaScript](#javascript)
  * [Web](#javascript-web)  
  * [Mobile](#javascript-mobile)
  * [Desktop](#javascript-desktop)
* [Swift](#swift)
* [C++](#cpp)
  * [Conferences](#cpp-conferences) 
  * [Tools](#cpp-tools)
* [Java](#java)
* [Scala](#scala)
  * [Akka](#akka) 
* [PHP](#php) 
* [Referenced Awesome Lists](#ref-awesomeness) 
* [Just Interesting](#just-interesting)
* [DevOps](#devops)
  * [Docker](#devops-docker) 
* [Analytics Solutions](#analytics) 
* [Jobs](#jobs)
* [Apps](#apps)
* [Games](#games)
* [Tech](#tech)

<a name='gamedev'></a>
## GameDev

<a name='gamedev-server' ></a>
### GameDev - Server

* [Akka Server][repo-akka-server] - some simple game server written with Akka, russian article about this - ([Site][site-akka-server]). Very interesting article describing some basic things on making distributed servers with Akka and Scala.

[repo-akka-server]: https://github.com/solverit/akka-server
[site-akka-server]: https://habrahabr.ru/post/259185/

<a name='gamedev-graphics' ></a>
### GameDev - Graphics

* [Vulkan Samples][repo-lunarg-vulkan-samples] - Samples for new graphics API - Vulkan (successor of OpenGL I think). Interesting things to explore to learn new API.
* [Vulkan C++ API][repo-nvpro-vulkan-cpp] - C++ for new graphics API Vulkan.
* [Vulkan Docs][repo-vulkan-docs] - New graphics api Vulkan Docs
* [TinyGL ES][repo-tinygles] - Software-rendered OpenGL ES
* [heman][repo-heman] - C99 heightmap utilites
* [Tiled][repo-tiled] - A generic tiled map editor
* [Sea3D][repo-sea3d] - An open-source format and tools for game developers.

[repo-lunarg-vulkan-samples]: https://github.com/LunarG/VulkanSamples
[repo-nvpro-vulkan-cpp]: https://github.com/nvpro-pipeline/vkcpp
[repo-vulkan-docs]: https://github.com/KhronosGroup/Vulkan-Docs
[repo-tinygles]: https://github.com/lunixbochs/tinygles
[repo-heman]: https://github.com/prideout/heman
[repo-tiled]: https://github.com/bjorn/tiled
[repo-sea3d]: https://github.com/sunag/sea3d

<a name='gamedev-foundation' ></a>
### GameDev - Foundation

* [EASTL][repo-eastl] - EASTL stands for Electronic Arts Standard Template Library. Implementation of STL from Electronic Arts. I've heard this is super fast and super useful, but it can be some marketing things, I've not tested it myself yet.
* [Selene][repo-selene] - C++11 header-only bindings to Lua

[repo-eastl]: https://github.com/electronicarts/EASTL
[repo-selene]: https://github.com/jeremyong/Selene

<a name='gamedev-web' ></a>
### GameDev - Web

* [goo.js][repo-goojs] - 3D WebGL engine

[repo-goojs]: https://github.com/GooTechnologies/goojs

<a name='gamedev-pcg' ></a>
### GameDev - Procedural Content Generation (PCG)

* [Procedural City Generation][repo-proc-city-gen] - Procedural city generation 

[repo-proc-city-gen]: https://github.com/josauder/procedural_city_generation

<a name='gamedev-ai' ></a>
### GameDev - AI

* [OpenRTS][repo-openrts] - OpenRTS - RTS game 3d engine in java 7
* [NoahGameFrame][repo-noah-game-frame] - A fast, scalable distributed game server framework for C++, include actor library, network library, can be used as a real time multiplayer game engine (MMO RPG)

[repo-openrts]: https://github.com/methusalah/OpenRTS
[repo-noah-game-frame]: https://github.com/ketoo/NoahGameFrame

<a name='gamedev-engines' ></a>
### GameDev - Engines

* [Cocos2d-x][repo-cocos2d-x] - cocos2d for C++
* [Atomic Game Engine][repo-atomic-ge] - Atomic Game Engine (crossplatform, 2D/3D)

* [GameGear.IO][repo-gamegear-io] - SDK directory for mobile game developers

[repo-cocos2d-x]: https://github.com/cocos2d/cocos2d-x
[repo-atomic-ge]: https://github.com/AtomicGameEngine/AtomicGameEngine

[repo-gamegear-io]: https://github.com/soomla/gamegear.io

<a name='ai-general' ></a>
## General AI

<a name='ai-general-machine-learning' ></a>
### General AI - Machine Learning

* [Machine Learning Tutorials][repo-ml-tutorials] - machine learning and deep learning tutorials, articles and other resources
* [Tensorflow][repo-tensorflow] - Google AI toolkit for Machine Learning
* [Neural Network Papers][repo-neural-network-papers]
* [Aerosolve][repo-aerosolve] - A machine learning package built for humans.

[repo-ml-tutorials]: https://github.com/ujjwalkarn/Machine-Learning-Tutorials
[repo-tensorflow]: https://github.com/tensorflow/tensorflow
[repo-neural-network-papers]: https://github.com/robertsdionne/neural-network-papers
[repo-aerosolve]: https://github.com/airbnb/aerosolve

<a name='ai-general-deep-learn'></a>
### General AI - Deep Learning

* [Neon][repo-neon] - described as Python based Deep Learning Framework by Nervana(tm). I've found this in some discussion about deep learning as a good industrial implementation of deep learning, and thought it worth exploring. Haven't explored yet.
* [DeepDetect][repo-deep-detect] - Deep Learning API and Server in C++11 with Python bindings and support for Caffe

[repo-neon]: https://github.com/NervanaSystems/neon
[repo-deep-detect]: https://github.com/beniz/deepdetect

<a name='ai-general-nlp' ></a>
### General AI - Natural Language Processing (NLP)

* [Annabell][repo-annabell] - cognitive neural architecture able to learn and communicate through natural language

[repo-annabell]: https://github.com/golosio/annabell

<a name='app-dev' ></a>
## App Dev

<a name='app-dev-backends' ></a>
### App Dev - Backends

* [Parse Alternatives][repo-parse-alternatives] - after Facebook closure of Parse some alternatives appeared. This is special list for such alternatives.

[repo-parse-alternatives]: https://github.com/relatedcode/ParseAlternatives

<a name='app-dev-ios' ></a>
### App Dev - iOS

* [Carthage][repo-carthage] - package manager for cocoa

[repo-carthage]: https://github.com/Carthage/Carthage

<a name='app-dev-css' ></a>
### App Dev - CSS (Markup)

* [Material Design Lite][repo-material-design-lite] - bootstrap like markup library for Google's material design

[repo-material-design-lite]: https://github.com/google/material-design-lite

<a name='app-dev-parallel' ></a>
### App Dev - Parallel Processing

* [Array Fire][repo-array-fire] - A general purpose GPU library.

[repo-array-fire]: https://github.com/arrayfire/arrayfire

<a name='nodejs' ></a>
## NodeJS

<a name='nodejs-libs' ></a>
### NodeJS - Libs

* [ParseServer][repo-parse-server] - Parse-compatible API server module for Node/Express.
* [emailjs][repo-emailjs] - Very good nodejs library to send emails. I've used it in my pet project and very satisfied.
* [request][repo-request] - Very good nodejs library to make HTTP request. A-ka CURL for nodejs.
* [jQuery][repo-node-jquery] - jQuery with a thin wrapper for node.js

[repo-parse-server]: https://github.com/ParsePlatform/parse-server
[repo-emailjs]: https://github.com/eleith/emailjs
[repo-request]: https://github.com/request/request
[repo-node-jquery]: https://github.com/UncoolAJ86/node-jquery

<a name='javascript' ></a>
## JavaScript

<a name='javascript-web' ></a>
### JavaScript - Web

* [CMS.js][repo-cmsjs] - JavaScript static web-site generator, like Jekyll but JavaScript.
* [D3.js][repo-d3js] - D3.js visualization library for HTML and SVG. Graph, charts, maps and other visualization things exists in this powerful library. I've used it in my projects.
* [plotly.js][repo-plotlyjs] - The open source javascript graphing library that powers plotly
* [quill][repo-quill] - A cross browser rich text editor with an API
* [TechAnJS][repo-techanjs] - A visual, technical analysis and charting (candlestick, OHLC, indicators)
* [KnockoutJS - LocalStorage][repo-ko-local-storage] - localStorage persistence for knockoutjs
* [KnockoutJS - sortable][repo-ko-sortable] - knockoutjs binding to connect observableArrays with jQuery UI sortable functionality
* [jQuery - Nestable][repo-jq-nestable] - Drag & drop hierarchical list with mouse and touch compatibility

[repo-cmsjs]: https://github.com/cdmedia/cms.js
[repo-d3js]: https://github.com/mbostock/d3
[repo-plotlyjs]: https://github.com/plotly/plotly.js
[repo-quill]: https://github.com/quilljs/quill
[repo-techanjs]: https://github.com/andredumas/techan.js
[repo-ko-local-storage]: https://github.com/jimrhoskins/knockout.localStorage
[repo-ko-sortable]: https://github.com/rniemeyer/knockout-sortable
[repo-jq-nestable]: https://github.com/dbushell/Nestable

<a name='javascript-mobile' ></a>
### JavaScript - Mobile

* [Image Picker for React-Native][repo-react-native-image-picker] - Native image picker functionality for React Native framework.

[repo-react-native-image-picker]: https://github.com/marcshilling/react-native-image-picker

<a name='javascript-desktop' ></a>
### JavaScript - Desktop

* [NW.js][repo-nwjs] - Special framework for writing desktop applications with JavaScript and NodeJS

[repo-nwjs]: https://github.com/nwjs/nw.js

<a name='swift' ></a>
## Swift

Any interesting things about new Apple programming language. I didn't have any time to explore swift yet, but I think it is very interesting thing to explore.

* [Kitura][repo-ibm-kitura] - Web-framework and HTTP-server developed by IBM for Swift. 
* [Swift Algorithms Club][repo-swift-algorithms-club] - Algorithms and Data Structures on Swift with explanations. Good reference for algorithms themselves and swift in particular.
* [Best Practices][repo-swift-best-practices] - Swift community best practices

[repo-ibm-kitura]: https://github.com/IBM-Swift/Kitura 
[repo-swift-algorithms-club]: https://github.com/hollance/swift-algorithm-club
[repo-swift-best-practices]: https://github.com/schwa/Swift-Community-Best-Practices

<a name='cpp' ></a>
## C++

* [par][repo-par] - single-file C libraries from Philip Allan Rideout. To reference. Simple things with code.
* [C++ DHT][repo-opendht] - A C++11 Distributed Hash Table implementation. I've always want to explore things such DHT. So this is a good place to see how jedi do it.
* [UTF-8][repo-utf8-str] - UTF-8 string functions for C++.
* [jucipp][repo-jucipp] - lightweight crossplatform C++ IDE. Haven't tested it yet.
* [hyperscan][repo-hyperscan] - High-performance regular expression library
* [xxHash][repo-xxhash] - Extremely fast non-cryptographic hash algorithm
* [BDE][repo-bde] - Basic Development Environment - a set of foundational C++ libraries used at Bloomberg
* [SDSL][repo-sdsl] - Bunch of C++11 data structures
* [CoreGuidelines][repo-cpp-core-guidelines] - C++ notation by Stroustrup
* [Spdlog][repo-spdlog] - Super fast c++ logging library
* [date][repo-cxx-date] - Date/time library based on c++11 &lt;chrono&gt;
* [rapid-json][repo-rapid-json] - fast JSON parser for C++ (SAX/DOM style)
* [CloudFlare zLib][repo-cloudflare-zlib] - cloudflare fork of zlib with performance improvements
* [HerculesWS][repo-hercules-ws] - Colaborative attempt to create MMORPG server
* [Cuberite][repo-cuberite] - A custom Minecraft compatible game server written in C++
* [Seastar][repo-seastar] - High performance server-side application framework

[repo-par]: https://github.com/prideout/par
[repo-opendht]: https://github.com/savoirfairelinux/opendht
[repo-utf8-str]: https://github.com/sheredom/utf8.h
[repo-jucipp]: https://github.com/cppit/jucipp
[repo-hyperscan]: https://github.com/01org/hyperscan
[repo-xxhash]: https://github.com/Cyan4973/xxHash
[repo-bde]: https://github.com/bloomberg/bde
[repo-sdsl]: https://github.com/simongog/sdsl-lite
[repo-cpp-core-guidelines]: https://github.com/isocpp/CppCoreGuidelines
[repo-spdlog]: https://github.com/gabime/spdlog
[repo-cxx-date]: https://github.com/HowardHinnant/date
[repo-rapid-json]: https://github.com/miloyip/rapidjson
[repo-hercules-ws]: https://github.com/HerculesWS/Hercules
[repo-cuberite]: https://github.com/cuberite/cuberite
[repo-seastar]: https://github.com/scylladb/seastar

<a name='cpp-conferences' ></a>
### C++ - Conferences

* [CppCon2015][repo-cppcon-2015] - Presentation Materials from C++ Con 2015
* [CppBestPractices][repo-cpp-best-practices] - Collaborative Collection of C++ Best Practices

[repo-cppcon-2015]: https://github.com/CppCon/CppCon2015
[repo-cpp-best-practices]: https://github.com/lefticus/cppbestpractices

<a name='cpp-tools' ></a>
### C++ - Tools

* [Snowman][repo-snowman] - Snowman decompiler

[repo-snowman]: https://github.com/yegord/snowman

<a name='java' ></a>
## Java

* [Java 8 Tutorial][repo-java8-tutorial] - Modern Java 8 Guide
* [TA4j][repo-ta4j] - Technical Analysis Library on Java
* [Feather][repo-feather] - Lightweight dependency injection for Java and Android (JSR-330)
* [Chronicle-Queue][repo-chronicle-queue] - Micro second messaging that stores everything to disk (OpenHFT)

[repo-java8-tutorial]: https://github.com/winterbe/java8-tutorial
[repo-ta4j]: https://github.com/mdeverdelhan/ta4j
[repo-feather]: https://github.com/zsoltherpai/feather
[repo-chronicle-queue]: https://github.com/OpenHFT/Chronicle-Queue

<a name='scala' ></a>
## Scala

* [Play! Framework][repo-play-framework] - Web-framework in Scala language from Akka creators. Looks interesting but haven't used yet. May be viable alternative to Spring MVC Framework.

[repo-play-framework]: https://github.com/playframework/playframework

<a name='akka' ></a>
### Scala - Akka

* [Akka][repo-akka] - Actor model implementation in Scala language. Very mature and very interesting.
* [Gearpump][repo-gearpump] - Streaming analytics engine based on Akka. Have some similarities with Storm.
* [Spray][repo-spray] - [Spray][site-spray] is an open-source toolkit for building REST/HTTP integration layers  on top of Scala and Akka.
* [Quiz Management Service][repo-quiz-management-service] - collection of tutorials on how to build REST with Spray/Akka http

[repo-akka]: https://github.com/akka/akka
[repo-gearpump]: https://github.com/gearpump/gearpump
[repo-spray]: https://github.com/spray/spray
[site-spray]: http://spray.io/
[repo-quiz-management-service]: https://github.com/DanielaSfregola/quiz-management-service

<a name='php' ></a>
## PHP

* [Kohana][repo-kohana] - PHP Web applications framework. Successor of CodeIgnitter. Very good, but in the age of nodejs is a bit outdated.

[repo-kohana]: https://github.com/kohana/kohana

<a name='ref-awesomeness' ></a>
## Referenced Awesome Lists

* [Awesome: Deep Vision][repo-awesome-deep-vision] - A curated list of deep learning resources for computer vision
* [Awesome: App Ideas][repo-awesome-app-ideas] - List of awesome app ideas. List of well known app ideas, check it before you start your own super-puper-mega-app.
* [Awesome: Interviews][repo-awesome-interviews] - Curated list of interview questions.
* [Awesome: Stock Resources][repo-awesome-stock-resources] - Collection of links for free stock photography, video and illustration websites
* [Awesome: OpenSource Documents][repo-awesome-opensource-documents] - Curated list of awesome open source or open source licensed documents, guides, books
* [Awesome: Web Scraping][repo-awesome-web-scraping] - List of libraries, tools, and APIs for web scraping and data processing
* [Awesome: Games][repo-awesome-games] - A list of popular/awesome videos games, add-ons, maps, etc. hosted on GitHub. Any genre. Any platform. Any engine
* [Awesome: Self Hosted][repo-awesome-self-hosted] - Curated list of self hosted apps
* [Awesome: Electron][repo-awesome-electron] - Useful resources for creating apps with Electron
* [Open Source iOS Apps][repo-open-source-ios-apps] - Collaborative List of Open-Source iOS Apps
* [Web Design Standards][repo-web-design-standards] - Open Source UI Components and visual style guides
* [Data Science Blogs][repo-data-science-blogs] - A curated list of Data Science Blogs
* [Software Engineering Blogs][repo-software-engineering-blogs] - A curated list of Software Engineering blogs
* [Open Exoplanet Catalogue][repo-open-exoplanet-catalogue] - The Open Exoplanet Catalogue
* [CSCS][repo-cscs] - A curated list of Coding Style Conventions and Standards
* [Awesome][repo-awesome] - Awesome list of awesome lists :)
* [Lists][repo-lists] - List of awesome lists :)

[repo-awesome-deep-vision]: https://github.com/kjw0612/awesome-deep-vision
[repo-awesome-app-ideas]: https://github.com/tastejs/awesome-app-ideas
[repo-awesome-interviews]: https://github.com/MaximAbramchuck/awesome-interviews
[repo-awesome-stock-resources]: https://github.com/neutraltone/awesome-stock-resources
[repo-awesome-opensource-documents]: https://github.com/hubtee/awesome-opensource-documents
[repo-awesome-web-scraping]: https://github.com/lorien/awesome-web-scraping
[repo-awesome-games]: https://github.com/leereilly/games
[repo-awesome-self-hosted]: https://github.com/Kickball/awesome-selfhosted
[repo-awesome-electron]: https://github.com/sindresorhus/awesome-electron
[repo-open-source-ios-apps]: https://github.com/dkhamsing/open-source-ios-apps
[repo-web-design-standards]: https://github.com/18F/web-design-standards
[repo-data-science-blogs]: https://github.com/rushter/data-science-blogs
[repo-software-engineering-blogs]: https://github.com/kilimchoi/engineering-blogs
[repo-open-exoplanet-catalogue]: https://github.com/OpenExoplanetCatalogue/open_exoplanet_catalogue
[repo-cscs]: https://github.com/SalGnt/cscs
[repo-awesome]: https://github.com/sindresorhus/awesome
[repo-lists]: https://github.com/jnv/lists

<a name='just-interesting' ></a>
## Just Interesting

* [Bloomberg-BETA Manual][repo-bloomberg-beta-manual] - Investment company placed their terms and some useful info on GitHub. Very interesting mean to publish information. For my personal reference.
* [52 technologies in 2016][repo-52tech-in2016] - Somebody (shekhargulati) publish very interesting tech article every week (saturdays).
* [Reading][repo-reading] - Some interesting things to read (even in mandarin)
* [Reading2][repo-reading2] - Another interesting things to read (again some things in mandarin)
* [Hack My Resume][repo-hack-my-resume] - Swiss army knife to work with resumes (CV)
* [Bad Data Guide][repo-bad-data-guide] - Exhaustive reference to problems with data in real world and how to deal with them.
* [Ghost][repo-ghost] - New blogging platform (Just a blogging platform)
* [RAML][repo-raml] - RESTful API Modelling Language 
* [Open Source Computer Science][repo-oss-cs] - Self taught lessons on computer science
* [DEX UI][repo-dex-ui] - Sci-Fi desktop on Linux
* [Washing Machine View][repo-washing-machine-view] - Just Android demo - Washing Machine
* [NASA 3D Models][repo-nasa-3d-models] - NASA 3D Models collection
* [Logos][repo-svg-logos] - HUGE collection of svg logos
* [Typefaces][repo-typefaces] - Typefaces for source code beautification

[repo-bloomberg-beta-manual]: https://github.com/Bloomberg-Beta/Manual
[repo-52tech-in2016]: https://github.com/shekhargulati/52-technologies-in-2016
[repo-reading]: https://github.com/emmore/Reading
[repo-reading2]: https://github.com/chenruiao/ares
[repo-hack-my-resume]: https://github.com/hacksalot/HackMyResume
[repo-bad-data-guide]: https://github.com/Quartz/bad-data-guide
[repo-ghost]: https://github.com/TryGhost/Ghost
[repo-raml]: https://github.com/raml-org/raml-spec
[repo-oss-cs]: https://github.com/open-source-society/computer-science
[repo-dex-ui]: https://github.com/seenaburns/dex-ui
[repo-washing-machine-view]: https://github.com/naman14/WashingMachineView
[repo-nasa-3d-models]: https://github.com/nasa/NASA-3D-Resources
[repo-svg-logos]: https://github.com/gilbarbara/logos
[repo-typefaces]: https://github.com/chrissimpkins/codeface

<a name='devops' ></a>
## DevOps

<a name='devops-docker' ></a>
### DevOps - Docker

* [Docker Curriculum][repo-docker-curriculum] - Tutorial on how to get started with docker. Worth exploring, but not yet.

[repo-docker-curriculum]: https://github.com/prakhar1989/docker-curriculum

<a name='analytics' ></a>
## Analytics Solutions

* [TAP][repo-tap] - [Trusted Analytics Platform][site-tap] from Intel (uses gearpump)
* [Arcadia][site-arcadia] - Arcadia Converged Analytics Platform (visualization without coding) for Hadoop
* [Keen IO][repo-keen-io] - Keen IO Data Explorer - a point-and-click analytics and visualization tool
* [Event Store][repo-event-store] - The open-source, functional database with Complex Event Processing in JavaScript

[repo-tap]: https://github.com/trustedanalytics
[site-tap]: https://trustedanalytics.org/
[site-arcadia]: http://www.arcadiadata.com/
[repo-keen-io]: https://github.com/keen/explorer
[repo-event-store]: https://github.com/EventStore/EventStore

<a name='jobs' ></a>
## Jobs

* [remove jobs][repo-remote-jobs] - A list of semi to fully remote-friendly companies in tech

[repo-remote-jobs]: https://github.com/jessicard/remote-jobs

<a name='apps' ></a>
## Apps

* [N1][repo-n1] - Extensible email client, built on web technologies (electron and so on)
* [Mattermost][repo-mattermost] - Open Source self-hosted Slack alternative
* [OpenSCAD][repo-openscad] - OpenSCAD - The programmers Solid 3D CAD Modeller
* [Streama][repo-streama] - Like Netflix, but self hosted
* [Gruik][repo-gruik] - Web-based markdown note-taking web app ( seams dead :( )
* [Lobsters][repo-lobsters] - Rails code running Lobsters link aggregation site
* [FreeCAD][repo-freecad] - FreeCAD official git mirror
* [KanDan][repo-kandan] - Kandan is an Open Source Alternative to HipChat
* [odoo][repo-odoo] - Odoo (formerly OpenERP). Open Source Apps To Grow Your Business.
* [Phabricator][repo-phabricator] - Open software engineering platform and fun adventure game

[repo-n1]: https://github.com/nylas/N1
[repo-mattermost]: https://github.com/mattermost/platform
[repo-openscad]: https://github.com/openscad/openscad
[repo-streama]: https://github.com/dularion/streama
[repo-gruik]: https://github.com/grena/gruik
[repo-lobsters]: https://github.com/jcs/lobsters
[repo-freecad]: https://github.com/FreeCAD/FreeCAD
[repo-kandan]: https://github.com/kandanapp/kandan
[repo-odoo]: https://github.com/odoo/odoo
[repo-phabricator]: https://github.com/phacility/phabricator

<a name='games' ></a>
## Games

* [StarCraft][repo-starcraft] - HTML5 version of StarCraft game

[repo-starcraft]: https://github.com/gloomyson/StarCraft

<a name='tech' ></a>
## Tech

* [Ceph][repo-ceph] - Ceph is a distributed object, block, and file storage platform

[repo-ceph]: https://github.com/ceph/ceph