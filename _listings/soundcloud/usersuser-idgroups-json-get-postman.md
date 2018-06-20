{
  "info": {
    "name": "Sound Cloud Get Users Groups",
    "_postman_id": "a5a2c70e-6ea3-4df4-95e9-ffe788d1798f",
    "description": "Returns a collection of groups joined by user with user id",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Users",
      "item": [
        {
          "id": "84f81bad-56fb-4b77-bf8a-50f9af4c0d98",
          "name": "getUsersUserGroups.json",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.soundcloud.com",
              "path": [
                "users/:user_id/groups.json"
              ],
              "query": [
                {
                  "key": "consumer_key",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "user_id",
                  "value": "user_id",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns a collection of groups joined by user with user id"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "d0a7a24b-b18d-47be-a597-b86201a83107"
            }
          ]
        }
      ]
    }
  ]
}