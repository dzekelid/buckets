---
name: AWS S3
x-slug: aws-s3
description: Amazon Simple Storage Service (Amazon S3) is object storage with a simple
  web service interface to store and retrieve any amount of data from anywhere on
  the web. It is designed to deliver 99.999999999% durability, and scale past trillions
  of objects worldwide.Customers use S3 as a bulk repository, or data lake, for analytics;
  backup &amp; recovery; disaster recovery; and serverless computing. Many cloud-native
  applications even use S3 as primary storage.Its simple to move large volumes of
  data into or out of S3 with Amazonscloud data migrationoptions. Once data is stored
  in Amazon S3, it can be automatically tiered into lower cost, longer-termcloud storageclasses
  like S3 Standard - Infrequent Access and Amazon Glacier for archiving.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AmazonS3.png
x-kinRank: "10"
x-alexaRank: "0"
tags: Buckets
created: "2018-08-27"
modified: "2018-08-27"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/apis.md
specificationVersion: "0.14"
apis:
- name: No Title - DELETE Bucket
  x-api-slug: delete
  description: This implementation of the DELETE operation deletes the bucket named
    inthe URI
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AmazonS3.png
  humanURL: https://aws.amazon.com/s3/
  baseURL: https:////
  tags: Amazon Web Services, Storage, Stack Network, Stack, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/delete-openapi.md
- name: No Title - HEAD Bucket
  x-api-slug: head
  description: This operation is useful to determine if a bucket exists and you have
    permission to accessit
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AmazonS3.png
  humanURL: https://aws.amazon.com/s3/
  baseURL: https:////
  tags: Amazon Web Services, Storage, Stack Network, Stack, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/head-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/head-openapi.md
- name: No Title - PUT Bucket
  x-api-slug: put
  description: This implementation of the PUT operation creates a new bucket
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AmazonS3.png
  humanURL: https://aws.amazon.com/s3/
  baseURL: https:////
  tags: Amazon Web Services, Storage, Stack Network, Stack, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/put-openapi.md
- name: No Title - GET Bucket accelerate
  x-api-slug: accelerate-get
  description: This implementation of the GET operation uses the acceleratesubresource
    to return the Transfer Acceleration state of a bucket, which is eitherEnabled
    or Suspended
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AmazonS3.png
  humanURL: https://aws.amazon.com/s3/
  baseURL: https:////
  tags: Amazon Web Services, Storage, Stack Network, Stack, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/accelerate-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/accelerate-get-openapi.md
- name: No Title - PUT Bucket accelerate
  x-api-slug: accelerate-put
  description: This implementation of the PUT operation uses the acceleratesubresource
    to set the Transfer Acceleration state of an existing bucket
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AmazonS3.png
  humanURL: https://aws.amazon.com/s3/
  baseURL: https:////
  tags: Amazon Web Services, Storage, Stack Network, Stack, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/accelerate-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/accelerate-put-openapi.md
- name: No Title - GET Bucket ACL
  x-api-slug: acl-get
  description: This implementation of the GET operation uses the aclsubresource to
    return the access control list (ACL) of a bucket
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AmazonS3.png
  humanURL: https://aws.amazon.com/s3/
  baseURL: https:////
  tags: Amazon Web Services, Storage, Stack Network, Stack, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/acl-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/acl-get-openapi.md
- name: No Title - PUT Bucket ACL
  x-api-slug: acl-put
  description: This implementation of the PUT operation uses the aclsubresource to
    set the permissions on an existing bucket using access control lists(ACL)
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AmazonS3.png
  humanURL: https://aws.amazon.com/s3/
  baseURL: https:////
  tags: Amazon Web Services, Storage, Stack Network, Stack, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/acl-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/acl-put-openapi.md
- name: No Title - List Bucket Analytics Configurations
  x-api-slug: analytics-get
  description: This implementation of the GET operation returns a list of analyticsconfigurations
    for the bucket
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AmazonS3.png
  humanURL: https://aws.amazon.com/s3/
  baseURL: https:////
  tags: Amazon Web Services, Storage, Stack Network, Stack, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/analytics-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/analytics-get-openapi.md
- name: No Title - DELETE Bucket analyticsnttconfiguration
  x-api-slug: analyticsampidanalyticsconfigurationid-delete
  description: This implementation of the DELETE operation deletes an analytics configuration(identified
    by the analytics configuration ID) from the bucket
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AmazonS3.png
  humanURL: https://aws.amazon.com/s3/
  baseURL: https:////
  tags: Amazon Web Services, Storage, Stack Network, Stack, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/analyticsampidanalyticsconfigurationid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/analyticsampidanalyticsconfigurationid-delete-openapi.md
- name: No Title - GET Bucket analytics configuration
  x-api-slug: analyticsampidanalyticsconfigurationid-get
  description: This implementation of the GET operation returns an analytics configuration
    (identified bythe analytics configuration ID) from the bucket
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AmazonS3.png
  humanURL: https://aws.amazon.com/s3/
  baseURL: https:////
  tags: Amazon Web Services, Storage, Stack Network, Stack, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/analyticsampidanalyticsconfigurationid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/analyticsampidanalyticsconfigurationid-get-openapi.md
- name: No Title - PUT Bucket analytics configuration
  x-api-slug: analyticsampidconfigurationid-put
  description: This implementation of the PUT operation adds an analytics configuration(identified
    by the analytics ID) to the bucket
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AmazonS3.png
  humanURL: https://aws.amazon.com/s3/
  baseURL: https:////
  tags: Amazon Web Services, Storage, Stack Network, Stack, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/analyticsampidconfigurationid-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/analyticsampidconfigurationid-put-openapi.md
- name: No Title - DELETE Bucket CORS
  x-api-slug: cors-delete
  description: Deletes the cors configuration information set for the bucket
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AmazonS3.png
  humanURL: https://aws.amazon.com/s3/
  baseURL: https:////
  tags: Amazon Web Services, Storage, Stack Network, Stack, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/cors-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/cors-delete-openapi.md
- name: No Title - GET Bucket CORS
  x-api-slug: cors-get
  description: Returns the cors configuration information set for thebucket
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AmazonS3.png
  humanURL: https://aws.amazon.com/s3/
  baseURL: https:////
  tags: Amazon Web Services, Storage, Stack Network, Stack, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/cors-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/cors-get-openapi.md
- name: No Title - List Bucket Inventory Configurations
  x-api-slug: inventory-get
  description: This implementation of the GET operation returns a list of inventoryconfigurations
    for the bucket
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AmazonS3.png
  humanURL: https://aws.amazon.com/s3/
  baseURL: https:////
  tags: Amazon Web Services, Storage, Stack Network, Stack, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/inventory-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/inventory-get-openapi.md
- name: No Title - PUT Bucket inventory configuration
  x-api-slug: inventoryampidconfigurationid-put
  description: This implementation of the PUT operation adds an inventory configuration(identified
    by the inventory ID) to the bucket
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AmazonS3.png
  humanURL: https://aws.amazon.com/s3/
  baseURL: https:////
  tags: Amazon Web Services, Storage, Stack Network, Stack, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/inventoryampidconfigurationid-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/inventoryampidconfigurationid-put-openapi.md
- name: No Title - DELETE Bucket inventory configuration
  x-api-slug: inventoryampidinventoryconfigurationid-delete
  description: This implementation of the DELETE operation deletes an inventory configuration(identified
    by the inventory configuration ID) from the bucket
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AmazonS3.png
  humanURL: https://aws.amazon.com/s3/
  baseURL: https:////
  tags: Amazon Web Services, Storage, Stack Network, Stack, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/inventoryampidinventoryconfigurationid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/inventoryampidinventoryconfigurationid-delete-openapi.md
- name: No Title - GET Bucket inventory configuration
  x-api-slug: inventoryampidinventoryconfigurationid-get
  description: This implementation of the GET operation returns an inventory configuration
    (identified bythe inventory configuration ID) from the bucket
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AmazonS3.png
  humanURL: https://aws.amazon.com/s3/
  baseURL: https:////
  tags: Amazon Web Services, Storage, Stack Network, Stack, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/inventoryampidinventoryconfigurationid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/inventoryampidinventoryconfigurationid-get-openapi.md
- name: No Title - DELETE Bucket lifecycle
  x-api-slug: lifecycle-delete
  description: Deletes the lifecycle configuration from the specified bucket
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AmazonS3.png
  humanURL: https://aws.amazon.com/s3/
  baseURL: https:////
  tags: Amazon Web Services, Storage, Stack Network, Stack, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/lifecycle-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/lifecycle-delete-openapi.md
- name: No Title - GET Bucket lifecycle
  x-api-slug: lifecycle-get
  description: NoteBucket lifecycle configuration now supports specifying lifecycle
    rule usingobject key name prefix, one or more object tags, or combination of both
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AmazonS3.png
  humanURL: https://aws.amazon.com/s3/
  baseURL: https:////
  tags: Amazon Web Services, Storage, Stack Network, Stack, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/lifecycle-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/lifecycle-get-openapi.md
