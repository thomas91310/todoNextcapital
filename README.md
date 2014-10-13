todoNextcapital
===============

Todo app which calls a ruby API to get, post, put, delete accounts and todos.

The application runs here on Heroku : http://todoappnextcapital.herokuapp.com

I used twitter bootstrap & AngularJS & the jQuery client that NextCapital provided to develop the app.
Added a remove property but it doesn't remove any todo since the API didn't provide a route for that.
The ordering of todos is just done on the client side since (drag the todo to change the order)

Requirements:
- Sign up done -> done
- Login done -> done
- Create todos -> done
- Mark todos as complete -> done
- Reorder todos with drag and drop -> done

Added: 
- Edit todo by double-clicking.
- See all or just completed or just active todos.
- Remove a todo from the list (just on the client side. Each time todos are reloaded, the todos come back because they are still on the server side).
 
