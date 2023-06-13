---
cover: ../../.gitbook/assets/Agregar un título (8).png
coverY: 0
---

# Syntax and Basic Structure

## 🍿 Hello World

To start, let's dive into the most popular program in programming: "**Hello, World.**" This will allow us to explore the syntax and the basic structure of Go code and learn how to run a program.

**"Hello, World"** is a simple program that **displays a greeting message on the screen**. Let me provide you with the code and guide you through the steps to execute it.

Here's the Golang code to print "Hello, World" on the screen:

{% code title="main.go" %}
```go
package main

import "fmt"

func main() {
    fmt.Println("Hello, World")
}
```
{% endcode %}

Now, let's break down the structure of the code.

## 🍿 The "main" package

```go
package main
```

* In Go, every program starts with a **package** declaration (we'll cover packages later). In this case, we've declared the **"main"** package.
* The **"main"** package is special in Golang as it indicates that this is the program's main entry point.

## 🍿 Importing the "fmt" package

```go
import "fmt"
```

* Next, we import the **"fmt"** package, which provides **functions** (we'll talk about functions later) for input and output formatting. We'll use the **"Println"** function from this package to display our message on the screen.

## 🍿 The "main" function

```go
func main() {
    fmt.Println("Hello, World")
}
```

* In Golang, the **"main" function serves as the entry point for the execution of the program**. When you run a Golang program, the runtime system automatically starts by invoking the main function.
* It's the primary function that kicks off the execution and performs the initial setup for your program.
* Inside the **"main"** function, we call the **"Println"** function and pass the message "Hello, World" as an argument.
* The **"Println"** function will print the message on the screen.

## 🍿 Run the program

Now that we've written our code, let's **execute** the program. **Make sure you have Golang installed on your system**. Open your terminal or command prompt and navigate to the directory where you've saved the file containing the code.

To run the program, run the following command:

```bash
go run main.go
```

After running the command, you should see the message "Hello, World" printed on the screen.

```bash
Hello, World
```

Congratulations! You've successfully executed your first program in Go.
