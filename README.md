*Stronger than steel, lighter in weight, FTN messages are its great freight.*

[![(a histogram of downloads)](https://nodei.co/npm-dl/mithrilsql.png?height=3)](https://npmjs.org/package/mithrilsql)

This module (`mithrilsql`) is a reader of MithrilSQL databases containing FTN messages for Fidonet Technology Networks.

This module is written in JavaScript and requires [Node.js](http://nodejs.org/) to run.

This module is currently in an early phase of its development and thus does not have the desired level of feature completeness.

## Database schema

This module is based on the ideas proposed in the message [`area://Ru.FTN.Develop?msgid=2:5063/88+4b7e31cf`](http://ftn.su/m/RU.FTN.DEVELOP/2:5063/88+4b7e31cf) and they imply [using SQLite as an application's file format](http://sqlite.org/appfileformat.html).

## Installing MithrilSQL

[![(npm package version)](https://nodei.co/npm/mithrilsql.png?downloads=true&downloadRank=true)](https://npmjs.org/package/mithrilsql)

* Latest packaged version: `npm install mithrilsql`

* Latest githubbed version: `npm install https://github.com/Mithgol/mithrilsql/tarball/master`

You may visit https://github.com/Mithgol/mithrilsql#readme occasionally to read the latest `README` because the package's version is not planned to grow after changes when they happen in `README` only. (And `npm publish --force` is [forbidden](http://blog.npmjs.org/post/77758351673/no-more-npm-publish-f) nowadays.)

## Testing MithrilSQL

[![(build testing status)](https://img.shields.io/travis/Mithgol/mithrilsql/master.svg?style=plastic)](https://travis-ci.org/Mithgol/mithrilsql)

It is necessary to install [JSHint](http://jshint.com/) for testing.

* You may install JSHint globally (`npm install jshint -g`) or locally (`npm install jshint` in the directory of MithrilSQL).

After that you may run `npm test` (in the directory of MithrilSQL). Only the JS code errors are caught; the code's behaviour is not tested.

## License

MIT license (see the `LICENSE` file).