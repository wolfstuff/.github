# Contributing

Thank you for your willingness to contribute to this project! We greatly appreciate your efforts. Please note our brief [code of conduct](CODE_OF_CONDUCT.md) before proceeding.

## Issues
When creating a new Issue...

1. check to see if your Issue has already been raised
2. use an appropriate Issue template when available
3. select appropriate tags
4. never disclose security vulnerabilities in an Issue; refer to this project's [security policy](SECURITY.md)

## Commit Messages
Always be clear when describing the changes you commit to the project. Shorter commit messages are fine for minor changes, but anything major should include more information:

```shell
$ git commit -m "a summary of your changes
> 
> Additional text describing what was changed and why."
```

## Coding Conventions
This project adheres to a set of coding conventions which include the following:

* indentation uses four spaces instead of tabs
* semicolons are required at the end of each statement
* single quotes are required for strings, excluding template strings that use interpolation
* spaces are required after key words, array elements, and operators
* blocks belong on the same line as the reserved word that precedes them
* files end in a line feed character
* and more!

Enabling EditorConfig in your IDE will help enforce the basics in your editor, but it won't catch everything. For that, this project uses ESLint to enforce consistent coding conventions between contributors.

## Pull Requests
When creating a new Pull Request...

1. use an appropriate Pull Request template when available
2. if applicable, reference any Issue(s) related to your Pull Request
3. check your code against ESLint by running the `npm run eslint` script
4. provide tests for any code you contribute
5. note that all Pull requests will be reviewed and discussed before they are merged

## Licensing
At the moment, none of the code in this project is licensed.