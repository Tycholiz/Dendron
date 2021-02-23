---
id: 4b29fefb-007c-4552-ae02-594ca57a4fa3
title: Curl
desc: ''
updated: 1614040493415
created: 1614040255463
---

## Get
`curl --data "param1=value1&param2=value2" https://example.com/resource.cgi`

## Post
`curl -X POST -d '{"key1":"value1", "key2":"value2"}' -H "Content-Type: application/x-www-form-urlencoded" https://example.com/resource.cgi`
- application/x-www-form-urlencoded is the default:
