swagger: "2.0"
x-collection-name: Plentymarkets
x-complete: 1
info:
  title: plentymarkets REST-API
  description: the-plentymarkets-rest-api-expands-the-functionality-of-the-plentymarkets-cms-and-allows-access-to-resources-i-e--data-records-via-unique-uri-paths
  contact:
    name: plentymarkets
    url: https://forum.plentymarkets.com/c/rest-api
  version: 1.0.0
host: example.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /rest/shop_builder/content_links:
    post:
      summary: Link a content to a a layout container of a frontend plugin.
      description: Link a content to a a layout container of a frontend plugin..
      operationId: postRestShopBuilderContentLinks
      x-api-path-slug: restshop-buildercontent-links-post
      parameters:
      - in: body
        name: /rest/shop_builder/content_links
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Link
      - Content
      - To
      - A
      - Layout
      - Container
      - Of
      - Frontend
      - Plugin