---
layout: page
title: ABSTAT
permalink: /abstat/
hidenInHeader: true
---

<div class="screenshot"><img alt="" src="/static/files/abstat/abstat_screenshot.png"></div>
<br>

#### Functionality
ABSTAT (Linked Data Summaries with ABstraction and STATistics) is a framework that computes and provides access to synthetic descriptions of RDF data sets. These descriptions can be viewed as profiles of RDF data sets and are called summaries in ABSTAT. 

The summary of a data set describes its content by listing every schema-level pattern that occurs in the data and a set of statistics. A schema-level pattern, named also abstract knowledge pattern (akp) or, more simply, pattern, is a triple <Type_1,P,Type_2> that tells there are instances of Type_1 linked to instances of Type_2 with the property P. With the term type we refer to either an ontology class (e.g., foaf:Person)  or a datatype (e.g., xsd:DateTime). In addition to patterns, summaries provide several statistics for the patterns and their constituents, i.e., types and properties. The version of ABSTAT that is deployed in the EuBusinessGraph computes and includes statistics about the occurrence of patterns, types and properties. Occurrence assigned to a pattern <Type_1,P,Type_2> tells how many instances of Type_1 are linked to instances of Type_2 with the property P.  

#### Installation guide
<a href="https://bitbucket.org/disco_unimib/abstat-core">https://bitbucket.org/disco_unimib/abstat-core</a>

#### User guide
<a href="https://bitbucket.org/disco_unimib/abstat-core">https://bitbucket.org/disco_unimib/abstat-core</a>

#### API documentation
<a href="https://bitbucket.org/disco_unimib/abstat-core">https://bitbucket.org/disco_unimib/abstat-core</a>

#### Software license
<a href="https://www.gnu.org/licenses/agpl-3.0.html">GNU Affero General Public License v3.0</a>

#### Source code repository
<a href="https://bitbucket.org/disco_unimib/abstat-core">https://bitbucket.org/disco_unimib/abstat-core</a>

#### Contact person
matteo.palmonari [at] unimib [dot] it