- name: No Title - PUT Bucket lifecycle
  x-api-slug: lifecycle-put
  description: Creates a new lifecycle configuration for the bucket or replaces an
    existing lifecycle configuration
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AmazonS3.png
  humanURL: https://aws.amazon.com/s3/
  baseURL: https:////
  tags: Amazon Web Services, Storage, Stack Network, Stack, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/lifecycle-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/lifecycle-put-openapi.md
- name: No Title - GET Bucket (List Objects) Version 2
  x-api-slug: listtype2-get
  description: This implementation of the GET operation returns some or all (up to
    1,000) ofthe objects in a bucket
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AmazonS3.png
  humanURL: https://aws.amazon.com/s3/
  baseURL: https:////
  tags: Amazon Web Services, Storage, Stack Network, Stack, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/listtype2-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/listtype2-get-openapi.md
- name: No Title - GET Bucket location
  x-api-slug: location-get
  description: This implementation of the GET operation uses thelocation subresource
    to return a bucket's region
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AmazonS3.png
  humanURL: https://aws.amazon.com/s3/
  baseURL: https:////
  tags: Amazon Web Services, Storage, Stack Network, Stack, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/location-get-openapi.md
- name: No Title - GET Bucket logging
  x-api-slug: logging-get
  description: This implementation of the GET operation uses thelogging subresource
    to return the logging status of a bucketand the permissions users have to view
    and modify that status
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AmazonS3.png
  humanURL: https://aws.amazon.com/s3/
  baseURL: https:////
  tags: Amazon Web Services, Storage, Stack Network, Stack, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/logging-get-openapi.md
- name: No Title - List Bucket Metrics
  x-api-slug: metrics-get
  description: Lists the metrics configurations for the CloudWatch request metrics
    of the bucket
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AmazonS3.png
  humanURL: https://aws.amazon.com/s3/
  baseURL: https:////
  tags: Amazon Web Services, Storage, Stack Network, Stack, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/metrics-get-openapi.md
- name: No Title - DELETE Bucket Metrics
  x-api-slug: metricsampidid-delete
  description: Deletes a metrics configuration for the CloudWatch request metrics
    (specified by the metricsconfiguration ID) from the bucket
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AmazonS3.png
  humanURL: https://aws.amazon.com/s3/
  baseURL: https:////
  tags: Amazon Web Services, Storage, Stack Network, Stack, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/metricsampidid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/metricsampidid-delete-openapi.md
- name: No Title - PUT Bucket Metrics
  x-api-slug: metricsampidid-put
  description: Sets or updates a metrics configuration for the CloudWatch request
    metrics (specified by themetrics configuration ID) from the bucket
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AmazonS3.png
  humanURL: https://aws.amazon.com/s3/
  baseURL: https:////
  tags: Amazon Web Services, Storage, Stack Network, Stack, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/metricsampidid-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/metricsampidid-put-openapi.md
- name: No Title - GET Bucket Metrics
  x-api-slug: metricsampidid-get
  description: Gets a metrics configuration for the CloudWatch request metrics (specified
    by the metricsconfiguration ID) from the bucket
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AmazonS3.png
  humanURL: https://aws.amazon.com/s3/
  baseURL: https:////
  tags: Amazon Web Services, Storage, Stack Network, Stack, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/metricsampidid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/metricsampidid-get-openapi.md
- name: No Title - GET Bucket notification
  x-api-slug: notification-get
  description: This implementation of the GET operation uses thenotification subresource
    to return the notificationconfiguration of a bucket
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AmazonS3.png
  humanURL: https://aws.amazon.com/s3/
  baseURL: https:////
  tags: Amazon Web Services, Storage, Stack Network, Stack, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/notification-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/notification-get-openapi.md
- name: No Title - PUT Bucket notification
  x-api-slug: notification-put
  description: The Amazon S3 notification feature enables you to receive notifications
    when certain eventshappen in your bucket
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AmazonS3.png
  humanURL: https://aws.amazon.com/s3/
  baseURL: https:////
  tags: Amazon Web Services, Storage, Stack Network, Stack, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/notification-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/notification-put-openapi.md
- name: No Title - DELETE Bucket policy
  x-api-slug: policy-delete
  description: This implementation of the DELETE operation uses the policy subresource
    to delete the policy on a specified bucket
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AmazonS3.png
  humanURL: https://aws.amazon.com/s3/
  baseURL: https:////
  tags: Amazon Web Services, Storage, Stack Network, Stack, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/policy-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/policy-delete-openapi.md
- name: No Title - GET Bucket policy
  x-api-slug: policy-get
  description: This implementation of the GET operation uses the policysubresource
    to return the policy of a specified bucket
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AmazonS3.png
  humanURL: https://aws.amazon.com/s3/
  baseURL: https:////
  tags: Amazon Web Services, Storage, Stack Network, Stack, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/policy-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/policy-get-openapi.md
- name: No Title - PUT Bucket policy
  x-api-slug: policy-put
  description: This implementation of the PUT operation uses the policysubresource
    to add to or replace a policy on a bucket
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AmazonS3.png
  humanURL: https://aws.amazon.com/s3/
  baseURL: https:////
  tags: Amazon Web Services, Storage, Stack Network, Stack, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/policy-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/policy-put-openapi.md
- name: No Title - DELETE Bucket replication
  x-api-slug: replication-delete
  description: Deletes the replication subresource associated with the specified bucket
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AmazonS3.png
  humanURL: https://aws.amazon.com/s3/
  baseURL: https:////
  tags: Amazon Web Services, Storage, Stack Network, Stack, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/replication-delete-openapi.md
- name: No Title - GET Bucket replication
  x-api-slug: replication-get
  description: Returns the replication configuration information set on the      bucket
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AmazonS3.png
  humanURL: https://aws.amazon.com/s3/
  baseURL: https:////
  tags: Amazon Web Services, Storage, Stack Network, Stack, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/replication-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/replication-get-openapi.md
- name: No Title - PUT Bucket replication
  x-api-slug: replication-put
  description: In a versioning-enabled bucket, this operation creates a new replication
    configuration (or      replaces an existing one, if present)
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AmazonS3.png
  humanURL: https://aws.amazon.com/s3/
  baseURL: https:////
  tags: Amazon Web Services, Storage, Stack Network, Stack, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/replication-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/replication-put-openapi.md
- name: No Title - DELETE Bucket tagging
  x-api-slug: tagging-delete
  description: This implementation of the DELETE operation uses the taggingsubresource
    to remove a tag set from the specified bucket
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AmazonS3.png
  humanURL: https://aws.amazon.com/s3/
  baseURL: https:////
  tags: Amazon Web Services, Storage, Stack Network, Stack, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/tagging-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/tagging-delete-openapi.md
- name: No Title - GET Bucket tagging
  x-api-slug: tagging-get
  description: This implementation of the GET operation uses the taggingsubresource
    to return the tag set associated with the bucket
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AmazonS3.png
  humanURL: https://aws.amazon.com/s3/
  baseURL: https:////
  tags: Amazon Web Services, Storage, Stack Network, Stack, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/tagging-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/tagging-get-openapi.md
- name: No Title - PUT Bucket tagging
  x-api-slug: tagging-put
  description: This implementation of the PUT operation uses the taggingsubresource
    to add a set of tags to an existing bucket
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AmazonS3.png
  humanURL: https://aws.amazon.com/s3/
  baseURL: https:////
  tags: Amazon Web Services, Storage, Stack Network, Stack, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/tagging-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/tagging-put-openapi.md
- name: No Title - GET Bucket versioning
  x-api-slug: versioning-get
  description: This implementation of the GET operation uses theversioning subresource
    to return the versioning state of abucket
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AmazonS3.png
  humanURL: https://aws.amazon.com/s3/
  baseURL: https:////
  tags: Amazon Web Services, Storage, Stack Network, Stack, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/versioning-get-openapi.md
- name: No Title - PUT Bucket versioning
  x-api-slug: versioning-put
  description: This implementation of the PUT operation uses theversioning subresource
    to set the versioning state of anexisting bucket
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AmazonS3.png
  humanURL: https://aws.amazon.com/s3/
  baseURL: https:////
  tags: Amazon Web Services, Storage, Stack Network, Stack, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/versioning-put-openapi.md
- name: No Title - GET Bucket Object versions
  x-api-slug: versions-get
  description: You can use the versions subresource to list metadata about all ofthe
    versions of objects in a bucket
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AmazonS3.png
  humanURL: https://aws.amazon.com/s3/
  baseURL: https:////
  tags: Amazon Web Services, Storage, Stack Network, Stack, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/versions-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/versions-get-openapi.md
- name: No Title - DELETE Bucket website
  x-api-slug: website-delete
  description: This operation removes the website configuration for a bucket
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AmazonS3.png
  humanURL: https://aws.amazon.com/s3/
  baseURL: https:////
  tags: Amazon Web Services, Storage, Stack Network, Stack, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/website-delete-openapi.md
- name: No Title - GET Bucket website
  x-api-slug: website-get
  description: This implementation of the GET operation returns the website configurationassociated
    with a bucket
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AmazonS3.png
  humanURL: https://aws.amazon.com/s3/
  baseURL: https:////
  tags: Amazon Web Services, Storage, Stack Network, Stack, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/website-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/website-get-openapi.md
