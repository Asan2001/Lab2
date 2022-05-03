# Laboratory work 2

## Structure

- [server](./server)

  Contains the app's api

- [persistence](./persistence)

  Contains model and all storage classes
  All storage objects conform to the same interface

- [templates](./templates)

  Html pages for the routes

- [main.py](./main.py)

  Entry point of the application

- [requirements.txt](./requirements.txt)

  Contains apps dependencies

## Description

Simple CRUD Api with browser interface

Operations supported:
- Get user/users

## How To Install And Run

1) Clone the repo

    ```sh
    git clone https://github.com/Asan2001/Lab2
    ```

2) Create virtual env
    ```sh
    python3 -m venv env
    ```

3) Activate the environment

    ```sh
    source env/bin/activate
    ```

4) Download the dependencies:

   ```sh
   pip3 install -r requirements.txt
   ```

5) Run the application

   ```sh
   python main.py
   ```
