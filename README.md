# Course 3 - DevOps with Rust

Part of the Coursera
specialization [Rust Programming Specialization](https://www.coursera.org/specializations/rust-programming) (Duke
University).

- Part 1: [Rust Programming](https://github.com/amasotti/duke-rust-specialization-1)
- Part 2: [Rust Programming for Data Engineering](https://github.com/amasotti/duke-rust-specialization-2)
- Part 3: this repository
- Part 4: [Rust with Linux Command Line CLI Tools](https://www.coursera.org/learn/python-rust-linux)
- Part 5: [Rust for ML Ops](https://www.coursera.org/learn/rust-llmops)

This is the second course of the specialization, which focuses on data engineering with Rust. It is all about performant
handling of date, ETL pipelines and MLOps.

__Instructor__: [Alfredo Deza](https://www.linkedin.com/in/alfredodeza/)

### Structure

- [Week1](week1) - Introduction
    - 

## Run

I've chosen to organize my snippets in separate cargo projects, under the directories
named after the course week. They don't follow exactly the same structure as the course.

The [just](https://just.systems/man/en/chapter_1.html) file is used to confortably run the snippets
in the different subfolders without having to manually navigate to them.

```sh
# In the justfile I've given custom names to the subfolders (see below)
# simple-api -> week1/0-simple-rust-api/simple-api

# To run them, just type
just run simple-api 

# To test them
just test simple-api

# To build
just build simple-api

# To lint
just lint simple-api 

# To clean
just clean simple-api
```

Some aliases are defined (just lazyness):

- `just t` -> `just test`
- `just r` -> `just run`
- `just b` -> `just build`
- `just l` -> `just lint`
- `just c` -> `just clean`
