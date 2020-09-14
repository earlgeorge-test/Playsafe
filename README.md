# Playsafe
Playsafe Assessment
"contributions": [
    {
      "id": "service-endpoint",
      "description": "The ktoc endpoint should produce an output amount in celsius when given an input amount in kelvin.",
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

        
