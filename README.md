# python-web-bottle-mvc-ssl-postgres-simple

## Description
Simple web app that serves static pages
for a bottle project.

Uses sqlalchemy query a table `dog`.

Is self-signed ssl cert.

## Tech stack
- python
  - bottle
  - sqlalchemy
  - beaker
  - cheroot
- bootstrap
- jquery
- dataTable
- postgres
- ssl

## Docker stack
- alpine:edge
- python:latest
- postgresql

## To run
`sudo ./install.sh -u`
- [Availble at](https://localhost)

## To stop
`sudo ./install.sh -d`

## For help
`sudo ./install.sh -h`

## Credit
[Bottle sqlalchemy setup](https://github.com/iurisilvio/bottle-sqlalchemy/blob/master/examples/basic.py)
