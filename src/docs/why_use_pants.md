Why Use Pants?
==============


Pants was designed for large codebases that require a scalable
version control system and a build system that can perform fine-grained dependency management among thousands of code modules in a single source tree.
Pants was made for this type of usage in a way that other popular build tools, such as
Ant, Maven, and SBT, were not. 

Pants is designed to give fast,
consistent builds in a monorepo environment.  Some noteworthy features
include:

+ Fine-grained invalidation.
+ Shared build caches.
+ Concurrent task execution.
+ Incremental compilation.
+ Extensibility, via a plugin API.

What does Pants support?
------------------------

Pants supports all stages of a typical build: tool bootstrapping, code
generation, third-party dependency resolution, compilation, test
running, linting, bundling and more.

Pants supports Java, Scala, Python, C/C++, Go, Thrift, Protobuf and Android code.
Support for other languages, frameworks and code generators can
be added by third party developers by authoring plugins through a well
defined module interface.

Pants is modeled after Blaze, Google's internal build system, now open-sourced as [Bazel](http://bazel.io/).
Another project with similar design goals to Pants is Facebook's [Buck](https://buckbuild.com/).
Pants' development and feature set were informed by the needs and
processes of many prominent software engineering organizations,
including those at Twitter, Foursquare, Square, Medium and others.
But it can also be used in smaller projects.  Best of all, Pants is
open source so you can freely share and modify Pants to suit your
needs or distribute it to others when you want to share your own
project.

How to get started
------------------------

+ Start by installing Pants. See [[Install|pants('src/docs:install')]].
+ Take a look at some basic [[Pants concepts|pants('src/docs:first_concepts')]].
+ Walk through a [[tutorial|pants('src/docs:first_tutorial')]].
