---
name: Google Tag Manager
x-slug: google-tag-manager
description: Deploy and update measurement tags on your websites and mobile apps without
  major code changes and app releases. Use Google Tag Manager to manage tags (such
  as tracking and marketing optimization JavaScript tags) on your site. Without editing
  your site code, you use GTM user interface to add and update AdWords, Google Analytics,
  Floodlight, and non-Google tags. This reduces errors and allows you to to deploy
  tags on your site quickly.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/googl_tag_manager_gplus-250.png
x-kinRank: "9"
x-alexaRank: "0"
tags: Containers
created: "2018-08-27"
modified: "2018-08-27"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/containers/master/_listings/google-tag-manager/apis.md
specificationVersion: "0.14"
apis:
- name: Tag Manager - Get Container Versions
  x-api-slug: accountsaccountidcontainerscontaineridversions-get
  description: Lists all Container Versions of a GTM Container.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/googl_tag_manager_gplus-250.png
  humanURL: https://developers.google.com/tag-manager/
  baseURL: ://www.googleapis.com//tagmanager/v1
  tags: Google APIs, Tags, Stack Network, API Service Provider, API Provider, Profiles,
    Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/containers/master/_listings/google-tag-manager/accountsaccountidcontainerscontaineridversions-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/containers/master/_listings/google-tag-manager/accountsaccountidcontainerscontaineridversions-get-openapi.md
- name: Tag Manager - Create Container Version
  x-api-slug: accountsaccountidcontainerscontaineridversions-post
  description: Creates a Container Version.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/googl_tag_manager_gplus-250.png
  humanURL: https://developers.google.com/tag-manager/
  baseURL: ://www.googleapis.com//tagmanager/v1
  tags: Google APIs, Tags, Stack Network, API Service Provider, API Provider, Profiles,
    Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/containers/master/_listings/google-tag-manager/accountsaccountidcontainerscontaineridversions-post-openapi.md
- name: Tag Manager - Delete Container Version
  x-api-slug: accountsaccountidcontainerscontaineridversionscontainerversionid-delete
  description: Deletes a Container Version.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/googl_tag_manager_gplus-250.png
  humanURL: https://developers.google.com/tag-manager/
  baseURL: ://www.googleapis.com//tagmanager/v1
  tags: Google APIs, Tags, Stack Network, API Service Provider, API Provider, Profiles,
    Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/containers/master/_listings/google-tag-manager/accountsaccountidcontainerscontaineridversionscontainerversionid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/containers/master/_listings/google-tag-manager/accountsaccountidcontainerscontaineridversionscontainerversionid-delete-openapi.md
- name: Tag Manager - Get Container Version
  x-api-slug: accountsaccountidcontainerscontaineridversionscontainerversionid-get
  description: Gets a Container Version.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/googl_tag_manager_gplus-250.png
  humanURL: https://developers.google.com/tag-manager/
  baseURL: ://www.googleapis.com//tagmanager/v1
  tags: Google APIs, Tags, Stack Network, API Service Provider, API Provider, Profiles,
    Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/containers/master/_listings/google-tag-manager/accountsaccountidcontainerscontaineridversionscontainerversionid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/containers/master/_listings/google-tag-manager/accountsaccountidcontainerscontaineridversionscontainerversionid-get-openapi.md
- name: Tag Manager - Update Container Version
  x-api-slug: accountsaccountidcontainerscontaineridversionscontainerversionid-put
  description: Updates a Container Version.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/googl_tag_manager_gplus-250.png
  humanURL: https://developers.google.com/tag-manager/
  baseURL: ://www.googleapis.com//tagmanager/v1
  tags: Google APIs, Tags, Stack Network, API Service Provider, API Provider, Profiles,
    Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/containers/master/_listings/google-tag-manager/accountsaccountidcontainerscontaineridversionscontainerversionid-put-openapi.md
- name: Tag Manager - Publish Container Version
  x-api-slug: accountsaccountidcontainerscontaineridversionscontainerversionidpublish-post
  description: Publishes a Container Version.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/googl_tag_manager_gplus-250.png
  humanURL: https://developers.google.com/tag-manager/
  baseURL: ://www.googleapis.com//tagmanager/v1
  tags: Google APIs, Tags, Stack Network, API Service Provider, API Provider, Profiles,
    Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/containers/master/_listings/google-tag-manager/accountsaccountidcontainerscontaineridversionscontainerversionidpublish-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/containers/master/_listings/google-tag-manager/accountsaccountidcontainerscontaineridversionscontainerversionidpublish-post-openapi.md
