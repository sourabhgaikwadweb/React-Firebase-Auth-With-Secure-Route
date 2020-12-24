# What you can find in this project


### `Authentication`

In this project we are using firebase for authentication. we are using email and password method for authentication.

### `Private route`

Once user login then we have created a private route so that only authenticated user can access those routes. 

### `Preventing access of Public routes`

Once user authenticated, user can't go to the public routes like login or signup page unless user logged out.

### `Added role based authentication`

Added role to the Authentication token so that It is easy to differentiate between Admin and User.

### `Steps to create firebase function and deploy it`
- Use below command to install firebase tools
   * npm install firebase-tools -g

- Authenticate firebase User
   * firebase login

- Initialize firebase fuctions
   * firebase init functions 

-  Deploy firebase functions
   * firebase deploy --only functions
