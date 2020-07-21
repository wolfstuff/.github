# Contributing

Thank you for your willingness to contribute! We greatly appreciate your efforts.

## Issues
1. Check to see if your Issue has already been raised.
2. When creating a new Issue, use an appropriate Issue template when available.
3. Select appropriate tags for your Issue.
4. Never disclose security vulnerabilities in an Issue. Refer to this project's [security policy](SECURITY.md).

## Commit Messages
Always be clear when describing the changes you commit to the project. Shorter commit messages are fine for minor changes, but anything major should include more information:

```shell
$ git commit -m "a summary of your changes
> 
> Additional text describing what was changed and why."
```

## Coding Conventions
This project adheres to a set of coding conventions which include the following:

* Indentation uses four spaces instead of tabs.
* Semicolons are required at the end of each statement.
* Single quotes are required for strings, excluding template strings that use interpolation.
* Spaces are required after key words, array elements, and operators.
* Blocks belong on the same line as the reserved word that precedes them.
* Files end in a line feed character.

Enabling EditorConfig in your IDE will help enforce the basics in your editor, but it won't catch everything. For that, this project uses ESLint to enforce consistent coding conventions.

## Pull Requests
1. When creating a new Pull Request, use an appropriate Pull Request template when available.
2. If applicable, reference whatever Issue is related to your Pull Request.
3. Please check all code against ESLint by running the `npm run eslint` script prior to opening your Pull Request. It will enforce our coding conventions as well as check for common JavaScript mistakes.
4. Pull requests will be reviewed and discussed before they are merged.

## Licensing
At the moment, none of the code in this project is licensed.