- name: Tag Manager - Restore Container Version
  x-api-slug: accountsaccountidcontainerscontaineridversionscontainerversionidrestore-post
  description: Restores a Container Version. This will overwrite the container's current
    configuration (including its variables, triggers and tags). The operation will
    not have any effect on the version that is being served (i.e. the published version).
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/googl_tag_manager_gplus-250.png
  humanURL: https://developers.google.com/tag-manager/
  baseURL: ://www.googleapis.com//tagmanager/v1
  tags: Google APIs, Tags, Stack Network, API Service Provider, API Provider, Profiles,
    Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/containers/master/_listings/google-tag-manager/accountsaccountidcontainerscontaineridversionscontainerversionidrestore-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/containers/master/_listings/google-tag-manager/accountsaccountidcontainerscontaineridversionscontainerversionidrestore-post-openapi.md
- name: Tag Manager - Undelete Container Version
  x-api-slug: accountsaccountidcontainerscontaineridversionscontainerversionidundelete-post
  description: Undeletes a Container Version.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/googl_tag_manager_gplus-250.png
  humanURL: https://developers.google.com/tag-manager/
  baseURL: ://www.googleapis.com//tagmanager/v1
  tags: Google APIs, Tags, Stack Network, API Service Provider, API Provider, Profiles,
    Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/containers/master/_listings/google-tag-manager/accountsaccountidcontainerscontaineridversionscontainerversionidundelete-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/containers/master/_listings/google-tag-manager/accountsaccountidcontainerscontaineridversionscontainerversionidundelete-post-openapi.md
- name: Tag Manager - Get Conainers
  x-api-slug: accountsaccountidcontainers-get
  description: Lists all Containers that belongs to a GTM Account.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/googl_tag_manager_gplus-250.png
  humanURL: https://developers.google.com/tag-manager/
  baseURL: ://www.googleapis.com//tagmanager/v1
  tags: Google APIs, Tags, Stack Network, API Service Provider, API Provider, Profiles,
    Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/containers/master/_listings/google-tag-manager/accountsaccountidcontainers-get-openapi.md
- name: Tag Manager - Create Container
  x-api-slug: accountsaccountidcontainers-post
  description: Creates a Container.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/googl_tag_manager_gplus-250.png
  humanURL: https://developers.google.com/tag-manager/
  baseURL: ://www.googleapis.com//tagmanager/v1
  tags: Google APIs, Tags, Stack Network, API Service Provider, API Provider, Profiles,
    Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/containers/master/_listings/google-tag-manager/accountsaccountidcontainers-post-openapi.md
- name: Tag Manager - Delete Container
  x-api-slug: accountsaccountidcontainerscontainerid-delete
  description: Deletes a Container.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/googl_tag_manager_gplus-250.png
  humanURL: https://developers.google.com/tag-manager/
  baseURL: ://www.googleapis.com//tagmanager/v1
  tags: Google APIs, Tags, Stack Network, API Service Provider, API Provider, Profiles,
    Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/containers/master/_listings/google-tag-manager/accountsaccountidcontainerscontainerid-delete-openapi.md
- name: Tag Manager - Get Container
  x-api-slug: accountsaccountidcontainerscontainerid-get
  description: Gets a Container.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/googl_tag_manager_gplus-250.png
  humanURL: https://developers.google.com/tag-manager/
  baseURL: ://www.googleapis.com//tagmanager/v1
  tags: Google APIs, Tags, Stack Network, API Service Provider, API Provider, Profiles,
    Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/containers/master/_listings/google-tag-manager/accountsaccountidcontainerscontainerid-get-openapi.md
- name: Tag Manager - Update Container
  x-api-slug: accountsaccountidcontainerscontainerid-put
  description: Updates a Container.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/googl_tag_manager_gplus-250.png
  humanURL: https://developers.google.com/tag-manager/
  baseURL: ://www.googleapis.com//tagmanager/v1
  tags: Google APIs, Tags, Stack Network, API Service Provider, API Provider, Profiles,
    Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/containers/master/_listings/google-tag-manager/accountsaccountidcontainerscontainerid-put-openapi.md
- name: Tag Manager - Get Conainers
  x-api-slug: accountsaccountidcontainers-get
  description: Lists all Containers that belongs to a GTM Account.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/googl_tag_manager_gplus-250.png
  humanURL: https://developers.google.com/tag-manager/
  baseURL: ://www.googleapis.com//tagmanager/v1
  tags: Google APIs, Tags, Stack Network, API Service Provider, API Provider, Profiles,
    Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/containers/master/_listings/google-tag-manager/accountsaccountidcontainers-get-openapi.md
