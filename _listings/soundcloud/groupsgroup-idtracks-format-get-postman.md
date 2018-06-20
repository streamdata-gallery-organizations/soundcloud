{
  "info": {
    "name": "Sound Cloud Get Groups Tracks. Format",
    "_postman_id": "a701eaca-6b73-490f-9980-35e1f032f321",
    "description": "Returns a collection of tracks contributed to the group with group id",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Users",
      "item": [
        {
          "id": "7edcbd6b-4231-4ef0-a432-fa5a71fad996",
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
              "id": "dd4f835d-3481-40ca-b51a-f29ba9e68732"
            }
          ]
        },
        {
          "id": "1200cd89-90ed-4645-9d92-a116625e1b59",
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
              "id": "2e355192-7f55-491f-b8a2-2e519abc9d9c"
            }
          ]
        }
      ]
    },
    {
      "name": "Me",
      "item": [
        {
          "id": "4488ef9a-ba2e-4c24-9d76-ed713441ae13",
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
              "id": "c15986f4-bc78-49de-978c-4e44c63f3aed"
            }
          ]
        },
        {
          "id": "8e29614c-df10-461e-8029-148b7ad85f00",
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
              "id": "ab51ae4f-55eb-4465-a61f-236b94c68f0b"
            }
          ]
        }
      ]
    },
    {
      "name": "Groups",
      "item": [
        {
          "id": "ffa64249-c593-4836-9583-fdae57ac7b0c",
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
              "id": "fe3a0454-9ffb-4ad9-9428-a246ab65683b"
            }
          ]
        },
        {
          "id": "b5da9c69-808e-4793-80c4-32ab8dcf4a36",
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
              "id": "bbed59ea-8cab-42da-b8ac-47abf745052d"
            }
          ]
        },
        {
          "id": "d174f8d8-d3f9-4eef-b6ca-9def7d81b461",
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
              "id": "a599f46a-44b8-4f97-a8a4-6e99e829afe5"
            }
          ]
        },
        {
          "id": "c9c87945-1bd9-4456-9e81-7d928d4db3ac",
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
              "id": "9d582282-d50e-493b-b820-69edfaf7a90f"
            }
          ]
        },
        {
          "id": "461757de-18be-4091-9c7f-234dd51c636f",
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
              "id": "8c7d8057-24a2-4a9c-adba-a809551df3a5"
            }
          ]
        },
        {
          "id": "fbac6705-e76a-4d9a-948d-e1d0f3e5c49e",
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
              "id": "b8b585aa-19d6-49b6-817b-a434ea7c037e"
            }
          ]
        },
        {
          "id": "18f345e8-e17d-4748-98c0-dc11f84fd1bb",
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
              "id": "8495d79a-8a1d-4f67-b583-c514e75aaa9c"
            }
          ]
        },
        {
          "id": "966a6a23-b2a6-46e3-a5d2-a91c1187899a",
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
              "id": "943f9a39-d8da-4ee3-9145-8cc5e4e60d55"
            }
          ]
        },
        {
          "id": "5ea992e6-e728-4058-b7af-1a0159845eee",
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
              "id": "58f902e0-bde5-4587-b48f-d02262a764ce"
            }
          ]
        },
        {
          "id": "9708e4e2-6bd7-4686-a06d-7e26833886f8",
          "name": "getGroupsGroupUsers.Format",
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
            "description": "Returns a combined collection of moderators, members and contributors of the group with group id"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "3e8374f1-aaec-4f14-96ab-a34b5411abf0"
            }
          ]
        },
        {
          "id": "ae118076-922c-4de3-ab94-dfe77cd0174b",
          "name": "getGroupsGroupModerators.Format",
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
            "description": "Returns a collection of moderators of the group with group id"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "033025e7-6f29-483e-8a24-bb4b240b6760"
            }
          ]
        },
        {
          "id": "cef81cce-4b40-43f8-8c78-f6d554058c34",
          "name": "getGroupsGroupMembers.Format",
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
            "description": "Returns a collection of members of the group with group id"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "3cc1bd3e-448c-4b71-96d8-14f2063eaca2"
            }
          ]
        },
        {
          "id": "9ea2b0a7-059b-415d-8eb5-5f7cb024ad14",
          "name": "getGroupsGroupContributors.Format",
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
            "description": "Returns a collection of contributors of the group with group id"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "e51cd443-5cd1-4dda-8d2b-01d6f06d6b4a"
            }
          ]
        },
        {
          "id": "9928b689-bccb-4c26-82fa-57fb44daa858",
          "name": "getGroupsGroupTracks.Format",
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
            "description": "Returns a collection of tracks contributed to the group with group id"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "2d916028-d9d5-4bbd-94df-2aea5cef0009"
            }
          ]
        }
      ]
    }
  ]
}