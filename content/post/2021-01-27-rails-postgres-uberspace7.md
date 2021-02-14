+++
title = "Rails and Postgres on Uberspace7"
date = 2021-01-27
draft = false
[taxonomies]
tags = ["rails", "postgres", "uberspace"]
category = ["blog"]
+++

We migrated rorganize.it to uberspace7

Postgres now has to be installed manually in a non-standard location.
Following this https://lab.uberspace.de/guide_postgresql.html


Effed your postgres user?
pg_hba.conf to the recue!

trust

https://datarrett.com/641/understanding-the-pg-hba-conf-file-in-postgresql

tell bundler the location of your postgres so it can install pg

```
bundle config build.pg --with-pg-config=/home/user/opt/postgres/bin/pg_config
```

you cat check the `cat ~/.bundler/config`


webbackend


serve static assets

supervisor.d
