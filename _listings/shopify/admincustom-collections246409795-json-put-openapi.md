---
swagger: "2.0"
x-collection-name: Shopify
x-complete: 0
info:
  title: Shopify update a custom collection
  description: Update a custom collection.
  version: 1.0.0
host: DefaultParameterValue:DefaultParameterValue@DefaultParameterValue.myshopify.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /admin/custom_collections.json:
    get:
      summary: Get a list of all custom collections
      description: Get a list of all custom collections.
      operationId: getAdminCustomCollections.json
      x-api-path-slug: admincustom-collections-json-get
      parameters:
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - List
      - Custom
      - Collections
    post:
      summary: Create a new custom collection
      description: Create a new custom collection.
      operationId: postAdminCustomCollections.json
      x-api-path-slug: admincustom-collections-json-post
      parameters:
      - in: body
        name: Body
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - New
      - Custom
      - Collection
  /admin/script_tags/373484.json:
    get:
      summary: Get a single  script tag
      description: Get a single  script tag.
      operationId: getAdminScriptTags373484.json
      x-api-path-slug: adminscript-tags373484-json-get
      parameters:
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - Single
      - Script
      - Tag
  /admin/comments/2941387470.json:
    put:
      summary: Update a comment
      description: Update a comment.
      operationId: putAdminComments2941387470.json
      x-api-path-slug: admincomments2941387470-json-put
      parameters:
      - in: body
        name: Body
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - Comment
  /admin/smart_collections/401912846.json:
    get:
      summary: Get a single collection
      description: Get a single collection.
      operationId: getAdminSmartCollections401912846.json
      x-api-path-slug: adminsmart-collections401912846-json-get
      parameters:
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - Single
      - Collection
    put:
      summary: Update a single collection
      description: Update a single collection.
      operationId: putAdminSmartCollections401912846.json
      x-api-path-slug: adminsmart-collections401912846-json-put
      parameters:
      - in: body
        name: Body
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - Single
      - Collection
  /admin/products/9579007950.json:
    put:
      summary: Update a product and one of its variants
      description: Update a product and one of its variants.
      operationId: putAdminProducts9579007950.json
      x-api-path-slug: adminproducts9579007950-json-put
      parameters:
      - in: body
        name: Body
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - Product
      - Its
      - Variants
    delete:
      summary: Remove a product from the shop
      description: Remove a product from the shop.
      operationId: deleteAdminProducts9579007950.json
      x-api-path-slug: adminproducts9579007950-json-delete
      parameters:
      - in: body
        name: Body
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - Remove
      - Product
      - From
      - Shop
  /admin/orders/4554953422/refunds/calculate.json:
    post:
      summary: Calculate a refund for a line item and shipping
      description: Calculate a refund for a line item and shipping.
      operationId: postAdminOrders4554953422RefundsCalculate.json
      x-api-path-slug: adminorders4554953422refundscalculate-json-post
      parameters:
      - in: body
        name: Body
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - Calculate
      - Refunda
      - Line
      - Item
      - Shipping
  /admin/collects.json:
    get:
      summary: List all collects
      description: List all collects.
      operationId: getAdminCollects.json
      x-api-path-slug: admincollects-json-get
      parameters:
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - List
      - Collects
  /admin/blogs/62581763/articles.json:
    get:
      summary: Get a list of all articles from a certain blog
      description: Get a list of all articles from a certain blog.
      operationId: getAdminBlogs62581763Articles.json
      x-api-path-slug: adminblogs62581763articles-json-get
      parameters:
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - List
      - Articles
      - From
      - Certain
      - Blog
    post:
      summary: Create a new article for a blog
      description: Create a new article for a blog.
      operationId: postAdminBlogs62581763Articles.json
      x-api-path-slug: adminblogs62581763articles-json-post
      parameters:
      - in: body
        name: Body
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - New
      - Articlea
      - Blog
  /admin/metafields.json:
    get:
      summary: Get all metafields that belong to a store
      description: Get all metafields that belong to a store.
      operationId: getAdminMetafields.json
      x-api-path-slug: adminmetafields-json-get
      parameters:
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - Metafields
      - That
      - Belong
      - To
      - Store
    post:
      summary: Create a new metafield for a store.
      description: Create a new metafield for a store..
      operationId: postAdminMetafields.json
      x-api-path-slug: adminmetafields-json-post
      parameters:
      - in: body
        name: Body
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - New
      - Metafielda
      - Store
  /admin/gift_cards/61810574/disable.json:
    post:
      summary: Disable a gift card
      description: Disable a gift card.
      operationId: postAdminGiftCards61810574Disable.json
      x-api-path-slug: admingift-cards61810574disable-json-post
      parameters:
      - in: body
        name: Body
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - Disable
      - Gift
      - Card
  /admin/webhooks/503738446.json:
    put:
      summary: Update a Webhook
      description: Update a webhook.
      operationId: putAdminWebhooks503738446.json
      x-api-path-slug: adminwebhooks503738446-json-put
      parameters:
      - in: body
        name: Body
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - Webhook
    delete:
      summary: Delete a Webhook
      description: Delete a webhook.
      operationId: deleteAdminWebhooks503738446.json
      x-api-path-slug: adminwebhooks503738446-json-delete
      parameters:
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - Webhook
  /admin/blogs/62581763/articles/196805774.json:
    get:
      summary: Get a single article by its ID and the ID of the parent blog
      description: Get a single article by its id and the id of the parent blog.
      operationId: getAdminBlogs62581763Articles196805774.json
      x-api-path-slug: adminblogs62581763articles196805774-json-get
      parameters:
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - Single
      - Article
      - By
      - Its
      - ID
      - ID
      - Parent
      - Blog
    put:
      summary: Update an article
      description: Update an article.
      operationId: putAdminBlogs62581763Articles196805774.json
      x-api-path-slug: adminblogs62581763articles196805774-json-put
      parameters:
      - in: body
        name: Body
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - Article
  /admin/metafields/33145232974.json:
    get:
      summary: Get a single store metafield by ID
      description: Get a single store metafield by id.
      operationId: getAdminMetafields33145232974.json
      x-api-path-slug: adminmetafields33145232974-json-get
      parameters:
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - Single
      - Store
      - Metafield
      - By
      - ID
    put:
      summary: Update an existing store metafield.
      description: Update an existing store metafield..
      operationId: putAdminMetafields33145232974.json
      x-api-path-slug: adminmetafields33145232974-json-put
      parameters:
      - in: body
        name: Body
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - Existing
      - Store
      - Metafield
    delete:
      summary: Delete a store metafield
      description: Delete a store metafield.
      operationId: deleteAdminMetafields33145232974.json
      x-api-path-slug: adminmetafields33145232974-json-delete
      parameters:
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - Store
      - Metafield
  /admin/orders/4554953422/cancel.json:
    post:
      summary: Canceling an Order
      description: Canceling an order.
      operationId: postAdminOrders4554953422Cancel.json
      x-api-path-slug: adminorders4554953422cancel-json-post
      parameters:
      - in: body
        name: Body
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - Canceling
      - Order
  /admin/gift_cards/61466894.json:
    get:
      summary: Show a specific gift card's details
      description: Show a specific gift card's details.
      operationId: getAdminGiftCards61466894.json
      x-api-path-slug: admingift-cards61466894-json-get
      parameters:
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - Show
      - Specific
      - Gift
      - Cards
      - Details
  /admin/orders/4554953422/close.json:
    post:
      summary: Close a processed order
      description: Close a processed order.
      operationId: postAdminOrders4554953422Close.json
      x-api-path-slug: adminorders4554953422close-json-post
      parameters:
      - in: body
        name: Body
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - Close
      - Processed
      - Order
  /admin/orders/4602125518/risks.json:
    get:
      summary: Get all Order Risks for an Order
      description: Get all order risks for an order.
      operationId: getAdminOrders4602125518Risks.json
      x-api-path-slug: adminorders4602125518risks-json-get
      parameters:
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - Order
      - Risksan
      - Order
    post:
      summary: Add a fraud risk for Proxy detection
      description: Add a fraud risk for proxy detection.
      operationId: postAdminOrders4602125518Risks.json
      x-api-path-slug: adminorders4602125518risks-json-post
      parameters:
      - in: body
        name: Body
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - Fraud
      - RiskProxy
      - Detection
  /admin/blogs.json:
    get:
      summary: Get a list of all blogs
      description: Get a list of all blogs.
      operationId: getAdminBlogs.json
      x-api-path-slug: adminblogs-json-get
      parameters:
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - List
      - Blogs
    post:
      summary: Create a new blog
      description: Create a new blog.
      operationId: postAdminBlogs.json
      x-api-path-slug: adminblogs-json-post
      parameters:
      - in: body
        name: Body
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - New
      - Blog
  /admin/policies.json:
    get:
      summary: getting the shops policies
      description: Getting the shops policies.
      operationId: getAdminPolicies.json
      x-api-path-slug: adminpolicies-json-get
      parameters:
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - Getting
      - Shops
      - Policies
  /admin/orders/4554953422/events.json:
    get:
      summary: Get all the events from a particular order
      description: Get all the events from a particular order.
      operationId: getAdminOrders4554953422Events.json
      x-api-path-slug: adminorders4554953422events-json-get
      parameters:
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - Events
      - From
      - Particular
      - Order
  /admin/pages/count.json:
    get:
      summary: Count all pages for a shop
      description: Count all pages for a shop.
      operationId: getAdminPagesCount.json
      x-api-path-slug: adminpagescount-json-get
      parameters:
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - Count
      - Pagesa
      - Shop
  /admin/orders/4554953422/transactions/count.json:
    get:
      summary: Get a count of transactions for an order
      description: Get a count of transactions for an order.
      operationId: getAdminOrders4554953422TransactionsCount.json
      x-api-path-slug: adminorders4554953422transactionscount-json-get
      parameters:
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - Count
      - Transactionsan
      - Order
  /admin/gift_cards/count.json:
    get:
      summary: Retrieve a count of all gift cards
      description: Retrieve a count of all gift cards.
      operationId: getAdminGiftCardsCount.json
      x-api-path-slug: admingift-cardscount-json-get
      parameters:
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - Retrieve
      - Count
      - Gift
      - Cards
  /admin/countries.json:
    get:
      summary: Get a list of all countries
      description: Get a list of all countries.
      operationId: getAdminCountries.json
      x-api-path-slug: admincountries-json-get
      parameters:
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - List
      - Countries
    post:
      summary: Create a country
      description: Create a country.
      operationId: postAdminCountries.json
      x-api-path-slug: admincountries-json-post
      parameters:
      - in: body
        name: Body
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - Country
  /admin/fulfillment_services.json:
    get:
      summary: List your app's fulfillment services
      description: List your app's fulfillment services.
      operationId: getAdminFulfillmentServices.json
      x-api-path-slug: adminfulfillment-services-json-get
      parameters:
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - List
      - Your
      - Apps
      - Fulfillment
      - Services
    post:
      summary: Create a fulfillment service
      description: Create a fulfillment service.
      operationId: postAdminFulfillmentServices.json
      x-api-path-slug: adminfulfillment-services-json-post
      parameters:
      - in: body
        name: Body
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - Fulfillment
      - Service
  /admin/pages/216307854.json:
    put:
      summary: update a page
      description: Update a page.
      operationId: putAdminPages216307854.json
      x-api-path-slug: adminpages216307854-json-put
      parameters:
      - in: body
        name: Body
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - Update
      - Page
    delete:
      summary: Delete a page
      description: Delete a page.
      operationId: deleteAdminPages216307854.json
      x-api-path-slug: adminpages216307854-json-delete
      parameters:
      - in: body
        name: Body
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - Page
  /admin/customers/3989659651/addresses/5484465742.json:
    put:
      summary: Updating a customers postal code
      description: Updating a customers postal code.
      operationId: putAdminCustomers3989659651Addresses5484465742.json
      x-api-path-slug: admincustomers3989659651addresses5484465742-json-put
      parameters:
      - in: body
        name: Body
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - Updating
      - Customers
      - Postal
      - Code
    delete:
      summary: Removing a customers address
      description: Removing a customers address.
      operationId: deleteAdminCustomers3989659651Addresses5484465742.json
      x-api-path-slug: admincustomers3989659651addresses5484465742-json-delete
      parameters:
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - Removing
      - Customers
      - Address
  /admin/customers/search.json:
    get:
      summary: Get all customers with an address in the Brazil
      description: Get all customers with an address in the brazil.
      operationId: getAdminCustomersSearch.json
      x-api-path-slug: admincustomerssearch-json-get
      parameters:
      - in: header
        name: Content-Type
      - in: query
        name: query
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - Customers
      - Address
      - In
      - Brazil
  /admin/application_charges.json:
    get:
      summary: Retrieving all one-time charges since a specified ID
      description: Retrieving all one-time charges since a specified id.
      operationId: getAdminApplicationCharges.json
      x-api-path-slug: adminapplication-charges-json-get
      parameters:
      - in: header
        name: Content-Type
      - in: query
        name: since_id
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - Retrieving
      - One-time
      - Charges
      - Since
      - Specified
      - ID
    post:
      summary: Create a new one-time application charge.
      description: Create a new one-time application charge..
      operationId: postAdminApplicationCharges.json
      x-api-path-slug: adminapplication-charges-json-post
      parameters:
      - in: body
        name: Body
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - New
      - One-time
      - Application
      - Charge
  /admin/blogs/62581763/articles/count.json:
    get:
      summary: Get a count of all articles from a certain blog
      description: Get a count of all articles from a certain blog.
      operationId: getAdminBlogs62581763ArticlesCount.json
      x-api-path-slug: adminblogs62581763articlescount-json-get
      parameters:
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - Count
      - Articles
      - From
      - Certain
      - Blog
  /admin/metafields/count.json:
    get:
      summary: Get a count of all metafields for a store
      description: Get a count of all metafields for a store.
      operationId: getAdminMetafieldsCount.json
      x-api-path-slug: adminmetafieldscount-json-get
      parameters:
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - Count
      - Metafieldsa
      - Store
  /admin/custom_collections/246409795.json:
    get:
      summary: Get a single custom collections
      description: Get a single custom collections.
      operationId: getAdminCustomCollections246409795.json
      x-api-path-slug: admincustom-collections246409795-json-get
      parameters:
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - Single
      - Custom
      - Collections
    put:
      summary: update a custom collection
      description: Update a custom collection.
      operationId: putAdminCustomCollections246409795.json
      x-api-path-slug: admincustom-collections246409795-json-put
      parameters:
      - in: body
        name: Body
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - Update
      - Custom
      - Collection
x-streamrank:
  polling_total_time_average: 0
  polling_size_download_average: 0
  streaming_total_time_average: 0
  streaming_size_download_average: 0
  change_yes: 0
  change_no: 0
  time_percentage: 0
  size_percentage: 0
  change_percentage: 0
  last_run: ""
  days_run: 0
  minute_run: 0
---