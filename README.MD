# Pic-Storage
pic-storage is the project for uploads and store images to the server.

This project using flask (A python web microframework).

This project is under the MIT License.

## To run the application

- Edit the Database Configuration file (settings.py)

```python
    DATABASE_NAME = 'YOUR_DATABASE_NAME'
    DATABASE_USER = 'YOUR_USER'
    DATABASE_HOST = 'YOUR_DATABASE_HOST'
    DATABASE_PASSWORD = 'YOUR_PASSWORD'
```
- Create the database table (for the first time) and install packages
     
     run the code below - make sure permission is set ( chmod +x setup.sh )
```
  $ ./setup.sh
```


- Run the app

```
  $ python app.py
```
