{
  "info": {
    "name": "Sound Cloud Get Tracks",
    "_postman_id": "36a6e1e5-f9ed-48d6-a348-3a0dcc3254b6",
    "description": "Returns a collection of tracks",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Tracks",
      "item": [
        {
          "id": "63b04a2e-fd67-492b-906a-93bc26e9aebe",
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
              "id": "ad565baf-7a3e-4f3f-a5f8-4e4fce3c402d"
            }
          ]
        }
      ]
    }
  ]
}