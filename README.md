# Portable Linked Profiles @ OuiShare Labs: Hacks Berlin

https://github.com/ouisharelabs/plp-berlin-hacks

## adding to your homepage

You can make your profile document discoverable either of:

1. [Content Negotiation](http://en.wikipedia.org/wiki/Content_negotiation)
2. [RDFa](http://www.w3.org/TR/xhtml-rdfa-primer/)
3. [rel="alternate"](http://www.w3.org/TR/html401/struct/links.html#h-12.3.3)
4. [JSON-LD in HTML](http://www.w3.org/TR/json-ld-syntax/#embedding-json-ld-in-html-documents)

## preparation steps

**example** profiles in ```./examples```
you can copy one of them to appropriate direcotry and edit

```shell
cp examples/person.cson people/
```

## technologies 

### JSON-LD and @context
please keep *plp-context.jsonld* file open and visible, it helps understand how
properties map to IRIs

### CSON

you will need node and npm on your maching, [nvm](https://github.com/creationix/nvm) recommended

[CSON package](http://npm.im/cson)


## TODO

### clarifications

* why to embedd objects
* why to inline types in embedded objects

### cases

* virtual machine used for hosting
* web service (offered)
* software project
* projects which organization works on
* 1 week ticket for public transport in berlin
