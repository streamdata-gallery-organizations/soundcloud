{
  "info": {
    "name": "Sound Cloud Delete Me Favorites Track . Format",
    "_postman_id": "0e5b029e-2e98-43f4-b1c5-13e869369c6c",
    "description": "Deletes the given track from the logged-in user's list of favorites.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Users",
      "item": [
        {
          "id": "f3b2b962-6689-4e2f-b902-116139bcc56c",
          "name": "getUsersUserFavorites.json",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.soundcloud.com",
              "path": [
                "users/:user_id/favorites.json"
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
            "description": "Returns a collection of tracks favorited by the user with user id"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "e5db3a8a-92e9-4667-8c11-1225a4ff134b"
            }
          ]
        },
        {
          "id": "7b1da316-ae93-4dac-9af5-9584601e6774",
          "name": "putUsersUserFavoritesTrack.json",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.soundcloud.com",
              "path": [
                "users/:user_id/favorites/:track_id.json"
              ],
              "variable": [
                {
                  "id": "user_id",
                  "value": "user_id",
                  "type": "string"
                },
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
            "description": "Adds the given track to the given user's list of favorites."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "1e33cb10-2912-402d-9b6c-c5c12fe6f3b5"
            }
          ]
        },
        {
          "id": "07b0942c-ae1b-4847-a879-7ecbcfb9f8a1",
          "name": "deleteUsersUserFavoritesTrack.json",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.soundcloud.com",
              "path": [
                "users/:user_id/favorites/:track_id.json"
              ],
              "variable": [
                {
                  "id": "user_id",
                  "value": "user_id",
                  "type": "string"
                },
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
            "description": "Deletes the given track from the given user's list of favorites."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "15859665-245f-47f0-9aa9-03571be60627"
            }
          ]
        },
        {
          "id": "c3368c1a-9ea2-428b-914a-eba13287b064",
          "name": "getUsersUserFavorites.Format",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.soundcloud.com",
              "path": [
                "users/:user_id/favorites.json"
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
            "description": "Returns a collection of tracks favorited by the user with user id"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "b22e4c05-3702-43be-889d-d888b6d6a8f0"
            }
          ]
        },
        {
          "id": "43254462-9d6d-48fe-8b01-9fd34bb49ca1",
          "name": "putUsersUserFavoritesTrack.Format",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.soundcloud.com",
              "path": [
                "users/:user_id/favorites/:track_id.json"
              ],
              "variable": [
                {
                  "id": "track_id",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "user_id",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "PUT",
            "body": {
              "mode": "raw"
            },
            "description": "Adds the given track to the given user's list of favorites."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "88ed335a-176d-4093-ae66-c2cb40c74f0b"
            }
          ]
        },
        {
          "id": "773816aa-090e-4f51-873f-1b49489aa608",
          "name": "deleteUsersUserFavoritesTrack.Format",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.soundcloud.com",
              "path": [
                "users/:user_id/favorites/:track_id.json"
              ],
              "variable": [
                {
                  "id": "track_id",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "user_id",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "DELETE",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes the given track from the given user's list of favorites."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "b74e86e2-6921-47be-8d1e-47bed3c5c30a"
            }
          ]
        }
      ]
    },
    {
      "name": "Me",
      "item": [
        {
          "id": "43ab2049-9122-402a-9a08-3ed7d4e27e53",
          "name": "getMeFavorites.json",
          "request": {
            "url": "http://api.soundcloud.com/me/favorites.json",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns a collection of tracks favorited by the logged-in user"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "b57a77e9-f68a-4d56-b8fd-9668e0206de6"
            }
          ]
        },
        {
          "id": "f77fedbb-077d-4730-9b96-b195a4d0c73e",
          "name": "putMeFavoritesTrack.json",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.soundcloud.com",
              "path": [
                "me/favorites/:track_id.json"
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
            "description": "Adds the given track to the logged-in user's list of favorites."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "fbda0a9c-b7cc-496d-a218-472de3ba1a2e"
            }
          ]
        },
        {
          "id": "417f9784-f6c8-49a8-9e7f-c5e5ea179361",
          "name": "deleteMeFavoritesTrack.json",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.soundcloud.com",
              "path": [
                "me/favorites/:track_id.json"
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
            "description": "Deletes the given track from the logged-in user's list of favorites."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "5dd7b054-60d0-426f-91eb-78113d1947cd"
            }
          ]
        },
        {
          "id": "6429c984-ff74-4cef-b9eb-a2a410fc5e6b",
          "name": "getMeFavorites.Format",
          "request": {
            "url": "http://api.soundcloud.com/me/favorites.json",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns a collection of tracks favorited by the logged-in user"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "3044cacb-f05a-4e65-b790-37028f396dc6"
            }
          ]
        },
        {
          "id": "c1a1c348-5584-4b83-b933-8af0d6c7afda",
          "name": "putMeFavoritesTrack.Format",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.soundcloud.com",
              "path": [
                "me/favorites/:track_id.json"
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
            "description": "Adds the given track to the logged-in user's list of favorites."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "eb3b2b4c-d861-47c6-9715-87965aa9a49f"
            }
          ]
        },
        {
          "id": "c88a2618-c30e-4dae-8e0c-7e5d7589f82e",
          "name": "deleteMeFavoritesTrack.Format",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.soundcloud.com",
              "path": [
                "me/favorites/:track_id.json"
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
            "description": "Deletes the given track from the logged-in user's list of favorites."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "2c6b8b02-0375-4320-a4ab-f42e88530d66"
            }
          ]
        }
      ]
    }
  ]
}