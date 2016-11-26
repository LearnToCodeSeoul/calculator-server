# Calculator
> Simple calculator written in Java

## How to run
- Mac O/S, Linux
```
$ ./mvnw spring-boot:run
```
- Windows
```
$ mvnw.cmd spring-boot:run
```

## How to test

### Server API
- Plus
```
$ curl "http://localhost:8080/plus?first=1&second=2"
```
- Minus
```
$ curl "http://localhost:8080/minus?first=2&second=1"
```
