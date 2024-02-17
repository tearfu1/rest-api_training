# converter

# REST API

GET /users -- list of user -- 200, 404, 500
GET /users:id -- user by id -- 200, 404, 500
POST /users:id -- create user -- 204, 4xx, Header location: url
PUT /users:id -- fully update user -- 204/200, 404, 400, 500
PATCH /users:id -- partially update user -- 204/200, 404, 400, 500
DELETE /user:id -- delete user by id -- 204, 404, 400