- name: Tag Manager - Create Container
  x-api-slug: accountsaccountidcontainers-post
  description: Creates a Container.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/googl_tag_manager_gplus-250.png
  humanURL: https://developers.google.com/tag-manager/
  baseURL: ://www.googleapis.com//tagmanager/v1
  tags: Google APIs, Tags, Stack Network, API Service Provider, API Provider, Profiles,
    Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/containers/master/_listings/google-tag-manager/accountsaccountidcontainers-post-openapi.md
- name: Tag Manager - Delete Container
  x-api-slug: accountsaccountidcontainerscontainerid-delete
  description: Deletes a Container.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/googl_tag_manager_gplus-250.png
  humanURL: https://developers.google.com/tag-manager/
  baseURL: ://www.googleapis.com//tagmanager/v1
  tags: Google APIs, Tags, Stack Network, API Service Provider, API Provider, Profiles,
    Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/containers/master/_listings/google-tag-manager/accountsaccountidcontainerscontainerid-delete-openapi.md
- name: Tag Manager - Get Container
  x-api-slug: accountsaccountidcontainerscontainerid-get
  description: Gets a Container.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/googl_tag_manager_gplus-250.png
  humanURL: https://developers.google.com/tag-manager/
  baseURL: ://www.googleapis.com//tagmanager/v1
  tags: Google APIs, Tags, Stack Network, API Service Provider, API Provider, Profiles,
    Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/containers/master/_listings/google-tag-manager/accountsaccountidcontainerscontainerid-get-openapi.md
- name: Tag Manager - Update Container
  x-api-slug: accountsaccountidcontainerscontainerid-put
  description: Updates a Container.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/googl_tag_manager_gplus-250.png
  humanURL: https://developers.google.com/tag-manager/
  baseURL: ://www.googleapis.com//tagmanager/v1
  tags: Google APIs, Tags, Stack Network, API Service Provider, API Provider, Profiles,
    Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/containers/master/_listings/google-tag-manager/accountsaccountidcontainerscontainerid-put-openapi.md
- name: Tag Manager - Get GTM Environments
  x-api-slug: accountsaccountidcontainerscontaineridenvironments-get
  description: Lists all GTM Environments of a GTM Container.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/googl_tag_manager_gplus-250.png
  humanURL: https://developers.google.com/tag-manager/
  baseURL: ://www.googleapis.com//tagmanager/v1
  tags: Google APIs, Tags, Stack Network, API Service Provider, API Provider, Profiles,
    Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/containers/master/_listings/google-tag-manager/accountsaccountidcontainerscontaineridenvironments-get-openapi.md
- name: Tag Manager - Get GTM Folders
  x-api-slug: accountsaccountidcontainerscontaineridfolders-get
  description: Lists all GTM Folders of a Container.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/googl_tag_manager_gplus-250.png
  humanURL: https://developers.google.com/tag-manager/
  baseURL: ://www.googleapis.com//tagmanager/v1
  tags: Google APIs, Tags, Stack Network, API Service Provider, API Provider, Profiles,
    Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/containers/master/_listings/google-tag-manager/accountsaccountidcontainerscontaineridfolders-get-openapi.md
- name: Tag Manager - Get GTM Tags
  x-api-slug: accountsaccountidcontainerscontaineridtags-get
  description: Lists all GTM Tags of a Container.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/googl_tag_manager_gplus-250.png
  humanURL: https://developers.google.com/tag-manager/
  baseURL: ://www.googleapis.com//tagmanager/v1
  tags: Google APIs, Tags, Stack Network, API Service Provider, API Provider, Profiles,
    Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/containers/master/_listings/google-tag-manager/accountsaccountidcontainerscontaineridtags-get-openapi.md
- name: Tag Manager - Get GTM Triggers
  x-api-slug: accountsaccountidcontainerscontaineridtriggers-get
  description: Lists all GTM Triggers of a Container.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/googl_tag_manager_gplus-250.png
  humanURL: https://developers.google.com/tag-manager/
  baseURL: ://www.googleapis.com//tagmanager/v1
  tags: Google APIs, Tags, Stack Network, API Service Provider, API Provider, Profiles,
    Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/containers/master/_listings/google-tag-manager/accountsaccountidcontainerscontaineridtriggers-get-openapi.md
- name: Tag Manager - Get GTM Variables
  x-api-slug: accountsaccountidcontainerscontaineridvariables-get
  description: Lists all GTM Variables of a Container.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/googl_tag_manager_gplus-250.png
  humanURL: https://developers.google.com/tag-manager/
  baseURL: ://www.googleapis.com//tagmanager/v1
  tags: Google APIs, Tags, Stack Network, API Service Provider, API Provider, Profiles,
    Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/containers/master/_listings/google-tag-manager/accountsaccountidcontainerscontaineridvariables-get-openapi.md
