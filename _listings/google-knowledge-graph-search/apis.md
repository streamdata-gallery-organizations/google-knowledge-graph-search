---
name: Google Knowledge Graph Search
x-slug: google-knowledge-graph-search
description: 'The Knowledge Graph Search API lets you find entities in the Google
  Knowledge Graph. The API uses standard schema.org types and is compliant with the
  JSON-LD specification. Some examples of how you can use the Knowledge Graph Search
  API include: Getting a ranked list of the most notable entities that match certain
  criteria. Predictively completing entities in a search box. Annotating/organizing
  content using the Knowledge Graph entities.'
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google-Knowledge-Graph.jpg
x-kinRank: "9"
x-alexaRank: "0"
tags: Google Knowledge Graph Search
created: "2018-08-30"
modified: "2018-08-30"
url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-knowledge-graph-search/master/_listings/google-knowledge-graph-search/apis.md
specificationVersion: "0.14"
apis:
- name: Knowledge Graph Search - Search Knowledge Graph
  x-api-slug: v1entitiessearch-get
  description: |-
    Searches Knowledge Graph for entities that match the constraints.
    A list of matched entities will be returned in response, which will be in
    JSON-LD format and compatible with http://schema.org
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google-Knowledge-Graph.jpg
  humanURL: https://developers.google.com/knowledge-graph/
  baseURL: ://kgsearch.googleapis.com//
  tags: Search, Google APIs, Stack Network, API Service Provider, API Provider, Profiles,
    Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-knowledge-graph-search/master/_listings/google-knowledge-graph-search/v1entitiessearch-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-knowledge-graph-search/master/_listings/google-knowledge-graph-search/v1entitiessearch-get-openapi.md
x-common:
- type: x-api-gallery
  url: http://google.glass.api.gallery.streamdata.io
- type: x-api-stack
  url: http://google.knowledge.graph.search.stack.network
- type: x-authentication
  url: https://developers.google.com/knowledge-graph/how-tos/authorizing
- type: x-code
  url: https://developers.google.com/knowledge-graph/libraries
- type: x-rate-limits
  url: https://developers.google.com/knowledge-graph/reference/rest/v1/usage-limits
- type: x-terms-of-service
  url: https://developers.google.com/knowledge-graph/terms
- type: x-website
  url: https://developers.google.com/knowledge-graph/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---