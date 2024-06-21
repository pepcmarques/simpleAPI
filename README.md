This is a small CRM API connected to a MongoDB database.

Use methods GET, POST, PUT, DELETE

```
http://<server ip>/contact
http://<server ip>/contact/<contact id>
```

Example of structure
```
[
  {
    "_id": "64642c0780c8ee820a364d2b",
    "firstName": "John",
    "lastName": "Doe",
    "phone": null,
    "email": "",
    "country": "USA",
    "notes": "",
    "created_date": "2023-05-17T01:21:11.186Z",
    "__v": 0
  },
  {
    "_id": "6467aade8cde7308422fc5fb",
    "firstName": "J",
    "lastName": "J",
    "phone": 123,
    "email": "",
    "country": "Jamaica",
    "notes": "",
    "created_date": "2023-05-19T16:59:10.868Z",
    "__v": 0
  }
]
```
