Welcome to TakeMeTour's Job Quest (Winter 2017 Edition)
===

Thank you for your interest in working at TakeMeTour. First, we would like to take a simple test on your coding skill.

Please fork this repo and work on the test. After finishing the test, please send your repo to WantToWork@takemetour.com (Subject: `JavaScript Engineer Application`).

The quest has 3 parts: front-end, back-end, data parts. **You are free to work on one or more of those parts**.

Back-end
---
- Write a To-do API in language of your choice having following endpoints
  - `GET /` Get all todos
  - `POST /` Create new todo
  - `DELETE /:id` Delete specific todo item
  - `POST /:id/toggle` Toggle the state of specific todo item (Todo / Done)
- The state of all todos have to be in stored in database of your choice
- Bonus: Try writing a GraphQL API on top of REST API

Front-end
---
- Write a To-do web client (single-page application)
- Any modern web framework/lib is okay (ReactJS, Angular, VueJS, ...)
- If no API is available, you can use IndexDB or LocalStorage instead
- Bonus: Try adding some animation to the UI

Data
---
- Given [Consumer complaint dataset file](https://data.consumerfinance.gov/api/views/s6ew-h6mp/rows.csv?accessType=DOWNLOAD), Write a python code to load the file and plot the following data
- X-axis representing year that the compaints have been received (`Date received` column)
- Y-axis representing total complaints count grouped by `Product` column