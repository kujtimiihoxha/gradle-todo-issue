# Test case for todo-issue
This project is created to demonstrate the use of [todo-issue](https://github.com/kujtimiihoxha/todo-issue) in a gradle project.
## Try it
You can clone this repository and test todo-issue.

- Clone repository 
- Create todo.json in the working directory (where build.gradle is).
```json
{
  "git-server":"Github",
  "repository-username":"kujtimiihoxha",
  "issuer-username":"{your-user}",
  "token":"{your-token}",
  "repository":"gradle-todo-issue"
  "file-link":true
}
```
- Run ``` gradle build ```
- Add an issue like described [here](https://github.com/kujtimiihoxha/todo-issue#syntax)
- Run ```gradle task:find```

Go to [issues page](https://github.com/kujtimiihoxha/gradle-todo-issue/issues) and see your issues appear.

Close any issue you created and run ```gradle task:find``` again and you will se the todo-s will disappear from the source file.