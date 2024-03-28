# Rails API 3/28/2024

### Notes

- Add RSpec
- Student model, name and cohort columns
- `rails g resource Student name:string cohort:string`
- resource generate command - model, controller, routes
- rails routes
- endpoint - how you can get data from the database when making a request over the internet
- if Postman returns HTML, click over to the preview tab

### RESTful Routes

- index - read, all the data
- show - read, one datum
- new - nothing
- create - create new data
- edit - nothing
- update - updates existing data
- destroy - deletes data

### RESTful API

- index - read, all the data
- show - read, one datum
- create - create new data
- update - updates existing data
- destroy - deletes data

### Index

- controller - active record query for all the students, rendered json
- checked in Postman

### Show

- controller - active record query for one students by params, rendered json
- checked in Postman

### Create

- controller - active record query to create a student, rendered json, added strong params method
- checked in Postman, create in Postman: body tab, raw radio button, JSON in the dropdown

### Update

- controller - active record query to update a student by params, rendered json, added strong params method
- checked in Postman, create in Postman: body tab, raw radio button, JSON in the dropdown

### Destroy

- controller
