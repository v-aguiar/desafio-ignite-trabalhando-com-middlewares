## Desafio 2 - Trabalhando com Middlewares

### Requests

- [x] It must be possible to create a new user with `name` and `username`
- [x] It must be possible to list all tasks
- [x] It must be possible to create a new task
- [x] It must be possible to change `title` and `deadline` from an existing task
- [x] It must be possible to check a task as done
- [x] It must be possible to delete a task
- [x] It must be possible to CRUD tasks

### Bussiness Rules

- [x] The `username` must be passed through the header
- [x] Should be able to find user by username in header and pass it to request.user
- [x] Should not be able to find a non existing user by username in header
- [x] Should be able to let user create a new todo when is in free plan and have less than ten todos
- [x] Should not be able to let user create a new todo when is not Pro and already have ten todos
- [] Should be able to let user create infinite new todos when is in Pro plan
- [] Should be able to put user and todo in request when both exits
- [] Should not be able to put user and todo in request when user does not exists
- [] Should not be able to put user and todo in request when todo id is not uuid
- [] Should not be able to put user and todo in request when todo does not exists
- [] Should be able to find user by id route param and pass it to request.user
- [] Should not be able to pass user to request.user when it does not exists