- name: Tag Manager - Get Container Versions
  x-api-slug: accountsaccountidcontainerscontaineridversions-get
  description: Lists all Container Versions of a GTM Container.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/googl_tag_manager_gplus-250.png
  humanURL: https://developers.google.com/tag-manager/
  baseURL: ://www.googleapis.com//tagmanager/v1
  tags: Google APIs, Tags, Stack Network, API Service Provider, API Provider, Profiles,
    Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/containers/master/_listings/google-tag-manager/accountsaccountidcontainerscontaineridversions-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/containers/master/_listings/google-tag-manager/accountsaccountidcontainerscontaineridversions-get-openapi.md
- name: Tag Manager - Create Container Version
  x-api-slug: accountsaccountidcontainerscontaineridversions-post
  description: Creates a Container Version.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/googl_tag_manager_gplus-250.png
  humanURL: https://developers.google.com/tag-manager/
  baseURL: ://www.googleapis.com//tagmanager/v1
  tags: Google APIs, Tags, Stack Network, API Service Provider, API Provider, Profiles,
    Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/containers/master/_listings/google-tag-manager/accountsaccountidcontainerscontaineridversions-post-openapi.md
- name: Tag Manager - Delete Container Version
  x-api-slug: accountsaccountidcontainerscontaineridversionscontainerversionid-delete
  description: Deletes a Container Version.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/googl_tag_manager_gplus-250.png
  humanURL: https://developers.google.com/tag-manager/
  baseURL: ://www.googleapis.com//tagmanager/v1
  tags: Google APIs, Tags, Stack Network, API Service Provider, API Provider, Profiles,
    Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/containers/master/_listings/google-tag-manager/accountsaccountidcontainerscontaineridversionscontainerversionid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/containers/master/_listings/google-tag-manager/accountsaccountidcontainerscontaineridversionscontainerversionid-delete-openapi.md
- name: Tag Manager - Get Container Version
  x-api-slug: accountsaccountidcontainerscontaineridversionscontainerversionid-get
  description: Gets a Container Version.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/googl_tag_manager_gplus-250.png
  humanURL: https://developers.google.com/tag-manager/
  baseURL: ://www.googleapis.com//tagmanager/v1
  tags: Google APIs, Tags, Stack Network, API Service Provider, API Provider, Profiles,
    Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/containers/master/_listings/google-tag-manager/accountsaccountidcontainerscontaineridversionscontainerversionid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/containers/master/_listings/google-tag-manager/accountsaccountidcontainerscontaineridversionscontainerversionid-get-openapi.md
- name: Tag Manager - Update Container Version
  x-api-slug: accountsaccountidcontainerscontaineridversionscontainerversionid-put
  description: Updates a Container Version.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/googl_tag_manager_gplus-250.png
  humanURL: https://developers.google.com/tag-manager/
  baseURL: ://www.googleapis.com//tagmanager/v1
  tags: Google APIs, Tags, Stack Network, API Service Provider, API Provider, Profiles,
    Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/containers/master/_listings/google-tag-manager/accountsaccountidcontainerscontaineridversionscontainerversionid-put-openapi.md
- name: Tag Manager - Publish Container Version
  x-api-slug: accountsaccountidcontainerscontaineridversionscontainerversionidpublish-post
  description: Publishes a Container Version.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/googl_tag_manager_gplus-250.png
  humanURL: https://developers.google.com/tag-manager/
  baseURL: ://www.googleapis.com//tagmanager/v1
  tags: Google APIs, Tags, Stack Network, API Service Provider, API Provider, Profiles,
    Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/containers/master/_listings/google-tag-manager/accountsaccountidcontainerscontaineridversionscontainerversionidpublish-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/containers/master/_listings/google-tag-manager/accountsaccountidcontainerscontaineridversionscontainerversionidpublish-post-openapi.md
- name: Tag Manager - Restore Container Version
  x-api-slug: accountsaccountidcontainerscontaineridversionscontainerversionidrestore-post
  description: Restores a Container Version. This will overwrite the container's current
    configuration (including its variables, triggers and tags). The operation will
    not have any effect on the version that is being served (i.e. the published version).
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/googl_tag_manager_gplus-250.png
  humanURL: https://developers.google.com/tag-manager/
  baseURL: ://www.googleapis.com//tagmanager/v1
  tags: Google APIs, Tags, Stack Network, API Service Provider, API Provider, Profiles,
    Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/containers/master/_listings/google-tag-manager/accountsaccountidcontainerscontaineridversionscontainerversionidrestore-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/containers/master/_listings/google-tag-manager/accountsaccountidcontainerscontaineridversionscontainerversionidrestore-post-openapi.md
