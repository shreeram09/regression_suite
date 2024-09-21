### Regression Suite

## purpose
- understand the RESTful webserivce API testing with postman collection
- write api tests with postman
- execute regression tests with postman gui, cli
- execute regression tests with newman cli
- prepre reports
- perform same in CI/CD pipelines

## prereuisites
- Postman application
- newman nodejs package
- newman-reports-htmlextra package
- newman-reports-json-extralight (optional)

## commands
- newman commandline regression test
```cmd
newman run path-to-collection.js
```
- newman reports generation
```cmd
newman run path-to-collection.js --reports cli,htmlextra path-to-reports
```
> commands will generate newman folder and store any outputs, reports under the same

