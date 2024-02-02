# Intro to JavaScript
01. Which keywords are used to declare a variable in JavaScript?

    > | Let, Var, and Const |

02. What is the definition of a function?

    > | A function is a subprogram designed to execute and complete a specific task when they are invoked. |

03. What are the `SOLID` principles?

    > |SOLID is an acronym standing for: Single responsibility, open-closed principles, Liskov substitution principle, interface segregation principle, and dependency inversion principle. |

04. Given this array: How could you remove the `pineapple`?

    ```js
    let fruit = ['apple', 'banana', 'pineapple', 'orange', 'strawberry']
    ```

    > | delete fruit[2];  |

05. Given these two objects: How could you add each to the others friends arrays?

    ```js
    let you = {
        name: "You",
        hair: true,
        friends: []
    }
    let them = {
        name: "Them",
        hair: false,
        friends: []
    }
    ```

    > |you.friends.push(them) 
        them.friends.push(you)  |

06. Give an example of a JavaScript `Conditional`:

    > | if(currentTime > 2200){
        console.log('time for bed')
    } else {
        console.log('do homework')
    } |

07. What is the main difference between `parameters` and `arguments`?

    > | Parameters are the empty placeholder variables assigned to functions, arguments are the actual values that are passed into parameters  |

08. Instead of writing everything to the console, what is a better way to debug your code?

    > | console.log values throughout your functions to get a visual of what the function is doing.  |

09. What is the difference between a `primitive` value and a `reference` value?

    > | A primitive value is a variable with a value that is scoped to where the variable is stored and has a single value.Reference values are objects, arrays, and functions. |

10. Demonstrate a loop that prints the numbers between -100 and 100?

    > | for(let i = -100; i <= 100; i++) {
        console.log(i)} |
