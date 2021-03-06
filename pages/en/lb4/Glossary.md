---
lang: en
title: 'Glossary'
keywords: LoopBack 4.0, LoopBack 4
tags:
sidebar: lb4_sidebar
permalink: /doc/en/lb4/Glossary.html
summary:
---
**Action**: JavaScript functions that only accept or return Elements. Since the input of one action (an Element) is the output of another action (Element) they are easily composed.

**API specification**: An [OpenAPI](https://www.openapis.org) document (in YAML or JSON format) that describes a REST API.  It specifies the metadata (verbs, paths, headers, and so on) a client needs to make a valid request to the API.

**Application**: A container of components.

**Component**: A reusable bundle of Bindings, [Controllers](Controllers.html), Services, [Repositories](Repositories.html), and models.  For more information, see [Using components](Using-components.html) and [Creating components](Creating-components.html).

**Connector**: An interface that abstracts underlying backend systems (for example, database, web service, and so on).

**Context**: An encapsulation of request and response objects provides useful values for writing web applications and APIs. For more information, see [Context](Context.html).

**Controller**: The implementation of API endpoints.

**DataSource**: A named configuration for a Connector instance that represents data in an external system.

**Element:**  The building blocks of a Sequence, such as route, params, and result.  For more information, see [Sequence](Sequence.html#elements).

**Mixin**: An interface for models.

**Model**: Defines application data and how it is connected to other data.

**Sequence**: A stateless grouping of actions that control how an Application responds to requests.

**Service**: Operations implemented in an external system.

**Repository**: A type of Service that represents a collection of data within a DataSource. For more information, see [Repositories](Repositories.html).
