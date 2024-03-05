get task list(get request)
curl http://127.0.0.1:5000/tasks

create a new task (post request)
curl -X POST -H "Content-Type: application/json" -d '{"title":"Learn Flask","description":"Study REST API creation."}' http://127.0.0.1:5000/tasks

delete a task (delete request)
curl -X DELETE http://127.0.0.1:5000/tasks/1
