# Departments

## Fields 

|Field Name           |Field Type        |Required     |
|---------------------|------------------|-------------|
|id                   |Integer           |true         |
|name                 |String            |true         |
|description          |String            |false        |
 
## Routes 

### GET `/api/departments`

Returns a list of departments that belong to a school.

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

### GET `/api/departments/:id`

Returns specific data about a department
 
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
