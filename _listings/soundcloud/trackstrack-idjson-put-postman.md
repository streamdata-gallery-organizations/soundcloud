{
  "info": {
    "name": "SoundCloud Update Track",
    "_postman_id": "5e205580-fac2-4461-8837-bcd44c874b11",
    "description": "Updates a given track",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Audio",
      "item": [
        {
          "id": "96906ce9-c40e-45a2-851e-565dc5fca0c8",
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
              "id": "7962fd17-59a1-44aa-bc84-f11fda744347"
            }
          ]
        },
        {
          "id": "ba4f8619-53bd-4c2c-ae74-403ef98a34de",
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
              "id": "ddfbb7ac-693b-4057-89dd-a035a64c0344"
            }
          ]
        },
        {
          "id": "75593e8d-b8df-4739-a419-0392015ecbc7",
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
              "id": "4e967b7f-6713-43b7-afbe-2142a9ffc789"
            }
          ]
        },
        {
          "id": "d7074efb-232a-4935-953a-328665c6bfa4",
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
              "id": "461e9f77-3f84-421f-b791-fc36cb276ec7"
            }
          ]
        }
      ]
    }
  ]
}