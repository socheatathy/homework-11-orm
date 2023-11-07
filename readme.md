## Questions

1. add new employee record to employee table with id = 168, firstname = 'John', lastname = 'Doe', initials = 'JD', job = 'Programmer', hire_date = today's date.
2. query the new created employee (id=168) from employee table, with information of employee id, firstname, lastname, initials, job description (join with job), charge per hour (join with job) and hire_date.
3. update the new created employee (id=168) job, from 'Programmer' to 'Database Designer'.
4. query all project that has "Programmer" assigned to, with information of project id, project name and program manager (join with employee).
5. delete the new created employee (id=168) from employee table.

## Submit

fork this repo, add your answer to the questions above in the `answer.md` file, and submit your forked repo url to the Canvas assignment.

## Setup

fork this repo to your repository

- [ ] fork this repo to your repository
- [ ] clone the forked repo to your local machine
- [ ] install dependencies `pip install -r requirements.txt`
- [ ] restore the database from `ch08_.ConstructCo.dump` file
- [ ] create `.env` file with content from `example.env` and update the values to your local environment
- [ ] create `answer.md` file with your answers to the questions above
- [ ] commit and push your changes to your forked repo

## Reference

### Object Relational Mapping (ORM)

1. [ORM Query Guide](https://docs.sqlalchemy.org/en/20/orm/queryguide/select.html#selecting-orm-entities)
2. [ORM Join Guide](https://docs.sqlalchemy.org/en/20/orm/queryguide/select.html#joins)
3. [ORM CRUD Guide](https://docs.sqlalchemy.org/en/20/orm/queryguide/dml.html#orm-update-and-delete-with-custom-where-criteria)