- name: Tag Manager - Undelete Container Version
  x-api-slug: accountsaccountidcontainerscontaineridversionscontainerversionidundelete-post
  description: Undeletes a Container Version.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/googl_tag_manager_gplus-250.png
  humanURL: https://developers.google.com/tag-manager/
  baseURL: ://www.googleapis.com//tagmanager/v1
  tags: Google APIs, Tags, Stack Network, API Service Provider, API Provider, Profiles,
    Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/containers/master/_listings/google-tag-manager/accountsaccountidcontainerscontaineridversionscontainerversionidundelete-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/containers/master/_listings/google-tag-manager/accountsaccountidcontainerscontaineridversionscontainerversionidundelete-post-openapi.md
- name: Tag Manager - Get User Permissions
  x-api-slug: accountsaccountidpermissions-get
  description: List all users that have access to the account along with Account and
    Container Permissions granted to each of them.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/googl_tag_manager_gplus-250.png
  humanURL: https://developers.google.com/tag-manager/
  baseURL: ://www.googleapis.com//tagmanager/v1
  tags: Google APIs, Tags, Stack Network, API Service Provider, API Provider, Profiles,
    Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/containers/master/_listings/google-tag-manager/accountsaccountidpermissions-get-openapi.md
- name: Tag Manager - Create User Permission
  x-api-slug: accountsaccountidpermissions-post
  description: Creates a user's Account & Container Permissions.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/googl_tag_manager_gplus-250.png
  humanURL: https://developers.google.com/tag-manager/
  baseURL: ://www.googleapis.com//tagmanager/v1
  tags: Google APIs, Tags, Stack Network, API Service Provider, API Provider, Profiles,
    Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/containers/master/_listings/google-tag-manager/accountsaccountidpermissions-post-openapi.md
- name: Tag Manager - Get User
  x-api-slug: accountsaccountidpermissionspermissionid-get
  description: Gets a user's Account & Container Permissions.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/googl_tag_manager_gplus-250.png
  humanURL: https://developers.google.com/tag-manager/
  baseURL: ://www.googleapis.com//tagmanager/v1
  tags: Google APIs, Tags, Stack Network, API Service Provider, API Provider, Profiles,
    Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/containers/master/_listings/google-tag-manager/accountsaccountidpermissionspermissionid-get-openapi.md
- name: Tag Manager - Update User
  x-api-slug: accountsaccountidpermissionspermissionid-put
  description: Updates a user's Account & Container Permissions.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/googl_tag_manager_gplus-250.png
  humanURL: https://developers.google.com/tag-manager/
  baseURL: ://www.googleapis.com//tagmanager/v1
  tags: Google APIs, Tags, Stack Network, API Service Provider, API Provider, Profiles,
    Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/containers/master/_listings/google-tag-manager/accountsaccountidpermissionspermissionid-put-openapi.md
- name: Tag Manager - Get Conainers
  x-api-slug: accountsaccountidcontainers-get
  description: Lists all Containers that belongs to a GTM Account.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/googl_tag_manager_gplus-250.png
  humanURL: https://developers.google.com/tag-manager/
  baseURL: ://www.googleapis.com//tagmanager/v1
  tags: Google APIs, Tags, Stack Network, API Service Provider, API Provider, Profiles,
    Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/containers/master/_listings/google-tag-manager/accountsaccountidcontainers-get-openapi.md
- name: Tag Manager - Create Container
  x-api-slug: accountsaccountidcontainers-post
  description: Creates a Container.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/googl_tag_manager_gplus-250.png
  humanURL: https://developers.google.com/tag-manager/
  baseURL: ://www.googleapis.com//tagmanager/v1
  tags: Google APIs, Tags, Stack Network, API Service Provider, API Provider, Profiles,
    Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/containers/master/_listings/google-tag-manager/accountsaccountidcontainers-post-openapi.md
- name: Tag Manager - Delete Container
  x-api-slug: accountsaccountidcontainerscontainerid-delete
  description: Deletes a Container.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/googl_tag_manager_gplus-250.png
  humanURL: https://developers.google.com/tag-manager/
  baseURL: ://www.googleapis.com//tagmanager/v1
  tags: Google APIs, Tags, Stack Network, API Service Provider, API Provider, Profiles,
    Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/containers/master/_listings/google-tag-manager/accountsaccountidcontainerscontainerid-delete-openapi.md
- name: Tag Manager - Get Container
  x-api-slug: accountsaccountidcontainerscontainerid-get
  description: Gets a Container.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/googl_tag_manager_gplus-250.png
  humanURL: https://developers.google.com/tag-manager/
  baseURL: ://www.googleapis.com//tagmanager/v1
  tags: Google APIs, Tags, Stack Network, API Service Provider, API Provider, Profiles,
    Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/containers/master/_listings/google-tag-manager/accountsaccountidcontainerscontainerid-get-openapi.md
