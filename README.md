# Bacon Snippets

Bacon snippets are very pretty code snippets, based on EC6.

### String iterpolation examples:
<img src="https://media.giphy.com/media/1qYhirOfgLjRSP6kH5/giphy.gif" title="String interpolation">

### Promise examples:
<img src="https://media.giphy.com/media/Lqx1g08cht2mL77HoP/giphy.gif" title="Promises">

### Arrow function example:
<img src="https://media.giphy.com/media/1BhGnRQhWyKrRm6SYc/giphy.gif" title="Arrow function">

## Snippets

There is the list of available snippets:

| Key | Result | Description | Languages |
| --------- | ------ | --------- | ------ |
| a> | ``` () => { } ``` | Creates an arrow function | Typescript / Javascript |
| p> | ``` new Promise<any> ((resolve, reject) => { }); ``` | Creates a new promise | Typescript / Javascript |
| p>> | ``` let promise = new Promise<any> ((resolve, reject) => { }); ``` | Creates a new promise with variable | Typescript / Javascript |
| s> | ``` ${this.test} ``` | Creates an expression interpolation to use a variable inside of the interpolated string. | Typescript / Javascript |
| s>> | ``` `My ${this.subject} is awesome.` ``` | Creates a new interpolated string. | Typescript / Javascript |

## Compatibility
These snippets are based on [EC6][ec-6].


## Usage
To use the bacon snippets, install first the ``` bacol-snippets ``` (called ``` Bacon Snippets ```) extension.

After open the correct language file and use the TAB button to trigger the snippet.

It's also recommended to set this custom vscode setting:
```sh
"editor.tabCompletion": true
```

## Source code

This is the [repository][git-repo-url]



   [git-repo-url]: <https://github.com/npacucci/bacol-snippets>
   [ec-6]: <http://es6-features.org/#TypedArrays>
