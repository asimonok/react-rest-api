# CRUD operations:
- Create application that will use data from the back-end
- Styles / CCS are not required in this task.
- Use only HTTP requests
- Use React
# Requiremnts:
- Listing page that will display all emements. "Remove" button next to the each element. Upon click, element should be deleted
- Page to create a new element
- Page to display value for one particular element
- Page to update "value" property of the element

# Format of the element object:
```
{
  value: <string_value>,
}
```
# API:
GET `<url>/test.json` - get all elements. Response format:
```
{
...
    <id>: {
        "value": "test"
    }
...
}
```
GET `<url>/test/<id>.json` - get element by id (`<id>` is a value from the GET `<url>/test.json` response)

POST `<url>/test.json` - create element. Request format:
```  
{
  value: <string_value>,
}
```
PUT `<url>/test/<id>.json` - update element. Request format:
```
{
  value: <string_value>,
}
```
DELETE `<url>/test/<id>.json` - delete element (`<id>` is a value from the GET `<url>/test.json` response)
