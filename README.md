This is the for of django-fts

<http://code.google.com/p/django-fts>

All the modification to fix issue #7 there are made.

<http://code.google.com/p/django-fts/issues/detail?id=7>

To include with pip in virtualenv add the following line to `requirements.txt`

```
-e git+https://github.com/dudarev/django-fts#egg=fts
```

## django-fts

This is a generic Full Text Search engine for Django projects.

Currently implements three backends: dummy, simple and pgsql.

* dummy: just uses ILIKE to do the search (no indexes)
* simple: implements the search using two helper tables for the indexes
* pgsql: uses PostgreSQL 8.3 full text search engine

It should be possible to easily integrate MySQL, Sphinx and Xapian backends too.

For installation instructions, see the file "INSTALL.txt" in this
directory; for instructions on how to use this application, and on
what it provides, see the file "overview.txt" in the "docs/"
directory.
