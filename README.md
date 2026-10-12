Quantum Madlib Choose Your Own Adventure Machine

A white-box AI system: deterministic, local, and auditable.

What it is

Quantum is a white-box AI system. You make algorithms into language.

You start by building a corpus from several sources: data scraped from the web, internal databases, the public domain, or paid services. From that corpus you create a schema. Data from the schema, whether complete sentences or partial information, is used to build algorithms that fill and modify templates, sentence by sentence. Those sentences are then used to create other algorithms, which change the sentences before or after them. The result is a custom response, built entirely from rules you can read and edit as the situation requires.

The system is:

Local: your data never leaves your machine.
Deterministic: the same input produces the same output, every time.
Has memory: resolved facts are kept and reused by later decisions.
Auditable: every output can be traced back to the rule that produced it.

No black box, no weights you can't read. Every rule is written by a person who understands it.

It is not limited to one field. Anything that turns information into structured writing or decisions can be built with it.

The core ideas
Nodes: the smallest holdable piece of information, which can be a word, a number, a sentence or a whole program.
Labels: what a node is.
Weights: how much a node's signal counts. A weight can be a boolean, arithmetic, a lookup, or a whole subprogram.
States: a node that has been weighed and resolved to yes, no, or not present. Permanent states become facts other decisions can rely on.
Templates (the "Mad Lib"): sentences with typed slots, chosen and filled by resolved states.
Read the book

The full method is explained in Book Explination of System, from nodes and labeling through states, templates and weights.

Status
 Book draft
 Python implementation
About

I have worked in anti-money laundering (AML) for 8 years and have refined this system over 10 years. I use it to automate my own work, generating deterministic, local, near-instantaneous narratives: documentation is quantified into nodes, and the outcome of the weights decides which template writes the result. AML is where it started, but I use it to automate many other tasks as well.

I am self-taught. This work is free, and I am not selling anything.

License

Public domain. Released under CC0 1.0 Universal: copy, adapt and use it for anything, without asking.
