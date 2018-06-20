{
  "info": {
    "name": "Sound Cloud Get Users Comments. Format",
    "_postman_id": "76f7ad78-1369-4c1c-8efb-e1f8a19382e1",
    "description": "Returns a collection of comments made by user id",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Tracks",
      "item": [
        {
          "id": "c7a60508-6df4-4e43-86fa-03a7e175b8a2",
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
              "id": "8ae5dfbe-6e66-437e-86c9-65642279dac9"
            }
          ]
        },
        {
          "id": "29bea4c8-2ccd-4515-b5c4-c28b19f6ea1e",
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
              "id": "4ef1bee4-59ef-47f9-85e4-8ee467fff2a9"
            }
          ]
        },
        {
          "id": "94c4f120-2677-4702-9b74-9b016a7f6ae7",
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
              "id": "a1f4622a-2b14-472d-86cc-f38cfb706599"
            }
          ]
        },
        {
          "id": "ae9c8d42-6bdd-4379-93d5-86441ec36bf8",
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
              "id": "4bacff8c-9c17-4b82-b21b-d337e17b7003"
            }
          ]
        }
      ]
    },
    {
      "name": "Users",
      "item": [
        {
          "id": "bd6b6c18-af5e-4013-933d-805105919bcc",
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
              "id": "97e632d6-cf13-4c2e-8b0b-8cbb6f9efad5"
            }
          ]
        },
        {
          "id": "65708dc8-80d0-42f7-86c9-9086d6fcece0",
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
              "id": "e707f09c-86ec-402f-8063-8d38e8694967"
            }
          ]
        }
      ]
    },
    {
      "name": "Me",
      "item": [
        {
          "id": "01e1b784-bdd9-4124-bb7d-04da6fc1b287",
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
              "id": "6ccfd772-c3c7-4ddd-8188-08c74b17818d"
            }
          ]
        }
      ]
    },
    {
      "name": "Comments",
      "item": [
        {
          "id": "e0bba22f-027e-4d03-b869-698f465c28c8",
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
              "id": "c0ccec8e-c3fe-4b76-9392-58f6df7bae22"
            }
          ]
        }
      ]
    }
  ]
}