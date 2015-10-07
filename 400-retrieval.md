---
layout: page
title: Retrieval
permalink: /retrieval/
---

3D Object Retrieval allows the search for a set of similar 3D models, having a single model as an example.
This utility is particularly powerful and useful when dealing with a large set of models (as in the Diorama
Marketplace).
Additionally, in a 3D modelling context, 3D Object Retrieval allows users to specify shapes roughly, having the ability
to replace these 3D sketches with pre-existing models later.

![][retrieval-similar]

In particular for Diorama, the *EnContRA* meta-framework is used for 3D Object Retrieval. With its modular 
architecture, this framework allows the fast prototyping of different content retrieval approaches, descriptors and 
algorithms. The *EnContRA* framework includes modules for:

* Descriptors:
   * Image;
   * Vector drawings;
   * Graph;
   * Music;
   * 3D.
* Indexes;
* Storage;
* Conversion helpers;
* Metadata extraction;
* Polygon detection and vectorization services;
* REST API.

More information about the framework is provided on the [*EnContRA* Springer] publication and on the 
[*EnContRA* GitHub] page.

[retrieval-similar]: {{site.baseurl}}/images/retrieval/retrieval-similar.png "Retrieval of similar 3D objects"
[*EnContRA* GitHub]: http://encontra.github.io/
[*EnContRA* Springer]: http://www.di.fc.ul.pt/~mjf/publications/2014-2010/pdf/mta13.pdf