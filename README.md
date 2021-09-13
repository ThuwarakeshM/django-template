# Django Best Practices Template by Thuwarakesh

This project creates a django project

- in a **Poetry** environment;
- with **postgres** backend, and;
- ability to create **graphql** apis.

In addition this project also has pre-commit hooks configured for

- **black** code formating;
- **isort** import sorting, and;
- **autflake** code cleaning.

---

## Setup

To set up the project you should have Poetry installed. You can find the instructions [here](https://python-poetry.org/docs/).

1. Clone the project
2. Install dependencies with

```
poetry install
```

3. Change the origin to point your own repository (optional)

```
git remote set-url <Your repository url>
```

4. Create a .env file in the project root directory. You can use the below template.

```
SECRET_KEY=
DB_NAME=
DB_USERNAME=
DB_PASSWORD=
```

To generate a secret key you can use ,

```
python -c "import secrets; print(secrets.token_urlsafe())"
```

---

## About me.

I am a data scientist and a writter on Medium. I mostly develop web application with machine learning components.

You can follow my work on

- [Medium](https://thuwarakesh.medium.com)
- [LinkedIn](https://linkedin.com/in/thuwarakesh)
- [Twitter](https://twitter.com/thuwarakesh)
