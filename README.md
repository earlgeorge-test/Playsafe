# Playsafe
Playsafe Assessment
"contributions": [
    {
      "id": "service-endpoint",
      "description": "The ktoc endpoint should produce an output amount in celsius when given an input amount in kelvin",
      "type": "ms.vss-endpoint.service-endpoint-type",
      "targets": [ "ms.vss-endpoint.endpoint-types" ],
      "properties": {
        "name": "/conversions/ktoc",
        "displayName": "conversions/ktoc",
        "url": {
          "displayName": "Server Url",
          "helpText": "Url for the conversions/ktoc server to connect to."
        },
        "dataSources": [
          {
            "name": "earlgeorge_test",
            "endpointUrl": "{{endpoint.url}}api/projects/index",
            "resultSelector": "jsonpath:$[*].nm"
          }
          
"contributions": [
    {
      "id": "service-endpoint",
      "description": "The ctok endpoint should produce an output amount in kelvin when given an input amount in celsius",
      "type": "ms.vss-endpoint.service-endpoint-type",
      "targets": [ "ms.vss-endpoint.endpoint-types" ],
      "properties": {
        "name": "//conversions/ctok",
        "displayName": "/conversions/ctok",
        "url": {
          "displayName": "Server Url",
          "helpText": "Url for the conversions/ctok server to connect to."
        },
        "dataSources": [
          {
            "name": "earlgeorge_test",
            "endpointUrl": "{{endpoint.url}}api/projects/index",
            "resultSelector": "jsonpath:$[*].nm"
          }          

"contributions": [
    {
      "id": "service-endpoint",
      "description": "The ktom endpoint should produce, when given an input amount in kilometers, an output amount in miles",
      "type": "ms.vss-endpoint.service-endpoint-type",
      "targets": [ "ms.vss-endpoint.endpoint-types" ],
      "properties": {
        "name": "//conversions/ktom",
        "displayName": "/conversions/ktom",
        "url": {
          "displayName": "Server Url",
          "helpText": "Url for the conversions/ktom server to connect to."
        },
        "dataSources": [
          {
            "name": "earlgeorge_test",
            "endpointUrl": "{{endpoint.url}}api/projects/index",
            "resultSelector": "jsonpath:$[*].nm"
          }          
 
 "contributions": [
    {
      "id": "service-endpoint",
      "description": "The mtok endpoint should produce, when given an input amount in miles, an output amount in kilometers",
      "type": "ms.vss-endpoint.service-endpoint-type",
      "targets": [ "ms.vss-endpoint.endpoint-types" ],
      "properties": {
        "name": "/conversions/mtok",
        "displayName": "/conversions/mtok",
        "url": {
          "displayName": "Server Url",
          "helpText": "Url for the conversions/mtok server to connect to."
        },
        "dataSources": [
          {
            "name": "earlgeorge_test",
            "endpointUrl": "{{endpoint.url}}api/projects/index",
            "resultSelector": "jsonpath:$[*].nm"
          }       
