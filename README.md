# Frying Plan

Backend file, view backend [here](https://github.com/rebeccahickson/frying-plan-frontend)

Frying Plan React/Redux application, using Rails as an API, that allows users to create meal plans by adding and removing recipes.

## Installation

- Ensure that you have [Ruby](https://www.ruby-lang.org/en/downloads/) installed properly
- Clone this repository and its matching [backend](https://github.com/rebeccahickson/frying-plan-frontend) into the same folder
- Prepare the backend by navigating into the backend folder and completing the following steps:

  - Make sure that you have all necessary gems by running:

    ```
    bundle install
    ```

  - Run the migrations

    ```
    rails db:migrate
    ```

  - Seed the database

    ```
    rails db:seed
    ```
    
- Prepare the frontend by navigating into the frontend folder and completing the following step:
  - Install the necessary packages

    ```
    npm install
    ```

## Usage

### Starting the program

To start the server, enter this command in your backend folder:

```
rails s
```

To open the application, enter this command in your frontend folder:

```
npm start
```

You will be notified that there is already already something running on the port, which is expected. To continue, enter:

```
y
```

### How to use the program

- The application opens on the home page. From here you can:
  - View your current meal plan by clicking "Meal Plan"
    - This page will give you the option to add or remove meals from your meal plan
      - Click the green calendar icon by the recipe you would like to add and fill out the form to add it to a particular day
      - Click the red minus icon to remove a meal from a particular day
  - View all recipes in the database by clicked "All Recipes"
  - Create a new recipe by clicking "New Recipe"
    - Fill out all the fields to create a new recipe - if you need to add multiple ingredients, you may open more input fields by clicking the green plus icon

## License

The program is available as open source under the terms of the [MIT License](https://opensource.org/licenses/MIT)

## Collaborating

Pull Requests are welcome on [GitHub](https://github.com/rebeccahickson/frying-plan-backend). This project is intended to be a safe, welcoming space for collaboration.

## Project Walkthrough

<a href="https://youtu.be/qSS3lEykFlE
" target="_blank"><img src="http://img.youtube.com/vi/qSS3lEykFlE/0.jpg" 
alt="Screenshot of project walkthrough" width="240" height="180" border="10" /></a>

## Further Reading

[Handling Nested Attributes with a Has Many Through Association with Rails API](https://levelup.gitconnected.com/handling-nested-attributes-with-a-has-many-through-association-with-rails-api-f91729547ea5)

A guide to handling nested attributes with a has_many :through association with Rails and React/Redux
