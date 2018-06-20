{
  "info": {
    "name": "Sound Cloud Get Users Followings. Format",
    "_postman_id": "8cdb0daf-e3a2-4013-8589-4e3c2819690d",
    "description": "Returns a collection of users the user with user id is following",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Users",
      "item": [
        {
          "id": "a9eb18d2-dc4c-43f0-be11-6a8acae5c5ee",
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
              "id": "a4d20509-adb4-4f2c-9d65-8af9db6de08a"
            }
          ]
        },
        {
          "id": "a85719d7-4b49-4d9b-96d2-0ffee12604b3",
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
              "id": "79072622-470f-42d3-9283-70421e0c9972"
            }
          ]
        },
        {
          "id": "862bf270-f7b2-41c4-93fa-b90cc3e09523",
          "name": "getUsersUserTracks.json",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.soundcloud.com",
              "path": [
                "users/:user_id/tracks.json"
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
            "description": "Returns a collection of tracks uploaded by user id"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "3cbe7968-d4aa-46a8-b985-58fba79dc878"
            }
          ]
        },
        {
          "id": "370aaf97-accc-436e-a935-7142d8cc5419",
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
              "id": "5978a5a7-0fff-433b-9b35-07c2ba849111"
            }
          ]
        },
        {
          "id": "e6ba3695-82b5-4680-8a5f-bb01f5d80c3b",
          "name": "getUsersUserFollowings.json",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.soundcloud.com",
              "path": [
                "users/:user_id/followings.json"
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
            "description": "Returns a collection of users the user with user id is following"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "4d57ceba-2622-4d0a-a09a-fc9b5d010eb9"
            }
          ]
        },
        {
          "id": "8128aae8-d08f-4e10-8303-cc7d2fd289d6",
          "name": "getUsersUserFollowingsContact.json",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.soundcloud.com",
              "path": [
                "users/:user_id/followings/:contact_id.json"
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
                },
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
            "description": "Checks if the user with the id contact_id is in the givens user's list of contacts."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "d79c0583-0e64-4f50-8980-e6c3a97623f4"
            }
          ]
        },
        {
          "id": "92f3cafc-5b09-4ebc-83c1-1b1a0a7b0f05",
          "name": "putUsersUserFollowingsContact.json",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.soundcloud.com",
              "path": [
                "users/:user_id/followings/:contact_id.json"
              ],
              "variable": [
                {
                  "id": "user_id",
                  "value": "user_id",
                  "type": "string"
                },
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
            "description": "Adds the user with the id contact_id to the givens user's list of contacts."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "8670801c-79b7-4d24-a4a8-1e55c44e95b7"
            }
          ]
        },
        {
          "id": "a01cfe89-165c-4672-96a8-ef35cb048784",
          "name": "deleteUsersUserFollowingsContact.json",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.soundcloud.com",
              "path": [
                "users/:user_id/followings/:contact_id.json"
              ],
              "variable": [
                {
                  "id": "user_id",
                  "value": "user_id",
                  "type": "string"
                },
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
            "description": "Removes the user with the id contact_id from the givens user's list of contacts."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "d60877bb-33e6-43b0-a38b-64cc9a5232bc"
            }
          ]
        },
        {
          "id": "253fbf61-1421-4dec-aa37-42a38236d199",
          "name": "getUsersUserFollowers.json",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.soundcloud.com",
              "path": [
                "users/:user_id/followers.json"
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
            "description": "Returns a collection of users who follow the user with user id"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "d08ed760-8dbd-4040-80e2-2cc6bab80653"
            }
          ]
        },
        {
          "id": "86af4852-a51e-4ea0-87e5-6367a2ffb358",
          "name": "getUsersUserFollowersContact.json",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.soundcloud.com",
              "path": [
                "users/:user_id/followers/:contact_id.json"
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
                },
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
            "description": "Checks if the user with contact_id is a follower of the given user."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "de0f9102-f866-4759-9467-38ca0d46d629"
            }
          ]
        },
        {
          "id": "9c80ee0e-ce07-4ec0-9832-68f6b1c0969f",
          "name": "getUsersUserFavorites.json",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.soundcloud.com",
              "path": [
                "users/:user_id/favorites.json"
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
            "description": "Returns a collection of tracks favorited by the user with user id"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "006c495e-97ef-4a70-a37f-a18947694cb2"
            }
          ]
        },
        {
          "id": "16ceb2c4-26bd-476a-81e9-502017f7d2a2",
          "name": "putUsersUserFavoritesTrack.json",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.soundcloud.com",
              "path": [
                "users/:user_id/favorites/:track_id.json"
              ],
              "variable": [
                {
                  "id": "user_id",
                  "value": "user_id",
                  "type": "string"
                },
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
            "description": "Adds the given track to the given user's list of favorites."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "99109695-f0c8-4fa6-b2c9-d2ea650e1a7a"
            }
          ]
        },
        {
          "id": "ced387e7-edfd-47f6-bdc5-b4224125c41b",
          "name": "deleteUsersUserFavoritesTrack.json",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.soundcloud.com",
              "path": [
                "users/:user_id/favorites/:track_id.json"
              ],
              "variable": [
                {
                  "id": "user_id",
                  "value": "user_id",
                  "type": "string"
                },
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
            "description": "Deletes the given track from the given user's list of favorites."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "263a326f-6a6d-435a-80ec-ff1d7adba304"
            }
          ]
        },
        {
          "id": "194c3ec8-16c8-450a-b11f-e5ca394b5b95",
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
              "id": "168cf1b0-915e-4a81-a541-3440251d9b32"
            }
          ]
        },
        {
          "id": "f5e4ce15-9f54-4f06-90ca-e3355c115be6",
          "name": "getUsersUserPlaylists.json",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.soundcloud.com",
              "path": [
                "users/:user_id/playlists.json"
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
            "description": "Returns a collection of playlists created by user with user id"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "b35f1d5d-93c4-4391-99e2-c70fddefed05"
            }
          ]
        },
        {
          "id": "8c6338e2-6726-44d6-80ce-7b59e67cb1b2",
          "name": "getUsers.Format",
          "request": {
            "url": "http://api.soundcloud.com/users.json?consumer_key=%7B%7D&q=%7B%7D",
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
              "id": "1edfc452-fbb8-46db-a72b-45df278c434b"
            }
          ]
        },
        {
          "id": "643c410a-1152-477e-9f51-704581af99ec",
          "name": "getUsersUser.Format",
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
                  "value": "{}",
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
              "id": "2f72cfcd-4ec7-4c38-8983-d684ac2c9244"
            }
          ]
        },
        {
          "id": "6b479fcb-c23e-42df-93cd-e1085e5a63ba",
          "name": "getUsersUserTracks.Format",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.soundcloud.com",
              "path": [
                "users/:user_id/tracks.json"
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
            "description": "Returns a collection of tracks uploaded by user id"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "469421dc-a3bc-4111-bc25-66d8f146a5bd"
            }
          ]
        },
        {
          "id": "61110175-90d4-454a-bb77-642bc56788aa",
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
              "id": "98368628-9e24-40e1-b4ae-cc3da55a28dc"
            }
          ]
        },
        {
          "id": "43f8d3ed-bb47-42f8-891b-ab7339d6af68",
          "name": "getUsersUserFollowings.Format",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.soundcloud.com",
              "path": [
                "users/:user_id/followings.json"
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
            "description": "Returns a collection of users the user with user id is following"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "1eeca8ac-4db2-475d-98a2-f95c749c4a08"
            }
          ]
        }
      ]
    },
    {
      "name": "Groups",
      "item": [
        {
          "id": "557b26a5-ba4f-4632-8523-8df2c7bb7e6b",
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
              "id": "5865c7c2-c15e-4cef-b306-4c1e22b7b038"
            }
          ]
        }
      ]
    }
  ]
}