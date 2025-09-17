# toy-robot-simulator
Take-home exercise in service of Rohirrim engineering role.
Created with Node v22.17.0

## Cloning the Repo
This project implements [submodules](https://git-scm.com/book/en/v2/Git-Tools-Submodules) to acheive separate git histories in the frontend and api layers.

Use the `--recurse-submodules` flag when cloning to ensure all files are copied:

```shell
git clone --recurse-submodules https://github.com/allanmaclean/toy-robot-simulator
```

## Running with Docker

> [!NOTE]
> Both the frontend and API are being running on dev servers with hot reload

1. Clone this repo
2. Ensure you have Docker installed on your system
3. Run `docker compose up --build`
4. Frontend will be accessible via [http://localhost:4200/](http://localhost:4200/)
5. Backend will be running on [http://localhost:3000/](http://localhost:3000/)