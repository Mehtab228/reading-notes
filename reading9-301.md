# Functional Programming

## --

### *What is functional programming?

- Functional programming is a programming paradigm — a style of building the structure and elements of computer programs — that treats computation as the evaluation of mathematical functions and avoids changing-state and mutable data

### *What is a pure function and how do we know if something is a pure function?

- t returns the same result if given the same arguments (it is also referred as deterministic)
- It does not cause any observable side effects


### *What are the benefits of a pure function?

- The code’s definitely easier to test. We don’t need to mock anything. So we can unit test pure functions with different contexts:

- Given a parameter A → expect the function to return value B
- Given a parameter C → expect the function to return value D

### *What is immutability?

- When data is immutable, its state cannot change after it’s created. If you want to change an immutable object, you can’t. Instead, you create a new object with the new value

### *What is Referential transparency?

- Basically, if a function consistently yields the same result for the same input, it is referentially transparent

### *What is a module?

- Modules are small units of independent, reusable code that is desired to be used as the building blocks in creating a non-trivial Javascript application

### *What does the word ‘require’ do?

- require() statement basically reads a JavaScript file, executes it, and then proceeds to return the export object. require() statement not only allows to add built-in core NodeJS modules but also community-based and local modules

### *How do we bring another module into the file the we are working in?

- As we have learned in the previous example, we can’t access the functions defined in one module in another module by default. To access the module functions, we have to export the functions and import them in the file we want to call the functions
