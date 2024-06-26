# Readings: Express, NPM, TDD, CI/CD

#### Explain middleware, answer as though I were a non-technical recruiter.

Middleware is like a connector that helps different software programs talk to each other effectively. It sits between them, making sure they understand each other's messages and can work together smoothly.

#### Express the most popular __ __ ____.

Middleware

#### Express is “unopinionated.” What does that mean?

It means that it doesn't enforce a specific way of structuring or organizing your web applications. It gives developers a lot of freedom to build their applications the way they want, without imposing strict rules or conventions.

#### What is a module and why is modularity useful to us as developers?

It is like a building block of code that performs a specific task or contains related functions. It helps keep our code organized and easy to manage by breaking it into smaller, reusable parts. Modularity is useful because it allows developers to write cleaner, more maintainable code. Instead of having one giant chunk of code, we can separate it into modules, making it easier to understand, debug, and update.

#### What version of npm are you running on your machine?

10.5.1

#### What command would you type to install a library/package called ‘jshint’ into your node project?

npm install jshint

#### Explain why tests are important. Please explain as though I were your non technical elder.

Tests are important because they help make sure that our programs work as they should. They're like double-checks that help catch mistakes or problems in our code before they cause any trouble. Just like how we might check the locks on our doors to make sure they keep our homes safe, tests check our code to keep our programs running smoothly and avoid headaches later on.

#### What are three expected benefits of testing

1. **Bug Prevention:** Testing helps catch mistakes and problems in code early on, preventing them from causing issues later.
2. **Increased Confidence:** Knowing that our code has been tested gives us more confidence that it will work as intended.
3. **Better Quality:** Testing helps improve the overall quality of our software by identifying and fixing issues before they reach users.

#### Name at lest 2 individual pitfalls and at least 2 team pitfalls commonly encountered while writing tests.

Individual Pitfalls:
1. **Overlooking Edge Cases:** Forgetting to test unusual or extreme scenarios in the code.
2. **Testing Everything:** Spending too much time testing trivial parts of the code, neglecting more critical areas.

Team Pitfalls:
1. **Lack of Communication:** Not discussing test strategies or priorities within the team, leading to inefficiencies.
2. **Dependency Issues:** Tests failing due to changes in unrelated parts of the codebase, causing confusion and frustration.

#### What are three benefits of Continuous Integration?

1. **Early Detection of Issues:** CI detects errors or bugs in code early in the development process, making them easier and cheaper to fix.
2. **Improved Collaboration:** CI encourages frequent integration of code changes, promoting collaboration among team members and reducing integration conflicts.
3. **Faster Feedback:** CI provides rapid feedback on code changes, allowing developers to quickly identify and address issues, leading to faster development cycles.

#### What is the difference between Continuos Delivery and Continuous Deployment?

In simple terms, Continuous Delivery means automatically releasing code to a testing or staging environment after it passes tests, while Continuous Deployment automatically releases code to production after passing tests. Continuous Delivery stops at the testing or staging phase, while Continuous Deployment goes all the way to production.

#### Explain how GitHub fits into this process assuming the listener comes from a non-technical background

GitHub is like a central hub where developers store and manage their code. It's a place where teams collaborate on building software projects. In the context of Continuous Integration, GitHub plays a crucial role as the repository where developers push their code changes. Continuous Integration systems often connect to GitHub, automatically grabbing the latest code changes from there. This integration allows developers to continuously test their code and ensure that it works well together before it's released to users. So, GitHub acts as the starting point for the Continuous Integration process, where all the code lives and where changes are tracked and managed.