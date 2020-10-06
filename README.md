# PouchDB sync with Couchbase

## Requirements
- Refer this https://docs.couchbase.com/sync-gateway/current/gs-sgw-prereqs.html
- Couchbase server
- Couchbase sync gateway https://docs.couchbase.com/sync-gateway/current/gs-sgw-install.html
- Web server like 'web server for chrome'

## Getting Started

```bash
git clone https://github.com/itsmrajesh/pouchDB-sync-couchbase.git

cd pouchDB-sync-couchbase

npm install --save pouchdb

npm install --save @hoodie/store-client

```

- Setup couchbase bucket for syncing [Click here](https://docs.couchbase.com/sync-gateway/current/gs-sgw-svr-cfg.html#step-2create-rbac-user)
- Configure sync gateway https://docs.couchbase.com/sync-gateway/current/gs-sgw-config.html
- Update DB name and DB url in assest/index.js
- Open you webserver and point to index.html

For detailed explanation refer below links



# Ref links 

- https://www.codementor.io/@pmbanugo/using-pouchdb-and-couchbase-in-an-offline-first-application-5pw2sxs6o
