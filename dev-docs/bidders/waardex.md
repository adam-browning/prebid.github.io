---
layout: bidder
title: waardex
description: Prebid Waardex Bidder Adaptor
hide: true
biddercode: waardex
media_types: banner
---

### Bid Params

{: .table .table-bordered .table-striped }
| Name          | Scope    | Description                                                      | Example          | Type     |
|---------------|----------|------------------------------------------------------------------|------------------|----------|
| `pubId`       | required | publisher identifier                                             | 1                | `number` |
| `bidId`       | required | bid request id                                                   | `'22c4871113f461'` | `string` |
| `placementId` | required | placement id                                                     | `'dsew53y678jgj1'` | `string` |
| `bidfloor`    | required | bid request price                                                | 0.5              | `float`  |
| `position`    | optional | ad position on the page                                          | 1                | `number` |
| `instl`       | optional | 1 when ad is interstitial or full screen, 0 when not interstitial| 0                | `number` |
