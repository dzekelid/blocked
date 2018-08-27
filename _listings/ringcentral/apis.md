---
name: RingCentral
x-slug: ringcentral
description: 'RingCentral, Inc. (NYSE: RNG) is a global provider of cloud enterprise
  unified communications and collaboration solutions. More flexible and cost-effective
  than legacy on-premise systems, RingCentral empowers today&rsquo;s mobile and distributed
  workforces to be connected anywhere and on any device through voice, video, team
  messaging, collaboration, SMS, conferencing, online meetings, contact center, and
  fax. RingCentral provides an open platform that integrates with today&rsquo;s leading
  business apps while giving customers the flexibility to customize their own workflows.'
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
x-kinRank: "7"
x-alexaRank: "7180"
tags: Blocked
created: "2018-08-27"
modified: "2018-08-27"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/blocked/master/_listings/ringcentral/apis.md
specificationVersion: "0.14"
apis:
- name: RingCentral Connect Platform API Explorer - Get Blocked Numbers
  x-api-slug: restapiv1-0accountaccountidextensionextensionidblockednumber-get
  description: "Returns the list of phone numbers which are specified by the user
    to block inbound calls and SMS messages.\nApp Permission\nReadAccounts\nUser Permission\nReadBlockedNumbers\nUsage
    Plan Group\nLight\nError Codes\n\n \n  \n   HTTP Code\n   Error Code\n   Error
    Message\n   \n \n\n400\nCMN-101\nParameter [perPage] value is invalid\n\n\n401\nCMN-405\nLogin
    to extension required\n\n\n401\nOAU-151\nAuthorization method not supported\n\n\n403\nCMN-401\nIn
    order to call this API endpoint, application needs to have [ReadAccounts] permission\n\n\n403\nCMN-408\nIn
    order to call this API endpoint, user needs to have [ReadBlockedNumbers] permission
    for requested resource.\n\n\n404\nCMN-102\nResource for parameter [extensionId]
    is not found"
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/blocked/master/_listings/ringcentral/restapiv1-0accountaccountidextensionextensionidblockednumber-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/blocked/master/_listings/ringcentral/restapiv1-0accountaccountidextensionextensionidblockednumber-get-openapi.md
- name: RingCentral Connect Platform API Explorer - Add Blocked Numbers
  x-api-slug: restapiv1-0accountaccountidextensionextensionidblockednumber-post
  description: "Adds a new phone number to the blocked number list.\nApp Permission\nEditExtensions\nUser
    Permission\nEditBlockedNumbers\nUsage Plan Group\nMedium\nError Codes\n\n \n  \n
    \  HTTP Code\n   Error Code\n   Error Message\n   \n \n\n400\nCMN-101\nParameter
    [phoneNumber] value is invalid\n\n\n403\nCMN-401\nIn order to call this API endpoint,
    application needs to have [EditExtensions] permission\n\n\n403\nCMN-408\nIn order
    to call this API endpoint, user needs to have [EditBlockedNumbers] permission
    for requested resource.\n\n\n404\nCMN-102\nResource for parameter [extensionId]
    is not found"
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/blocked/master/_listings/ringcentral/restapiv1-0accountaccountidextensionextensionidblockednumber-post-openapi.md
- name: RingCentral Connect Platform API Explorer - Get Blocked Number
  x-api-slug: restapiv1-0accountaccountidextensionextensionidblockednumberblockednumberid-get
  description: "Returns specific information on blocked phone number(s) by their ID(s).
    Batch request is supported.\nApp Permission\nReadAccounts\nUser Permission\nReadBlockedNumbers\nUsage
    Plan Group\nLight\nError Codes\n\n \n  \n   HTTP Code\n   Error Code\n   Error
    Message\n   \n \n\n403\nCMN-401\nIn order to call this API endpoint, application
    needs to have [ReadAccounts] permission\n\n\n403\nCMN-408\nIn order to call this
    API endpoint, user needs to have [ReadBlockedNumbers] permission for requested
    resource.\n\n\n404\nCMN-102\nResource for parameter [accountId] is not found"
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/blocked/master/_listings/ringcentral/restapiv1-0accountaccountidextensionextensionidblockednumberblockednumberid-get-openapi.md
- name: RingCentral Connect Platform API Explorer - Update Blocked Number
  x-api-slug: restapiv1-0accountaccountidextensionextensionidblockednumberblockednumberid-put
  description: "Updates blocked number(s) by their ID(s). Currently only the name
    can be updated. Batch request is supported.\nApp Permission\nEditExtensions\nUser
    Permission\nEditBlockedNumbers\nUsage Plan Group\nMedium\nError Codes\n\n \n  \n
    \  HTTP Code\n   Error Code\n   Error Message\n   \n \n\n400\nCMN-101\nParameter
    [] value is invalid\n\n\n403\nCMN-401\nIn order to call this API endpoint, application
    needs to have [EditExtensions] permission\n\n\n403\nCMN-408\nIn order to call
    this API endpoint, user needs to have [EditBlockedNumbers] permission for requested
    resource.\n\n\n404\nCMN-102\nResource for parameter [extensionId] is not found"
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/blocked/master/_listings/ringcentral/restapiv1-0accountaccountidextensionextensionidblockednumberblockednumberid-put-openapi.md
- name: RingCentral Connect Platform API Explorer - Delete Blocked Number
  x-api-slug: restapiv1-0accountaccountidextensionextensionidblockednumberblockednumberid-delete
  description: "Deletes a phone number from the blocked number list. Batch request
    is supported.\nApp Permission\nEditExtensions\nUser Permission\nEditBlockedNumbers\nUsage
    Plan Group\nMedium\nError Codes\n\n \n  \n   HTTP Code\n   Error Code\n   Error
    Message\n   \n \n\n403\nCMN-401\nIn order to call this API endpoint, application
    needs to have [EditExtensions] permission\n\n\n403\nCMN-408\nIn order to call
    this API endpoint, user needs to have [EditBlockedNumbers] permission for requested
    resource.\n\n\n404\nCMN-102\nResource for parameter [extensionId] is not found"
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/blocked/master/_listings/ringcentral/restapiv1-0accountaccountidextensionextensionidblockednumberblockednumberid-delete-openapi.md
- name: RingCentral Connect Platform API Explorer - Get Blocked Numbers
  x-api-slug: restapiv1-0accountaccountidextensionextensionidcallerblockingphonenumbers-get
  description: "Returns the lists of blocked and allowed phone numbers.\nApp Permission\nReadAccounts\nUser
    Permission\nReadBlockedNumbers\nUsage Plan Group\nLight\nError Codes\n\n \n  \n
    \  HTTP Code\n   Error Code\n   Error Message\n   \n \n\n404\nCMN-102\nResource
    for parameter [accountId] is not found"
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/blocked/master/_listings/ringcentral/restapiv1-0accountaccountidextensionextensionidcallerblockingphonenumbers-get-openapi.md
- name: RingCentral Connect Platform API Explorer - Add Blocked Number
  x-api-slug: restapiv1-0accountaccountidextensionextensionidcallerblockingphonenumbers-post
  description: |-
    Updates either blocked or allowed phone number list with a new phone number.
    App Permission
    EditExtensions
    User Permission
    EditBlockedNumbers
    Usage Plan Group
    Medium
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/blocked/master/_listings/ringcentral/restapiv1-0accountaccountidextensionextensionidcallerblockingphonenumbers-post-openapi.md
- name: RingCentral Connect Platform API Explorer - Get Blocked Number
  x-api-slug: restapiv1-0accountaccountidextensionextensionidcallerblockingphonenumbersblockednumberid-get
  description: "Returns blocked or allowed phone number(s) by their ID(s). Batch request
    is supported.\nApp Permission\nReadAccounts\nUser Permission\nReadBlockedNumbers\nUsage
    Plan Group\nLight\nError Codes\n\n \n  \n   HTTP Code\n   Error Code\n   Error
    Message\n   \n \n\n404\nCMN-102\nResource for parameter [accountId] is not found"
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/blocked/master/_listings/ringcentral/restapiv1-0accountaccountidextensionextensionidcallerblockingphonenumbersblockednumberid-get-openapi.md
- name: RingCentral Connect Platform API Explorer - Delete Blocked Number
  x-api-slug: restapiv1-0accountaccountidextensionextensionidcallerblockingphonenumbersblockednumberid-delete
  description: |-
    Deletes blocked or allowed phone number(s) by their ID(s). Batch request is supported.
    App Permission
    EditExtensions
    User Permission
    EditBlockedNumbers
    Usage Plan Group
    Medium
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/blocked/master/_listings/ringcentral/restapiv1-0accountaccountidextensionextensionidcallerblockingphonenumbersblockednumberid-delete-openapi.md
- name: RingCentral Connect Platform API Explorer - Update Blocked Number
  x-api-slug: restapiv1-0accountaccountidextensionextensionidcallerblockingphonenumbersblockednumberid-put
  description: |-
    Updates blocked or allowed phone number(s) by their ID(s). Batch request is supported.
    App Permission
    EditExtensions
    User Permission
    EditBlockedNumbers
    Usage Plan Group
    Medium
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/blocked/master/_listings/ringcentral/restapiv1-0accountaccountidextensionextensionidcallerblockingphonenumbersblockednumberid-put-openapi.md
x-common:
- type: x-blog
  url: https://medium.com/ringcentral-developers
- type: x-blog-rss
  url: https://medium.com/feed/ringcentral-developers
- type: x-github
  url: https://github.com/ringcentral
- type: x-openapi
  url: https://netstorage.ringcentral.com/dpw/api-explorer/swagger-ring_basic.yml?v=20180816
- type: x-website
  url: http://www.ringcentral.com
- type: x-api-gallery
  url: http://reverb.api.gallery.streamdata.io
- type: x-api-stack
  url: http://ringcentral.stack.network
- type: x-code
  url: https://developer.ringcentral.com/library/sdks.html
- type: x-crunchbase
  url: https://crunchbase.com/organization/ringcentral
- type: x-developer
  url: https://developer.ringcentral.com/
- type: x-documentation
  url: https://developer.ringcentral.com/api-explorer/latest/index.html?_ga=2.259782990.551967760.1534465156-1236351744.1533920460
- type: x-support
  url: https://developer.ringcentral.com/support.html
- type: x-twitter
  url: https://twitter.com/RingCentral
- type: x-website
  url: https://developer.ringcentral.com
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---