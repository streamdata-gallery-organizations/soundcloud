{
  "info": {
    "name": "Sound Cloud Get Tracks Track",
    "_postman_id": "bfcfffe3-da8c-4389-a0bc-faf0600a9fbe",
    "description": "Returns a track by track id",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Tracks",
      "item": [
        {
          "id": "ceee4ee5-cbbd-46d6-84b0-bd3da56cd14d",
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
              "id": "0077f74f-8bf6-46a3-aad3-cc52b8425c70"
            }
          ]
        },
        {
          "id": "4155e1c9-7d82-4bcc-95b9-2cab80f6d073",
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
              "id": "6a0b5583-b997-446e-b177-d6ff2576a79a"
            }
          ]
        },
        {
          "id": "f7fa3f24-7062-48f5-bb57-254d4646c56d",
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
              "id": "f642b7bd-fdc0-4d3f-9d84-142111d142be"
            }
          ]
        }
      ]
    }
  ]
}