- name: Tag Manager - Update Container
  x-api-slug: accountsaccountidcontainerscontainerid-put
  description: Updates a Container.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/googl_tag_manager_gplus-250.png
  humanURL: https://developers.google.com/tag-manager/
  baseURL: ://www.googleapis.com//tagmanager/v1
  tags: Google APIs, Tags, Stack Network, API Service Provider, API Provider, Profiles,
    Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/containers/master/_listings/google-tag-manager/accountsaccountidcontainerscontainerid-put-openapi.md
- name: Tag Manager - Get GTM Environments
  x-api-slug: accountsaccountidcontainerscontaineridenvironments-get
  description: Lists all GTM Environments of a GTM Container.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/googl_tag_manager_gplus-250.png
  humanURL: https://developers.google.com/tag-manager/
  baseURL: ://www.googleapis.com//tagmanager/v1
  tags: Google APIs, Tags, Stack Network, API Service Provider, API Provider, Profiles,
    Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/containers/master/_listings/google-tag-manager/accountsaccountidcontainerscontaineridenvironments-get-openapi.md
- name: Tag Manager - Get GTM Folders
  x-api-slug: accountsaccountidcontainerscontaineridfolders-get
  description: Lists all GTM Folders of a Container.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/googl_tag_manager_gplus-250.png
  humanURL: https://developers.google.com/tag-manager/
  baseURL: ://www.googleapis.com//tagmanager/v1
  tags: Google APIs, Tags, Stack Network, API Service Provider, API Provider, Profiles,
    Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/containers/master/_listings/google-tag-manager/accountsaccountidcontainerscontaineridfolders-get-openapi.md
- name: Tag Manager - Get GTM Tags
  x-api-slug: accountsaccountidcontainerscontaineridtags-get
  description: Lists all GTM Tags of a Container.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/googl_tag_manager_gplus-250.png
  humanURL: https://developers.google.com/tag-manager/
  baseURL: ://www.googleapis.com//tagmanager/v1
  tags: Google APIs, Tags, Stack Network, API Service Provider, API Provider, Profiles,
    Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/containers/master/_listings/google-tag-manager/accountsaccountidcontainerscontaineridtags-get-openapi.md
- name: Tag Manager - Get GTM Triggers
  x-api-slug: accountsaccountidcontainerscontaineridtriggers-get
  description: Lists all GTM Triggers of a Container.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/googl_tag_manager_gplus-250.png
  humanURL: https://developers.google.com/tag-manager/
  baseURL: ://www.googleapis.com//tagmanager/v1
  tags: Google APIs, Tags, Stack Network, API Service Provider, API Provider, Profiles,
    Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/containers/master/_listings/google-tag-manager/accountsaccountidcontainerscontaineridtriggers-get-openapi.md
- name: Tag Manager - Get GTM Variables
  x-api-slug: accountsaccountidcontainerscontaineridvariables-get
  description: Lists all GTM Variables of a Container.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/googl_tag_manager_gplus-250.png
  humanURL: https://developers.google.com/tag-manager/
  baseURL: ://www.googleapis.com//tagmanager/v1
  tags: Google APIs, Tags, Stack Network, API Service Provider, API Provider, Profiles,
    Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/containers/master/_listings/google-tag-manager/accountsaccountidcontainerscontaineridvariables-get-openapi.md
- name: Tag Manager - Get Container Versions
  x-api-slug: accountsaccountidcontainerscontaineridversions-get
  description: Lists all Container Versions of a GTM Container.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/googl_tag_manager_gplus-250.png
  humanURL: https://developers.google.com/tag-manager/
  baseURL: ://www.googleapis.com//tagmanager/v1
  tags: Google APIs, Tags, Stack Network, API Service Provider, API Provider, Profiles,
    Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/containers/master/_listings/google-tag-manager/accountsaccountidcontainerscontaineridversions-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/containers/master/_listings/google-tag-manager/accountsaccountidcontainerscontaineridversions-get-openapi.md
- name: Tag Manager - Create Container Version
  x-api-slug: accountsaccountidcontainerscontaineridversions-post
  description: Creates a Container Version.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/googl_tag_manager_gplus-250.png
  humanURL: https://developers.google.com/tag-manager/
  baseURL: ://www.googleapis.com//tagmanager/v1
  tags: Google APIs, Tags, Stack Network, API Service Provider, API Provider, Profiles,
    Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/containers/master/_listings/google-tag-manager/accountsaccountidcontainerscontaineridversions-post-openapi.md
