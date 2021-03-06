---
title: Museum
layout: listing
active: false
status: museum
---

# The Theorem Prover Museum

Theorem provers are software systems that can find or check proofs for conjectures given in some logic. 
Research in theorem proving system started with the logical theorist 1955 and has led to a succession of systems since. 

Theorem provers are complex software systems that have pushed the envelope of artificial intelligence and programming, and as such they constitute important cultural artefacts. 

With the current wave of retirements of the original principal investigators there is good chance that the systems are lost, when their group servers are shut down. 
This web site aims to preserve the ones we can still get our hands on. 
This idea is compatible with the [Software Heritage](https://www.softwareheritage.org) initiative, and contributes since it is based on [GitHub](https://github.com) repositories. 

The term "museum" may be sound bit ambitious, since the exhibition and didactic interpretation of the theorem provers is beyond our scope (and perhaps abilities). 
But the foremost function of a [museum](https://en.wikipedia.org/wiki/Museum) is the conservation of artefacts, which is what the "theorem prover museum" project intends to do. 

This site is the front-end to a collection of source code repositories for theorem provers (see below). 
Note that it is not the purpose of this site to keep the theorem proving systems running (in many cases the compilers and dependencies have moved on, making this very difficult), but only to archive the source code for academic study and aggregate meta-data about the systems. 
In particular this should lower the barrier of archiving systems here. 

See also [most wanted list](/wanted/), [systems believed lost](/lost/), [how to contribute](/contributors/), [Community](/community/), [project/issues](https://github.com/theoremprover-museum/theoremprover-museum.github.io/issues). 

### Latest News [Full List](/news/) [<img class="icon" src="{{ site.baseurl }}/public/feed.png" alt="atom feed">]({{ site.baseurl }}/atom.xml)

<ul class="collection">
  {% for post in site.posts limit:5 %}
    <li class="collection-item">
      <a href="{{post.url}}" class="title">{{post.title}}</a>
		  ({{post.date | date: "%-d %B %Y" }})
    </li>
  {% endfor %}
</ul>

### Related Resources

[Encyclopedia of proof systems](https://proofsystem.github.io/Encyclopedia/), [Wikipedia page](https://en.wikipedia.org/wiki/Automated_theorem_proving), [... more](/related/). 

All theorem provers start out as active systems, eventually development gets discontinued as developers retire or move to newer systems. 
Therefore we also maintain a list of [source code repositories of active theorem provers](/active/). 

## Theorem Provers