- name: No Title - PUT Bucket website
  x-api-slug: website-put
  description: Sets the configuration of the website that is specified in thewebsite
    subresource
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AmazonS3.png
  humanURL: https://aws.amazon.com/s3/
  baseURL: https:////
  tags: Amazon Web Services, Storage, Stack Network, Stack, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/website-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/website-put-openapi.md
- name: No Title - GET Bucket requestPayment
  x-api-slug: requestpayment-get
  description: This implementation of the GET operation uses therequestPayment subresource
    to return the request paymentconfiguration of a bucket
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AmazonS3.png
  humanURL: https://aws.amazon.com/s3/
  baseURL: https:////
  tags: Amazon Web Services, Storage, Stack Network, Stack, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/requestpayment-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/requestpayment-get-openapi.md
- name: No Title - PUT Bucket requestPayment
  x-api-slug: requestpayment-put
  description: This implementation of the PUT operation uses therequestPayment subresource
    to set the request paymentconfiguration of a bucket
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AmazonS3.png
  humanURL: https://aws.amazon.com/s3/
  baseURL: https:////
  tags: Amazon Web Services, Storage, Stack Network, Stack, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/requestpayment-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/requestpayment-put-openapi.md
- name: No Title - DELETE Bucket
  x-api-slug: delete
  description: This implementation of the DELETE operation deletes the bucket named
    inthe URI
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AmazonS3.png
  humanURL: https://aws.amazon.com/s3/
  baseURL: https:////
  tags: Amazon Web Services, Storage, Stack Network, Stack, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/delete-openapi.md
- name: No Title - HEAD Bucket
  x-api-slug: head
  description: This operation is useful to determine if a bucket exists and you have
    permission to accessit
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AmazonS3.png
  humanURL: https://aws.amazon.com/s3/
  baseURL: https:////
  tags: Amazon Web Services, Storage, Stack Network, Stack, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/head-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/head-openapi.md
- name: No Title - PUT Bucket
  x-api-slug: put
  description: This implementation of the PUT operation creates a new bucket
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AmazonS3.png
  humanURL: https://aws.amazon.com/s3/
  baseURL: https:////
  tags: Amazon Web Services, Storage, Stack Network, Stack, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/put-openapi.md
- name: No Title - GET Bucket accelerate
  x-api-slug: accelerate-get
  description: This implementation of the GET operation uses the acceleratesubresource
    to return the Transfer Acceleration state of a bucket, which is eitherEnabled
    or Suspended
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AmazonS3.png
  humanURL: https://aws.amazon.com/s3/
  baseURL: https:////
  tags: Amazon Web Services, Storage, Stack Network, Stack, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/accelerate-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/accelerate-get-openapi.md
- name: No Title - PUT Bucket accelerate
  x-api-slug: accelerate-put
  description: This implementation of the PUT operation uses the acceleratesubresource
    to set the Transfer Acceleration state of an existing bucket
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AmazonS3.png
  humanURL: https://aws.amazon.com/s3/
  baseURL: https:////
  tags: Amazon Web Services, Storage, Stack Network, Stack, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/accelerate-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/accelerate-put-openapi.md
- name: No Title - GET Bucket ACL
  x-api-slug: acl-get
  description: This implementation of the GET operation uses the aclsubresource to
    return the access control list (ACL) of a bucket
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AmazonS3.png
  humanURL: https://aws.amazon.com/s3/
  baseURL: https:////
  tags: Amazon Web Services, Storage, Stack Network, Stack, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/acl-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/acl-get-openapi.md
- name: No Title - PUT Bucket ACL
  x-api-slug: acl-put
  description: This implementation of the PUT operation uses the aclsubresource to
    set the permissions on an existing bucket using access control lists(ACL)
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AmazonS3.png
  humanURL: https://aws.amazon.com/s3/
  baseURL: https:////
  tags: Amazon Web Services, Storage, Stack Network, Stack, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/acl-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/acl-put-openapi.md
- name: No Title - List Bucket Analytics Configurations
  x-api-slug: analytics-get
  description: This implementation of the GET operation returns a list of analyticsconfigurations
    for the bucket
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AmazonS3.png
  humanURL: https://aws.amazon.com/s3/
  baseURL: https:////
  tags: Amazon Web Services, Storage, Stack Network, Stack, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/analytics-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/analytics-get-openapi.md
- name: No Title - DELETE Bucket analyticsnttconfiguration
  x-api-slug: analyticsampidanalyticsconfigurationid-delete
  description: This implementation of the DELETE operation deletes an analytics configuration(identified
    by the analytics configuration ID) from the bucket
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AmazonS3.png
  humanURL: https://aws.amazon.com/s3/
  baseURL: https:////
  tags: Amazon Web Services, Storage, Stack Network, Stack, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/analyticsampidanalyticsconfigurationid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/analyticsampidanalyticsconfigurationid-delete-openapi.md
- name: No Title - GET Bucket analytics configuration
  x-api-slug: analyticsampidanalyticsconfigurationid-get
  description: This implementation of the GET operation returns an analytics configuration
    (identified bythe analytics configuration ID) from the bucket
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AmazonS3.png
  humanURL: https://aws.amazon.com/s3/
  baseURL: https:////
  tags: Amazon Web Services, Storage, Stack Network, Stack, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/analyticsampidanalyticsconfigurationid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/analyticsampidanalyticsconfigurationid-get-openapi.md
- name: No Title - PUT Bucket analytics configuration
  x-api-slug: analyticsampidconfigurationid-put
  description: This implementation of the PUT operation adds an analytics configuration(identified
    by the analytics ID) to the bucket
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AmazonS3.png
  humanURL: https://aws.amazon.com/s3/
  baseURL: https:////
  tags: Amazon Web Services, Storage, Stack Network, Stack, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/analyticsampidconfigurationid-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/analyticsampidconfigurationid-put-openapi.md
- name: No Title - DELETE Bucket CORS
  x-api-slug: cors-delete
  description: Deletes the cors configuration information set for the bucket
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AmazonS3.png
  humanURL: https://aws.amazon.com/s3/
  baseURL: https:////
  tags: Amazon Web Services, Storage, Stack Network, Stack, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/cors-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/cors-delete-openapi.md
- name: No Title - GET Bucket CORS
  x-api-slug: cors-get
  description: Returns the cors configuration information set for thebucket
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AmazonS3.png
  humanURL: https://aws.amazon.com/s3/
  baseURL: https:////
  tags: Amazon Web Services, Storage, Stack Network, Stack, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/cors-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/cors-get-openapi.md
- name: No Title - List Bucket Inventory Configurations
  x-api-slug: inventory-get
  description: This implementation of the GET operation returns a list of inventoryconfigurations
    for the bucket
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AmazonS3.png
  humanURL: https://aws.amazon.com/s3/
  baseURL: https:////
  tags: Amazon Web Services, Storage, Stack Network, Stack, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/inventory-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/inventory-get-openapi.md
- name: No Title - PUT Bucket inventory configuration
  x-api-slug: inventoryampidconfigurationid-put
  description: This implementation of the PUT operation adds an inventory configuration(identified
    by the inventory ID) to the bucket
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AmazonS3.png
  humanURL: https://aws.amazon.com/s3/
  baseURL: https:////
  tags: Amazon Web Services, Storage, Stack Network, Stack, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/inventoryampidconfigurationid-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/inventoryampidconfigurationid-put-openapi.md
- name: No Title - DELETE Bucket inventory configuration
  x-api-slug: inventoryampidinventoryconfigurationid-delete
  description: This implementation of the DELETE operation deletes an inventory configuration(identified
    by the inventory configuration ID) from the bucket
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AmazonS3.png
  humanURL: https://aws.amazon.com/s3/
  baseURL: https:////
  tags: Amazon Web Services, Storage, Stack Network, Stack, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/inventoryampidinventoryconfigurationid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/inventoryampidinventoryconfigurationid-delete-openapi.md
- name: No Title - GET Bucket inventory configuration
  x-api-slug: inventoryampidinventoryconfigurationid-get
  description: This implementation of the GET operation returns an inventory configuration
    (identified bythe inventory configuration ID) from the bucket
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AmazonS3.png
  humanURL: https://aws.amazon.com/s3/
  baseURL: https:////
  tags: Amazon Web Services, Storage, Stack Network, Stack, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/inventoryampidinventoryconfigurationid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/inventoryampidinventoryconfigurationid-get-openapi.md
- name: No Title - DELETE Bucket lifecycle
  x-api-slug: lifecycle-delete
  description: Deletes the lifecycle configuration from the specified bucket
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AmazonS3.png
  humanURL: https://aws.amazon.com/s3/
  baseURL: https:////
  tags: Amazon Web Services, Storage, Stack Network, Stack, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/lifecycle-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/lifecycle-delete-openapi.md
- name: No Title - GET Bucket lifecycle
  x-api-slug: lifecycle-get
  description: NoteBucket lifecycle configuration now supports specifying lifecycle
    rule usingobject key name prefix, one or more object tags, or combination of both
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AmazonS3.png
  humanURL: https://aws.amazon.com/s3/
  baseURL: https:////
  tags: Amazon Web Services, Storage, Stack Network, Stack, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/lifecycle-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/lifecycle-get-openapi.md
