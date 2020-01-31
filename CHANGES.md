2020-01-31, Version 0.5.17
==========================

 * revert: go back to using original bagpipes (Kevin Delisle)

 * chore: use @stack-fintech/bagpipes (Kevin Delisle)

 * chore: switch to @stack-fintech/bagpipes (Kevin Delisle)

 * Bugfix for specifying swagger file directory (Meyenehi Iduwe)


2015-10-19, Version 0.5.13
==========================

 * update swagger-tools version (Scott Ganyo)

 * Change JsonErrorHandler to handle statusCode on Errors (Hans)


2015-10-12, Version 0.5.11
==========================

 * swagger-tools 0.9.7 causes some breakage, pinning to 0.9.6 until it's worked out (Scott Ganyo)


2015-10-09, Version 0.5.10
==========================

 * have error handler use existing statusCode when it seems appropriate (Scott Ganyo)

 * fix tests (Scott Ganyo)


2015-10-08, Version 0.5.9
=========================

 * Do not allow error to propagate after handler (Scott Ganyo)


2015-10-08, Version 0.5.8
=========================

 * force new version of bagpipes (Scott Ganyo)


2015-10-07, Version 0.5.7
=========================

 * mockMode not being processed correctly. Fixes swagger-api/swagger-node/issues/302 (Scott Ganyo)


2015-10-06, Version 0.5.6
=========================

 * Allow connect errors to be emitted. Fixes https://github.com/swagger-api/swagger-node/issues/301 (Scott Ganyo)


2015-09-28, Version 0.5.5
=========================

 * switch to using 'config' module to load config (Scott Ganyo)


2015-09-10, Version 0.5.4
=========================

 * fix hapi middleware (Scott Ganyo)


2015-09-10, Version 0.5.3
=========================

 * fix error in sails middleware (Scott Ganyo)


2015-09-10, Version 0.5.2
=========================

 * middleware fixes for hapi, restify, and sails (Scott Ganyo)


2015-09-10, Version 0.5.1
=========================

 * force up the bagpipes version (Scott Ganyo)

 * emit uncaught errors to the console (Scott Ganyo)

 * use arrays for fittings and views dirs (Scott Ganyo)

 * fix tests (Scott Ganyo)

 * rename swagger_doc to swagger_raw (Scott Ganyo)

 * allow direct setting of swagger object from config (Scott Ganyo)

 * minor updates (Scott Ganyo)

 * fix existing tests (Scott Ganyo)

 * switch to bagpipes (Scott Ganyo)


2015-08-03, Version 0.4.6
=========================

 * ensure json error handler is included by default (Scott Ganyo)


2015-07-27, Version 0.4.5
=========================

 * Made Assignment of `json` to `res` conditional (Behrang Saeedzadeh)

 * bump swagger-tools version. fixes #5 (Scott Ganyo)

 * fix leaky rawDoc path (shole)


2015-06-12, Version 0.4.4
=========================

 * fixes #2 (Scott Ganyo)


2015-06-08, Version 0.4.3
=========================

 * update swagger-tools version to 0.8.7 (Scott Ganyo)

 * Always attaching config to request.swagger causes swagger-tools to choke and throw 405. Removing this feature. (Scott Ganyo)


2015-05-28, Version 0.4.2
=========================

 * set content-type in jsonErrorHandler (Scott Ganyo)


2015-05-06, Version 0.4.1
=========================

 * switch from yamljs to js-yaml (Scott Ganyo)


2015-05-04, Version 0.4.0
=========================

 * Switch config from swaggerNode to just swagger. Note: This module is moving to a backend utility for specifically-named middleware. (Scott Ganyo)


2015-04-23, Version 0.3.4
=========================

 * ensure header name case is insensitive (Scott Ganyo)


2015-04-23, Version 0.3.3
=========================

 * don't delete request.query, set it to undefined to prototype isn't used (Scott Ganyo)

 * change deps (Scott Ganyo)

 * add travis build status (Scott Ganyo)

 * add travis command file (Scott Ganyo)


2015-04-22, Version 0.3.2
=========================

 * repair issue created in swagger-tools version rev (Scott Ganyo)


2015-04-22, Version 0.3.1
=========================

 * test coverage for utility (Scott Ganyo)

 * add some hapi test coverage (Scott Ganyo)

 * even more tests (Scott Ganyo)

 * more tests (Scott Ganyo)

 * Update README.md (Scott Ganyo)

 * added some tests, made minor repairs (Scott Ganyo)


2015-04-16, Version 0.3.0
=========================

 * add filtering capability to swagger doc serving middleware (Scott Ganyo)

 * fix up middleware to better address supported and unsupported options (Scott Ganyo)

 * typo (Scott Ganyo)


2015-04-14, Version 0.2.2
=========================



2015-04-14, Version 0.2.1
=========================

 * sails middleware must not use mapErrorsToJson (Scott Ganyo)


2015-04-14, Version 0.2.0
=========================

 * explicit restify middleware, better error handling, fix hapi (Scott Ganyo)

 * don't allow json err handler to error (Scott Ganyo)

 * add swaggerDoc serving function (Scott Ganyo)


2015-04-08, Version 0.1.0
=========================

 * fix up config option hierarchy and enable CORS support (Scott Ganyo)


2015-04-05, Version 0.0.7
=========================

 * Initial Hapi support (Scott Ganyo)


2015-04-03, Version 0.0.6
=========================

 * update readme (Scott Ganyo)

 * add sails and hapi aliases (Scott Ganyo)

 * add jshint file (Scott Ganyo)

 * fix config names (Scott Ganyo)


2015-04-02, Version 0.0.5
=========================

 * add explicit express and restify middleware options (Scott Ganyo)


2015-04-01, Version 0.0.4
=========================

 * name anonymous functions (Scott Ganyo)

 * add jsonErrorHandler middleware (Scott Ganyo)


2015-03-31, Version 0.0.3
=========================

 * add missing require (Scott Ganyo)


2015-03-30, Version 0.0.2
=========================

 * First release!
