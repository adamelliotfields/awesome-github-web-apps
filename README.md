# Awesome Web Applications [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
> :octocat: _A curated collection of web applications with source code available on GitHub._

The purpose of this list is to focus on the architecture, technologies, and design used to build
some truly _awesome_ apps available on GitHub.

Use it as a source of inspiration and knowledge.

## Contributing
To be included in the list, each application should meet the following criteria:
  1. **Must have source code on GitHub.** Furthermore, all of the source code required to run the app should be public.
  2. **Must be able to run locally on a Linux operating system.** Docker/Compose files would be nice to have. Having external dependencies (i.e., API keys, Firebase) is fine as long as they have a free tier.
  3. **Must be a functioning application.** It should not be a starter-kit.
  4. **Must have acceptable documentation.** Should contain information about the application along with installation instructions. A demo or screenshots are certainly nice to have. Documentation and demo apps should be in English.
  5. **Must have at least 100 stars.** Exceptions can be made for awesome apps of all star counts, though.

Ideally, the focus should be on quality over quantity.

Simply open an issue explaining why you want to add the app and we can discuss if a pull request
makes sense :smile:

## Tags
  - `abandoned` - All development has stopped.
  - `inactive` - Limited development activity.
  - `mobile` - Includes native mobile code (e.g., React Native, Flutter).
  - `desktop` - Includes desktop code (e.g., Electron, NW.js).
  - `static` - Can be deployed to any static web server (e.g., GitHub Pages, Surge).
  - `docker` - Includes a Dockerfile and/or Docker Compose configuration.