- name: No Title - PUT Bucket lifecycle
  x-api-slug: lifecycle-put
  description: Creates a new lifecycle configuration for the bucket or replaces an
    existing lifecycle configuration
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AmazonS3.png
  humanURL: https://aws.amazon.com/s3/
  baseURL: https:////
  tags: Amazon Web Services, Storage, Stack Network, Stack, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/lifecycle-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/lifecycle-put-openapi.md
- name: No Title - GET Bucket (List Objects) Version 2
  x-api-slug: listtype2-get
  description: This implementation of the GET operation returns some or all (up to
    1,000) ofthe objects in a bucket
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AmazonS3.png
  humanURL: https://aws.amazon.com/s3/
  baseURL: https:////
  tags: Amazon Web Services, Storage, Stack Network, Stack, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/listtype2-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/listtype2-get-openapi.md
- name: No Title - GET Bucket location
  x-api-slug: location-get
  description: This implementation of the GET operation uses thelocation subresource
    to return a bucket's region
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AmazonS3.png
  humanURL: https://aws.amazon.com/s3/
  baseURL: https:////
  tags: Amazon Web Services, Storage, Stack Network, Stack, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/location-get-openapi.md
- name: No Title - GET Bucket logging
  x-api-slug: logging-get
  description: This implementation of the GET operation uses thelogging subresource
    to return the logging status of a bucketand the permissions users have to view
    and modify that status
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AmazonS3.png
  humanURL: https://aws.amazon.com/s3/
  baseURL: https:////
  tags: Amazon Web Services, Storage, Stack Network, Stack, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/logging-get-openapi.md
- name: No Title - List Bucket Metrics
  x-api-slug: metrics-get
  description: Lists the metrics configurations for the CloudWatch request metrics
    of the bucket
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AmazonS3.png
  humanURL: https://aws.amazon.com/s3/
  baseURL: https:////
  tags: Amazon Web Services, Storage, Stack Network, Stack, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/metrics-get-openapi.md
- name: No Title - DELETE Bucket Metrics
  x-api-slug: metricsampidid-delete
  description: Deletes a metrics configuration for the CloudWatch request metrics
    (specified by the metricsconfiguration ID) from the bucket
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AmazonS3.png
  humanURL: https://aws.amazon.com/s3/
  baseURL: https:////
  tags: Amazon Web Services, Storage, Stack Network, Stack, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/metricsampidid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/metricsampidid-delete-openapi.md
- name: No Title - PUT Bucket Metrics
  x-api-slug: metricsampidid-put
  description: Sets or updates a metrics configuration for the CloudWatch request
    metrics (specified by themetrics configuration ID) from the bucket
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AmazonS3.png
  humanURL: https://aws.amazon.com/s3/
  baseURL: https:////
  tags: Amazon Web Services, Storage, Stack Network, Stack, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/metricsampidid-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/metricsampidid-put-openapi.md
- name: No Title - GET Bucket Metrics
  x-api-slug: metricsampidid-get
  description: Gets a metrics configuration for the CloudWatch request metrics (specified
    by the metricsconfiguration ID) from the bucket
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AmazonS3.png
  humanURL: https://aws.amazon.com/s3/
  baseURL: https:////
  tags: Amazon Web Services, Storage, Stack Network, Stack, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/metricsampidid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/metricsampidid-get-openapi.md
- name: No Title - GET Bucket notification
  x-api-slug: notification-get
  description: This implementation of the GET operation uses thenotification subresource
    to return the notificationconfiguration of a bucket
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AmazonS3.png
  humanURL: https://aws.amazon.com/s3/
  baseURL: https:////
  tags: Amazon Web Services, Storage, Stack Network, Stack, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/notification-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/notification-get-openapi.md
- name: No Title - PUT Bucket notification
  x-api-slug: notification-put
  description: The Amazon S3 notification feature enables you to receive notifications
    when certain eventshappen in your bucket
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AmazonS3.png
  humanURL: https://aws.amazon.com/s3/
  baseURL: https:////
  tags: Amazon Web Services, Storage, Stack Network, Stack, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/notification-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/notification-put-openapi.md
- name: No Title - DELETE Bucket policy
  x-api-slug: policy-delete
  description: This implementation of the DELETE operation uses the policy subresource
    to delete the policy on a specified bucket
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AmazonS3.png
  humanURL: https://aws.amazon.com/s3/
  baseURL: https:////
  tags: Amazon Web Services, Storage, Stack Network, Stack, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/policy-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/policy-delete-openapi.md
- name: No Title - GET Bucket policy
  x-api-slug: policy-get
  description: This implementation of the GET operation uses the policysubresource
    to return the policy of a specified bucket
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AmazonS3.png
  humanURL: https://aws.amazon.com/s3/
  baseURL: https:////
  tags: Amazon Web Services, Storage, Stack Network, Stack, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/policy-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/policy-get-openapi.md
- name: No Title - PUT Bucket policy
  x-api-slug: policy-put
  description: This implementation of the PUT operation uses the policysubresource
    to add to or replace a policy on a bucket
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AmazonS3.png
  humanURL: https://aws.amazon.com/s3/
  baseURL: https:////
  tags: Amazon Web Services, Storage, Stack Network, Stack, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/policy-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/policy-put-openapi.md
- name: No Title - DELETE Bucket replication
  x-api-slug: replication-delete
  description: Deletes the replication subresource associated with the specified bucket
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AmazonS3.png
  humanURL: https://aws.amazon.com/s3/
  baseURL: https:////
  tags: Amazon Web Services, Storage, Stack Network, Stack, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/replication-delete-openapi.md
- name: No Title - GET Bucket replication
  x-api-slug: replication-get
  description: Returns the replication configuration information set on the      bucket
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AmazonS3.png
  humanURL: https://aws.amazon.com/s3/
  baseURL: https:////
  tags: Amazon Web Services, Storage, Stack Network, Stack, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/replication-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/replication-get-openapi.md
- name: No Title - PUT Bucket replication
  x-api-slug: replication-put
  description: In a versioning-enabled bucket, this operation creates a new replication
    configuration (or      replaces an existing one, if present)
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AmazonS3.png
  humanURL: https://aws.amazon.com/s3/
  baseURL: https:////
  tags: Amazon Web Services, Storage, Stack Network, Stack, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/replication-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/replication-put-openapi.md
- name: No Title - DELETE Bucket tagging
  x-api-slug: tagging-delete
  description: This implementation of the DELETE operation uses the taggingsubresource
    to remove a tag set from the specified bucket
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AmazonS3.png
  humanURL: https://aws.amazon.com/s3/
  baseURL: https:////
  tags: Amazon Web Services, Storage, Stack Network, Stack, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/tagging-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/tagging-delete-openapi.md
- name: No Title - GET Bucket tagging
  x-api-slug: tagging-get
  description: This implementation of the GET operation uses the taggingsubresource
    to return the tag set associated with the bucket
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AmazonS3.png
  humanURL: https://aws.amazon.com/s3/
  baseURL: https:////
  tags: Amazon Web Services, Storage, Stack Network, Stack, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/tagging-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/tagging-get-openapi.md
- name: No Title - PUT Bucket tagging
  x-api-slug: tagging-put
  description: This implementation of the PUT operation uses the taggingsubresource
    to add a set of tags to an existing bucket
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AmazonS3.png
  humanURL: https://aws.amazon.com/s3/
  baseURL: https:////
  tags: Amazon Web Services, Storage, Stack Network, Stack, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/tagging-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/tagging-put-openapi.md
- name: No Title - GET Bucket versioning
  x-api-slug: versioning-get
  description: This implementation of the GET operation uses theversioning subresource
    to return the versioning state of abucket
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AmazonS3.png
  humanURL: https://aws.amazon.com/s3/
  baseURL: https:////
  tags: Amazon Web Services, Storage, Stack Network, Stack, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/versioning-get-openapi.md
- name: No Title - PUT Bucket versioning
  x-api-slug: versioning-put
  description: This implementation of the PUT operation uses theversioning subresource
    to set the versioning state of anexisting bucket
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AmazonS3.png
  humanURL: https://aws.amazon.com/s3/
  baseURL: https:////
  tags: Amazon Web Services, Storage, Stack Network, Stack, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/versioning-put-openapi.md
- name: No Title - GET Bucket Object versions
  x-api-slug: versions-get
  description: You can use the versions subresource to list metadata about all ofthe
    versions of objects in a bucket
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AmazonS3.png
  humanURL: https://aws.amazon.com/s3/
  baseURL: https:////
  tags: Amazon Web Services, Storage, Stack Network, Stack, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/versions-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/versions-get-openapi.md
- name: No Title - DELETE Bucket website
  x-api-slug: website-delete
  description: This operation removes the website configuration for a bucket
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AmazonS3.png
  humanURL: https://aws.amazon.com/s3/
  baseURL: https:////
  tags: Amazon Web Services, Storage, Stack Network, Stack, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/website-delete-openapi.md
