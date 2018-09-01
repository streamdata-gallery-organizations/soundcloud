{
  "info": {
    "name": "SoundCloud Update Tracks",
    "_postman_id": "80839b1d-55ef-4d6a-b26e-f64f2a9e5927",
    "description": "Uploads a track",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Audio",
      "item": [
        {
          "id": "97b061f5-0980-46f9-a003-e03fd9e57685",
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
              "id": "36ab6f89-03f4-493c-8d00-d0836059a24f"
            }
          ]
        },
        {
          "id": "2fb1af6a-b576-42d2-b7dc-bbc0085fdb69",
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
              "id": "61a05e7d-5c17-4831-82e7-253b9a0c7dff"
            }
          ]
        }
      ]
    }
  ]
}