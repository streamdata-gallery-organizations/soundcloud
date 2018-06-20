{
  "info": {
    "name": "Sound Cloud Get Users",
    "_postman_id": "4f5df69d-38b5-4d6a-9c57-a8773696f34a",
    "description": "Returns a user by user id",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Users",
      "item": [
        {
          "id": "9122ccee-e628-41e6-b097-3040f35941e2",
          "name": "getUsers.json",
          "request": {
            "url": "http://api.soundcloud.com/users.json?consumer_key=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns a collection of users"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "070e4d34-1c11-422c-9ca5-7b963694cf8d"
            }
          ]
        },
        {
          "id": "58b79584-d732-4df8-93ae-35d76cd55e36",
          "name": "getUsersUser.json",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.soundcloud.com",
              "path": [
                "users/:user_id.json"
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
            "description": "Returns a user by user id"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "35460c81-dc85-426e-ad28-755353e85fa4"
            }
          ]
        }
      ]
    }
  ]
}