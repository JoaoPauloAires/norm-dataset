# Norm Dataset

This repository contains datasets used for sentence classification and norm conflict identification.

### Sentence Classification

In order to create a sentence classifier to say if a given sentence is either a norm or not, we manually annotated a set containing both norm and non-norm sentences.
Such annotation was made using existing contracts extracted from [onecle](http://contracts.onecle.com/) and organized by Gao and Singh in their work [Mining Business Contracts for Service Exceptions](http://ieeexplore.ieee.org/document/5708127/).

### Conflict Identification

To test a conflict identifier, we created norm conflicts from norms in existing contracts.
We created a tool that gets a random contract, selects a norm from it and asks to the user to modify such norm in order to generate a conflict.
We use, as in sentence classification dataset, contracts from [oncle](http://contracts.onecle.com/) organized by Gao and Singh.
