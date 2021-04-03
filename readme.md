# Project Name

- **Author:**
- **Link to Live Site:**

## Project Summary

## Technology Used

## Models

Sample Model:

- name => String
- Schema = new Schema({
  name: {type: String, required: true},
  todos:[{type: Schema.Types.ObjectId, ref: "Todo"}]
  })

## Route Map

| Method | Endpoint           | Resource/View                                |
| ------ | ------------------ | -------------------------------------------- |
| GET    | "/sample"          | List all Samples (sample/index.ejs)          |
| GET    | "/sample/:id       | Display single Sample (sample/show.ejs)      |
| GET    | "/sample/new       | Render form for New Sample (sample/new.ejs)  |
| POST   | "/sample"          | Uses Form Submission to Create new Sample    |
| GET    | "/sample/:id/edit" | Render form to edit Sample (sample/edit.ejs) |
| PUT    | "/sample/:id"      | Uses Form Submission to edit Sample          |
| DELETE | "/sample/:id"      | Delete a particular Sample                   |

## Challenges

## Existing Bugs
