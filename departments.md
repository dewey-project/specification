# Departments

## Fields 

|Field Name           |Field Type        |Required     |
|---------------------|------------------|-------------|
|id                   |Integer           |true         |
|name                 |String            |true         |
|description          |String            |false        |
 
## Routes 

### GET `/api/departments` - returns a list of departments

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

### GET `/api/departments/:id` - returns the data for a specific department
 
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
