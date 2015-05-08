state-of-the-union
==================

About
-----

Describes various php DDD and CQRS initiatives all around the universe (mainly github universe, in fact).

- **DDD**: stands for <strong>D</strong>omain <strong>D</strong>riven <strong>D</strong>esign
- **CQRS**: stands for <strong>C</strong>ommand <strong>Q</strong>uery <strong>R</strong>esponsibility <strong>S</strong>egregation

Resources
---------

### DDD introductions

- [en] [slides] https://speakerdeck.com/richardmiller/avoiding-the-mud
- [en] [slides] https://speakerdeck.com/mathiasverraes/unbreakable-domain-models-dpc13
- [en] [video|slides] http://www.craftitonline.com/2014/01/ddd-series-domain-vs-frameworks-symfony2-silex-cilex-yolo-et-al/
- [en] [article] http://dddsample.sourceforge.net/characterization.html
- [en] [video] https://www.youtube.com/watch?v=QaIGN_cTcc8
- [en] [slides] https://speakerdeck.com/jacegu/my-domain-is-mine-and-i-dont-share-it
- [es] [youtube channel] http://www.youtube.com/playlist?list=PLfgj7DYkKH3DjmXTOxIMs-5fcOgDg_Dd2
- [fr] [article] http://www.infoq.com/fr/articles/seven-modelling-smells
- [fr] [article] http://www.croes.org/gerald/blog/domain-driven-design-ddd-pour-les-intimes/866/
- [fr] [article] http://blog.octo.com/domain-driven-design-des-armes-pour-affronter-la-complexite/
- [fr] [video] http://www.youtube.com/watch?v=dV8EFyIRagA
- [fr] [PDF] http://blog.infosaurus.fr/public/docs/DDDViteFait.pdf

### SOLID principle

- [en] [article] http://en.wikipedia.org/wiki/SOLID_%28object-oriented_design%29
- [fr] [article] http://afsy.fr/avent/2013/02-principes-stupid-solid-poo
- [fr] [article] http://blog.lepine.pro/php/gerer-des-regles-metiers-complexes-etou-changeantes
- [en] [article] http://williamdurand.fr/2013/07/30/from-stupid-to-solid-code/

### Design patterns

- https://github.com/domnikl/DesignPatternsPHP

### Code Organisation

- [en] [article] http://williamdurand.fr/2013/08/07/ddd-with-symfony2-folder-structure-and-code-first/

### Bounded contexts

- [en] [article] https://github.com/beberlei/whitewashing.de/blob/master/2013/06/24/bounded_contexts.rst
- [en] [video] https://www.youtube.com/watch?v=aieoAWXNjl0

### Specification pattern

- [en] [article] http://en.wikipedia.org/wiki/Specification_pattern
- [en] [article] https://github.com/beberlei/whitewashing.de/blob/master/2013/03/04/doctrine_repositories.rst
- [fr] [article] http://blog.lepine.pro/php/gerer-des-regles-metiers-complexes-etou-changeantes
- [fr] [article] http://blog.xebia.fr/2009/12/29/le-pattern-specification-pour-la-gestion-de-vos-regles-metier/

### Service Layers
- [en] [slides] http://www.slideshare.net/rosstuck/models-and-service-layers-hemoglobin-and-hobgoblins
- [en] [video] https://www.youtube.com/watch?v=3uV3ngl1Z8g

### CQRS / Event Sourcing

- [fr] [video] http://parleys.com/play/51b7f063e4b01033a7e4b764
- [en] [slides] http://verraes.net/2013/12/fighting-bottlenecks-with-cqrs/
- [en] [article] http://vadimcomanescu.wordpress.com/2012/06/26/cqrs-domain-events-and-ddd-review/
- [en] [article] http://msdn.microsoft.com/en-us/library/jj554200.aspx
- [en] [article] http://www.codeproject.com/Articles/555855/Introduction-to-CQRS
- [en] [article] http://coding-insomnia.com/2012/05/28/a-trip-to-cqrs-intro/
- [en] [slides] http://verraes.net/2014/03/practical-event-sourcing/
- [en] [slides] https://speakerdeck.com/stijnvnh/cqrs-or-did-you-mean-cars
- [ru] [article] http://habrahabr.ru/post/146429/
- [ru] [article] http://habrahabr.ru/post/149464/

