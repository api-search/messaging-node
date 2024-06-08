---
name: Postmark
description: >-
  Postmark helps deliver and track application email. In a nutshell, the service
  replaces SMTP (or Sendmail) with a far more reliable, scalable and care-free
  environment. In addition, you can track statistics such as number of emails
  sent or processed, opens, bounces and spam complaints.
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
url: https://raw.githubusercontent.com/apis-json/artisanal/main/apis/postmark.yml
created: 2023-11-15
modified: 2024-06-07
specificationVersion: '0.18'
tags: []
apis:
  - name: Postmark Server API
    description: >-
      Postmark helps deliver and track application email. In a nutshell, the service replaces SMTP (or Sendmail) with a far more reliable, scalable and care-free environment. In addition, you can track statistics such as number of emails sent or processed, opens, bounces and spam complaints.
    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
    humanURL: https://postmarkapp.com/api-explorer?api-type=server
    baseURL: https://api.example.com
    tags: []
    properties:
      - type: Documentation
        url: https://postmarkapp.com/api-explorer?api-type=server
      - type: OpenAPI
        url: properties/postmark-server-openapi-original.yml
    aid: postmark:postmark-server-api
  - name: Postmark Account API
    description: >-
      Postmark makes sending and receiving email incredibly easy. The Account-level API allows users to configure all Servers, Domains, and Sender Signatures associated with an Account.
    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
    humanURL: https://postmarkapp.com/api-explorer?api-type=account
    baseURL: https://api.example.com
    tags: []
    properties:
      - type: Documentation
        url: https://postmarkapp.com/api-explorer?api-type=account
      - type: OpenAPI
        url: example/postmark-account-openapi-original.yml
    aid: postmark:postmark-account-api    
common:
  - type: Support
    url: https://postmarkapp.com/support
  - type: Blog
    url: https://postmarkapp.com/blog
  - type: Getting Started
    url: https://postmarkapp.com/manual
  - type: Videos
    url: https://postmarkapp.com/videos
  - type: Webinars
    url: https://postmarkapp.com/webinars
  - type: Labs
    url: https://postmarkapp.com/labs
  - type: Newsletter
    url: https://postmarkapp.com/newsletter
  - type: Glossary
    url: https://postmarkapp.com/glossary
  - type: Terms of Servivce
    url: https://postmarkapp.com/terms-of-service
  - type: Privacy Policy
    url: https://postmarkapp.com/privacy-policy
  - type: Plans
    url: https://postmarkapp.com/pricing
  - type: Sign UP
    url: https://account.postmarkapp.com/sign_up
maintainers:
  - FN: API Evangelist
    url: http://apievangelist.com
    email: info@apievangelist.com
overlays:
  - type: APIs.io Search
    url: overlays/apis-io-search.yml
aid: postmark
---