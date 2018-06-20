{
  "info": {
    "name": "Sound Cloud Delete Tracks Track . Format",
    "_postman_id": "0a12449e-76c8-4331-9f5b-ef703aa0b2bc",
    "description": "Delete tracks track . format.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Tracks",
      "item": [
        {
          "id": "3407b87b-eacd-4926-9518-2aca9163a14c",
          "name": "getTracks.json",
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
              "id": "3b180697-fb5d-465b-b5b6-be3aa7ef6f47"
            }
          ]
        },
        {
          "id": "63e1e7ed-94b0-4a68-9572-d6b941d4136c",
          "name": "postTracks.json",
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
              "id": "38135700-7c0a-40f0-b908-267412b4336d"
            }
          ]
        },
        {
          "id": "516755e6-dccb-4a2c-a912-d72a86295c90",
          "name": "getTracksTrack.json",
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
              "id": "eb1ecea9-0a79-4acb-a999-2d8eca74b11b"
            }
          ]
        },
        {
          "id": "e7c8bb2f-7f14-4616-b3d0-12ae2b63dedb",
          "name": "putTracksTrack.json",
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
              "id": "d6b4d762-bc6e-45fc-a69f-a29334ac29b0"
            }
          ]
        },
        {
          "id": "fb6b4907-3381-44e9-8e5f-8ac3ef6a8f5c",
          "name": "deleteTracksTrack.json",
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
              "id": "4ea98da7-996d-49e9-b042-26688b07d236"
            }
          ]
        },
        {
          "id": "a3cff258-3810-4dcf-84e2-003373ae08a8",
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
              "id": "546dd8f3-bd94-42a4-9be6-024d54e87082"
            }
          ]
        },
        {
          "id": "c75def9c-cc10-4cf8-be0d-e2e807db2d4b",
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
              "id": "f6a6e748-2253-4475-b562-7d0fb489fbc6"
            }
          ]
        },
        {
          "id": "4cccf444-11fe-4a53-b3c4-4a8322339faa",
          "name": "getTracksTrackPermissions.json",
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
              "id": "e685b7dd-e60f-44cf-9c90-73a55c23deb8"
            }
          ]
        },
        {
          "id": "7dbc3866-44c1-4243-a465-04975d3e55e0",
          "name": "putTracksTrackPermissions.json",
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
              "id": "6ffcd2fb-2433-4f2c-9b3b-71bf3f089194"
            }
          ]
        },
        {
          "id": "dec59828-10de-411e-adea-cb159f7a6e67",
          "name": "getTracksTrackSecretToken.json",
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
              "id": "2751bf78-e2ac-4a89-ac7e-eb4ada687991"
            }
          ]
        },
        {
          "id": "b529c44c-f9e0-47c5-8aee-ff9e04494a39",
          "name": "putTracksTrackSecretToken.json",
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
              "id": "2e1849e6-de58-4b3e-be8d-e69d4541783a"
            }
          ]
        },
        {
          "id": "dd650ea7-d5b3-4c7c-89e6-d7aef408239c",
          "name": "getTracks.Format",
          "request": {
            "url": "http://api.soundcloud.com/tracks.json?bpm-from=%7B%7D&bpm-to=%7B%7D&consumer_key=%7B%7D&created_at-from=%7B%7D&created_at-to=%7B%7D&duration-from=%7B%7D&duration-to=%7B%7D&filter=%7B%7D&ids=%7B%7D&order=%7B%7D&q=%7B%7D&tags=%7B%7D",
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
              "id": "fc540f0d-9fdb-41dd-8bce-3416861231c7"
            }
          ]
        },
        {
          "id": "20a6b813-9915-49ab-871f-2a87af3277a7",
          "name": "postTracks.Format",
          "request": {
            "url": "http://api.soundcloud.com/tracks.json?asset_data=%7B%7D&title=%7B%7D",
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "Post tracks. format."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "12d7a542-3af5-432b-a105-35816339d780"
            }
          ]
        },
        {
          "id": "436de238-93b4-4acc-9426-5e2c99f6c000",
          "name": "getTracksTrack.Format",
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
                  "value": "{}",
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
              "id": "7b1c6488-980f-4593-956d-24a11c421189"
            }
          ]
        },
        {
          "id": "57cade5f-ae35-4ae2-9641-7e4cabe90492",
          "name": "putTracksTrack.Format",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.soundcloud.com",
              "path": [
                "tracks/:track_id.json"
              ],
              "query": [
                {
                  "key": "asset_data",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "title",
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
            "method": "PUT",
            "body": {
              "mode": "raw"
            },
            "description": "Put tracks track . format."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "becc4a19-735d-4a88-befb-a77f84f64e26"
            }
          ]
        },
        {
          "id": "81c9ff14-0736-460f-b442-f5b68d75cd62",
          "name": "deleteTracksTrack.Format",
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
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "DELETE",
            "body": {
              "mode": "raw"
            },
            "description": "Delete tracks track . format."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "c3ec4732-d1e1-48a7-9d60-9bd4c89c5899"
            }
          ]
        }
      ]
    },
    {
      "name": "Users",
      "item": [
        {
          "id": "5909893b-18c6-466e-bbd8-ded087af298b",
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
              "id": "8e09707a-9020-4333-9747-a7f5cb950244"
            }
          ]
        }
      ]
    },
    {
      "name": "Me",
      "item": [
        {
          "id": "8c09f8bf-4bad-48d8-be5a-756280243a11",
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
              "id": "22bb2e83-6611-4183-90d6-0298c9b2dcc1"
            }
          ]
        }
      ]
    },
    {
      "name": "Groups",
      "item": [
        {
          "id": "d398565e-402c-4aa2-a17a-5b1f7eab5361",
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
              "id": "4c0f9fde-3f40-4714-9948-3340cf16a6ad"
            }
          ]
        }
      ]
    }
  ]
}