# Credifit flutter challenge

In this exercise, you need to implement a Brazilian bank account digit validation.

Example:

- Itau (341): branch 1230 and account 12345-6 is incorrect. Calculated digit should be 5 (12345-5)
- Bradesco (237): branch 7777 and account 123456-7 is incorrect. Calculated digit should 0 (123456-0)

We are providing you the following artifacts:

- A codebase created with [slidy](https://pub.dev/packages/slidy), [Modular](https://pub.dev/packages/flutter_modular) and [MobX](https://pub.dev/packages/flutter_mobx)

Your task is to create a digit validator for Brazilian bank accounts, following the requirements below:

- User inputs: Bank name/number, branch number, account number with digit, and account type (checking / saving)
- Validation for at least Itau (341) and Bradesco (237). A "bonus" will be given for CEF (Caixa) implementation
- Output: digit validation

This problem is designed to give you some flavor of the work we do here at Credifit.
Please if you have any questions, just make your assumptions, comment on the code and follow along. Part of the skill is to make decisions. If you need to change any code already written, do so.

## Additional Requirements

- We love code quality! Be careful with the details.
- When in doubt, make a decision, comment the code and go ahead.
- Organize your code, including components, data structures, and state management - the way you would in a real project.
- At the end, we should be able to run the project (Flutter Web / Chrome) and run successfully.

## Getting started

To get started with the app, clone the repository by:

- By SSH: `git clone git@github.com:credifit-br/flutter_challenge.git`
- By HTTPS: `git clone https://github.com/credifit-br/flutter_challenge.git`

## Submitting

To submit your project, please push your code to a private repo on Github, and then share it with us:

- On Github: add credifit users [isorensen](https://github.com/isorensen), [victorjatoba](https://github.com/victorjatoba) and [lucas123ho](https://github.com/lucas123ho) as a collaborator.

For instance, to push your code from this existing repo to a brand new empty Github project, replace the ALLCAPS parts below:

- git remote rename origin old-origin
- git remote add origin git@github.com:YOURNAME/YOURPROJECT.git
- git push -u origin --all
- git push -u origin --tags
