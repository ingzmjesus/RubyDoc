### Operators

| Operator | Description                                                  |
| -------- | :----------------------------------------------------------- |
| @        | Instance variable.                                           |
| @@       | Class variable.                                              |
| $        | Global variable.                                             |
| *        | Splat operator (receive one or more arguments).              |
| **       | Same as splat operator but only for hashes.                  |
| !!       | It converts the value to a boolean.                          |
| <=>      | Spaceship operator (useful to sort arrays).                  |
| \|\|=    | Conditional assignment.                                      |
| ::       | Scope resolution operator                                    |
| %r()     | Is another way to write a regular expression.                |
| %q()     | Is another way to write a single-quoted string (and can be multi-line, which is useful) |
| %Q()     | Gives a double-quoted string `%x()` is a shell command       |
| %i()     | Gives an array of symbols (Ruby >= 2.0.0)                    |
| %s()     | Turns `foo` into a symbol (`:foo`)                           |
| &Proc    | Convert a proc to block.                                     |
| &Symbol  | Convert a symbol to block.                                   |
| &Lambda  | Convert a lambda to block.                                   |

### Definitions

| Concept | Definition                                             |
| ------- | :----------------------------------------------------- |
| Closure | Persistent local variable scope.                       |
| Block   | Nameless methods (anon. functions, executable code).   |
| Proc    | Saved block.                                           |
| Lambda  | Same as a proc with different inner functionalities.   |
| yield   | Keyword to transfer flow control and execute blocks.   |
| require | Bring in the contents of another file.                 |
| include | Object-oriented inheritance mechanism used for mixins. |
| extend  | Mixes a module’s methods at the class level.           |

#### Procs Advantages

They have all the power and abilities of objects. Prevent from retype.

#### Lambdas vs. Procs

Lambda checks the number of arguments passed to it, while proc does not.

When lambda returns, it passes control back to the calling method; Proc does it immediately.