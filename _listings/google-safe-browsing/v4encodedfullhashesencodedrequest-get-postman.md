{
  "info": {
    "name": "Google Safe Browsing API Encode Full Hashes",
    "_postman_id": "d8dc4fd5-ffca-4878-8b39-b1b0a3a1ba07",
    "description": "Encode Full Hashes",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Hash",
      "item": [
        {
          "id": "539c1a12-e5eb-4f0f-80ed-ef18a3f3af64",
          "name": "safebrowsing.encodedFullHashes.get",
          "request": {
            "url": {
              "protocol": "http",
              "host": "safebrowsing.googleapis.com",
              "path": [
                "v4/encodedFullHashes/:encodedRequest"
              ],
              "query": [
                {
                  "key": "clientId",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "clientVersion",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "encodedRequest",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Encode Full Hashes"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "0fa965ba-ff3b-40a2-8659-8b990adf8b36"
            }
          ]
        }
      ]
    }
  ]
}