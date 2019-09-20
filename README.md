# gateway

## Frontend
http://trevorjdobson-taskmaster-frontend.s3-website-us-east-1.amazonaws.com/

## Routes
* GET
  * https://hjnbrvdt2e.execute-api.us-east-1.amazonaws.com/dev/tasks/
  * https://hjnbrvdt2e.execute-api.us-east-1.amazonaws.com/dev/tasks/{user}

* POST
  * https://hjnbrvdt2e.execute-api.us-east-1.amazonaws.com/dev/tasks/
   * {"title":"new","description":"new","assignee":"uopu"}
    
* PUT
 * https://hjnbrvdt2e.execute-api.us-east-1.amazonaws.com/dev/tasks/{user}/assign/{id}
   * assigns the task to a user

