<!--
SPDX-FileCopyrightText: 2025 comodelling.org contributors: https://github.com/comodelling/comodelling-website/CONTRIBUTORS.md
SPDX-License-Identifier: CC-BY-SA-4.0
-->

# Modelling space

A convenient way to think about different data models we can build is to start from an empty space, and progressively adding structure to it.
So we could start by imagining the modelling space as an empty 2D plane, an expansive space to write on.

<!-- Empty modelling space image -->

By giving this space a structure, we are at the same time enabling and constraining possible creations within the space, thus defining our data model.

How would you like your co-modelling community to interact with that space? What tools, constraints or rules should we give ourselves to produce, model, represent content?

## Entity space

Say that in that space, we can spawn different entities, represented as distinct circles on the plane.

Though those entities don't have an explicit meaning associated with them (yet), we could attach attributes, like strings or numbers to them.


## Semantic space

Say that in that space, we can spawn different entities, represented as distinct circles on the plane.

We could choose to associate a certain named type or meaning to all entities, say for example that they can only represent "questions", or "possible actions", resulting in a “question space", or an “action space", etc.

<!-- example of a typed entity space -->

Of course, we could combine different types in one space, for example a space of "projects" and "problems".
And we could also associate properties to each entity type, i.e. give a name, type and associated meaning with its attributes.

<!-- example of a space with two types -->

When specifying types with associated meaning, we are defining a semantic layer in our data model.


## Graph space

Graphs provide a data structure to explicitly link different entities together, through directed or undirected links.
Those links are generally represented with arrows (when directed) or segments (when undirected).

<!-- example of graph space -->

[Knowledge graphs](knowledge_graphs.md) effectively add a semantic layer onto graphs.


## Metric space

Thinking explicitly about a metric space can help us with visualising, navigating or clustering the products of our model.
By imagining entities on a 2D plane, we have already suggested a support for representation, though without explicitly specifying how the entities should be layed out.