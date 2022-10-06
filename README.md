# 99_basic_1week_backend
![image](https://user-images.githubusercontent.com/83463300/194335831-41dceec8-0102-40bb-9c1c-052f145d8d32.png)

GET
/api/post
-
{
"success": true,
"data": [
{
"createdAt": "2022-07-25T12:43:01.226062”,
"modifiedAt": "2022-07-25T12:43:01.226062”,
"id": 1,
"title": "title2",
"content": "content2",
"author": "author2"
},
{
"createdAt": "2022-07-25T12:43:01.226062”,
"modifiedAt": "2022-07-25T12:43:01.226062”,
"id": 2,
"title": "title",
"content": "content",
"author": "author"
}
],
"error”: null
}
GET
/api/post/{id}
-
{
"success": true,
"data": {
"createdAt": "2022-07-25T12:43:01.226062”,
"modifiedAt": "2022-07-25T12:43:01.226062”,
"id": 1,
"title": "title2",
"content": "content2",
"author": "author2"
},
"error": null
}
POST
/api/post
{
"title" : "title",
"content" : "content",
"author" : "author",
"password" : "password"
}
{
"success": true,
"data": {
"createdAt": "2022-07-25T12:43:01.226062”,
"modifiedAt": "2022-07-25T12:43:01.226062”,
"id": 1,
"title": "title",
"content": "content",
"author": "author"
},
"error": null
}
POST
/api/post/{id}
{
"password" :"password"
}
{
"success": true,
"data": true,
"error": null
}
PUT
/api/post/{id}
{
"title" : "title2",
"content" : "content2",
"author" : "author2",
"password" : "password2"
}
{
"success": true,
"data": {
"createdAt": "2022-07-25T12:43:01.226062”,
"modifiedAt": "2022-07-25T12:43:01.226062”,
"id": 1,
"title": "title2",
"content": "content2",
"author": "author2"
},
"error": null
}
DELETE
/api/post/{id}
{
"success": true,
"data": true,
"error": null
}