- name: No Title - GET Bucket website
  x-api-slug: website-get
  description: This implementation of the GET operation returns the website configurationassociated
    with a bucket
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AmazonS3.png
  humanURL: https://aws.amazon.com/s3/
  baseURL: https:////
  tags: Amazon Web Services, Storage, Stack Network, Stack, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/website-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/website-get-openapi.md
- name: No Title - PUT Bucket website
  x-api-slug: website-put
  description: Sets the configuration of the website that is specified in thewebsite
    subresource
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AmazonS3.png
  humanURL: https://aws.amazon.com/s3/
  baseURL: https:////
  tags: Amazon Web Services, Storage, Stack Network, Stack, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/website-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/website-put-openapi.md
- name: No Title - GET Bucket requestPayment
  x-api-slug: requestpayment-get
  description: This implementation of the GET operation uses therequestPayment subresource
    to return the request paymentconfiguration of a bucket
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AmazonS3.png
  humanURL: https://aws.amazon.com/s3/
  baseURL: https:////
  tags: Amazon Web Services, Storage, Stack Network, Stack, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/requestpayment-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/requestpayment-get-openapi.md
- name: No Title - PUT Bucket requestPayment
  x-api-slug: requestpayment-put
  description: This implementation of the PUT operation uses therequestPayment subresource
    to set the request paymentconfiguration of a bucket
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AmazonS3.png
  humanURL: https://aws.amazon.com/s3/
  baseURL: https:////
  tags: Amazon Web Services, Storage, Stack Network, Stack, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/requestpayment-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/requestpayment-put-openapi.md
- name: No Title - DELETE Bucket
  x-api-slug: delete
  description: This implementation of the DELETE operation deletes the bucket named
    inthe URI
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AmazonS3.png
  humanURL: https://aws.amazon.com/s3/
  baseURL: https:////
  tags: Amazon Web Services, Storage, Stack Network, Stack, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/delete-openapi.md
- name: No Title - HEAD Bucket
  x-api-slug: head
  description: This operation is useful to determine if a bucket exists and you have
    permission to accessit
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AmazonS3.png
  humanURL: https://aws.amazon.com/s3/
  baseURL: https:////
  tags: Amazon Web Services, Storage, Stack Network, Stack, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/head-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/head-openapi.md
- name: No Title - PUT Bucket
  x-api-slug: put
  description: This implementation of the PUT operation creates a new bucket
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AmazonS3.png
  humanURL: https://aws.amazon.com/s3/
  baseURL: https:////
  tags: Amazon Web Services, Storage, Stack Network, Stack, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/put-openapi.md
- name: No Title - GET Bucket accelerate
  x-api-slug: accelerate-get
  description: This implementation of the GET operation uses the acceleratesubresource
    to return the Transfer Acceleration state of a bucket, which is eitherEnabled
    or Suspended
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AmazonS3.png
  humanURL: https://aws.amazon.com/s3/
  baseURL: https:////
  tags: Amazon Web Services, Storage, Stack Network, Stack, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/accelerate-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/accelerate-get-openapi.md
- name: No Title - PUT Bucket accelerate
  x-api-slug: accelerate-put
  description: This implementation of the PUT operation uses the acceleratesubresource
    to set the Transfer Acceleration state of an existing bucket
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AmazonS3.png
  humanURL: https://aws.amazon.com/s3/
  baseURL: https:////
  tags: Amazon Web Services, Storage, Stack Network, Stack, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/accelerate-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/accelerate-put-openapi.md
- name: No Title - GET Bucket ACL
  x-api-slug: acl-get
  description: This implementation of the GET operation uses the aclsubresource to
    return the access control list (ACL) of a bucket
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AmazonS3.png
  humanURL: https://aws.amazon.com/s3/
  baseURL: https:////
  tags: Amazon Web Services, Storage, Stack Network, Stack, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/acl-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/acl-get-openapi.md
- name: No Title - PUT Bucket ACL
  x-api-slug: acl-put
  description: This implementation of the PUT operation uses the aclsubresource to
    set the permissions on an existing bucket using access control lists(ACL)
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AmazonS3.png
  humanURL: https://aws.amazon.com/s3/
  baseURL: https:////
  tags: Amazon Web Services, Storage, Stack Network, Stack, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/acl-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/acl-put-openapi.md
- name: No Title - PUT Bucket requestPayment
  x-api-slug: requestpayment-put
  description: This implementation of the PUT operation uses therequestPayment subresource
    to set the request paymentconfiguration of a bucket
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AmazonS3.png
  humanURL: https://aws.amazon.com/s3/
  baseURL: https:////
  tags: Amazon Web Services, Storage, Stack Network, Stack, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/requestpayment-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/requestpayment-put-openapi.md
- name: No Title - PUT Bucket requestPayment
  x-api-slug: requestpayment-put
  description: This implementation of the PUT operation uses therequestPayment subresource
    to set the request paymentconfiguration of a bucket
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AmazonS3.png
  humanURL: https://aws.amazon.com/s3/
  baseURL: https:////
  tags: Amazon Web Services, Storage, Stack Network, Stack, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/requestpayment-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/requestpayment-put-openapi.md
- name: No Title - GET Bucket requestPayment
  x-api-slug: requestpayment-get
  description: This implementation of the GET operation uses therequestPayment subresource
    to return the request paymentconfiguration of a bucket
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AmazonS3.png
  humanURL: https://aws.amazon.com/s3/
  baseURL: https:////
  tags: Amazon Web Services, Storage, Stack Network, Stack, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/requestpayment-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/requestpayment-get-openapi.md
- name: No Title - GET Bucket requestPayment
  x-api-slug: requestpayment-get
  description: This implementation of the GET operation uses therequestPayment subresource
    to return the request paymentconfiguration of a bucket
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AmazonS3.png
  humanURL: https://aws.amazon.com/s3/
  baseURL: https:////
  tags: Amazon Web Services, Storage, Stack Network, Stack, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/requestpayment-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/requestpayment-get-openapi.md
- name: No Title - PUT Bucket website
  x-api-slug: website-put
  description: Sets the configuration of the website that is specified in thewebsite
    subresource
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AmazonS3.png
  humanURL: https://aws.amazon.com/s3/
  baseURL: https:////
  tags: Amazon Web Services, Storage, Stack Network, Stack, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/website-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/website-put-openapi.md
- name: No Title - PUT Bucket website
  x-api-slug: website-put
  description: Sets the configuration of the website that is specified in thewebsite
    subresource
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AmazonS3.png
  humanURL: https://aws.amazon.com/s3/
  baseURL: https:////
  tags: Amazon Web Services, Storage, Stack Network, Stack, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/website-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/website-put-openapi.md
- name: No Title - GET Bucket website
  x-api-slug: website-get
  description: This implementation of the GET operation returns the website configurationassociated
    with a bucket
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AmazonS3.png
  humanURL: https://aws.amazon.com/s3/
  baseURL: https:////
  tags: Amazon Web Services, Storage, Stack Network, Stack, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/website-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/website-get-openapi.md
- name: No Title - GET Bucket website
  x-api-slug: website-get
  description: This implementation of the GET operation returns the website configurationassociated
    with a bucket
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AmazonS3.png
  humanURL: https://aws.amazon.com/s3/
  baseURL: https:////
  tags: Amazon Web Services, Storage, Stack Network, Stack, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/website-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/website-get-openapi.md
- name: No Title - DELETE Bucket website
  x-api-slug: website-delete
  description: This operation removes the website configuration for a bucket
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AmazonS3.png
  humanURL: https://aws.amazon.com/s3/
  baseURL: https:////
  tags: Amazon Web Services, Storage, Stack Network, Stack, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/website-delete-openapi.md
- name: No Title - DELETE Bucket website
  x-api-slug: website-delete
  description: This operation removes the website configuration for a bucket
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AmazonS3.png
  humanURL: https://aws.amazon.com/s3/
  baseURL: https:////
  tags: Amazon Web Services, Storage, Stack Network, Stack, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/website-delete-openapi.md
- name: No Title - GET Bucket Object versions
  x-api-slug: versions-get
  description: You can use the versions subresource to list metadata about all ofthe
    versions of objects in a bucket
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AmazonS3.png
  humanURL: https://aws.amazon.com/s3/
  baseURL: https:////
  tags: Amazon Web Services, Storage, Stack Network, Stack, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/versions-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/versions-get-openapi.md
- name: No Title - GET Bucket Object versions
  x-api-slug: versions-get
  description: You can use the versions subresource to list metadata about all ofthe
    versions of objects in a bucket
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AmazonS3.png
  humanURL: https://aws.amazon.com/s3/
  baseURL: https:////
  tags: Amazon Web Services, Storage, Stack Network, Stack, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/versions-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/versions-get-openapi.md
- name: No Title - PUT Bucket versioning
  x-api-slug: versioning-put
  description: This implementation of the PUT operation uses theversioning subresource
    to set the versioning state of anexisting bucket
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AmazonS3.png
  humanURL: https://aws.amazon.com/s3/
  baseURL: https:////
  tags: Amazon Web Services, Storage, Stack Network, Stack, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/versioning-put-openapi.md
