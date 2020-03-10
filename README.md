# Introduction
The task is to write a simple todo list application that allows
the user to add a task by typing into the input field and clicking on the Add button.

# How to Install
```
$ rails new todo-list-app
```
Just use this command in terminal:
```
rails server
```
And look at the rails opening screen.
![Screen Shot 2020-03-10 at 12 53 28 AM](https://user-images.githubusercontent.com/50501566/76280889-c25a3000-6269-11ea-9e19-bf32cbc9320d.png)

We’ve added slim-rails gem to our gem, now we run the bundle install
```
$ bundle install
```
We can create our first model.
```
rails generate model Todo item:string
```
