{
  "info": {
    "name": "SoundCloud Update Me",
    "_postman_id": "b75c516b-81a0-4170-b8d4-687226601c94",
    "description": "Updates the logged-in user",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Audio",
      "item": [
        {
          "id": "cc31278b-b725-412c-a3c1-50720d418784",
          "name": "tracks.json.get",
          "request": {
            "url": "http://api.soundcloud.com/tracks.json?consumer_key=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns a collection of tracks"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "45139db0-6c74-44ce-8bdf-abe7fe63d440"
            }
          ]
        },
        {
          "id": "44f146a1-d053-4571-8034-fd5edc0603a4",
          "name": "tracks.json.post",
          "request": {
            "url": "http://api.soundcloud.com/tracks.json",
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "Uploads a track"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "cc4e6c58-017a-4a32-8cae-8419366310c0"
            }
          ]
        },
        {
          "id": "b59e3ff8-60a2-4a3d-a110-085068acb955",
          "name": "tracks.track_id.json.get",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.soundcloud.com",
              "path": [
                "tracks/:track_id.json"
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
            "description": "Returns a track by track id"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "316ff871-dbca-4a7d-9a12-d7700fd796f3"
            }
          ]
        },
        {
          "id": "58b618ec-625b-47ba-b876-2d41d38f080a",
          "name": "tracks.track_id.json.put",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.soundcloud.com",
              "path": [
                "tracks/:track_id.json"
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
            "description": "Updates a given track"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "62678dcc-738d-458d-9089-bf4968109d63"
            }
          ]
        },
        {
          "id": "181fe9ff-6d07-468d-ad66-e766ac5624c9",
          "name": "tracks.track_id.json.delete",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.soundcloud.com",
              "path": [
                "tracks/:track_id.json"
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
            "description": "Deletes a given track"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "7966ae7f-1f67-437a-a8e7-9e30842a36b2"
            }
          ]
        },
        {
          "id": "acb94813-607b-4cb1-9335-af9b86373347",
          "name": "tracks.track_id.comments.json.get",
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
              "id": "08630197-6189-42ab-a1c1-4a1f8e3b0c07"
            }
          ]
        },
        {
          "id": "995392d2-9730-4560-93eb-61ca1defab0a",
          "name": "tracks.track_id.comments.json.post",
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
              "id": "3de6d647-eeda-4054-bafe-75f66a08f798"
            }
          ]
        },
        {
          "id": "af9f774b-9fbd-4cca-a75a-6ac630f2c963",
          "name": "tracks.track_id.permissions.json.get",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.soundcloud.com",
              "path": [
                "tracks/:track_id/permissions.json"
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
            "description": "Returns all users with permission for a track by track id"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "2da8a137-8fb4-4d04-b62f-78f11c515010"
            }
          ]
        },
        {
          "id": "bb85dd6d-3941-45ff-8e43-96a9d426916f",
          "name": "tracks.track_id.permissions.json.put",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.soundcloud.com",
              "path": [
                "tracks/:track_id/permissions.json"
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
            "description": "Updates the list of permitted users for a track by track id"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "d2e76d83-da90-4102-9fc4-ec743b3531c2"
            }
          ]
        },
        {
          "id": "975c6f92-03dc-4d39-aeb7-9c095f227561",
          "name": "tracks.track_id.secret_token.json.get",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.soundcloud.com",
              "path": [
                "tracks/:track_id/secret-token.json"
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
            "description": "Returns the secret token for a track by track id. This resource can only be used by the track owner."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "baef784e-81aa-4582-99ea-55717ef75504"
            }
          ]
        },
        {
          "id": "95a98968-fe11-4283-9519-b6740c98b2cd",
          "name": "tracks.track_id.secret_token.json.put",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.soundcloud.com",
              "path": [
                "tracks/:track_id/secret-token.json"
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
            "description": "Resets the secret token for a track by track id. The secret token can not be specified but will be randomly chosen on\n          the server and returned. This resource can only be used by the track owner."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "1128980e-bffd-459f-a39e-ce11df278601"
            }
          ]
        },
        {
          "id": "75302763-c96b-4a0d-8211-dff887cf1fee",
          "name": "users.json.get",
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
              "id": "9d5997a4-da37-4e4b-80d6-ef3592ce3aef"
            }
          ]
        },
        {
          "id": "3b84f97b-d525-4897-b4c6-348f67eadf96",
          "name": "users.user_id.json.get",
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
              "id": "fc4be3b3-3224-4a06-8af5-eb6dbd620ca5"
            }
          ]
        },
        {
          "id": "ae34fa18-8a7f-4e34-aefe-926aba54d1db",
          "name": "users.user_id.tracks.json.get",
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
              "id": "43be0779-dcca-4401-a3ab-0a26d2933277"
            }
          ]
        },
        {
          "id": "dcb1f2a3-3201-4aaa-9252-8b6b15e3914a",
          "name": "users.user_id.comments.json.get",
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
              "id": "cf3ad5e6-83f4-4d26-9c84-52c6c693a096"
            }
          ]
        },
        {
          "id": "77cf26e6-e756-451c-a857-30415cfc7318",
          "name": "users.user_id.followings.json.get",
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
              "id": "6128c54f-bb1b-4c6e-82b4-766682af6e71"
            }
          ]
        },
        {
          "id": "7455ce69-b20f-497a-82a4-974530a9939e",
          "name": "users.user_id.followings.contact_id.json.get",
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
              "id": "b34bfa2d-3103-4d69-822b-8a86f000f5a1"
            }
          ]
        },
        {
          "id": "77d03071-e224-493c-bfde-1f87b9b7c9d1",
          "name": "users.user_id.followings.contact_id.json.put",
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
              "id": "afb2852c-54f5-40af-a3bf-f4c06676b54f"
            }
          ]
        },
        {
          "id": "70a5497e-aa9b-4a23-9076-0598815db8fa",
          "name": "users.user_id.followings.contact_id.json.delete",
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
              "id": "fca28b55-4ff0-491d-96cf-f27173f5991e"
            }
          ]
        },
        {
          "id": "323a644d-279b-4e41-a493-d8fd1054b17e",
          "name": "users.user_id.followers.json.get",
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
              "id": "fd15a0b3-2eff-41bd-8f4c-fff4e33f154d"
            }
          ]
        },
        {
          "id": "987a62be-e128-4e0a-af0f-518aff56ee78",
          "name": "users.user_id.followers.contact_id.json.get",
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
              "id": "e3f2de95-9958-41d0-ab75-1d8186b670e9"
            }
          ]
        },
        {
          "id": "33e31bd7-4a1a-4d7b-bf88-e793ed869e1c",
          "name": "users.user_id.favorites.json.get",
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
              "id": "8fea1d8e-bac3-448f-9d90-46c97145674e"
            }
          ]
        },
        {
          "id": "5b4c4aa1-c410-4178-8397-e4118c13fd54",
          "name": "users.user_id.favorites.track_id.json.put",
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
              "id": "8419074a-b9f0-4ec8-a813-df3dd2ce6aee"
            }
          ]
        },
        {
          "id": "fbf5cca3-4881-4adb-abeb-762321b5db73",
          "name": "users.user_id.favorites.track_id.json.delete",
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
              "id": "401acef8-4fc6-41ce-966f-3484011cf416"
            }
          ]
        },
        {
          "id": "0082826d-6da9-4068-9404-487020b579c2",
          "name": "users.user_id.groups.json.get",
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
              "id": "495bfdd4-22ee-4423-a1c9-6610d19565eb"
            }
          ]
        },
        {
          "id": "b05c738d-41b2-4f3d-a210-5480455969be",
          "name": "users.user_id.playlists.json.get",
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
              "id": "1b1f6ffe-a4df-4a49-9916-129f9469f7ec"
            }
          ]
        },
        {
          "id": "bf87a870-052c-4cdc-8021-af425d64b0d0",
          "name": "me.json.get",
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
              "id": "e4ce67f0-cfa0-4390-9d39-5417db6ec436"
            }
          ]
        },
        {
          "id": "227fc18c-8b4d-4867-a834-db37c6594684",
          "name": "me.json.put",
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
              "id": "4b5c8799-766b-4621-99d5-1c9f7cca3696"
            }
          ]
        }
      ]
    }
  ]
}