- name: Tag Manager - Delete Container Version
  x-api-slug: accountsaccountidcontainerscontaineridversionscontainerversionid-delete
  description: Deletes a Container Version.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/googl_tag_manager_gplus-250.png
  humanURL: https://developers.google.com/tag-manager/
  baseURL: ://www.googleapis.com//tagmanager/v1
  tags: Google APIs, Tags, Stack Network, API Service Provider, API Provider, Profiles,
    Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/containers/master/_listings/google-tag-manager/accountsaccountidcontainerscontaineridversionscontainerversionid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/containers/master/_listings/google-tag-manager/accountsaccountidcontainerscontaineridversionscontainerversionid-delete-openapi.md
- name: Tag Manager - Get Container Version
  x-api-slug: accountsaccountidcontainerscontaineridversionscontainerversionid-get
  description: Gets a Container Version.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/googl_tag_manager_gplus-250.png
  humanURL: https://developers.google.com/tag-manager/
  baseURL: ://www.googleapis.com//tagmanager/v1
  tags: Google APIs, Tags, Stack Network, API Service Provider, API Provider, Profiles,
    Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/containers/master/_listings/google-tag-manager/accountsaccountidcontainerscontaineridversionscontainerversionid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/containers/master/_listings/google-tag-manager/accountsaccountidcontainerscontaineridversionscontainerversionid-get-openapi.md
- name: Tag Manager - Update Container Version
  x-api-slug: accountsaccountidcontainerscontaineridversionscontainerversionid-put
  description: Updates a Container Version.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/googl_tag_manager_gplus-250.png
  humanURL: https://developers.google.com/tag-manager/
  baseURL: ://www.googleapis.com//tagmanager/v1
  tags: Google APIs, Tags, Stack Network, API Service Provider, API Provider, Profiles,
    Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/containers/master/_listings/google-tag-manager/accountsaccountidcontainerscontaineridversionscontainerversionid-put-openapi.md
- name: Tag Manager - Publish Container Version
  x-api-slug: accountsaccountidcontainerscontaineridversionscontainerversionidpublish-post
  description: Publishes a Container Version.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/googl_tag_manager_gplus-250.png
  humanURL: https://developers.google.com/tag-manager/
  baseURL: ://www.googleapis.com//tagmanager/v1
  tags: Google APIs, Tags, Stack Network, API Service Provider, API Provider, Profiles,
    Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/containers/master/_listings/google-tag-manager/accountsaccountidcontainerscontaineridversionscontainerversionidpublish-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/containers/master/_listings/google-tag-manager/accountsaccountidcontainerscontaineridversionscontainerversionidpublish-post-openapi.md
- name: Tag Manager - Restore Container Version
  x-api-slug: accountsaccountidcontainerscontaineridversionscontainerversionidrestore-post
  description: Restores a Container Version. This will overwrite the container's current
    configuration (including its variables, triggers and tags). The operation will
    not have any effect on the version that is being served (i.e. the published version).
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/googl_tag_manager_gplus-250.png
  humanURL: https://developers.google.com/tag-manager/
  baseURL: ://www.googleapis.com//tagmanager/v1
  tags: Google APIs, Tags, Stack Network, API Service Provider, API Provider, Profiles,
    Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/containers/master/_listings/google-tag-manager/accountsaccountidcontainerscontaineridversionscontainerversionidrestore-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/containers/master/_listings/google-tag-manager/accountsaccountidcontainerscontaineridversionscontainerversionidrestore-post-openapi.md
- name: Tag Manager - Undelete Container Version
  x-api-slug: accountsaccountidcontainerscontaineridversionscontainerversionidundelete-post
  description: Undeletes a Container Version.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/googl_tag_manager_gplus-250.png
  humanURL: https://developers.google.com/tag-manager/
  baseURL: ://www.googleapis.com//tagmanager/v1
  tags: Google APIs, Tags, Stack Network, API Service Provider, API Provider, Profiles,
    Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/containers/master/_listings/google-tag-manager/accountsaccountidcontainerscontaineridversionscontainerversionidundelete-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/containers/master/_listings/google-tag-manager/accountsaccountidcontainerscontaineridversionscontainerversionidundelete-post-openapi.md
- name: Tag Manager - Get User Permissions
  x-api-slug: accountsaccountidpermissions-get
  description: List all users that have access to the account along with Account and
    Container Permissions granted to each of them.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/googl_tag_manager_gplus-250.png
  humanURL: https://developers.google.com/tag-manager/
  baseURL: ://www.googleapis.com//tagmanager/v1
  tags: Google APIs, Tags, Stack Network, API Service Provider, API Provider, Profiles,
    Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/containers/master/_listings/google-tag-manager/accountsaccountidpermissions-get-openapi.md
