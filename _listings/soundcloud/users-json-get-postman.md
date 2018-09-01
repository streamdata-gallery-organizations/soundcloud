{
  "info": {
    "name": "Sound Cloud Get Users",
    "_postman_id": "01aaa7b9-4224-4e9f-bb4b-58adfcc024d1",
    "description": "Returns a collection of users",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Users",
      "item": [
        {
          "id": "7b408bcd-1c52-4e2d-b62b-2fc74f7ce67b",
          "name": "getUsers.json",
          "request": {
            "url": "http://api.soundcloud.com/users.json?consumer_key=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns a collection of users"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "67edc71e-470a-4bdf-9ae4-9fe6feca779b"
            }
          ]
        }
      ]
    }
  ]
}