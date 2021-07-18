# Outline snippets

Snippets for the Outline Design system. Extended from [Lit Snippets](https://marketplace.visualstudio.com/items?itemName=lit.lit-snippets) to add Outline specific commands to speed up development.

## Features

- Supports TypeScript with Lit 2.0

## List

Includes all snippets from [Lit Snippets](https://marketplace.visualstudio.com/items?itemName=lit.lit-snippets) as well as additional Outline specific commands for scaffolding components and stories

### OutlineElement

| Trigger          | Snippet                                                 |
| ---------------- | ------------------------------------------------------- |
| outline template | Create Outline subclass with styles and render function |

### Outline Story

| Trigger       | Snippet                                  |
| ------------- | ---------------------------------------- |
| outline story | Create Outline component Storybook story |

### Element and Its Property Snippets

| Trigger        | Snippet                                                      |
| -------------- | ------------------------------------------------------------ |
| litbase        | Create LitElement subclasss                                  |
| lit template   | Create LitElement subclasss with styles and render fn        |
| litprop        | Generate property                                            |
| litquery       | Generate @query property                                     |
| litqueryall    | Generate @queryall property                                  |
| litrender      | Generate render function with lit-html                       |
| litstyles      | Generate `styles` static property                            |
| ctlit template | Create @conectate/ct-lit subclasss with styles and render fn |

### Event Related Snippets

| Trigger                             | Snippet                             |
| ----------------------------------- | ----------------------------------- |
| addeventlistener                    | Generate component's event listener |
| litfire \| fire \| litdispatchevent | Generate dispatch of the event      |

### Custom Element [Lifecycle Callback](https://developers.google.com/web/fundamentals/web-components/customelements#reactions) Snippets

| Trigger                  | Snippet                                                                                                                                                                    |
| ------------------------ | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| connectedcallback        | Generate `connectedCallback()`                                                                                                                                             |
| disconnectedcallback     | Generate `disconnectedCallback()`                                                                                                                                          |
| adoptedcallback          | Generate `adoptedCallback()`                                                                                                                                               |
| attributechangedcallback | Generate `attributechangedCallback(_,_,_)`                                                                                                                                 |
| observedattributes       | Generate `static get observedAttributes()` see [Observing changes to attributes](https://developers.google.com/web/fundamentals/web-components/customelements#attrchanges) |

### Other Snippets

| Trigger   | Snippet              |
| --------- | -------------------- |
| importele | Import other element |

## Development

Install dependencies
`yarn install`

To package extension locally
`yarn run package`

Install package at root
`code --install-extension ./outlne-snippets-<version number>.vsix`

Uninstall package
`code --uninstall-extension ./outlne-snippets-<version number>.vsix`

Publish package
`yarn run dist`

## Contact

(TODO)

## License

MIT
