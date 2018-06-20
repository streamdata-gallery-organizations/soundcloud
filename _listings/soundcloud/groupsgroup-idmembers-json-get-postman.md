{
  "info": {
    "name": "Sound Cloud Get Groups Members",
    "_postman_id": "661c867a-e3b2-43ad-a927-199bd50307af",
    "description": "Returns a collection of members of the group with group id",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Users",
      "item": [
        {
          "id": "110af614-945b-4c64-b9a5-2c2d0c440087",
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
              "id": "e5d6bf22-2f97-4371-a175-96498fc831de"
            }
          ]
        }
      ]
    },
    {
      "name": "Me",
      "item": [
        {
          "id": "5c9e5103-0b24-4fa3-9329-aa943eec2e1a",
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
              "id": "fa9a10f7-105d-4998-97f5-7301d843ea4d"
            }
          ]
        }
      ]
    },
    {
      "name": "Groups",
      "item": [
        {
          "id": "dad9c947-fe91-4d0a-9a65-4578d249a4a5",
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
              "id": "ed25b4cf-26fe-48f4-82de-a56ef735c15b"
            }
          ]
        },
        {
          "id": "4f1da3f3-5d5c-4982-8bf1-009084145bf0",
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
              "id": "bf63346d-7913-4ad6-80fe-6be30179ce37"
            }
          ]
        },
        {
          "id": "614ef7f1-994a-409a-bda3-26d8736a5c1f",
          "name": "getGroupsGroupUsers.json",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.soundcloud.com",
              "path": [
                "groups/:group_id/users.json"
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
            "description": "Returns a combined collection of moderators, members and contributors of the group with group id"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "b3c55323-51a2-4e2b-ab54-c394b4572eee"
            }
          ]
        },
        {
          "id": "dc9cddd6-412c-4aa7-b8b2-5aed6263c4d8",
          "name": "getGroupsGroupModerators.json",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.soundcloud.com",
              "path": [
                "groups/:group_id/moderators.json"
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
            "description": "Returns a collection of moderators of the group with group id"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "49363448-0ed3-454f-98bf-4e5110a2f4a4"
            }
          ]
        },
        {
          "id": "d11fb854-5fbe-45e5-b278-5619ecd6db03",
          "name": "getGroupsGroupMembers.json",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.soundcloud.com",
              "path": [
                "groups/:group_id/members.json"
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
            "description": "Returns a collection of members of the group with group id"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "32116ef7-7099-44e3-88a6-8e29ad298f15"
            }
          ]
        }
      ]
    }
  ]
}