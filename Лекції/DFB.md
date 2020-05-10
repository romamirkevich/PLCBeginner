| [<- до лекцій](README.md)        | [на основну сторінку курсу](../README.md) |
| -------------------------------- | ----------------------------------------- |
| [<- PID-регулювання](4_1_PID.md) |                                           |

# Розробка власних функціональних блоків

лекція розробляється

## Необхідність у створенні власних функцій та функціональних блоків

 

## Розробка власних функцій 

### Функції користувача в М221 (User Defined Fucntion)

 A [user-defined function](javascript:void(0)) allows you to  create new functions with input parameters, local variables and a return value.  User-defined functions are stored as part of the EcoStruxure Machine Expert -  Basic project. 

You can call user-defined functions in: 

The Master task  Periodic tasks  Events  Free POUs 

The following illustration shows the actions that are available  in the Properties view of the  user-defined function: 

![img](G-SE-0058719.1.gif)

`1 `Delete the Return  value, an input Parameter, or a Local variable `2 `Add a Return value,  an input Parameter, or a Local  variable `3 `Optionally, write a description of the purpose  of the user-defined function. This description appears in a tooltip when you use  the user-defined function in an Operation Block or  Comparison Block. `4 `Detach the properties view

You can call other user-defined functions in the rungs that  implement a user-defined function. 

NOTE: User-defined functions cannot be  recursive: a user-defined function cannot call itself directly or indirectly. 

A user-defined function cannot call a subroutine, but a subroutine  can call a user-defined function. 

Variables and Global Variables 

The three following variables can only be used in the rungs  that implement the user-defined function: 

%RET0  %PARAMn  %VARn 

Global variables are the other variables that you can use in an  EcoStruxure Machine Expert - Basic program, including the rungs of a  user-defined function. 

Defining the Interface of a  User-Defined Function 

To use a user-defined function, you have to define the objects and  their data types. 

| Object                                                       | Data Type                                                    | Description                                                  |
| ------------------------------------------------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ |
| Return  value  %RET0                                         | Word  Double  Float                                          | Value returned by the user-defined function.  Can only be used in a rung of a user-defined function. |
| Parameters  %PARAMn(1)                                       | Parameter of a user-defined function.  Can only be used in a rung of a user-defined function.  You cannot change the default parameter address.  You cannot add parameters to animation tables.  In online mode, the current values of parameters are not  displayed on IL/Ladder editor. |                                                              |
| Local  variables  %VARn(1)                                   | Variables used to store data values within the  user-defined function.  Can only be used in a rung of a user-defined function.  You cannot change the default local variable address.  You cannot add local variables to animation tables.  In online mode, the current values of local variables are not  displayed on IL/Ladder editor. |                                                              |
| (1) n is an integer incremented each time a parameter or a  local variable is created. |                                                              |                                                              |

These objects are optional. 

Using User-Defined Functions 

Once defined, user-defined functions can be used anywhere in the  program using an Operation  Block or Comparison Block in the same  way as any other function. 

User-Defined Functions in  Offline and Online Modes 

You can manage user-defined functions in offline mode. 

In online mode, you can: 

add a rung to an existing user-defined function  modify a rung calling a user-defined function 

User-defined functions are stored as part of the project. If you  want to use a user-defined function in another project, you have to export it,  then import it to the other project. 

User-defined functions are stored as part of the project. If you want to use a  user-defined function in another project, you have to export it, then import it  to the other project. 



 

### Приклад створення користувацької функції

## Розробка власних функціональних блоків

### Функціональні блоки в М221 (User Defined Fucntion Blocks)  

### Приклад створення користувацького ФБ



| [<- до лекцій](README.md)        | [на основну сторінку курсу](../README.md) |
| -------------------------------- | ----------------------------------------- |
| [<- PID-регулювання](4_1_PID.md) |                                           |