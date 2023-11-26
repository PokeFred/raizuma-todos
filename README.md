# ToDo
## raizuma.de

## admin.raizuma.de
- [ ] auth
    - [ ] register page (/auth/signup)
    - [ ] login page (/auth/login)
    - [ ] logout page (/auth/logout)
- [ ] app
    - [ ] welcome page (/app)
    - [ ] user
        - [ ] list page (/app/user)
        - [ ] show page (/app/user/[id])
        - [ ] edit page (/app/user/[id])
    - [ ] post
        - [ ] list page (/app/post)
        - [ ] show page (/app/post/[id])
        - [ ] edit page (/app/post/[id])
    - [ ] project
        - [ ] list page (/app/project)
        - [ ] show page (/app/project/[id])
        - [ ] edit page (/app/project/[id])

## api.raizuma.de
- [ ] user
    - [ ] [GET] /user (get user information)
    - [ ] [POST] /user (create new user)
    - [ ] [PATCH] /user (edit user settings)
    - [ ] [DELETE] /user (delete a user)
    - [ ] [GET] /user/[id] (get user information by id)
    - [ ] [PATCH] /user/[id] (edit user by id)
    - [ ] [DELETE] /user/[id] (delete user by id)
- [ ] auth
    - [ ] [GET] /auth (get access_token information)
    - [ ] [POST] /auth (create new auth/login)
- [ ] post
    - [ ] [GET] /post (get all posts)
    - [ ] [GET] /post/[id] (get post by id)
    - [ ] [POST] /post/[id] (create post by id)
    - [ ] [PATCH] /post/[id] (edit post by id)
    - [ ] [DELETE] /post/[id] (delete post by id)
- [ ] project
    - [ ] [GET] /project (get all projects)
    - [ ] [GET] /project/[id] (get project by id)
    - [ ] [POST] /project/[id] (create project by id)
    - [ ] [PATCH] /project/[id] (edit project by id)
    - [ ] [DELETE] /project/[id] (delete project by id)