### Existing php frameworks/libraries integrations, discussions


#### Proof of concept, implementation examples

- https://github.com/TBeijen/DDD-HRM
- https://github.com/beberlei/litecqrs-php
- https://github.com/tyx/cqrs-php-sandbox
- https://github.com/idr0id/ddd-blog
- https://github.com/szjani/predaddy
- https://github.com/malocher/cqrs-esb
- https://github.com/prooph/event-store
- https://github.com/prooph/service-bus
- https://github.com/codeliner/php-ddd-cargo-sample
- https://github.com/qandidate-labs/broadway
- https://github.com/dddinphp/ddd

### Hexagonal

Also know as Entity-Boundary-Interactor or Ports and Adapters.

- [Symfony2 sample application](https://github.com/MarcelloDuarte/hexagonal-symfony/)
- [Silex sample application](https://github.com/igorw/doucheswag/)
- [Last Wishes: A Silex sample application](https://github.com/dddinphp/last-wishes/)
- [Cockburn's hexagonal explains the architecture](http://alistair.cockburn.us/Hexagonal+architecture)
- [Chris Fidao explains hexagonal architecture](http://fideloper.com/hexagonal-architecture)
- [Palermo's onion shares the hexagonal architecture](http://jeffreypalermo.com/blog/the-onion-architecture-part-1)

#### Typo3/Flow3

- [poc] https://github.com/hmrdk/Cqrs.Core

#### Symfony2

- [en] [article] http://williamdurand.fr/2013/11/13/ddd-with-symfony2-basic-persistence-and-testing/
- [en] [article] http://williamdurand.fr/2013/08/20/ddd-with-symfony2-making-things-clear/
- [en] [slides] http://qafoo.com/talks/13_12_symfonycon_domain_events.pdf

#### Zend Framework 2

- https://github.com/prooph/ProophEventStoreModule
- https://github.com/prooph/ProophServiceBusModule

#### Doctrine2

- [en] [article] http://www.tibobeijen.nl/blog/2011/06/27/ddd-using-doctrine-2-a-case-study/
- https://github.com/TBeijen/DDD-HRM/tree/v001
- [en] [slides] http://qafoo.com/talks/13_12_symfonycon_domain_events.pdf

### CQRS implementations in other languages

- [ruby] https://github.com/cavalle/banksimplistic
- [fsharp] https://github.com/thinkbeforecoding/FsUno
- [java] http://www.axonframework.org/

Recommended reading
-------------------

### DDD

- ["Domain-Driven Design in PHP"](https://leanpub.com/ddd-in-php), Carlos Buenosvinos, Christian Soronellas, and Keyvan Akbary, 2014
- ["Domain Driven Design Quickly"](http://www.infoq.com/fr/minibooks/domain-driven-design-quickly), InfoQ.com, 2006
- "Domain-Driven Design: Tackling Complexity in the Heart of Software", Eric Evans, 2005
- "Applying Domain-Driven Design and Patterns: With Examples in C# and .NET", Jimmy Nilsson, 2006
- "Implementing Domain-Driven Design", Vaughn Vernon, 2013
- "Domain-Driven Design Reference: Definitions and Pattern Summaries", Eric Evans, 2014

####DDD C# implementations

- ".NET Domain-Driven Design with C#: Problem - Design - Solution", Tim McCarthy, 2008

### Coding practices

- "Patterns of Enterprise Application Architecture", Martin Fowler, 2002

Other Github organisations
--------------------------

- https://github.com/dddinphp
- https://github.com/orgs/ddd-php
- https://github.com/phpmentors-jp

On Discussion Groups
----------------

- [DDDinPHP](http://dddinphp.org) on Google Group

On twitter
----------

- https://twitter.com/DDDBE
- https://twitter.com/dddbook

On IRC
------

- [#DDDinPHP](irc://irc.freenode.net/#dddinphp) on Freenode
