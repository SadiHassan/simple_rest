### Simple REST API ###
Simple REST API project in Python and Flask

### Basic dependecies ###
`python3`

### Additional Libraries required ###
This project needs `flask` to be installed. 
To install it, in command line: 
`pip install flask`

### How to run ###
Go into the `api` folder using command line.
Then, run command: `python api.py`

You will see a base url like: `http://127.0.0.1:5000/api/v1/resources/user/` in the command line. 
Use this URL in the browser to start with.

### list users ###
In the browser, type end-point as below:
`http://127.0.0.1:5000/api/v1/resources/user/all`
This will return a json string containing all users.

### add user ###
In the browser, type end-point as below:
`http://127.0.0.1:5000/api/v1/resources/user/add?birthdate=20201111&email=SS@gmail.com&firstname=John&lastname=Smith`
Change firstname, lastname, email etc. as you wish.

Note: Use the **exact sequence** shown in the example. Otherwise, it might not work.

### remove user ###
In the browser, type end-point as below:
`http://127.0.0.1:5000/api/v1/resources/user/remove?id=1`
here, `id` is the `user id` you want to remove.

### get user by id ###
In the browser, type end-point as below:
`http://127.0.0.1:5000/api/v1/resources/user?id=2`
here, `id` is the `user id` you want to view.

### grant permission for a user ###
In the browser, type end-point as below:
`http://127.0.0.1:5000/api/v1/resources/user/grant?id=2`
here, `id` is the `user id` you want to grant permission.

### revoke permission for a user ###
In the browser, type end-point as below:
`http://127.0.0.1:5000/api/v1/resources/user/revoke?id=2`
here, `id` is the `user id` you want to revoke permission.

### search users by last name ###
In the browser, type end-point as below:
`http://127.0.0.1:5000/api/v1/resources/user/search?lastname=LL`

