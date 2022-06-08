# Spring Boot Tutorial

https://youtu.be/9SGDpanrc8U

- 49abb53 init project
- c25dd52 Atudent class
- e01e0ce API layer
- f345406 Business layer (service)
- b8b1fa4 Dependency injection
- 0a963a7 Properties file
- 84a8667 uncomment JPA dependency
- f16df0b JPA and Entity
- f316a4f JPA Repository
- 7e11337 Saving student
- f9d5770 Transient
- 79099f7 Post Mapping
- 98795b4 Throw error if user email taken
- bbc87c3 Incluce message in error
- c592cd9 Delete API
- 6f54b63 Put API - Transactional

```http
GET /api/v1/student HTTP/1.1
Host: localhost:8080
```

```http
POST /api/v1/student HTTP/1.1
Host: localhost:8080
Content-Type: application/json
Content-Length: 86

{
  "name": "Bilal",
  "email": "bilal.ahmed@gmail.com",
  "dob": "1995-12-17"
}
```

```http
DELETE /api/v1/student/1 HTTP/1.1
Host: localhost:8080
```

```http
PUT /api/v1/student/1?name=Maria&email=maria@gmail.com HTTP/1.1
Host: localhost:8080
```