- name: No Title - PUT Bucket versioning
  x-api-slug: versioning-put
  description: This implementation of the PUT operation uses theversioning subresource
    to set the versioning state of anexisting bucket
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AmazonS3.png
  humanURL: https://aws.amazon.com/s3/
  baseURL: https:////
  tags: Amazon Web Services, Storage, Stack Network, Stack, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/versioning-put-openapi.md
- name: No Title - GET Bucket versioning
  x-api-slug: versioning-get
  description: This implementation of the GET operation uses theversioning subresource
    to return the versioning state of abucket
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AmazonS3.png
  humanURL: https://aws.amazon.com/s3/
  baseURL: https:////
  tags: Amazon Web Services, Storage, Stack Network, Stack, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/versioning-get-openapi.md
- name: No Title - GET Bucket versioning
  x-api-slug: versioning-get
  description: This implementation of the GET operation uses theversioning subresource
    to return the versioning state of abucket
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AmazonS3.png
  humanURL: https://aws.amazon.com/s3/
  baseURL: https:////
  tags: Amazon Web Services, Storage, Stack Network, Stack, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/versioning-get-openapi.md
- name: No Title - PUT Bucket tagging
  x-api-slug: tagging-put
  description: This implementation of the PUT operation uses the taggingsubresource
    to add a set of tags to an existing bucket
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AmazonS3.png
  humanURL: https://aws.amazon.com/s3/
  baseURL: https:////
  tags: Amazon Web Services, Storage, Stack Network, Stack, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/tagging-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/tagging-put-openapi.md
- name: No Title - PUT Bucket tagging
  x-api-slug: tagging-put
  description: This implementation of the PUT operation uses the taggingsubresource
    to add a set of tags to an existing bucket
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AmazonS3.png
  humanURL: https://aws.amazon.com/s3/
  baseURL: https:////
  tags: Amazon Web Services, Storage, Stack Network, Stack, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/tagging-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/tagging-put-openapi.md
- name: No Title - GET Bucket tagging
  x-api-slug: tagging-get
  description: This implementation of the GET operation uses the taggingsubresource
    to return the tag set associated with the bucket
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AmazonS3.png
  humanURL: https://aws.amazon.com/s3/
  baseURL: https:////
  tags: Amazon Web Services, Storage, Stack Network, Stack, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/tagging-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/tagging-get-openapi.md
- name: No Title - GET Bucket tagging
  x-api-slug: tagging-get
  description: This implementation of the GET operation uses the taggingsubresource
    to return the tag set associated with the bucket
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AmazonS3.png
  humanURL: https://aws.amazon.com/s3/
  baseURL: https:////
  tags: Amazon Web Services, Storage, Stack Network, Stack, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/tagging-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/tagging-get-openapi.md
- name: No Title - DELETE Bucket tagging
  x-api-slug: tagging-delete
  description: This implementation of the DELETE operation uses the taggingsubresource
    to remove a tag set from the specified bucket
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AmazonS3.png
  humanURL: https://aws.amazon.com/s3/
  baseURL: https:////
  tags: Amazon Web Services, Storage, Stack Network, Stack, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/tagging-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/tagging-delete-openapi.md
- name: No Title - DELETE Bucket tagging
  x-api-slug: tagging-delete
  description: This implementation of the DELETE operation uses the taggingsubresource
    to remove a tag set from the specified bucket
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AmazonS3.png
  humanURL: https://aws.amazon.com/s3/
  baseURL: https:////
  tags: Amazon Web Services, Storage, Stack Network, Stack, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/tagging-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/tagging-delete-openapi.md
- name: No Title - PUT Bucket replication
  x-api-slug: replication-put
  description: In a versioning-enabled bucket, this operation creates a new replication
    configuration (or      replaces an existing one, if present)
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AmazonS3.png
  humanURL: https://aws.amazon.com/s3/
  baseURL: https:////
  tags: Amazon Web Services, Storage, Stack Network, Stack, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/replication-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/replication-put-openapi.md
- name: No Title - PUT Bucket replication
  x-api-slug: replication-put
  description: In a versioning-enabled bucket, this operation creates a new replication
    configuration (or      replaces an existing one, if present)
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AmazonS3.png
  humanURL: https://aws.amazon.com/s3/
  baseURL: https:////
  tags: Amazon Web Services, Storage, Stack Network, Stack, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/replication-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/replication-put-openapi.md
- name: No Title - GET Bucket replication
  x-api-slug: replication-get
  description: Returns the replication configuration information set on the      bucket
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AmazonS3.png
  humanURL: https://aws.amazon.com/s3/
  baseURL: https:////
  tags: Amazon Web Services, Storage, Stack Network, Stack, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/replication-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/replication-get-openapi.md
- name: No Title - GET Bucket replication
  x-api-slug: replication-get
  description: Returns the replication configuration information set on the      bucket
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AmazonS3.png
  humanURL: https://aws.amazon.com/s3/
  baseURL: https:////
  tags: Amazon Web Services, Storage, Stack Network, Stack, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/replication-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/replication-get-openapi.md
- name: No Title - DELETE Bucket replication
  x-api-slug: replication-delete
  description: Deletes the replication subresource associated with the specified bucket
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AmazonS3.png
  humanURL: https://aws.amazon.com/s3/
  baseURL: https:////
  tags: Amazon Web Services, Storage, Stack Network, Stack, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/replication-delete-openapi.md
- name: No Title - DELETE Bucket replication
  x-api-slug: replication-delete
  description: Deletes the replication subresource associated with the specified bucket
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AmazonS3.png
  humanURL: https://aws.amazon.com/s3/
  baseURL: https:////
  tags: Amazon Web Services, Storage, Stack Network, Stack, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/replication-delete-openapi.md
- name: No Title - PUT Bucket policy
  x-api-slug: policy-put
  description: This implementation of the PUT operation uses the policysubresource
    to add to or replace a policy on a bucket
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AmazonS3.png
  humanURL: https://aws.amazon.com/s3/
  baseURL: https:////
  tags: Amazon Web Services, Storage, Stack Network, Stack, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/policy-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/policy-put-openapi.md
- name: No Title - PUT Bucket policy
  x-api-slug: policy-put
  description: This implementation of the PUT operation uses the policysubresource
    to add to or replace a policy on a bucket
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AmazonS3.png
  humanURL: https://aws.amazon.com/s3/
  baseURL: https:////
  tags: Amazon Web Services, Storage, Stack Network, Stack, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/policy-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/policy-put-openapi.md
- name: No Title - GET Bucket policy
  x-api-slug: policy-get
  description: This implementation of the GET operation uses the policysubresource
    to return the policy of a specified bucket
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AmazonS3.png
  humanURL: https://aws.amazon.com/s3/
  baseURL: https:////
  tags: Amazon Web Services, Storage, Stack Network, Stack, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/policy-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/policy-get-openapi.md
- name: No Title - GET Bucket policy
  x-api-slug: policy-get
  description: This implementation of the GET operation uses the policysubresource
    to return the policy of a specified bucket
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AmazonS3.png
  humanURL: https://aws.amazon.com/s3/
  baseURL: https:////
  tags: Amazon Web Services, Storage, Stack Network, Stack, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/policy-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/policy-get-openapi.md
- name: No Title - DELETE Bucket policy
  x-api-slug: policy-delete
  description: This implementation of the DELETE operation uses the policy subresource
    to delete the policy on a specified bucket
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AmazonS3.png
  humanURL: https://aws.amazon.com/s3/
  baseURL: https:////
  tags: Amazon Web Services, Storage, Stack Network, Stack, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/policy-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/policy-delete-openapi.md
- name: No Title - DELETE Bucket policy
  x-api-slug: policy-delete
  description: This implementation of the DELETE operation uses the policy subresource
    to delete the policy on a specified bucket
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AmazonS3.png
  humanURL: https://aws.amazon.com/s3/
  baseURL: https:////
  tags: Amazon Web Services, Storage, Stack Network, Stack, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/policy-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/policy-delete-openapi.md
- name: No Title - PUT Bucket notification
  x-api-slug: notification-put
  description: The Amazon S3 notification feature enables you to receive notifications
    when certain eventshappen in your bucket
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AmazonS3.png
  humanURL: https://aws.amazon.com/s3/
  baseURL: https:////
  tags: Amazon Web Services, Storage, Stack Network, Stack, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/notification-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/notification-put-openapi.md
- name: No Title - PUT Bucket notification
  x-api-slug: notification-put
  description: The Amazon S3 notification feature enables you to receive notifications
    when certain eventshappen in your bucket
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AmazonS3.png
  humanURL: https://aws.amazon.com/s3/
  baseURL: https:////
  tags: Amazon Web Services, Storage, Stack Network, Stack, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/notification-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/notification-put-openapi.md
- name: No Title - GET Bucket notification
  x-api-slug: notification-get
  description: This implementation of the GET operation uses thenotification subresource
    to return the notificationconfiguration of a bucket
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AmazonS3.png
  humanURL: https://aws.amazon.com/s3/
  baseURL: https:////
  tags: Amazon Web Services, Storage, Stack Network, Stack, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/notification-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/notification-get-openapi.md
