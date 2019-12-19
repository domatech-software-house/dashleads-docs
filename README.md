# Dashboard Leads for developers

Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book. It has survived not only five centuries, but also the leap into electronic typesetting, remaining essentially unchanged.

## Request

### Route

> POST

~~~
https://ws.dashboardleads.com.br/api/v1.0/lead
~~~

### Header

~~~
Content-Type: application/json
~~~

### Body

~~~JSON
{
    "token": "YOUR_TOKEN",
    "name": "Test",
    "email": "test@test.com",
    "phone": "(00) 00000-0000",
    "date": "1998-05-04",
    "target": "Test",
    "status": "Test",
    "comments": "Long Text",
    "extraFieldOne": "Test",
    "extraFieldTwo": "Test",
    "extraFieldThree": "Test",
    "extraFieldFour": "Test",
    "extraFieldFive": "Test",
    "extraFieldSix": "Test"
}
~~~

## Response

### Status

~~~PHP
200
~~~

### Body

~~~JSON
{
    "_id": "ID_LEAD",
    "name": "Test",
    "email": "test@test.com",
    "phone": "(00) 00000-0000",
    "date": "1998-05-04",
    "target": "Test",
    "status": "Test",
    "comments": "Long Text",
    "extraFieldOne": "Test",
    "extraFieldTwo": "Test",
    "extraFieldThree": "Test",
    "extraFieldFour": "Test",
    "extraFieldFive": "Test",
    "extraFieldSix": "Test",
    "createdAt": "1998-05-04T00:00:00.000Z",
    "updatedAt": "1998-05-04T00:00:00.000Z"
}
~~~

## Developers

- [Gustavo Aldar](https://github.com/gustavoaldar);



