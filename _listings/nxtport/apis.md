---
name: NxtPort
x-slug: nxtport
description: NxtPort opens the gates to the Port of the future. This project is a
  milestone in the digitalization of logistics and cargo.
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28835-www-nxtport-eu.jpg
x-kinRank: "7"
x-alexaRank: "3933231"
tags: Shipping
created: "2018-08-28"
modified: "2018-08-28"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/shipping/master/_listings/nxtport/apis.md
specificationVersion: "0.14"
apis:
- name: Vessel Stay API (live) - Get Stay
  x-api-slug: staysimonumber-get
  description: Get a single stay by IMO number.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28835-www-nxtport-eu.jpg
  humanURL: https://www.nxtport.eu
  baseURL: https://api.nxtport.eu//sa/v1
  tags: Technology, SaaS, Enterprise, Shipping, Data, General Data, Relative Data,
    Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/shipping/master/_listings/nxtport/staysimonumber-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/shipping/master/_listings/nxtport/staysimonumber-get-openapi.md
- name: VGM API (live) - Get VERMAS Files
  x-api-slug: nxtportdocumentbookingnumbercontainernumber-get
  description: Returns the VERMAS files with the according booking number and container
    number
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28835-www-nxtport-eu.jpg
  humanURL: https://www.nxtport.eu
  baseURL: https://api.nxtport.eu//VGM/v1
  tags: Technology, SaaS, Enterprise, Shipping, Data, General Data, Relative Data,
    Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/shipping/master/_listings/nxtport/nxtportdocumentbookingnumbercontainernumber-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/shipping/master/_listings/nxtport/nxtportdocumentbookingnumbercontainernumber-get-openapi.md
- name: Portcall+ API (sandbox) - Get Expected Vessels
  x-api-slug: vesselsexpected-get
  description: Get all the expected vessels of BEANR and BEZEE
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28835-www-nxtport-eu.jpg
  humanURL: https://www.nxtport.eu
  baseURL: https://api-sb.nxtport.eu//PortCallPlus/v1
  tags: Technology, SaaS, Enterprise, Shipping, Data, General Data, Relative Data,
    Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/shipping/master/_listings/nxtport/vesselsexpected-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/shipping/master/_listings/nxtport/vesselsexpected-get-openapi.md
- name: Portcall+ API (sandbox) - Get Vessels In Port
  x-api-slug: vesselsinport-get
  description: Get all the in-port vessels of BEANR and BEZEE
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28835-www-nxtport-eu.jpg
  humanURL: https://www.nxtport.eu
  baseURL: https://api-sb.nxtport.eu//PortCallPlus/v1
  tags: Technology, SaaS, Enterprise, Shipping, Data, General Data, Relative Data,
    Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/shipping/master/_listings/nxtport/vesselsinport-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/shipping/master/_listings/nxtport/vesselsinport-get-openapi.md
x-common:
- type: x-api-gallery
  url: http://npr.api.gallery.streamdata.io
- type: x-api-stack
  url: http://nxtport.stack.network
- type: x-email
  url: mail@nxtport.eu
- type: x-email
  url: development@nxtport.eu
- type: x-email
  url: privacy@nxtport.eu
- type: x-github
  url: https://github.com/NxtPort
- type: x-openapi
  url: https://github.com/NxtPort/nxtport.github.io/tree/master/api
- type: x-twitter
  url: https://twitter.com/NxtPortNews
- type: x-website
  url: https://www.nxtport.eu
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---