- name: No Title - GET Bucket notification
  x-api-slug: notification-get
  description: This implementation of the GET operation uses thenotification subresource
    to return the notificationconfiguration of a bucket
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AmazonS3.png
  humanURL: https://aws.amazon.com/s3/
  baseURL: https:////
  tags: Amazon Web Services, Storage, Stack Network, Stack, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/notification-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/notification-get-openapi.md
- name: No Title - GET Bucket Metrics
  x-api-slug: metricsampidid-get
  description: Gets a metrics configuration for the CloudWatch request metrics (specified
    by the metricsconfiguration ID) from the bucket
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AmazonS3.png
  humanURL: https://aws.amazon.com/s3/
  baseURL: https:////
  tags: Amazon Web Services, Storage, Stack Network, Stack, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/metricsampidid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/metricsampidid-get-openapi.md
- name: No Title - GET Bucket Metrics
  x-api-slug: metricsampidid-get
  description: Gets a metrics configuration for the CloudWatch request metrics (specified
    by the metricsconfiguration ID) from the bucket
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AmazonS3.png
  humanURL: https://aws.amazon.com/s3/
  baseURL: https:////
  tags: Amazon Web Services, Storage, Stack Network, Stack, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/metricsampidid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/metricsampidid-get-openapi.md
- name: No Title - PUT Bucket Metrics
  x-api-slug: metricsampidid-put
  description: Sets or updates a metrics configuration for the CloudWatch request
    metrics (specified by themetrics configuration ID) from the bucket
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AmazonS3.png
  humanURL: https://aws.amazon.com/s3/
  baseURL: https:////
  tags: Amazon Web Services, Storage, Stack Network, Stack, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/metricsampidid-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/metricsampidid-put-openapi.md
- name: No Title - PUT Bucket Metrics
  x-api-slug: metricsampidid-put
  description: Sets or updates a metrics configuration for the CloudWatch request
    metrics (specified by themetrics configuration ID) from the bucket
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AmazonS3.png
  humanURL: https://aws.amazon.com/s3/
  baseURL: https:////
  tags: Amazon Web Services, Storage, Stack Network, Stack, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/metricsampidid-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/metricsampidid-put-openapi.md
- name: No Title - DELETE Bucket Metrics
  x-api-slug: metricsampidid-delete
  description: Deletes a metrics configuration for the CloudWatch request metrics
    (specified by the metricsconfiguration ID) from the bucket
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AmazonS3.png
  humanURL: https://aws.amazon.com/s3/
  baseURL: https:////
  tags: Amazon Web Services, Storage, Stack Network, Stack, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/metricsampidid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/metricsampidid-delete-openapi.md
- name: No Title - DELETE Bucket Metrics
  x-api-slug: metricsampidid-delete
  description: Deletes a metrics configuration for the CloudWatch request metrics
    (specified by the metricsconfiguration ID) from the bucket
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AmazonS3.png
  humanURL: https://aws.amazon.com/s3/
  baseURL: https:////
  tags: Amazon Web Services, Storage, Stack Network, Stack, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/metricsampidid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/metricsampidid-delete-openapi.md
- name: No Title - List Bucket Metrics
  x-api-slug: metrics-get
  description: Lists the metrics configurations for the CloudWatch request metrics
    of the bucket
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AmazonS3.png
  humanURL: https://aws.amazon.com/s3/
  baseURL: https:////
  tags: Amazon Web Services, Storage, Stack Network, Stack, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/metrics-get-openapi.md
- name: No Title - List Bucket Metrics
  x-api-slug: metrics-get
  description: Lists the metrics configurations for the CloudWatch request metrics
    of the bucket
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AmazonS3.png
  humanURL: https://aws.amazon.com/s3/
  baseURL: https:////
  tags: Amazon Web Services, Storage, Stack Network, Stack, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/metrics-get-openapi.md
- name: No Title - GET Bucket logging
  x-api-slug: logging-get
  description: This implementation of the GET operation uses thelogging subresource
    to return the logging status of a bucketand the permissions users have to view
    and modify that status
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AmazonS3.png
  humanURL: https://aws.amazon.com/s3/
  baseURL: https:////
  tags: Amazon Web Services, Storage, Stack Network, Stack, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/logging-get-openapi.md
- name: No Title - GET Bucket logging
  x-api-slug: logging-get
  description: This implementation of the GET operation uses thelogging subresource
    to return the logging status of a bucketand the permissions users have to view
    and modify that status
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AmazonS3.png
  humanURL: https://aws.amazon.com/s3/
  baseURL: https:////
  tags: Amazon Web Services, Storage, Stack Network, Stack, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/logging-get-openapi.md
- name: No Title - GET Bucket location
  x-api-slug: location-get
  description: This implementation of the GET operation uses thelocation subresource
    to return a bucket's region
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AmazonS3.png
  humanURL: https://aws.amazon.com/s3/
  baseURL: https:////
  tags: Amazon Web Services, Storage, Stack Network, Stack, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/location-get-openapi.md
- name: No Title - GET Bucket location
  x-api-slug: location-get
  description: This implementation of the GET operation uses thelocation subresource
    to return a bucket's region
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AmazonS3.png
  humanURL: https://aws.amazon.com/s3/
  baseURL: https:////
  tags: Amazon Web Services, Storage, Stack Network, Stack, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/location-get-openapi.md
- name: No Title - GET Bucket (List Objects) Version 2
  x-api-slug: listtype2-get
  description: This implementation of the GET operation returns some or all (up to
    1,000) ofthe objects in a bucket
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AmazonS3.png
  humanURL: https://aws.amazon.com/s3/
  baseURL: https:////
  tags: Amazon Web Services, Storage, Stack Network, Stack, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/listtype2-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/listtype2-get-openapi.md
- name: No Title - GET Bucket (List Objects) Version 2
  x-api-slug: listtype2-get
  description: This implementation of the GET operation returns some or all (up to
    1,000) ofthe objects in a bucket
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AmazonS3.png
  humanURL: https://aws.amazon.com/s3/
  baseURL: https:////
  tags: Amazon Web Services, Storage, Stack Network, Stack, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/listtype2-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/listtype2-get-openapi.md
- name: No Title - PUT Bucket lifecycle
  x-api-slug: lifecycle-put
  description: Creates a new lifecycle configuration for the bucket or replaces an
    existing lifecycle configuration
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AmazonS3.png
  humanURL: https://aws.amazon.com/s3/
  baseURL: https:////
  tags: Amazon Web Services, Storage, Stack Network, Stack, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/lifecycle-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/lifecycle-put-openapi.md
- name: No Title - PUT Bucket lifecycle
  x-api-slug: lifecycle-put
  description: Creates a new lifecycle configuration for the bucket or replaces an
    existing lifecycle configuration
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AmazonS3.png
  humanURL: https://aws.amazon.com/s3/
  baseURL: https:////
  tags: Amazon Web Services, Storage, Stack Network, Stack, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/lifecycle-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/lifecycle-put-openapi.md
- name: No Title - GET Bucket lifecycle
  x-api-slug: lifecycle-get
  description: NoteBucket lifecycle configuration now supports specifying lifecycle
    rule usingobject key name prefix, one or more object tags, or combination of both
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AmazonS3.png
  humanURL: https://aws.amazon.com/s3/
  baseURL: https:////
  tags: Amazon Web Services, Storage, Stack Network, Stack, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/lifecycle-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/lifecycle-get-openapi.md
- name: No Title - GET Bucket lifecycle
  x-api-slug: lifecycle-get
  description: NoteBucket lifecycle configuration now supports specifying lifecycle
    rule usingobject key name prefix, one or more object tags, or combination of both
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AmazonS3.png
  humanURL: https://aws.amazon.com/s3/
  baseURL: https:////
  tags: Amazon Web Services, Storage, Stack Network, Stack, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/lifecycle-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/lifecycle-get-openapi.md
- name: No Title - DELETE Bucket lifecycle
  x-api-slug: lifecycle-delete
  description: Deletes the lifecycle configuration from the specified bucket
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AmazonS3.png
  humanURL: https://aws.amazon.com/s3/
  baseURL: https:////
  tags: Amazon Web Services, Storage, Stack Network, Stack, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/lifecycle-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/lifecycle-delete-openapi.md
- name: No Title - DELETE Bucket lifecycle
  x-api-slug: lifecycle-delete
  description: Deletes the lifecycle configuration from the specified bucket
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AmazonS3.png
  humanURL: https://aws.amazon.com/s3/
  baseURL: https:////
  tags: Amazon Web Services, Storage, Stack Network, Stack, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/lifecycle-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/lifecycle-delete-openapi.md
- name: No Title - GET Bucket inventory configuration
  x-api-slug: inventoryampidinventoryconfigurationid-get
  description: This implementation of the GET operation returns an inventory configuration
    (identified bythe inventory configuration ID) from the bucket
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AmazonS3.png
  humanURL: https://aws.amazon.com/s3/
  baseURL: https:////
  tags: Amazon Web Services, Storage, Stack Network, Stack, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/inventoryampidinventoryconfigurationid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/inventoryampidinventoryconfigurationid-get-openapi.md
