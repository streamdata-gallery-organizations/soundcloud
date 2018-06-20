{
  "info": {
    "name": "Sound Cloud Get Groups . Format",
    "_postman_id": "c5e7e0b7-3b11-45b6-ba52-95e73b66279d",
    "description": "Returns a group by group id",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Users",
      "item": [
        {
          "id": "1a2baab5-8557-4b40-9438-3a8217ca557e",
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
              "id": "4403bfb5-30c5-4638-aa62-a70020e5dfb2"
            }
          ]
        },
        {
          "id": "9f50db2d-8ef6-4c26-90f2-3ea310128952",
          "name": "getUsersUserGroups.Format",
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
                  "value": "{}",
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
              "id": "4ea21d16-eb70-4248-9b1c-1b9605dbd65c"
            }
          ]
        }
      ]
    },
    {
      "name": "Me",
      "item": [
        {
          "id": "f921d500-b364-4c7d-9843-75d7ddc4759a",
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
              "id": "5cbdced3-4a9f-4e33-b40c-0d1f43e2bb12"
            }
          ]
        },
        {
          "id": "efd1baf3-f692-4a38-a035-20a09e387ccd",
          "name": "getMeGroups.Format",
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
              "id": "ac02bd67-f939-415b-9a87-c17a04342b27"
            }
          ]
        }
      ]
    },
    {
      "name": "Groups",
      "item": [
        {
          "id": "39b6f114-163a-461e-ba4f-62c058324e18",
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
              "id": "59d4b141-dba7-4d8b-a426-89f8189a9caa"
            }
          ]
        },
        {
          "id": "2687374c-350b-485a-956d-25aa79e70130",
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
              "id": "7fdddf6d-67c4-407c-b3be-87efb9b407f4"
            }
          ]
        },
        {
          "id": "e8281206-670d-4916-8976-62aa45872d5f",
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
              "id": "5484a640-b945-467e-affd-c9f64f6adaf2"
            }
          ]
        },
        {
          "id": "937daeca-784b-4619-bddc-764e74e102f3",
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
              "id": "4708c77e-5ff9-4185-9ba9-80b84aff8db8"
            }
          ]
        },
        {
          "id": "f12889ab-5822-4aae-9616-406abd25a5a4",
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
              "id": "6b032b3e-fc3d-4967-b90a-f3e3faf9aeea"
            }
          ]
        },
        {
          "id": "559a3b49-1233-4264-b89d-ab11ae560166",
          "name": "getGroupsGroupContributors.json",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.soundcloud.com",
              "path": [
                "groups/:group_id/contributors.json"
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
            "description": "Returns a collection of contributors of the group with group id"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "6279ddc3-4746-420b-b231-590dac1b69b5"
            }
          ]
        },
        {
          "id": "02ef5e91-26d0-4eb8-a9c2-6d618aac9e89",
          "name": "getGroupsGroupTracks.json",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.soundcloud.com",
              "path": [
                "groups/:group_id/tracks.json"
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
            "description": "Returns a collection of tracks contributed to the group with group id"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "c795d819-de6e-4f05-b94c-543419707a72"
            }
          ]
        },
        {
          "id": "7fdfba36-331d-4bf4-bd78-23fb24beeb6e",
          "name": "getGroups.Format",
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
              "id": "3c9c096b-d509-4a43-8926-92ed80fa4cdc"
            }
          ]
        },
        {
          "id": "ea6acc24-5943-419d-a478-320526ee252c",
          "name": "getGroupsGroup.Format",
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
                },
                {
                  "key": "playlist_id",
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
              "id": "62c36cea-3af1-44e5-93b1-a3f78c2eceef"
            }
          ]
        }
      ]
    }
  ]
}