# restalk-editor

This repository will hopefully evolve to become a tool for creating RESTalk Conversation diagrams.

## RESTalk DSL

RESTalk is a (currently) visual language for designing HTTP API interaction, which span over multiple requests to the server. 
It defines multiple building blocks, which you can see in the image below.

![RESTalk DSL](http://restalk-patterns.org/img/notation_horizontal.svg)

To learn more, follow the links below:

* [RESTalk patterns](http://restalk-patterns.org/)
* [RESTFest Edinburgh 2016 slides](https://github.com/RESTFest/2016-Edinburgh/wiki/Cesare-Pautasso#proposed-talks)

## The problem

RESTalk was designed as a teaching tool - the main purpose is to document the repeating patterns, commonly seen in Client-Server 
interaction. There is, however, great potential for it to become a API design tool. 

To become a design tools it would be necessary to create 

1. a human-readable, preferably textual, format (JSON? YAML? Markdown?) for authoring the conversations
2. simple tooling for generating RESTalk diagrams
3. (optional) more sophisticated tooling for creating conversations visually

## The solution

1. [Design the language][issue-design]
2. [Implement diagram generation][issue-generation]
3. [Implement visual editor][issue-editor]

[issue-design]: /tpluscode/restalk-editor/issues/1
[issue-generation]: /tpluscode/restalk-editor/issues/2
[issue-editor]: /tpluscode/restalk-editor/issues/3