- name: Tag Manager - Create User Permission
  x-api-slug: accountsaccountidpermissions-post
  description: Creates a user's Account & Container Permissions.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/googl_tag_manager_gplus-250.png
  humanURL: https://developers.google.com/tag-manager/
  baseURL: ://www.googleapis.com//tagmanager/v1
  tags: Google APIs, Tags, Stack Network, API Service Provider, API Provider, Profiles,
    Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/containers/master/_listings/google-tag-manager/accountsaccountidpermissions-post-openapi.md
- name: Tag Manager - Get User
  x-api-slug: accountsaccountidpermissionspermissionid-get
  description: Gets a user's Account & Container Permissions.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/googl_tag_manager_gplus-250.png
  humanURL: https://developers.google.com/tag-manager/
  baseURL: ://www.googleapis.com//tagmanager/v1
  tags: Google APIs, Tags, Stack Network, API Service Provider, API Provider, Profiles,
    Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/containers/master/_listings/google-tag-manager/accountsaccountidpermissionspermissionid-get-openapi.md
- name: Tag Manager - Update User
  x-api-slug: accountsaccountidpermissionspermissionid-put
  description: Updates a user's Account & Container Permissions.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/googl_tag_manager_gplus-250.png
  humanURL: https://developers.google.com/tag-manager/
  baseURL: ://www.googleapis.com//tagmanager/v1
  tags: Google APIs, Tags, Stack Network, API Service Provider, API Provider, Profiles,
    Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/containers/master/_listings/google-tag-manager/accountsaccountidpermissionspermissionid-put-openapi.md
- name: Tag Manager - Update Container
  x-api-slug: accountsaccountidcontainerscontainerid-put
  description: Updates a Container.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/googl_tag_manager_gplus-250.png
  humanURL: https://developers.google.com/tag-manager/
  baseURL: ://www.googleapis.com//tagmanager/v1
  tags: Google APIs, Tags, Stack Network, API Service Provider, API Provider, Profiles,
    Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/containers/master/_listings/google-tag-manager/accountsaccountidcontainerscontainerid-put-openapi.md
- name: Tag Manager - Get Container
  x-api-slug: accountsaccountidcontainerscontainerid-get
  description: Gets a Container.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/googl_tag_manager_gplus-250.png
  humanURL: https://developers.google.com/tag-manager/
  baseURL: ://www.googleapis.com//tagmanager/v1
  tags: Google APIs, Tags, Stack Network, API Service Provider, API Provider, Profiles,
    Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/containers/master/_listings/google-tag-manager/accountsaccountidcontainerscontainerid-get-openapi.md
- name: Tag Manager - Delete Container
  x-api-slug: accountsaccountidcontainerscontainerid-delete
  description: Deletes a Container.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/googl_tag_manager_gplus-250.png
  humanURL: https://developers.google.com/tag-manager/
  baseURL: ://www.googleapis.com//tagmanager/v1
  tags: Google APIs, Tags, Stack Network, API Service Provider, API Provider, Profiles,
    Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/containers/master/_listings/google-tag-manager/accountsaccountidcontainerscontainerid-delete-openapi.md
- name: Tag Manager - Create Container
  x-api-slug: accountsaccountidcontainers-post
  description: Creates a Container.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/googl_tag_manager_gplus-250.png
  humanURL: https://developers.google.com/tag-manager/
  baseURL: ://www.googleapis.com//tagmanager/v1
  tags: Google APIs, Tags, Stack Network, API Service Provider, API Provider, Profiles,
    Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/containers/master/_listings/google-tag-manager/accountsaccountidcontainers-post-openapi.md
- name: Tag Manager - Get Conainers
  x-api-slug: accountsaccountidcontainers-get
  description: Lists all Containers that belongs to a GTM Account.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/googl_tag_manager_gplus-250.png
  humanURL: https://developers.google.com/tag-manager/
  baseURL: ://www.googleapis.com//tagmanager/v1
  tags: Google APIs, Tags, Stack Network, API Service Provider, API Provider, Profiles,
    Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/containers/master/_listings/google-tag-manager/accountsaccountidcontainers-get-openapi.md
x-common:
- type: x-api-gallery
  url: http://google.stackdriver.monitoring.api.gallery.streamdata.io
- type: x-api-stack
  url: http://google.tag.manager.stack.network
- type: x-authentication
  url: https://developers.google.com/tag-manager/api/v1/authorization
- type: x-change-log
  url: https://developers.google.com/tag-manager/api/v1/changelog
- type: x-code
  url: https://developers.google.com/tag-manager/api/v1/libraries
- type: x-documentation
  url: https://developers.google.com/tag-manager/api/v1/
- type: x-performance
  url: https://developers.google.com/tag-manager/api/v1/performance
- type: x-website
  url: https://developers.google.com/tag-manager/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---