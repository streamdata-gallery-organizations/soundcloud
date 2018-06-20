{
  "info": {
    "name": "Sound Cloud Get Me Followings Contact",
    "_postman_id": "bb24daa7-ed35-4e00-a85f-9d0f7a83b8d2",
    "description": "Checks if the user with the id contact_id is in the logged-in user's list of contacts.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Tracks",
      "item": [
        {
          "id": "19ff442e-fb8f-497a-996f-e41440f65e53",
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
              "id": "b5f04243-6f78-4a19-95f7-1333e9a66bcd"
            }
          ]
        },
        {
          "id": "84e610cf-c826-4c85-8886-00a9ec5db53c",
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
              "id": "8906b239-80b7-41c1-96b0-e2c7c68a8e97"
            }
          ]
        }
      ]
    },
    {
      "name": "Users",
      "item": [
        {
          "id": "6133eaec-0e2d-4eb8-a3fd-713ebae8a0bf",
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
              "id": "e131c08c-aaa8-4311-b7e3-ca8f9ecc380c"
            }
          ]
        }
      ]
    },
    {
      "name": "Me",
      "item": [
        {
          "id": "5949e786-0a09-49f8-b7af-5243d5b9f72b",
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
              "id": "d11aff49-88ff-4014-a366-a321a636aa77"
            }
          ]
        },
        {
          "id": "780560be-22c9-448c-a4de-0e06fa931a7f",
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
              "id": "245d8338-797b-4a55-9c2d-ca0622486f0a"
            }
          ]
        },
        {
          "id": "17b653bd-12a2-4972-9b36-7de101e5c8be",
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
              "id": "7d80ae38-da96-451a-a05a-c9b04bf213b5"
            }
          ]
        },
        {
          "id": "5e4b75cb-2231-42ea-b2b7-36e8048e81c1",
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
              "id": "b46d9ec3-d22f-4ef6-bf42-9cc03f4f08db"
            }
          ]
        },
        {
          "id": "1105232c-7f50-497d-9324-5ed589f1ba39",
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
              "id": "0d9fd998-84b2-47d1-9a36-c6692419022c"
            }
          ]
        },
        {
          "id": "1266b548-3198-4a6f-a13c-76cc33b700b9",
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
              "id": "f23fae82-90b9-4f67-ad48-ffbcb5cb7eae"
            }
          ]
        }
      ]
    }
  ]
}