- name: No Title - GET Bucket inventory configuration
  x-api-slug: inventoryampidinventoryconfigurationid-get
  description: This implementation of the GET operation returns an inventory configuration
    (identified bythe inventory configuration ID) from the bucket
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AmazonS3.png
  humanURL: https://aws.amazon.com/s3/
  baseURL: https:////
  tags: Amazon Web Services, Storage, Stack Network, Stack, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/inventoryampidinventoryconfigurationid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/inventoryampidinventoryconfigurationid-get-openapi.md
- name: No Title - DELETE Bucket inventory configuration
  x-api-slug: inventoryampidinventoryconfigurationid-delete
  description: This implementation of the DELETE operation deletes an inventory configuration(identified
    by the inventory configuration ID) from the bucket
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AmazonS3.png
  humanURL: https://aws.amazon.com/s3/
  baseURL: https:////
  tags: Amazon Web Services, Storage, Stack Network, Stack, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/inventoryampidinventoryconfigurationid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/inventoryampidinventoryconfigurationid-delete-openapi.md
- name: No Title - DELETE Bucket inventory configuration
  x-api-slug: inventoryampidinventoryconfigurationid-delete
  description: This implementation of the DELETE operation deletes an inventory configuration(identified
    by the inventory configuration ID) from the bucket
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AmazonS3.png
  humanURL: https://aws.amazon.com/s3/
  baseURL: https:////
  tags: Amazon Web Services, Storage, Stack Network, Stack, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/inventoryampidinventoryconfigurationid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/inventoryampidinventoryconfigurationid-delete-openapi.md
- name: No Title - PUT Bucket inventory configuration
  x-api-slug: inventoryampidconfigurationid-put
  description: This implementation of the PUT operation adds an inventory configuration(identified
    by the inventory ID) to the bucket
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AmazonS3.png
  humanURL: https://aws.amazon.com/s3/
  baseURL: https:////
  tags: Amazon Web Services, Storage, Stack Network, Stack, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/inventoryampidconfigurationid-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/inventoryampidconfigurationid-put-openapi.md
- name: No Title - PUT Bucket inventory configuration
  x-api-slug: inventoryampidconfigurationid-put
  description: This implementation of the PUT operation adds an inventory configuration(identified
    by the inventory ID) to the bucket
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AmazonS3.png
  humanURL: https://aws.amazon.com/s3/
  baseURL: https:////
  tags: Amazon Web Services, Storage, Stack Network, Stack, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/inventoryampidconfigurationid-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/inventoryampidconfigurationid-put-openapi.md
- name: No Title - List Bucket Inventory Configurations
  x-api-slug: inventory-get
  description: This implementation of the GET operation returns a list of inventoryconfigurations
    for the bucket
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AmazonS3.png
  humanURL: https://aws.amazon.com/s3/
  baseURL: https:////
  tags: Amazon Web Services, Storage, Stack Network, Stack, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/inventory-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/inventory-get-openapi.md
- name: No Title - List Bucket Inventory Configurations
  x-api-slug: inventory-get
  description: This implementation of the GET operation returns a list of inventoryconfigurations
    for the bucket
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AmazonS3.png
  humanURL: https://aws.amazon.com/s3/
  baseURL: https:////
  tags: Amazon Web Services, Storage, Stack Network, Stack, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/inventory-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/inventory-get-openapi.md
- name: No Title - GET Bucket CORS
  x-api-slug: cors-get
  description: Returns the cors configuration information set for thebucket
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AmazonS3.png
  humanURL: https://aws.amazon.com/s3/
  baseURL: https:////
  tags: Amazon Web Services, Storage, Stack Network, Stack, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/cors-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/cors-get-openapi.md
- name: No Title - GET Bucket CORS
  x-api-slug: cors-get
  description: Returns the cors configuration information set for thebucket
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AmazonS3.png
  humanURL: https://aws.amazon.com/s3/
  baseURL: https:////
  tags: Amazon Web Services, Storage, Stack Network, Stack, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/cors-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/cors-get-openapi.md
- name: No Title - DELETE Bucket CORS
  x-api-slug: cors-delete
  description: Deletes the cors configuration information set for the bucket
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AmazonS3.png
  humanURL: https://aws.amazon.com/s3/
  baseURL: https:////
  tags: Amazon Web Services, Storage, Stack Network, Stack, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/cors-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/cors-delete-openapi.md
- name: No Title - DELETE Bucket CORS
  x-api-slug: cors-delete
  description: Deletes the cors configuration information set for the bucket
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AmazonS3.png
  humanURL: https://aws.amazon.com/s3/
  baseURL: https:////
  tags: Amazon Web Services, Storage, Stack Network, Stack, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/cors-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/cors-delete-openapi.md
- name: No Title - PUT Bucket analytics configuration
  x-api-slug: analyticsampidconfigurationid-put
  description: This implementation of the PUT operation adds an analytics configuration(identified
    by the analytics ID) to the bucket
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AmazonS3.png
  humanURL: https://aws.amazon.com/s3/
  baseURL: https:////
  tags: Amazon Web Services, Storage, Stack Network, Stack, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/analyticsampidconfigurationid-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/analyticsampidconfigurationid-put-openapi.md
- name: No Title - PUT Bucket analytics configuration
  x-api-slug: analyticsampidconfigurationid-put
  description: This implementation of the PUT operation adds an analytics configuration(identified
    by the analytics ID) to the bucket
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AmazonS3.png
  humanURL: https://aws.amazon.com/s3/
  baseURL: https:////
  tags: Amazon Web Services, Storage, Stack Network, Stack, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/analyticsampidconfigurationid-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/analyticsampidconfigurationid-put-openapi.md
- name: No Title - GET Bucket analytics configuration
  x-api-slug: analyticsampidanalyticsconfigurationid-get
  description: This implementation of the GET operation returns an analytics configuration
    (identified bythe analytics configuration ID) from the bucket
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AmazonS3.png
  humanURL: https://aws.amazon.com/s3/
  baseURL: https:////
  tags: Amazon Web Services, Storage, Stack Network, Stack, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/analyticsampidanalyticsconfigurationid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/analyticsampidanalyticsconfigurationid-get-openapi.md
- name: No Title - GET Bucket analytics configuration
  x-api-slug: analyticsampidanalyticsconfigurationid-get
  description: This implementation of the GET operation returns an analytics configuration
    (identified bythe analytics configuration ID) from the bucket
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AmazonS3.png
  humanURL: https://aws.amazon.com/s3/
  baseURL: https:////
  tags: Amazon Web Services, Storage, Stack Network, Stack, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/analyticsampidanalyticsconfigurationid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/analyticsampidanalyticsconfigurationid-get-openapi.md
- name: No Title - DELETE Bucket analyticsnttconfiguration
  x-api-slug: analyticsampidanalyticsconfigurationid-delete
  description: This implementation of the DELETE operation deletes an analytics configuration(identified
    by the analytics configuration ID) from the bucket
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AmazonS3.png
  humanURL: https://aws.amazon.com/s3/
  baseURL: https:////
  tags: Amazon Web Services, Storage, Stack Network, Stack, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/analyticsampidanalyticsconfigurationid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/analyticsampidanalyticsconfigurationid-delete-openapi.md
- name: No Title - DELETE Bucket analyticsnttconfiguration
  x-api-slug: analyticsampidanalyticsconfigurationid-delete
  description: This implementation of the DELETE operation deletes an analytics configuration(identified
    by the analytics configuration ID) from the bucket
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AmazonS3.png
  humanURL: https://aws.amazon.com/s3/
  baseURL: https:////
  tags: Amazon Web Services, Storage, Stack Network, Stack, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/analyticsampidanalyticsconfigurationid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/analyticsampidanalyticsconfigurationid-delete-openapi.md
- name: No Title - List Bucket Analytics Configurations
  x-api-slug: analytics-get
  description: This implementation of the GET operation returns a list of analyticsconfigurations
    for the bucket
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AmazonS3.png
  humanURL: https://aws.amazon.com/s3/
  baseURL: https:////
  tags: Amazon Web Services, Storage, Stack Network, Stack, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/analytics-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/analytics-get-openapi.md
- name: No Title - List Bucket Analytics Configurations
  x-api-slug: analytics-get
  description: This implementation of the GET operation returns a list of analyticsconfigurations
    for the bucket
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AmazonS3.png
  humanURL: https://aws.amazon.com/s3/
  baseURL: https:////
  tags: Amazon Web Services, Storage, Stack Network, Stack, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/analytics-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/aws-s3/analytics-get-openapi.md
x-common:
- type: x-api-gallery
  url: http://aws.route.53.api.gallery.streamdata.io
- type: x-api-stack
  url: http://aws.s3.stack.network
- type: x-documentation
  url: http://docs.aws.amazon.com/AmazonS3/latest/API/Welcome.html
- type: x-faq
  url: https://aws.amazon.com/s3/faqs/
- type: x-getting-started
  url: https://aws.amazon.com/s3/getting-started/
- type: x-pricing
  url: https://aws.amazon.com/s3/pricing/
- type: x-sla
  url: https://aws.amazon.com/s3/sla/
- type: x-website
  url: https://aws.amazon.com/s3/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---