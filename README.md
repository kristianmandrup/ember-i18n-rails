#ember-i18n-rails#

Loosely Based on https://github.com/fnando/i18n-js of Nando Vieira

## Instalation:

### in Gemfile:

    gem "ember-i18n-rails"

### then call:

    rake ember:i18n:setup

### in app/assets/javascript/application.js
    //= require i18n/cldr_plurals
    //= require i18n/ember-i18n
    //= require i18n/translations

Or try simply using

    //= require ./i18n

Or even

    //= require_tree ./i18n

## Exporting locales:

    rake ember:i18n:export

## Updating ember-i18n

    rake ember:i18n:update

