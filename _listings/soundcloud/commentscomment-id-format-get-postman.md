{
  "info": {
    "name": "Sound Cloud Get Comments . Format",
    "_postman_id": "e462dddc-02c3-43f9-9032-b3d6278f9b20",
    "description": "Returns a comment by comment id",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Tracks",
      "item": [
        {
          "id": "92b3ecd0-d66e-4b2c-9e98-5bd7ad2eff7e",
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
              "id": "bd580db1-06ad-47b6-9481-b6f75220c8d0"
            }
          ]
        },
        {
          "id": "43c1eced-eb6a-4e07-9b22-7eb076ca2bf0",
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
              "id": "c63204da-3304-4b8f-8331-ee845f94caa3"
            }
          ]
        },
        {
          "id": "1885736b-cb3d-4a70-a5fb-fa5d9c6fd5aa",
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
              "id": "98660541-7836-4de0-883b-1c5c4a49acd0"
            }
          ]
        },
        {
          "id": "b4220fe0-b753-4f27-9d58-aa256e200a32",
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
              "id": "6aded7f5-18f6-42b4-bb6c-d8b58c898749"
            }
          ]
        }
      ]
    },
    {
      "name": "Users",
      "item": [
        {
          "id": "8d9da48e-cf49-4922-9033-7cd583dfa7e6",
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
              "id": "e744f041-ad87-432f-a395-3f510b35c752"
            }
          ]
        },
        {
          "id": "1364e7a1-6154-4c12-ba09-c379138350a0",
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
              "id": "f18407d9-d18f-47c5-bdc0-9bfe7d87a4bf"
            }
          ]
        }
      ]
    },
    {
      "name": "Me",
      "item": [
        {
          "id": "397ef8b0-1a11-4ebb-ab4f-a432b13301b3",
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
              "id": "e7b5d55c-8087-43fd-9a6a-abb414809e81"
            }
          ]
        },
        {
          "id": "ae4c432e-a38e-45fc-8a46-45955123d32d",
          "name": "getMeComments.Format",
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
              "id": "22744df2-dbde-41f5-8929-e4a40cda9f48"
            }
          ]
        }
      ]
    },
    {
      "name": "Comments",
      "item": [
        {
          "id": "9d8c849a-90b9-4625-a75c-b198251b3f0b",
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
              "id": "db9365b8-432c-4076-b2bd-e89ac0c105b3"
            }
          ]
        },
        {
          "id": "8cc3a3db-5c8b-4ecd-a650-b0f53d3839cb",
          "name": "getCommentsComment.Format",
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
                },
                {
                  "key": "playlist_id",
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
              "id": "c3e15e6f-31e3-4c6c-8ea8-85029c59f2cd"
            }
          ]
        }
      ]
    }
  ]
}