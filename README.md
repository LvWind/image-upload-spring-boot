# image-upload-spring-boot
A simple Spring Boot application for image uploading

## Init
```
./mvnw clean install
```

## Use
Use Multipart/form-data POST

DataPart name: 'file'

## Return value
```json
{
  "status":200,
  "message":"success",
  "results":[
    {"url":"http://0.0.0.0/uploads/1509496746189.jpg"},
    {"url":"http://0.0.0.0/uploads/1509496734770.jpg"}]
}
```