## Programming Languages
  - [C#](#c)
  - [Dart](#dart)
  - [Elixir](#elixir)
  - [Go](#go)
  - [Java](#java)
  - [JavaScript](#javascript)
  - [PHP](#php)
  - [Python](#python)
  - [Ruby](#ruby)

## C&#35;

#### [reactivetradercloud](https://github.com/AdaptiveConsulting/ReactiveTraderCloud) ([demo](https://web-demo.adaptivecluster.com/)) `docker`
A .NET application demonstrating a real-time foreign exchange trading platform. It is written using
stream-based, reactive programming using the Event Source database. The frontend is a React
application. Deployment instructions include Docker as well as Kubernetes.

## Dart

#### [inkino](https://github.com/roughike/inKino) ([demo](https://inkino.app)) `mobile`
A multi-platform Dart application for browsing movies and showtimes at Finnkino (Finland) cinemas.
It emphasizes maximum code reuse between the mobile and web applications. The native mobile apps are
built with Flutter, and the web app uses AngularDart. Movie metadata is pulled from the TMDb API.

## Elixir

#### [mogo-chat](https://github.com/HashNuke/mogo-chat) `abandoned`
A Phoenix team chat application. Includes an Ember frontend written in Coffeescript, and uses a
PostgreSQL database on the backend.

## Go

#### [filebrowser](https://github.com/filebrowser/filebrowser) `docker` `inactive`
A Go application for managing files on a server. Supports multiple users and each user can have
their own folder. Users can upload, delete, rename, preview, and edit files. The client is a Vue
application and text files can be edited using CodeMirror. Can be deployed as a single Docker image
or as a Caddy plugin.

#### [gitea](https://github.com/go-gitea/gitea) ([demo](https://try.gitea.io)) `docker`
A Go application originally forked from Gogs providing a self-hosted Git service. Built with the
Macaron web framework. Supports MySQL, PostgreSQL, MSSQL, and SQLite databases via the XORM ORM.
Authentication sources include LDAP, PAM, SMTP, and FreeIPA. Also has support for web hooks, and can
be backed up to a zip file. Deployment via source, binary, or Docker.

#### [gogs](https://github.com/gogs/gogs) ([demo](https://try.gogs.io)) `docker`
A self-hosted Git service written in Go with a GitHub-like interface using jQuery and Semantic UI.
Built with the Macaron web framework. Supports MySQL, PostgreSQL, MSSQL, and SQLite databases via
the XORM ORM. Authentication sources include LDAP, PAM, and SMTP. Has support for web hooks.
Deployment via source, binary, or Docker.

#### [gotty](https://github.com/yudai/gotty)
A single Go binary for displaying terminal output in the browser.

#### [mattermost](https://github.com/mattermost/mattermost-server) ([demo](https://demo.mattermost.com)) `mobile` `desktop` `docker`
A Go team chat application providing a Slack-like experience. Includes a React web interface, as
well as React Native mobile applications and an Electron desktop application. Can use either MySQL
or PostgreSQL databases. Deployment via binary or Docker.

#### [minio](https://github.com/minio/minio) `docker`
A Go file storage application with an AWS S3 compatible API. Includes a React web interface as well
as a terminal CLI. Deployment via binary or Docker.

## Java

#### [commafeed](https://github.com/Athou/commafeed) ([demo](https://www.commafeed.com/#/feeds/view/category/all)) `inactive`
A Dropwizard RSS reader with an AngularJS frontend. Supports MySQL, PostgreSQL, or MSSQL databases.

#### [hygieia](https://github.com/Hygieia/Hygieia) `docker`
CapitalOne's DevOps dashboard application written with Spring. It can monitor sprint progress,
commits, builds, and server status. Uses MongoDB on the backend. Deployment via source or Docker
Compose.

#### [gitbucket](https://github.com/gitbucket/gitbucket) ([demo](https://gitbucket.herokuapp.com)) `docker`
A Git platform written in Scala using the Scalatra microframework. It uses Java's H2 database by
default, but can be configured to use MySQL or PostgreSQL. Slick is used for data access. LDAP
integration is available. Deployment via servlet container or Docker.

#### [profile-summary-for-github](https://github.com/tipsy/profile-summary-for-github) ([demo](https://profile-summary-for-github.com)) `docker`
A Kotlin application for generating a dashboard based on your GitHub activity. It uses the Javalin
microframework on the backend. Deployment via source or Docker.

#### [sourcerer](https://github.com/sourcerer-io/sourcerer-app) ([demo](https://sourcerer.io/start)) `docker`
A Kotlin application for generating a visual profile based on your GitHub activity. Goes beyond the
GitHub API by inspecting your code to determine your coding style, technologies and libraries used,
and statistics about your coding activity. Deployment via a Bash script or Docker.

#### [streama](https://github.com/streamaserver/streama) `docker`
A Grails application for streaming a video collection inspired by Netflix. Uses a MySQL database and
Hibernate on the backend. The frontend is an AngularJS application. Deployment via war file or
Docker.

## JavaScript

#### [algorithm-visualizer](https://github.com/algorithm-visualizer/algorithm-visualizer) ([demo](http://algorithm-visualizer.org))
An Express application with a React frontend for visualizing algorithms in JavaScript. It includes a
list of popular algorithms, and the user can edit them or create new algorithms.

#### [bookmarkly](https://github.com/dangrossman/Bookmarkly) `abandoned`
An Express application for storing bookmarks. MySQL and Redis are used on the backend, and the
frontend is written with Backbone.

#### [countly](https://github.com/Countly/countly-server) `docker`
An Express application that provides a dashboard and REST API for visualizing analytics gathered
from users of your web application. A JavaScript SDK integrated into your app provides the data.
Uses MongoDB on the backend. Can be deployed via a Bash script or Docker.

#### [crate](https://github.com/atulmy/crate) `mobile`
A JavaScript clone of StitchFix/Krate written with Express and isomorphic React/Redux. Includes a
GraphQL API backed by a MySQL database. Uses JSON Web Tokens for authentication. Also includes a
React Native version for building native mobile apps.

#### [cyberchef](https://github.com/gchq/CyberChef) ([demo](https://gchq.github.io/CyberChef)) `static`
A JavaScript application providing encoding, encryption, compression, and other cyber operations in
a single browser window. Built with jQuery and Bootstrap Material.

#### [droppy](https://github.com/silverwind/droppy) ([demo](https://droppy.silverwind.io)) `docker`
A Node.js file storage application. Users can view and edit files in the browser. Deployment via
source or Docker.

#### [habitica](https://github.com/HabitRPG/habitica) `docker`
A JavaScript application for gamifying your habits. The backend is Express and MongoDB, while the
frontend is a Vue application. Deployment via source, Docker, or Kubernetes on AWS.

#### [hackernews-react-graphql](https://github.com/clintonwoo/hackernews-react-graphql) ([demo](http://www.hnclone.win)) `docker`
A React application using Next, Redux, GraphQL (Apollo), and Express. Aims to match the styling of
Hacker News. Deployment via source or Docker.

#### [hotel](https://github.com/typicode/hotel)
An Express application for managing local web applications. Provides a browser dashboard for
starting-up/shutting-down services, displaying their output, and assigning them a `.localhost`
domain.

#### [jspaint](https://github.com/1j01/jspaint) ([demo](https://jspaint.app)) `static`
A clone of MS Paint using jQuery and HTML5 Canvas.

#### [laverna](https://github.com/Laverna/laverna) ([demo](https://laverna.cc)) `static` `inactive`
A JavaScript note-taking application written with Marionette using localStorage and indexedDB for
storage. Can syncronize with Dropbox for persistence.

#### [lets-chat](https://github.com/sdelements/lets-chat) `docker` `inactive`
An Express chat application featuring multiple rooms, private chats, image embeds, Giphy
integration, code snippets, file uploads, and a REST API. Uses MongoDB for persistence and files can
be stored on the local filesystem, AWS S3, or Azure Blob. Deployment via source or Docker.

#### [location-history-visualizer](https://github.com/theopolisme/location-history-visualizer) ([demo](https://locationhistoryvisualizer.com/heatmap)) `static` `inactive`
A browser application that takes a single JSON dump of your Google location history and renders a
heatmap of your location data over time.

#### [mailtrain](https://github.com/Mailtrain-org/mailtrain) `docker`
An Express application for managing newsletter email lists. Email templates can be edited in the
app, and users can be uploaded using CSV. Uses MySQL and Redis databases on the backend. Deployment
via source or Docker Compose.

#### [nosqlclient](https://github.com/nosqlclient/nosqlclient) `docker`
A Meteor application for interacting with a MongoDB database. Uses a MongoDB database itself for
data persistence. Deployment via Docker.

#### [notational](https://github.com/tmm/notational) `static` `inactive`
A Vue note taking application with a Firebase backend.

#### [notella](https://github.com/siddharthkp/notella) ([demo](https://siddharthkp.github.io/notella)) `static` `inactive`
A note taking PWA written with vanilla JavaScript and a Firebase backend. Demo requires Twitter
authorization.

#### [opennote](https://github.com/FoxUSA/OpenNote) ([demo](https://foxusa.github.io/OpenNote/OpenNote)) `inactive`
An AngularJS note-taking application using PouchDB for browser storage. Can be connected to a
CouchDB database for syncing/persistence and Minio for file storage.

#### [pa11y-dashboard](https://github.com/pa11y/pa11y-dashboard)
An Express application for visualizing the results of the pa11y accessibility scan tool. Uses
MongoDB on the backend.

#### [pixel-art-react](https://github.com/jvalen/pixel-art-react) ([demo](https://www.pixelartcss.com))
A React application for drawing pixel illustrations and converting them to CSS code. Also supports
animations using Keyframes, exporting images, and sharing on Twitter. The backend is a small Express
application.

#### [qr-code-scanner](https://github.com/code-kotis/qr-code-scanner) ([demo](https://qrcodescan.in)) `static`
A PWA for decoding QR codes using the browser Media Stream API.

#### [react-kanban](https://github.com/markusenglund/react-kanban) ([demo](https://www.reactkanban.com))
A React kanban application inspired by Trello. It features a drag-and-drop interface and cards can
be written using Markdown. The backend is an Express application using MongoDB and Passport for
social authentication.

#### [reactjs-tmdb-app](https://github.com/SKempin/reactjs-tmdb-app) ([demo](https://skempin.github.io/reactjs-tmdb-app)) `static`
A React application using the TMDb API and Twitter's Typeahead.js.

#### [reforum](https://github.com/shoumma/ReForum) ([demo](https://reforum-app.herokuapp.com)) `inactive`
A JavaScript forum application with an Express backend using MongoDB and Passport, and a React
frontend.

#### [reportr](https://github.com/Reportr/dashboard) `abandoned`
An Express application that provides a visual dashboard of your daily activities and a REST API to
interface with it. Uses MongoDB on the backend.

#### [shout](https://github.com/erming/shout) `abandoned`
An Express-based IRC client that can be installed using NPM.

#### [sitespeed](https://github.com/sitespeedio/sitespeed.io) `docker`
A Node application for running a performance test on a website and generating HTML reports. Can be
run continuously to feed metrics to Grafana for monitoring. Can be installed using NPM or deployed
via Docker Compose.

#### [stackedit](https://github.com/benweet/stackedit) ([demo](https://stackedit.io)) `docker`
An in-browser Markdown editor. It can edit files either in the cloud or local. Files can be exported
in Markdown, HTML, PDF, Word, or EPUB. Content can be published to various blogging platforms or
GitHub. The backend is written with Express, and the frontend is a Vue application. Deployment via
source or Docker.

#### [stocks](https://github.com/toddwschneider/stocks) ([demo](https://toddwschneider.com/stocks)) `static`
A single HTML file for displaying stock market data using the IEX API. Users can pass additional
stock symbols as URL query parameters.

#### [svgomg](https://github.com/jakearchibald/svgomg) ([demo](https://jakearchibald.github.io/svgomg)) `static`
A browser application for using the SVGO optimization tool.

#### [syte](https://github.com/rigoneri/Syte2) ([demo](http://www.rigoneri.com)) `abandoned`
An Express application that builds a personal website for you by pulling data from Twitter,
Instagram, Foursquare, GitHub, Dribbble, Spotify, YouTube, and Tumblr. The frontend uses AngularJS,
and MongoDB is used for data persistence.

#### [thelounge](https://github.com/thelounge/thelounge) ([demo](https://demo.thelounge.chat))
A community maintained fork of Shout, an Express IRC client.

#### [snapdrop](https://github.com/RobinLinus/snapdrop) ([demo](https://snapdrop.net))
A PWA for sharing files between devices on the same network using WebRTC similar to Apple AirDrop.
Includes a Node.js server using Web Sockets as a fallback for devices that do not support WebRTC.
Also includes a starter NGINX config for serving the web app.

#### [speedtest](https://github.com/adolfintel/speedtest) ([demo](http://speedtest.fdossena.com))
A JavaScript application for implementing a speedtest on a server. Can use any backend capable of
serving a 20mb file.

#### [webogram](https://github.com/zhukov/webogram) `docker`
An AngularJS client for the Telegram messaging platform. Deployment via source or Docker.

#### [wekan](https://github.com/wekan/wekan) `docker`
A Meteor kanban application with a MongoDB backend. Features OAuth2 authentication, LDAP and IFTTT
integrations, Webhooks, and a REST API. Deployment via source or Docker Compose.

#### [winds](https://github.com/GetStream/Winds) `desktop` `docker`
A JavaScript application with a podcast player and RSS reader. The backend is written with Express,
MongoDB, and Redis; while the frontend is React. Requires API keys from Stream, Algolia, and Mercury
to run. Can be run as a web application or a desktop application via Electron. Deployment via
source or Docker.

#### [youtransfer](https://github.com/YouTransfer/YouTransfer) ([demo](http://demo.youtransfer.io)) `docker` `inactive`
A Restify application providing a simple web interface for uploading files to a server. Deployment
via source or Docker.

## PHP

#### [411](https://github.com/etsy/411) ([demo](https://demo.fouroneone.io))
A PHP application for managing alerts from Etsy. Uses SQLite, MySQL, and ElasticSearch LogStash.
Triggers can be setup to email uses when certain criteria is discovered in LogStash. Users can log
in and mark alerts as resolved or escalate them.

#### [akaunting](https://github.com/akaunting/akaunting) `docker`
A Laravel accounting application with a jQuery and Bootstrap frontend. Can use any database
supported by Laravel. Deployment via source or Docker Compose.

#### [ampache](https://github.com/ampache/ampache) ([demo](http://ampache.org/demo.html))
A Symfony application for streaming local and remote audio/video files. Uses a MySQL database on the
backend.

#### [bookstack](https://github.com/BookStackApp/BookStack) ([demo](https://demo.bookstackapp.com))
A Laravel documentation/wiki application with a Vue frontend using a MySQL database.

#### [cachet](https://github.com/CachetHQ/Cachet) ([demo](https://dev.cachethq.io/dashboard))
A Laravel application for hosting a status page similar to <https://status.github.com>. Can use any
database supported by Laravel. Demo credentials are `test`:`test123`.

#### [dolibarr](https://github.com/Dolibarr/dolibarr)
A PHP ERP and CRM application. Can use either MariaDB, MySQL, or PostgreSQL on the backend.

#### [faveo](https://github.com/ladybirdweb/faveo-helpdesk) ([demo](https://www.faveohelpdesk.com/online-demo))
A Laravel help-desk application. Uses a MySQL database on the backend.

#### [flarepoint](https://github.com/Bottelet/Flarepoint-crm) `docker`
A Laravel CRM application. Uses a MySQL database on the backend. Deployment via source or Docker
Compose.

#### [flarum](https://github.com/flarum/flarum) ([demo](https://discuss.flarum.org))
A PHP forum application with a Mithril frontend. Uses a MySQL database on the backend.

#### [freshrss](https://github.com/FreshRSS/FreshRSS) ([demo](https://demo.freshrss.org)) `docker`
A PHP RSS feed aggregator using a MySQL database on the backend. Deployment via source or Docker
Compose.

#### [handesk](https://github.com/BadChoice/handesk) `docker`
A Laravel help-desk system with a Vue frontend that also provides a REST API. Includes integrations
for Mailchimp and Bitbucket. Uses MySQL and LetsEncrypt. Deployment via source or Docker Compose.

#### [heimdall](https://github.com/linuxserver/Heimdall) `docker`
A Laravel application launcher and dashboard for web-based applications. Uses a SQLite database on
the backend. Deployment via source or Docker.

#### [invoiceninja](https://github.com/invoiceninja/invoiceninja)
A Laravel invoicing application with a frontend written with Knockout, jQuery, Bootstrap, and D3.
Uses a MySQL database. Also includes Dart code for building native mobile apps using Flutter.
Deployment via zip file or Docker.

#### [invoiceplane](https://github.com/InvoicePlane/InvoicePlane) ([demo](https://demo.invoiceplane.com)) `inactive`
A CodeIgniter invoicing application using a MySQL database on the backend.

#### [koel](https://github.com/phanan/koel) ([demo](http://demo.koel.phanan.net))
A Laravel application with a Vue frontend for streaming an MP3 collection using a Spotify-like
UI. Can be configured to scan a folder on the server or an AWS S3 bucket. Can pull metadata from
Last.fm or search for music videos on YouTube. Supports any database supported by Laravel.

#### [monica](https://github.com/monicahq/monica) `docker`
A Laravel application for keeping track of personal relationships like a CRM. Can use any database
supported by Laravel. Deployment via source or Docker.

#### [paperwork](https://github.com/twostairs/paperwork) `docker` `inactive`
A Laravel note-taking application with an AngularJS frontend. Uses a MySQL database on the backend.
Deployment via source or Docker.

#### [polr](https://github.com/cydrobolt/polr) ([demo](https://demo.polr.me)) `inactive`
A Lumen URL-shortener application using a MySQL database.

#### [selfoss](https://github.com/SSilence/selfoss)
A feed aggregator written with the Fat Free microframework. Pulls in RSS feeds, Twitter tweets, and
other news sources. Uses either MySQL, PostgreSQL, or SQLite on the backend. Frontend built with
jQuery UI.

#### [sonerezh](https://github.com/Sonerezh/sonerezh) ([demo](https://www.sonerezh.bzh/demo))
A Cake application for streaming a music collection. Uses a MySQL database on the backend.

#### [unmark](https://github.com/cdevroe/unmark) `inactive`
A PHP bookmark manager application using a MySQL database on the backend.

#### [wallabag](https://github.com/wallabag/wallabag) `docker`
A Symfony application for saving web sites and articles, similar to Pocket. Uses either MySQL,
PostgreSQL, or SQLite on the backend. Deployment via source or Docker.

## Python

#### [babybuddy](https://github.com/cdubz/babybuddy) ([demo](http://demo.baby-buddy.net)) `docker`
A Django application for parents to track a baby's daily activity. Requires a web server,
application server, and SQL database on the backend. Deployment via Heroku, AWS Elastic Beanstalk,
or Docker. Demo credentials are `admin`:`admin`.

#### [cabot](https://github.com/arachnys/cabot) `docker` `inactive`
A Django DevOps monitoring application. Uses PostgreSQL, Redis, Celery, and Caddy. Deployment via
Docker Compose.

#### [cloudtunes](https://github.com/jakubroztocil/cloudtunes) `abandoned`
An iTunes clone that streams audio files saved in Dropbox. The backend is written in Python using
Tornado, Celery, MongoDB, and Redis. The frontend is written in Coffeescript using Backbone.

#### [misago](https://github.com/rafalp/Misago) ([demo](https://misago-project.org)) `docker`
A Django forum application with a React frontend. Uses a PostgreSQL database on the backend.
Deployment via Docker Compose.

#### [pretix](https://github.com/pretix/pretix) `docker`
A Django ticket sales application. Uses MySQL, Redis, Memcached, and Postfix. Supports payments via
Stripe, PayPal, and bank transfer. Deployment via Docker.

#### [reminiscence](https://github.com/kanishka-linux/reminiscence) `docker`
A Django application for storing bookmarks. Uses a SQLite database by default, but can be replaced
with any database supported by Django. Deployment via source or Docker Compose.

#### [taiga](https://github.com/taigaio/taiga-doc)
A project management application with a Python backend using Django, PostgreSQL, and RabbitMQ; and
a JavaScript frontend using AngularJS.

#### [wger](https://github.com/wger-project/wger) `docker` `inactive`
A Django fitness tracker application for managing your weight, diet, and workouts. Can also be used
by personal trainers for managing individual clients. Can use any database supported by Django.
Deployment via source, PyPI, or Docker.

## Ruby

#### [discourse](https://github.com/discourse/discourse) ([demo](https://try.discourse.org)) `docker`
A Rails discussion/forum application with an Ember frontend. Uses PostgreSQL and Redis for data
persistence and caching. The only supported deployment method is via Docker.

#### [loomio](https://github.com/loomio/loomio) ([demo](https://www.loomio.org/p/example/proposal)) `docker`
A Rails app to fascilitate group decision making. Uses LetsEncrypt, Mailin, and PostgreSQL.
Deployment via source or Docker Compose.

#### [mastodon](https://github.com/tootsuite/mastodon) `docker`
A distributed (decentralized) social network. Each installation of Mastodon is a community, and can
communicate with other instances (or choose to remain private). The backend consists of a Rails
application that provides a REST API and a Node.js Express application provides a real-time,
streaming API. The frontend is built with React and Redux. PostgreSQL is used for data persistence,
and Redis is used for pub/sub. Deployment via source or Docker Compose.

#### [resume](https://github.com/resume/resume.github.com) ([demo](http://resume.github.io)) `abandoned`
An application that generates a resume based on your GitHub activity. Uses Rack on the backend.

#### [snibox](https://github.com/snibox/snibox) ([demo](https://snibox-demo.herokuapp.com)) `docker`
A Rails application for storing code snippets. Includes a Vue frontend and uses a PostgreSQL
database on the backend. Also includes integration with Mailgun for email. Deployment via source or
Docker Compose.

#### [standardnotes](https://github.com/standardnotes/web) ([demo](https://app.standardnotes.org)) `mobile` `desktop` `docker`
An encrypted note-taking application. There are clients available for all platforms. The web client
is an AngularJS application, while the server is a Rails application with a MySQL database.
Deployment via source, Heroku, or Docker Compose.

## Related
  * [awesome-selfhosted](https://github.com/Kickball/awesome-selfhosted)
  * [awesome-opensource-apps](https://github.com/unicodeveloper/awesome-opensource-apps)
  * [awesome-pwa](https://github.com/hemanth/awesome-pwa)

## License
[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [Adam Fields](https://github.com/adamelliotfields) has waived all
copyright and related or neighboring rights to this work.
