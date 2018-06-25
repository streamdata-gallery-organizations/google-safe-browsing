---
name: Google Safe Browsing
x-slug: google-safe-browsing
description: The Safe Browsing APIs (v4) let your client applications check URLs against
  Googles constantly updated lists of unsafe web resources. Examples of unsafe web
  resources are social engineering sites (phishing and deceptive sites) and sites
  that host malware or unwanted software. Any URL found on a Safe Browsing list is
  considered unsafe.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/SafeBrowsing_Icon.png
x-kinRank: "9"
x-alexaRank: "0"
tags: Google Safe Browsing
created: "2018-06-25"
modified: "2018-06-25"
url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-safe-browsing/master/_listings/google-safe-browsing/apis.md
specificationVersion: "0.14"
apis:
- name: Google Safe Browsing API Encode Full Hashes
  x-api-slug: google-safe-browsing-api
  description: Encode Full Hashes
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/SafeBrowsing_Icon.png
  humanURL: https://developers.google.com/safe-browsing/
  baseURL: ://safebrowsing.googleapis.com////v4/encodedFullHashes/{encodedRequest}
  tags: Hash
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-safe-browsing/master/_listings/google-safe-browsing/v4encodedfullhashesencodedrequest-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-safe-browsing/master/_listings/google-safe-browsing/v4encodedfullhashesencodedrequest-get-openapi.md
- name: Google Safe Browsing API Encoded Updates
  x-api-slug: google-safe-browsing-api
  description: Encoded Updates
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/SafeBrowsing_Icon.png
  humanURL: https://developers.google.com/safe-browsing/
  baseURL: ://safebrowsing.googleapis.com////v4/encodedUpdates/{encodedRequest}
  tags: Updates
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-safe-browsing/master/_listings/google-safe-browsing/v4encodedupdatesencodedrequest-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-safe-browsing/master/_listings/google-safe-browsing/v4encodedupdatesencodedrequest-get-openapi.md
- name: Google Safe Browsing API Find Full Hash Match
  x-api-slug: google-safe-browsing-api
  description: Finds the full hashes that match the requested hash prefixes.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/SafeBrowsing_Icon.png
  humanURL: https://developers.google.com/safe-browsing/
  baseURL: ://safebrowsing.googleapis.com////v4/fullHashes:find
  tags: Hash
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-safe-browsing/master/_listings/google-safe-browsing/v4fullhashesfind-post-openapi.md
- name: Google Safe Browsing API List Most Recent Threats
  x-api-slug: google-safe-browsing-api
  description: |-
    Fetches the most recent threat list updates. A client can request updates
    for multiple lists at once.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/SafeBrowsing_Icon.png
  humanURL: https://developers.google.com/safe-browsing/
  baseURL: ://safebrowsing.googleapis.com////v4/threatListUpdates:fetch
  tags: Threats
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-safe-browsing/master/_listings/google-safe-browsing/v4threatlistupdatesfetch-post-openapi.md
- name: Google Safe Browsing API List Threats
  x-api-slug: google-safe-browsing-api
  description: Lists the Safe Browsing threat lists available for download.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/SafeBrowsing_Icon.png
  humanURL: https://developers.google.com/safe-browsing/
  baseURL: ://safebrowsing.googleapis.com////v4/threatLists
  tags: Threats
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-safe-browsing/master/_listings/google-safe-browsing/v4threatlists-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-safe-browsing/master/_listings/google-safe-browsing/v4threatlists-get-openapi.md
- name: Google Safe Browsing API Find Threat Entry
  x-api-slug: google-safe-browsing-api
  description: Finds the threat entries that match the Safe Browsing lists.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/SafeBrowsing_Icon.png
  humanURL: https://developers.google.com/safe-browsing/
  baseURL: ://safebrowsing.googleapis.com////v4/threatMatches:find
  tags: Threats
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-safe-browsing/master/_listings/google-safe-browsing/v4threatmatchesfind-post-openapi.md
- name: Google Safe Browsing API
  x-api-slug: google-safe-browsing-api
  description: The Safe Browsing APIs (v4) let your client applications check URLs
    against Googles constantly updated lists of unsafe web resources. Examples of
    unsafe web resources are social engineering sites (phishing and deceptive sites)
    and sites that host malware or unwanted software. Any URL found on a Safe Browsing
    list is considered unsafe.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/SafeBrowsing_Icon.png
  humanURL: https://developers.google.com/safe-browsing/
  baseURL: ://safebrowsing.googleapis.com//
  tags: Google Safe Browsing
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-safe-browsing/master/_listings/google-safe-browsing/openapi.md
x-common:
- type: x-documentation
  url: https://developers.google.com/safe-browsing/v4/
- type: x-forum
  url: http://groups.google.com/group/google-safe-browsing-api
- type: x-getting-started
  url: https://developers.google.com/safe-browsing/v4/get-started
- type: x-website
  url: https://developers.google.com/safe-browsing/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---