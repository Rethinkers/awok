# awok Overview

## Description
awok is a knowledge management platform that models logical and probabilistic connections between units of knowledge.  A unit of knowledge is conceptually a proposition, but it is up to the user or user-programmed agent to decide what constitutes a proposition and what it means.  awok focuses not on the content of the propositions, but their logical relationships. For example, propositions A and B might be related by the logical relationship ```if A then B```. 

## Objective
The purpose of awok is to allow a user to accomplish any of the following goals:

* __delineate__ the logical structure of documents, collections of documents, fragments of documents and other sets of text data;
* __visualize__ such logical structures;
* __validate__ such logical structures to determine if they are sound, and if not, identify the error;
* __evaluate__ such logical structures to determine the truth or probability of potential conclusions given the truth or probability of selected premises;
* __explore__ what happens when assumptions are changed; 
* __define__ abstract models of logical structures;
* __apply__ such abstract models to new sets of knowledge; and
* __export__ this value-added knowledge .

## How It Works
awok operates as a web application, suitable for deploying to cloud infrastructures.  It is comprised of several fairly independent components, each addressing a particular task domain:
* data aquisition -- upload files, retrieve documents from web urls, or enter text directly into the system
* persistence -- store data in a database
* logical metadata -- allow logical connections to be defined, displayed, edited and exported
* knowledge web visualizer -- generate an interactive graphical representation of data plus logical metadata
* analytical plugins -- an API and plugin architecture supporting components that analyze and report on the knowledge web, for example:
** validator -- find contradictions and inconsistencies
** evaluator -- compute boolean values and probabilities given a paeriial set of a values


