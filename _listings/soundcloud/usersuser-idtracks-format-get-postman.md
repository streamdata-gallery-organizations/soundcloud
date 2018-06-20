{
  "info": {
    "name": "Sound Cloud Get Users Tracks. Format",
    "_postman_id": "fc7c705b-fcc8-4f67-a08b-f011ad3f7791",
    "description": "Returns a collection of tracks uploaded by user id",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Tracks",
      "item": [
        {
          "id": "f9694241-512b-4871-a030-ea67d4166115",
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
              "id": "7a48e1e9-4fca-41f8-8e98-b8bfc7f7c3e4"
            }
          ]
        },
        {
          "id": "16a1faad-b8b3-4227-bcc2-db206f3f144a",
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
              "id": "94449d34-f1a8-40f3-8741-2ed53537aa01"
            }
          ]
        },
        {
          "id": "7d196081-9aae-41c3-a004-90949d6f1b5e",
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
              "id": "101384ec-5ba0-4d31-9775-c1626dc32361"
            }
          ]
        },
        {
          "id": "a0a90af4-16bd-4de8-a746-882714406d0d",
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
              "id": "eb6da47d-c58a-4b1e-bc85-d80ee2f0b830"
            }
          ]
        },
        {
          "id": "abb2e5d5-201e-43fc-a088-66c7ff277eee",
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
              "id": "bf27df59-de32-4b5f-9eed-3d802a1322ad"
            }
          ]
        },
        {
          "id": "c2b7468d-42a3-4820-8b5f-6e12b4487e9d",
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
              "id": "f124498d-4325-4d08-9fd2-b992928875f4"
            }
          ]
        },
        {
          "id": "2ffdcae7-52c4-44cc-8d01-27495989c76a",
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
              "id": "6afba43b-c7c8-44de-90d9-2c6778a0450f"
            }
          ]
        },
        {
          "id": "5a11b5c1-7e02-4c6a-8342-d64767f1498c",
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
              "id": "129888b4-24ce-4f87-91ba-26505a793a81"
            }
          ]
        },
        {
          "id": "ea84efa2-febd-4b4c-93a6-f252c6bffa41",
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
              "id": "96192f65-aa83-4957-85b4-d2478ef84ff5"
            }
          ]
        },
        {
          "id": "a91a53b4-0a98-4917-96e5-39046ac2d27d",
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
              "id": "8f921c1b-a1fe-4246-b2a1-645078c53eba"
            }
          ]
        },
        {
          "id": "a79131ca-ed64-4c0a-9271-55521d24662c",
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
              "id": "af808335-3f0c-42b7-97c9-c016238c9136"
            }
          ]
        },
        {
          "id": "ec94e76a-7b7d-4736-8ff9-78b758d0562f",
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
              "id": "899e6b76-e687-49d0-9fcf-c6af9c5e6e1c"
            }
          ]
        },
        {
          "id": "5f09752e-e68b-4a20-a8e6-889e07c0422b",
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
              "id": "311f059f-c44a-422b-9c5e-6fc7bc3723ff"
            }
          ]
        },
        {
          "id": "9cd908d6-6c83-4655-8e23-698b19208c2a",
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
              "id": "23b9a350-36eb-451a-9dd1-8020b9481766"
            }
          ]
        },
        {
          "id": "d31d21fe-fd7e-4f8d-aacb-9fd69f2b11b6",
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
              "id": "50c97453-195c-405f-ac19-4167978657f7"
            }
          ]
        },
        {
          "id": "89623319-28bf-44d2-bb4f-f96b4897acb8",
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
              "id": "9cf94e0e-2f11-4219-8ae8-d073c9222903"
            }
          ]
        },
        {
          "id": "6a5d52f4-05f6-4d04-a132-7bb53a478af7",
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
              "id": "888b172a-df64-4011-b808-273b00c750ea"
            }
          ]
        },
        {
          "id": "c277c79d-17b5-4b79-ba81-fd8af2285d5d",
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
              "id": "aa66de52-4cd8-40f9-a08a-fc4e3d49cdd1"
            }
          ]
        },
        {
          "id": "2600b3cb-d8bb-42e5-b047-7b9b643bcf9c",
          "name": "getTracksTrackPermissions.Format",
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
                  "value": "{}",
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
              "id": "95c9864a-de24-4868-9ec7-1491f92e097d"
            }
          ]
        },
        {
          "id": "45fd727c-8fcc-446c-bb28-0d8f29c04ab0",
          "name": "putTracksTrackPermissions.Format",
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
                  "value": "{}",
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
              "id": "51f11d86-d902-4f9b-9d78-fca2558fba7b"
            }
          ]
        },
        {
          "id": "198a9175-f207-4269-aca5-167e28441e5c",
          "name": "getTracksTrackSecretToken.Format",
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
                  "value": "{}",
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
              "id": "0f7f7b92-522a-4569-be46-44a783fbc7c8"
            }
          ]
        },
        {
          "id": "7713d244-4cbb-46b5-abae-9dc752ac22ba",
          "name": "putTracksTrackSecretToken.Format",
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
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "PUT",
            "body": {
              "mode": "raw"
            },
            "description": "Resets the secret token for a track by track id. The secret token can not be specified but will be randomly chosen on\n                    the server and returned. This resource can only be used by the track owner."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "afb549fd-0ab3-49f7-a069-a31f68729fd6"
            }
          ]
        }
      ]
    },
    {
      "name": "Users",
      "item": [
        {
          "id": "03b3566b-7af3-43a9-9013-f4262237f986",
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
              "id": "1cdfbe69-4877-42d3-b62d-e22273fd3eaf"
            }
          ]
        },
        {
          "id": "0d52ef0a-e0a6-4fe9-94eb-ce3067dc6836",
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
              "id": "64bcfb51-7c7d-4414-8f13-d628e2fc1c6d"
            }
          ]
        }
      ]
    },
    {
      "name": "Me",
      "item": [
        {
          "id": "68872dff-10f6-4c86-8dd1-2f4e949e745c",
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
              "id": "c899a7ee-6bdc-48dd-b674-c26695666806"
            }
          ]
        }
      ]
    },
    {
      "name": "Groups",
      "item": [
        {
          "id": "a2d62fcc-7f1d-4c83-9a4d-0656c387ec63",
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
              "id": "e8809fd0-333f-40b0-a961-30e335afd2fc"
            }
          ]
        }
      ]
    }
  ]
}