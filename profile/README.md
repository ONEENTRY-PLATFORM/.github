<p align="center">
  <a href="https://oneentry.cloud" target="_blank">
    <img src="https://oneentry.cloud/img/git/oneenrty_light.png" alt="OneEntry Platform" width="480">
  </a>
  <br /><br />
</p>

Welcome to the official repository of OneEntry.

<p>
📚 <a href="https://doc.oneentry.cloud/docs/category/">Documentation</a>
</p>
<p>
🛠️ <a href="https://js-sdk.oneentry.cloud/docs/index/">JavaScript and TypeScript SDK Documentation</a>
</p>
<p>
📱 <a href="https://sdk-kmp.oneentry.cloud/">Kotlin Multiplatform SDK Documentation</a>
</p>

<br />

 <p align="center"> 🚀 <a href="https://oneentry.cloud/instructions">Get started</a> &nbsp;|&nbsp; 👤 <a href="https://account.oneentry.cloud/authentication/register">SignUp</a></p>
<br>

OneEntry combines Headless CMS and Headless E‑Commerce into a single BaaS platform, providing a unified backend designed for scalability and seamless management of both content and commerce. The core concept of the platform is to free developers from server setup, ensure secure data storage, and deliver extensible business logic without plugins or external workarounds.

<a href="https://www.youtube.com/watch?v=WIdew_41UNM" target="_blank" alt="Watch the video">
  <img src="https://img.youtube.com/vi/WIdew_41UNM/maxresdefault.jpg" alt="Watch the video"/>
</a>
<p align="center">(Video overview of the admin panel)</p>

## How It Works

The architecture delivers data via API and renders it using any frontend technology: websites, mobile apps, social network mini‑apps, Smart TV, and more. OneEntry includes a ready‑made cloud infrastructure, eliminating the need for DevOps involvement and letting teams focus on product development.

To make development easier, we provide SDKs for **JavaScript/TypeScript**, **Kotlin**, and **Swift**.  
These SDKs include full in‑code documentation, strict type definitions, and extensive usage guides with examples — enabling fast and frictionless integration of OneEntry into projects of any complexity.

# Key Features

## Backend as a Service

A ready‑to‑use backend including business logic, database, APIs, microservices, and low‑code tools for integrating third‑party systems directly in the interface. Projects can launch without setting up servers or databases manually.

## Headless CMS

Content is managed independently from its presentation layer. The system supports text, media, files, user data, catalogs, content versioning, and multilingual support.

You can create and edit flexible data models directly in the interface, with configurable validation rules.

### Attributes & Attribute Sets

Dynamic fields grouped into sets, supporting types including:

-   string, text, rich text
-   number, float
-   date, time, date‑time, intervals
-   image, image groups
-   file
-   list, radio
-   dynamic references to pages or catalog items
-   button
-   JSON

Each attribute supports:

-   additional metadata fields
-   data validators with custom error messages
    -   required
    -   trim whitespace
    -   string length
    -   URL validation
    -   number validation and rounding
    -   email validation
    -   default value
    -   allowed values list
    -   input mask
    -   regex validation
    -   comparison
    -   logical validation
    -   image size validation
    -   file validation

