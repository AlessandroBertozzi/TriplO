# Iteration 1: Motivating Scenario

## Name
Basic document entites

## Description
Documents are one of the main entities within Triple's infrastructure. Each document has a substantial number of fields, which in turn are divided into a fair number of subfields. Some can be considered basic fields, with which simple queries can be constructed. 
These fields can be grouped as follows:

* Content fields:
    * `abstract`
    * `headline`
    * `language`
    * `topic`
* Fields about the subjects involved in the creation and publishing of the document:
    * `author`
    * `contributor`
    * `publisher`
* Time fields:
    * `date published`
* Technical fields, for the identification of the document within Triple's infrastructure or within other infrastructures that precede insertion into Triple's architecture:
    * `id`
    * `doi`

## Example 1

The document with id `oai:bibliotekanauki.pl:441219` has this entites:

* `author`: Arkadiusz Stempin
* `topic`: socio
* `headline`: The German model of integration policy

## Example 2

The document with Headline `Memórias da violência na América Latina: Araguaia – Campo Sagrado, Kamchatka e Linha de Passe` has this entites:

* `id`: oai:doaj.org/article:08e8a2c938404aebbaddbfcc02ab2954
* `date published`: 1985
* `headline`: The German model of integration policy
* `doi`: 10.7179/psri_2014.23.05