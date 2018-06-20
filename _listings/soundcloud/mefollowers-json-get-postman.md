{
  "info": {
    "name": "Sound Cloud Get Me Followers",
    "_postman_id": "44393bdd-03af-4f4d-999b-67581c513e3f",
    "description": "Returns a collection of users who follow the logged-in user",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Tracks",
      "item": [
        {
          "id": "b8711af5-bb11-40f8-8827-9a662653412a",
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
              "id": "366b279a-a0ce-4fc0-b5ee-779b4dd6d236"
            }
          ]
        },
        {
          "id": "c88f1d0b-2414-4a01-aa68-dc8df282157b",
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
              "id": "f7d52a4f-2893-4ff3-b130-329a82547863"
            }
          ]
        }
      ]
    },
    {
      "name": "Users",
      "item": [
        {
          "id": "1499748b-10f9-44f1-99b9-d00a4fcbe9cc",
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
              "id": "e2b429ce-cf36-4e83-ae34-50d28ad03afb"
            }
          ]
        }
      ]
    },
    {
      "name": "Me",
      "item": [
        {
          "id": "598a2421-4185-458b-b1d0-baa79ba6b7dc",
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
              "id": "97c77d89-91ef-4bba-a5a3-aa5c930a3a5d"
            }
          ]
        },
        {
          "id": "c2a5e24c-fa0c-4cdd-a634-2aa2d4618ca5",
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
              "id": "cc254fd2-0de6-48be-b21b-cb7b7f8ea18e"
            }
          ]
        },
        {
          "id": "1a74b01b-a076-4b9c-a04e-8e8c0822408c",
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
              "id": "d97a5e3d-2e4e-4269-a08d-25f637fd8cfa"
            }
          ]
        },
        {
          "id": "7259f435-4e50-4d41-8983-6f16decb55ea",
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
              "id": "52ca7e64-af9c-4258-84c8-b88a5c0f03a0"
            }
          ]
        },
        {
          "id": "14abdf9b-865d-4019-a380-2cd423dd73a7",
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
              "id": "c7745bbb-8bfd-4ed4-aa27-1e377659012f"
            }
          ]
        },
        {
          "id": "6b5c3c3e-795e-4aad-8731-203560a39a8c",
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
              "id": "bb94a3cf-58f3-400b-92f8-31801b382cfd"
            }
          ]
        },
        {
          "id": "1d3ba55c-b6ae-402f-8903-8665deddace0",
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
              "id": "784d26e9-06bb-4ffd-bc92-8d5d6f94f6bf"
            }
          ]
        },
        {
          "id": "095729df-5c4a-4720-b21c-a0afe3121613",
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
              "id": "4d6841a0-6fde-4478-bc3f-c336ea21900c"
            }
          ]
        },
        {
          "id": "666fa3ba-4a9e-42b3-bd65-508ac0e28731",
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
              "id": "04e7e1dc-7db8-415a-b04c-e36c2cc2e232"
            }
          ]
        }
      ]
    }
  ]
}