[Video](https://www.youtube.com/watch?v=-F3B3mpp7yU&pp=0gcJCRUKAYcqIYzv) | [Documentation](https://doc.oneentry.cloud/docs/category/attributes)

## Pages

Structure and content of website sections or app screens.

Includes:

-   hierarchical tree of pages
-   error pages
-   visibility management
-   page ordering
-   attaching attribute sets, blocks, and forms

[Video](https://www.youtube.com/watch?v=AqraOf5WW7Y) | [Documentation](https://doc.oneentry.cloud/docs/category/pages)

## Blocks

Reusable data blocks with or without logic.

[Video](https://www.youtube.com/watch?v=cQpyEi-S4Gw) | [Documentation](https://doc.oneentry.cloud/docs/category/blocks)

## Templates

Mappings between content and frontend components.

[Documentation](https://doc.oneentry.cloud/docs/category/templates)

## Menus

Navigation structure.

[Documentation](https://doc.oneentry.cloud/docs/category/menu)

## Forms

Registration, login, feedback, comments, data collection.

[Documentation](https://doc.oneentry.cloud/docs/category/forms)

## Multi‑language

Full multi‑language content support.

[Video](https://www.youtube.com/watch?v=-7gl9-rU30M) | [Documentation](https://doc.oneentry.cloud/docs/category/languages)

## Real‑time Editing

Simultaneous work of multiple administrators.

## Administrators Permissions

Fine‑grained permissions for system administrators.

[Documentation](https://doc.oneentry.cloud/docs/category/administrators)

## Users & Permissions

User registration, authentication, verification, roles, and access rights.

[Video](https://www.youtube.com/watch?v=FoK1Wi75peE) | [Documentation](https://doc.oneentry.cloud/docs/category/users)

## Visual Text Editor

Supports HTML and Markdown.

## Integration (Low‑code)

Connect external services, exchange data, and create custom API endpoints.

[Video](https://www.youtube.com/watch?v=4RX4TsJm-tc) | [Documentation](https://doc.oneentry.cloud/docs/category/integrations)

## Integration Collections

Custom data storage for external system data.

[Video](https://www.youtube.com/watch?v=4RX4TsJm-tc) | [Documentation](https://doc.oneentry.cloud/docs/category/integration-collections)

## Journal

Administrator activity history.

[Video](https://www.youtube.com/watch?v=6FMJV7qW-c0) | [Documentation](https://doc.oneentry.cloud/docs/category/journal)

## Events

Trigger actions based on data changes, configurable notifications and payload structure.

[Video](https://www.youtube.com/watch?v=LGR_Zc1yDb4) | [Documentation](https://doc.oneentry.cloud/docs/category/events)

## Newsletters

Email campaigns for users.

[Documentation](https://doc.oneentry.cloud/docs/events/edit-event#Mailing-to-Users-Mailing-Mode)

## Push Notifications

Configurable push delivery logic.

[Documentation](https://doc.oneentry.cloud/docs/events/introduction/#Key-Interface-Elements-of-the-Events-Module)

## Custom Business Logic

Extend platform logic using low‑code tools or custom modules in Node.js, Python, or PHP with built‑in CI/CD.

[Video](https://www.youtube.com/watch?v=sQYEbioR_YQ) | [Documentation](https://doc.oneentry.cloud/docs/settings/custom_modules)

## Image Preview & Optimization

Thumbnail presets, optimization pipelines, default thumbnails, per‑attribute thumbnail templates.

[Documentation](https://doc.oneentry.cloud/docs/templates/templates_preview)

## Search

Content search.

## Filter Data

Configurable filtering conditions for content retrieval.

## Data Migration

Import MySQL and PostgreSQL databases from other systems.

## Import OpenAPI Schemas

Upload existing OpenAPI schemas directly into the Integration module.

[Documentation](https://doc.oneentry.cloud/docs/integrations/import)

## Catalog Module

### Categories

-   hierarchical category tree
-   visibility and ordering
-   product ordering and fixing
-   default blocks and forms per category
-   attach attribute sets, blocks, forms

[Video](https://www.youtube.com/watch?v=q9xj0Q630-g) | [Documentation](https://doc.oneentry.cloud/docs/catalog/add-catalog_element)

### Catalog Search & Filters

Search and filter configuration.

[Video](https://www.youtube.com/watch?v=a4-wcseD9Sg) | [Documentation](https://doc.oneentry.cloud/docs/catalog/filter-by-products)

## User Permissions

Roles, access, verification.

[Video](https://www.youtube.com/watch?v=FoK1Wi75peE) | [Documentation](https://doc.oneentry.cloud/docs/category/users)

## User States

Persist user data: cart, favorites, browsing history, etc.

[Documentation](https://doc.oneentry.cloud/docs/category/users)

## Promotions

Reusable blocks for promotions based on Blocks logic.

[Video](https://www.youtube.com/watch?v=cQpyEi-S4Gw) | [Documentation](https://doc.oneentry.cloud/docs/blocks/create-similar-products-block)

## Recommended Products

Recommendation blocks (static or dynamic).

[Video](https://www.youtube.com/watch?v=cQpyEi-S4Gw) | [Documentation](https://doc.oneentry.cloud/docs/blocks/create-product-block)

## Orders

Full order management.

[Video](https://www.youtube.com/watch?v=1V1SMbkOQq0) | [Documentation](https://doc.oneentry.cloud/docs/category/orders)

## Payments

Payment processing.

[Video](https://www.youtube.com/watch?v=1V1SMbkOQq0) | [Documentation](https://doc.oneentry.cloud/docs/category/payments)

## Statuses

Status management for products, orders, and payments.

## Payment Services

Connect any payment gateways.

[Video](https://www.youtube.com/watch?v=4RX4TsJm-tc&pp=0gcJCRUKAYcqIYzv) | [Documentation](https://doc.oneentry.cloud/docs/integrations/paypal-example)

## Delivery Services

Connect any delivery provider.

[Video](https://www.youtube.com/watch?v=4RX4TsJm-tc&pp=0gcJCRUKAYcqIYzv) | [Documentation](https://doc.oneentry.cloud/docs/integrations/fedex-example)

## Grouping Products by Attributes

Group products by characteristics like color, model, etc.

[Video](https://www.youtube.com/watch?v=3OByJVOjWmI) | [Documentation](https://doc.oneentry.cloud/docs/catalog/product-links)

## Comments & Reviews

Collect and manage reviews via Forms.

[Documentation](https://doc.oneentry.cloud/docs/forms/create-form#4-Engagement-Forms)

## Discounts & Bonuses

Powered by Integration module with configurable low‑code logic.

## Catalog Import Tools

Upload from Excel, XML, CSV, folders, files.

[Video](https://www.youtube.com/watch?v=q9xj0Q630-g) | [Documentation](https://doc.oneentry.cloud/docs/category/catalog-upload)

## Integration

Low‑code tools to connect internal or external systems (ERP, CRM, inventory, accounting) and create custom API endpoints.

[Video](https://www.youtube.com/watch?v=4RX4TsJm-tc) | [Documentation](https://doc.oneentry.cloud/docs/category/integrations)

---

# In Development

-   Visual constructor for discounts & bonuses
-   Ratings system
-   “Customers also bought” product module
-   Export users/orders/payments to Excel & CSV
-   Content versioning
-   File manager
-   Direct export to Excel & CSV
-   MCP server

---

# Contact

Have questions or suggestions?  
We’re always happy to help — email us at:

**questions@oneentry.cloud**
