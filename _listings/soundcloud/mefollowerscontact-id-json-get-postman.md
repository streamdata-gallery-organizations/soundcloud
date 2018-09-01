{
  "info": {
    "name": "Sound Cloud Get Me Followers Contact",
    "_postman_id": "8d9a5a4c-0f2e-4f18-baf2-85141352f05d",
    "description": "Checks if the user with the id contact_id is a follower of the logged-in user",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Tracks",
      "item": [
        {
          "id": "bc201d41-e254-4cd4-a2cf-9d2fd7dfc67a",
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
              "id": "9c08eb3e-52de-47ec-b367-f70db407f6a7"
            }
          ]
        },
        {
          "id": "56eadf8e-6e1d-4d4a-818f-25ba8a5796f3",
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
              "id": "cdfce7dc-5a80-47e7-9b6b-a907e41aec26"
            }
          ]
        }
      ]
    },
    {
      "name": "Users",
      "item": [
        {
          "id": "017c8ce5-ffce-40c1-ad31-6d94f6f0d8b2",
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
              "id": "cd5cae55-53f5-4491-965e-1b0584046586"
            }
          ]
        }
      ]
    },
    {
      "name": "Me",
      "item": [
        {
          "id": "c145cd6a-cb36-494e-9f41-e64e5d754c52",
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
              "id": "821854b8-7b10-4347-89be-7d9ab3969f43"
            }
          ]
        },
        {
          "id": "8749aa3d-5b93-4f3b-b2ef-fcda2505e287",
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
              "id": "59b74b02-0910-4297-8d98-cd41adbf4bf9"
            }
          ]
        },
        {
          "id": "20ecdbf3-4d9c-432e-9185-730f0e8fd33b",
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
              "id": "5f723835-3946-4d64-8411-9f76479bc6ad"
            }
          ]
        },
        {
          "id": "39ad20bf-af4b-4c9b-a5b2-5ae1fbbcf266",
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
              "id": "c53aa645-d366-42fe-abfc-9b56696b6e7c"
            }
          ]
        },
        {
          "id": "1de4e79a-c2d1-4998-ba81-374d0d89054f",
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
              "id": "6d1cb268-4a1c-4d92-a257-c5f31a3ad120"
            }
          ]
        },
        {
          "id": "74c62ce9-7888-42ee-9e4e-2c4d06919129",
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
              "id": "18b225ab-d718-47e9-960a-7ddb3151e81e"
            }
          ]
        },
        {
          "id": "8a074217-5285-4c5b-9500-e637b7dea273",
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
              "id": "637e4e86-8491-4637-a59a-9c2d66edf6f4"
            }
          ]
        },
        {
          "id": "2d86069a-79d9-4914-a366-b108665f183c",
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
              "id": "24ce7ea3-69be-4f78-b50f-3dfdefc43e6d"
            }
          ]
        },
        {
          "id": "a8a20a82-286d-4f26-af02-ef6544a88a86",
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
              "id": "1bbfa08a-c772-4c47-b203-252b0ebbf073"
            }
          ]
        },
        {
          "id": "c0fcdb01-e214-48ea-a369-b2d292fc302f",
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
              "id": "95c0dfbd-1083-4d1b-a86a-5243b8342eb0"
            }
          ]
        }
      ]
    }
  ]
}