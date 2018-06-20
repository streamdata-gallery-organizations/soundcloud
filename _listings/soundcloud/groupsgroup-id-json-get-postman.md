{
  "info": {
    "name": "Sound Cloud Get Groups",
    "_postman_id": "f4d3b663-4c20-4631-bb43-d815439421ed",
    "description": "Returns a group by group id",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Users",
      "item": [
        {
          "id": "f8e119f9-82d9-409a-9cbf-3246632dad11",
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
              "id": "abb11885-f1f6-4553-b3e4-6b79c200c815"
            }
          ]
        }
      ]
    },
    {
      "name": "Me",
      "item": [
        {
          "id": "30790505-d557-4cee-9100-4037fea5b737",
          "name": "getMeGroups.json",
          "request": {
            "url": "http://api.soundcloud.com/me/groups.json",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns a collection of groups joined by logged-in user"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "b771b025-ea01-4edb-a1e0-6a612e4c7b22"
            }
          ]
        }
      ]
    },
    {
      "name": "Groups",
      "item": [
        {
          "id": "b67835bb-ecae-4b8c-a1ee-20c45e1b2f4a",
          "name": "getGroups.json",
          "request": {
            "url": "http://api.soundcloud.com/groups.json?consumer_key=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns a collection of groups"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "23fb7cd9-fb2b-443c-ac7f-577fcc485f59"
            }
          ]
        },
        {
          "id": "47f66ac7-16e5-44c3-9b2c-5598a85f323b",
          "name": "getGroupsGroup.json",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.soundcloud.com",
              "path": [
                "groups/:group_id.json"
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
                  "id": "group_id",
                  "value": "group_id",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns a group by group id"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "9a8320c5-46ac-4da3-91a5-0774a7bfd566"
            }
          ]
        }
      ]
    }
  ]
}