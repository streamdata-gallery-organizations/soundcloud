{
  "info": {
    "name": "Sound Cloud Put Me. Format",
    "_postman_id": "c4a69099-e6a7-451c-9565-de4e365f2e6b",
    "description": "Updates the logged-in user",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Tracks",
      "item": [
        {
          "id": "587c6eae-a630-497d-8930-39a3d6205e7f",
          "name": "getTracksTrackComments.json",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.soundcloud.com",
              "path": [
                "tracks/:track_id/comments.json"
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
                  "id": "track_id",
                  "value": "track_id",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns comments of a track by track id"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "78bbd97c-e586-4c98-b63c-ec8068f4333a"
            }
          ]
        },
        {
          "id": "76805d25-12e3-4722-8954-e30a851dcbe0",
          "name": "postTracksTrackComments.json",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.soundcloud.com",
              "path": [
                "tracks/:track_id/comments.json"
              ],
              "variable": [
                {
                  "id": "track_id",
                  "value": "track_id",
                  "type": "string"
                }
              ]
            },
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "Posts a comments to a track by track id"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "dd81434f-97f9-48f0-b7f2-eb8bdece132b"
            }
          ]
        },
        {
          "id": "aa7e6b49-d68e-4841-9e87-52bae71e9fce",
          "name": "getTracksTrackComments.Format",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.soundcloud.com",
              "path": [
                "tracks/:track_id/comments.json"
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
                  "id": "track_id",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns comments of a track by track id"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "27140be3-f623-470d-be81-06f0afbe2728"
            }
          ]
        },
        {
          "id": "8bcc0845-0521-46de-8cb3-6bae825bc079",
          "name": "postTracksTrackComments.Format",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.soundcloud.com",
              "path": [
                "tracks/:track_id/comments.json"
              ],
              "variable": [
                {
                  "id": "track_id",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "Posts a comments to a track by track id"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "d93c8d12-2d5a-42f8-94ca-572cfdcc05fe"
            }
          ]
        }
      ]
    },
    {
      "name": "Users",
      "item": [
        {
          "id": "df5a2ffc-e71d-46d8-b986-44035316ec1b",
          "name": "getUsersUserComments.json",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.soundcloud.com",
              "path": [
                "users/:user_id/comments.json"
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
            "description": "Returns a collection of comments made by user id"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "c2639709-531f-430c-acf9-cb97f7e8fed5"
            }
          ]
        },
        {
          "id": "8b170b80-95e1-44d2-bc36-a05a5f6d5ff5",
          "name": "getUsersUserComments.Format",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.soundcloud.com",
              "path": [
                "users/:user_id/comments.json"
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
            "description": "Returns a collection of comments made by user id"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "5579ed30-da02-489f-b979-e5d5cc972423"
            }
          ]
        }
      ]
    },
    {
      "name": "Me",
      "item": [
        {
          "id": "e25a6a8a-bd39-4592-9230-9b1675dec914",
          "name": "getMe.json",
          "request": {
            "url": "http://api.soundcloud.com/me.json",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns the logged-in user"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "5f371ced-19ff-4fd0-8239-6502658ff992"
            }
          ]
        },
        {
          "id": "084a5274-02c2-4c71-b42a-c2370c2a40c2",
          "name": "putMe.json",
          "request": {
            "url": "http://api.soundcloud.com/me.json",
            "method": "PUT",
            "body": {
              "mode": "raw"
            },
            "description": "Updates the logged-in user"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "a5441a93-5b7a-4ac7-b3a3-3a97e91634b8"
            }
          ]
        },
        {
          "id": "52dfd417-85e6-496b-841d-2155c8d97ad2",
          "name": "getMeTracks.json",
          "request": {
            "url": "http://api.soundcloud.com/me/tracks.json",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns a collection of tracks uploaded by logged-in user"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "d2ec9298-8d94-4a6f-a54b-0cb741e3380f"
            }
          ]
        },
        {
          "id": "2a2cdf6b-0169-4d6c-b604-8e100f4fe21a",
          "name": "getMeComments.json",
          "request": {
            "url": "http://api.soundcloud.com/me/comments.json",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns a collection of comments made by logged-in user"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "3874bb26-ff81-416a-ac3a-a925fd9d1ca0"
            }
          ]
        },
        {
          "id": "d289175b-0579-48b7-8c11-d9212a7e4d4f",
          "name": "getMeFollowings.json",
          "request": {
            "url": "http://api.soundcloud.com/me/followings.json",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns a collection of users the logged-in user is following"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "b6028858-a91a-497f-952e-3b66d9e74062"
            }
          ]
        },
        {
          "id": "6e3fe9ba-de82-4501-afda-6a238ae6128c",
          "name": "getMeFollowingsContact.json",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.soundcloud.com",
              "path": [
                "me/followings/:contact_id.json"
              ],
              "variable": [
                {
                  "id": "contact_id",
                  "value": "contact_id",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Checks if the user with the id contact_id is in the logged-in user's list of contacts."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "4e9ba376-eedd-4711-8f68-8f209b0a9d77"
            }
          ]
        },
        {
          "id": "bcc50cac-e78c-4c2b-ab9a-6eb625f403b0",
          "name": "putMeFollowingsContact.json",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.soundcloud.com",
              "path": [
                "me/followings/:contact_id.json"
              ],
              "variable": [
                {
                  "id": "contact_id",
                  "value": "contact_id",
                  "type": "string"
                }
              ]
            },
            "method": "PUT",
            "body": {
              "mode": "raw"
            },
            "description": "Adds the user with the id contact_id to the logged-in user's list of contacts."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "6fe6f002-f83b-44f2-b2e5-4e156acb80de"
            }
          ]
        },
        {
          "id": "838ca4b0-5076-4891-a11d-5684e372057d",
          "name": "deleteMeFollowingsContact.json",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.soundcloud.com",
              "path": [
                "me/followings/:contact_id.json"
              ],
              "variable": [
                {
                  "id": "contact_id",
                  "value": "contact_id",
                  "type": "string"
                }
              ]
            },
            "method": "DELETE",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes the user with the id contact_id from the logged-in user's list of contacts."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "9707f965-c661-4474-bc90-1c788bbc623b"
            }
          ]
        },
        {
          "id": "bf8d6402-87e8-429b-95c3-26b2012b7e77",
          "name": "getMeFollowers.json",
          "request": {
            "url": "http://api.soundcloud.com/me/followers.json",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns a collection of users who follow the logged-in user"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "dacfce0d-b58d-4ca0-b88d-be0710fed8aa"
            }
          ]
        },
        {
          "id": "b9466b5e-76ae-4931-a14b-4fd17321e949",
          "name": "getMeFollowersContact.json",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.soundcloud.com",
              "path": [
                "me/followers/:contact_id.json"
              ],
              "variable": [
                {
                  "id": "contact_id",
                  "value": "contact_id",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Checks if the user with the id contact_id is a follower of the logged-in user"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "da6d2270-4056-4d89-b653-a286d8ed71f1"
            }
          ]
        },
        {
          "id": "006f441d-eea7-4a61-9834-708f6ab7908e",
          "name": "getMeFavorites.json",
          "request": {
            "url": "http://api.soundcloud.com/me/favorites.json",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns a collection of tracks favorited by the logged-in user"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "c22c1ba0-8e90-4d99-b52e-ba93dfea5a8c"
            }
          ]
        },
        {
          "id": "8ad34e2b-cb14-4d28-af9c-2ac979bea8ba",
          "name": "putMeFavoritesTrack.json",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.soundcloud.com",
              "path": [
                "me/favorites/:track_id.json"
              ],
              "variable": [
                {
                  "id": "track_id",
                  "value": "track_id",
                  "type": "string"
                }
              ]
            },
            "method": "PUT",
            "body": {
              "mode": "raw"
            },
            "description": "Adds the given track to the logged-in user's list of favorites."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "96c8a85f-8124-4aca-8c2e-a72f80ff89c4"
            }
          ]
        },
        {
          "id": "7184ceca-606c-4fc6-9177-2a522bdd236c",
          "name": "deleteMeFavoritesTrack.json",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.soundcloud.com",
              "path": [
                "me/favorites/:track_id.json"
              ],
              "variable": [
                {
                  "id": "track_id",
                  "value": "track_id",
                  "type": "string"
                }
              ]
            },
            "method": "DELETE",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes the given track from the logged-in user's list of favorites."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "5c542ede-5152-42ec-a077-dedfc2714473"
            }
          ]
        },
        {
          "id": "dffbb79f-a5bb-4b21-9da2-cd28f2b2d4bf",
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
              "id": "30fa01e1-473b-4ef0-a9a4-8ad251735428"
            }
          ]
        },
        {
          "id": "72239fac-a12d-4010-ba3f-d7c9fcc4268a",
          "name": "getMePlaylists.json",
          "request": {
            "url": "http://api.soundcloud.com/me/playlists.json",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns a collection of playlists created by the logged-in user"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "ad49cc86-b51e-4264-8c0b-901deca1ecdd"
            }
          ]
        },
        {
          "id": "ac9dd793-50c0-420e-8911-db06ca991729",
          "name": "getMe.Format",
          "request": {
            "url": "http://api.soundcloud.com/me.json",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns the logged-in user"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "0a5822b3-7455-49c4-8f6e-ad50e464c656"
            }
          ]
        },
        {
          "id": "b0d82129-ae12-4aee-8cc9-15ca791875a3",
          "name": "putMe.Format",
          "request": {
            "url": "http://api.soundcloud.com/me.json",
            "method": "PUT",
            "body": {
              "mode": "raw"
            },
            "description": "Updates the logged-in user"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "95b954aa-bc6d-4f9e-b0be-16a54e91b355"
            }
          ]
        }
      ]
    },
    {
      "name": "Groups",
      "item": [
        {
          "id": "4a9dab71-f166-4ce2-b1f5-e0e376e89ce5",
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
              "id": "7f375586-fff2-47ff-b3e2-a4bbbecc7ccb"
            }
          ]
        }
      ]
    },
    {
      "name": "Comments",
      "item": [
        {
          "id": "81a2a030-a700-4af7-8bfe-b223b251de02",
          "name": "getCommentsComment.json",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.soundcloud.com",
              "path": [
                "comments/:comment_id.json"
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
                  "id": "comment_id",
                  "value": "comment_id",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns a comment by comment id"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "9f1939ce-c54d-4f62-8a16-f7ce8d67a282"
            }
          ]
        }
      ]
    }
  ]
}