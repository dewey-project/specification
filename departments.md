# Departments

## Fields 

|Field Name           |Field Type        |Required     |
|---------------------|------------------|-------------|
|id                   |Integer           |true         |
|name                 |String            |true         |
|description          |String            |false        |
 
## Routes

The following routes should be implemented.

`GET /api/departments`

Returns a list of departments that belong to a school.

Response

```
 {
  data: [
   {
    id: 1, 
    name: 'Mathematics',
    description: 'The Mathematics department'
   },
   {
    id: 2,
    name: 'English',
    description: 'The English department'
   }
  ]
 }
```

`GET /api/departments/:id`

Returns specific data about a department

Response
 
```
 {
  data: [
   {
    id: 1, 
    name: 'Mathematics',
    description: 'The Mathematics department'
   }
  ]
 }
```
