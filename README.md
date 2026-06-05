# DCRM

A simple Django CRM project.

## Run the project locally

From the project root:

1. Create or activate the Pipenv environment:

   ```sh
   pipenv install
   ```

2. Apply database migrations:

   ```sh
   pipenv run python dcrm/manage.py migrate
   ```

3. Start the development server:

   ```sh
   pipenv run python dcrm/manage.py runserver
   ```

4. Open the app in your browser:
   ```text
   http://127.0.0.1:8000/
   ```

## Useful checks

You can verify the project is configured correctly with:

```sh
pipenv run python dcrm/manage.py check
```
