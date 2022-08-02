# Reading Notes class-08

Using best practices will ease the changes that need to be made in the future.

## API Design Best Practices

1. <ins>Re</ins>presentational <ins>S</ins>tate <ins>T</ins>ransfer
2. REST APIs are designed around resources - https://docs.microsoft.com/en-us/azure/architecture/best-practices/api-design
3. A resource has an identifier, a unique  URI
4. GET, POST, PUT, PATCH, DELETE
5. A unique piece of data from the resource
6. An employee id number would be a good.
7. A chatty API requires more input. For each small component a request needs to be made. Not the preferred method
8. Successful GET returns a 200 ok message.
9. Unsuccessful GET can return 404, or 204.
10. Successful POST returns 201(created).
11. Successful DELETE returns 204(No content)