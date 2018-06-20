{
  "info": {
    "name": "Sound Cloud Post Tracks",
    "_postman_id": "35c59f05-48e6-4e53-a2e6-6cb9ad571826",
    "description": "Uploads a track",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Tracks",
      "item": [
        {
          "id": "4cef9429-339c-46fc-9968-14763243496e",
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
              "id": "c5c362ca-e8b2-49e7-844e-a432773970b1"
            }
          ]
        },
        {
          "id": "87962718-94bf-44cd-9041-7b759c7e00cb",
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
              "id": "7dc2bfcf-3b86-41a9-ba5d-5602def2d8ab"
            }
          ]
        }
      ]
    }
  ]
}