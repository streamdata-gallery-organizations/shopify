---
swagger: "2.0"
x-collection-name: Shopify
x-complete: 0
info:
  title: Shopify Calculate a refund for a line item and shipping
  description: Calculate a refund for a line item and shipping.
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