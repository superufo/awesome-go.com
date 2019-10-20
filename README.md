# awesome-go.com

<!DOCTYPE html>
<html>
<head>
	<meta charset="utf-8">
	<meta http-equiv="X-UA-Compatible" content="IE=edge">
	<meta http-equiv="Content-Language" content="en">
	<meta name="viewport" content="width=device-width">
	<title>Awesome Go</title>
	<meta name="description" content="A curated list of awesome Go frameworks, libraries and software">
	<meta name="keywords" content="golang, go, awesome, awesome-go, go framework, golang framework">
        <meta name="twitter:card" value="summary">
        <meta property="og:title" content="Awesome Go" />
        <meta property="og:type" content="article" />
        <meta property="og:url" content="https://awesome-go.com/" />
        <meta property="og:image" content="https://awesome-go.com/assets/logo.png" />
        <meta property="og:description" content="A curated list of awesome #Golang frameworks, libraries and software" /> 
	
	<link rel="stylesheet" type="text/css" href="/assets/fonts/firasans.css">
	<link rel="stylesheet" type="text/css" href="/assets/normalize.css">
	<link rel="stylesheet" type="text/css" href="/assets/awesome-go.css">
</head>
<body>
	<img src="/assets/logo.png" alt="Awesome Go" class="awesome-logo" />

	<div id="content">
		<h1><a name="awesome-go" class="anchor" href="#awesome-go" rel="nofollow" aria-hidden="true"><span class="octicon octicon-link"></span></a>Awesome Go</h1>

<p><a href="https://travis-ci.org/avelino/awesome-go" rel="nofollow"><img src="https://travis-ci.org/avelino/awesome-go.svg?branch=master" alt="Build Status"></a> <a href="https://github.com/sindresorhus/awesome" rel="nofollow"><img src="https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg" alt="Awesome"></a> <a href="http://gophers.slack.com/messages/awesome" rel="nofollow"><img src="https://img.shields.io/badge/join-us%20on%20slack-gray.svg?colorB=red&logo=slack&longCache=true" alt="Slack Widget"></a> <a href="https://app.netlify.com/sites/awesome-go/deploys" rel="nofollow"><img src="https://api.netlify.com/api/v1/badges/83a6dcbe-0da6-433e-b586-f68109286bd5/deploy-status" alt="Netlify Status"></a></p>

<p><a href="https://www.patreon.com/avelinosource" rel="nofollow"><img src="https://c5.patreon.com/external/logo/become_a_patron_button@2x.png" alt="patreon avelino"></a> financial support to Awesome Go</p>

<p>A curated list of awesome Go frameworks, libraries and software. Inspired by <a href="https://github.com/vinta/awesome-python" rel="nofollow">awesome-python</a>.</p>
<h3><a name="contributing" class="anchor" href="#contributing" rel="nofollow" aria-hidden="true"><span class="octicon octicon-link"></span></a>
Contributing</h3>

<p>Please take a quick gander at the <a href="https://github.com/avelino/awesome-go/blob/master/CONTRIBUTING.md" rel="nofollow">contribution guidelines</a> first. Thanks to all <a href="https://github.com/avelino/awesome-go/graphs/contributors" rel="nofollow">contributors</a>; you rock!</p>
<h4><a name="if-you-see-a-package-or-project-here-that-is-no-longer-maintained-or-is-not-a-good-fit-please-submit-a-pull-request-to-improve-this-file-thank-you" class="anchor" href="#if-you-see-a-package-or-project-here-that-is-no-longer-maintained-or-is-not-a-good-fit-please-submit-a-pull-request-to-improve-this-file-thank-you" rel="nofollow" aria-hidden="true"><span class="octicon octicon-link"></span></a>
<em>If you see a package or project here that is no longer maintained or is not a good fit, please submit a pull request to improve this file. Thank you!</em></h4>
<h3><a name="contents" class="anchor" href="#contents" rel="nofollow" aria-hidden="true"><span class="octicon octicon-link"></span></a>
Contents</h3>

<ul>
<li><p><a href="#awesome-go" rel="nofollow">Awesome Go</a></p>

<ul>
<li><a href="#audio-and-music" rel="nofollow">Audio and Music</a></li>
<li><a href="#authentication-and-oauth" rel="nofollow">Authentication and OAuth</a></li>
<li><a href="#bot-building" rel="nofollow">Bot Building</a></li>
<li><a href="#command-line" rel="nofollow">Command Line</a></li>
<li><a href="#configuration" rel="nofollow">Configuration</a></li>
<li><a href="#continuous-integration" rel="nofollow">Continuous Integration</a></li>
<li><a href="#css-preprocessors" rel="nofollow">CSS Preprocessors</a></li>
<li><a href="#data-structures" rel="nofollow">Data Structures</a></li>
<li><a href="#database" rel="nofollow">Database</a></li>
<li><a href="#database-drivers" rel="nofollow">Database Drivers</a></li>
<li><a href="#date-and-time" rel="nofollow">Date and Time</a></li>
<li><a href="#distributed-systems" rel="nofollow">Distributed Systems</a></li>
<li><a href="#email" rel="nofollow">Email</a></li>
<li><a href="#embeddable-scripting-languages" rel="nofollow">Embeddable Scripting Languages</a></li>
<li><a href="#error-handling" rel="nofollow">Error Handling</a></li>
<li><a href="#files" rel="nofollow">Files</a></li>
<li><a href="#financial" rel="nofollow">Financial</a></li>
<li><a href="#forms" rel="nofollow">Forms</a></li>
<li><a href="#functional" rel="nofollow">Functional</a></li>
<li><a href="#game-development" rel="nofollow">Game Development</a></li>
<li><a href="#generation-and-generics" rel="nofollow">Generation and Generics</a></li>
<li><a href="#geographic" rel="nofollow">Geographic</a></li>
<li><a href="#go-compilers" rel="nofollow">Go Compilers</a></li>
<li><a href="#goroutines" rel="nofollow">Goroutines</a></li>
<li><a href="#gui" rel="nofollow">GUI</a></li>
<li><a href="#hardware" rel="nofollow">Hardware</a></li>
<li><a href="#images" rel="nofollow">Images</a></li>
<li><a href="#iot-internet-of-things" rel="nofollow">IoT</a></li>
<li><a href="#job-scheduler" rel="nofollow">Job Scheduler</a></li>
<li><a href="#json" rel="nofollow">JSON</a></li>
<li><a href="#logging" rel="nofollow">Logging</a></li>
<li><a href="#machine-learning" rel="nofollow">Machine Learning</a></li>
<li><a href="#messaging" rel="nofollow">Messaging</a></li>
<li><a href="#microsoft-office" rel="nofollow">Microsoft Office</a>

<ul>
<li><a href="#microsoft-excel" rel="nofollow">Microsoft Excel</a></li>
</ul></li>
<li><a href="#miscellaneous" rel="nofollow">Miscellaneous</a>

<ul>
<li><a href="#dependency-injection" rel="nofollow">Dependency Injection</a></li>
<li><a href="#project-layout" rel="nofollow">Project Layout</a></li>
<li><a href="#strings" rel="nofollow">Strings</a></li>
</ul></li>
<li><a href="#natural-language-processing" rel="nofollow">Natural Language Processing</a></li>
<li><a href="#networking" rel="nofollow">Networking</a>

<ul>
<li><a href="#http-clients" rel="nofollow">HTTP Clients</a></li>
</ul></li>
<li><a href="#opengl" rel="nofollow">OpenGL</a></li>
<li><a href="#orm" rel="nofollow">ORM</a></li>
<li><a href="#package-management" rel="nofollow">Package Management</a></li>
<li><a href="#performance" rel="nofollow">Performance</a></li>
<li><a href="#query-language" rel="nofollow">Query Language</a></li>
<li><a href="#resource-embedding" rel="nofollow">Resource Embedding</a></li>
<li><a href="#science-and-data-analysis" rel="nofollow">Science and Data Analysis</a></li>
<li><a href="#security" rel="nofollow">Security</a></li>
<li><a href="#serialization" rel="nofollow">Serialization</a></li>
<li><a href="#server-applications" rel="nofollow">Server Applications</a></li>
<li><a href="#stream-processing" rel="nofollow">Stream Processing</a></li>
<li><a href="#template-engines" rel="nofollow">Template Engines</a></li>
<li><a href="#testing" rel="nofollow">Testing</a></li>
<li><a href="#text-processing" rel="nofollow">Text Processing</a></li>
<li><a href="#third-party-apis" rel="nofollow">Third-party APIs</a></li>
<li><a href="#utilities" rel="nofollow">Utilities</a></li>
<li><a href="#uuid" rel="nofollow">UUID</a></li>
<li><a href="#validation" rel="nofollow">Validation</a></li>
<li><a href="#version-control" rel="nofollow">Version Control</a></li>
<li><a href="#video" rel="nofollow">Video</a></li>
<li><a href="#web-frameworks" rel="nofollow">Web Frameworks</a>

<ul>
<li><a href="#middlewares" rel="nofollow">Middlewares</a>

<ul>
<li><a href="#actual-middlewares" rel="nofollow">Actual middlewares</a></li>
<li><a href="#libraries-for-creating-http-middlewares" rel="nofollow">Libraries for creating HTTP middlewares</a></li>
</ul></li>
<li><a href="#routers" rel="nofollow">Routers</a></li>
</ul></li>
<li><a href="#windows" rel="nofollow">Windows</a></li>
<li><a href="#xml" rel="nofollow">XML</a></li>
</ul></li>

<li><p><a href="#tools" rel="nofollow">Tools</a></p>

<ul>
<li><a href="#code-analysis" rel="nofollow">Code Analysis</a></li>
<li><a href="#editor-plugins" rel="nofollow">Editor Plugins</a></li>
<li><a href="#go-generate-tools" rel="nofollow">Go Generate Tools</a></li>
<li><a href="#go-tools" rel="nofollow">Go Tools</a></li>
<li><a href="#software-packages" rel="nofollow">Software Packages</a>

<ul>
<li><a href="#devops-tools" rel="nofollow">DevOps Tools</a></li>
<li><a href="#other-software" rel="nofollow">Other Software</a></li>
</ul></li>
</ul></li>

<li><p><a href="#resources" rel="nofollow">Resources</a></p>

<ul>
<li><a href="#benchmarks" rel="nofollow">Benchmarks</a></li>
<li><a href="#conferences" rel="nofollow">Conferences</a></li>
<li><a href="#e-books" rel="nofollow">E-Books</a></li>
<li><a href="#gophers" rel="nofollow">Gophers</a></li>
<li><a href="#meetups" rel="nofollow">Meetups</a></li>
<li><a href="#twitter" rel="nofollow">Twitter</a></li>
<li><a href="#websites" rel="nofollow">Websites</a>

<ul>
<li><a href="#tutorials" rel="nofollow">Tutorials</a></li>
</ul></li>
</ul></li>
</ul>
<h2><a name="audio-and-music" class="anchor" href="#audio-and-music" rel="nofollow" aria-hidden="true"><span class="octicon octicon-link"></span></a>
Audio and Music</h2>

<p><em>Libraries for manipulating audio.</em></p>

<ul>
<li><a href="https://github.com/algoGuy/EasyMIDI" rel="nofollow">EasyMIDI</a> - EasyMidi is a simple and reliable library for working with standard midi file (SMF).</li>
<li><a href="https://github.com/eaburns/flac" rel="nofollow">flac</a> - No-frills native Go FLAC decoder that decodes FLAC files into byte slices.</li>
<li><a href="https://github.com/mewkiz/flac" rel="nofollow">flac</a> - Native Go FLAC encoder/decoder with support for FLAC streams.</li>
<li><a href="https://github.com/Comcast/gaad" rel="nofollow">gaad</a> - Native Go AAC bitstream parser.</li>
<li><a href="https://github.com/krig/go-sox" rel="nofollow">go-sox</a> - libsox bindings for go.</li>
<li><a href="https://github.com/zhulik/go_mediainfo" rel="nofollow">go_mediainfo</a> - libmediainfo bindings for go.</li>
<li><a href="https://github.com/dh1tw/gosamplerate" rel="nofollow">gosamplerate</a> - libsamplerate bindings for go.</li>
<li><a href="https://github.com/bogem/id3v2" rel="nofollow">id3v2</a> - Fast and stable ID3 parsing and writing library for Go.</li>
<li><a href="https://github.com/gen2brain/malgo" rel="nofollow">malgo</a> - Mini audio library.</li>
<li><a href="https://github.com/tosone/minimp3" rel="nofollow">minimp3</a> - Lightweight MP3 decoder library.</li>
<li><a href="https://github.com/go-mix/mix" rel="nofollow">mix</a> - Sequence-based Go-native audio mixer for music apps.</li>
<li><a href="https://github.com/tcolgate/mp3" rel="nofollow">mp3</a> - Native Go MP3 decoder.</li>
<li><a href="https://github.com/go-music-theory/music-theory" rel="nofollow">music-theory</a> - Music theory models in Go.</li>
<li><a href="https://github.com/hajimehoshi/oto" rel="nofollow">Oto</a> - A low-level library to play sound on multiple platforms.</li>
<li><a href="https://github.com/gordonklaus/portaudio" rel="nofollow">PortAudio</a> - Go bindings for the PortAudio audio I/O library.</li>
<li><a href="https://github.com/rakyll/portmidi" rel="nofollow">portmidi</a> - Go bindings for PortMidi.</li>
<li><a href="https://github.com/wtolson/go-taglib" rel="nofollow">taglib</a> - Go bindings for taglib.</li>
<li><a href="https://github.com/mccoyst/vorbis" rel="nofollow">vorbis</a> - &#34;Native&#34; Go Vorbis decoder (uses CGO, but has no dependencies).</li>
<li><a href="https://github.com/mdlayher/waveform" rel="nofollow">waveform</a> - Go package capable of generating waveform images from audio streams.</li>
</ul>
<h2><a name="authentication-and-oauth" class="anchor" href="#authentication-and-oauth" rel="nofollow" aria-hidden="true"><span class="octicon octicon-link"></span></a>
Authentication and OAuth</h2>

<p><em>Libraries for implementing authentications schemes.</em></p>

<ul>
<li><a href="https://github.com/volatiletech/authboss" rel="nofollow">authboss</a> - Modular authentication system for the web. It tries to remove as much boilerplate and &#34;hard things&#34; as possible so that each time you start a new web project in Go, you can plug it in, configure, and start building your app without having to build an authentication system each time.</li>
<li><a href="https://github.com/hako/branca" rel="nofollow">branca</a> - Golang implementation of Branca Tokens.</li>
<li><a href="https://github.com/hsluoyz/casbin" rel="nofollow">casbin</a> - Authorization library that supports access control models like ACL, RBAC, ABAC.</li>
<li><a href="https://github.com/mengzhuo/cookiestxt" rel="nofollow">cookiestxt</a> - provides parser of cookies.txt file format.</li>
<li><a href="https://github.com/square/go-jose" rel="nofollow">go-jose</a> - Fairly complete implementation of the JOSE working group&#39;s JSON Web Token, JSON Web Signatures, and JSON Web Encryption specs.</li>
<li><a href="https://github.com/RichardKnop/go-oauth2-server" rel="nofollow">go-oauth2-server</a> - Standalone, specification-compliant,  OAuth2 server written in Golang.</li>
<li><a href="https://github.com/dghubble/gologin" rel="nofollow">gologin</a> - chainable handlers for login with OAuth1 and OAuth2 authentication providers.</li>
<li><a href="https://github.com/mikespook/gorbac" rel="nofollow">gorbac</a> - provides a lightweight role-based access control (RBAC) implementation in Golang.</li>
<li><a href="https://github.com/markbates/goth" rel="nofollow">goth</a> - provides a simple, clean, and idiomatic way to use OAuth and OAuth2. Handles multiple providers out of the box.</li>
<li><a href="https://github.com/goji/httpauth" rel="nofollow">httpauth</a> - HTTP Authentication middleware.</li>
<li><a href="https://github.com/abraithwaite/jeff" rel="nofollow">jeff</a> - Simple, flexible, secure and idiomatic web session management with pluggable backends.</li>
<li><a href="https://github.com/robbert229/jwt" rel="nofollow">jwt</a> - Clean and easy to use implementation of JSON Web Tokens (JWT).</li>
<li><a href="https://github.com/pascaldekloe/jwt" rel="nofollow">jwt</a> - Lightweight JSON Web Token (JWT) library.</li>
<li><a href="https://github.com/adam-hanna/jwt-auth" rel="nofollow">jwt-auth</a> - JWT middleware for Golang http servers with many configuration options.</li>
<li><a href="https://github.com/dgrijalva/jwt-go" rel="nofollow">jwt-go</a> - Golang implementation of JSON Web Tokens (JWT).</li>
<li><a href="https://github.com/tarent/loginsrv" rel="nofollow">loginsrv</a> - JWT login microservice with plugable backends such as OAuth2 (Github), htpasswd, osiam.</li>
<li><a href="https://github.com/golang/oauth2" rel="nofollow">oauth2</a> - Successor of goauth2. Generic OAuth 2.0 package that comes with JWT, Google APIs, Compute Engine and App Engine support.</li>
<li><a href="https://github.com/openshift/osin" rel="nofollow">osin</a> - Golang OAuth2 server library.</li>
<li><a href="https://github.com/o1egl/paseto" rel="nofollow">paseto</a> - Golang implementation of Platform-Agnostic Security Tokens (PASETO).</li>
<li><a href="https://github.com/xyproto/permissions2" rel="nofollow">permissions2</a> - Library for keeping track of users, login states and permissions. Uses secure cookies and bcrypt.</li>
<li><a href="https://github.com/zpatrick/rbac" rel="nofollow">rbac</a> - Minimalistic RBAC package for Go applications.</li>
<li><a href="https://github.com/SonicRoshan/scope" rel="nofollow">scope</a> - Easily Manage OAuth2 Scopes In Go.</li>
<li><a href="https://github.com/alexedwards/scs" rel="nofollow">scs</a> - Session Manager for HTTP servers.</li>
<li><a href="https://github.com/chmike/securecookie" rel="nofollow">securecookie</a> - Efficient secure cookie encoding/decoding.</li>
<li><a href="https://github.com/icza/session" rel="nofollow">session</a> - Go session management for web servers (including support for Google App Engine - GAE).</li>
<li><a href="https://github.com/f0rmiga/sessiongate-go" rel="nofollow">sessiongate-go</a> - Go session management using the SessionGate Redis module.</li>
<li><a href="https://github.com/adam-hanna/sessions" rel="nofollow">sessions</a> - Dead simple, highly performant, highly customizable sessions service for go http servers.</li>
<li><a href="https://github.com/swithek/sessionup" rel="nofollow">sessionup</a> - Simple, yet effective HTTP session management and identification package.</li>
<li><a href="https://github.com/sashka/signedvalue" rel="nofollow">signedvalue</a> - Signed and timestamped strings compatible with <a href="https://github.com/tornadoweb/tornado" rel="nofollow">Tornado&#39;s</a> <code>create_signed_value</code>, <code>decode_signed_value</code>, and therefore <code>set_secure_cookie</code> and <code>get_secure_cookie</code>.</li>
<li><a href="https://github.com/brianvoe/sjwt" rel="nofollow">sjwt</a> - Simple jwt generator and parser.</li>
</ul>
<h2><a name="bot-building" class="anchor" href="#bot-building" rel="nofollow" aria-hidden="true"><span class="octicon octicon-link"></span></a>
Bot Building</h2>

<p><em>Libraries for building and working with bots.</em></p>

<ul>
<li><a href="https://github.com/go-chat-bot/bot" rel="nofollow">go-chat-bot</a> - IRC, Slack &amp; Telegram bot written in Go.</li>
<li><a href="https://github.com/oklahomer/go-sarah" rel="nofollow">go-sarah</a> - Framework to build bot for desired chat services including LINE, Slack, Gitter and more.</li>
<li><a href="https://github.com/olebedev/go-tgbot" rel="nofollow">go-tgbot</a> - Pure Golang Telegram Bot API wrapper, generated from swagger file, session-based router and middleware.</li>
<li><a href="https://github.com/saniales/golang-crypto-trading-bot" rel="nofollow">Golang CryptoTrading Bot</a> - A golang implementation of a console-based trading bot for cryptocurrency exchanges.</li>
<li><a href="https://github.com/nikepan/govkbot" rel="nofollow">govkbot</a> - Simple Go <a href="https://vk.com" rel="nofollow">VK</a> bot library.</li>
<li><a href="https://github.com/sbstjn/hanu" rel="nofollow">hanu</a> - Framework for writing Slack bots.</li>
<li><a href="https://github.com/stellar/kelp" rel="nofollow">Kelp</a> - official trading and market-making bot for the <a href="https://www.stellar.org/" rel="nofollow">Stellar</a> DEX. Works out-of-the-box, written in Golang, compatible with centralized exchanges and custom trading strategies.</li>
<li><a href="https://github.com/zhulik/margelet" rel="nofollow">margelet</a> - Framework for building Telegram bots.</li>
<li><a href="https://github.com/onrik/micha" rel="nofollow">micha</a> - Go Library for Telegram bot api.</li>
<li><a href="https://github.com/shomali11/slacker" rel="nofollow">slacker</a> - Easy to use framework to create Slack bots.</li>
<li><a href="https://github.com/alexandre-normand/slackscot" rel="nofollow">slackscot</a> - Another framework for building Slack bots.</li>
<li><a href="https://github.com/yanzay/tbot" rel="nofollow">tbot</a> - Telegram bot server with API similar to net/http.</li>
<li><a href="https://github.com/tucnak/telebot" rel="nofollow">telebot</a> - Telegram bot framework written in Go.</li>
<li><a href="https://github.com/Syfaro/telegram-bot-api" rel="nofollow">telegram-bot-api</a> - Simple and clean Telegram bot client.</li>
<li><a href="https://github.com/kyleterry/tenyks" rel="nofollow">Tenyks</a> - Service oriented IRC bot using Redis and JSON for messaging.</li>
</ul>
<h2><a name="command-line" class="anchor" href="#command-line" rel="nofollow" aria-hidden="true"><span class="octicon octicon-link"></span></a>
Command Line</h2>
<h3><a name="standard-cli" class="anchor" href="#standard-cli" rel="nofollow" aria-hidden="true"><span class="octicon octicon-link"></span></a>
Standard CLI</h3>

<p><em>Libraries for building standard or basic Command Line applications.</em></p>

<ul>
<li><a href="https://github.com/akamensky/argparse" rel="nofollow">argparse</a> - Command line argument parser inspired by Python&#39;s argparse module.</li>
<li><a href="https://github.com/cosiner/argv" rel="nofollow">argv</a> - Go library to split command line string as arguments array using the bash syntax.</li>
<li><a href="https://github.com/mkideal/cli" rel="nofollow">cli</a> - Feature-rich and easy to use command-line package based on golang struct tags.</li>
<li><a href="https://github.com/teris-io/cli" rel="nofollow">cli</a> - Simple and complete API for building command line interfaces in Go.</li>
<li><a href="https://github.com/tcnksm/gcli" rel="nofollow">cli-init</a> - The easy way to start building Golang command line applications.</li>
<li><a href="http://github.com/tucnak/climax" rel="nofollow">climax</a> - Alternative CLI with &#34;human face&#34;, in spirit of Go command.</li>
<li><a href="https://github.com/hedzr/cmdr" rel="nofollow">cmdr</a> - A POSIX/GNU style, getopt-like command-line UI Go library.</li>
<li><a href="https://github.com/spf13/cobra" rel="nofollow">cobra</a> - Commander for modern Go CLI interactions.</li>
<li><a href="https://github.com/jaffee/commandeer" rel="nofollow">commandeer</a> - Dev-friendly CLI apps: sets up flags, defaults, and usage based on struct fields and tags.</li>
<li><a href="https://github.com/posener/complete" rel="nofollow">complete</a> - Write bash completions in Go + Go command bash completion.</li>
<li><a href="https://github.com/dnote/dnote" rel="nofollow">Dnote</a> - A simple and end-to-end encrypted notebook for developers.</li>
<li><a href="https://github.com/docopt/docopt.go" rel="nofollow">docopt.go</a> - Command-line arguments parser that will make you smile.</li>
<li><a href="https://github.com/codingconcepts/env" rel="nofollow">env</a> - Tag-based environment configuration for structs.</li>
<li><a href="https://github.com/cosiner/flag" rel="nofollow">flag</a> - Simple but powerful command line option parsing library for Go supporting subcommand.</li>
<li><a href="https://github.com/integrii/flaggy" rel="nofollow">flaggy</a> - A robust and idiomatic flags package with excellent subcommand support.</li>
<li><a href="https://github.com/sgreben/flagvar" rel="nofollow">flagvar</a> - A collection of flag argument types for Go&#39;s standard <code>flag</code> package.</li>
<li><a href="https://github.com/alexflint/go-arg" rel="nofollow">go-arg</a> - Struct-based argument parsing in Go.</li>
<li><a href="https://github.com/yitsushi/go-commander" rel="nofollow">go-commander</a> - Go library to simplify CLI workflow.</li>
<li><a href="https://github.com/jessevdk/go-flags" rel="nofollow">go-flags</a> - go command line option parser.</li>
<li><a href="https://github.com/DavidGamba/go-getoptions" rel="nofollow">go-getoptions</a> - Go option parser inspired on the flexibility of Perl’s GetOpt::Long.</li>
<li><a href="https://github.com/devfacet/gocmd" rel="nofollow">gocmd</a> - Go library for building command line applications.</li>
<li><a href="https://github.com/hidevopsio/hiboot/tree/master/pkg/app/cli" rel="nofollow">hiboot cli</a> - cli application framework with auto configuration and dependency injection.</li>
<li><a href="https://github.com/liujianping/job" rel="nofollow">job</a> - JOB, make your short-term command as a long-term job.</li>
<li><a href="https://github.com/alecthomas/kingpin" rel="nofollow">kingpin</a> - Command line and flag parser supporting sub commands.</li>
<li><a href="https://github.com/peterh/liner" rel="nofollow">liner</a> - Go readline-like library for command-line interfaces.</li>
<li><a href="https://github.com/mitchellh/cli" rel="nofollow">mitchellh/cli</a> - Go library for implementing command-line interfaces.</li>
<li><a href="https://github.com/jawher/mow.cli" rel="nofollow">mow.cli</a> - Go library for building CLI applications with sophisticated flag and argument parsing and validation.</li>
<li><a href="https://github.com/nanovms/ops" rel="nofollow">ops</a> - Unikernel Builder/Orchestrator.</li>
<li><a href="https://github.com/spf13/pflag" rel="nofollow">pflag</a> - Drop-in replacement for Go&#39;s flag package, implementing POSIX/GNU-style --flags.</li>
<li><a href="https://github.com/chzyer/readline" rel="nofollow">readline</a> - Pure golang implementation that provides most features in GNU-Readline under MIT license.</li>
<li><a href="https://github.com/Zaba505/sand" rel="nofollow">sand</a> - Simple API for creating interpreters and so much more.</li>
<li><a href="https://github.com/octago/sflags" rel="nofollow">sflags</a> - Struct based flags generator for flag, urfave/cli, pflag, cobra, kingpin and other libraries.</li>
<li><a href="https://github.com/antham/strumt" rel="nofollow">strumt</a> - Library to create prompt chain.</li>
<li><a href="https://github.com/liujianping/ts" rel="nofollow">ts</a> - Timestamp convert &amp; compare tool.</li>
<li><a href="https://github.com/ukautz/clif" rel="nofollow">ukautz/clif</a> - Small command line interface framework.</li>
<li><a href="https://github.com/urfave/cli" rel="nofollow">urfave/cli</a> - Simple, fast, and fun package for building command line apps in Go (formerly codegangsta/cli).</li>
<li><a href="https://github.com/dixonwille/wlog" rel="nofollow">wlog</a> - Simple logging interface that supports cross-platform color and concurrency.</li>
<li><a href="https://github.com/dixonwille/wmenu" rel="nofollow">wmenu</a> - Easy to use menu structure for cli applications that prompts users to make choices.</li>
</ul>
<h3><a name="advanced-console-uis" class="anchor" href="#advanced-console-uis" rel="nofollow" aria-hidden="true"><span class="octicon octicon-link"></span></a>
Advanced Console UIs</h3>

<p><em>Libraries for building Console Applications and Console User Interfaces.</em></p>

<ul>
<li><a href="https://github.com/guptarohit/asciigraph" rel="nofollow">asciigraph</a> - Go package to make lightweight ASCII line graph ╭┈╯ in command line apps with no other dependencies.</li>
<li><a href="https://github.com/logrusorgru/aurora" rel="nofollow">aurora</a> - ANSI terminal colors that supports fmt.Printf/Sprintf.</li>
<li><a href="https://github.com/mingrammer/cfmt" rel="nofollow">cfmt</a> - Contextual fmt inspired by bootstrap color classes.</li>
<li><a href="https://github.com/ttacon/chalk" rel="nofollow">chalk</a> - Intuitive package for prettifying terminal/console output.</li>
<li><a href="https://github.com/fatih/color" rel="nofollow">color</a> - Versatile package for colored terminal output.</li>
<li><a href="https://github.com/TreyBastian/colourize" rel="nofollow">colourize</a> - Go library for ANSI colour text in terminals.</li>
<li><a href="https://github.com/wzshiming/ctc" rel="nofollow">ctc</a> - The non-invasive cross-platform terminal color library does not need to modify the Print method.</li>
<li><a href="https://github.com/workanator/go-ataman" rel="nofollow">go-ataman</a> - Go library for rendering ANSI colored text templates in terminals.</li>
<li><a href="https://github.com/mattn/go-colorable" rel="nofollow">go-colorable</a> - Colorable writer for windows.</li>
<li><a href="https://github.com/daviddengcn/go-colortext" rel="nofollow">go-colortext</a> - Go library for color output in terminals.</li>
<li><a href="https://github.com/mattn/go-isatty" rel="nofollow">go-isatty</a> - isatty for golang.</li>
<li><a href="https://github.com/c-bata/go-prompt" rel="nofollow">go-prompt</a> - Library for building a powerful interactive prompt, inspired by <a href="https://github.com/jonathanslenders/python-prompt-toolkit" rel="nofollow">python-prompt-toolkit</a>.</li>
<li><a href="https://github.com/jroimartin/gocui" rel="nofollow">gocui</a> - Minimalist Go library aimed at creating Console User Interfaces.</li>
<li><a href="https://github.com/labstack/gommon/tree/master/color" rel="nofollow">gommon/color</a> - Style terminal text.</li>
<li><a href="https://github.com/gookit/color" rel="nofollow">gookit/color</a> - Terminal color rendering tool library, support 16 colors, 256 colors, RGB color rendering output, compatible with Windows.</li>
<li><a href="https://github.com/vbauerster/mpb" rel="nofollow">mpb</a> - Multi progress bar for terminal applications.</li>
<li><a href="https://github.com/schollz/progressbar" rel="nofollow">progressbar</a> - Basic thread-safe progress bar that works in every OS.</li>
<li><a href="https://github.com/alexeyco/simpletable" rel="nofollow">simpletable</a> - Simple tables in terminal with Go.</li>
<li><a href="https://github.com/cheynewallace/tabby" rel="nofollow">tabby</a> - A tiny library for super simple Golang tables.</li>
<li><a href="https://github.com/InVisionApp/tabular" rel="nofollow">tabular</a> - Print ASCII tables from command line utilities without the need to pass large sets of data to the API.</li>
<li><a href="https://github.com/nsf/termbox-go" rel="nofollow">termbox-go</a> - Termbox is a library for creating cross-platform text-based interfaces.</li>
<li><a href="https://github.com/mum4k/termdash" rel="nofollow">termdash</a> - Go terminal dashboard based on <strong>termbox-go</strong> and inspired by <a href="https://github.com/gizak/termui" rel="nofollow">termui</a>.</li>
<li><a href="https://github.com/apcera/termtables" rel="nofollow">termtables</a> - Go port of the Ruby library <a href="https://github.com/tj/terminal-table" rel="nofollow">terminal-tables</a> for simple ASCII table generation as well as providing markdown and HTML output.</li>
<li><a href="https://github.com/gizak/termui" rel="nofollow">termui</a> - Go terminal dashboard based on <strong>termbox-go</strong> and inspired by <a href="https://github.com/yaronn/blessed-contrib" rel="nofollow">blessed-contrib</a>.</li>
<li><a href="https://github.com/gosuri/uilive" rel="nofollow">uilive</a> - Library for updating terminal output in realtime.</li>
<li><a href="https://github.com/gosuri/uiprogress" rel="nofollow">uiprogress</a> - Flexible library to render progress bars in terminal applications.</li>
<li><a href="https://github.com/gosuri/uitable" rel="nofollow">uitable</a> - Library to improve readability in terminal apps using tabular data.</li>
</ul>
<h2><a name="configuration" class="anchor" href="#configuration" rel="nofollow" aria-hidden="true"><span class="octicon octicon-link"></span></a>
Configuration</h2>

<p><em>Libraries for configuration parsing.</em></p>

<ul>
<li><a href="https://github.com/JeremyLoy/config" rel="nofollow">config</a> - Cloud native application configuration. Bind ENV to structs in only two lines.</li>
<li><a href="https://github.com/olebedev/config" rel="nofollow">config</a> - JSON or YAML configuration wrapper with environment variables and flags parsing.</li>
<li><a href="https://github.com/paked/configure" rel="nofollow">configure</a> - Provides configuration through multiple sources, including JSON, flags and environment variables.</li>
<li><a href="https://github.com/heetch/confita" rel="nofollow">confita</a> - Load configuration in cascade from multiple backends into a struct.</li>
<li><a href="https://github.com/the4thamigo-uk/conflate" rel="nofollow">conflate</a> - Library/tool to merge multiple JSON/YAML/TOML files from arbitrary URLs, validation against a JSON schema, and application of default values defined in the schema.</li>
<li><a href="https://github.com/caarlos0/env" rel="nofollow">env</a> - Parse environment variables to Go structs (with defaults).</li>
<li><a href="https://github.com/tomazk/envcfg" rel="nofollow">envcfg</a> - Un-marshaling environment variables to Go structs.</li>
<li><a href="https://github.com/ian-kent/envconf" rel="nofollow">envconf</a> - Configuration from environment.</li>
<li><a href="https://github.com/vrischmann/envconfig" rel="nofollow">envconfig</a> - Read your configuration from environment variables.</li>
<li><a href="https://github.com/antham/envh" rel="nofollow">envh</a> - Helpers to manage environment variables.</li>
<li><a href="https://github.com/go-gcfg/gcfg" rel="nofollow">gcfg</a> - read INI-style configuration files into Go structs; supports user-defined types and subsections.</li>
<li><a href="https://github.com/sakirsensoy/genv" rel="nofollow">genv</a> - Read environment variables easily with dotenv support.</li>
<li><a href="https://github.com/ufoscout/go-up" rel="nofollow">go-up</a> - A simple configuration library with recursive placeholders resolution and no magic.</li>
<li><a href="https://github.com/crgimenes/goConfig" rel="nofollow">goConfig</a> - Parses a struct as input and populates the fields of this struct with parameters from command line, environment variables and configuration file.</li>
<li><a href="https://github.com/joho/godotenv" rel="nofollow">godotenv</a> - Go port of Ruby&#39;s dotenv library (Loads environment variables from <code>.env</code>).</li>
<li><a href="https://github.com/ian-kent/gofigure" rel="nofollow">gofigure</a> - Go application configuration made easy.</li>
<li><a href="https://github.com/One-com/gone/tree/master/jconf" rel="nofollow">gone/jconf</a> - Modular JSON configuration. Keep you config structs along with the code they configure and delegate parsing to submodules without sacrificing full config serialization.</li>
<li><a href="https://github.com/gookit/config" rel="nofollow">gookit/config</a> - application config manage(load,get,set). support JSON, YAML, TOML, INI, HCL. multi file load, data override merge.</li>
<li><a href="https://github.com/beatlabs/harvester" rel="nofollow">harvester</a> - Harvester, a easy to use static and dynamic configuration package supportig seeding, env vars and Consul integration.</li>
<li><a href="https://github.com/hjson/hjson-go" rel="nofollow">hjson</a> - Human JSON, a configuration file format for humans. Relaxed syntax, fewer mistakes, more comments.</li>
<li><a href="https://github.com/schachmat/ingo" rel="nofollow">ingo</a> - Flags persisted in an ini-like config file.</li>
<li><a href="https://github.com/go-ini/ini" rel="nofollow">ini</a> - Go package to read and write INI files.</li>
<li><a href="https://github.com/joshbetz/config" rel="nofollow">joshbetz/config</a> - Small configuration library for Go that parses environment variables, JSON files, and reloads automatically on SIGHUP.</li>
<li><a href="https://github.com/kelseyhightower/envconfig" rel="nofollow">kelseyhightower/envconfig</a> - Go library for managing configuration data from environment variables.</li>
<li><a href="https://github.com/knadh/koanf" rel="nofollow">koanf</a> - Light weight, extensible library for reading config in Go applications. Built in support for JSON, TOML, YAML, env, command line.</li>
<li><a href="https://github.com/lalamove/konfig" rel="nofollow">konfig</a> - Composable, observable and performant config handling for Go for the distributed processing era.</li>
<li><a href="https://github.com/sasbury/mini" rel="nofollow">mini</a> - Golang package for parsing ini-style configuration files.</li>
<li><a href="https://github.com/nasermirzaei89/env" rel="nofollow">nasermirzaei89/env</a> - Simple useful package for read environment variables.</li>
<li><a href="https://github.com/oblq/sprbox" rel="nofollow">sprbox</a> - Build-environment aware toolbox factory and agnostic config parser (YAML, TOML, JSON and Environment vars).</li>
<li><a href="https://github.com/tucnak/store" rel="nofollow">store</a> - Lightweight configuration manager for Go.</li>
<li><a href="https://github.com/spf13/viper" rel="nofollow">viper</a> - Go configuration with fangs.</li>
<li><a href="https://github.com/OpenPeeDeeP/xdg" rel="nofollow">xdg</a> - Cross platform package that follows the <a href="https://standards.freedesktop.org/basedir-spec/basedir-spec-latest.html" rel="nofollow">XDG Standard</a>.</li>
</ul>
<h2><a name="continuous-integration" class="anchor" href="#continuous-integration" rel="nofollow" aria-hidden="true"><span class="octicon octicon-link"></span></a>
Continuous Integration</h2>

<p><em>Tools for help with continuous integration.</em></p>

<ul>
<li><a href="https://github.com/drone/drone" rel="nofollow">drone</a> - Drone is a Continuous Integration platform built on Docker, written in Go.</li>
<li><a href="https://github.com/duck8823/duci" rel="nofollow">duci</a> - A simple ci server no needs domain specific languages.</li>
<li><a href="https://github.com/nikogura/gomason" rel="nofollow">gomason</a> - Test, Build, Sign, and Publish your go binaries from a clean workspace.</li>
<li><a href="https://github.com/mattn/goveralls" rel="nofollow">goveralls</a> - Go integration for Coveralls.io continuous code coverage tracking system.</li>
<li><a href="https://github.com/go-playground/overalls" rel="nofollow">overalls</a> - Multi-Package go project coverprofile for tools like goveralls.</li>
<li><a href="https://github.com/LawrenceWoodman/roveralls" rel="nofollow">roveralls</a> - Recursive coverage testing tool.</li>
</ul>
<h2><a name="css-preprocessors" class="anchor" href="#css-preprocessors" rel="nofollow" aria-hidden="true"><span class="octicon octicon-link"></span></a>
CSS Preprocessors</h2>

<p><em>Libraries for preprocessing CSS files.</em></p>

<ul>
<li><a href="https://github.com/yosssi/gcss" rel="nofollow">gcss</a> - Pure Go CSS Preprocessor.</li>
<li><a href="https://github.com/wellington/go-libsass" rel="nofollow">go-libsass</a> - Go wrapper to the 100% Sass compatible libsass project.</li>
</ul>
<h2><a name="data-structures" class="anchor" href="#data-structures" rel="nofollow" aria-hidden="true"><span class="octicon octicon-link"></span></a>
Data Structures</h2>

<p><em>Generic datastructures and algorithms in Go.</em></p>

<ul>
<li><a href="https://github.com/shady831213/algorithms" rel="nofollow">algorithms</a> - Algorithms and data structures.CLRS study.</li>
<li><a href="https://github.com/zhuangsirui/binpacker" rel="nofollow">binpacker</a> - Binary packer and unpacker helps user build custom binary stream.</li>
<li><a href="https://github.com/yourbasic/bit" rel="nofollow">bit</a> - Golang set data structure with bonus bit-twiddling functions.</li>
<li><a href="https://github.com/willf/bitset" rel="nofollow">bitset</a> - Go package implementing bitsets.</li>
<li><a href="https://github.com/zhenjl/bloom" rel="nofollow">bloom</a> - Bloom filters implemented in Go.</li>
<li><a href="https://github.com/yourbasic/bloom" rel="nofollow">bloom</a> - Golang Bloom filter implementation.</li>
<li><a href="https://github.com/tylertreat/BoomFilters" rel="nofollow">boomfilters</a> - Probabilistic data structures for processing continuous, unbounded streams.</li>
<li><a href="https://github.com/free/concurrent-writer" rel="nofollow">concurrent-writer</a> - Highly concurrent drop-in replacement for <code>bufio.Writer</code>.</li>
<li><a href="https://github.com/InVisionApp/conjungo" rel="nofollow">conjungo</a> - A small, powerful and flexible merge library.</li>
<li><a href="https://github.com/seiflotfy/count-min-log" rel="nofollow">count-min-log</a> - Go implementation Count-Min-Log sketch: Approximately counting with approximate counters (Like Count-Min sketch but using less memory).</li>
<li><a href="https://github.com/superwhiskers/crunch" rel="nofollow">crunch</a> - Go package implementing buffers for handling various datatypes easily.</li>
<li><a href="https://github.com/seiflotfy/cuckoofilter" rel="nofollow">cuckoofilter</a> - Cuckoo filter: a good alternative to a counting bloom filter implemented in Go.</li>
<li><a href="https://github.com/edwingeng/deque" rel="nofollow">deque</a> - A highly optimized double-ended queue.</li>
<li><a href="https://github.com/gammazero/deque" rel="nofollow">deque</a> - Fast ring-buffer deque (double-ended queue).</li>
<li><a href="https://github.com/srfrog/dict" rel="nofollow">dict</a> - Python-like dictionaries (dict) for Go.</li>
<li><a href="https://github.com/zhenjl/encoding" rel="nofollow">encoding</a> - Integer Compression Libraries for Go.</li>
<li><a href="https://github.com/plar/go-adaptive-radix-tree" rel="nofollow">go-adaptive-radix-tree</a> - Go implementation of Adaptive Radix Tree.</li>
<li><a href="https://github.com/Workiva/go-datastructures" rel="nofollow">go-datastructures</a> - Collection of useful, performant, and thread-safe data structures.</li>
<li><a href="https://github.com/amallia/go-ef" rel="nofollow">go-ef</a> - A Go implementation of the Elias-Fano encoding.</li>
<li><a href="https://github.com/hailocab/go-geoindex" rel="nofollow">go-geoindex</a> - In-memory geo index.</li>
<li><a href="https://github.com/OrlovEvgeny/go-mcache" rel="nofollow">go-mcache</a> - Fast in-memory key:value store/cache library. Pointer caches.</li>
<li><a href="https://github.com/aurelien-rainone/go-rquad" rel="nofollow">go-rquad</a> - Region quadtrees with efficient point location and neighbour finding.</li>
<li><a href="https://github.com/enriquebris/goconcurrentqueue" rel="nofollow">goconcurrentqueue</a> - Concurrent FIFO queue.</li>
<li><a href="https://github.com/emirpasic/gods" rel="nofollow">gods</a> - Go Data Structures. Containers, Sets, Lists, Stacks, Maps, BidiMaps, Trees, HashSet etc.</li>
<li><a href="https://github.com/xxjwxc/gofal" rel="nofollow">gofal</a> - fractional api for Go.</li>
<li><a href="https://github.com/deckarep/golang-set" rel="nofollow">golang-set</a> - Thread-Safe and Non-Thread-Safe high-performance sets for Go.</li>
<li><a href="https://github.com/zoumo/goset" rel="nofollow">goset</a> - A useful Set collection implementation for Go.</li>
<li><a href="https://github.com/ryszard/goskiplist" rel="nofollow">goskiplist</a> - Skip list implementation in Go.</li>
<li><a href="https://github.com/kniren/gota" rel="nofollow">gota</a> - Implementation of dataframes, series, and data wrangling methods for Go.</li>
<li><a href="https://github.com/emvi/hide" rel="nofollow">hide</a> - ID type with marshalling to/from hash to prevent sending IDs to clients.</li>
<li><a href="https://github.com/google/hilbert" rel="nofollow">hilbert</a> - Go package for mapping values to and from space-filling curves, such as Hilbert and Peano curves.</li>
<li><a href="https://github.com/axiomhq/hyperloglog" rel="nofollow">hyperloglog</a> - HyperLogLog implementation with Sparse, LogLog-Beta bias correction and TailCut space reduction.</li>
<li><a href="https://github.com/agext/levenshtein" rel="nofollow">levenshtein</a> - Levenshtein distance and similarity metrics with customizable edit costs and Winkler-like bonus for common prefix.</li>
<li><a href="https://github.com/agnivade/levenshtein" rel="nofollow">levenshtein</a> - Implementation to calculate levenshtein distance in Go.</li>
<li><a href="https://github.com/smartystreets/mafsa" rel="nofollow">mafsa</a> - MA-FSA implementation with Minimal Perfect Hashing.</li>
<li><a href="https://github.com/cbergoon/merkletree" rel="nofollow">merkletree</a> - Implementation of a merkle tree providing an efficient and secure verification of the contents of data structures.</li>
<li><a href="https://github.com/BlackRabbitt/mspm" rel="nofollow">mspm</a> - Multi-String Pattern Matching Algorithm for information retrieval.</li>
<li><a href="https://github.com/emvi/null" rel="nofollow">null</a> - Nullable Go types that can be marshalled/unmarshalled to/from JSON.</li>
<li><a href="https://github.com/MonaxGT/parsefields" rel="nofollow">parsefields</a> - Tools for parse JSON-like logs for collecting unique fields and events.</li>
<li><a href="https://github.com/hyfather/pipeline" rel="nofollow">pipeline</a> - An implementation of pipelines with fan-in and fan-out.</li>
<li><a href="https://github.com/viant/ptrie" rel="nofollow">ptrie</a> - An implementation of prefix tree.</li>
<li><a href="https://github.com/rocketlaunchr/remember-go" rel="nofollow">remember-go</a> - A universal interface for caching data (redis, memory, memcached etc).</li>
<li><a href="https://github.com/TheTannerRyan/ring" rel="nofollow">ring</a> - Go implementation of a high performance, thread safe bloom filter.</li>
<li><a href="https://github.com/RoaringBitmap/roaring" rel="nofollow">roaring</a> - Go package implementing compressed bitsets.</li>
<li><a href="https://github.com/StudioSol/set" rel="nofollow">set</a> - Simple set data structure implementation in Go using LinkedHashMap.</li>
<li><a href="https://github.com/MauriceGit/skiplist" rel="nofollow">skiplist</a> - Very fast Go Skiplist implementation.</li>
<li><a href="https://github.com/gansidui/skiplist" rel="nofollow">skiplist</a> - Skiplist implementation in Go.</li>
<li><a href="https://github.com/zekroTJA/timedmap" rel="nofollow">timedmap</a> - Map with expiring key-value pairs.</li>
<li><a href="https://github.com/perdata/treap" rel="nofollow">treap</a> - Persistent, fast ordered map using tree heaps.</li>
<li><a href="https://github.com/derekparker/trie" rel="nofollow">trie</a> - Trie implementation in Go.</li>
<li><a href="https://github.com/diegobernardes/ttlcache" rel="nofollow">ttlcache</a> - In-memory LRU string-interface{} map with expiration for golang.</li>
<li><a href="https://github.com/gurukami/typ" rel="nofollow">typ</a> - Null Types, Safe primitive type conversion and fetching value from complex structures.</li>
<li><a href="https://github.com/willf/bloom" rel="nofollow">willf/bloom</a> - Go package implementing Bloom filters.</li>
</ul>
<h2><a name="database" class="anchor" href="#database" rel="nofollow" aria-hidden="true"><span class="octicon octicon-link"></span></a>
Database</h2>

<p><em>Databases implemented in Go.</em></p>

<ul>
<li><a href="https://github.com/dgraph-io/badger" rel="nofollow">badger</a> - Fast key-value store in Go.</li>
<li><a href="https://github.com/iwanbk/bcache" rel="nofollow">bcache</a> - Eventually consistent distributed in-memory  cache Go library.</li>
<li><a href="https://github.com/allegro/bigcache" rel="nofollow">BigCache</a> - Efficient key/value cache for gigabytes of data.</li>
<li><a href="https://github.com/prologic/bitcask" rel="nofollow">Bitcask</a> - Bitcask is an embeddable, persistent and fast key-value (KV) database written in pure Go with predictable read/write performance, low latency and high throughput thanks to the bitcask on-disk layout (LSM+WAL).</li>
<li><a href="https://github.com/boltdb/bolt" rel="nofollow">bolt</a> - Low-level key/value database for Go.</li>
<li><a href="https://github.com/tidwall/buntdb" rel="nofollow">buntdb</a> - Fast, embeddable, in-memory key/value database for Go with custom indexing and spatial support.</li>
<li><a href="https://github.com/akyoto/cache" rel="nofollow">cache</a> - In-memory key:value store with expiration time, 0 dependencies, &lt;100 LoC, 100% coverage.</li>
<li><a href="https://github.com/muesli/cache2go" rel="nofollow">cache2go</a> - In-memory key:value cache which supports automatic invalidation based on timeouts.</li>
<li><a href="https://github.com/oaStuff/clusteredBigCache" rel="nofollow">clusteredBigCache</a> - BigCache with clustering support and individual item expiration.</li>
<li><a href="https://github.com/cockroachdb/cockroach" rel="nofollow">cockroach</a> - Scalable, Geo-Replicated, Transactional Datastore.</li>
<li><a href="https://github.com/codingsince1985/couchcache" rel="nofollow">couchcache</a> - RESTful caching micro-service backed by Couchbase server.</li>
<li><a href="https://github.com/CovenantSQL/CovenantSQL" rel="nofollow">CovenantSQL</a> - CovenantSQL is a SQL database on blockchain.</li>
<li><a href="https://github.com/dgraph-io/dgraph" rel="nofollow">dgraph</a> - Scalable, Distributed, Low Latency, High Throughput Graph Database.</li>
<li><a href="https://github.com/peterbourgon/diskv" rel="nofollow">diskv</a> - Home-grown disk-backed key-value store.</li>
<li><a href="https://github.com/krotik/eliasdb" rel="nofollow">eliasdb</a> - Dependency-free, transactional graph database with REST API, phrase search and SQL-like query language.</li>
<li><a href="https://github.com/VictoriaMetrics/fastcache" rel="nofollow">fastcache</a> - fast thread-safe inmemory cache for big number of entries. Minimizes GC overhead.</li>
<li><a href="https://github.com/bluele/gcache" rel="nofollow">GCache</a> - Cache library with support for expirable Cache, LFU, LRU and ARC.</li>
<li><a href="https://github.com/pmylund/go-cache" rel="nofollow">go-cache</a> - In-memory key:value store/cache (similar to Memcached) library for Go, suitable for single-machine applications.</li>
<li><a href="https://github.com/syndtr/goleveldb" rel="nofollow">goleveldb</a> - Implementation of the <a href="https://github.com/google/leveldb" rel="nofollow">LevelDB</a> key/value database in Go.</li>
<li><a href="https://github.com/kapitan-k/gorocksdb" rel="nofollow">gorocksdb</a> - Gorocksdb is a wrapper for <a href="https://rocksdb.org" rel="nofollow">RocksDB</a> written in Go.</li>
<li><a href="https://github.com/golang/groupcache" rel="nofollow">groupcache</a> - Groupcache is a caching and cache-filling library, intended as a replacement for memcached in many cases.</li>
<li><a href="https://github.com/influxdb/influxdb" rel="nofollow">influxdb</a> - Scalable datastore for metrics, events, and real-time analytics.</li>
<li><a href="https://github.com/go-kivik/kivik" rel="nofollow">Kivik</a> - Kivik provides a common Go and GopherJS client library for CouchDB, PouchDB, and similar databases.</li>
<li><a href="https://github.com/siddontang/ledisdb" rel="nofollow">ledisdb</a> - Ledisdb is a high performance NoSQL like Redis based on LevelDB.</li>
<li><a href="https://github.com/jmhodges/levigo" rel="nofollow">levigo</a> - Levigo is a Go wrapper for LevelDB.</li>
<li><a href="https://github.com/couchbase/moss" rel="nofollow">moss</a> - Moss is a simple LSM key-value storage engine written in 100% Go.</li>
<li><a href="https://github.com/xujiajun/nutsdb" rel="nofollow">nutsdb</a> - Nutsdb is a simple, fast, embeddable, persistent key/value store written in pure Go. It supports fully serializable transactions and many data structures such as  list, set, sorted set.</li>
<li><a href="https://github.com/fern4lvarez/piladb" rel="nofollow">piladb</a> - Lightweight RESTful database engine based on stack data structures.</li>
<li><a href="https://github.com/prometheus/prometheus" rel="nofollow">prometheus</a> - Monitoring system and time series database.</li>
<li><a href="https://github.com/recoilme/pudge" rel="nofollow">pudge</a> - Fast and simple  key/value store written using Go&#39;s standard library.</li>
<li><a href="https://github.com/rqlite/rqlite" rel="nofollow">rqlite</a> - The lightweight, distributed, relational database built on SQLite.</li>
<li><a href="https://github.com/nanobox-io/golang-scribble" rel="nofollow">Scribble</a> - Tiny flat file JSON store.</li>
<li><a href="https://github.com/recoilme/slowpoke" rel="nofollow">slowpoke</a> - Key-value store with persistence.</li>
<li><a href="https://github.com/rafaeljesus/tempdb" rel="nofollow">tempdb</a> - Key-value store for temporary items.</li>
<li><a href="https://github.com/pingcap/tidb" rel="nofollow">tidb</a> - TiDB is a distributed SQL database. Inspired by the design of Google F1.</li>
<li><a href="https://github.com/HouzuoGuo/tiedot" rel="nofollow">tiedot</a> - Your NoSQL database powered by Golang.</li>
<li><a href="https://github.com/chrislusf/vasto" rel="nofollow">Vasto</a> - A distributed high-performance key-value store. On Disk. Eventual consistent. HA. Able to grow or shrink without service interruption.</li>
<li><a href="https://github.com/VictoriaMetrics/VictoriaMetrics" rel="nofollow">VictoriaMetrics</a> - fast, resource-effective and scalable open source time series database. May be used as long-term remote storage for Prometheus. Supports PromQL.</li>
</ul>

<p><em>Database schema migration.</em></p>

<ul>
<li><a href="https://github.com/khezen/avro" rel="nofollow">avro</a> - Discover SQL schemas and convert them to AVRO schemas. Query SQL records into AVRO bytes.</li>
<li><a href="https://github.com/GuiaBolso/darwin" rel="nofollow">darwin</a> - Database schema evolution library for Go.</li>
<li><a href="https://github.com/RichardKnop/go-fixtures" rel="nofollow">go-fixtures</a> - Django style fixtures for Golang&#39;s excellent built-in database/sql library.</li>
<li><a href="https://github.com/robinjoseph08/go-pg-migrations" rel="nofollow">go-pg-migrations</a> - A Go package to help write migrations with go-pg/pg.</li>
<li><a href="https://github.com/emvi/gondolier" rel="nofollow">gondolier</a> - Database migration library using struct decorators.</li>
<li><a href="https://github.com/steinbacher/goose" rel="nofollow">goose</a> - Database migration tool. You can manage your database&#39;s evolution by creating incremental SQL or Go scripts.</li>
<li><a href="https://github.com/go-gormigrate/gormigrate" rel="nofollow">gormigrate</a> - Database schema migration helper for Gorm ORM.</li>
<li><a href="https://github.com/golang-migrate/migrate" rel="nofollow">migrate</a> - Database migrations. CLI and Golang library.</li>
<li><a href="https://github.com/lopezator/migrator" rel="nofollow">migrator</a> - Dead simple Go database migration library.</li>
<li><a href="https://github.com/pravasan/pravasan" rel="nofollow">pravasan</a> - Simple Migration tool - currently for MySQL but planning to soon support Postgres, SQLite, MongoDB, etc.</li>
<li><a href="https://github.com/adlio/schema" rel="nofollow">schema</a> - Library to embed schema migrations for database/sql-compatible databases inside your Go binaries.</li>
<li><a href="https://github.com/skeema/skeema" rel="nofollow">skeema</a> - Pure-SQL schema management system for MySQL, with support for sharding and external online schema change tools.</li>
<li><a href="https://github.com/gobuffalo/pop/tree/master/soda" rel="nofollow">soda</a> - Database migration, creation, ORM, etc... for MySQL, PostgreSQL, and SQLite.</li>
<li><a href="https://github.com/rubenv/sql-migrate" rel="nofollow">sql-migrate</a> - Database migration tool. Allows embedding migrations into the application using go-bindata.</li>
</ul>

<p><em>Database tools.</em></p>

<ul>
<li><a href="https://github.com/PumpkinSeed/bucket" rel="nofollow">bucket</a> - Optimized data structure framework for Couchbase specialized on one bucket usage.</li>
<li><a href="https://github.com/Vertamedia/chproxy" rel="nofollow">chproxy</a> - HTTP proxy for ClickHouse database.</li>
<li><a href="https://github.com/nikepan/clickhouse-bulk" rel="nofollow">clickhouse-bulk</a> - Collects small insterts and sends big requests to ClickHouse servers.</li>
<li><a href="https://github.com/codingconcepts/datagen" rel="nofollow">datagen</a> - A fast data generator that&#39;s multi-table aware and supports multi-row DML.</li>
<li><a href="https://github.com/sj14/dbbench" rel="nofollow">dbbench</a> - Database benchmarking tool with support for several databases and scripts.</li>
<li><a href="https://github.com/siddontang/go-mysql" rel="nofollow">go-mysql</a> - Go toolset to handle MySQL protocol and replication.</li>
<li><a href="https://github.com/siddontang/go-mysql-elasticsearch" rel="nofollow">go-mysql-elasticsearch</a> - Sync your MySQL data into Elasticsearch automatically.</li>
<li><a href="https://github.com/flike/kingshard" rel="nofollow">kingshard</a> - kingshard is a high performance proxy for MySQL powered by Golang.</li>
<li><a href="https://github.com/2tvenom/myreplication" rel="nofollow">myreplication</a> - MySql binary log replication listener. Supports statement and row based replication.</li>
<li><a href="https://github.com/knocknote/octillery" rel="nofollow">octillery</a> - Go package for sharding databases ( Supports every ORM or raw SQL ).</li>
<li><a href="https://github.com/github/orchestrator" rel="nofollow">orchestrator</a> - MySQL replication topology manager &amp; visualizer.</li>
<li><a href="https://github.com/sosedoff/pgweb" rel="nofollow">pgweb</a> - Web-based PostgreSQL database browser.</li>
<li><a href="https://github.com/hexdigest/prep" rel="nofollow">prep</a> - Use prepared SQL statements without changing your code.</li>
<li><a href="https://github.com/nuveo/prest" rel="nofollow">pREST</a> - Serve a RESTful API from any PostgreSQL database.</li>
<li><a href="https://github.com/andizzle/rwdb" rel="nofollow">rwdb</a> - rwdb provides read replica capability for multiple database servers setup.</li>
<li><a href="https://github.com/youtube/vitess" rel="nofollow">vitess</a> - vitess provides servers and tools which facilitate scaling of MySQL databases for large scale web services.</li>
</ul>

<p><em>SQL query builder, libraries for building and using SQL.</em></p>

<ul>
<li><a href="https://github.com/rocketlaunchr/dbq" rel="nofollow">dbq</a> - Zero boilerplate database operations for Go.</li>
<li><a href="https://github.com/gchaincl/dotsql" rel="nofollow">Dotsql</a> - Go library that helps you keep sql files in one place and use them with ease.</li>
<li><a href="https://github.com/didi/gendry" rel="nofollow">gendry</a> - Non-invasive SQL builder and powerful data binder.</li>
<li><a href="https://github.com/xujiajun/godbal" rel="nofollow">godbal</a> - Database Abstraction Layer (dbal) for go. Support SQL builder and get result easily.</li>
<li><a href="https://github.com/doug-martin/goqu" rel="nofollow">goqu</a> - Idiomatic SQL builder and query library.</li>
<li><a href="https://github.com/galeone/igor" rel="nofollow">igor</a> - Abstraction layer for PostgreSQL that supports advanced functionality and uses gorm-like syntax.</li>
<li><a href="https://github.com/go-jet/jet" rel="nofollow">jet</a> - Framework for writing type-safe SQL queries in Go, with ability to easily convert database query result into desired arbitrary object structure.</li>
<li><a href="https://github.com/pupizoid/ormlite" rel="nofollow">ormlite</a> - Lightweight package containing some ORM-like features and helpers for sqlite databases.</li>
<li><a href="https://github.com/go-ozzo/ozzo-dbx" rel="nofollow">ozzo-dbx</a> - Powerful data retrieval methods as well as DB-agnostic query building capabilities.</li>
<li><a href="https://github.com/variadico/scaneo" rel="nofollow">scaneo</a> - Generate Go code to convert database rows into arbitrary structs.</li>
<li><a href="https://github.com/leporo/sqlf" rel="nofollow">sqlf</a> - Fast SQL query builder.</li>
<li><a href="https://github.com/elgris/sqrl" rel="nofollow">sqrl</a> - SQL query builder, fork of Squirrel with improved performance.</li>
<li><a href="https://gitlab.com/qosenergy/squalus" rel="nofollow">Squalus</a> - Thin layer over the Go SQL package that makes it easier to perform queries.</li>
<li><a href="https://github.com/Masterminds/squirrel" rel="nofollow">Squirrel</a> - Go library that helps you build SQL queries.</li>
<li><a href="https://github.com/knq/xo" rel="nofollow">xo</a> - Generate idiomatic Go code for databases based on existing schema definitions or custom queries supporting PostgreSQL, MySQL, SQLite, Oracle, and Microsoft SQL Server.</li>
</ul>
<h2><a name="database-drivers" class="anchor" href="#database-drivers" rel="nofollow" aria-hidden="true"><span class="octicon octicon-link"></span></a>
Database Drivers</h2>

<p><em>Libraries for connecting and operating databases.</em></p>

<ul>
<li><p>Relational Databases</p>

<ul>
<li><a href="https://github.com/apache/calcite-avatica-go" rel="nofollow">avatica</a> - Apache Avatica/Phoenix SQL driver for database/sql.</li>
<li><a href="https://github.com/viant/bgc" rel="nofollow">bgc</a> - Datastore Connectivity for BigQuery for go.</li>
<li><a href="https://github.com/nakagami/firebirdsql" rel="nofollow">firebirdsql</a> - Firebird RDBMS SQL driver for Go.</li>
<li><a href="https://github.com/mattn/go-adodb" rel="nofollow">go-adodb</a> - Microsoft ActiveX Object DataBase driver for go that uses database/sql.</li>
<li><a href="https://github.com/denisenkom/go-mssqldb" rel="nofollow">go-mssqldb</a> - Microsoft MSSQL driver for Go.</li>
<li><a href="https://github.com/mattn/go-oci8" rel="nofollow">go-oci8</a> - Oracle driver for go that uses database/sql.</li>
<li><a href="https://github.com/go-sql-driver/mysql" rel="nofollow">go-sql-driver/mysql</a> - MySQL driver for Go.</li>
<li><a href="https://github.com/mattn/go-sqlite3" rel="nofollow">go-sqlite3</a> - SQLite3 driver for go that uses database/sql.</li>
<li><a href="https://github.com/minus5/gofreetds" rel="nofollow">gofreetds</a> - Microsoft MSSQL driver. Go wrapper over <a href="http://www.freetds.org" rel="nofollow">FreeTDS</a>.</li>
<li><a href="https://github.com/go-goracle/goracle" rel="nofollow">goracle</a> - Oracle driver for Go, using the ODPI-C driver.</li>
<li><a href="https://github.com/jackc/pgx" rel="nofollow">pgx</a> - PostgreSQL driver supporting features beyond those exposed by database/sql.</li>
<li><a href="https://github.com/lib/pq" rel="nofollow">pq</a> - Pure Go Postgres driver for database/sql.</li>
</ul></li>

<li><p>NoSQL Databases</p>

<ul>
<li><a href="https://github.com/aerospike/aerospike-client-go" rel="nofollow">aerospike-client-go</a> - Aerospike client in Go language.</li>
<li><a href="https://github.com/solher/arangolite" rel="nofollow">arangolite</a> - Lightweight golang driver for ArangoDB.</li>
<li><a href="https://github.com/viant/asc" rel="nofollow">asc</a> - Datastore Connectivity for Aerospike for go.</li>
<li><a href="https://github.com/underarmour/dynago" rel="nofollow">dynago</a> - Dynago is a principle of least surprise client for DynamoDB.</li>
<li><a href="https://github.com/couchbase/goforestdb" rel="nofollow">forestdb</a> - Go bindings for ForestDB.</li>
<li><a href="https://github.com/couchbase/go-couchbase" rel="nofollow">go-couchbase</a> - Couchbase client in Go.</li>
<li><a href="https://github.com/pilosa/go-pilosa" rel="nofollow">go-pilosa</a> - Go client library for Pilosa.</li>
<li><a href="https://github.com/nitishm/go-rejson" rel="nofollow">go-rejson</a> - Golang client for redislabs&#39; ReJSON module using Redigo golang client. Store and manipulate structs as JSON objects in redis with ease.</li>
<li><a href="https://github.com/couchbase/gocb" rel="nofollow">gocb</a> - Official Couchbase Go SDK.</li>
<li><a href="http://gocql.github.io" rel="nofollow">gocql</a> - Go language driver for Apache Cassandra.</li>
<li><a href="https://github.com/piaohao/godis" rel="nofollow">godis</a> - redis client implement by golang, inspired by jedis.</li>
<li><a href="https://github.com/defcronyke/godscache" rel="nofollow">godscache</a> - A wrapper for the Google Cloud Platform Go Datastore package that adds caching using memcached.</li>
<li><a href="https://github.com/bradfitz/gomemcache/" rel="nofollow">gomemcache</a> - memcache client library for the Go programming language.</li>
<li><a href="https://github.com/dancannon/gorethink" rel="nofollow">gorethink</a> - Go language driver for RethinkDB.</li>
<li><a href="https://github.com/zegl/goriak" rel="nofollow">goriak</a> - Go language driver for Riak KV.</li>
<li><a href="https://github.com/globalsign/mgo" rel="nofollow">mgo</a> - (unmaintained) MongoDB driver for the Go language that implements a rich and well tested selection of features under a very simple API following standard Go idioms.</li>
<li><a href="https://github.com/mongodb/mongo-go-driver" rel="nofollow">mongo-go-driver</a> - Official MongoDB driver for the Go language.</li>
<li><a href="https://github.com/cihangir/neo4j" rel="nofollow">neo4j</a> - Neo4j Rest API Bindings for Golang.</li>
<li><a href="https://github.com/davemeehan/Neo4j-GO" rel="nofollow">Neo4j-GO</a> - Neo4j REST Client in golang.</li>
<li><a href="https://github.com/jmcvetta/neoism" rel="nofollow">neoism</a> - Neo4j client for Golang.</li>
<li><a href="https://github.com/bsm/redeo" rel="nofollow">redeo</a> - Redis-protocol compatible TCP servers/services.</li>
<li><a href="https://github.com/gomodule/redigo" rel="nofollow">redigo</a> - Redigo is a Go client for the Redis database.</li>
<li><a href="https://github.com/go-redis/redis" rel="nofollow">redis</a> - Redis client for Golang.</li>
<li><a href="https://github.com/shomali11/xredis" rel="nofollow">xredis</a> - Typesafe, customizable, clean &amp; easy to use Redis client.</li>
</ul></li>

<li><p>Search and Analytic Databases.</p>

<ul>
<li><a href="https://github.com/blevesearch/bleve" rel="nofollow">bleve</a> - Modern text indexing library for go.</li>
<li><a href="https://github.com/olivere/elastic" rel="nofollow">elastic</a> - Elasticsearch client for Go.</li>
<li><a href="https://github.com/cch123/elasticsql" rel="nofollow">elasticsql</a> - Convert sql to elasticsearch dsl in Go.</li>
<li><a href="https://github.com/mattbaird/elastigo" rel="nofollow">elastigo</a> - Elasticsearch client library.</li>
<li><a href="https://github.com/elastic/go-elasticsearch" rel="nofollow">go-elasticsearch</a> - Official Elasticsearch client for Go.</li>
<li><a href="https://github.com/OwnLocal/goes" rel="nofollow">goes</a> - Library to interact with Elasticsearch.</li>
<li><a href="https://github.com/go-ego/riot" rel="nofollow">riot</a> - Go Open Source, Distributed, Simple and efficient Search Engine.</li>
<li><a href="https://github.com/seiflotfy/skizze" rel="nofollow">skizze</a> - probabilistic data-structures service and storage.</li>
</ul></li>

<li><p>Multiple Backends.</p>

<ul>
<li><a href="https://github.com/fabiorphp/cachego" rel="nofollow">cachego</a> - Golang Cache component for multiple drivers.</li>
<li><a href="https://github.com/google/cayley" rel="nofollow">cayley</a> - Graph database with support for multiple backends.</li>
<li><a href="https://github.com/viant/dsc" rel="nofollow">dsc</a> - Datastore connectivity for SQL, NoSQL, structured files.</li>
<li><a href="https://github.com/philippgille/gokv" rel="nofollow">gokv</a> - Simple key-value store abstraction and implementations for Go (Redis, Consul, etcd, bbolt, BadgerDB, LevelDB, Memcached, DynamoDB, S3, PostgreSQL, MongoDB, CockroachDB and many more).</li>
</ul></li>
</ul>
<h2><a name="date-and-time" class="anchor" href="#date-and-time" rel="nofollow" aria-hidden="true"><span class="octicon octicon-link"></span></a>
Date and Time</h2>

<p><em>Libraries for working with dates and times.</em></p>

<ul>
<li><a href="https://github.com/uniplaces/carbon" rel="nofollow">carbon</a> - Simple Time extension with a lot of util methods, ported from PHP Carbon library.</li>
<li><a href="https://github.com/rickb777/date" rel="nofollow">date</a> - Augments Time for working with dates, date ranges, time spans, periods, and time-of-day.</li>
<li><a href="https://github.com/araddon/dateparse" rel="nofollow">dateparse</a> - Parse date&#39;s without knowing format in advance.</li>
<li><a href="https://github.com/hako/durafmt" rel="nofollow">durafmt</a> - Time duration formatting library for Go.</li>
<li><a href="https://github.com/wlbr/feiertage" rel="nofollow">feiertage</a> - Set of functions to calculate public holidays in Germany, incl. specialization on the states of Germany (Bundesländer). Things like Easter, Pentecost, Thanksgiving...</li>
<li><a href="https://github.com/yaa110/go-persian-calendar" rel="nofollow">go-persian-calendar</a> - The implementation of the Persian (Solar Hijri) Calendar in Go (golang).</li>
<li><a href="https://github.com/nathan-osman/go-sunrise" rel="nofollow">go-sunrise</a> - Calculate the sunrise and sunset times for a given location.</li>
<li><a href="https://github.com/grsmv/goweek" rel="nofollow">goweek</a> - Library for working with week entity in golang.</li>
<li><a href="https://github.com/relvacode/iso8601" rel="nofollow">iso8601</a> - Efficiently parse ISO8601 date-times without regex.</li>
<li><a href="https://github.com/GuilhermeCaruso/kair" rel="nofollow">kair</a> - Date and Time - Golang Formatting Library.</li>
<li><a href="https://github.com/jinzhu/now" rel="nofollow">now</a> - Now is a time toolkit for golang.</li>
<li><a href="https://github.com/kirillDanshin/nulltime" rel="nofollow">NullTime</a> - Nullable <code>time.Time</code>.</li>
<li><a href="https://github.com/awoodbeck/strftime" rel="nofollow">strftime</a> - C99-compatible strftime formatter.</li>
<li><a href="https://github.com/SaidinWoT/timespan" rel="nofollow">timespan</a> - For interacting with intervals of time, defined as a start time and a duration.</li>
<li><a href="https://github.com/leekchan/timeutil" rel="nofollow">timeutil</a> - Useful extensions (Timedelta, Strftime, ...) to the golang&#39;s time package.</li>
<li><a href="https://github.com/osteele/tuesday" rel="nofollow">tuesday</a> - Ruby-compatible Strftime function.</li>
</ul>
<h2><a name="distributed-systems" class="anchor" href="#distributed-systems" rel="nofollow" aria-hidden="true"><span class="octicon octicon-link"></span></a>
Distributed Systems</h2>

<p><em>Packages that help with building Distributed Systems.</em></p>

<ul>
<li><a href="https://github.com/svcavallar/celeriac.v1" rel="nofollow">celeriac</a> - Library for adding support for interacting and monitoring Celery workers, tasks and events in Go.</li>
<li><a href="https://github.com/buraksezer/consistent" rel="nofollow">consistent</a> - Consistent hashing with bounded loads.</li>
<li><a href="https://github.com/anacrolix/dht" rel="nofollow">dht</a> - BitTorrent Kademlia DHT implementation.</li>
<li><a href="https://github.com/digota/digota" rel="nofollow">digota</a> - grpc ecommerce microservice.</li>
<li><a href="https://github.com/dotchain/dot/" rel="nofollow">dot</a> - distributed sync using operational transformation/OT.</li>
<li><a href="https://github.com/edwingeng/doublejump" rel="nofollow">doublejump</a> - A revamped Google&#39;s jump consistent hash.</li>
<li><a href="https://github.com/lni/dragonboat" rel="nofollow">dragonboat</a> - A feature complete and high performance multi-group Raft library in Go.</li>
<li><a href="https://github.com/dgruber/drmaa" rel="nofollow">drmaa</a> - Job submission library for cluster schedulers based on the DRMAA standard.</li>
<li><a href="https://cirello.io/dynamolock" rel="nofollow">dynamolock</a> - DynamoDB-backed distributed locking implementation.</li>
<li><a href="https://github.com/tylfin/dynatomic" rel="nofollow">dynatomic</a> - A library for using DynamoDB as an atomic counter.</li>
<li><a href="https://github.com/emitter-io/emitter" rel="nofollow">emitter-io</a> - High performance, distributed, secure and low latency publish-subscribe platform built with MQTT, Websockets and love.</li>
<li><a href="https://github.com/vectaport/flowgraph" rel="nofollow">flowgraph</a> - flow-based programming package.</li>
<li><a href="https://github.com/chrislusf/gleam" rel="nofollow">gleam</a> - Fast and scalable distributed map/reduce system written in pure Go and Luajit, combining Go&#39;s high concurrency with Luajit&#39;s high performance, runs standalone or distributed.</li>
<li><a href="https://github.com/chrislusf/glow" rel="nofollow">glow</a> - Easy-to-Use scalable distributed big data processing, Map-Reduce, DAG execution, all in pure Go.</li>
<li><a href="https://github.com/InVisionApp/go-health" rel="nofollow">go-health</a> - Library for enabling asynchronous dependency health checks in your service.</li>
<li><a href="https://github.com/dgryski/go-jump" rel="nofollow">go-jump</a> - Port of Google&#39;s &#34;Jump&#34; Consistent Hash function.</li>
<li><a href="https://github.com/go-kit/kit" rel="nofollow">go-kit</a> - Microservice toolkit with support for service discovery, load balancing, pluggable transports, request tracking, etc.</li>
<li><a href="https://github.com/AppsFlyer/go-sundheit" rel="nofollow">go-sundheit</a> - A library built to provide support for defining async service health checks for golang services.</li>
<li><a href="https://github.com/valyala/gorpc" rel="nofollow">gorpc</a> - Simple, fast and scalable RPC library for high load.</li>
<li><a href="https://github.com/grpc/grpc-go" rel="nofollow">grpc-go</a> - The Go language implementation of gRPC. HTTP/2 based RPC.</li>
<li><a href="https://github.com/hprose/hprose-golang" rel="nofollow">hprose</a> - Very newbility RPC Library, support 25+ languages now.</li>
<li><a href="https://github.com/osamingo/jsonrpc" rel="nofollow">jsonrpc</a> - The jsonrpc package helps implement of JSON-RPC 2.0.</li>
<li><a href="https://github.com/ybbus/jsonrpc" rel="nofollow">jsonrpc</a> - JSON-RPC 2.0 HTTP client implementation.</li>
<li><a href="https://github.com/devopsfaith/krakend" rel="nofollow">KrakenD</a> - Ultra performant API Gateway framework with middlewares.</li>
<li><a href="https://github.com/micro/micro" rel="nofollow">micro</a> - Pluggable microservice toolkit and distributed systems platform.</li>
<li><a href="https://github.com/nats-io/gnatsd" rel="nofollow">NATS</a> - Lightweight, high performance messaging system for microservices, IoT, and cloud native systems.</li>
<li><a href="https://github.com/italolelis/outboxer" rel="nofollow">outboxer</a> - Outboxer is a go library that implements the outbox pattern.</li>
<li><a href="https://cirello.io/pglock" rel="nofollow">pglock</a> - PostgreSQL-backed distributed locking implementation.</li>
<li><a href="https://github.com/hashicorp/raft" rel="nofollow">raft</a> - Golang implementation of the Raft consensus protocol, by HashiCorp.</li>
<li><a href="https://github.com/coreos/etcd/tree/master/raft" rel="nofollow">raft</a> - Go implementation of the Raft consensus protocol, by CoreOS.</li>
<li><a href="https://github.com/cenkalti/rain" rel="nofollow">rain</a> - BitTorrent client and library.</li>
<li><a href="https://github.com/bsm/redislock" rel="nofollow">redis-lock</a> - Simplified distributed locking implementation using Redis.</li>
<li><a href="https://resgate.io/" rel="nofollow">resgate</a> - Realtime API Gateway for building REST, real time, and RPC APIs, where all clients are synchronized seamlessly.</li>
<li><a href="https://github.com/uber/ringpop-go" rel="nofollow">ringpop-go</a> - Scalable, fault-tolerant application-layer sharding for Go applications.</li>
<li><a href="https://github.com/smallnest/rpcx" rel="nofollow">rpcx</a> - Distributed pluggable RPC service framework like alibaba Dubbo.</li>
<li><a href="https://github.com/ursiform/sleuth" rel="nofollow">sleuth</a> - Library for master-less p2p auto-discovery and RPC between HTTP services (using <a href="https://github.com/zeromq/libzmq" rel="nofollow">ZeroMQ</a>).</li>
<li><a href="https://github.com/tendermint/tendermint" rel="nofollow">tendermint</a> - High-performance middleware for transforming a state machine written in any programming language into a Byzantine Fault Tolerant replicated state machine using the Tendermint consensus and blockchain protocols.</li>
<li><a href="https://github.com/anacrolix/torrent" rel="nofollow">torrent</a> - BitTorrent client package.</li>
</ul>
<h2><a name="email" class="anchor" href="#email" rel="nofollow" aria-hidden="true"><span class="octicon octicon-link"></span></a>
Email</h2>

<p><em>Libraries and tools that implement email creation and sending.</em></p>

<ul>
<li><a href="https://blitiri.com.ar/p/chasquid" rel="nofollow">chasquid</a> - SMTP server written in Go.</li>
<li><a href="https://github.com/aymerick/douceur" rel="nofollow">douceur</a> - CSS inliner for your HTML emails.</li>
<li><a href="https://github.com/jordan-wright/email" rel="nofollow">email</a> - A robust and flexible email library for Go.</li>
<li><a href="https://github.com/toorop/go-dkim" rel="nofollow">go-dkim</a> - DKIM library, to sign &amp; verify email.</li>
<li><a href="https://github.com/emersion/go-imap" rel="nofollow">go-imap</a> - IMAP library for clients and servers.</li>
<li><a href="https://github.com/emersion/go-message" rel="nofollow">go-message</a> - Streaming library for the Internet Message Format and mail messages.</li>
<li><a href="https://github.com/vanng822/go-premailer" rel="nofollow">go-premailer</a> - Inline styling for HTML mail in Go.</li>
<li><a href="https://github.com/xhit/go-simple-mail" rel="nofollow">go-simple-mail</a> - Very simple package to send emails with SMTP Keep Alive and two timeouts: Connect and Send.</li>
<li><a href="https://github.com/hectane/hectane" rel="nofollow">Hectane</a> - Lightweight SMTP client providing an HTTP API.</li>
<li><a href="https://github.com/matcornic/hermes" rel="nofollow">hermes</a> - Golang package that generates clean, responsive HTML e-mails.</li>
<li><a href="https://github.com/mailgun/mailgun-go" rel="nofollow">mailgun-go</a> - Go library for sending mail with the Mailgun API.</li>
<li><a href="https://github.com/mailhog/MailHog" rel="nofollow">MailHog</a> - Email and SMTP testing with web and API interface.</li>
<li><a href="https://github.com/sendgrid/sendgrid-go" rel="nofollow">SendGrid</a> - SendGrid&#39;s Go library for sending email.</li>
<li><a href="https://github.com/mailhog/smtp" rel="nofollow">smtp</a> - SMTP server protocol state machine.</li>
</ul>
<h2><a name="embeddable-scripting-languages" class="anchor" href="#embeddable-scripting-languages" rel="nofollow" aria-hidden="true"><span class="octicon octicon-link"></span></a>
Embeddable Scripting Languages</h2>

<p><em>Embedding other languages inside your go code.</em></p>

<ul>
<li><a href="https://github.com/PuerkitoBio/agora" rel="nofollow">agora</a> - Dynamically typed, embeddable programming language in Go.</li>
<li><a href="https://github.com/mattn/anko" rel="nofollow">anko</a> - Scriptable interpreter written in Go.</li>
<li><a href="https://github.com/alexeyco/binder" rel="nofollow">binder</a> - Go to Lua binding library, based on <a href="https://github.com/yuin/gopher-lua" rel="nofollow">gopher-lua</a>.</li>
<li><a href="https://github.com/google/cel-go" rel="nofollow">cel-go</a> - Fast, portable, non-Turing complete expression evaluation with gradual typing.</li>
<li><a href="https://github.com/antonmedv/expr" rel="nofollow">expr</a> - an engine that can evaluate expressions.</li>
<li><a href="https://github.com/gentee/gentee" rel="nofollow">gentee</a> - Embeddable scripting programming language.</li>
<li><a href="https://github.com/jcla1/gisp" rel="nofollow">gisp</a> - Simple LISP in Go.</li>
<li><a href="https://github.com/olebedev/go-duktape" rel="nofollow">go-duktape</a> - Duktape JavaScript engine bindings for Go.</li>
<li><a href="https://github.com/Shopify/go-lua" rel="nofollow">go-lua</a> - Port of the Lua 5.2 VM to pure Go.</li>
<li><a href="https://github.com/deuill/go-php" rel="nofollow">go-php</a> - PHP bindings for Go.</li>
<li><a href="https://github.com/sbinet/go-python" rel="nofollow">go-python</a> - naive go bindings to the CPython C-API.</li>
<li><a href="https://github.com/aarzilli/golua" rel="nofollow">golua</a> - Go bindings for Lua C API.</li>
<li><a href="https://github.com/yuin/gopher-lua" rel="nofollow">gopher-lua</a> - Lua 5.1 VM and compiler written in Go.</li>
<li><a href="https://github.com/PaesslerAG/gval" rel="nofollow">gval</a> - A highly customizable expression language written in Go.</li>
<li><a href="https://github.com/db47h/ngaro" rel="nofollow">ngaro</a> - Embeddable Ngaro VM implementation enabling scripting in Retro.</li>
<li><a href="https://github.com/robertkrimen/otto" rel="nofollow">otto</a> - JavaScript interpreter written in Go.</li>
<li><a href="https://github.com/ian-kent/purl" rel="nofollow">purl</a> - Perl 5.18.2 embedded in Go.</li>
<li><a href="https://github.com/d5/tengo" rel="nofollow">tengo</a> - Bytecode compiled script language for Go.</li>
</ul>
<h2><a name="error-handling" class="anchor" href="#error-handling" rel="nofollow" aria-hidden="true"><span class="octicon octicon-link"></span></a>
Error Handling</h2>

<p><em>Libraries for handling errors.</em></p>

<ul>
<li><a href="https://github.com/emperror/emperror" rel="nofollow">emperror</a> - Error handling tools and best practices for Go libraries and applications.</li>
<li><a href="https://github.com/snwfdhmp/errlog" rel="nofollow">errlog</a> - Hackable package that determines responsible source code for an error (and some other fast-debugging features). Pluggable to any logger in-place.</li>
<li><a href="https://github.com/emperror/errors" rel="nofollow">errors</a> - Drop-in replacement for the standard library errors package and github.com/pkg/errors. Provides various error handling primitives.</li>
<li><a href="https://github.com/pkg/errors" rel="nofollow">errors</a> - Package that provides simple error handling primitives.</li>
<li><a href="https://github.com/neuronlabs/errors" rel="nofollow">errors</a> - Simple golang error handling with classification primitives.</li>
<li><a href="https://github.com/joomcode/errorx" rel="nofollow">errorx</a> - A feature rich error package with stack traces, composition of errors and more.</li>
<li><a href="https://github.com/SonicRoshan/falcon" rel="nofollow">Falcon</a> - A Simple Yet Highly Powerful Package For Error Handling.</li>
<li><a href="https://github.com/hashicorp/go-multierror" rel="nofollow">go-multierror</a> - Go (golang) package for representing a list of errors as a single error.</li>
<li><a href="https://github.com/ztrue/tracerr" rel="nofollow">tracerr</a> - Golang errors with stack trace and source fragments.</li>
<li><a href="https://github.com/txgruppi/werr" rel="nofollow">werr</a> - Error Wrapper creates an wrapper for the error type in Go which captures the File, Line and Stack of where it was called.</li>
</ul>
<h2><a name="files" class="anchor" href="#files" rel="nofollow" aria-hidden="true"><span class="octicon octicon-link"></span></a>
Files</h2>

<p><em>Libraries for handling files and file systems.</em></p>

<ul>
<li><a href="https://github.com/spf13/afero" rel="nofollow">afero</a> - FileSystem Abstraction System for Go.</li>
<li><a href="https://github.com/viant/afs" rel="nofollow">afs</a> - Abstract File Storage (mem, scp, zip, tar, cloud: s3, gs) for Go.</li>
<li><a href="https://github.com/bigfile/bigfile" rel="nofollow">bigfile</a> - A file transfer system, support to manage files with http api, rpc call and ftp client.</li>
<li><a href="https://github.com/codingsince1985/checksum" rel="nofollow">checksum</a> - Compute message digest, like MD5 and SHA256, for large files.</li>
<li><a href="https://github.com/homedepot/flop" rel="nofollow">flop</a> - File operations library which aims to mirror feature parity with <a href="https://www.gnu.org/software/coreutils/manual/html_node/cp-invocation.html" rel="nofollow">GNU cp</a>.</li>
<li><a href="https://github.com/artonge/go-csv-tag" rel="nofollow">go-csv-tag</a> - Load csv file using tag.</li>
<li><a href="https://github.com/hugocarreira/go-decent-copy" rel="nofollow">go-decent-copy</a> - Copy files for humans.</li>
<li><a href="https://github.com/barasher/go-exiftool" rel="nofollow">go-exiftool</a> - Go bindings for ExifTool, the well-known library used to extract as much metadata as possible (EXIF, IPTC, ...) from files (pictures, PDF, office, ...).</li>
<li><a href="https://github.com/artonge/go-gtfs" rel="nofollow">go-gtfs</a> - Load gtfs files in go.</li>
<li><a href="https://github.com/rjeczalik/notify" rel="nofollow">notify</a> - File system event notification library with simple API, similar to os/signal.</li>
<li><a href="https://github.com/qmuntal/opc" rel="nofollow">opc</a> - Load Open Packaging Conventions (OPC) files for Go.</li>
<li><a href="https://github.com/parsyl/parquet" rel="nofollow">parquet</a> - Read and write <a href="https://parquet.apache.org" rel="nofollow">parquet</a> files.</li>
<li><a href="https://github.com/hhrutter/pdfcpu" rel="nofollow">pdfcpu</a> - PDF processor.</li>
<li><a href="https://github.com/dixonwille/skywalker" rel="nofollow">skywalker</a> - Package to allow one to concurrently go through a filesystem with ease.</li>
<li><a href="https://gitlab.com/russoj88/stl" rel="nofollow">stl</a> - Modules to read and write STL (stereolithography) files.  Concurrent algorithm for reading.</li>
<li><a href="https://github.com/posener/tarfs" rel="nofollow">tarfs</a> - Implementation of the <a href="https://godoc.org/github.com/kr/fs#FileSystem" rel="nofollow"><code>FileSystem</code> interface</a> for tar files.</li>
<li><a href="https://github.com/C2FO/vfs" rel="nofollow">vfs</a> - A pluggable, extensible, and opinionated set of filesystem functionality for Go across a number of filesystem types such as os, S3, and GCS.</li>
</ul>
<h2><a name="financial" class="anchor" href="#financial" rel="nofollow" aria-hidden="true"><span class="octicon octicon-link"></span></a>
Financial</h2>

<p><em>Packages for accounting and finance.</em></p>

<ul>
<li><a href="https://github.com/leekchan/accounting" rel="nofollow">accounting</a> - money and currency formatting for golang.</li>
<li><a href="https://github.com/bnkamalesh/currency" rel="nofollow">currency</a> - High performant &amp; accurate currency computation package.</li>
<li><a href="https://github.com/shopspring/decimal" rel="nofollow">decimal</a> - Arbitrary-precision fixed-point decimal numbers.</li>
<li><a href="https://github.com/FlashBoys/go-finance" rel="nofollow">go-finance</a> - Comprehensive financial markets data in Go.</li>
<li><a href="https://github.com/alpeb/go-finance" rel="nofollow">go-finance</a> - Library of financial functions for time value of money (annuities), cash flow, interest rate conversions, bonds and depreciation calculations.</li>
<li><a href="https://github.com/rhymond/go-money" rel="nofollow">go-money</a> - Implementation of Fowler&#39;s Money pattern.</li>
<li><a href="https://github.com/aclindsa/ofxgo" rel="nofollow">ofxgo</a> - Query OFX servers and/or parse the responses (with example command-line client).</li>
<li><a href="https://github.com/i25959341/orderbook" rel="nofollow">orderbook</a> - Matching Engine for Limit Order Book in Golang.</li>
<li><a href="https://github.com/sdcoffey/techan" rel="nofollow">techan</a> - Technical analysis library with advanced market analysis and trading strategies.</li>
<li><a href="https://github.com/claygod/transaction" rel="nofollow">transaction</a> - Embedded transactional database of accounts, running in multithreaded mode.</li>
<li><a href="https://github.com/dannyvankooten/vat" rel="nofollow">vat</a> - VAT number validation &amp; EU VAT rates.</li>
</ul>
<h2><a name="forms" class="anchor" href="#forms" rel="nofollow" aria-hidden="true"><span class="octicon octicon-link"></span></a>
Forms</h2>

<p><em>Libraries for working with forms.</em></p>

<ul>
<li><a href="https://github.com/robfig/bind" rel="nofollow">bind</a> - Bind form data to any Go values.</li>
<li><a href="https://github.com/mholt/binding" rel="nofollow">binding</a> - Binds form and JSON data from net/http Request to struct.</li>
<li><a href="https://github.com/leebenson/conform" rel="nofollow">conform</a> - Keeps user input in check. Trims, sanitizes &amp; scrubs data based on struct tags.</li>
<li><a href="https://github.com/go-playground/form" rel="nofollow">form</a> - Decodes url.Values into Go value(s) and Encodes Go value(s) into url.Values. Dual Array and Full map support.</li>
<li><a href="https://github.com/monoculum/formam" rel="nofollow">formam</a> - decode form&#39;s values into a struct.</li>
<li><a href="https://github.com/albrow/forms" rel="nofollow">forms</a> - Framework-agnostic library for parsing and validating form/JSON data which supports multipart forms and files.</li>
<li><a href="https://github.com/gorilla/csrf" rel="nofollow">gorilla/csrf</a> - CSRF protection for Go web applications &amp; services.</li>
<li><a href="https://github.com/justinas/nosurf" rel="nofollow">nosurf</a> - CSRF protection middleware for Go.</li>
</ul>
<h2><a name="functional" class="anchor" href="#functional" rel="nofollow" aria-hidden="true"><span class="octicon octicon-link"></span></a>
Functional</h2>

<p><em>Packages to support functional programming in Go.</em></p>

<ul>
<li><a href="https://github.com/TeaEntityLab/fpGo" rel="nofollow">fpGo</a> - Monad, Functional Programming features for Golang.</li>
<li><a href="https://github.com/seborama/fuego" rel="nofollow">fuego</a> - Functional Experiment in Go.</li>
<li><a href="https://github.com/tobyhede/go-underscore" rel="nofollow">go-underscore</a> - Useful collection of helpfully functional Go collection utilities.</li>
</ul>
<h2><a name="game-development" class="anchor" href="#game-development" rel="nofollow" aria-hidden="true"><span class="octicon octicon-link"></span></a>
Game Development</h2>

<p><em>Awesome game development libraries.</em></p>

<ul>
<li><a href="https://github.com/azul3d/engine" rel="nofollow">Azul3D</a> - 3D game engine written in Go.</li>
<li><a href="https://github.com/hajimehoshi/ebiten" rel="nofollow">Ebiten</a> - dead simple 2D game library in Go.</li>
<li><a href="https://github.com/EngoEngine/engo" rel="nofollow">engo</a> - Engo is an open-source 2D game engine written in Go. It follows the Entity-Component-System paradigm.</li>
<li><a href="https://github.com/g3n/engine" rel="nofollow">g3n</a> - Go 3D Game Engine.</li>
<li><a href="https://github.com/vova616/GarageEngine" rel="nofollow">GarageEngine</a> - 2d game engine written in Go working on OpenGL.</li>
<li><a href="https://github.com/runningwild/glop" rel="nofollow">glop</a> - Glop (Game Library Of Power) is a fairly simple cross-platform game library.</li>
<li><a href="https://github.com/beefsack/go-astar" rel="nofollow">go-astar</a> - Go implementation of the A* path finding algorithm.</li>
<li><a href="https://github.com/GlenKelley/go-collada" rel="nofollow">go-collada</a> - Go package for working with the Collada file format.</li>
<li><a href="https://github.com/veandco/go-sdl2" rel="nofollow">go-sdl2</a> - Go bindings for the <a href="https://www.libsdl.org/" rel="nofollow">Simple DirectMedia Layer</a>.</li>
<li><a href="https://github.com/ungerik/go3d" rel="nofollow">go3d</a> - Performance oriented 2D/3D math package for Go.</li>
<li><a href="https://github.com/xtaci/gonet" rel="nofollow">gonet</a> - Game server skeleton implemented with golang.</li>
<li><a href="https://github.com/xiaonanln/goworld" rel="nofollow">goworld</a> - Scalable game server engine, featuring space-entity framework and hot-swapping.</li>
<li><a href="https://github.com/name5566/leaf" rel="nofollow">Leaf</a> - Lightweight game server framework.</li>
<li><a href="https://github.com/lonng/nano" rel="nofollow">nano</a> - Lightweight, facility, high performance golang based game server framework.</li>
<li><a href="https://github.com/oakmound/oak" rel="nofollow">Oak</a> - Pure Go game engine.</li>
<li><a href="https://github.com/topfreegames/pitaya" rel="nofollow">Pitaya</a> - Scalable game server framework with clustering support and client libraries for iOS, Android, Unity and others through the C SDK.</li>
<li><a href="https://github.com/faiface/pixel" rel="nofollow">Pixel</a> - Hand-crafted 2D game library in Go.</li>
<li><a href="https://github.com/gen2brain/raylib-go" rel="nofollow">raylib-go</a> - Go bindings for <a href="http://www.raylib.com/" rel="nofollow">raylib</a>, a simple and easy-to-use library to learn videogames programming.</li>
<li><a href="https://github.com/JoelOtter/termloop" rel="nofollow">termloop</a> - Terminal-based game engine for Go, built on top of Termbox.</li>
</ul>
<h2><a name="generation-and-generics" class="anchor" href="#generation-and-generics" rel="nofollow" aria-hidden="true"><span class="octicon octicon-link"></span></a>
Generation and Generics</h2>

<p><em>Tools to enhance the language with features like generics via code generation.</em></p>

<ul>
<li><a href="https://github.com/t0pep0/efaceconv" rel="nofollow">efaceconv</a> - Code generation tool for high performance conversion from interface{} to immutable type without allocations.</li>
<li><a href="https://github.com/clipperhouse/gen" rel="nofollow">gen</a> - Code generation tool for ‘generics’-like functionality.</li>
<li><a href="https://github.com/senselogic/GENERIS" rel="nofollow">generis</a> - Code generation tool providing generics, free-form macros, conditional compilation and HTML templating.</li>
<li><a href="https://github.com/abice/go-enum" rel="nofollow">go-enum</a> - Code generation for enums from code comments.</li>
<li><a href="https://github.com/ahmetalpbalkan/go-linq" rel="nofollow">go-linq</a> - .NET LINQ-like query methods for Go.</li>
<li><a href="https://github.com/awalterschulze/goderive" rel="nofollow">goderive</a> - Derives functions from input types.</li>
<li><a href="https://github.com/wzshiming/gotype" rel="nofollow">gotype</a> - Golang source code parsing, usage like reflect package.</li>
<li><a href="https://github.com/hexdigest/gowrap" rel="nofollow">GoWrap</a> - Generate decorators for Go interfaces using simple templates.</li>
<li><a href="https://github.com/rjeczalik/interfaces" rel="nofollow">interfaces</a> - Command line tool for generating interface definitions.</li>
<li><a href="https://github.com/dave/jennifer" rel="nofollow">jennifer</a> - Generate arbitrary Go code without templates.</li>
<li><a href="https://github.com/ungerik/pkgreflect" rel="nofollow">pkgreflect</a> - Go preprocessor for package scoped reflection.</li>
</ul>
<h2><a name="geographic" class="anchor" href="#geographic" rel="nofollow" aria-hidden="true"><span class="octicon octicon-link"></span></a>
Geographic</h2>

<p><em>Geographic tools and servers</em></p>

<ul>
<li><a href="https://github.com/melihmucuk/geocache" rel="nofollow">geocache</a> - In-memory cache that is suitable for geolocation based applications.</li>
<li><a href="https://github.com/hishamkaram/geoserver" rel="nofollow">geoserver</a> - geoserver Is a Go Package For Manipulating a GeoServer Instance via the GeoServer REST API.</li>
<li><a href="https://github.com/hishamkaram/gismanager" rel="nofollow">gismanager</a> - Publish Your GIS Data(Vector Data) to PostGIS and Geoserver.</li>
<li><a href="https://github.com/paulmach/osm" rel="nofollow">osm</a> - Library for reading, writing and working with OpenStreetMap data and APIs.</li>
<li><a href="https://github.com/maguro/pbf" rel="nofollow">pbf</a> - OpenStreetMap PBF golang encoder/decoder.</li>
<li><a href="https://github.com/golang/geo" rel="nofollow">S2 geometry</a> - S2 geometry library in Go.</li>
<li><a href="https://github.com/tidwall/tile38" rel="nofollow">Tile38</a> - Geolocation DB with spatial index and realtime geofencing.</li>
<li><a href="https://github.com/wroge/wgs84" rel="nofollow">WGS84</a> - Library for Coordinate Conversion and Transformation (ETRS89, OSGB36, NAD83, RGF93, Web Mercator, UTM).</li>
</ul>
<h2><a name="go-compilers" class="anchor" href="#go-compilers" rel="nofollow" aria-hidden="true"><span class="octicon octicon-link"></span></a>
Go Compilers</h2>

<p><em>Tools for compiling Go to other languages.</em></p>

<ul>
<li><a href="https://github.com/Konstantin8105/c4go" rel="nofollow">c4go</a> - Transpile C code to Go code.</li>
<li><a href="https://github.com/Konstantin8105/f4go" rel="nofollow">f4go</a> - Transpile FORTRAN 77 code to Go code.</li>
<li><a href="https://github.com/gopherjs/gopherjs" rel="nofollow">gopherjs</a> - Compiler from Go to JavaScript.</li>
<li><a href="https://github.com/go-llvm/llgo" rel="nofollow">llgo</a> - LLVM-based compiler for Go.</li>
<li><a href="https://github.com/tardisgo/tardisgo" rel="nofollow">tardisgo</a> - Golang to Haxe to CPP/CSharp/Java/JavaScript transpiler.</li>
</ul>
<h2><a name="goroutines" class="anchor" href="#goroutines" rel="nofollow" aria-hidden="true"><span class="octicon octicon-link"></span></a>
Goroutines</h2>

<p><em>Tools for managing and working with Goroutines.</em></p>

<ul>
<li><a href="https://github.com/panjf2000/ants" rel="nofollow">ants</a> - A high-performance goroutine pool for golang.</li>
<li><a href="https://github.com/borderstech/artifex" rel="nofollow">artifex</a> - Simple in-memory job queue for Golang using worker-based dispatching.</li>
<li><a href="https://github.com/studiosol/async" rel="nofollow">async</a> - A safe way to execute functions asynchronously, recovering them in case of panic.</li>
<li><a href="https://github.com/kamilsk/breaker" rel="nofollow">breaker</a> - Flexible mechanism to make execution flow interruptible.</li>
<li><a href="https://github.com/marusama/cyclicbarrier" rel="nofollow">cyclicbarrier</a> - CyclicBarrier for golang.</li>
<li><a href="https://github.com/workanator/go-floc" rel="nofollow">go-floc</a> - Orchestrate goroutines with ease.</li>
<li><a href="https://github.com/kamildrazkiewicz/go-flow" rel="nofollow">go-flow</a> - Control goroutines execution order.</li>
<li><a href="https://github.com/nikhilsaraf/go-tools" rel="nofollow">go-tools/multithreading</a> - Manage a pool of goroutines using this lightweight library with a simple API.</li>
<li><a href="https://github.com/subchen/go-trylock" rel="nofollow">go-trylock</a> - TryLock support on read-write lock for Golang.</li>
<li><a href="https://github.com/loveleshsharma/gohive" rel="nofollow">gohive</a> - A highly performant and easy to use Goroutine pool for Go.</li>
<li><a href="https://github.com/vardius/gollback" rel="nofollow">gollback</a> - asynchronous simple function utilities, for managing execution of closures and callbacks.</li>
<li><a href="https://github.com/themester/GoSlaves" rel="nofollow">GoSlaves</a> - Simple and Asynchronous Goroutine pool library.</li>
<li><a href="https://github.com/benmanns/goworker" rel="nofollow">goworker</a> - goworker is a Go-based background worker.</li>
<li><a href="https://github.com/xxjwxc/gowp" rel="nofollow">gowp</a> - gowp is concurrency limiting goroutine pool.</li>
<li><a href="https://github.com/Sherifabdlnaby/gpool" rel="nofollow">gpool</a> - manages a resizeable pool of context-aware goroutines to bound concurrency.</li>
<li><a href="https://github.com/ivpusic/grpool" rel="nofollow">grpool</a> - Lightweight Goroutine pool.</li>
<li><a href="https://github.com/AaronJan/Hunch" rel="nofollow">Hunch</a> - Hunch provides functions like: <code>All</code>, <code>First</code>, <code>Retry</code>, <code>Waterfall</code> etc., that makes asynchronous flow control more intuitive.</li>
<li><a href="https://cirello.io/oversight" rel="nofollow">oversight</a> - Oversight is a complete implementation of the Erlang supervision trees.</li>
<li><a href="https://github.com/rafaeljesus/parallel-fn" rel="nofollow">parallel-fn</a> - Run functions in parallel.</li>
<li><a href="https://github.com/go-playground/pool" rel="nofollow">pool</a> - Limited consumer goroutine or unlimited goroutine pool for easier goroutine handling and cancellation.</li>
<li><a href="https://github.com/AnikHasibul/queue" rel="nofollow">queue</a> - Gives you a <code>sync.WaitGroup</code> like queue group accessibility. Helps you to throttle and limit goroutines, wait for the end of the all goroutines and much more.</li>
<li><a href="https://github.com/x-mod/routine" rel="nofollow">routine</a> - go routine control with context, support: Main, Go, Pool and some useful Executors.</li>
<li><a href="https://github.com/kamilsk/semaphore" rel="nofollow">semaphore</a> - Semaphore pattern implementation with timeout of lock/unlock operations based on channel and context.</li>
<li><a href="https://github.com/marusama/semaphore" rel="nofollow">semaphore</a> - Fast resizable semaphore implementation based on CAS (faster than channel-based semaphore implementations).</li>
<li><a href="https://github.com/ssgreg/stl" rel="nofollow">stl</a> - Software transactional locks based on Software Transactional Memory (STM) concurrency control mechanism.</li>
<li><a href="https://github.com/shettyh/threadpool" rel="nofollow">threadpool</a> - Golang threadpool implementation.</li>
<li><a href="https://github.com/Jeffail/tunny" rel="nofollow">tunny</a> - Goroutine pool for golang.</li>
<li><a href="https://github.com/vardius/worker-pool" rel="nofollow">worker-pool</a> - goworker is a Go simple async worker pool.</li>
<li><a href="https://github.com/gammazero/workerpool" rel="nofollow">workerpool</a> - Goroutine pool that limits the concurrency of task execution, not the number of tasks queued.</li>
</ul>
<h2><a name="gui" class="anchor" href="#gui" rel="nofollow" aria-hidden="true"><span class="octicon octicon-link"></span></a>
GUI</h2>

<p><em>Libraries for building GUI Applications.</em></p>

<p><em>Toolkits</em></p>

<ul>
<li><a href="https://github.com/murlokswarm/app" rel="nofollow">app</a> - Package to create apps with GO, HTML and CSS. Supports: MacOS, Windows in progress.</li>
<li><a href="https://github.com/fyne-io/fyne" rel="nofollow">fyne</a> - Cross platform native GUIs designed for Go, rendered using EFL. Supports: Linux, macOS, Windows.</li>
<li><a href="https://github.com/asticode/go-astilectron" rel="nofollow">go-astilectron</a> - Build cross platform GUI apps with GO and HTML/JS/CSS (powered by Electron).</li>
<li><a href="http://mattn.github.io/go-gtk/" rel="nofollow">go-gtk</a> - Go bindings for GTK.</li>
<li><a href="https://github.com/sciter-sdk/go-sciter" rel="nofollow">go-sciter</a> - Go bindings for Sciter: the Embeddable HTML/CSS/script engine for modern desktop UI development. Cross platform.</li>
<li><a href="https://github.com/gotk3/gotk3" rel="nofollow">gotk3</a> - Go bindings for GTK3.</li>
<li><a href="https://github.com/dtylman/gowd" rel="nofollow">gowd</a> - Rapid and simple desktop UI development with GO, HTML, CSS and NW.js. Cross platform.</li>
<li><a href="https://github.com/therecipe/qt" rel="nofollow">qt</a> - Qt binding for Go (support for Windows / macOS / Linux / Android / iOS / Sailfish OS / Raspberry Pi).</li>
<li><a href="https://github.com/andlabs/ui" rel="nofollow">ui</a> - Platform-native GUI library for Go. Cross platform.</li>
<li><a href="https://wails.app" rel="nofollow">Wails</a> - Mac, Windows, Linux desktop apps with HTML UI using built-in OS HTML renderer.</li>
<li><a href="https://github.com/lxn/walk" rel="nofollow">walk</a> - Windows application library kit for Go.</li>
<li><a href="https://github.com/zserge/webview" rel="nofollow">webview</a> - Cross-platform webview window with simple two-way JavaScript bindings (Windows / macOS / Linux).</li>
</ul>

<p><em>Interaction</em></p>

<ul>
<li><a href="https://github.com/dawidd6/go-appindicator" rel="nofollow">go-appindicator</a> - Go bindings for libappindicator3 C library.</li>
<li><a href="https://github.com/deckarep/gosx-notifier" rel="nofollow">gosx-notifier</a> - OSX Desktop Notifications library for Go.</li>
<li><a href="https://github.com/prashantgupta24/activity-tracker" rel="nofollow">mac-activity-tracker</a> - OSX library to notify about any (pluggable) activity on your machine.</li>
<li><a href="https://github.com/prashantgupta24/mac-sleep-notifier" rel="nofollow">mac-sleep-notifier</a> - OSX Sleep/Wake notifications in golang.</li>
<li><a href="https://github.com/go-vgo/robotgo" rel="nofollow">robotgo</a> - Go Native cross-platform GUI system automation. Control the mouse, keyboard and other.</li>
<li><a href="https://github.com/getlantern/systray" rel="nofollow">systray</a> - Cross platform Go library to place an icon and menu in the notification area.</li>
<li><a href="https://github.com/shurcooL/trayhost" rel="nofollow">trayhost</a> - Cross-platform Go library to place an icon in the host operating system&#39;s taskbar.</li>
</ul>
<h2><a name="hardware" class="anchor" href="#hardware" rel="nofollow" aria-hidden="true"><span class="octicon octicon-link"></span></a>
Hardware</h2>

<p><em>Libraries, tools, and tutorials for interacting with hardware.</em></p>

<p>See <a href="https://github.com/rakyll/go-hardware" rel="nofollow">go-hardware</a> for a comprehensive list.</p>
<h2><a name="images" class="anchor" href="#images" rel="nofollow" aria-hidden="true"><span class="octicon octicon-link"></span></a>
Images</h2>

<p><em>Libraries for manipulating images.</em></p>

<ul>
<li><a href="https://github.com/anthonynsimon/bild" rel="nofollow">bild</a> - Collection of image processing algorithms in pure Go.</li>
<li><a href="https://github.com/h2non/bimg" rel="nofollow">bimg</a> - Small package for fast and efficient image processing using libvips.</li>
<li><a href="https://github.com/aofei/cameron" rel="nofollow">cameron</a> - An avatar generator for Go.</li>
<li><a href="https://github.com/tdewolff/canvas" rel="nofollow">canvas</a> - Vector graphics to PDF, SVG or rasterized image.</li>
<li><a href="https://github.com/gojek/darkroom" rel="nofollow">darkroom</a> - An image proxy with changeable storage backends and image processing engines with focus on speed and resiliency.</li>
<li><a href="https://github.com/pravj/geopattern" rel="nofollow">geopattern</a> - Create beautiful generative image patterns from a string.</li>
<li><a href="https://github.com/fogleman/gg" rel="nofollow">gg</a> - 2D rendering in pure Go.</li>
<li><a href="https://github.com/disintegration/gift" rel="nofollow">gift</a> - Package of image processing filters.</li>
<li><a href="https://github.com/qmuntal/gltf" rel="nofollow">gltf</a> - Efficient and robust glTF 2.0 reader, writer and validator.</li>
<li><a href="https://github.com/ungerik/go-cairo" rel="nofollow">go-cairo</a> - Go binding for the cairo graphics library.</li>
<li><a href="https://github.com/bolknote/go-gd" rel="nofollow">go-gd</a> - Go binding for GD library.</li>
<li><a href="https://github.com/koyachi/go-nude" rel="nofollow">go-nude</a> - Nudity detection with Go.</li>
<li><a href="https://github.com/lazywei/go-opencv" rel="nofollow">go-opencv</a> - Go bindings for OpenCV.</li>
<li><a href="https://github.com/jyotiska/go-webcolors" rel="nofollow">go-webcolors</a> - Port of webcolors library from Python to Go.</li>
<li><a href="https://github.com/hybridgroup/gocv" rel="nofollow">gocv</a> - Go package for computer vision using OpenCV 3.3+.</li>
<li><a href="https://github.com/corona10/goimagehash" rel="nofollow">goimagehash</a> - Go Perceptual image hashing package.</li>
<li><a href="https://github.com/corona10/goimghdr" rel="nofollow">goimghdr</a> - The imghdr module determines the type of image contained in a file for Go.</li>
<li><a href="https://github.com/o1egl/govatar" rel="nofollow">govatar</a> - Library and CMD tool for generating funny avatars.</li>
<li><a href="https://github.com/qeesung/image2ascii" rel="nofollow">image2ascii</a> - Convert image to ASCII.</li>
<li><a href="https://github.com/gographics/imagick" rel="nofollow">imagick</a> - Go binding to ImageMagick&#39;s MagickWand C API.</li>
<li><a href="https://github.com/h2non/imaginary" rel="nofollow">imaginary</a> - Fast and simple HTTP microservice for image resizing.</li>
<li><a href="https://github.com/disintegration/imaging" rel="nofollow">imaging</a> - Simple Go image processing package.</li>
<li><a href="https://github.com/hawx/img" rel="nofollow">img</a> - Selection of image manipulation tools.</li>
<li><a href="https://github.com/fogleman/ln" rel="nofollow">ln</a> - 3D line art rendering in Go.</li>
<li><a href="https://github.com/noelyahan/mergi" rel="nofollow">mergi</a> - Tool &amp; Go library for image manipulation (Merge, Crop, Resize, Watermark, Animate).</li>
<li><a href="https://github.com/aldor007/mort" rel="nofollow">mort</a> - Storage and image processing server written in Go.</li>
<li><a href="https://github.com/donatj/mpo" rel="nofollow">mpo</a> - Decoder and conversion tool for MPO 3D Photos.</li>
<li><a href="https://github.com/thoas/picfit" rel="nofollow">picfit</a> - An image resizing server written in Go.</li>
<li><a href="https://github.com/fogleman/pt" rel="nofollow">pt</a> - Path tracing engine written in Go.</li>
<li><a href="https://github.com/nfnt/resize" rel="nofollow">resize</a> - Image resizing for Go with common interpolation methods.</li>
<li><a href="https://github.com/bamiaux/rez" rel="nofollow">rez</a> - Image resizing in pure Go and SIMD.</li>
<li><a href="https://github.com/muesli/smartcrop" rel="nofollow">smartcrop</a> - Finds good crops for arbitrary images and crop sizes.</li>
<li><a href="https://github.com/auyer/steganography" rel="nofollow">steganography</a> - Pure Go Library for LSB steganography.</li>
<li><a href="https://github.com/DimitarPetrov/stegify" rel="nofollow">stegify</a> - Go tool for LSB steganography, capable of hiding any file within an image.</li>
<li><a href="https://github.com/ajstarks/svgo" rel="nofollow">svgo</a> - Go Language Library for SVG generation.</li>
<li><a href="https://github.com/ftrvxmtrx/tga" rel="nofollow">tga</a> - Package tga is a TARGA image format decoder/encoder.</li>
</ul>
<h2><a name="iot-internet-of-things" class="anchor" href="#iot-internet-of-things" rel="nofollow" aria-hidden="true"><span class="octicon octicon-link"></span></a>
IoT (Internet of Things)</h2>

<p><em>Libraries for programming devices of the IoT.</em></p>

<ul>
<li><a href="https://github.com/connectordb/connectordb" rel="nofollow">connectordb</a> - Open-Source Platform for Quantified Self &amp; IoT.</li>
<li><a href="https://github.com/goiot/devices" rel="nofollow">devices</a> - Suite of libraries for IoT devices, experimental for x/exp/io.</li>
<li><a href="https://github.com/xcodersun/eywa" rel="nofollow">eywa</a> - Project Eywa is essentially a connection manager that keeps track of connected devices.</li>
<li><a href="https://github.com/tibcosoftware/flogo" rel="nofollow">flogo</a> - Project Flogo is an Open Source Framework for IoT Edge Apps &amp; Integration.</li>
<li><a href="https://github.com/paypal/gatt" rel="nofollow">gatt</a> - Gatt is a Go package for building Bluetooth Low Energy peripherals.</li>
<li><a href="https://github.com/hybridgroup/gobot/" rel="nofollow">gobot</a> - Gobot is a framework for robotics, physical computing, and the Internet of Things.</li>
<li><a href="https://github.com/amimof/huego" rel="nofollow">huego</a> - An extensive Philips Hue client library for Go.</li>
<li><a href="https://github.com/vaelen/iot/" rel="nofollow">iot</a> - IoT is a simple framework for implementing a Google IoT Core device.</li>
<li><a href="https://github.com/Mainflux/mainflux" rel="nofollow">mainflux</a> - Industrial IoT Messaging and Device Management Server.</li>
<li><a href="https://periph.io/" rel="nofollow">periph</a> - Peripherals I/O to interface with low-level board facilities.</li>
<li><a href="https://github.com/sensorbee/sensorbee" rel="nofollow">sensorbee</a> - Lightweight stream processing engine for IoT.</li>
</ul>
<h2><a name="job-scheduler" class="anchor" href="#job-scheduler" rel="nofollow" aria-hidden="true"><span class="octicon octicon-link"></span></a>
Job Scheduler</h2>

<p><em>Libraries for scheduling jobs.</em></p>

<ul>
<li><a href="http://github.com/onatm/clockwerk" rel="nofollow">clockwerk</a> - Go package to schedule periodic jobs using a simple, fluent syntax.</li>
<li><a href="https://github.com/whiteShtef/clockwork" rel="nofollow">clockwork</a> - Simple and intuitive job scheduling library in Go.</li>
<li><a href="https://github.com/rk/go-cron" rel="nofollow">go-cron</a> - Simple Cron library for go that can execute closures or functions at varying intervals, from once a second to once a year on a specific date and time. Primarily for web applications and long running daemons.</li>
<li><a href="https://github.com/roylee0704/gron" rel="nofollow">gron</a> - Define time-based tasks using a simple Go API and Gron’s scheduler will run them accordingly.</li>
<li><a href="https://github.com/bamzi/jobrunner" rel="nofollow">JobRunner</a> - Smart and featureful cron job scheduler with job queuing and live monitoring built in.</li>
<li><a href="https://github.com/albrow/jobs" rel="nofollow">jobs</a> - Persistent and flexible background jobs library.</li>
<li><a href="https://github.com/kilgaloon/leprechaun" rel="nofollow">leprechaun</a> - Job scheduler that supports webhooks, crons and classic scheduling.</li>
<li><a href="https://github.com/carlescere/scheduler" rel="nofollow">scheduler</a> - Cronjobs scheduling made easy.</li>
</ul>
<h2><a name="json" class="anchor" href="#json" rel="nofollow" aria-hidden="true"><span class="octicon octicon-link"></span></a>
JSON</h2>

<p><em>Libraries for working with JSON.</em></p>

<ul>
<li><a href="https://github.com/spyzhov/ajson" rel="nofollow">ajson</a> - Abstract JSON for golang with JSONPath support.</li>
<li><a href="https://github.com/skanehira/gjo" rel="nofollow">gjo</a> - Small utility to create JSON objects.</li>
<li><a href="https://github.com/tidwall/gjson" rel="nofollow">GJSON</a> - Get a JSON value with one line of code.</li>
<li><a href="https://github.com/ddymko/go-jsonerror" rel="nofollow">go-jsonerror</a> - Go-JsonError is ment to allow us to easily create json response errors that follow the JsonApi spec.</li>
<li><a href="https://github.com/nicklaw5/go-respond" rel="nofollow">go-respond</a> - Go package for handling common HTTP JSON responses.</li>
<li><a href="https://github.com/elgs/gojq" rel="nofollow">gojq</a> - JSON query in Golang.</li>
<li><a href="https://github.com/ChimeraCoder/gojson" rel="nofollow">gojson</a> - Automatically generate Go (golang) struct definitions from example JSON.</li>
<li><a href="https://github.com/yazgazan/jaydiff" rel="nofollow">JayDiff</a> - JSON diff utility written in Go.</li>
<li><a href="https://github.com/wI2L/jettison" rel="nofollow">jettison</a> - High performance, reflection-less JSON encoder for Go.</li>
<li><a href="https://mholt.github.io/json-to-go/" rel="nofollow">JSON-to-Go</a> - Convert JSON to Go struct.</li>
<li><a href="https://github.com/m-zajac/json2go" rel="nofollow">json2go</a> - Advanced JSON to Go struct conversion. Provides package that can parse multiple JSON documents and create struct to fit them all.</li>
<li><a href="https://github.com/AmuzaTkts/jsonapi-errors" rel="nofollow">jsonapi-errors</a> - Go bindings based on the JSON API errors reference.</li>
<li><a href="https://github.com/miolini/jsonf" rel="nofollow">jsonf</a> - Console tool for highlighted formatting and struct query fetching JSON.</li>
<li><a href="https://github.com/ricardolonga/jsongo" rel="nofollow">jsongo</a> - Fluent API to make it easier to create Json objects.</li>
<li><a href="https://github.com/RichardKnop/jsonhal" rel="nofollow">jsonhal</a> - Simple Go package to make custom structs marshal into HAL compatible JSON responses.</li>
<li><a href="https://github.com/Qntfy/kazaam" rel="nofollow">kazaam</a> - API for arbitrary transformation of JSON documents.</li>
<li><a href="https://github.com/sanbornm/mp" rel="nofollow">mp</a> - Simple cli email parser. It currently takes stdin and outputs JSON.</li>
</ul>
<h2><a name="logging" class="anchor" href="#logging" rel="nofollow" aria-hidden="true"><span class="octicon octicon-link"></span></a>
Logging</h2>

<p><em>Libraries for generating and working with log files.</em></p>

<ul>
<li><a href="https://github.com/amoghe/distillog" rel="nofollow">distillog</a> - distilled levelled logging (think of it as stdlib + log levels).</li>
<li><a href="https://github.com/kpango/glg" rel="nofollow">glg</a> - glg is simple and fast leveled logging library for Go.</li>
<li><a href="https://github.com/lajosbencz/glo" rel="nofollow">glo</a> - PHP Monolog inspired logging facility with identical severity levels.</li>
<li><a href="https://github.com/golang/glog" rel="nofollow">glog</a> - Leveled execution logs for Go.</li>
<li><a href="https://github.com/utahta/go-cronowriter" rel="nofollow">go-cronowriter</a> - Simple writer that rotate log files automatically based on current date and time, like cronolog.</li>
<li><a href="https://github.com/subchen/go-log" rel="nofollow">go-log</a> - Simple and configurable Logging in Go, with level, formatters and writers.</li>
<li><a href="https://github.com/siddontang/go-log" rel="nofollow">go-log</a> - Log lib supports level and multi handlers.</li>
<li><a href="https://github.com/ian-kent/go-log" rel="nofollow">go-log</a> - Log4j implementation in Go.</li>
<li><a href="https://github.com/apsdehal/go-logger" rel="nofollow">go-logger</a> - Simple logger of Go Programs, with level handlers.</li>
<li><a href="https://github.com/sadlil/gologger" rel="nofollow">gologger</a> - Simple easy to use log lib for go, logs in Colored Console, Simple Console, File or Elasticsearch.</li>
<li><a href="https://github.com/aphistic/gomol" rel="nofollow">gomol</a> - Multiple-output, structured logging for Go with extensible logging outputs.</li>
<li><a href="https://github.com/One-com/gone/tree/master/log" rel="nofollow">gone/log</a> - Fast, extendable, full-featured, std-lib source compatible log library.</li>
<li><a href="https://github.com/ssgreg/journald" rel="nofollow">journald</a> - Go implementation of systemd Journal&#39;s native API for logging.</li>
<li><a href="https://github.com/aerogo/log" rel="nofollow">log</a> - An O(1) logging system that allows you to connect one log to multiple writers (e.g. stdout, a file and a TCP connection).</li>
<li><a href="https://github.com/apex/log" rel="nofollow">log</a> - Structured logging package for Go.</li>
<li><a href="https://github.com/go-playground/log" rel="nofollow">log</a> - Simple, configurable and scalable Structured Logging for Go.</li>
<li><a href="https://github.com/teris-io/log" rel="nofollow">log</a> - Structured log interface for Go cleanly separates logging facade from its implementation.</li>
<li><a href="https://github.com/firstrow/logvoyage" rel="nofollow">log-voyage</a> - Full-featured logging saas written in golang.</li>
<li><a href="https://github.com/inconshreveable/log15" rel="nofollow">log15</a> - Simple, powerful logging for Go.</li>
<li><a href="https://github.com/ewwwwwqm/logdump" rel="nofollow">logdump</a> - Package for multi-level logging.</li>
<li><a href="https://github.com/chzyer/logex" rel="nofollow">logex</a> - Golang log lib, supports tracking and level, wrap by standard log lib.</li>
<li><a href="https://github.com/azer/logger" rel="nofollow">logger</a> - Minimalistic logging library for Go.</li>
<li><a href="https://github.com/borderstech/logmatic" rel="nofollow">logmatic</a> - Colorized logger for Golang with dynamic log level configuration.</li>
<li><a href="https://github.com/mbndr/logo" rel="nofollow">logo</a> - Golang logger to different configurable writers.</li>
<li><a href="https://github.com/Sirupsen/logrus" rel="nofollow">logrus</a> - Structured logger for Go.</li>
<li><a href="https://github.com/cabify/logrusiowriter" rel="nofollow">logrusiowriter</a> - <code>io.Writer</code> implementation using <a href="https://github.com/sirupsen/logrus" rel="nofollow">logrus</a> logger.</li>
<li><a href="https://github.com/sebest/logrusly" rel="nofollow">logrusly</a> - <a href="https://github.com/sirupsen/logrus" rel="nofollow">logrus</a> plug-in to send errors to a <a href="https://www.loggly.com/" rel="nofollow">Loggly</a>.</li>
<li><a href="https://github.com/hashicorp/logutils" rel="nofollow">logutils</a> - Utilities for slightly better logging in Go (Golang) extending the standard logger.</li>
<li><a href="https://github.com/mgutz/logxi" rel="nofollow">logxi</a> - 12-factor app logger that is fast and makes you happy.</li>
<li><a href="https://github.com/natefinch/lumberjack" rel="nofollow">lumberjack</a> - Simple rolling logger, implements io.WriteCloser.</li>
<li><a href="https://github.com/jbrodriguez/mlog" rel="nofollow">mlog</a> - Simple logging module for go, with 5 levels, an optional rotating logfile feature and stdout/stderr output.</li>
<li><a href="https://github.com/francoispqt/onelog" rel="nofollow">onelog</a> - Onelog is a dead simple but very efficient JSON logger. It is the fastest JSON logger out there in all scenario. Also, it is one of the logger with the lowest allocation.</li>
<li><a href="https://github.com/go-ozzo/ozzo-log" rel="nofollow">ozzo-log</a> - High performance logging supporting log severity, categorization, and filtering. Can send filtered log messages to various targets (e.g. console, network, mail).</li>
<li><a href="https://github.com/arthurkiller/rollingWriter" rel="nofollow">rollingwriter</a> - RollingWriter is an auto-rotate <code>io.Writer</code> implementation with multi policies to provide log file rotation.</li>
<li><a href="https://github.com/cihub/seelog" rel="nofollow">seelog</a> - Logging functionality with flexible dispatching, filtering, and formatting.</li>
<li><a href="https://github.com/davecgh/go-spew" rel="nofollow">spew</a> - Implements a deep pretty printer for Go data structures to aid in debugging.</li>
<li><a href="https://github.com/alexcesaro/log" rel="nofollow">stdlog</a> - Stdlog is an object-oriented library providing leveled logging. It is very useful for cron jobs.</li>
<li><a href="https://github.com/hpcloud/tail" rel="nofollow">tail</a> - Go package striving to emulate the features of the BSD tail program.</li>
<li><a href="https://github.com/xfxdev/xlog" rel="nofollow">xlog</a> - Plugin architecture and flexible log system for Go, with level ctrl, multiple log target and custom log format.</li>
<li><a href="https://github.com/rs/xlog" rel="nofollow">xlog</a> - Structured logger for <code>net/context</code> aware HTTP handlers with flexible dispatching.</li>
<li><a href="https://github.com/uber-go/zap" rel="nofollow">zap</a> - Fast, structured, leveled logging in Go.</li>
<li><a href="https://github.com/rs/zerolog" rel="nofollow">zerolog</a> - Zero-allocation JSON logger.</li>
</ul>
<h2><a name="machine-learning" class="anchor" href="#machine-learning" rel="nofollow" aria-hidden="true"><span class="octicon octicon-link"></span></a>
Machine Learning</h2>

<p><em>Libraries for Machine Learning.</em></p>

<ul>
<li><a href="https://github.com/jbrukh/bayesian" rel="nofollow">bayesian</a> - Naive Bayesian Classification for Golang.</li>
<li><a href="https://github.com/ryanbressler/CloudForest" rel="nofollow">CloudForest</a> - Fast, flexible, multi-threaded ensembles of decision trees for machine learning in pure Go.</li>
<li><a href="https://github.com/MaxHalford/eaopt" rel="nofollow">eaopt</a> - An evolutionary optimization library.</li>
<li><a href="https://github.com/khezen/evoli" rel="nofollow">evoli</a> - Genetic Algorithm and Particle Swarm Optimization library.</li>
<li><a href="https://github.com/Fontinalis/fonet" rel="nofollow">fonet</a> - A Deep Neural Network library written in Go.</li>
<li><a href="https://github.com/e-XpertSolutions/go-cluster" rel="nofollow">go-cluster</a> - Go implementation of the k-modes and k-prototypes clustering algorithms.</li>
<li><a href="https://github.com/patrikeh/go-deep" rel="nofollow">go-deep</a> - A feature-rich neural network library in Go.</li>
<li><a href="https://github.com/white-pony/go-fann" rel="nofollow">go-fann</a> - Go bindings for Fast Artificial Neural Networks(FANN) library.</li>
<li><a href="https://github.com/thoj/go-galib" rel="nofollow">go-galib</a> - Genetic Algorithms library written in Go / golang.</li>
<li><a href="https://github.com/daviddengcn/go-pr" rel="nofollow">go-pr</a> - Pattern recognition package in Go lang.</li>
<li><a href="https://github.com/goml/gobrain" rel="nofollow">gobrain</a> - Neural Networks written in go.</li>
<li><a href="https://github.com/e-dard/godist" rel="nofollow">godist</a> - Various probability distributions, and associated methods.</li>
<li><a href="https://github.com/tomcraven/goga" rel="nofollow">goga</a> - Genetic algorithm library for Go.</li>
<li><a href="https://github.com/sjwhitworth/golearn" rel="nofollow">GoLearn</a> - General Machine Learning library for Go.</li>
<li><a href="https://github.com/danieldk/golinear" rel="nofollow">golinear</a> - liblinear bindings for Go.</li>
<li><a href="https://github.com/surenderthakran/gomind" rel="nofollow">GoMind</a> - A simplistic Neural Network Library in Go.</li>
<li><a href="https://github.com/cdipaolo/goml" rel="nofollow">goml</a> - On-line Machine Learning in Go.</li>
<li><a href="https://github.com/c-bata/goptuna" rel="nofollow">Goptuna</a> - Bayesian optimization framework for black-box functions written in Go. Everything will be optimized.</li>
<li><a href="https://github.com/timkaye11/goRecommend" rel="nofollow">goRecommend</a> - Recommendation Algorithms library written in Go.</li>
<li><a href="https://github.com/gorgonia/gorgonia" rel="nofollow">gorgonia</a> - graph-based computational library like Theano for Go that provides primitives for building various machine learning and neural network algorithms.</li>
<li><a href="https://github.com/zhenghaoz/gorse" rel="nofollow">gorse</a> - A High Performance Recommender System Package based on Collaborative Filtering for Go.</li>
<li><a href="https://github.com/asafschers/goscore" rel="nofollow">goscore</a> - Go Scoring API for PMML.</li>
<li><a href="https://github.com/otiai10/gosseract" rel="nofollow">gosseract</a> - Go package for OCR (Optical Character Recognition), by using Tesseract C++ library.</li>
<li><a href="https://github.com/datastream/libsvm" rel="nofollow">libsvm</a> - libsvm golang version derived work based on LIBSVM 3.14.</li>
<li><a href="https://github.com/jinyeom/neat" rel="nofollow">neat</a> - Plug-and-play, parallel Go framework for NeuroEvolution of Augmenting Topologies (NEAT).</li>
<li><a href="https://github.com/schuyler/neural-go" rel="nofollow">neural-go</a> - Multilayer perceptron network implemented in Go, with training via backpropagation.</li>
<li><a href="https://github.com/otiai10/ocrserver" rel="nofollow">ocrserver</a> - A simple OCR API server, seriously easy to be deployed by Docker and Heroku.</li>
<li><a href="https://github.com/owulveryck/onnx-go" rel="nofollow">onnx-go</a> - Go Interface to Open Neural Network Exchange (ONNX).</li>
<li><a href="https://github.com/ThePaw/probab" rel="nofollow">probab</a> - Probability distribution functions. Bayesian inference. Written in pure Go.</li>
<li><a href="https://github.com/muesli/regommend" rel="nofollow">regommend</a> - Recommendation &amp; collaborative filtering engine.</li>
<li><a href="https://github.com/eaigner/shield" rel="nofollow">shield</a> - Bayesian text classifier with flexible tokenizers and storage backends for Go.</li>
<li><a href="https://github.com/galeone/tfgo" rel="nofollow">tfgo</a> - Easy to use Tensorflow bindings: simplifies the usage of the official Tensorflow Go bindings. Define computational graphs in Go, load and execute models trained in Python.</li>
<li><a href="https://github.com/Xamber/Varis" rel="nofollow">Varis</a> - Golang Neural Network.</li>
</ul>
<h2><a name="messaging" class="anchor" href="#messaging" rel="nofollow" aria-hidden="true"><span class="octicon octicon-link"></span></a>
Messaging</h2>

<p><em>Libraries that implement messaging systems.</em></p>

<ul>
<li><a href="https://github.com/sideshow/apns2" rel="nofollow">APNs2</a> - HTTP/2 Apple Push Notification provider for Go — Send push notifications to iOS, tvOS, Safari and OSX apps.</li>
<li><a href="https://github.com/Clivern/Beaver" rel="nofollow">Beaver</a> - A real time messaging server to build a scalable in-app notifications, multiplayer games, chat apps in web and mobile apps.</li>
<li><a href="https://github.com/Jeffail/benthos" rel="nofollow">Benthos</a> - A message streaming bridge between a range of protocols.</li>
<li><a href="https://github.com/mustafaturan/bus" rel="nofollow">Bus</a> - Minimalist message bus implementation for internal communication.</li>
<li><a href="https://github.com/centrifugal/centrifugo" rel="nofollow">Centrifugo</a> - Real-time messaging (Websockets or SockJS) server in Go.</li>
<li><a href="https://github.com/jeroenrinzema/commander" rel="nofollow">Commander</a> - A high-level event driven consumer/producer supporting various &#34;dialects&#34; such as Apache Kafka.</li>
<li><a href="https://github.com/godbus/dbus" rel="nofollow">dbus</a> - Native Go bindings for D-Bus.</li>
<li><a href="https://github.com/appleboy/drone-line" rel="nofollow">drone-line</a> - Sending <a href="https://at.line.me/en" rel="nofollow">Line</a> notifications using a binary, docker or Drone CI.</li>
<li><a href="https://github.com/olebedev/emitter" rel="nofollow">emitter</a> - Emits events using Go way, with wildcard, predicates, cancellation possibilities and many other good wins.</li>
<li><a href="https://github.com/agoalofalife/event" rel="nofollow">event</a> - Implementation of the pattern observer.</li>
<li><a href="https://github.com/asaskevich/EventBus" rel="nofollow">EventBus</a> - The lightweight event bus with async compatibility.</li>
<li><a href="https://github.com/osamingo/gaurun-client" rel="nofollow">gaurun-client</a> - Gaurun Client written in Go.</li>
<li><a href="https://github.com/desertbit/glue" rel="nofollow">Glue</a> - Robust Go and Javascript Socket Library (Alternative to Socket.io).</li>
<li><a href="https://github.com/TheCreeper/go-notify" rel="nofollow">go-notify</a> - Native implementation of the freedesktop notification spec.</li>
<li><a href="https://github.com/nsqio/go-nsq" rel="nofollow">go-nsq</a> - the official Go package for NSQ.</li>
<li><a href="https://github.com/googollee/go-socket.io" rel="nofollow">go-socket.io</a> - socket.io library for golang, a realtime application framework.</li>
<li><a href="https://github.com/maxatome/go-vitotrol" rel="nofollow">go-vitotrol</a> - Client library to Viessmann Vitotrol web service.</li>
<li><a href="https://github.com/trivago/gollum" rel="nofollow">Gollum</a> - A n:m multiplexer that gathers messages from different sources and broadcasts them to a set of destinations.</li>
<li><a href="https://github.com/jcuga/golongpoll" rel="nofollow">golongpoll</a> - HTTP longpoll server library that makes web pub-sub simple.</li>
<li><a href="https://github.com/ian-kent/goose" rel="nofollow">goose</a> - Server Sent Events in Go.</li>
<li><a href="https://github.com/Terry-Mao/gopush-cluster" rel="nofollow">gopush-cluster</a> - gopush-cluster is a go push server cluster.</li>
<li><a href="https://github.com/appleboy/gorush" rel="nofollow">gorush</a> - Push notification server using <a href="https://github.com/sideshow/apns2" rel="nofollow">APNs2</a> and google <a href="https://github.com/google/go-gcm" rel="nofollow">GCM</a>.</li>
<li><a href="https://github.com/smancke/guble" rel="nofollow">guble</a> - Messaging server using push notifications (Google Firebase Cloud Messaging, Apple Push Notification services, SMS) as well as websockets, a REST API, featuring distributed operation and message-persistence.</li>
<li><a href="https://github.com/leandro-lugaresi/hub" rel="nofollow">hub</a> - A Message/Event Hub for Go applications, using publish/subscribe pattern with support for alias like rabbitMQ exchanges.</li>
<li><a href="https://github.com/socifi/jazz" rel="nofollow">jazz</a> - A simple RabbitMQ abstraction layer for queue administration and publishing and consuming of messages.</li>
<li><a href="https://github.com/RichardKnop/machinery" rel="nofollow">machinery</a> - Asynchronous task queue/job queue based on distributed message passing.</li>
<li><a href="https://github.com/go-mangos/mangos" rel="nofollow">mangos</a> - Pure go implementation of the Nanomsg (&#34;Scalable Protocols&#34;) with transport interoperability.</li>
<li><a href="https://github.com/olahol/melody" rel="nofollow">melody</a> - Minimalist framework for dealing with websocket sessions, includes broadcasting and automatic ping/pong handling.</li>
<li><a href="https://github.com/dunglas/mercure" rel="nofollow">Mercure</a> - Server and library to dispatch server-sent updates using the Mercure protocol (built on top of Server-Sent Events).</li>
<li><a href="https://github.com/vardius/message-bus" rel="nofollow">messagebus</a> - messagebus is a Go simple async message bus, perfect for using as event bus when doing event sourcing, CQRS, DDD.</li>
<li><a href="https://github.com/nats-io/nats" rel="nofollow">NATS Go Client</a> - Lightweight and high performance publish-subscribe and distributed queueing messaging system - this is the Go library.</li>
<li><a href="https://github.com/rafaeljesus/nsq-event-bus" rel="nofollow">nsq-event-bus</a> - A tiny wrapper around NSQ topic and channel.</li>
<li><a href="https://github.com/dailymotion/oplog" rel="nofollow">oplog</a> - Generic oplog/replication system for REST APIs.</li>
<li><a href="https://github.com/tuxychandru/pubsub" rel="nofollow">pubsub</a> - Simple pubsub package for go.</li>
<li><a href="https://github.com/rafaeljesus/rabbus" rel="nofollow">rabbus</a> - A tiny wrapper over amqp exchanges and queues.</li>
<li><a href="https://github.com/jandelgado/rabtap" rel="nofollow">rabtap</a> - RabbitMQ swiss army knife cli app.</li>
<li><a href="https://github.com/sybrexsys/RapidMQ" rel="nofollow">RapidMQ</a> - RapidMQ is a lightweight and reliable library for managing of the local messages queue.</li>
<li><a href="https://github.com/robinjoseph08/redisqueue" rel="nofollow">redisqueue</a> - redisqueue provides a producer and consumer of a queue that uses Redis streams.</li>
<li><a href="https://github.com/sbabiv/rmqconn" rel="nofollow">rmqconn</a> - RabbitMQ Reconnection. Wrapper over amqp.Connection and amqp.Dial. Allowing to do a reconnection when the connection is broken before forcing the call to the Close () method to be closed.</li>
<li><a href="https://github.com/Shopify/sarama" rel="nofollow">sarama</a> - Go library for Apache Kafka.</li>
<li><a href="https://github.com/uniqush/uniqush-push" rel="nofollow">Uniqush-Push</a> - Redis backed unified push service for server-side notifications to mobile devices.</li>
<li><a href="https://github.com/pebbe/zmq4" rel="nofollow">zmq4</a> - Go interface to ZeroMQ version 4. Also available for <a href="https://github.com/pebbe/zmq3" rel="nofollow">version 3</a> and <a href="https://github.com/pebbe/zmq2" rel="nofollow">version 2</a>.</li>
</ul>
<h2><a name="microsoft-office" class="anchor" href="#microsoft-office" rel="nofollow" aria-hidden="true"><span class="octicon octicon-link"></span></a>
Microsoft Office</h2>

<ul>
<li><a href="https://github.com/unidoc/unioffice" rel="nofollow">unioffice</a> - Pure go library for creating and processing Office Word (.docx), Excel (.xlsx) and Powerpoint (.pptx) documents.</li>
</ul>
<h3><a name="microsoft-excel" class="anchor" href="#microsoft-excel" rel="nofollow" aria-hidden="true"><span class="octicon octicon-link"></span></a>
Microsoft Excel</h3>

<p><em>Libraries for working with Microsoft Excel.</em></p>

<ul>
<li><a href="https://github.com/360EntSecGroup-Skylar/excelize" rel="nofollow">excelize</a> - Golang library for reading and writing Microsoft Excel™ (XLSX) files.</li>
<li><a href="https://github.com/szyhf/go-excel" rel="nofollow">go-excel</a> - A simple and light reader to read a relate-db-like excel as a table.</li>
<li><a href="https://github.com/fterrag/goxlsxwriter" rel="nofollow">goxlsxwriter</a> - Golang bindings for libxlsxwriter for writing XLSX (Microsoft Excel) files.</li>
<li><a href="https://github.com/tealeg/xlsx" rel="nofollow">xlsx</a> - Library to simplify reading the XML format used by recent version of Microsoft Excel in Go programs.</li>
<li><a href="https://github.com/plandem/xlsx" rel="nofollow">xlsx</a> - Fast and safe way to read/update your existing Microsoft Excel files in Go programs.</li>
</ul>
<h2><a name="miscellaneous" class="anchor" href="#miscellaneous" rel="nofollow" aria-hidden="true"><span class="octicon octicon-link"></span></a>
Miscellaneous</h2>
<h3><a name="dependency-injection" class="anchor" href="#dependency-injection" rel="nofollow" aria-hidden="true"><span class="octicon octicon-link"></span></a>
Dependency Injection</h3>

<p><em>Libraries for working with dependency injection.</em></p>

<ul>
<li><a href="https://github.com/magic003/alice" rel="nofollow">alice</a> - Additive dependency injection container for Golang.</li>
<li><a href="https://github.com/golobby/container" rel="nofollow">container</a> - A powerful IoC Container with fluent and easy-to-use interface.</li>
<li><a href="https://github.com/uber-go/dig" rel="nofollow">dig</a> - A reflection based dependency injection toolkit for Go.</li>
<li><a href="https://github.com/uber-go/fx" rel="nofollow">fx</a> - A dependency injection based application framework for Go (built on top of dig).</li>
<li><a href="https://github.com/vardius/gocontainer" rel="nofollow">gocontainer</a> - Simple Dependency Injection Container.</li>
<li><a href="https://github.com/defval/inject" rel="nofollow">inject</a> - A reflection based dependency injection container with simple interface.</li>
<li><a href="https://github.com/logrange/linker" rel="nofollow">linker</a> - A reflection based dependency injection and inversion of control library with components lifecycle support.</li>
<li><a href="https://github.com/Fs02/wire" rel="nofollow">wire</a> - Strict Runtime Dependency Injection for Golang.</li>
</ul>
<h3><a name="project-layout" class="anchor" href="#project-layout" rel="nofollow" aria-hidden="true"><span class="octicon octicon-link"></span></a>
Project Layout</h3>

<p><em>Unofficial set of patterns for structuring projects.</em></p>

<ul>
<li><a href="https://github.com/zitryss/go-sample" rel="nofollow">go-sample</a> - A sample layout for Go application projects with the real code.</li>
<li><a href="https://github.com/golang-standards/project-layout" rel="nofollow">golang-standards/project-layout</a> - Set of common historical and emerging project layout patterns in the Go ecosystem.</li>
<li><a href="https://github.com/sagikazarmark/modern-go-application" rel="nofollow">modern-go-application</a> - Go application boilerplate and example applying modern practices.</li>
<li><a href="https://github.com/catchplay/scaffold" rel="nofollow">scaffold</a> - Scaffold generates starter Go project layout. Lets you focus on business logic implemeted.</li>
</ul>
<h3><a name="strings" class="anchor" href="#strings" rel="nofollow" aria-hidden="true"><span class="octicon octicon-link"></span></a>
Strings</h3>

<p><em>Libraries for working with strings.</em></p>

<ul>
<li><a href="https://github.com/ozgio/strutil" rel="nofollow">strutil</a> - String utilities.</li>
<li><a href="https://github.com/huandu/xstrings" rel="nofollow">xstrings</a> - Collection of useful string functions ported from other languages.</li>
</ul>

<p><em>These libraries were placed here because none of the other categories seemed to fit.</em></p>

<ul>
<li><a href="https://github.com/mudler/anagent" rel="nofollow">anagent</a> - Minimalistic, pluggable Golang evloop/timer handler with dependency-injection.</li>
<li><a href="https://github.com/antchfx/antch" rel="nofollow">antch</a> - A fast, powerful and extensible web crawling &amp; scraping framework.</li>
<li><a href="https://github.com/mholt/archiver" rel="nofollow">archiver</a> - Library and command for making and extracting .zip and .tar.gz archives.</li>
<li><a href="https://github.com/artyom/autoflags" rel="nofollow">autoflags</a> - Go package to automatically define command line flags from struct fields.</li>
<li><a href="https://github.com/kirillDanshin/avgRating" rel="nofollow">avgRating</a> - Calculate average score and rating based on Wilson Score Equation.</li>
<li><a href="https://github.com/dimiro1/banner" rel="nofollow">banner</a> - Add beautiful banners into your Go applications.</li>
<li><a href="https://github.com/mojocn/base64Captcha" rel="nofollow">base64Captcha</a> - Base64captch supports digit, number, alphabet, arithmetic, audio and digit-alphabet captcha.</li>
<li><a href="https://github.com/distatus/battery" rel="nofollow">battery</a> - Cross-platform, normalized battery information library.</li>
<li><a href="https://github.com/icza/bitio" rel="nofollow">bitio</a> - Highly optimized bit-level Reader and Writer for Go.</li>
<li><a href="https://github.com/digitalcrab/browscap_go" rel="nofollow">browscap_go</a> - GoLang Library for <a href="http://browscap.org/" rel="nofollow">Browser Capabilities Project</a>.</li>
<li><a href="https://github.com/steambap/captcha" rel="nofollow">captcha</a> - Package captcha provides an easy to use, unopinionated API for captcha generation.</li>
<li><a href="https://github.com/cstockton/go-conv" rel="nofollow">conv</a> - Package conv provides fast and intuitive conversions across Go types.</li>
<li><a href="https://github.com/miolini/datacounter" rel="nofollow">datacounter</a> - Go counters for readers/writer/http.ResponseWriter.</li>
<li><a href="https://github.com/go-ffmt/ffmt" rel="nofollow">ffmt</a> - Beautify data display for Humans.</li>
<li><a href="https://github.com/gabrie30/ghorg" rel="nofollow">ghorg</a> - Quickly clone an entire org/users repositories into one directory - Supports GitHub, GitLab, and Bitbucket.</li>
<li><a href="https://github.com/jolestar/go-commons-pool" rel="nofollow">go-commons-pool</a> - Generic object pool for Golang.</li>
<li><a href="https://github.com/go-openapi" rel="nofollow">go-openapi</a> - Collection of packages to parse and utilize open-api schemas.</li>
<li><a href="https://github.com/eapache/go-resiliency" rel="nofollow">go-resiliency</a> - Resiliency patterns for golang.</li>
<li><a href="https://github.com/gen2brain/go-unarr" rel="nofollow">go-unarr</a> - Decompression library for RAR, TAR, ZIP and 7z archives.</li>
<li><a href="https://github.com/brianvoe/gofakeit" rel="nofollow">gofakeit</a> - Random data generator written in go.</li>
<li><a href="https://github.com/antham/gommit" rel="nofollow">gommit</a> - Analyze git commit messages to ensure they follow defined patterns.</li>
<li><a href="https://github.com/shirou/gopsutil" rel="nofollow">gopsutil</a> - Cross-platform library for retrieving process and system utilization(CPU, Memory, Disks, etc).</li>
<li><a href="https://github.com/osamingo/gosh" rel="nofollow">gosh</a> - Provide Go Statistics Handler, Struct, Measure Method.</li>
<li><a href="https://github.com/haxpax/gosms" rel="nofollow">gosms</a> - Your own local SMS gateway in Go that can be used to send SMS.</li>
<li><a href="https://github.com/cabify/gotoprom" rel="nofollow">gotoprom</a> - Type-safe metrics builder wrapper library for the official Prometheus client.</li>
<li><a href="https://github.com/pariz/gountries" rel="nofollow">gountries</a> - Package that exposes country and subdivision data.</li>
<li><a href="https://github.com/dimiro1/health" rel="nofollow">health</a> - Easy to use, extensible health check library.</li>
<li><a href="https://github.com/etherlabsio/healthcheck" rel="nofollow">healthcheck</a> - An opinionated and concurrent health-check HTTP handler for RESTful services.</li>
<li><a href="https://github.com/Wing924/hostutils" rel="nofollow">hostutils</a> - A golang library for packing and unpacking FQDNs list.</li>
<li><a href="https://github.com/osamingo/indigo" rel="nofollow">indigo</a> - Distributed unique ID generator of using Sonyflake and encoded by Base58.</li>
<li><a href="https://github.com/hyperboloide/lk" rel="nofollow">lk</a> - A simple licensing library for golang.</li>
<li><a href="https://github.com/llir/llvm" rel="nofollow">llvm</a> - Library for interacting with LLVM IR in pure Go.</li>
<li><a href="https://github.com/pascaldekloe/metrics" rel="nofollow">metrics</a> - Library for metrics instrumentation and Prometheus exposition.</li>
<li><a href="https://github.com/alwindoss/morse" rel="nofollow">morse</a> - Library to convert to and from morse code.</li>
<li><a href="https://github.com/lrita/numa" rel="nofollow">numa</a> - NUMA is a utility library, which is written in go. It help us to write some NUMA-AWARED code.</li>
<li><a href="https://github.com/hyperboloide/pdfgen" rel="nofollow">pdfgen</a> - HTTP service to generate PDF from Json requests.</li>
<li><a href="https://github.com/mavihq/persian" rel="nofollow">persian</a> - Some utilities for Persian language in go.</li>
<li><a href="https://github.com/aofei/sandid" rel="nofollow">sandid</a> - Every grain of sand on earth has its own ID.</li>
<li><a href="https://github.com/Wing924/shellwords" rel="nofollow">shellwords</a> - A Golang library to manipulate strings according to the word parsing rules of the UNIX Bourne shell.</li>
<li><a href="https://github.com/teris-io/shortid" rel="nofollow">shortid</a> - Distributed generation of super short, unique, non-sequential, URL friendly IDs.</li>
<li><a href="https://github.com/qmuntal/stateless" rel="nofollow">stateless</a> - A fluent library for creating state machines.</li>
<li><a href="https://github.com/go-playground/stats" rel="nofollow">stats</a> - Monitors Go MemStats + System stats such as Memory, Swap and CPU and sends via UDP anywhere you want for logging etc...</li>
<li><a href="https://github.com/hackebrot/turtle" rel="nofollow">turtle</a> - Emojis for Go.</li>
<li><a href="https://github.com/pantrif/url-shortener" rel="nofollow">url-shortener</a> - A modern, powerful, and robust URL shortener microservice with mysql support.</li>
<li><a href="https://github.com/azr/generators/tree/master/varhandler" rel="nofollow">VarHandler</a> - Generate boilerplate http input and output handling.</li>
<li><a href="https://github.com/rkoesters/xdg" rel="nofollow">xdg</a> - FreeDesktop.org (xdg) Specs implemented in Go.</li>
<li><a href="https://github.com/go-xkg/xkg" rel="nofollow">xkg</a> - X Keyboard Grabber.</li>
</ul>
<h2><a name="natural-language-processing" class="anchor" href="#natural-language-processing" rel="nofollow" aria-hidden="true"><span class="octicon octicon-link"></span></a>
Natural Language Processing</h2>

<p><em>Libraries for working with human languages.</em></p>

<ul>
<li><a href="https://github.com/rylans/getlang" rel="nofollow">getlang</a> - Fast natural language detection package.</li>
<li><a href="https://github.com/nicksnyder/go-i18n/" rel="nofollow">go-i18n</a> - Package and an accompanying tool to work with localized text.</li>
<li><a href="https://github.com/dveselov/mystem" rel="nofollow">go-mystem</a> - CGo bindings to Yandex.Mystem - russian morphology analyzer.</li>
<li><a href="https://github.com/nuance/go-nlp" rel="nofollow">go-nlp</a> - Utilities for working with discrete probability distributions and other tools useful for doing NLP work.</li>
<li><a href="https://github.com/mozillazg/go-pinyin" rel="nofollow">go-pinyin</a> - CN Hanzi to Hanyu Pinyin converter.</li>
<li><a href="https://github.com/agonopol/go-stem" rel="nofollow">go-stem</a> - Implementation of the porter stemming algorithm.</li>
<li><a href="https://github.com/mozillazg/go-unidecode" rel="nofollow">go-unidecode</a> - ASCII transliterations of Unicode text.</li>
<li><a href="https://github.com/danieldk/go2vec" rel="nofollow">go2vec</a> - Reader and utility functions for word2vec embeddings.</li>
<li><a href="https://github.com/yanyiwu/gojieba" rel="nofollow">gojieba</a> - This is a Go implementation of <a href="https://github.com/fxsjy/jieba" rel="nofollow">jieba</a> which a Chinese word splitting algorithm.</li>
<li><a href="https://github.com/rjohnsondev/golibstemmer" rel="nofollow">golibstemmer</a> - Go bindings for the snowball libstemmer library including porter 2.</li>
<li><a href="https://github.com/xujiajun/gotokenizer" rel="nofollow">gotokenizer</a> - A tokenizer based on the dictionary and Bigram language models for Golang. (Now only support chinese segmentation)</li>
<li><a href="https://github.com/fiam/gounidecode" rel="nofollow">gounidecode</a> - Unicode transliterator (also known as unidecode) for Go.</li>
<li><a href="https://github.com/go-ego/gse" rel="nofollow">gse</a> - Go efficient text segmentation; support english, chinese, japanese and other.</li>
<li><a href="https://github.com/goodsign/icu" rel="nofollow">icu</a> - Cgo binding for icu4c C library detection and conversion functions. Guaranteed compatibility with version 50.1.</li>
<li><a href="https://github.com/ikawaha/kagome" rel="nofollow">kagome</a> - JP morphological analyzer written in pure Go.</li>
<li><a href="https://github.com/goodsign/libtextcat" rel="nofollow">libtextcat</a> - Cgo binding for libtextcat C library. Guaranteed compatibility with version 2.2.</li>
<li><a href="https://github.com/awsong/MMSEGO" rel="nofollow">MMSEGO</a> - This is a GO implementation of <a href="http://technology.chtsai.org/mmseg/" rel="nofollow">MMSEG</a> which a Chinese word splitting algorithm.</li>
<li><a href="https://github.com/Shixzie/nlp" rel="nofollow">nlp</a> - Extract values from strings and fill your structs with nlp.</li>
<li><a href="https://github.com/james-bowman/nlp" rel="nofollow">nlp</a> - Go Natural Language Processing library supporting LSA (Latent Semantic Analysis).</li>
<li><a href="https://github.com/rookii/paicehusk" rel="nofollow">paicehusk</a> - Golang implementation of the Paice/Husk Stemming Algorithm.</li>
<li><a href="https://github.com/striker2000/petrovich" rel="nofollow">petrovich</a> - Petrovich is the library which inflects Russian names to given grammatical case.</li>
<li><a href="https://github.com/a2800276/porter" rel="nofollow">porter</a> - This is a fairly straightforward port of Martin Porter&#39;s C implementation of the Porter stemming algorithm.</li>
<li><a href="https://github.com/zhenjl/porter2" rel="nofollow">porter2</a> - Really fast Porter 2 stemmer.</li>
<li><a href="https://github.com/jdkato/prose" rel="nofollow">prose</a> - Library for text processing that supports tokenization, part-of-speech tagging, named-entity extraction, and more. English only.</li>
<li><a href="https://github.com/Obaied/RAKE.go" rel="nofollow">RAKE.go</a> - Go port of the Rapid Automatic Keyword Extraction Algorithm (RAKE).</li>
<li><a href="https://github.com/blevesearch/segment" rel="nofollow">segment</a> - Go library for performing Unicode Text Segmentation as described in <a href="http://www.unicode.org/reports/tr29/" rel="nofollow">Unicode Standard Annex #29</a></li>
<li><a href="https://github.com/neurosnap/sentences" rel="nofollow">sentences</a> - Sentence tokenizer:  converts text into a list of sentences.</li>
<li><a href="https://github.com/osamingo/shamoji" rel="nofollow">shamoji</a> - The shamoji is word filtering package written in Go.</li>
<li><a href="https://github.com/goodsign/snowball" rel="nofollow">snowball</a> - Snowball stemmer port (cgo wrapper) for Go. Provides word stem extraction functionality <a href="http://snowball.tartarus.org/" rel="nofollow">Snowball native</a>.</li>
<li><a href="https://github.com/dchest/stemmer" rel="nofollow">stemmer</a> - Stemmer packages for Go programming language. Includes English and German stemmers.</li>
<li><a href="https://github.com/pebbe/textcat" rel="nofollow">textcat</a> - Go package for n-gram based text categorization, with support for utf-8 and raw text.</li>
<li><a href="https://github.com/abadojack/whatlanggo" rel="nofollow">whatlanggo</a> - Natural language detection package for Go. Supports 84 languages and 24 scripts (writing systems e.g. Latin, Cyrillic, etc).</li>
<li><a href="https://github.com/olebedev/when" rel="nofollow">when</a> - Natural EN and RU language date/time parser with pluggable rules.</li>
</ul>
<h2><a name="networking" class="anchor" href="#networking" rel="nofollow" aria-hidden="true"><span class="octicon octicon-link"></span></a>
Networking</h2>

<p><em>Libraries for working with various layers of the network.</em></p>

<ul>
<li><a href="https://github.com/mdlayher/arp" rel="nofollow">arp</a> - Package arp implements the ARP protocol, as described in RFC 826.</li>
<li><a href="https://github.com/stabbycutyou/buffstreams" rel="nofollow">buffstreams</a> - Streaming protocolbuffer data over TCP made easy.</li>
<li><a href="https://github.com/zubairhamed/canopus" rel="nofollow">canopus</a> - CoAP Client/Server implementation (RFC 7252).</li>
<li><a href="https://github.com/yl2chen/cidranger" rel="nofollow">cidranger</a> - Fast IP to CIDR lookup for Go.</li>
<li><a href="https://github.com/mdlayher/dhcp6" rel="nofollow">dhcp6</a> - Package dhcp6 implements a DHCPv6 server, as described in RFC 3315.</li>
<li><a href="https://github.com/miekg/dns" rel="nofollow">dns</a> - Go library for working with DNS.</li>
<li><a href="https://github.com/songgao/ether" rel="nofollow">ether</a> - Cross-platform Go package for sending and receiving ethernet frames.</li>
<li><a href="https://github.com/mdlayher/ethernet" rel="nofollow">ethernet</a> - Package ethernet implements marshaling and unmarshaling of IEEE 802.3 Ethernet II frames and IEEE 802.1Q VLAN tags.</li>
<li><a href="https://github.com/valyala/fasthttp" rel="nofollow">fasthttp</a> - Package fasthttp is a fast HTTP implementation for Go, up to 10 times faster than net/http.</li>
<li><a href="https://github.com/fortio/fortio" rel="nofollow">fortio</a> - Load testing library and command line tool, advanced echo server and web UI. Allows to specify a set query-per-second load and record latency histograms and other useful stats and graph them. Tcp, Http, gRPC.</li>
<li><a href="https://github.com/jlaffaye/ftp" rel="nofollow">ftp</a> - Package ftp implements a FTP client as described in <a href="http://tools.ietf.org/html/rfc959" rel="nofollow">RFC 959</a>.</li>
<li><a href="https://github.com/Allenxuxu/gev" rel="nofollow">gev</a> - gev is a lightweight, fast non-blocking TCP network library based on Reactor mode.</li>
<li><a href="https://github.com/DrmagicE/gmqtt" rel="nofollow">gmqtt</a> - Gmqtt is a flexible, high-performance MQTT broker library that fully implements the MQTT protocol V3.1.1.</li>
<li><a href="https://github.com/panjf2000/gnet" rel="nofollow">gnet</a> - <code>gnet</code> is a high-performance, lightweight, nonblocking, event-loop networking library written in pure Go.</li>
<li><a href="https://github.com/google/gnxi" rel="nofollow">gNxI</a> - A collection of tools for Network Management that use the gNMI and gNOI protocols.</li>
<li><a href="https://github.com/hashicorp/go-getter" rel="nofollow">go-getter</a> - Go library for downloading files or directories from various sources using a URL.</li>
<li><a href="https://github.com/joeig/go-powerdns" rel="nofollow">go-powerdns</a> - PowerDNS API bindings for Golang.</li>
<li><a href="https://github.com/ccding/go-stun" rel="nofollow">go-stun</a> - Go implementation of the STUN client (RFC 3489 and RFC 5389).</li>
<li><a href="https://github.com/osrg/gobgp" rel="nofollow">gobgp</a> - BGP implemented in the Go Programming Language.</li>
<li><a href="https://github.com/sunwxg/golibwireshark" rel="nofollow">golibwireshark</a> - Package golibwireshark use libwireshark library to decode pcap file and analyse dissection data.</li>
<li><a href="https://github.com/google/gopacket" rel="nofollow">gopacket</a> - Go library for packet processing with libpcap bindings.</li>
<li><a href="https://github.com/akrennmair/gopcap" rel="nofollow">gopcap</a> - Go wrapper for libpcap.</li>
<li><a href="https://github.com/sunwxg/goshark" rel="nofollow">goshark</a> - Package goshark use tshark to decode IP packet and create data struct to analyse packet.</li>
<li><a href="https://github.com/soniah/gosnmp" rel="nofollow">gosnmp</a> - Native Go library for performing SNMP actions.</li>
<li><a href="https://github.com/gansidui/gotcp" rel="nofollow">gotcp</a> - Go package for quickly writing tcp applications.</li>
<li><a href="https://github.com/cavaliercoder/grab" rel="nofollow">grab</a> - Go package for managing file downloads.</li>
<li><a href="https://github.com/koofr/graval" rel="nofollow">graval</a> - Experimental FTP server framework.</li>
<li><a href="https://github.com/gchaincl/httplab" rel="nofollow">HTTPLab</a> - HTTPLabs let you inspect HTTP requests and forge responses.</li>
<li><a href="https://github.com/c-robinson/iplib" rel="nofollow">iplib</a> - Library for working with IP addresses (net.IP, net.IPNet), inspired by python <a href="https://docs.python.org/3/library/ipaddress.html" rel="nofollow">ipaddress</a> and ruby <a href="https://ruby-doc.org/stdlib-2.5.1/libdoc/ipaddr/rdoc/IPAddr.html" rel="nofollow">ipaddr</a></li>
<li><a href="https://github.com/udhos/jazigo" rel="nofollow">jazigo</a> - Jazigo is a tool written in Go for retrieving configuration for multiple network devices.</li>
<li><a href="https://github.com/xtaci/kcp-go" rel="nofollow">kcp-go</a> - KCP - Fast and Reliable ARQ Protocol.</li>
<li><a href="https://github.com/xtaci/kcptun" rel="nofollow">kcptun</a> - Extremely simple &amp; fast udp tunnel based on KCP protocol.</li>
<li><a href="https://github.com/fanux/lhttp" rel="nofollow">lhttp</a> - Powerful websocket framework, build your IM server more easily.</li>
<li><a href="https://github.com/ian-kent/linkio" rel="nofollow">linkio</a> - Network link speed simulation for Reader/Writer interfaces.</li>
<li><a href="https://github.com/kirillDanshin/llb" rel="nofollow">llb</a> - It&#39;s a very simple but quick backend for proxy servers. Can be useful for fast redirection to predefined domain with zero memory allocation and fast response.</li>
<li><a href="https://github.com/hashicorp/mdns" rel="nofollow">mdns</a> - Simple mDNS (Multicast DNS) client/server library in Golang.</li>
<li><a href="https://eclipse.org/paho/clients/golang/" rel="nofollow">mqttPaho</a> - The Paho Go Client provides an MQTT client library for connection to MQTT brokers via TCP, TLS or WebSockets.</li>
<li><a href="https://github.com/intel-go/nff-go" rel="nofollow">NFF-Go</a> - Framework for rapid development of performant network functions for cloud and bare-metal (former YANFF).</li>
<li><a href="https://github.com/aerogo/packet" rel="nofollow">packet</a> - Send packets over TCP and UDP. It can buffer messages and hot-swap connections if needed.</li>
<li><a href="https://github.com/schollz/peerdiscovery" rel="nofollow">peerdiscovery</a> - Pure Go library for cross-platform local peer discovery using UDP multicast.</li>
<li><a href="https://github.com/aybabtme/portproxy" rel="nofollow">portproxy</a> - Simple TCP proxy which adds CORS support to API&#39;s which don&#39;t support it.</li>
<li><a href="https://github.com/polera/publicip" rel="nofollow">publicip</a> - Package publicip returns your public facing IPv4 address (internet egress).</li>
<li><a href="https://github.com/lucas-clemente/quic-go" rel="nofollow">quic-go</a> - An implementation of the QUIC protocol in pure Go.</li>
<li><a href="https://github.com/mdlayher/raw" rel="nofollow">raw</a> - Package raw enables reading and writing data at the device driver level for a network interface.</li>
<li><a href="https://github.com/pkg/sftp" rel="nofollow">sftp</a> - Package sftp implements the SSH File Transfer Protocol as described in <a href="https://filezilla-project.org/specs/draft-ietf-secsh-filexfer-02.txt" rel="nofollow">https://filezilla-project.org/specs/draft-ietf-secsh-filexfer-02.txt</a>.</li>
<li><a href="https://github.com/gliderlabs/ssh" rel="nofollow">ssh</a> - Higher-level API for building SSH servers (wraps crypto/ssh).</li>
<li><a href="https://github.com/eduardonunesp/sslb" rel="nofollow">sslb</a> - It&#39;s a Super Simples Load Balancer, just a little project to achieve some kind of performance.</li>
<li><a href="https://github.com/go-rtc/stun" rel="nofollow">stun</a> - Go implementation of RFC 5389 STUN protocol.</li>
<li><a href="https://github.com/firstrow/tcp_server" rel="nofollow">tcp_server</a> - Go library for building tcp servers faster.</li>
<li><a href="https://github.com/two/tspool" rel="nofollow">tspool</a> - A TCP Library use worker pool to improve performance and protect your server.</li>
<li><a href="https://github.com/anacrolix/utp" rel="nofollow">utp</a> - Go uTP micro transport protocol implementation.</li>
<li><a href="https://github.com/songgao/water" rel="nofollow">water</a> - Simple TUN/TAP library.</li>
<li><a href="https://github.com/pions/webrtc" rel="nofollow">webrtc</a> - A pure Go implementation of the WebRTC API.</li>
<li><a href="https://github.com/masterzen/winrm" rel="nofollow">winrm</a> - Go WinRM client to remotely execute commands on Windows machines.</li>
<li><a href="https://github.com/xfxdev/xtcp" rel="nofollow">xtcp</a> - TCP Server Framework with simultaneous full duplex communication,graceful shutdown,custom protocol.</li>
</ul>
<h3><a name="http-clients" class="anchor" href="#http-clients" rel="nofollow" aria-hidden="true"><span class="octicon octicon-link"></span></a>
HTTP Clients</h3>

<p><em>Libraries for making HTTP requests.</em></p>

<ul>
<li><a href="https://github.com/h2non/gentleman" rel="nofollow">gentleman</a> - Full-featured plugin-driven HTTP client library.</li>
<li><a href="https://github.com/smallnest/goreq" rel="nofollow">goreq</a> - Enhanced simplified HTTP client based on gorequest.</li>
<li><a href="https://github.com/levigross/grequests" rel="nofollow">grequests</a> - A Go &#34;clone&#34; of the great and famous Requests library.</li>
<li><a href="https://github.com/gojektech/heimdall" rel="nofollow">heimdall</a> - An enchanced http client with retry and hystrix capabilities.</li>
<li><a href="https://github.com/sethgrid/pester" rel="nofollow">pester</a> - Go HTTP client calls with retries, backoff, and concurrency.</li>
<li><a href="https://github.com/ddo/rq" rel="nofollow">rq</a> - A nicer interface for golang stdlib HTTP client.</li>
<li><a href="https://github.com/dghubble/sling" rel="nofollow">sling</a> - Sling is a Go HTTP client library for creating and sending API requests.</li>
<li><a href="https://github.com/winterssy/sreq" rel="nofollow">sreq</a> - A simple, user-friendly and concurrent safe HTTP request library for Go.</li>
</ul>
<h2><a name="opengl" class="anchor" href="#opengl" rel="nofollow" aria-hidden="true"><span class="octicon octicon-link"></span></a>
OpenGL</h2>

<p><em>Libraries for using OpenGL in Go.</em></p>

<ul>
<li><a href="https://github.com/go-gl/gl" rel="nofollow">gl</a> - Go bindings for OpenGL (generated via glow).</li>
<li><a href="https://github.com/go-gl/glfw" rel="nofollow">glfw</a> - Go bindings for GLFW 3.</li>
<li><a href="https://github.com/goxjs/gl" rel="nofollow">goxjs/gl</a> - Go cross-platform OpenGL bindings (OS X, Linux, Windows, browsers, iOS, Android).</li>
<li><a href="https://github.com/goxjs/glfw" rel="nofollow">goxjs/glfw</a> - Go cross-platform glfw library for creating an OpenGL context and receiving events.</li>
<li><a href="https://github.com/go-gl/mathgl" rel="nofollow">mathgl</a> - Pure Go math package specialized for 3D math, with inspiration from GLM.</li>
</ul>
<h2><a name="orm" class="anchor" href="#orm" rel="nofollow" aria-hidden="true"><span class="octicon octicon-link"></span></a>
ORM</h2>

<p><em>Libraries that implement Object-Relational Mapping or datamapping techniques.</em></p>

<ul>
<li><a href="https://github.com/astaxie/beego/tree/master/orm" rel="nofollow">beego orm</a> - Powerful orm framework for go. Support: pq/mysql/sqlite3.</li>
<li><a href="https://github.com/jschoedt/go-firestorm" rel="nofollow">go-firestorm</a> - A simple ORM for Google/Firebase Cloud Firestore.</li>
<li><a href="https://github.com/go-pg/pg" rel="nofollow">go-pg</a> - PostgreSQL ORM with focus on PostgreSQL specific features and performance.</li>
<li><a href="https://github.com/jirfag/go-queryset" rel="nofollow">go-queryset</a> - 100% type-safe ORM with code generation and MySQL, PostgreSQL, Sqlite3, SQL Server support based on GORM.</li>
<li><a href="https://github.com/huandu/go-sqlbuilder" rel="nofollow">go-sqlbuilder</a> - A flexible and powerful SQL string builder library plus a zero-config ORM.</li>
<li><a href="https://github.com/gosuri/go-store" rel="nofollow">go-store</a> - Simple and fast Redis backed key-value store library for Go.</li>
<li><a href="https://github.com/jinzhu/gorm" rel="nofollow">GORM</a> - The fantastic ORM library for Golang, aims to be developer friendly.</li>
<li><a href="https://github.com/go-gorp/gorp" rel="nofollow">gorp</a> - Go Relational Persistence, ORM-ish library for Go.</li>
<li><a href="https://github.com/Fs02/grimoire" rel="nofollow">grimoire</a> - Grimoire is a database access layer and validation for golang. (Support: MySQL, PostgreSQL and SQLite3).</li>
<li><a href="https://github.com/abrahambotros/lore" rel="nofollow">lore</a> - Simple and lightweight pseudo-ORM/pseudo-struct-mapping environment for Go.</li>
<li><a href="https://github.com/dadleyy/marlow" rel="nofollow">Marlow</a> - Generated ORM from project structs for compile time safety assurances.</li>
<li><a href="https://github.com/gobuffalo/pop" rel="nofollow">pop/soda</a> - Database migration, creation, ORM, etc... for MySQL, PostgreSQL, and SQLite.</li>
<li><a href="https://github.com/coocood/qbs" rel="nofollow">QBS</a> - Stands for Query By Struct. A Go ORM.</li>
<li><a href="https://github.com/go-reform/reform" rel="nofollow">reform</a> - Better ORM for Go, based on non-empty interfaces and code generation.</li>
<li><a href="https://github.com/volatiletech/sqlboiler" rel="nofollow">SQLBoiler</a> - ORM generator. Generate a featureful and blazing-fast ORM tailored to your database schema.</li>
<li><a href="https://github.com/upper/db" rel="nofollow">upper.io/db</a> - Single interface for interacting with different data sources through the use of adapters that wrap mature database drivers.</li>
<li><a href="https://github.com/go-xorm/xorm" rel="nofollow">Xorm</a> - Simple and powerful ORM for Go.</li>
<li><a href="https://github.com/albrow/zoom" rel="nofollow">Zoom</a> - Blazing-fast datastore and querying engine built on Redis.</li>
</ul>
<h2><a name="package-management" class="anchor" href="#package-management" rel="nofollow" aria-hidden="true"><span class="octicon octicon-link"></span></a>
Package Management</h2>

<p><em>Official tooling for dependency and package management</em></p>

<ul>
<li><a href="https://golang.org/cmd/go/#hdr-Modules__module_versions__and_more" rel="nofollow">go modules</a> - Modules are the unit of source code interchange and versioning. The go command has direct support for working with modules, including recording and resolving dependencies on other modules.</li>
</ul>

<p><em>Official experimental tooling for package management</em></p>

<ul>
<li><a href="https://github.com/golang/dep" rel="nofollow">dep</a> - Go dependency tool.</li>
<li><a href="https://go.googlesource.com/vgo/" rel="nofollow">vgo</a> - Versioned Go.</li>
</ul>

<p><em>Unofficial libraries for package and dependency management.</em></p>

<ul>
<li><a href="https://github.com/LyricalSecurity/gigo" rel="nofollow">gigo</a> - PIP-like dependency tool for golang, with support for private repositories and hashes.</li>
<li><a href="https://github.com/Masterminds/glide" rel="nofollow">glide</a> - Manage your golang vendor and vendored packages with ease. Inspired by tools like Maven, Bundler, and Pip.</li>
<li><a href="https://github.com/tools/godep" rel="nofollow">godep</a> - dependency tool for go, godep helps build packages reproducibly by fixing their dependencies.</li>
<li><a href="https://github.com/mattn/gom" rel="nofollow">gom</a> - Go Manager - bundle for go.</li>
<li><a href="https://github.com/nitrous-io/goop" rel="nofollow">goop</a> - Simple dependency manager for Go (golang), inspired by Bundler.</li>
<li><a href="https://github.com/lunny/gop" rel="nofollow">gop</a> - Build and manage your Go applications out of GOPATH.</li>
<li><a href="https://github.com/gpmgo/gopm" rel="nofollow">gopm</a> - Go Package Manager.</li>
<li><a href="https://github.com/kardianos/govendor" rel="nofollow">govendor</a> - Go Package Manager. Go vendor tool that works with the standard vendor file.</li>
<li><a href="https://github.com/pote/gpm" rel="nofollow">gpm</a> - Barebones dependency manager for Go.</li>
<li><a href="https://github.com/VividCortex/johnny-deps" rel="nofollow">johnny-deps</a> - Minimal dependency version using Git.</li>
<li><a href="https://github.com/raydac/mvn-golang" rel="nofollow">mvn-golang</a> - plugin that provides way for auto-loading of Golang SDK, dependency management and start build environment in Maven project infrastructure.</li>
<li><a href="https://github.com/jingweno/nut" rel="nofollow">nut</a> - Vendor Go dependencies.</li>
<li><a href="https://github.com/DamnWidget/VenGO" rel="nofollow">VenGO</a> - create and manage exportable isolated go virtual environments.</li>
</ul>
<h2><a name="performance" class="anchor" href="#performance" rel="nofollow" aria-hidden="true"><span class="octicon octicon-link"></span></a>
Performance</h2>

<ul>
<li><a href="https://github.com/jaegertracing/jaeger" rel="nofollow">jaeger</a> - A distributed tracing system.</li>
<li><a href="https://github.com/pkg/profile" rel="nofollow">profile</a> - Simple profiling support package for Go.</li>
<li><a href="https://github.com/kamilsk/tracer" rel="nofollow">tracer</a> - Simple, lightweight tracing.</li>
</ul>
<h2><a name="query-language" class="anchor" href="#query-language" rel="nofollow" aria-hidden="true"><span class="octicon octicon-link"></span></a>
Query Language</h2>

<ul>
<li><a href="https://github.com/thedevsaddam/gojsonq" rel="nofollow">gojsonq</a> - A simple Go package to Query over JSON Data.</li>
<li><a href="https://github.com/tmc/graphql" rel="nofollow">graphql</a> - graphql parser + utilities.</li>
<li><a href="https://github.com/neelance/graphql-go" rel="nofollow">graphql</a> - GraphQL server with a focus on ease of use.</li>
<li><a href="https://github.com/graphql-go/graphql" rel="nofollow">graphql-go</a> - Implementation of GraphQL for Go.</li>
<li><a href="https://github.com/elgs/jsonql" rel="nofollow">jsonql</a> - JSON query expression library in Golang.</li>
<li><a href="https://github.com/bhmj/jsonslice" rel="nofollow">jsonslice</a> - Jsonpath queries with advanced filters.</li>
<li><a href="https://github.com/a8m/rql" rel="nofollow">rql</a> - Resource Query Language for REST API.</li>
<li><a href="https://github.com/SonicRoshan/straf" rel="nofollow">straf</a> - Easily Convert Golang structs to GraphQL objects.</li>
</ul>
<h2><a name="resource-embedding" class="anchor" href="#resource-embedding" rel="nofollow" aria-hidden="true"><span class="octicon octicon-link"></span></a>
Resource Embedding</h2>

<ul>
<li><a href="https://github.com/mjibson/esc" rel="nofollow">esc</a> - Embeds files into Go programs and provides http.FileSystem interfaces to them.</li>
<li><a href="https://github.com/UnnoTed/fileb0x" rel="nofollow">fileb0x</a> - Simple tool to embed files in go with focus on &#34;customization&#34; and ease to use.</li>
<li><a href="https://github.com/pyros2097/go-embed" rel="nofollow">go-embed</a> - Generates go code to embed resource files into your library or executable.</li>
<li><a href="https://github.com/omeid/go-resources" rel="nofollow">go-resources</a> - Unfancy resources embedding with Go.</li>
<li><a href="https://github.com/GeertJohan/go.rice" rel="nofollow">go.rice</a> - go.rice is a Go package that makes working with resources such as html,js,css,images and templates very easy.</li>
<li><a href="https://github.com/gobuffalo/packr" rel="nofollow">packr</a> - The simple and easy way to embed static files into Go binaries.</li>
<li><a href="https://github.com/go-playground/statics" rel="nofollow">statics</a> - Embeds static resources into go files for single binary compilation + works with http.FileSystem + symlinks.</li>
<li><a href="https://github.com/rakyll/statik" rel="nofollow">statik</a> - Embeds static files into a Go executable.</li>
<li><a href="https://github.com/wlbr/templify" rel="nofollow">templify</a> - Embed external template files into Go code to create single file binaries.</li>
<li><a href="https://github.com/shurcooL/vfsgen" rel="nofollow">vfsgen</a> - Generates a vfsdata.go file that statically implements the given virtual filesystem.</li>
</ul>
<h2><a name="science-and-data-analysis" class="anchor" href="#science-and-data-analysis" rel="nofollow" aria-hidden="true"><span class="octicon octicon-link"></span></a>
Science and Data Analysis</h2>

<p><em>Libraries for scientific computing and data analyzing.</em></p>

<ul>
<li><a href="https://github.com/ndabAP/assocentity" rel="nofollow">assocentity</a> - Package assocentity returns the average distance from words to a given entity.</li>
<li><a href="https://github.com/seanhagen/bradleyterry" rel="nofollow">bradleyterry</a> - Provides a Bradley-Terry Model for pairwise comparisons.</li>
<li><a href="https://github.com/vdobler/chart" rel="nofollow">chart</a> - Simple Chart Plotting library for Go. Supports many graphs types.</li>
<li><a href="https://github.com/rocketlaunchr/dataframe-go" rel="nofollow">dataframe-go</a> - Dataframes for Go for machine-learning and statistics (similar to pandas).</li>
<li><a href="https://github.com/soniah/evaler" rel="nofollow">evaler</a> - Simple floating point arithmetic expression evaluator.</li>
<li><a href="https://github.com/VividCortex/ewma" rel="nofollow">ewma</a> - Exponentially-weighted moving averages.</li>
<li><a href="https://github.com/skelterjohn/geom" rel="nofollow">geom</a> - 2D geometry for golang.</li>
<li><a href="https://github.com/mjibson/go-dsp" rel="nofollow">go-dsp</a> - Digital Signal Processing for Go.</li>
<li><a href="https://github.com/ThePaw/go-gt" rel="nofollow">go-gt</a> - Graph theory algorithms written in &#34;Go&#34; language.</li>
<li><a href="https://github.com/kzahedi/goent" rel="nofollow">goent</a> - GO Implementation of Entropy Measures.</li>
<li><a href="https://github.com/VividCortex/gohistogram" rel="nofollow">gohistogram</a> - Approximate histograms for data streams.</li>
<li><a href="https://github.com/gonum/gonum" rel="nofollow">gonum</a> - Gonum is a set of numeric libraries for the Go programming language. It contains libraries for matrices, statistics, optimization, and more.</li>
<li><a href="https://github.com/gonum/plot" rel="nofollow">gonum/plot</a> - gonum/plot provides an API for building and drawing plots in Go.</li>
<li><a href="https://github.com/gyuho/goraph" rel="nofollow">goraph</a> - Pure Go graph theory library(data structure, algorith visualization).</li>
<li><a href="https://github.com/cpmech/gosl" rel="nofollow">gosl</a> - Go scientific library for linear algebra, FFT, geometry, NURBS, numerical methods, probabilities, optimisation, differential equations, and more.</li>
<li><a href="https://github.com/OGFris/GoStats" rel="nofollow">GoStats</a> - GoStats is an Open Source GoLang library for math statistics mostly used in Machine Learning domains, it covers most of the Statistical measures functions.</li>
<li><a href="https://github.com/yourbasic/graph" rel="nofollow">graph</a> - Library of basic graph algorithms.</li>
<li><a href="https://github.com/ChristopherRabotin/ode" rel="nofollow">ode</a> - Ordinary differential equation (ODE) solver which supports extended states and channel-based iteration stop conditions.</li>
<li><a href="https://github.com/paulmach/orb" rel="nofollow">orb</a> - 2D geometry types with clipping, GeoJSON and Mapbox Vector Tile support.</li>
<li><a href="https://github.com/alixaxel/pagerank" rel="nofollow">pagerank</a> - Weighted PageRank algorithm implemented in Go.</li>
<li><a href="https://github.com/sgreben/piecewiselinear" rel="nofollow">piecewiselinear</a> - Tiny linear interpolation library.</li>
<li><a href="https://github.com/claygod/PiHex" rel="nofollow">PiHex</a> - Implementation of the &#34;Bailey-Borwein-Plouffe&#34; algorithm for the hexadecimal number Pi.</li>
<li><a href="https://github.com/khezen/rootfinding" rel="nofollow">rootfinding</a> - root-finding algorithms library for finding roots of quadratic functions.</li>
<li><a href="https://github.com/james-bowman/sparse" rel="nofollow">sparse</a> - Go Sparse matrix formats for linear algebra supporting scientific and machine learning applications, compatible with gonum matrix libraries.</li>
<li><a href="https://github.com/montanaflynn/stats" rel="nofollow">stats</a> - Statistics package with common functions missing from the Golang standard library.</li>
<li><a href="https://github.com/nytlabs/streamtools" rel="nofollow">streamtools</a> - general purpose, graphical tool for dealing with streams of data.</li>
<li><a href="https://github.com/DavidBelicza/TextRank" rel="nofollow">TextRank</a> - TextRank implementation in Golang with extendable features (summarization, weighting, phrase extraction) and multithreading (goroutine) support.</li>
<li><a href="https://github.com/tchayen/triangolatte" rel="nofollow">triangolatte</a> - 2D triangulation library. Allows translating lines and polygons (both based on points) to the language of GPUs.</li>
</ul>
<h2><a name="security" class="anchor" href="#security" rel="nofollow" aria-hidden="true"><span class="octicon octicon-link"></span></a>
Security</h2>

<p><em>Libraries that are used to help make your application more secure.</em></p>

<ul>
<li><a href="https://github.com/hlandau/acme" rel="nofollow">acmetool</a> - ACME (Let&#39;s Encrypt) client tool with automatic renewal.</li>
<li><a href="https://github.com/cossacklabs/acra" rel="nofollow">acra</a> - Network encryption proxy to protect database-based applications from data leaks: strong selective encryption, SQL injections prevention, intrusion detection system.</li>
<li><a href="https://github.com/raja/argon2pw" rel="nofollow">argon2pw</a> - Argon2 password hash generation with constant-time password comparison.</li>
<li><a href="https://godoc.org/golang.org/x/crypto/acme/autocert" rel="nofollow">autocert</a> - Auto provision Let&#39;s Encrypt certificates and start a TLS server.</li>
<li><a href="https://github.com/jaredfolkins/badactor" rel="nofollow">BadActor</a> - In-memory, application-driven jailer built in the spirit of fail2ban.</li>
<li><a href="https://github.com/Ullaakut/cameradar" rel="nofollow">Cameradar</a> - Tool and library to remotely hack RTSP streams from surveillance cameras.</li>
<li><a href="https://github.com/mvmaasakkers/certificates" rel="nofollow">certificates</a> - An opinionated tool for generating tls certificates.</li>
<li><a href="https://github.com/hillu/go-yara" rel="nofollow">go-yara</a> - Go Bindings for <a href="https://github.com/plusvic/yara" rel="nofollow">YARA</a>, the &#34;pattern matching swiss knife for malware researchers (and everyone else)&#34;.</li>
<li><a href="https://github.com/dwin/goArgonPass" rel="nofollow">goArgonPass</a> - Argon2 password hash and verification designed to be compatible with existing Python and PHP implementations.</li>
<li><a href="https://github.com/dwin/goSecretBoxPassword" rel="nofollow">goSecretBoxPassword</a> - A probably paranoid package for securely hashing and encrypting passwords.</li>
<li><a href="https://bitbucket.org/vahidi/interpol" rel="nofollow">Interpol</a> - Rule-based data generator for fuzzing and penetration testing.</li>
<li><a href="https://github.com/khezen/jwc" rel="nofollow">jwc</a> - JSON Web Cryptography library.</li>
<li><a href="https://github.com/xenolf/lego" rel="nofollow">lego</a> - Pure Go ACME client library and CLI tool (for use with Let&#39;s Encrypt).</li>
<li><a href="https://github.com/awnumar/memguard" rel="nofollow">memguard</a> - A pure Go library for handling sensitive values in memory.</li>
<li><a href="https://github.com/kevinburke/nacl" rel="nofollow">nacl</a> - Go implementation of the NaCL set of API&#39;s.</li>
<li><a href="https://github.com/hlandau/passlib" rel="nofollow">passlib</a> - Futureproof password hashing library.</li>
<li><a href="https://github.com/unrolled/secure" rel="nofollow">secure</a> - HTTP middleware for Go that facilitates some quick security wins.</li>
<li><a href="https://github.com/elithrar/simple-scrypt" rel="nofollow">simple-scrypt</a> - Scrypt package with a simple, obvious API and automatic cost calibration built-in.</li>
<li><a href="https://github.com/ssh-vault/ssh-vault" rel="nofollow">ssh-vault</a> - encrypt/decrypt using ssh keys.</li>
<li><a href="https://github.com/adrianosela/sslmgr" rel="nofollow">sslmgr</a> - SSL certificates made easy with a high level wrapper around acme/autocert.</li>
</ul>
<h2><a name="serialization" class="anchor" href="#serialization" rel="nofollow" aria-hidden="true"><span class="octicon octicon-link"></span></a>
Serialization</h2>

<p><em>Libraries and tools for binary serialization.</em></p>

<ul>
<li><a href="https://github.com/PromonLogicalis/asn1" rel="nofollow">asn1</a> - Asn.1 BER and DER encoding library for golang.</li>
<li><a href="https://github.com/glycerine/bambam" rel="nofollow">bambam</a> - generator for Cap&#39;n Proto schemas from go.</li>
<li><a href="https://github.com/32leaves/bel" rel="nofollow">bel</a> - Generate TypeScript interfaces from Go structs/interfaces. Useful for JSON RPC.</li>
<li><a href="https://github.com/ghostiam/binstruct" rel="nofollow">binstruct</a> - Golang binary decoder for mapping data into the structure.</li>
<li><a href="https://github.com/fxamacker/cbor" rel="nofollow">cbor</a> - Small, safe, and easy CBOR encoding and decoding library.</li>
<li><a href="https://github.com/pascaldekloe/colfer" rel="nofollow">colfer</a> - Code generation for the Colfer binary format.</li>
<li><a href="https://github.com/jszwec/csvutil" rel="nofollow">csvutil</a> - High Performance, idiomatic CSV record encoding and decoding to native Go structures.</li>
<li><a href="https://github.com/o1egl/fwencoder" rel="nofollow">fwencoder</a> - Fixed width file parser (encoding and decoding library) for Go.</li>
<li><a href="https://github.com/glycerine/go-capnproto" rel="nofollow">go-capnproto</a> - Cap&#39;n Proto library and parser for go.</li>
<li><a href="https://github.com/ugorji/go" rel="nofollow">go-codec</a> - High Performance, feature-Rich, idiomatic encode, decode and rpc library for msgpack, cbor and json, with runtime-based OR code-generation support.</li>
<li><a href="https://github.com/gogo/protobuf" rel="nofollow">gogoprotobuf</a> - Protocol Buffers for Go with Gadgets.</li>
<li><a href="https://github.com/golang/protobuf" rel="nofollow">goprotobuf</a> - Go support, in the form of a library and protocol compiler plugin, for Google&#39;s protocol buffers.</li>
<li><a href="https://github.com/json-iterator/go" rel="nofollow">jsoniter</a> - High-performance 100% compatible drop-in replacement of &#34;encoding/json&#34;.</li>
<li><a href="https://github.com/mitchellh/mapstructure" rel="nofollow">mapstructure</a> - Go library for decoding generic map values into native Go structures.</li>
<li><a href="https://github.com/yvasiyarov/php_session_decoder" rel="nofollow">php_session_decoder</a> - GoLang library for working with PHP session format and PHP Serialize/Unserialize functions.</li>
<li><a href="https://github.com/vimeda/pletter" rel="nofollow">pletter</a> - A standard way to wrap a proto message for message brokers.</li>
<li><a href="https://github.com/tuvistavie/structomap" rel="nofollow">structomap</a> - Library to easily and dynamically generate maps from static structures.</li>
</ul>
<h2><a name="server-applications" class="anchor" href="#server-applications" rel="nofollow" aria-hidden="true"><span class="octicon octicon-link"></span></a>
Server Applications</h2>

<ul>
<li><a href="https://github.com/xyproto/algernon" rel="nofollow">algernon</a> - HTTP/2 web server with built-in support for Lua, Markdown, GCSS and Amber.</li>
<li><a href="https://github.com/mholt/caddy" rel="nofollow">Caddy</a> - Caddy is an alternative, HTTP/2 web server that&#39;s easy to configure and use.</li>
<li><a href="https://www.consul.io/" rel="nofollow">consul</a> - Consul is a tool for service discovery, monitoring and configuration.</li>
<li><a href="https://github.com/cortesi/devd" rel="nofollow">devd</a> - Local webserver for developers.</li>
<li><a href="https://github.com/Bilibili/discovery" rel="nofollow">discovery</a> - A registry for resilient mid-tier load balancing and failover.</li>
<li><a href="https://github.com/krotik/dudeldu" rel="nofollow">dudeldu</a> - A simple SHOUTcast server.</li>
<li><a href="https://github.com/coreos/etcd" rel="nofollow">etcd</a> - Highly-available key value store for shared configuration and service discovery.</li>
<li><a href="https://github.com/getfider/fider" rel="nofollow">Fider</a> - Fider is an open platform to collect and organize customer feedback.</li>
<li><a href="https://github.com/checkr/flagr" rel="nofollow">Flagr</a> - Flagr is an open-source feature flagging and A/B testing service.</li>
<li><a href="https://github.com/markphelps/flipt" rel="nofollow">flipt</a> - A self contained feature flag solution written in Go and Vue.js</li>
<li><a href="https://github.com/ortuman/jackal" rel="nofollow">jackal</a> - An XMPP server written in Go.</li>
<li><a href="https://github.com/minio/minio" rel="nofollow">minio</a> - Minio is a distributed object storage server.</li>
<li><a href="https://github.com/blind-oracle/nginx-prometheus" rel="nofollow">nginx-prometheus</a> - Nginx log parser and exporter to Prometheus.</li>
<li><a href="http://nsq.io/" rel="nofollow">nsq</a> - A realtime distributed messaging platform.</li>
<li><a href="https://github.com/blind-oracle/psql-streamer" rel="nofollow">psql-streamer</a> - Stream database events from PostgreSQL to Kafka.</li>
<li><a href="https://github.com/blind-oracle/riemann-relay" rel="nofollow">riemann-relay</a> - Relay to load-balance Riemann events and/or convert them to Carbon.</li>
<li><a href="https://github.com/spiral/roadrunner" rel="nofollow">RoadRunner</a> - High-performance PHP application server, load-balancer and process manager.</li>
<li><a href="https://github.com/drakkan/sftpgo" rel="nofollow">SFTPGo</a> - Full featured and highly configurable SFTP server software.</li>
<li><a href="https://git.sci4me.com/sci4me/yakvs" rel="nofollow">yakvs</a> - Small, networked, in-memory key-value store.</li>
</ul>
<h2><a name="stream-processing" class="anchor" href="#stream-processing" rel="nofollow" aria-hidden="true"><span class="octicon octicon-link"></span></a>
Stream Processing</h2>

<p><em>Libraries and tools for stream processing and reactive programming.</em></p>

<ul>
<li><a href="https://github.com/reugn/go-streams" rel="nofollow">go-streams</a> - Go stream processing library.</li>
</ul>
<h2><a name="template-engines" class="anchor" href="#template-engines" rel="nofollow" aria-hidden="true"><span class="octicon octicon-link"></span></a>
Template Engines</h2>

<p><em>Libraries and tools for templating and lexing.</em></p>

<ul>
<li><a href="https://github.com/yosssi/ace" rel="nofollow">ace</a> - Ace is an HTML template engine for Go, inspired by Slim and Jade. Ace is a refinement of Gold.</li>
<li><a href="https://github.com/eknkc/amber" rel="nofollow">amber</a> - Amber is an elegant templating engine for Go Programming Language It is inspired from HAML and Jade.</li>
<li><a href="https://github.com/dskinner/damsel" rel="nofollow">damsel</a> - Markup language featuring html outlining via css-selectors, extensible via pkg html/template and others.</li>
<li><a href="https://github.com/benbjohnson/ego" rel="nofollow">ego</a> - Lightweight templating language that lets you write templates in Go. Templates are translated into Go and compiled.</li>
<li><a href="https://github.com/dannyvankooten/extemplate" rel="nofollow">extemplate</a> - Tiny wrapper around html/template to allow for easy file-based template inheritance.</li>
<li><a href="https://github.com/valyala/fasttemplate" rel="nofollow">fasttemplate</a> - Simple and fast template engine. Substitutes template placeholders up to 10x faster than <a href="http://golang.org/pkg/text/template/" rel="nofollow">text/template</a>.</li>
<li><a href="https://github.com/jung-kurt/gofpdf" rel="nofollow">gofpdf</a> - PDF document generator with high level support for text, drawing and images.</li>
<li><a href="https://github.com/foolin/goview" rel="nofollow">goview</a> - Goview is a lightweight, minimalist and idiomatic template library based on golang html/template for building Go web application.</li>
<li><a href="https://github.com/shiyanhui/hero" rel="nofollow">hero</a> - Hero is a handy, fast and powerful go template engine.</li>
<li><a href="https://github.com/CloudyKit/jet" rel="nofollow">jet</a> - Jet template engine.</li>
<li><a href="https://github.com/ziutek/kasia.go" rel="nofollow">kasia.go</a> - Templating system for HTML and other text documents - go implementation.</li>
<li><a href="https://github.com/osteele/liquid" rel="nofollow">liquid</a> - Go implementation of Shopify Liquid templates.</li>
<li><a href="https://github.com/johnfercher/maroto" rel="nofollow">maroto</a> - A maroto way to create PDFs. Maroto is inspired in Bootstrap and uses gofpdf. Fast and simple.</li>
<li><a href="https://github.com/hoisie/mustache" rel="nofollow">mustache</a> - Go implementation of the Mustache template language.</li>
<li><a href="https://github.com/flosch/pongo2" rel="nofollow">pongo2</a> - Django-like template-engine for Go.</li>
<li><a href="https://github.com/valyala/quicktemplate" rel="nofollow">quicktemplate</a> - Fast, powerful, yet easy to use template engine. Converts templates into Go code and then compiles it.</li>
<li><a href="https://github.com/aymerick/raymond" rel="nofollow">raymond</a> - Complete handlebars implementation in Go.</li>
<li><a href="https://github.com/sipin/gorazor" rel="nofollow">Razor</a> - Razor view engine for Golang.</li>
<li><a href="https://github.com/robfig/soy" rel="nofollow">Soy</a> - Closure templates (aka Soy templates) for Go, following the <a href="https://developers.google.com/closure/templates/" rel="nofollow">official spec</a>.</li>
<li><a href="https://github.com/gobuffalo/velvet" rel="nofollow">velvet</a> - Complete handlebars implementation in Go.</li>
</ul>
<h2><a name="testing" class="anchor" href="#testing" rel="nofollow" aria-hidden="true"><span class="octicon octicon-link"></span></a>
Testing</h2>

<p><em>Libraries for testing codebases and generating test data.</em></p>

<ul>
<li><p>Testing Frameworks</p>

<ul>
<li><a href="https://apitest.dev" rel="nofollow">apitest</a> - Simple and extensible behavioural testing library for REST based services or HTTP handlers that supports mocking external http calls and rendering of sequence diagrams.</li>
<li><a href="https://github.com/go-playground/assert" rel="nofollow">assert</a> - Basic Assertion Library used along side native go testing, with building blocks for custom assertions.</li>
<li><a href="https://github.com/cavaliercoder/badio" rel="nofollow">badio</a> - Extensions to Go&#39;s <code>testing/iotest</code> package.</li>
<li><a href="https://github.com/h2non/baloo" rel="nofollow">baloo</a> - Expressive and versatile end-to-end HTTP API testing made easy.</li>
<li><a href="https://github.com/fulldump/biff" rel="nofollow">biff</a> - Bifurcation testing framework, BDD compatible.</li>
<li><a href="https://github.com/percolate/charlatan" rel="nofollow">charlatan</a> - Tool to generate fake interface implementations for tests.</li>
<li><a href="https://github.com/SimonBaeumer/commander" rel="nofollow">commander</a> - Tool for testing cli applications on windows, linux and osx.</li>
<li><a href="https://github.com/bradleyjkemp/cupaloy" rel="nofollow">cupaloy</a> - Simple snapshot testing addon for your test framework.</li>
<li><a href="https://github.com/khaiql/dbcleaner" rel="nofollow">dbcleaner</a> - Clean database for testing purpose, inspired by <code>database_cleaner</code> in Ruby.</li>
<li><a href="https://github.com/viant/dsunit" rel="nofollow">dsunit</a> - Datastore testing for SQL, NoSQL, structured files.</li>
<li><a href="https://github.com/viant/endly" rel="nofollow">endly</a> - Declarative end to end functional testing.</li>
<li><a href="https://github.com/suzuki-shunsuke/flute" rel="nofollow">flute</a> - HTTP client testing framework.</li>
<li><a href="https://github.com/verdverm/frisby" rel="nofollow">frisby</a> - REST API testing framework.</li>
<li><a href="http://onsi.github.io/ginkgo/" rel="nofollow">ginkgo</a> - BDD Testing Framework for Go.</li>
<li><a href="https://github.com/msoap/go-carpet" rel="nofollow">go-carpet</a> - Tool for viewing test coverage in terminal.</li>
<li><a href="https://github.com/google/go-cmp" rel="nofollow">go-cmp</a> - Package for comparing Go values in tests.</li>
<li><a href="https://github.com/zimmski/go-mutesting" rel="nofollow">go-mutesting</a> - Mutation testing for Go source code.</li>
<li><a href="https://github.com/maxatome/go-testdeep" rel="nofollow">go-testdeep</a> - Extremely flexible golang deep comparison, extends the go testing package.</li>
<li><a href="https://github.com/dnaeon/go-vcr" rel="nofollow">go-vcr</a> - Record and replay your HTTP interactions for fast, deterministic and accurate tests.</li>
<li><a href="https://github.com/franela/goblin" rel="nofollow">goblin</a> - Mocha like testing framework fo Go.</li>
<li><a href="http://labix.org/gocheck" rel="nofollow">gocheck</a> - More advanced testing framework alternative to gotest.</li>
<li><a href="https://github.com/smartystreets/goconvey/" rel="nofollow">GoConvey</a> - BDD-style framework with web UI and live reload.</li>
<li><a href="https://github.com/corbym/gocrest" rel="nofollow">gocrest</a> - Composable hamcrest-like matchers for Go assertions.</li>
<li><a href="https://github.com/DATA-DOG/godog" rel="nofollow">godog</a> - Cucumber or Behat like BDD framework for Go.</li>
<li><a href="https://github.com/appleboy/gofight" rel="nofollow">gofight</a> - API Handler Testing for Golang Router framework.</li>
<li><a href="https://github.com/corbym/gogiven" rel="nofollow">gogiven</a> - YATSPEC-like BDD testing framework for Go.</li>
<li><a href="https://github.com/jfilipczyk/gomatch" rel="nofollow">gomatch</a> - library created for testing JSON against patterns.</li>
<li><a href="http://onsi.github.io/gomega/" rel="nofollow">gomega</a> - Rspec like matcher/assertion library.</li>
<li><a href="https://github.com/orfjackal/gospec" rel="nofollow">GoSpec</a> - BDD-style testing framework for the Go programming language.</li>
<li><a href="https://github.com/stesla/gospecify" rel="nofollow">gospecify</a> - This provides a BDD syntax for testing your Go code. It should be familiar to anybody who has used libraries such as rspec.</li>
<li><a href="https://github.com/pavlo/gosuite" rel="nofollow">gosuite</a> - Brings lightweight test suites with setup/teardown facilities to <code>testing</code> by leveraging Go1.7&#39;s Subtests.</li>
<li><a href="https://github.com/gotestyourself/gotest.tools" rel="nofollow">gotest.tools</a> - A collection of packages to augment the go testing package and support common patterns.</li>
<li><a href="https://github.com/rdrdr/hamcrest" rel="nofollow">Hamcrest</a> - fluent framework for declarative Matcher objects that, when applied to input values, produce self-describing results.</li>
<li><a href="https://github.com/gavv/httpexpect" rel="nofollow">httpexpect</a> - Concise, declarative, and easy to use end-to-end HTTP and REST API testing.</li>
<li><a href="https://github.com/kinbiko/jsonassert" rel="nofollow">jsonassert</a> - Package for verifying that your JSON payloads are serialized correctly.</li>
<li><a href="https://github.com/yookoala/restit" rel="nofollow">restit</a> - Go micro framework to help writing RESTful API integration test.</li>
<li><a href="https://github.com/jgroeneveld/schema" rel="nofollow">schema</a> - Quick and easy expression matching for JSON schemas used in requests and responses.</li>
<li><a href="https://github.com/adamluzsi/testcase" rel="nofollow">testcase</a> - Idiomatic testing framework for Behavior Driven Development.</li>
<li><a href="https://github.com/go-testfixtures/testfixtures" rel="nofollow">testfixtures</a> - A helper for Rails&#39; like test fixtures to test database applications.</li>
<li><a href="https://github.com/stretchr/testify" rel="nofollow">Testify</a> - Sacred extension to the standard go testing package.</li>
<li><a href="https://godoc.org/github.com/tvastar/test/cmd/testmd" rel="nofollow">testmd</a> - Convert markdown snippets into testable go code.</li>
<li><a href="https://github.com/zhulongcheng/testsql" rel="nofollow">testsql</a> - Generate test data from SQL files before testing and clear it after finished.</li>
<li><a href="https://github.com/jgroeneveld/trial" rel="nofollow">trial</a> - Quick and easy extendable assertions without introducing much boilerplate.</li>
<li><a href="https://github.com/vcaesar/tt" rel="nofollow">Tt</a> - Simple and colorful test tools.</li>
<li><a href="https://github.com/posener/wstest" rel="nofollow">wstest</a> - Websocket client for unit-testing a websocket http.Handler.</li>
</ul></li>

<li><p>Mock</p>

<ul>
<li><a href="https://github.com/maxbrunsfeld/counterfeiter" rel="nofollow">counterfeiter</a> - Tool for generating self-contained mock objects.</li>
<li><a href="https://github.com/DATA-DOG/go-sqlmock" rel="nofollow">go-sqlmock</a> - Mock SQL driver for testing database interactions.</li>
<li><a href="https://github.com/DATA-DOG/go-txdb" rel="nofollow">go-txdb</a> - Single transaction based database driver mainly for testing purposes.</li>
<li><a href="https://github.com/h2non/gock" rel="nofollow">gock</a> - Versatile HTTP mocking made easy.</li>
<li><a href="https://github.com/golang/mock" rel="nofollow">gomock</a> - Mocking framework for the Go programming language.</li>
<li><a href="https://github.com/seborama/govcr" rel="nofollow">govcr</a> - HTTP mock for Golang: record and replay HTTP interactions for offline testing.</li>
<li><a href="https://github.com/SpectoLabs/hoverfly" rel="nofollow">hoverfly</a> - HTTP(S) proxy for recording and simulating REST/SOAP APIs with extensible middleware and easy-to-use CLI.</li>
<li><a href="https://github.com/jarcoal/httpmock" rel="nofollow">httpmock</a> - Easy mocking of HTTP responses from external resources.</li>
<li><a href="https://github.com/gojuno/minimock" rel="nofollow">minimock</a> - Mock generator for Go interfaces.</li>
<li><a href="https://github.com/tv42/mockhttp" rel="nofollow">mockhttp</a> - Mock object for Go http.ResponseWriter.</li>
</ul></li>

<li><p>Fuzzing and delta-debugging/reducing/shrinking.</p>

<ul>
<li><a href="https://github.com/dvyukov/go-fuzz" rel="nofollow">go-fuzz</a> - Randomized testing system.</li>
<li><a href="https://github.com/google/gofuzz" rel="nofollow">gofuzz</a> - Library for populating go objects with random values.</li>
<li><a href="https://github.com/zimmski/tavor" rel="nofollow">Tavor</a> - Generic fuzzing and delta-debugging framework.</li>
</ul></li>

<li><p>Selenium and browser control tools.</p>

<ul>
<li><a href="https://github.com/mafredri/cdp" rel="nofollow">cdp</a> - Type-safe bindings for the Chrome Debugging Protocol that can be used with browsers or other debug targets that implement it.</li>
<li><a href="https://github.com/knq/chromedp" rel="nofollow">chromedp</a> - a way to drive/test Chrome, Safari, Edge, Android Webviews, and other browsers supporting the Chrome Debugging Protocol.</li>
<li><a href="https://github.com/aerokube/ggr" rel="nofollow">ggr</a> - a lightweight server that routes and proxies Selenium WebDriver requests to multiple Selenium hubs.</li>
<li><a href="https://github.com/aerokube/selenoid" rel="nofollow">selenoid</a> - alternative Selenium hub server that launches browsers within containers.</li>
</ul></li>

<li><p>Fail injection</p>

<ul>
<li><a href="https://github.com/pingcap/failpoint" rel="nofollow">failpoint</a> - An implementation of <a href="http://www.freebsd.org/cgi/man.cgi?query=fail" rel="nofollow">failpoints</a> for Golang.</li>
</ul></li>
</ul>
<h2><a name="text-processing" class="anchor" href="#text-processing" rel="nofollow" aria-hidden="true"><span class="octicon octicon-link"></span></a>
Text Processing</h2>

<p><em>Libraries for parsing and manipulating texts.</em></p>

<ul>
<li>Specific Formats

<ul>
<li><a href="https://github.com/Guitarbum722/align" rel="nofollow">align</a> - A general purpose application that aligns text.</li>
<li><a href="https://github.com/sbstjn/allot" rel="nofollow">allot</a> - Placeholder and wildcard text parsing for CLI tools and bots.</li>
<li><a href="https://github.com/CalebQ42/bbConvert" rel="nofollow">bbConvert</a> - Converts bbCode to HTML that allows you to add support for custom bbCode tags.</li>
<li><a href="https://github.com/russross/blackfriday" rel="nofollow">blackfriday</a> - Markdown processor in Go.</li>
<li><a href="https://github.com/microcosm-cc/bluemonday" rel="nofollow">bluemonday</a> - HTML Sanitizer.</li>
<li><a href="https://github.com/aerogo/codetree" rel="nofollow">codetree</a> - Parses indented code (python, pixy, scarlet, etc.) and returns a tree structure.</li>
<li><a href="https://github.com/asciimoo/colly" rel="nofollow">colly</a> - Fast and Elegant Scraping Framework for Gophers.</li>
<li><a href="https://github.com/mingrammer/commonregex" rel="nofollow">commonregex</a> - A collection of common regular expressions for Go.</li>
<li><a href="https://github.com/slotix/dataflowkit" rel="nofollow">dataflowkit</a> - Web scraping Framework to turn websites into structured data.</li>
<li><a href="https://github.com/ockam-network/did" rel="nofollow">did</a> - DID (Decentralized Identifiers) Parser and Stringer in Go.</li>
<li><a href="https://github.com/hscells/doi" rel="nofollow">doi</a> - Document object identifier (doi) parser in Go.</li>
<li><a href="https://github.com/editorconfig/editorconfig-core-go" rel="nofollow">editorconfig-core-go</a> - Editorconfig file parser and manipulator for Go.</li>
<li><a href="https://github.com/endeveit/enca" rel="nofollow">enca</a> - Minimal cgo bindings for <a href="http://cihar.com/software/enca/" rel="nofollow">libenca</a>.</li>
<li><a href="https://github.com/mickep76/encdec" rel="nofollow">encdec</a> - Package provides a generic interface to encoders and decodersa.</li>
<li><a href="https://github.com/alixaxel/genex" rel="nofollow">genex</a> - Count and expand Regular Expressions into all matching Strings.</li>
<li><a href="https://godoc.org/github.com/shurcooL/github_flavored_markdown" rel="nofollow">github_flavored_markdown</a> - GitHub Flavored Markdown renderer (using blackfriday) with fenced code block highlighting, clickable header anchor links.</li>
<li><a href="https://github.com/ianlopshire/go-fixedwidth" rel="nofollow">go-fixedwidth</a> - Fixed-width text formatting (encoder/decoder with reflection).</li>
<li><a href="https://github.com/dustin/go-humanize" rel="nofollow">go-humanize</a> - Formatters for time, numbers, and memory size to human readable format.</li>
<li><a href="https://github.com/adrianmo/go-nmea" rel="nofollow">go-nmea</a> - NMEA parser library for the Go language.</li>
<li><a href="https://github.com/mattn/go-runewidth" rel="nofollow">go-runewidth</a> - Functions to get fixed width of the character or string.</li>
<li><a href="https://github.com/mozillazg/go-slugify" rel="nofollow">go-slugify</a> - Make pretty slug with multiple languages support.</li>
<li><a href="https://github.com/pelletier/go-toml" rel="nofollow">go-toml</a> - Go library for the TOML format with query support and handy cli tools.</li>
<li><a href="https://github.com/emersion/go-vcard" rel="nofollow">go-vcard</a> - Parse and format vCard.</li>
<li><a href="https://github.com/trubitsyn/go-zero-width" rel="nofollow">go-zero-width</a> - Zero-width character detection and removal for Go.</li>
<li><a href="https://github.com/mmcdole/gofeed" rel="nofollow">gofeed</a> - Parse RSS and Atom feeds in Go.</li>
<li><a href="https://github.com/awalterschulze/gographviz" rel="nofollow">gographviz</a> - Parses the Graphviz DOT language.</li>
<li><a href="https://github.com/labstack/gommon/tree/master/bytes" rel="nofollow">gommon/bytes</a> - Format bytes to string.</li>
<li><a href="https://github.com/polera/gonameparts" rel="nofollow">gonameparts</a> - Parses human names into individual name parts.</li>
<li><a href="https://github.com/andrewstuart/goq" rel="nofollow">goq</a> - Declarative unmarshaling of HTML using struct tags with jQuery syntax (uses GoQuery).</li>
<li><a href="https://github.com/PuerkitoBio/goquery" rel="nofollow">GoQuery</a> - GoQuery brings a syntax and a set of features similar to jQuery to the Go language.</li>
<li><a href="https://github.com/zach-klippenstein/goregen" rel="nofollow">goregen</a> - Library for generating random strings from regular expressions.</li>
<li><a href="https://github.com/zhshch2002/goribot" rel="nofollow">goribot</a> - A simple golang spider/scraping framework,build a spider in 3 lines.</li>
<li><a href="https://github.com/leonelquinteros/gotext" rel="nofollow">gotext</a> - GNU gettext utilities for Go.</li>
<li><a href="https://github.com/endeveit/guesslanguage" rel="nofollow">guesslanguage</a> - Functions to determine the natural language of a unicode text.</li>
<li><a href="https://github.com/antchfx/htmlquery" rel="nofollow">htmlquery</a> - An XPath query package for HTML, lets you extract data or evaluate from HTML documents by an XPath expression.</li>
<li><a href="https://github.com/facebookgo/inject" rel="nofollow">inject</a> - Package inject provides a reflect based injector.</li>
<li><a href="https://github.com/Wing924/ltsv" rel="nofollow">ltsv</a> - High performance <a href="http://ltsv.org/" rel="nofollow">LTSV (Labeled Tab Separeted Value)</a> reader for Go.</li>
<li><a href="https://github.com/clbanning/mxj" rel="nofollow">mxj</a> - Encode / decode XML as JSON or map[string]interface{}; extract values with dot-notation paths and wildcards. Replaces x2j and j2x packages.</li>
<li><a href="https://github.com/gortc/sdp" rel="nofollow">sdp</a> - SDP: Session Description Protocol [<a href="https://tools.ietf.org/html/rfc4566" rel="nofollow">RFC 4566</a>].</li>
<li><a href="https://github.com/mvdan/sh" rel="nofollow">sh</a> - Shell parser and formatter.</li>
<li><a href="https://github.com/gosimple/slug" rel="nofollow">slug</a> - URL-friendly slugify with multiple languages support.</li>
<li><a href="https://github.com/avelino/slugify" rel="nofollow">Slugify</a> - Go slugify application that handles string.</li>
<li><a href="https://github.com/zhengchun/syndfeed" rel="nofollow">syndfeed</a> - A syndication feed for Atom 1.0 and RSS 2.0.</li>
<li><a href="https://github.com/BurntSushi/toml" rel="nofollow">toml</a> - TOML configuration format (encoder/decoder with reflection).</li>
</ul></li>
<li>Utility

<ul>
<li><a href="https://github.com/JoshuaDoes/gofuckyourself" rel="nofollow">gofuckyourself</a> - A sanitization-based swear filter for Go.</li>
<li><a href="https://github.com/bndr/gotabulate" rel="nofollow">gotabulate</a> - Easily pretty-print your tabular data with Go.</li>
<li><a href="https://github.com/codemodus/kace" rel="nofollow">kace</a> - Common case conversions covering common initialisms.</li>
<li><a href="https://github.com/nproc/parseargs-go" rel="nofollow">parseargs-go</a> - string argument parser that understands quotes and backslashes.</li>
<li><a href="https://github.com/codemodus/parth" rel="nofollow">parth</a> - URL path segmentation parsing.</li>
<li><a href="https://github.com/yourbasic/radix" rel="nofollow">radix</a> - fast string sorting algorithm.</li>
<li><a href="https://github.com/zoomio/tagify" rel="nofollow">Tagify</a> - Produces a set of tags from given source.</li>
<li><a href="https://github.com/isbm/textwrap" rel="nofollow">textwrap</a> - Implementation of <code>textwrap</code> module from Python.</li>
<li><a href="https://github.com/Dynom/TySug" rel="nofollow">TySug</a> - Alternative suggestions with respect to keyboard layouts.</li>
<li><a href="https://github.com/stackerzzq/xj2go" rel="nofollow">xj2go</a> - Convert xml or json to go struct.</li>
<li><a href="https://github.com/mvdan/xurls" rel="nofollow">xurls</a> - Extract urls from text.</li>
</ul></li>
</ul>
<h2><a name="third-party-apis" class="anchor" href="#third-party-apis" rel="nofollow" aria-hidden="true"><span class="octicon octicon-link"></span></a>
Third-party APIs</h2>

<p><em>Libraries for accessing third party APIs.</em></p>

<ul>
<li><a href="https://github.com/ngs/go-amazon-product-advertising-api" rel="nofollow">amazon-product-advertising-api</a> - Go Client Library for <a href="https://affiliate-program.amazon.com/gp/advertising/api/detail/main.html" rel="nofollow">Amazon Product Advertising API</a>.</li>
<li><a href="https://github.com/ChimeraCoder/anaconda" rel="nofollow">anaconda</a> - Go client library for the Twitter 1.1 API.</li>
<li><a href="https://github.com/aws/aws-sdk-go" rel="nofollow">aws-sdk-go</a> - The official AWS SDK for the Go programming language.</li>
<li><a href="https://github.com/naegelejd/brewerydb" rel="nofollow">brewerydb</a> - Go library for accessing the BreweryDB API.</li>
<li><a href="https://github.com/andygrunwald/cachet" rel="nofollow">cachet</a> - Go client library for <a href="https://cachethq.io/" rel="nofollow">Cachet (open source status page system)</a>.</li>
<li><a href="https://github.com/jszwedko/go-circleci" rel="nofollow">circleci</a> - Go client library for interacting with CircleCI&#39;s API.</li>
<li><a href="https://github.com/samuelcouch/clarifai" rel="nofollow">clarifai</a> - Go client library for interfacing with the Clarifai API.</li>
<li><a href="https://github.com/codeship/codeship-go" rel="nofollow">codeship-go</a> - Go client library for interacting with Codeship&#39;s API v2.</li>
<li><a href="https://github.com/coinpaprika/coinpaprika-api-go-client" rel="nofollow">coinpaprika-go</a> - Go client library for interacting with Coinpaprika&#39;s API.</li>
<li><a href="https://github.com/bwmarrin/discordgo" rel="nofollow">discordgo</a> - Go bindings for the Discord Chat API.</li>
<li><a href="https://github.com/onrik/ethrpc" rel="nofollow">ethrpc</a> - Go bindings for Ethereum JSON RPC API.</li>
<li><a href="https://github.com/huandu/facebook" rel="nofollow">facebook</a> - Go Library that supports the Facebook Graph API.</li>
<li><a href="https://github.com/maddevsio/fcm" rel="nofollow">fcm</a> - Go library for Firebase Cloud Messaging.</li>
<li><a href="https://github.com/emiddleton/gads" rel="nofollow">gads</a> - Google Adwords Unofficial API.</li>
<li><a href="https://github.com/bit4bit/gami" rel="nofollow">gami</a> - Go library for Asterisk Manager Interface.</li>
<li><a href="https://github.com/Aorioli/gcm" rel="nofollow">gcm</a> - Go library for Google Cloud Messaging.</li>
<li><a href="https://github.com/codingsince1985/geo-golang" rel="nofollow">geo-golang</a> - Go Library to access <a href="https://developers.google.com/maps/documentation/geocoding/intro" rel="nofollow">Google Maps</a>, <a href="http://open.mapquestapi.com/geocoding/" rel="nofollow">MapQuest</a>, <a href="https://developer.mapquest.com/documentation/open/nominatim-search" rel="nofollow">Nominatim</a>, <a href="http://geocoder.opencagedata.com/api.html" rel="nofollow">OpenCage</a>, <a href="https://msdn.microsoft.com/en-us/library/ff701715.aspx" rel="nofollow">Bing</a>, <a href="https://www.mapbox.com/developers/api/geocoding/" rel="nofollow">Mapbox</a>, and <a href="https://wiki.openstreetmap.org/wiki/Nominatim" rel="nofollow">OpenStreetMap</a> geocoding / reverse geocoding APIs.</li>
<li><a href="https://github.com/google/go-github" rel="nofollow">github</a> - Go library for accessing the GitHub REST API v3.</li>
<li><a href="https://github.com/shurcooL/githubql" rel="nofollow">githubql</a> - Go library for accessing the GitHub GraphQL API v4.</li>
<li><a href="https://github.com/axelspringer/go-chronos" rel="nofollow">go-chronos</a> - Go library for interacting with the <a href="https://mesos.github.io/chronos/" rel="nofollow">Chronos</a> Job Scheduler</li>
<li><a href="https://github.com/PaulRosset/go-hacknews" rel="nofollow">go-hacknews</a> - Tiny Go client for HackerNews API.</li>
<li><a href="https://github.com/abdullahselek/go-here" rel="nofollow">go-here</a> - Go client library around the HERE location based APIs.</li>
<li><a href="https://github.com/koffeinsource/go-imgur" rel="nofollow">go-imgur</a> - Go client library for <a href="https://imgur.com" rel="nofollow">imgur</a></li>
<li><a href="https://github.com/andygrunwald/go-jira" rel="nofollow">go-jira</a> - Go client library for <a href="https://www.atlassian.com/software/jira" rel="nofollow">Atlassian JIRA</a></li>
<li><a href="https://github.com/gambol99/go-marathon" rel="nofollow">go-marathon</a> - Go library for interacting with Mesosphere&#39;s Marathon PAAS.</li>
<li><a href="https://github.com/nstratos/go-myanimelist" rel="nofollow">go-myanimelist</a> - Go client library for accessing the <a href="http://myanimelist.net/modules.php?go=api" rel="nofollow">MyAnimeList API</a>.</li>
<li><a href="https://github.com/esurdam/go-sophos" rel="nofollow">go-sophos</a> - Go client library for the <a href="https://www.sophos.com/en-us/medialibrary/PDFs/documentation/UTMonAWS/Sophos-UTM-RESTful-API.pdf?la=en" rel="nofollow">Sophos UTM REST API</a> with zero dependencies.</li>
<li><a href="https://github.com/sergioaugrod/go-sptrans" rel="nofollow">go-sptrans</a> - Go client library for the SPTrans Olho Vivo API.</li>
<li><a href="https://gitlab.com/toby3d/telegraph" rel="nofollow">go-telegraph</a> - Telegraph publishing platform API client.</li>
<li><a href="https://github.com/andygrunwald/go-trending" rel="nofollow">go-trending</a> - Go library for accessing <a href="https://github.com/trending" rel="nofollow">trending repositories</a> and <a href="https://github.com/trending/developers" rel="nofollow">developers</a> at Github.</li>
<li><a href="https://github.com/knspriggs/go-twitch" rel="nofollow">go-twitch</a> - Go client for interacting with the Twitch v3 API.</li>
<li><a href="https://github.com/dghubble/go-twitter" rel="nofollow">go-twitter</a> - Go client library for the Twitter v1.1 APIs.</li>
<li><a href="https://github.com/hbagdi/go-unsplash" rel="nofollow">go-unsplash</a> - Go client library for the <a href="https://unsplash.com" rel="nofollow">Unsplash.com</a> API.</li>
<li><a href="https://github.com/nishanths/go-xkcd" rel="nofollow">go-xkcd</a> - Go client for the xkcd API.</li>
<li><a href="https://github.com/mamal72/golyrics" rel="nofollow">golyrics</a> - Golyrics is a Go library to fetch music lyrics data from the Wikia website.</li>
<li><a href="https://github.com/MonaxGT/gomalshare" rel="nofollow">gomalshare</a> - Go library MalShare API <a href="http://www.malshare.com/" rel="nofollow">malshare.com</a></li>
<li><a href="https://github.com/michiwend/gomusicbrainz" rel="nofollow">GoMusicBrainz</a> - Go MusicBrainz WS2 client library.</li>
<li><a href="https://github.com/google/google-api-go-client" rel="nofollow">google</a> - Auto-generated Google APIs for Go.</li>
<li><a href="https://github.com/chonthu/go-google-analytics" rel="nofollow">google-analytics</a> - Simple wrapper for easy google analytics reporting.</li>
<li><a href="https://github.com/GoogleCloudPlatform/gcloud-golang" rel="nofollow">google-cloud</a> - Google Cloud APIs Go Client Library.</li>
<li><a href="https://github.com/ngs/go-google-email-audit-api" rel="nofollow">google-email-audit-api</a> - Go client library for <a href="https://developers.google.com/admin-sdk/email-audit/" rel="nofollow">Google G Suite Email Audit API</a>.</li>
<li><a href="https://github.com/jsgilmore/gostorm" rel="nofollow">gostorm</a> - GoStorm is a Go library that implements the communications protocol required to write Storm spouts and Bolts in Go that communicate with the Storm shells.</li>
<li><a href="https://github.com/andybons/hipchat" rel="nofollow">hipchat</a> - This project implements a golang client library for the Hipchat API.</li>
<li><a href="https://github.com/daneharrigan/hipchat" rel="nofollow">hipchat (xmpp)</a> - A golang package to communicate with HipChat over XMPP.</li>
<li><a href="https://github.com/Henry-Sarabia/igdb" rel="nofollow">igdb</a> - Go client for the <a href="https://api.igdb.com/" rel="nofollow">Internet Game Database API</a>.</li>
<li><a href="https://github.com/ansd/lastpass-go" rel="nofollow">lastpass-go</a> - Go client library for the <a href="https://www.lastpass.com/" rel="nofollow">LastPass</a> API.</li>
<li><a href="https://github.com/clevabit/libgoffi" rel="nofollow">libgoffi</a> - Library adapter toolbox for native <a href="http://sourceware.org/libffi/" rel="nofollow">libffi</a> integration</li>
<li><a href="https://github.com/Medium/medium-sdk-go" rel="nofollow">Medium</a> - Golang SDK for Medium&#39;s OAuth2 API.</li>
<li><a href="https://github.com/andygrunwald/megos" rel="nofollow">megos</a> - Client library for accessing an <a href="http://mesos.apache.org/" rel="nofollow">Apache Mesos</a> cluster.</li>
<li><a href="https://github.com/minio/minio-go" rel="nofollow">minio-go</a> - Minio Go Library for Amazon S3 compatible cloud storage.</li>
<li><a href="https://github.com/dukex/mixpanel" rel="nofollow">mixpanel</a> - Mixpanel is a library for tracking events and sending Mixpanel profile updates to Mixpanel from your go applications.</li>
<li><a href="https://github.com/mxpv/patreon-go" rel="nofollow">patreon-go</a> - Go library for Patreon API.</li>
<li><a href="https://github.com/logpacker/PayPal-Go-SDK" rel="nofollow">paypal</a> - Wrapper for PayPal payment API.</li>
<li><a href="https://github.com/playlyfe/playlyfe-go-sdk" rel="nofollow">playlyfe</a> - The Playlyfe Rest API Go SDK.</li>
<li><a href="https://github.com/gregdel/pushover" rel="nofollow">pushover</a> - Go wrapper for the Pushover API.</li>
<li><a href="https://github.com/Omie/rrdaclient" rel="nofollow">rrdaclient</a> - Go Library to access statdns.com API, which is in turn RRDA API. DNS Queries over HTTP.</li>
<li><a href="https://github.com/rapito/go-shopify" rel="nofollow">shopify</a> - Go Library to make CRUD request to the Shopify API.</li>
<li><a href="https://github.com/rhnvrm/simples3" rel="nofollow">simples3</a> - Simple no frills AWS S3 Library using REST with V4 Signing written in Go.</li>
<li><a href="https://github.com/nlopes/slack" rel="nofollow">slack</a> - Slack API in Go.</li>
<li><a href="https://github.com/sergiotapia/smitego" rel="nofollow">smite</a> - Go package to wraps access to the Smite game API.</li>
<li><a href="https://github.com/rapito/go-spotify" rel="nofollow">spotify</a> - Go Library to access Spotify WEB API.</li>
<li><a href="https://github.com/sostronk/go-steam" rel="nofollow">steam</a> - Go Library to interact with Steam game servers.</li>
<li><a href="https://github.com/stripe/stripe-go" rel="nofollow">stripe</a> - Go client for the Stripe API.</li>
<li><a href="https://github.com/dietsche/textbelt" rel="nofollow">textbelt</a> - Go client for the textbelt.com txt messaging API.</li>
<li><a href="https://github.com/poorny/translate" rel="nofollow">translate</a> - Go online translation package.</li>
<li><a href="https://github.com/adlio/trello" rel="nofollow">Trello</a> - Go wrapper for the Trello API.</li>
<li><a href="https://github.com/mrbenosborne/tripadvisor-golang" rel="nofollow">TripAdvisor</a> - Go wrapper for the TripAdvisor API.</li>
<li><a href="https://github.com/mattcunningham/gumblr" rel="nofollow">tumblr</a> - Go wrapper for the Tumblr v2 API.</li>
<li><a href="https://github.com/bitfield/uptimerobot" rel="nofollow">uptimerobot</a> - Go wrapper and command-line client for the Uptime Robot v2 API.</li>
<li><a href="https://github.com/go-playground/webhooks" rel="nofollow">webhooks</a> - Webhook receiver for GitHub and Bitbucket.</li>
<li><a href="https://github.com/wit-ai/wit-go" rel="nofollow">wit-go</a> - Go client for wit.ai HTTP API.</li>
<li><a href="https://github.com/brunomvsouza/ynab.go" rel="nofollow">ynab</a> - Go wrapper for the YNAB API.</li>
<li><a href="https://github.com/gojuno/go-zooz" rel="nofollow">zooz</a> - Go client for the Zooz API.</li>
</ul>
<h2><a name="utilities" class="anchor" href="#utilities" rel="nofollow" aria-hidden="true"><span class="octicon octicon-link"></span></a>
Utilities</h2>

<p><em>General utilities and tools to make your life easier.</em></p>

<ul>
<li><a href="https://github.com/topfreegames/apm" rel="nofollow">apm</a> - Process manager for Golang applications with an HTTP API.</li>
<li><a href="https://github.com/icza/backscanner" rel="nofollow">backscanner</a> - A scanner similar to bufio.Scanner, but it reads and returns lines in reverse order, starting at a given position and going backward.</li>
<li><a href="https://github.com/Henry-Sarabia/blank" rel="nofollow">blank</a> - Verify or remove blanks and whitespace from strings.</li>
<li><a href="https://github.com/tmrts/boilr" rel="nofollow">boilr</a> - Blazingly fast CLI tool for creating projects from boilerplate templates.</li>
<li><a href="https://github.com/antham/chyle" rel="nofollow">chyle</a> - Changelog generator using a git repository with multiple configuration possibilities.</li>
<li><a href="https://github.com/cep21/circuit" rel="nofollow">circuit</a> - An efficient and feature complete Hystrix like Go implementation of the circuit breaker pattern.</li>
<li><a href="https://github.com/rubyist/circuitbreaker" rel="nofollow">circuitbreaker</a> - Circuit Breakers in Go.</li>
<li><a href="https://github.com/jonboulle/clockwork" rel="nofollow">clockwork</a> - A simple fake clock for golang.</li>
<li><a href="https://github.com/txgruppi/command" rel="nofollow">command</a> - Command pattern for Go with thread safe serial and parallel dispatcher.</li>
<li><a href="https://github.com/jutkko/copy-pasta" rel="nofollow">copy-pasta</a> - Universal multi-workstation clipboard that uses S3 like backend for the storage.</li>
<li><a href="https://github.com/bcicen/ctop" rel="nofollow">ctop</a> - <a href="http://ctop.sh" rel="nofollow">Top-like</a> interface (e.g. htop) for container metrics.</li>
<li><a href="https://github.com/posener/ctxutil" rel="nofollow">ctxutil</a> - A collection of utility functions for contexts.</li>
<li><a href="https://github.com/nikogura/dbt" rel="nofollow">dbt</a> - A framework for running self-updating signed binaries from a central, trusted repository.</li>
<li><a href="https://github.com/vrecan/death" rel="nofollow">Death</a> - Managing go application shutdown with signals.</li>
<li><a href="https://github.com/ulule/deepcopier" rel="nofollow">Deepcopier</a> - Simple struct copying for Go.</li>
<li><a href="https://github.com/derekparker/delve" rel="nofollow">delve</a> - Go debugger.</li>
<li><a href="https://github.com/kirillDanshin/dlog" rel="nofollow">dlog</a> - Compile-time controlled logger to make your release smaller without removing debug calls.</li>
<li><a href="https://github.com/cristianoliveira/ergo" rel="nofollow">ergo</a> - The management of multiple local services running over different ports made easy.</li>
<li><a href="https://github.com/nullne/evaluator" rel="nofollow">evaluator</a> - Evaluate an expression dynamicly based on s-expression. It&#39;s simple and easy to extend.</li>
<li><a href="https://github.com/h2non/filetype" rel="nofollow">filetype</a> - Small package to infer the file type checking the magic numbers signature.</li>
<li><a href="https://github.com/yaronsumel/filler" rel="nofollow">filler</a> - small utility to fill structs using &#34;fill&#34; tag.</li>
<li><a href="https://github.com/gookit/filter" rel="nofollow">filter</a> - provide filtering, sanitizing, and conversion of Go data.</li>
<li><a href="https://github.com/junegunn/fzf" rel="nofollow">fzf</a> - Command-line fuzzy finder written in Go.</li>
<li><a href="https://github.com/maxcnunes/gaper" rel="nofollow">gaper</a> - Builds and restarts a Go project when it crashes or some watched file changes.</li>
<li><a href="https://github.com/go-playground/generate" rel="nofollow">generate</a> - runs go generate recursively on a specified path or environment variable and can filter by regex.</li>
<li><a href="https://github.com/antham/ghokin" rel="nofollow">ghokin</a> - Parallelized formatter with no external dependencies for gherkin (cucumber, behat...).</li>
<li><a href="https://github.com/git-time-metric/gtm" rel="nofollow">git-time-metric</a> - Simple, seamless, lightweight time tracking for Git.</li>
<li><a href="https://github.com/asticode/go-astitodo" rel="nofollow">go-astitodo</a> - Parse TODOs in your GO code.</li>
<li><a href="https://github.com/wendigo/go-bind-plugin" rel="nofollow">go-bind-plugin</a> - go:generate tool for wrapping symbols exported by golang plugins (1.8 only).</li>
<li><a href="https://github.com/gabstv/go-bsdiff" rel="nofollow">go-bsdiff</a> - Pure Go bsdiff and bspatch libraries and CLI tools.</li>
<li><a href="https://github.com/ungerik/go-dry" rel="nofollow">go-dry</a> - DRY (don&#39;t repeat yourself) package for Go.</li>
<li><a href="https://github.com/thoas/go-funk" rel="nofollow">go-funk</a> - Modern Go utility library which provides helpers (map, find, contains, filter, chunk, reverse, ...).</li>
<li><a href="https://github.com/Talento90/go-health" rel="nofollow">go-health</a> - Health package simplifies the way you add health check to your services.</li>
<li><a href="https://github.com/mozillazg/go-httpheader" rel="nofollow">go-httpheader</a> - Go library for encoding structs into Header fields.</li>
<li><a href="https://github.com/mvmaasakkers/go-problemdetails" rel="nofollow">go-problemdetails</a> - Go package for working with Problem Details.</li>
<li><a href="https://github.com/beefsack/go-rate" rel="nofollow">go-rate</a> - Timed rate limiter for Go.</li>
<li><a href="https://github.com/ikeikeikeike/go-sitemap-generator" rel="nofollow">go-sitemap-generator</a> - XML Sitemap generator written in Go.</li>
<li><a href="https://github.com/sadlil/go-trigger" rel="nofollow">go-trigger</a> - Go-lang global event triggerer, Register Events with an id and trigger the event from anywhere from your project.</li>
<li><a href="https://github.com/carlescere/goback" rel="nofollow">goback</a> - Go simple exponential backoff package.</li>
<li><a href="https://github.com/VividCortex/godaemon" rel="nofollow">godaemon</a> - Utility to write daemons.</li>
<li><a href="https://github.com/dropbox/godropbox" rel="nofollow">godropbox</a> - Common libraries for writing Go services/applications from Dropbox.</li>
<li><a href="https://github.com/cosiner/gohper" rel="nofollow">gohper</a> - Various tools/modules help for development.</li>
<li><a href="https://github.com/msempere/golarm" rel="nofollow">golarm</a> - Fire alarms with system events.</li>
<li><a href="https://github.com/mlimaloureiro/golog" rel="nofollow">golog</a> - Easy and lightweight CLI tool to time track your tasks.</li>
<li><a href="https://github.com/bndr/gopencils" rel="nofollow">gopencils</a> - Small and simple package to easily consume REST APIs.</li>
<li><a href="https://github.com/michiwend/goplaceholder" rel="nofollow">goplaceholder</a> - a small golang lib to generate placeholder images.</li>
<li><a href="https://github.com/philipjkim/goreadability" rel="nofollow">goreadability</a> - Webpage summary extractor using Facebook Open Graph and arc90&#39;s readability.</li>
<li><a href="https://github.com/goreleaser/goreleaser" rel="nofollow">goreleaser</a> - Deliver Go binaries as fast and easily as possible.</li>
<li><a href="https://github.com/wgliang/goreporter" rel="nofollow">goreporter</a> - Golang tool that does static analysis, unit testing, code review and generate code quality report.</li>
<li><a href="https://github.com/linxGnu/goseaweedfs" rel="nofollow">goseaweedfs</a> - SeaweedFS client library with almost full features.</li>
<li><a href="https://github.com/ik5/gostrutils" rel="nofollow">gostrutils</a> - Collections of string manipulation and conversion functions.</li>
<li><a href="https://github.com/subosito/gotenv" rel="nofollow">gotenv</a> - Load environment variables from <code>.env</code> or any <code>io.Reader</code> in Go.</li>
<li><a href="https://github.com/tenntenn/gpath" rel="nofollow">gpath</a> - Library to simplify access struct fields with Go&#39;s expression in reflection.</li>
<li><a href="https://github.com/novalagung/gubrak" rel="nofollow">gubrak</a> - Golang utility library with syntactic sugar. It&#39;s like lodash, but for golang.</li>
<li><a href="https://github.com/miguelpragier/handy" rel="nofollow">handy</a> - Many utilities and helpers like string handlers/formatters and validators.</li>
<li><a href="https://github.com/htcat/htcat" rel="nofollow">htcat</a> - Parallel and Pipelined HTTP GET Utility.</li>
<li><a href="https://github.com/github/hub" rel="nofollow">hub</a> - wrap git commands with additional functionality to interact with github from the terminal.</li>
<li><a href="https://github.com/afex/hystrix-go" rel="nofollow">hystrix-go</a> - Implements Hystrix patterns of programmer-defined fallbacks aka circuit breaker.</li>
<li><a href="https://github.com/immortal/immortal" rel="nofollow">immortal</a> - *nix cross-platform (OS agnostic) supervisor.</li>
<li><a href="https://github.com/mengzhuo/intrinsic" rel="nofollow">intrinsic</a> - Use x86 SIMD without writing any assembly code.</li>
<li><a href="https://github.com/gsamokovarov/jump" rel="nofollow">jump</a> - Jump helps you navigate faster by learning your habits.</li>
<li><a href="https://github.com/wesovilabs/koazee" rel="nofollow">koazee</a> - Library inspired in Lazy evaluation and functional programming that takes the hassle out of working with arrays.</li>
<li><a href="https://github.com/mennanov/limiters" rel="nofollow">limiters</a> - Rate limiters for distributed applications in Golang with configurable back-ends and distributed locks.</li>
<li><a href="https://github.com/jaschaephraim/lrserver" rel="nofollow">lrserver</a> - LiveReload server for Go.</li>
<li><a href="https://github.com/minio/mc" rel="nofollow">mc</a> - Minio Client provides minimal tools to work with Amazon S3 compatible cloud storage and filesystems.</li>
<li><a href="https://github.com/imdario/mergo" rel="nofollow">mergo</a> - Helper to merge structs and maps in Golang. Useful for configuration default values, avoiding messy if-statements.</li>
<li><a href="https://github.com/zRedShift/mimemagic" rel="nofollow">mimemagic</a> - Pure Go ultra performant MIME sniffing library/utility.</li>
<li><a href="https://github.com/aofei/mimesniffer" rel="nofollow">mimesniffer</a> - A MIME type sniffer for Go.</li>
<li><a href="https://github.com/gabriel-vasile/mimetype" rel="nofollow">mimetype</a> - Package for MIME type detection based on magic numbers.</li>
<li><a href="https://github.com/tdewolff/minify" rel="nofollow">minify</a> - Fast minifiers for HTML, CSS, JS, XML, JSON and SVG file formats.</li>
<li><a href="https://github.com/icza/minquery" rel="nofollow">minquery</a> - MongoDB / mgo.v2 query that supports efficient pagination (cursors to continue listing documents where we left off).</li>
<li><a href="https://github.com/tj/mmake" rel="nofollow">mmake</a> - Modern Make.</li>
<li><a href="https://github.com/StabbyCutyou/moldova" rel="nofollow">moldova</a> - Utility for generating random data based on an input template.</li>
<li><a href="https://github.com/davrodpin/mole" rel="nofollow">mole</a> - cli app to easily create ssh tunnels.</li>
<li><a href="https://github.com/linxGnu/mssqlx" rel="nofollow">mssqlx</a> - Database client library, proxy for any master slave, master master structures. Lightweight and auto balancing in mind.</li>
<li><a href="https://github.com/VividCortex/multitick" rel="nofollow">multitick</a> - Multiplexor for aligned tickers.</li>
<li><a href="https://github.com/inancgumus/myhttp" rel="nofollow">myhttp</a> - Simple API to make HTTP GET requests with timeout support.</li>
<li><a href="https://github.com/xta/okrun" rel="nofollow">okrun</a> - go run error steamroller.</li>
<li><a href="https://github.com/btnguyen2k/olaf" rel="nofollow">olaf</a> - Twitter Snowflake implemented in Go.</li>
<li><a href="https://github.com/adelowo/onecache" rel="nofollow">onecache</a> - Caching library with support for multiple backend stores (Redis, Memcached, filesystem etc).</li>
<li><a href="https://github.com/maruel/panicparse" rel="nofollow">panicparse</a> - Groups similar goroutines and colorizes stack dump.</li>
<li><a href="https://github.com/peco/peco" rel="nofollow">peco</a> - Simplistic interactive filtering tool.</li>
<li><a href="https://github.com/arthurkushman/pgo" rel="nofollow">pgo</a> - Convenient functions for PHP community.</li>
<li><a href="https://github.com/VividCortex/pm" rel="nofollow">pm</a> - Process (i.e. goroutine) manager with an HTTP API.</li>
<li><a href="https://github.com/zpatrick/rclient" rel="nofollow">rclient</a> - Readable, flexible, simple-to-use client for REST APIs.</li>
<li><a href="https://github.com/tockins/realize" rel="nofollow">realize</a> - Go build system with file watchers and live reload. Run, build and watch file changes with custom paths.</li>
<li><a href="https://github.com/ssgreg/repeat" rel="nofollow">repeat</a> - Go implementation of different backoff strategies useful for retrying operations and heartbeating.</li>
<li><a href="https://github.com/mozillazg/request" rel="nofollow">request</a> - Go HTTP Requests for Humans™.</li>
<li><a href="https://github.com/abo/rerate" rel="nofollow">rerate</a> - Redis-based rate counter and rate limiter for Go.</li>
<li><a href="https://github.com/ivpusic/rerun" rel="nofollow">rerun</a> - Recompiling and rerunning go apps when source changes.</li>
<li><a href="https://github.com/edermanoel94/rest-go" rel="nofollow">rest-go</a> - A package that provide many helpful methods for working with rest api.</li>
<li><a href="https://github.com/go-resty/resty" rel="nofollow">resty</a> - Simple HTTP and REST client for Go inspired by Ruby rest-client.</li>
<li><a href="https://github.com/kamilsk/retry" rel="nofollow">retry</a> - The most advanced functional mechanism to perform actions repetitively until successful.</li>
<li><a href="https://github.com/percolate/retry" rel="nofollow">retry</a> - A simple but highly configurable retry package for Go.</li>
<li><a href="https://github.com/thedevsaddam/retry" rel="nofollow">retry</a> - Simple and easy retry mechanism package for Go.</li>
<li><a href="https://github.com/shafreeck/retry" rel="nofollow">retry</a> - A pretty simple library to ensure your work to be done.</li>
<li><a href="https://github.com/rafaeljesus/retry-go" rel="nofollow">retry-go</a> - Retrying made simple and easy for golang.</li>
<li><a href="https://github.com/VividCortex/robustly" rel="nofollow">robustly</a> - Runs functions resiliently, catching and restarting panics.</li>
<li><a href="https://github.com/blockloop/scan" rel="nofollow">scan</a> - Scan golang <code>sql.Rows</code> directly to structs, slices, or primitive types.</li>
<li><a href="https://github.com/syntaqx/serve" rel="nofollow">serve</a> - A static http server anywhere you need.</li>
<li><a href="https://github.com/ztrue/shutdown" rel="nofollow">shutdown</a> - App shutdown hooks for <code>os.Signal</code> handling.</li>
<li><a href="https://github.com/chrispassas/silk" rel="nofollow">silk</a> - Read silk netflow files.</li>
<li><a href="https://github.com/Henry-Sarabia/sliceconv" rel="nofollow">sliceconv</a> - Slice conversion between primitive types.</li>
<li><a href="https://github.com/leaanthony/slicer" rel="nofollow">slicer</a> - Makes working with slices easier.</li>
<li><a href="https://github.com/briandowns/spinner" rel="nofollow">spinner</a> - Go package to easily provide a terminal spinner with options.</li>
<li><a href="https://github.com/jmoiron/sqlx" rel="nofollow">sqlx</a> - provides a set of extensions on top of the excellent built-in database/sql package.</li>
<li><a href="https://github.com/yaa110/sslice" rel="nofollow">sslice</a> - Create a slice which is always sorted.</li>
<li><a href="https://github.com/asdine/storm" rel="nofollow">Storm</a> - Simple and powerful toolkit for BoltDB.</li>
<li><a href="https://github.com/PumpkinSeed/structs" rel="nofollow">structs</a> - Implement simple functions to manipulate structs.</li>
<li><a href="https://github.com/go-task/task" rel="nofollow">Task</a> - simple &#34;Make&#34; alternative.</li>
<li><a href="https://github.com/viant/toolbox" rel="nofollow">toolbox</a> - Slice, map, multimap, struct, function, data conversion utilities. Service router, macro evaluator, tokenizer.</li>
<li><a href="https://github.com/alxrm/ugo" rel="nofollow">ugo</a> - ugo is slice toolbox with concise syntax for Go.</li>
<li><a href="https://github.com/esemplastic/unis" rel="nofollow">UNIS</a> - Common Architecture™ for String Utilities in Go.</li>
<li><a href="https://github.com/knq/usql" rel="nofollow">usql</a> - usql is a universal command-line interface for SQL databases.</li>
<li><a href="https://github.com/shomali11/util" rel="nofollow">util</a> - Collection of useful utility functions. (strings, concurrency, manipulations, ...).</li>
<li><a href="https://github.com/asciimoo/wuzz" rel="nofollow">wuzz</a> - Interactive cli tool for HTTP inspection.</li>
<li><a href="https://github.com/monmohan/xferspdy" rel="nofollow">xferspdy</a> - Xferspdy provides binary diff and patch library in golang.</li>
</ul>
<h2><a name="uuid" class="anchor" href="#uuid" rel="nofollow" aria-hidden="true"><span class="octicon octicon-link"></span></a>
UUID</h2>

<p><em>Libraries for working with UUIDs.</em></p>

<ul>
<li><a href="https://github.com/jakehl/goid" rel="nofollow">goid</a> - Generate and Parse RFC4122 compliant V4 UUIDs.</li>
<li><a href="https://github.com/aidarkhanov/nanoid" rel="nofollow">nanoid</a> - A tiny and efficient Go unique string ID generator.</li>
<li><a href="https://github.com/muyo/sno" rel="nofollow">sno</a> - Compact, sortable and fast unique IDs with embedded metadata.</li>
<li><a href="https://github.com/oklog/ulid" rel="nofollow">ulid</a> - Go implementation of ULID (Universally Unique Lexicographically Sortable Identifier).</li>
<li><a href="https://gitlab.com/skilstak/code/go/uniq" rel="nofollow">uniq</a> - No hassle safe, fast unique identifiers with commands.</li>
<li><a href="https://github.com/agext/uuid" rel="nofollow">uuid</a> - Generate, encode, and decode UUIDs v1 with fast or cryptographic-quality random node identifier.</li>
<li><a href="https://github.com/gofrs/uuid" rel="nofollow">uuid</a> - Implementation of Universally Unique Identifier (UUID). Supports both creation and parsing of UUIDs. Actively maintained fork of satori uuid.</li>
<li><a href="https://github.com/edwingeng/wuid" rel="nofollow">wuid</a> - An extremely fast unique number generator, 10-135 times faster than UUID.</li>
</ul>
<h2><a name="validation" class="anchor" href="#validation" rel="nofollow" aria-hidden="true"><span class="octicon octicon-link"></span></a>
Validation</h2>

<p><em>Libraries for validation.</em></p>

<ul>
<li><a href="https://github.com/osamingo/checkdigit" rel="nofollow">checkdigit</a> - Provide check digit algorithms (Luhn, Verhoeff, Damm) and calculators (ISBN, EAN, JAN, UPC, etc.).</li>
<li><a href="https://github.com/asaskevich/govalidator" rel="nofollow">govalidator</a> - Validators and sanitizers for strings, numerics, slices and structs.</li>
<li><a href="https://github.com/thedevsaddam/govalidator" rel="nofollow">govalidator</a> - Validate Golang request data with simple rules. Highly inspired by Laravel&#39;s request validation.</li>
<li><a href="https://github.com/faceair/jio" rel="nofollow">jio</a> - jio is a json schema validator similar to <a href="https://github.com/hapijs/joi" rel="nofollow">joi</a>.</li>
<li><a href="https://github.com/go-ozzo/ozzo-validation" rel="nofollow">ozzo-validation</a> - Supports validation of various data types (structs, strings, maps, slices, etc.) with configurable and extensible validation rules specified in usual code constructs instead of struct tags.</li>
<li><a href="https://github.com/thazelart/terraform-validator" rel="nofollow">terraform-validator</a> - A norms and conventions validator for Terraform.</li>
<li><a href="https://github.com/gookit/validate" rel="nofollow">validate</a> - Go package for data validation and filtering. support validate Map, Struct, Request(Form, JSON, url.Values, Uploaded Files) data and more features.</li>
<li><a href="https://github.com/gobuffalo/validate" rel="nofollow">validate</a> - This package provides a framework for writing validations for Go applications.</li>
<li><a href="https://github.com/go-playground/validator" rel="nofollow">validator</a> - Go Struct and Field validation, including Cross Field, Cross Struct, Map, Slice and Array diving.</li>
</ul>
<h2><a name="version-control" class="anchor" href="#version-control" rel="nofollow" aria-hidden="true"><span class="octicon octicon-link"></span></a>
Version Control</h2>

<p><em>Libraries for version control.</em></p>

<ul>
<li><a href="https://github.com/rjeczalik/gh" rel="nofollow">gh</a> - Scriptable server and net/http middleware for GitHub Webhooks.</li>
<li><a href="https://github.com/libgit2/git2go" rel="nofollow">git2go</a> - Go bindings for libgit2.</li>
<li><a href="https://github.com/src-d/go-git" rel="nofollow">go-git</a> - highly extensible Git implementation in pure Go.</li>
<li><a href="https://github.com/sourcegraph/go-vcs" rel="nofollow">go-vcs</a> - manipulate and inspect VCS repositories in Go.</li>
<li><a href="https://github.com/src-d/hercules" rel="nofollow">hercules</a> - gaining advanced insights from Git repository history.</li>
<li><a href="https://github.com/beyang/hgo" rel="nofollow">hgo</a> - Hgo is a collection of Go packages providing read-access to local Mercurial repositories.</li>
</ul>
<h2><a name="video" class="anchor" href="#video" rel="nofollow" aria-hidden="true"><span class="octicon octicon-link"></span></a>
Video</h2>

<p><em>Libraries for manipulating video.</em></p>

<ul>
<li><a href="https://github.com/3d0c/gmf" rel="nofollow">gmf</a> - Go bindings for FFmpeg av* libraries.</li>
<li><a href="https://github.com/asticode/go-astisub" rel="nofollow">go-astisub</a> - Manipulate subtitles in GO (.srt, .stl, .ttml, .webvtt, .ssa/.ass, teletext, .smi, etc.).</li>
<li><a href="https://github.com/asticode/go-astits" rel="nofollow">go-astits</a> - Parse and demux MPEG Transport Streams (.ts) natively in GO.</li>
<li><a href="https://github.com/quangngotan95/go-m3u8" rel="nofollow">go-m3u8</a> - Parser and generator library for Apple m3u8 playlists.</li>
<li><a href="https://github.com/giorgisio/goav" rel="nofollow">goav</a> - Comphrensive Go bindings for FFmpeg.</li>
<li><a href="https://github.com/ziutek/gst" rel="nofollow">gst</a> - Go bindings for GStreamer.</li>
<li><a href="https://github.com/wargarblgarbl/libgosubs" rel="nofollow">libgosubs</a> - Subtitle format support for go. Supports .srt, .ttml, and .ass.</li>
<li><a href="https://github.com/adrg/libvlc-go" rel="nofollow">libvlc-go</a> - Go bindings for libvlc 2.X/3.X/4.X (used by the VLC media player).</li>
<li><a href="https://github.com/korandiz/v4l" rel="nofollow">v4l</a> - Video capture library for Linux, written in Go.</li>
</ul>
<h2><a name="web-frameworks" class="anchor" href="#web-frameworks" rel="nofollow" aria-hidden="true"><span class="octicon octicon-link"></span></a>
Web Frameworks</h2>

<p><em>Full stack web frameworks.</em></p>

<ul>
<li><a href="https://aahframework.org" rel="nofollow">aah</a> - Scalable, performant, rapid development Web framework for Go.</li>
<li><a href="https://github.com/aerogo/aero" rel="nofollow">Aero</a> - High-performance web framework for Go, reaches top scores in Lighthouse.</li>
<li><a href="https://github.com/aofei/air" rel="nofollow">Air</a> - An ideally refined web framework for Go.</li>
<li><a href="https://github.com/nsheremet/banjo" rel="nofollow">Banjo</a> - Very simple and fast web framework for Go.</li>
<li><a href="https://github.com/astaxie/beego" rel="nofollow">Beego</a> - beego is an open-source, high-performance web framework for the Go programming language.</li>
<li><a href="http://gobuffalo.io" rel="nofollow">Buffalo</a> - Bringing the productivity of Rails to Go!</li>
<li><a href="https://github.com/labstack/echo" rel="nofollow">Echo</a> - High performance, minimalist Go web framework.</li>
<li><a href="https://github.com/zpatrick/fireball" rel="nofollow">Fireball</a> - More &#34;natural&#34; feeling web framework.</li>
<li><a href="https://github.com/gin-gonic/gin" rel="nofollow">Gin</a> - Gin is a web framework written in Go! It features a martini-like API with much better performance, up to 40 times faster. If you need performance and good productivity.</li>
<li><a href="https://github.com/xxjwxc/ginrpc" rel="nofollow">Ginrpc</a> - Gin parameter automatic binding tool,gin rpc tools.</li>
<li><a href="https://github.com/NYTimes/gizmo" rel="nofollow">Gizmo</a> - Microservice toolkit used by the New York Times.</li>
<li><a href="https://github.com/ant0ine/go-json-rest" rel="nofollow">go-json-rest</a> - Quick and easy way to setup a RESTful JSON API.</li>
<li><a href="https://github.com/ungerik/go-rest" rel="nofollow">go-rest</a> - Small and evil REST framework for Go.</li>
<li><a href="https://github.com/goadesign/goa" rel="nofollow">Goa</a> - Goa provides a holistic approach for developing remote APIs and microservices in Go.</li>
<li><a href="https://github.com/goa-go/goa" rel="nofollow">goa</a> - goa is just like koajs for golang, it is a flexible, light, high-performance and extensible web framework based on middleware.</li>
<li><a href="https://github.com/fulldump/golax" rel="nofollow">Golax</a> - A non Sinatra fast HTTP framework with support for Google custom methods, deep interceptors, recursion and more.</li>
<li><a href="https://github.com/dinever/golf" rel="nofollow">Golf</a> - Golf is a fast, simple and lightweight micro-web framework for Go. It comes with powerful features and has no dependencies other than the Go Standard Library.</li>
<li><a href="https://github.com/rainycape/gondola" rel="nofollow">Gondola</a> - The web framework for writing faster sites, faster.</li>
<li><a href="https://github.com/mustafaakin/gongular" rel="nofollow">gongular</a> - Fast Go web framework with input mapping/validation and (DI) Dependency Injection.</li>
<li><a href="https://github.com/hidevopsio/hiboot" rel="nofollow">hiboot</a> - hiboot is a high performance web application framework with auto configuration and dependency injection support.</li>
<li><a href="https://github.com/go-macaron/macaron" rel="nofollow">Macaron</a> - Macaron is a high productive and modular design web framework in Go.</li>
<li><a href="https://github.com/paulbellamy/mango" rel="nofollow">mango</a> - Mango is a modular web-application framework for Go, inspired by Rack, and PEP333.</li>
<li><a href="https://github.com/claygod/microservice" rel="nofollow">Microservice</a> - The framework for the creation of microservices, written in Golang.</li>
<li><a href="https://github.com/ivpusic/neo" rel="nofollow">neo</a> - Neo is minimal and fast Go Web Framework with extremely simple API.</li>
<li><a href="https://github.com/beatlabs/patron" rel="nofollow">patron</a> - Patron is a microservice framework following best cloud practices with a focus on productivity.</li>
<li><a href="https://github.com/resoursea/api" rel="nofollow">Resoursea</a> - REST framework for quickly writing resource based services.</li>
<li><a href="http://rest-layer.io" rel="nofollow">REST Layer</a> - Framework to build REST/GraphQL API on top of databases with mostly configuration over code.</li>
<li><a href="https://github.com/revel/revel" rel="nofollow">Revel</a> - High-productivity web framework for the Go language.</li>
<li><a href="https://github.com/goanywhere/rex" rel="nofollow">rex</a> - Rex is a library for modular development built upon gorilla/mux, fully compatible with <code>net/http</code>.</li>
<li><a href="https://github.com/gookit/rux" rel="nofollow">rux</a> - Simple and fast web framework for build golang HTTP applications.</li>
<li><a href="https://github.com/lunny/tango" rel="nofollow">tango</a> - Micro &amp; pluggable web framework for Go.</li>
<li><a href="https://github.com/rcrowley/go-tigertonic" rel="nofollow">tigertonic</a> - Go framework for building JSON web services inspired by Dropwizard.</li>
<li><a href="https://github.com/uadmin/uadmin" rel="nofollow">uAdmin</a> - Fully featured web framework for Golang, inspired by Django.</li>
<li><a href="https://github.com/gernest/utron" rel="nofollow">utron</a> - Lightweight MVC framework for Go(Golang).</li>
<li><a href="https://github.com/aisk/vox" rel="nofollow">vox</a> - A golang web framework for humans, inspired by Koa heavily.</li>
<li><a href="https://github.com/bnkamalesh/webgo" rel="nofollow">WebGo</a> - A micro-framework to build web apps; with handler chaining, middleware and context injection. With standard library compliant HTTP handlers(i.e. http.HandlerFunc).</li>
<li><a href="https://github.com/yarf-framework/yarf" rel="nofollow">YARF</a> - Fast micro-framework designed to build REST APIs and web services in a fast and simple way.</li>
</ul>
<h3><a name="middlewares" class="anchor" href="#middlewares" rel="nofollow" aria-hidden="true"><span class="octicon octicon-link"></span></a>
Middlewares</h3>
<h4><a name="actual-middlewares" class="anchor" href="#actual-middlewares" rel="nofollow" aria-hidden="true"><span class="octicon octicon-link"></span></a>
Actual middlewares</h4>

<ul>
<li><a href="https://github.com/posener/client-timing" rel="nofollow">client-timing</a> - An HTTP client for Server-Timing header.</li>
<li><a href="https://github.com/rs/cors" rel="nofollow">CORS</a> - Easily add CORS capabilities to your API.</li>
<li><a href="https://github.com/rs/formjson" rel="nofollow">formjson</a> - Transparently handle JSON input as a standard form POST.</li>
<li><a href="https://github.com/mitchellh/go-server-timing" rel="nofollow">go-server-timing</a> - Add/parse Server-Timing header.</li>
<li><a href="https://github.com/ulule/limiter" rel="nofollow">Limiter</a> - Dead simple rate limit middleware for Go.</li>
<li><a href="https://github.com/philippgille/ln-paywall" rel="nofollow">ln-paywall</a> - Go middleware for monetizing APIs on a per-request basis with the Lightning Network (Bitcoin).</li>
<li><a href="https://github.com/didip/tollbooth" rel="nofollow">Tollbooth</a> - Rate limit HTTP request handler.</li>
<li><a href="https://github.com/sebest/xff" rel="nofollow">XFF</a> - Handle <code>X-Forwarded-For</code> header and friends.</li>
</ul>
<h4><a name="libraries-for-creating-http-middlewares" class="anchor" href="#libraries-for-creating-http-middlewares" rel="nofollow" aria-hidden="true"><span class="octicon octicon-link"></span></a>
Libraries for creating HTTP middlewares</h4>

<ul>
<li><a href="https://github.com/justinas/alice" rel="nofollow">alice</a> - Painless middleware chaining for Go.</li>
<li><a href="https://github.com/codemodus/catena" rel="nofollow">catena</a> - http.Handler wrapper catenation (same API as &#34;chain&#34;).</li>
<li><a href="https://github.com/codemodus/chain" rel="nofollow">chain</a> - Handler wrapper chaining with scoped data (net/context-based &#34;middleware&#34;).</li>
<li><a href="https://github.com/go-on/wrap" rel="nofollow">go-wrap</a> - Small middlewares package for net/http.</li>
<li><a href="https://github.com/alioygur/gores" rel="nofollow">gores</a> - Go package that handles HTML, JSON, XML and etc. responses. Useful for RESTful APIs.</li>
<li><a href="https://github.com/carbocation/interpose" rel="nofollow">interpose</a> - Minimalist net/http middleware for golang.</li>
<li><a href="https://github.com/stephens2424/muxchain" rel="nofollow">muxchain</a> - Lightweight middleware for net/http.</li>
<li><a href="https://github.com/urfave/negroni" rel="nofollow">negroni</a> - Idiomatic HTTP middleware for Golang.</li>
<li><a href="https://github.com/unrolled/render" rel="nofollow">render</a> - Go package for easily rendering JSON, XML, and HTML template responses.</li>
<li><a href="https://github.com/thedevsaddam/renderer" rel="nofollow">renderer</a> - Simple, lightweight and faster response (JSON, JSONP, XML, YAML, HTML, File) rendering package for Go.</li>
<li><a href="https://github.com/InVisionApp/rye" rel="nofollow">rye</a> - Tiny Go middleware library (with canned Middlewares) that supports JWT, CORS, Statsd, and Go 1.7 context.</li>
<li><a href="https://github.com/thoas/stats" rel="nofollow">stats</a> - Go middleware that stores various information about your web application.</li>
</ul>
<h3><a name="routers" class="anchor" href="#routers" rel="nofollow" aria-hidden="true"><span class="octicon octicon-link"></span></a>
Routers</h3>

<ul>
<li><a href="https://github.com/gernest/alien" rel="nofollow">alien</a> - Lightweight and fast http router from outer space.</li>
<li><a href="https://github.com/GuilhermeCaruso/bellt" rel="nofollow">bellt</a> - A simple Go HTTP router.</li>
<li><a href="https://github.com/go-zoo/bone" rel="nofollow">Bone</a> - Lightning Fast HTTP Multiplexer.</li>
<li><a href="https://github.com/claygod/Bxog" rel="nofollow">Bxog</a> - Simple and fast HTTP router for Go. It works with routes of varying difficulty, length and nesting. And he knows how to create a URL from the received parameters.</li>
<li><a href="https://github.com/go-chi/chi" rel="nofollow">chi</a> - Small, fast and expressive HTTP router built on net/context.</li>
<li><a href="https://github.com/buaazp/fasthttprouter" rel="nofollow">fasthttprouter</a> - High performance router forked from <code>httprouter</code>. The first router fit for <code>fasthttp</code>.</li>
<li><a href="https://github.com/razonyang/fastrouter" rel="nofollow">FastRouter</a> - a fast, flexible HTTP router written in Go.</li>
<li><a href="https://github.com/gocraft/web" rel="nofollow">gocraft/web</a> - Mux and middleware package in Go.</li>
<li><a href="https://github.com/goji/goji" rel="nofollow">Goji</a> - Goji is a minimalistic and flexible HTTP request multiplexer with support for <code>net/context</code>.</li>
<li><a href="https://github.com/goroute/route" rel="nofollow">goroute</a> - Simple yet powerful HTTP request multiplexer.</li>
<li><a href="https://github.com/vardius/gorouter" rel="nofollow">GoRouter</a> - GoRouter is a Server/API micro framwework, HTTP request router, multiplexer, mux that provides request router with middleware supporting <code>net/context</code>.</li>
<li><a href="https://github.com/gowww/router" rel="nofollow">gowww/router</a> - Lightning fast HTTP router fully compatible with the net/http.Handler interface.</li>
<li><a href="https://github.com/julienschmidt/httprouter" rel="nofollow">httprouter</a> - High performance router. Use this and the standard http handlers to form a very high performance web framework.</li>
<li><a href="https://github.com/dimfeld/httptreemux" rel="nofollow">httptreemux</a> - High-speed, flexible tree-based HTTP router for Go. Inspiration from httprouter.</li>
<li><a href="https://github.com/go-playground/lars" rel="nofollow">lars</a> - Is a lightweight, fast and extensible zero allocation HTTP router for Go used to create customizable frameworks.</li>
<li><a href="https://github.com/gorilla/mux" rel="nofollow">mux</a> - Powerful URL router and dispatcher for golang.</li>
<li><a href="https://github.com/go-ozzo/ozzo-routing" rel="nofollow">ozzo-routing</a> - An extremely fast Go (golang) HTTP router that supports regular expression route matching. Comes with full support for building RESTful APIs.</li>
<li><a href="https://github.com/go-playground/pure" rel="nofollow">pure</a> - Is a lightweight HTTP router that sticks to the std &#34;net/http&#34; implementation.</li>
<li><a href="https://github.com/VividCortex/siesta" rel="nofollow">Siesta</a> - Composable framework to write middleware and handlers.</li>
<li><a href="https://github.com/husobee/vestigo" rel="nofollow">vestigo</a> - Performant, stand-alone, HTTP compliant URL Router for go web applications.</li>
<li><a href="https://github.com/nbari/violetear" rel="nofollow">violetear</a> - Go HTTP router.</li>
<li><a href="https://github.com/rs/xmux" rel="nofollow">xmux</a> - High performance muxer based on <code>httprouter</code> with <code>net/context</code> support.</li>
<li><a href="https://github.com/xujiajun/gorouter" rel="nofollow">xujiajun/gorouter</a> - A simple and fast HTTP router for Go.</li>
</ul>
<h2><a name="windows" class="anchor" href="#windows" rel="nofollow" aria-hidden="true"><span class="octicon octicon-link"></span></a>
Windows</h2>

<ul>
<li><a href="https://github.com/gonutz/d3d9" rel="nofollow">d3d9</a> - Go bindings for Direct3D9.</li>
<li><a href="https://github.com/go-ole/go-ole" rel="nofollow">go-ole</a> - Win32 OLE implementation for golang.</li>
<li><a href="https://github.com/MonaxGT/gosddl" rel="nofollow">gosddl</a> - Converter from SDDL-string to user-friendly JSON. SDDL consist of four part: Owner, Primary Group, DACL, SACL.</li>
</ul>
<h2><a name="xml" class="anchor" href="#xml" rel="nofollow" aria-hidden="true"><span class="octicon octicon-link"></span></a>
XML</h2>

<p><em>Libraries and tools for manipulating XML.</em></p>

<ul>
<li><a href="https://github.com/xml-comp/xml-comp" rel="nofollow">XML-Comp</a> - Simple command line XML comparer that generates diffs of folders, files and tags.</li>
<li><a href="https://github.com/sbabiv/xml2map" rel="nofollow">xml2map</a> - XML to MAP converter written Golang.</li>
<li><a href="https://github.com/shabbyrobe/xmlwriter" rel="nofollow">xmlwriter</a> - Procedural XML generation API based on libxml2&#39;s xmlwriter module.</li>
<li><a href="https://github.com/antchfx/xpath" rel="nofollow">xpath</a> - XPath package for Go.</li>
<li><a href="https://github.com/antchfx/xquery" rel="nofollow">xquery</a> - XQuery lets you extract data from HTML/XML documents using XPath expression.</li>
<li><a href="https://github.com/miku/zek" rel="nofollow">zek</a> - Generate a Go struct from XML.</li>
</ul>
<h1><a name="tools" class="anchor" href="#tools" rel="nofollow" aria-hidden="true"><span class="octicon octicon-link"></span></a>
Tools</h1>

<p><em>Go software and plugins.</em></p>
<h2><a name="code-analysis" class="anchor" href="#code-analysis" rel="nofollow" aria-hidden="true"><span class="octicon octicon-link"></span></a>
Code Analysis</h2>

<ul>
<li><a href="https://github.com/bradleyfalzon/apicompat" rel="nofollow">apicompat</a> - Checks recent changes to a Go project for backwards incompatible changes.</li>
<li><a href="https://github.com/mibk/dupl" rel="nofollow">dupl</a> - Tool for code clone detection.</li>
<li><a href="https://github.com/kisielk/errcheck" rel="nofollow">errcheck</a> - Errcheck is a program for checking for unchecked errors in Go programs.</li>
<li><a href="https://github.com/davecheney/gcvis" rel="nofollow">gcvis</a> - Visualise Go program GC trace data in real time.</li>
<li><a href="https://github.com/qiniu/checkstyle" rel="nofollow">go-checkstyle</a> - checkstyle is a style check tool like java checkstyle. This tool inspired by java checkstyle, golint. The style referred to some points in Go Code Review Comments.</li>
<li><a href="https://github.com/roblaszczak/go-cleanarch" rel="nofollow">go-cleanarch</a> - go-cleanarch was created to validate Clean Architecture rules, like a The Dependency Rule and interaction between packages in your Go projects.</li>
<li><a href="https://github.com/go-critic/go-critic" rel="nofollow">go-critic</a> - source code linter that brings checks that are currently not implemented in other linters.</li>
<li><a href="https://github.com/psampaz/go-mod-outdated" rel="nofollow">go-mod-outdated</a> - An easy way to find outdated dependencies of your Go projects.</li>
<li><a href="https://github.com/firstrow/go-outdated" rel="nofollow">go-outdated</a> - Console application that displays outdated packages.</li>
<li><a href="https://github.com/yuroyoro/goast-viewer" rel="nofollow">goast-viewer</a> - Web based Golang AST visualizer.</li>
<li><a href="http://gocover.io/" rel="nofollow">GoCover.io</a> - GoCover.io offers the code coverage of any golang package as a service.</li>
<li><a href="https://godoc.org/golang.org/x/tools/cmd/goimports" rel="nofollow">goimports</a> - Tool to fix (add, remove) your Go imports automatically.</li>
<li><a href="https://golangci.com/" rel="nofollow">GolangCI</a> - GolangCI is an automated Golang code review service for GitHub pull requests. Service is open source and it&#39;s free for open source projects.</li>
<li><a href="https://github.com/golang/lint" rel="nofollow">GoLint</a> - Golint is a linter for Go source code.</li>
<li><a href="http://go-lint.appspot.com/" rel="nofollow">Golint online</a> - Lints online Go source files on GitHub, Bitbucket and Google Project Hosting using the golint package.</li>
<li><a href="https://sourcegraph.com/github.com/sqs/goreturns" rel="nofollow">goreturns</a> - Adds zero-value return statements to match the func return types.</li>
<li><a href="https://github.com/dominikh/go-tools/tree/master/cmd/gosimple" rel="nofollow">gosimple</a> - gosimple is a linter for Go source code that specialises on simplifying code.</li>
<li><a href="https://github.com/shurcooL/gostatus" rel="nofollow">gostatus</a> - Command line tool, shows the status of repositories that contain Go packages.</li>
<li><a href="https://github.com/surullabs/lint" rel="nofollow">lint</a> - Run linters as part of go test.</li>
<li><a href="https://github.com/z7zmey/php-parser" rel="nofollow">php-parser</a> - A Parser for PHP written in Go.</li>
<li><a href="https://github.com/dominikh/go-tools/tree/master/cmd/staticcheck" rel="nofollow">staticcheck</a> - staticcheck is <code>go vet</code> on steroids, applying a ton of static analysis checks you might be used to from tools like ReSharper for C#.</li>
<li><a href="https://github.com/verygoodsoftwarenotvirus/tarp" rel="nofollow">tarp</a> - tarp finds functions and methods without direct unit tests in Go source code.</li>
<li><a href="https://github.com/mdempsky/unconvert" rel="nofollow">unconvert</a> - Remove unnecessary type conversions from Go source.</li>
<li><a href="https://github.com/dominikh/go-tools/tree/master/cmd/unused" rel="nofollow">unused</a> - unused checks Go code for unused constants, variables, functions and types.</li>
<li><a href="https://github.com/mccoyst/validate" rel="nofollow">validate</a> - Automatically validates struct fields with tags.</li>
</ul>
<h2><a name="editor-plugins" class="anchor" href="#editor-plugins" rel="nofollow" aria-hidden="true"><span class="octicon octicon-link"></span></a>
Editor Plugins</h2>

<ul>
<li><a href="https://plugins.jetbrains.com/plugin/9568-go" rel="nofollow">Go plugin for JetBrains IDEs</a> - Go plugin for JetBrains IDEs.</li>
<li><a href="https://github.com/theia-ide/go-language-server" rel="nofollow">go-language-server</a> - A wrapper to turn the VSCode go extension into a language server supporting the language-server-protocol.</li>
<li><a href="https://github.com/dominikh/go-mode.el" rel="nofollow">go-mode</a> - Go mode for GNU/Emacs.</li>
<li><a href="https://github.com/joefitzgerald/go-plus" rel="nofollow">go-plus</a> - Go (Golang) Package For Atom That Adds Autocomplete, Formatting, Syntax Checking, Linting and Vetting.</li>
<li><a href="https://github.com/nsf/gocode" rel="nofollow">gocode</a> - Autocompletion daemon for the Go programming language.</li>
<li><a href="https://marketplace.visualstudio.com/items?itemName=MaxMedia.go-prof" rel="nofollow">goprofiling</a> - This extension adds benchmark profiling support for the Go language to VS Code.</li>
<li><a href="https://github.com/DisposaBoy/GoSublime" rel="nofollow">GoSublime</a> - Golang plugin collection for the text editor SublimeText 3 providing code completion and other IDE-like features.</li>
<li><a href="https://github.com/hexdigest/gounit-vim" rel="nofollow">gounit-vim</a> - Vim plugin for generating Go tests based on the function&#39;s or method&#39;s signature.</li>
<li><a href="https://github.com/theia-ide/theia-go-extension" rel="nofollow">theia-go-extension</a> - Go language support for the Theia IDE.</li>
<li><a href="https://github.com/rjohnsondev/vim-compiler-go" rel="nofollow">vim-compiler-go</a> - Vim plugin to highlight syntax errors on save.</li>
<li><a href="https://github.com/fatih/vim-go" rel="nofollow">vim-go</a> - Go development plugin for Vim.</li>
<li><a href="https://github.com/Microsoft/vscode-go" rel="nofollow">vscode-go</a> - Extension for Visual Studio Code (VS Code) which provides support for the Go language.</li>
<li><a href="https://github.com/eaburns/Watch" rel="nofollow">Watch</a> - Runs a command in an acme win on file changes.</li>
</ul>
<h2><a name="go-generate-tools" class="anchor" href="#go-generate-tools" rel="nofollow" aria-hidden="true"><span class="octicon octicon-link"></span></a>
Go Generate Tools</h2>

<ul>
<li><a href="https://github.com/usk81/generic" rel="nofollow">generic</a> - flexible data type for Go.</li>
<li><a href="https://github.com/cheekybits/genny" rel="nofollow">genny</a> - Elegant generics for Go.</li>
<li><a href="https://github.com/Parquery/gocontracts" rel="nofollow">gocontracts</a> - brings design-by-contract to Go by synchronizing the code with the documentation.</li>
<li><a href="http://github.com/bouk/gonerics" rel="nofollow">gonerics</a> - Idiomatic Generics in Go.</li>
<li><a href="https://github.com/cweill/gotests" rel="nofollow">gotests</a> - Generate Go tests from your source code.</li>
<li><a href="https://github.com/hexdigest/gounit" rel="nofollow">gounit</a> - Generate Go tests using your own templates.</li>
<li><a href="https://github.com/DylanMeeus/hasgo" rel="nofollow">hasgo</a> - Generate Haskell inspired functions for your slices.</li>
<li><a href="https://github.com/opennota/re2dfa" rel="nofollow">re2dfa</a> - Transform regular expressions into finite state machines and output Go source code.</li>
<li><a href="https://xuri.me/toml-to-go" rel="nofollow">TOML-to-Go</a> - Translates TOML into a Go type in the browser instantly.</li>
</ul>
<h2><a name="go-tools" class="anchor" href="#go-tools" rel="nofollow" aria-hidden="true"><span class="octicon octicon-link"></span></a>
Go Tools</h2>

<ul>
<li><a href="https://github.com/songgao/colorgo" rel="nofollow">colorgo</a> - Wrapper around <code>go</code> command for colorized <code>go build</code> output.</li>
<li><a href="https://github.com/KyleBanks/depth" rel="nofollow">depth</a> - Visualize dependency trees of any package by analyzing imports.</li>
<li><a href="https://getgb.io/" rel="nofollow">gb</a> - An easy to use project based build tool for the Go programming language.</li>
<li><a href="https://github.com/axelspringer/generator-go-lang" rel="nofollow">generator-go-lang</a> - A <a href="http://yeoman.io" rel="nofollow">Yeoman</a> generator to get new Go projects started.</li>
<li><a href="https://go-gilbert.github.io" rel="nofollow">gilbert</a> - Build system and task runner for Go projects.</li>
<li><a href="https://github.com/TrueFurby/go-callvis" rel="nofollow">go-callvis</a> - Visualize call graph of your Go program using dot format.</li>
<li><a href="https://github.com/skelterjohn/go-pkg-complete" rel="nofollow">go-pkg-complete</a> - Bash completion for go and wgo.</li>
<li><a href="https://github.com/go-swagger/go-swagger" rel="nofollow">go-swagger</a> - Swagger 2.0 implementation for go. Swagger is a simple yet powerful representation of your RESTful API.</li>
<li><a href="https://github.com/tylerwince/godbg" rel="nofollow">godbg</a> - Implementation of Rusts <code>dbg!</code> macro for quick and easy debugging during development.</li>
<li><a href="https://github.com/OctoLinker/browser-extension" rel="nofollow">OctoLinker</a> - Navigate through go files efficiently with the OctoLinker browser extension for GitHub.</li>
<li><a href="https://github.com/kyoh86/richgo" rel="nofollow">richgo</a> - Enrich <code>go test</code> outputs with text decorations.</li>
<li><a href="https://github.com/galeone/rts" rel="nofollow">rts</a> - RTS: response to struct. Generates Go structs from server responses.</li>
</ul>
<h2><a name="software-packages" class="anchor" href="#software-packages" rel="nofollow" aria-hidden="true"><span class="octicon octicon-link"></span></a>
Software Packages</h2>

<p><em>Software written in Go.</em></p>
<h3><a name="devops-tools" class="anchor" href="#devops-tools" rel="nofollow" aria-hidden="true"><span class="octicon octicon-link"></span></a>
DevOps Tools</h3>

<ul>
<li><a href="https://github.com/smira/aptly" rel="nofollow">aptly</a> - aptly is a Debian repository management tool.</li>
<li><a href="https://github.com/xuri/aurora" rel="nofollow">aurora</a> - Cross-platform web-based Beanstalkd queue server console.</li>
<li><a href="https://github.com/soniah/awsenv" rel="nofollow">awsenv</a> - Small binary that loads Amazon (AWS) environment variables for a profile.</li>
<li><a href="https://github.com/dave/blast" rel="nofollow">Blast</a> - A simple tool for API load testing and batch jobs.</li>
<li><a href="https://github.com/codesenberg/bombardier" rel="nofollow">bombardier</a> - Fast cross-platform HTTP benchmarking tool.</li>
<li><a href="https://github.com/bosun-monitor/bosun" rel="nofollow">bosun</a> - Time Series Alerting Framework.</li>
<li><a href="https://github.com/centerorbit/depcharge" rel="nofollow">DepCharge</a> - Helps orchestrating the execution of commands across the many dependencies in larger projects.</li>
<li><a href="https://github.com/ozankasikci/dockerfile-generator" rel="nofollow">Dockerfile-Generator</a> - A go library and an executable that produces valid Dockerfiles using various input channels.</li>
<li><a href="https://github.com/liudng/dogo" rel="nofollow">dogo</a> - Monitoring changes in the source file and automatically compile and run (restart).</li>
<li><a href="https://github.com/appleboy/drone-jenkins" rel="nofollow">drone-jenkins</a> - Trigger downstream Jenkins jobs using a binary, docker or Drone CI.</li>
<li><a href="https://github.com/appleboy/drone-scp" rel="nofollow">drone-scp</a> - Copy files and artifacts via SSH using a binary, docker or Drone CI.</li>
<li><a href="https://github.com/chrismckenzie/dropship" rel="nofollow">Dropship</a> - Tool for deploying code via cdn.</li>
<li><a href="https://github.com/appleboy/easyssh-proxy" rel="nofollow">easyssh-proxy</a> - Golang package for easy remote execution through SSH and SCP downloading via <code>ProxyCommand</code>.</li>
<li><a href="https://github.com/mkchoi212/fac" rel="nofollow">fac</a> - Command-line user interface to fix git merge conflicts.</li>
<li><a href="https://github.com/gaia-pipeline/gaia" rel="nofollow">gaia</a> - Build powerful pipelines in any programming language.</li>
<li><a href="https://github.com/go-gitea/gitea" rel="nofollow">Gitea</a> - Fork of Gogs, entirely community driven.</li>
<li><a href="https://git.jonasfranz.software/JonasFranzDEV/gitea-github-migrator" rel="nofollow">gitea-github-migrator</a> - Migrate all your GitHub repositories, issues, milestones and labels to your Gitea instance.</li>
<li><a href="https://github.com/go-furnace/go-furnace" rel="nofollow">go-furnace</a> - Hosting solution written in Go. Deploy your Application with ease on AWS, GCP or DigitalOcean.</li>
<li><a href="https://github.com/sanbornm/go-selfupdate" rel="nofollow">go-selfupdate</a> - Enable your Go applications to self update.</li>
<li><a href="https://github.com/cryptojuice/gobrew" rel="nofollow">gobrew</a> - gobrew lets you easily switch between multiple versions of go.</li>
<li><a href="https://github.com/sirnewton01/godbg" rel="nofollow">godbg</a> - Web-based gdb front-end application.</li>
<li><a href="https://gogs.io/" rel="nofollow">Gogs</a> - A Self Hosted Git Service in the Go Programming Language.</li>
<li><a href="https://github.com/inconshreveable/gonative" rel="nofollow">gonative</a> - Tool which creates a build of Go that can cross compile to all platforms while still using the Cgo-enabled versions of the stdlib packages.</li>
<li><a href="https://github.com/ahmetalpbalkan/govvv" rel="nofollow">govvv</a> - “go build” wrapper to easily add version information into Go binaries.</li>
<li><a href="https://github.com/mitchellh/gox" rel="nofollow">gox</a> - Dead simple, no frills Go cross compile tool.</li>
<li><a href="https://github.com/laher/goxc" rel="nofollow">goxc</a> - build tool for Go, with a focus on cross-compiling and packaging.</li>
<li><a href="https://github.com/yaronsumel/grapes" rel="nofollow">grapes</a> - Lightweight tool designed to distribute commands over ssh with ease.</li>
<li><a href="https://github.com/moovweb/gvm" rel="nofollow">GVM</a> - GVM provides an interface to manage Go versions.</li>
<li><a href="https://github.com/rakyll/hey" rel="nofollow">Hey</a> - Hey is a tiny program that sends some load to a web application.</li>
<li><a href="https://github.com/ajvb/kala" rel="nofollow">kala</a> - Simplistic, modern, and performant job scheduler.</li>
<li><a href="https://github.com/cswank/kcli" rel="nofollow">kcli</a> - Command line tool for inspecting kafka topics/partitions/messages.</li>
<li><a href="https://github.com/kubernetes/kubernetes" rel="nofollow">kubernetes</a> - Container Cluster Manager from Google.</li>
<li><a href="https://github.com/ivanilves/lstags" rel="nofollow">lstags</a> - Tool and API to sync Docker images across different registries.</li>
<li><a href="https://github.com/timdp/lwc" rel="nofollow">lwc</a> - A live-updating version of the UNIX wc command.</li>
<li><a href="https://github.com/xwjdsh/manssh" rel="nofollow">manssh</a> - manssh is a command line tool for managing your ssh alias config easily.</li>
<li><a href="https://github.com/moby/moby" rel="nofollow">Moby</a> - Collaborative project for the container ecosystem to assemble container-based systems.</li>
<li><a href="https://github.com/emicklei/mora" rel="nofollow">Mora</a> - REST server for accessing MongoDB documents and meta data.</li>
<li><a href="https://github.com/ostrost/ostent" rel="nofollow">ostent</a> - collects and displays system metrics and optionally relays to Graphite and/or InfluxDB.</li>
<li><a href="https://github.com/mitchellh/packer" rel="nofollow">Packer</a> - Packer is a tool for creating identical machine images for multiple platforms from a single source configuration.</li>
<li><a href="https://github.com/bengadbois/pewpew" rel="nofollow">Pewpew</a> - Flexible HTTP command line stress tester.</li>
<li><a href="https://github.com/pomerium/pomerium" rel="nofollow">Pomerium</a> - Pomerium is an identity-aware access proxy.</li>
<li><a href="https://github.com/alouche/rodent" rel="nofollow">Rodent</a> - Rodent helps you manage Go versions, projects and track dependencies.</li>
<li><a href="https://github.com/rlmcpherson/s3gof3r" rel="nofollow">s3gof3r</a> - Small utility/library optimized for high speed transfer of large objects into and out of Amazon S3.</li>
<li><a href="https://github.com/scaleway/scaleway-cli" rel="nofollow">Scaleway-cli</a> - Manage BareMetal Servers from Command Line (as easily as with Docker).</li>
<li><a href="https://github.com/bitfield/script" rel="nofollow">script</a> - Making it easy to write shell-like scripts in Go for DevOps and system administration tasks.</li>
<li><a href="https://github.com/ChristopherRabotin/sg" rel="nofollow">sg</a> - Benchmarks a set of HTTP endpoints (like ab), with possibility to use the response code and data between each call for specific server stress based on its previous response.</li>
<li><a href="https://github.com/TimothyYe/skm" rel="nofollow">skm</a> - SKM is a simple and powerful SSH Keys Manager, it helps you to manage your multiple SSH keys easily!</li>
<li><a href="https://github.com/sanathp/statusok" rel="nofollow">StatusOK</a> - Monitor your Website and REST APIs.Get Notified through Slack, E-mail when your server is down or response time is more than expected.</li>
<li><a href="https://github.com/containous/traefik" rel="nofollow">traefik</a> - Reverse proxy and load balancer with support for multiple backends.</li>
<li><a href="https://github.com/tsenart/vegeta" rel="nofollow">Vegeta</a> - HTTP load testing tool and library. It&#39;s over 9000!</li>
<li><a href="https://github.com/adnanh/webhook" rel="nofollow">webhook</a> - Tool which allows user to create HTTP endpoints (hooks) that execute commands on the server.</li>
<li><a href="https://wide.b3log.org/login" rel="nofollow">Wide</a> - Web-based IDE for Teams using Golang.</li>
<li><a href="https://github.com/masterzen/winrm-cli" rel="nofollow">winrm-cli</a> - Cli tool to remotely execute commands on Windows machines.</li>
</ul>
<h3><a name="other-software" class="anchor" href="#other-software" rel="nofollow" aria-hidden="true"><span class="octicon octicon-link"></span></a>
Other Software</h3>

<ul>
<li><a href="https://github.com/crufter/borg" rel="nofollow">borg</a> - Terminal based search engine for bash snippets.</li>
<li><a href="https://github.com/tejo/boxed" rel="nofollow">boxed</a> - Dropbox based blog engine.</li>
<li><a href="https://github.com/rafael-santiago/cherry" rel="nofollow">Cherry</a> - Tiny webchat server in Go.</li>
<li><a href="https://github.com/gocircuit/circuit" rel="nofollow">Circuit</a> - Circuit is a programmable platform-as-a-service (PaaS) and/or Infrastructure-as-a-Service (IaaS), for management, discovery, synchronization and orchestration of services and hosts comprising cloud applications.</li>
<li><a href="https://github.com/tylertreat/Comcast" rel="nofollow">Comcast</a> - Simulate bad network connections.</li>
<li><a href="https://github.com/kelseyhightower/confd" rel="nofollow">confd</a> - Manage local application configuration files using templates and data from etcd or consul.</li>
<li><a href="https://github.com/schollz/croc" rel="nofollow">croc</a> - Easily and securely send files or folders from one computer to another.</li>
<li><a href="https://github.com/skibish/ddns" rel="nofollow">DDNS</a> - Personal DDNS client with Digital Ocean Networking DNS as backend.</li>
<li><a href="http://www.docker.com/" rel="nofollow">Docker</a> - Open platform for distributed applications for developers and sysadmins.</li>
<li><a href="https://github.com/documize/community" rel="nofollow">Documize</a> - Modern wiki software that integrates data from SaaS tools.</li>
<li><a href="https://github.com/odeke-em/drive" rel="nofollow">drive</a> - Google Drive client for the commandline.</li>
<li><a href="https://github.com/gilbertchen/duplicacy" rel="nofollow">Duplicacy</a> - A cross-platform network and cloud backup tool based on the idea of lock-free deduplication.</li>
<li><a href="https://github.com/Antonito/gfile" rel="nofollow">gfile</a> - Securely transfer files between two computers, without any third party, over WebRTC.</li>
<li><a href="https://github.com/shurcooL/Go-Package-Store" rel="nofollow">Go Package Store</a> - App that displays updates for the Go packages in your GOPATH.</li>
<li><a href="https://github.com/Sioro-Neoku/go-peerflix" rel="nofollow">go-peerflix</a> - Video streaming torrent client.</li>
<li><a href="https://github.com/Humpheh/goboy" rel="nofollow">GoBoy</a> - Nintendo Game Boy Color emulator written in Go.</li>
<li><a href="https://github.com/goccmack/gocc" rel="nofollow">gocc</a> - Gocc is a compiler kit for Go written in Go.</li>
<li><a href="https://github.com/timothyye/godns" rel="nofollow">GoDNS</a> - A dynamic DNS client tool, supports DNSPod &amp; HE.net, written in Go.</li>
<li><a href="https://github.com/diankong/GoDocTooltip" rel="nofollow">GoDocTooltip</a> - Chrome extension for Go Doc sites, which shows function description as tooltip at function list.</li>
<li><a href="https://jetbrains.com/go" rel="nofollow">GoLand</a> - Full featured cross-platform Go IDE.</li>
<li><a href="https://github.com/buger/gor" rel="nofollow">Gor</a> - Http traffic replication tool, for replaying traffic from production to stage/dev environments in real-time.</li>
<li><a href="http://gohugo.io/" rel="nofollow">hugo</a> - Fast and Modern Static Website Engine.</li>
<li><a href="https://github.com/thestrukture/ide" rel="nofollow">ide</a> - Browser accessible IDE. Designed for Go with Go.</li>
<li><a href="https://github.com/dimiro1/ipe" rel="nofollow">ipe</a> - Open source Pusher server implementation compatible with Pusher client libraries written in GO.</li>
<li><a href="https://github.com/assafmo/joincap" rel="nofollow">joincap</a> - Command-line utility for merging multiple pcap files together.</li>
<li><a href="https://jujucharms.com/" rel="nofollow">Juju</a> - Cloud-agnostic service deployment and orchestration - supports EC2, Azure, Openstack, MAAS and more.</li>
<li><a href="https://github.com/jeffail/leaps" rel="nofollow">Leaps</a> - Pair programming service using Operational Transforms.</li>
<li><a href="https://github.com/yunabe/lgo" rel="nofollow">lgo</a> - Interactive Go programming with Jupyter. It supports code completion, code inspection and 100% Go compatibility.</li>
<li><a href="http://limetext.org/" rel="nofollow">limetext</a> - Lime Text is a powerful and elegant text editor primarily developed in Go that aims to be a Free and open-source software successor to Sublime Text.</li>
<li><a href="https://github.com/visualfc/liteide" rel="nofollow">LiteIDE</a> - LiteIDE is a simple, open source, cross-platform Go IDE.</li>
<li><a href="https://github.com/quii/mockingjay-server" rel="nofollow">mockingjay</a> - Fake HTTP servers and consumer driven contracts from one configuration file. You can also make the server randomly misbehave to help do more realistic performance tests.</li>
<li><a href="https://github.com/mehrdadrad/mylg" rel="nofollow">myLG</a> - Command Line Network Diagnostic tool written in Go.</li>
<li><a href="https://github.com/unix4fun/naclpipe" rel="nofollow">naclpipe</a> - Simple NaCL EC25519 based crypto pipe tool written in Go.</li>
<li><a href="https://github.com/fogleman/nes" rel="nofollow">nes</a> - Nintendo Entertainment System (NES) emulator written in Go.</li>
<li><a href="https://github.com/noraesae/orange-cat" rel="nofollow">orange-cat</a> - Markdown previewer written in Go.</li>
<li><a href="https://github.com/gulien/orbit" rel="nofollow">Orbit</a> - A simple tool for running commands and generating files from templates.</li>
<li><a href="https://github.com/pointlander/peg" rel="nofollow">peg</a> - Peg, Parsing Expression Grammar, is an implementation of a Packrat parser generator.</li>
<li><a href="https://github.com/b3log/pipe" rel="nofollow">Pipe</a> - A small and beautiful blogging platform.</li>
<li><a href="https://github.com/restic/restic" rel="nofollow">restic</a> - De-duplicating backup program.</li>
<li><a href="https://github.com/boyter/scc" rel="nofollow">scc</a> - Sloc Cloc and Code, a very fast accurate code counter with complexity calculations and COCOMO estimates.</li>
<li><a href="https://github.com/chrislusf/seaweedfs" rel="nofollow">Seaweed File System</a> - Fast, Simple and Scalable Distributed File System with O(1) disk seek.</li>
<li><a href="https://github.com/msoap/shell2http" rel="nofollow">shell2http</a> - Executing shell commands via http server (for prototyping or remote control).</li>
<li><a href="https://github.com/intelsdi-x/snap" rel="nofollow">snap</a> - Powerful telemetry framework.</li>
<li><a href="https://github.com/lucasgomide/snitch" rel="nofollow">Snitch</a> - Simple way to notify your team and many tools when someone has deployed any application via Tsuru.</li>
<li><a href="https://github.com/pressly/sup" rel="nofollow">Stack Up</a> - Stack Up, a super simple deployment tool - just Unix - think of it like &#39;make&#39; for a network of servers.</li>
<li><a href="https://syncthing.net/" rel="nofollow">syncthing</a> - Open, decentralized file synchronization tool and protocol.</li>
<li><a href="https://github.com/crazcalm/term-quiz" rel="nofollow">term-quiz</a> - Quizzes for your terminal.</li>
<li><a href="https://github.com/shopify/toxiproxy" rel="nofollow">toxiproxy</a> - Proxy to simulate network and system conditions for automated tests.</li>
<li><a href="https://tsuru.io/" rel="nofollow">tsuru</a> - Extensible and open source Platform as a Service software.</li>
<li><a href="https://github.com/VerizonDigital/vflow" rel="nofollow">vFlow</a> - High-performance, scalable and reliable IPFIX, sFlow and Netflow collector.</li>
<li><a href="https://github.com/wellington/wellington" rel="nofollow">wellington</a> - Sass project management tool, extends the language with sprite functions (like Compass).</li>
</ul>
<h1><a name="resources" class="anchor" href="#resources" rel="nofollow" aria-hidden="true"><span class="octicon octicon-link"></span></a>
Resources</h1>

<p><em>Where to discover new Go libraries.</em></p>
<h2><a name="benchmarks" class="anchor" href="#benchmarks" rel="nofollow" aria-hidden="true"><span class="octicon octicon-link"></span></a>
Benchmarks</h2>

<ul>
<li><a href="https://github.com/davecheney/autobench" rel="nofollow">autobench</a> - Framework to compare the performance between different Go versions.</li>
<li><a href="https://github.com/mrLSD/go-benchmark-app" rel="nofollow">go-benchmark-app</a> - Powerful HTTP-benchmark tool mixed with Аb, Wrk, Siege tools. Gathering statistics and various parameters for benchmarks and comparison results.</li>
<li><a href="https://github.com/tylertreat/go-benchmarks" rel="nofollow">go-benchmarks</a> - Few miscellaneous Go microbenchmarks. Compare some language features to alternative approaches.</li>
<li><a href="https://github.com/julienschmidt/go-http-routing-benchmark" rel="nofollow">go-http-routing-benchmark</a> - Go HTTP request router benchmark and comparison.</li>
<li><a href="https://github.com/smallnest/go-web-framework-benchmark" rel="nofollow">go-web-framework-benchmark</a> - Go web framework benchmark.</li>
<li><a href="https://github.com/alecthomas/go_serialization_benchmarks" rel="nofollow">go_serialization_benchmarks</a> - Benchmarks of Go serialization methods.</li>
<li><a href="https://github.com/PuerkitoBio/gocostmodel" rel="nofollow">gocostmodel</a> - Benchmarks of common basic operations for the Go language.</li>
<li><a href="https://github.com/tyler-smith/golang-sql-benchmark" rel="nofollow">golang-sql-benchmark</a> - Collection of benchmarks for popular Go database/SQL utilities.</li>
<li><a href="https://github.com/feyeleanor/GoSpeed" rel="nofollow">gospeed</a> - Go micro-benchmarks for calculating the speed of language constructs.</li>
<li><a href="https://github.com/jimrobinson/kvbench" rel="nofollow">kvbench</a> - Key/Value database benchmark.</li>
<li><a href="https://github.com/atemerev/skynet" rel="nofollow">skynet</a> - Skynet 1M threads microbenchmark.</li>
<li><a href="https://github.com/fawick/speedtest-resize" rel="nofollow">speedtest-resize</a> - Compare various Image resize algorithms for the Go language.</li>
</ul>
<h2><a name="conferences" class="anchor" href="#conferences" rel="nofollow" aria-hidden="true"><span class="octicon octicon-link"></span></a>
Conferences</h2>

<ul>
<li><a href="http://www.capitalgolang.com" rel="nofollow">Capital Go</a> - Washington, D.C., USA.</li>
<li><a href="http://www.dotgo.eu" rel="nofollow">dotGo</a> - Paris, France.</li>
<li><a href="http://gocon.connpass.com/" rel="nofollow">GoCon</a> - Tokyo, Japan.</li>
<li><a href="https://www.godays.io/" rel="nofollow">GoDays</a> - Berlin, Germany.</li>
<li><a href="http://golab.io/" rel="nofollow">GoLab</a> - Florence, Italy.</li>
<li><a href="http://golanguk.com/" rel="nofollow">GolangUK</a> - London, UK.</li>
<li><a href="http://gopherchina.org" rel="nofollow">GopherChina</a> - Shanghai, China.</li>
<li><a href="http://www.gophercon.com/" rel="nofollow">GopherCon</a> - Denver, USA.</li>
<li><a href="https://gophercon.com.au/" rel="nofollow">GopherCon Australia</a> - Sydney, Australia.</li>
<li><a href="https://gopherconbr.org" rel="nofollow">GopherCon Brazil</a> - Florianópolis, BR.</li>
<li><a href="https://gophercon.is/" rel="nofollow">GopherCon Europe</a> - Berlin, Germany.</li>
<li><a href="https://www.gophercon.in/" rel="nofollow">GopherCon India</a> - Pune, India.</li>
<li><a href="https://www.gophercon.org.il/" rel="nofollow">GopherCon Israel</a> - Tel Aviv, Israel.</li>
<li><a href="https://www.gophercon-russia.ru" rel="nofollow">GopherCon Russia</a> - Moscow, Russia.</li>
<li><a href="https://gophercon.sg" rel="nofollow">GopherCon Singapore</a> - Mapletree Business City, Singapore.</li>
<li><a href="https://gophercon.vn/" rel="nofollow">GopherCon Vietnam</a> - Ho Chi Minh City, Vietnam.</li>
<li><a href="http://gothamgo.com/" rel="nofollow">GothamGo</a> - New York City, USA.</li>
<li><a href="https://goway.io/" rel="nofollow">GoWayFest</a> - Minsk, Belarus.</li>
</ul>
<h2><a name="e-books" class="anchor" href="#e-books" rel="nofollow" aria-hidden="true"><span class="octicon octicon-link"></span></a>
E-Books</h2>

<ul>
<li><a href="https://leanpub.com/GoNotebook/read" rel="nofollow">A Go Developer&#39;s Notebook</a></li>
<li><a href="http://www.golang-book.com/" rel="nofollow">An Introduction to Programming in Go</a></li>
<li><a href="https://www.gitbook.com/book/astaxie/build-web-application-with-golang/details" rel="nofollow">Build Web Application with Golang</a></li>
<li><a href="https://www.gitbook.com/book/codegangsta/building-web-apps-with-go/details" rel="nofollow">Building Web Apps With Go</a></li>
<li><a href="https://go101.org" rel="nofollow">Go 101</a> - A book focusing on Go syntax/semantics and all kinds of details.</li>
<li><a href="http://golangbootcamp.com" rel="nofollow">Go Bootcamp</a></li>
<li><a href="https://github.com/thedevsir/gosuccinctly" rel="nofollow">Go Succinctly</a> - in Persian.</li>
<li><a href="https://github.com/dariubs/GoBooks" rel="nofollow">GoBooks</a> - A curated list of Go books.</li>
<li><a href="https://www.miek.nl/downloads/Go/Learning-Go-latest.pdf" rel="nofollow">Learning Go</a></li>
<li><a href="https://jan.newmarch.name/go/" rel="nofollow">Network Programming With Go</a></li>
<li><a href="http://www.gopl.io/" rel="nofollow">The Go Programming Language</a></li>
<li><a href="https://github.com/polaris1119/The-Golang-Standard-Library-by-Example" rel="nofollow">The Golang Standard Library by Example (Chinese)</a></li>
<li><a href="https://github.com/thewhitetulip/web-dev-golang-anti-textbook/" rel="nofollow">Web Application with Go the Anti-Textbook</a></li>
<li><a href="https://compilerbook.com" rel="nofollow">Writing A Compiler In Go</a></li>
<li><a href="https://interpreterbook.com" rel="nofollow">Writing An Interpreter In Go</a></li>
</ul>
<h2><a name="gophers" class="anchor" href="#gophers" rel="nofollow" aria-hidden="true"><span class="octicon octicon-link"></span></a>
Gophers</h2>

<ul>
<li><a href="https://github.com/MariaLetta/free-gophers-pack" rel="nofollow">Free Gophers Pack</a> - Gopher graphics pack by Maria Letta with illustrations and emotional characters in vector and raster.</li>
<li><a href="https://github.com/keygx/Go-gopher-Vector" rel="nofollow">Go-gopher-Vector</a> - Go gopher Vector Data [.ai, .svg].</li>
<li><a href="https://github.com/GolangUA/gopher-logos" rel="nofollow">gopher-logos</a> - adorable gopher logos.</li>
<li><a href="https://github.com/tenntenn/gopher-stickers" rel="nofollow">gopher-stickers</a></li>
<li><a href="https://github.com/golang-samples/gopher-vector" rel="nofollow">gopher-vector</a></li>
<li><a href="https://github.com/shalakhin/gophericons" rel="nofollow">gophericons</a></li>
<li><a href="https://github.com/matryer/gopherize.me" rel="nofollow">gopherize.me</a> - Gopherize yourself.</li>
<li><a href="https://github.com/ashleymcnamara/gophers" rel="nofollow">gophers</a> - Gopher artworks by Ashley McNamara.</li>
<li><a href="https://github.com/egonelbre/gophers" rel="nofollow">gophers</a> - Free gophers.</li>
<li><a href="https://github.com/rogeralsing/gophers" rel="nofollow">gophers</a> - random gopher graphics.</li>
<li><a href="https://github.com/sillecelik/go-gopher" rel="nofollow">gophers</a> - Gopher amigurumi toy pattern.</li>
</ul>
<h2><a name="meetups" class="anchor" href="#meetups" rel="nofollow" aria-hidden="true"><span class="octicon octicon-link"></span></a>
Meetups</h2>

<ul>
<li><a href="https://www.meetup.com/Basel-Go-Meetup/" rel="nofollow">Basel Go Meetup</a></li>
<li><a href="https://www.meetup.com/golang-users-berlin/" rel="nofollow">Berlin Golang</a></li>
<li><a href="https://www.meetup.com/Brisbane-Golang-Meetup/" rel="nofollow">Brisbane Gophers</a></li>
<li><a href="https://www.meetup.com/Canberra-Gophers/" rel="nofollow">Canberra Gophers</a></li>
<li><a href="https://www.meetup.com/golanguagenewyork/" rel="nofollow">Go Language NYC</a></li>
<li><a href="https://www.meetup.com/Go-London-User-Group/" rel="nofollow">Go London User Group</a></li>
<li><a href="https://www.meetup.com/go-toronto/" rel="nofollow">Go Toronto</a></li>
<li><a href="https://www.meetup.com/Go-Users-Group-Atlanta/" rel="nofollow">Go User Group Atlanta</a></li>
<li><a href="https://www.meetup.com/gobridge/" rel="nofollow">GoBridge, San Francisco, CA</a></li>
<li><a href="https://www.meetup.com/GoJakarta/" rel="nofollow">GoJakarta</a></li>
<li><a href="https://www.meetup.com/golang-amsterdam/" rel="nofollow">Golang Amsterdam</a></li>
<li><a href="https://www.meetup.com/Golang-Argentina/" rel="nofollow">Golang Argentina</a></li>
<li><a href="https://www.meetup.com/BaltimoreGolang/" rel="nofollow">Golang Baltimore, MD</a></li>
<li><a href="https://www.meetup.com/Golang-Bangalore/" rel="nofollow">Golang Bangalore</a></li>
<li><a href="https://www.meetup.com/go-belo-horizonte/" rel="nofollow">Golang Belo Horizonte - Brazil</a></li>
<li><a href="https://www.meetup.com/bostongo/" rel="nofollow">Golang Boston</a></li>
<li><a href="https://www.meetup.com/Golang-Bulgaria/" rel="nofollow">Golang Bulgaria</a></li>
<li><a href="https://www.meetup.com/Cardiff-Go-Meetup/" rel="nofollow">Golang Cardiff, UK</a></li>
<li><a href="https://www.meetup.com/Go-Cph/" rel="nofollow">Golang Copenhagen</a></li>
<li><a href="https://www.meetup.com/Golang-DC/" rel="nofollow">Golang DC, Arlington, VA</a></li>
<li><a href="https://www.meetup.com/golang-dorset/" rel="nofollow">Golang Dorset, UK</a></li>
<li><a href="https://www.meetup.com/Gurgaon-Go-Meetup/" rel="nofollow">Golang Gurgaon, India</a></li>
<li><a href="https://www.meetup.com/Go-User-Group-Hamburg/" rel="nofollow">Golang Hamburg - Germany</a></li>
<li><a href="https://www.meetup.com/Go-Israel/" rel="nofollow">Golang Israel</a></li>
<li><a href="https://www.meetup.com/Joinville-Go-Meetup/" rel="nofollow">Golang Joinville - Brazil</a></li>
<li><a href="https://www.meetup.com/GDG-Golang-Korea/" rel="nofollow">Golang Korea</a></li>
<li><a href="https://www.meetup.com/Golang-Peru/" rel="nofollow">Golang Lima - Peru</a></li>
<li><a href="https://www.meetup.com/Golang-Lyon/" rel="nofollow">Golang Lyon</a></li>
<li><a href="https://www.meetup.com/fr-FR/Golang-Marseille/" rel="nofollow">Golang Marseille</a></li>
<li><a href="https://www.meetup.com/golang-mel/" rel="nofollow">Golang Melbourne</a></li>
<li><a href="https://www.meetup.com/Golang-Mountain-View/" rel="nofollow">Golang Mountain View</a></li>
<li><a href="https://www.meetup.com/nycgolang/" rel="nofollow">Golang New York</a></li>
<li><a href="https://www.meetup.com/Golang-Paris/" rel="nofollow">Golang Paris</a></li>
<li><a href="https://www.meetup.com/Golang-Pune/" rel="nofollow">Golang Pune</a></li>
<li><a href="https://www.meetup.com/golangsg/" rel="nofollow">Golang Singapore</a></li>
<li><a href="https://www.meetup.com/Go-Stockholm/" rel="nofollow">Golang Stockholm</a></li>
<li><a href="https://www.meetup.com/golang-syd/" rel="nofollow">Golang Sydney, AU</a></li>
<li><a href="https://www.meetup.com/golangbr/" rel="nofollow">Golang São Paulo - Brazil</a></li>
<li><a href="https://www.meetup.com/golang-taipei-meetup/" rel="nofollow">Golang Taipei</a></li>
<li><a href="https://www.meetup.com/golangvan/" rel="nofollow">Golang Vancouver, BC</a></li>
<li><a href="https://www.meetup.com/GolangKazan/" rel="nofollow">Golang Казань</a></li>
<li><a href="https://www.meetup.com/Golang-Moscow/" rel="nofollow">Golang Москва</a></li>
<li><a href="https://www.meetup.com/Golang-Peter/" rel="nofollow">Golang Питер</a></li>
<li><a href="https://www.meetup.com/golangsf" rel="nofollow">GoSF - San Francisco, CA</a></li>
<li><a href="https://www.meetup.com/Istanbul-Golang/" rel="nofollow">Istanbul Golang</a></li>
<li><a href="https://www.meetup.com/golang/" rel="nofollow">Seattle Go Programmers</a></li>
<li><a href="https://www.meetup.com/uagolang/" rel="nofollow">Ukrainian Golang User Groups</a></li>
<li><a href="https://www.meetup.com/utahgophers/" rel="nofollow">Utah Go User Group</a></li>
<li><a href="https://www.meetup.com/Women-Who-Go/" rel="nofollow">Women Who Go - San Francisco, CA</a></li>
</ul>

<p>*Add the group of your city/country here (send <strong>PR</strong>)*</p>
<h2><a name="twitter" class="anchor" href="#twitter" rel="nofollow" aria-hidden="true"><span class="octicon octicon-link"></span></a>
Twitter</h2>

<ul>
<li><a href="https://twitter.com/golang" rel="nofollow">@golang</a></li>
<li><a href="https://twitter.com/golang_news" rel="nofollow">@golang_news</a></li>
<li><a href="https://twitter.com/golangch" rel="nofollow">@golangch</a></li>
<li><a href="https://twitter.com/golangflow" rel="nofollow">@golangflow</a></li>
<li><a href="https://twitter.com/golangweekly" rel="nofollow">@golangweekly</a></li>
</ul>
<h2><a name="websites" class="anchor" href="#websites" rel="nofollow" aria-hidden="true"><span class="octicon octicon-link"></span></a>
Websites</h2>

<ul>
<li><a href="https://go.libhunt.com" rel="nofollow">Awesome Go @LibHunt</a> - Your go-to Go Toolbox.</li>
<li><a href="https://github.com/lukasz-madon/awesome-remote-job" rel="nofollow">Awesome Remote Job</a> - Curated list of awesome remote jobs. A lot of them are looking for Go hackers.</li>
<li><a href="https://github.com/bayandin/awesome-awesomeness" rel="nofollow">awesome-awesomeness</a> - List of other amazingly awesome lists.</li>
<li><a href="https://www.codingame.com/" rel="nofollow">CodinGame</a> - Learn Go by solving interactive tasks using small games as practical examples.</li>
<li><a href="http://blog.golang.org" rel="nofollow">Go Blog</a> - The official Go blog.</li>
<li><a href="http://golang-challenge.org/" rel="nofollow">Go Challenge</a> - Learn Go by solving problems and getting feedback from Go experts.</li>
<li><a href="https://hashnode.com/n/go" rel="nofollow">Go Community on Hashnode</a> - Community of Gophers on Hashnode.</li>
<li><a href="https://forum.golangbridge.org" rel="nofollow">Go Forum</a> - Forum to discuss Go.</li>
<li><a href="https://www.goin5minutes.com/" rel="nofollow">Go In 5 Minutes</a> - 5 minute screencasts focused on getting one thing done.</li>
<li><a href="https://github.com/golang/go/wiki/Projects" rel="nofollow">Go Projects</a> - List of projects on the Go community wiki.</li>
<li><a href="https://goreportcard.com" rel="nofollow">Go Report Card</a> - A report card for your Go package.</li>
<li><a href="https://github.com/ninedraft/gocryforhelp" rel="nofollow">gocryforhelp</a> - Collection of Go projects that needs help. Good place to start your open-source way in Go.</li>
<li><a href="https://godoc.org/" rel="nofollow">godoc.org</a> - Documentation for open source Go packages.</li>
<li><a href="https://golangjob.xyz" rel="nofollow">Golang Developer Jobs</a> - Developer Jobs exclusivly for Golang related Roles.</li>
<li><a href="https://golangflow.io" rel="nofollow">Golang Flow</a> - Post Updates, News, Packages and more.</li>
<li><a href="https://golangnews.com" rel="nofollow">Golang News</a> - Links and news about Go programming.</li>
<li><a href="https://github.com/mholt/golang-graphics" rel="nofollow">golang-graphics</a> - Collection of Go images, graphics, and art.</li>
<li><a href="https://groups.google.com/forum/#!forum/golang-nuts" rel="nofollow">golang-nuts</a> - Go mailing list.</li>
<li><a href="https://plus.google.com/communities/114112804251407510571" rel="nofollow">Google Plus Community</a> - The Google+ community for #golang enthusiasts.</li>
<li><a href="https://invite.slack.golangbridge.org" rel="nofollow">Gopher Community Chat</a> - Join Our New Slack Community For Gophers (<a href="https://blog.gopheracademy.com/gophers-slack-community/" rel="nofollow">Understand how it came</a>).</li>
<li><a href="https://gophercises.com/" rel="nofollow">Gophercises</a> - Free coding exercises for budding gophers.</li>
<li><a href="https://gowalker.org" rel="nofollow">gowalker.org</a> - Go Project API documentation.</li>
<li><a href="https://m-zajac.github.io/json2go" rel="nofollow">json2go</a> - Advanced JSON to Go struct conversion - online tool.</li>
<li><a href="https://www.youtube.com/c/justforfunc" rel="nofollow">justforfunc</a> - Youtube channel dedicated to Go programming language tips and tricks, hosted by  Francesc Campoy <a href="https://twitter.com/francesc" rel="nofollow">@francesc</a>.</li>
<li><a href="https://madewithgolang.com/?ref=awesome-go" rel="nofollow">Made with Golang</a></li>
<li><a href="https://www.reddit.com/r/golang" rel="nofollow">r/Golang</a> - News about Go.</li>
<li><a href="https://studygolang.com" rel="nofollow">studygolang</a> - The community of studygolang in China.</li>
<li><a href="https://github.com/trending?l=go" rel="nofollow">Trending Go repositories on GitHub today</a> - Good place to find new Go libraries.</li>
<li><a href="https://tutorialedge.net/course/golang/" rel="nofollow">TutorialEdge - Golang</a></li>
</ul>
<h3><a name="tutorials" class="anchor" href="#tutorials" rel="nofollow" aria-hidden="true"><span class="octicon octicon-link"></span></a>
Tutorials</h3>

<ul>
<li><a href="http://devs.cloudimmunity.com/gotchas-and-common-mistakes-in-go-golang/" rel="nofollow">50 Shades of Go</a> - Traps, Gotchas, and Common Mistakes for New Golang Devs.</li>
<li><a href="https://snipcart.com/blog/golang-ecommerce-ponzu-cms-demo?utm_term=golang-ecommerce-ponzu-cms-demo" rel="nofollow">A Guide to Golang E-Commerce</a> - Building a Golang site for e-commerce (demo included).</li>
<li><a href="http://tour.golang.org/" rel="nofollow">A Tour of Go</a> - Interactive tour of Go.</li>
<li><a href="https://github.com/astaxie/build-web-application-with-golang" rel="nofollow">Build web application with Golang</a> - Golang ebook intro how to build a web app with golang.</li>
<li><a href="https://semaphoreci.com/community/tutorials/building-go-web-applications-and-microservices-using-gin" rel="nofollow">Building Go Web Applications and Microservices Using Gin</a> - Get familiar with Gin and find out how it can help you reduce boilerplate code and build a request handling pipeline.</li>
<li><a href="https://medium.com/@rocketlaunchr.cloud/caching-slow-database-queries-1085d308a0c9" rel="nofollow">Caching Slow Database Queries</a> - How to cache slow database queries.</li>
<li><a href="https://medium.com/@rocketlaunchr.cloud/canceling-mysql-in-go-827ed8f83b30" rel="nofollow">Canceling MySQL</a> - How to cancel MySQL queries.</li>
<li><a href="https://github.com/miguelmota/ethereum-development-with-go-book" rel="nofollow">Ethereum Development with Go</a> - A little e-book on Ethereum Development with Go.</li>
<li><a href="http://gameswithgo.org/" rel="nofollow">Games With Go</a> - A video series teaching programming and game development.</li>
<li><a href="https://gobyexample.com/" rel="nofollow">Go By Example</a> - Hands-on introduction to Go using annotated example programs.</li>
<li><a href="https://github.com/a8m/go-lang-cheat-sheet" rel="nofollow">Go Cheat Sheet</a> - Go&#39;s reference card.</li>
<li><a href="http://go-database-sql.org/" rel="nofollow">Go database/sql tutorial</a> - Introduction to database/sql.</li>
<li><a href="https://itunes.apple.com/us/app/go-playground/id1437518275?ls=1&mt=8" rel="nofollow">Go Playground for iOS</a> - Interactively edit &amp; play Go snippets on your mobile device.</li>
<li><a href="https://tutorialedge.net/golang/go-webassembly-tutorial/" rel="nofollow">Go WebAssembly Tutorial - Building a Simple Calculator</a></li>
<li><a href="https://github.com/tmrts/go-patterns" rel="nofollow">go-patterns</a> - Curated list of Go design patterns, recipes and idioms.</li>
<li><a href="https://github.com/miguelmota/golang-for-nodejs-developers" rel="nofollow">Golang for Node.js Developers</a> - Examples of Golang compared to Node.js for learning.</li>
<li><a href="https://golangbot.com/learn-golang-series/" rel="nofollow">Golangbot</a> - Tutorials to get started with programming in Go.</li>
<li><a href="https://golangcode.com/" rel="nofollow">GolangCode</a> - Collection of code snippets and tutorials to help tackle every day issues.</li>
<li><a href="https://hackr.io/tutorials/learn-golang" rel="nofollow">Hackr.io</a> - Learn Go from the best online golang tutorials submitted &amp; voted by the golang programming community.</li>
<li><a href="https://semaphoreci.com/community/tutorials/how-to-use-godog-for-behavior-driven-development-in-go" rel="nofollow">How to Use Godog for Behavior-driven Development in Go</a> - Get started with Godog — a Behavior-driven development framework for building and testing Go applications.</li>
<li><a href="https://github.com/quii/learn-go-with-tests" rel="nofollow">Learn Go with TDD</a> - Learn Go with test-driven development.</li>
<li><a href="https://milapneupane.com.np/2019/07/06/learning-golang-from-zero-to-hero/" rel="nofollow">Learning Golang - From zero to hero</a> - Getting started with golang for beginner.</li>
<li><a href="https://www.youtube.com/packagemain" rel="nofollow">package main</a> - YouTube channel about Programming in Go.</li>
<li><a href="https://www.coursera.org/specializations/google-golang" rel="nofollow">Programming with Google Go</a> - Coursera Specialization to learn about Go from scratch.</li>
<li><a href="https://medium.com/@martinolsansky/webassembly-with-golang-is-fun-b243c0e34f02" rel="nofollow">The world’s easiest introduction to WebAssembly with Golang</a></li>
<li><a href="https://github.com/mkaz/working-with-go" rel="nofollow">Working with Go</a> - Intro to go for experienced programmers.</li>
<li><a href="http://yourbasic.org/golang" rel="nofollow">Your basic Go</a> - Huge collection of tutorials and how to&#39;s.</li>
</ul>

	</div>

	<script src="/assets/jquery-custom.min.js"></script>
	<script src="/assets/marked.js"></script>
	<script>
	  (function(i,s,o,g,r,a,m){i['GoogleAnalyticsObject']=r;i[r]=i[r]||function(){
	  (i[r].q=i[r].q||[]).push(arguments)},i[r].l=1*new Date();a=s.createElement(o),
	  m=s.getElementsByTagName(o)[0];a.async=1;a.src=g;m.parentNode.insertBefore(a,m)
	  })(window,document,'script','https://www.google-analytics.com/analytics.js','ga');

	  ga('create', 'UA-85465107-1', 'auto');
	  ga('send', 'pageview');
	</script>
</body>
</html>

