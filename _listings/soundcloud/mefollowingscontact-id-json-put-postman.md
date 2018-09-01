{
  "info": {
    "name": "Sound Cloud Put Me Followings Contact",
    "_postman_id": "edb0a267-ef54-4615-b67a-a6ccf231f07d",
    "description": "Adds the user with the id contact_id to the logged-in user's list of contacts.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Tracks",
      "item": [
        {
          "id": "114b2720-b739-4b06-9b37-16c69bfc6c11",
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
              "id": "515b9ae0-5667-4a26-b716-e2645efe2296"
            }
          ]
        },
        {
          "id": "88dfa486-63b6-47b7-930f-1cc33544ff68",
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
              "id": "19fad5ab-5d51-4ccb-ae0a-6b0d05435c62"
            }
          ]
        }
      ]
    },
    {
      "name": "Users",
      "item": [
        {
          "id": "7d2dd386-e49d-4bd4-a513-c6b9829e0a03",
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
              "id": "d666766f-854b-44c8-920d-ba0ff9cff9c6"
            }
          ]
        }
      ]
    },
    {
      "name": "Me",
      "item": [
        {
          "id": "39864762-e4d1-49af-9f88-d26246c89e3c",
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
              "id": "3c83cb57-a2f0-42e0-8780-b1fc183ed614"
            }
          ]
        },
        {
          "id": "87e35782-270f-40b0-9a06-505a03125513",
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
              "id": "8b86eb90-44de-477b-93b9-8f95c6ccb1a2"
            }
          ]
        },
        {
          "id": "8a8c610a-1a8f-4df0-ad13-f029dd9e9811",
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
              "id": "3bebdf7c-82db-4072-8002-a397795a845f"
            }
          ]
        },
        {
          "id": "743b8f20-3580-4b4f-bd86-1f6a27299ca7",
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
              "id": "9f92c4f8-b4d6-4ac4-9cbd-fa7601dc30ec"
            }
          ]
        },
        {
          "id": "5473f53d-818f-4fea-b7c9-2c1184a5b7a7",
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
              "id": "c13a24ee-1479-48a2-bc35-9f2b5b3da304"
            }
          ]
        },
        {
          "id": "5f6a5c19-7d6f-4500-9c06-89d4c669ed24",
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
              "id": "0ee7154e-23da-44a1-8b2a-49b0c1a62b31"
            }
          ]
        },
        {
          "id": "36f19c75-e3b3-4b4c-bf1e-b688485faf1b",
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
              "id": "4803535d-3392-43e5-ba10-c2d0e1cd031a"
            }
          ]
        }
      ]
    }
  ]
}