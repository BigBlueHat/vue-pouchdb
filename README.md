[![MIT License](https://img.shields.io/badge/license-MIT-blue.svg?style=flat-square)](LICENSE)
[![Patreon](https://img.shields.io/badge/donate-patreon-orange.svg?style=flat-square)](https://www.patreon.com/BigBlueHat)

# vue-pouchdb

[Vue.js](http://vuejs.com/) plugin that adds [PouchDB](http://pouchdb.com/)
to your Vue.js apps.

It also (currently) includes
[pouchdb-authentication](http://github.com/nolanlawson/pouchdb-authentication)
because you probably should use that if you're building browser apps. :smiley_cat:

It's a tiny useful bit of code I extraced from [BlueInk](http://github.com/BigBlueHat/BlueInk).

## Usage

Assumes [browserify](http://browserify.org/):

```
Vue.use(require('vue-pouchdb'), {name: 'database-name'});
```

The first option is the plugin--see
[Vue.use()](http://vuejs.org/guide/plugins.html#Using_a_Plugin) for more info.
The second option is the [options object for PouchDB](https://pouchdb.com/api.html#create_database).

If you want to use this with [Apache CouchDB](http://couchdb.apache.org/) or [Cloudant](http://cloudant.com/), pass a database URL as the `name`. Easy peasy! :smiley_cat:

## License

MIT
