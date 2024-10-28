# Workshop #1: Getting SOLID

---

## Structure

1. In this workshop, you have a simple project to complete. You can start with the prototype of the app that one of your coworkers has created. You are free to use it, rewrite it, or take parts from it.
2. Try to improve the provided solution, keeping in mind material from lectures, signs of good and bad code, etc.
3. Before submission, rewrite this README to directly describe what parts of your solution you like and what parts you don't like, and why.
4. Be prepared for _an important update_ that will arrive 30 minutes before the class ends, introducing some changes in business logic. You can try to prepare for that change.
5. It's acceptable for this workshop to be completed by students working together on one computer.

---

## Task

You have been hired to develop a command-line to-do application for a client who wants to manage tasks efficiently. The application should be simple to use. Initially, the client requires the application to support basic commands to add, remove, list, and complete tasks, as well as some more complex tasks, such as tasks with deadlines.

Tasks should persist between sessions. The team is still considering options for the service to use, so file storage is chosen for the MVP (Minimum Viable Product).

### Sample Usage


1. Add a task: `add <task description>`
Example:`add <Buy milk>`

2. List tasks: `list all`
Example output:
```
1.[x] Order a book
2.[]  Buy milk
```

3. Remove a task: `remove <task number>`
Example:`remove 1`

4. Complete a task `complete <task number>`

5. Tasks with deadlines:
`add deadline <task description> <deadline>`

Listing should include that information:
```
list all
1.[x] Order a book
2.[]  Buy milk
3.[]  Make Assignment #1 on OOD (until 21.09.2024)
```

And in case of missed deadline:
```
list all
1.[x] Order a book
2.[]  Buy milk
3.[overdue]  Make Assignment #1 on OOD (until 21.09.2024)
```


### Grading Policy
You can get up to 4 points for this task.

**Note:** Remember to focus on applying SOLID principles, especially the Single Responsibility Principle (SRP), Open/Closed Principle (OCP), and Dependency Inversion Principle (DIP). Aim for high cohesion and low coupling in your design to make your code maintainable and extensible.

Good luck with your implementation!