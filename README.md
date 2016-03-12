# Web Shell

A tiny shell for browser based content editor apps.

Equivalently, an ala carté CMS for static sites.

## Technical architecture

 - Runtime component registration via ES6/commonjs modules
 - Services dependency injected as Shell environment provides services (storage provider etc).


* *Decouple apps from their storage*:  Abstract StorageProvider interface
  - [ ] Local (IndexedDB)
  - [ ] Webdav
  - [ ] IPFS
  - [ ] Tiddlywiki file storage
  - [ ] Tiddlyweb server
* [ ] Run [Metalsmith](https://github.com/metalsmith/metalsmith) pipelines through the browser?


* [ ] interface 
  * [ ] local DB (indexeddb)
  * 



* [ ] interface HtmlApp
  - [ ] Instantiated in an iframe subdomain
  - shell injects dependencies via [jspm](http://jspm.io/) manifest.
  - Interfaces are dependency injected via a load-time manifest (jspm.conf)
  - suborigin sandboxing
* Apps installed by dragging URL to "new app" button

Prosemirror Demo App

http://codepen.io/edrex/full/ONNqLx/

Idea: edit your content over the web.

Browser apps are cool. You know what's cooler? Unhosted browser apps!

Idea:

 - Local markdown 

This is an experimental adapter enabl

Here's the idea: create a contract between simple HTML5 web apps and 

## Reseach

### WYSIWYG editor for markdown

- http://marijnhaverbeke.nl/blog/prosemirror.html
- https://prosemirror.net/guide/basics.html


### Extensions VS apps



### App loading



### Would atom shell be useful?

https://github.com/sindresorhus/awesome-electron
