# Vue Airbnb Styled VSCode Snippets

## Description

These snippets are for commonly used Vue code following the Airbnb style guide.

Heavily inspired by [Sarah Drasner](https://github.com/sdras/vue-vscode-snippets)

## Installation

- go here [vscode Extensions Marketplace](https://marketplace.visualstudio.com/items?itemName=dannynpham.vue-airbnb-vscode-snippets)

```javascript
ext install Vue VSCode Snippets
```

You can enable tab completion (recommended) by opening `Code > Preferences > Settings` (on a Mac) and applying `"editor.tabCompletion": "onlySnippets"` to your personal settings

## Snippets

### Vue

| Snippet     | Purpose                                    |
| ----------- | ------------------------------------------ |
| `vbase`     | Scaffold single file component base        |

### Template

| Snippet           | Purpose                             |
| ----------------- | ----------------------------------- |
| `vfor`            | v-for directive                     |
| `von`             | v-on click handler with arguments   |
| `vel-props`       | Component element with props        |

### Script

| Snippet          | Purpose                                                       |
| ---------------- | --------------------------------------------------------------|
| `vdata`          | Component data as a function                                  |
| `vmethod`        | Vue method                                                    |
| `vcomputed`      | Vue computed property                                         |
| `vwatcher`       | Vue watcher                                                   |
| `vwatch-opt`     | Vue watcher with options                                      |
| `vbeforecreate`  | beforeCreate lifecycle method                                 |
| `vcreated`       | created lifecycle method                                      |
| `vbeforemount`   | beforeMount lifecycle method                                  |
| `vmounted`       | vmounted lifecycle method                                     |
| `vbeforeupdate`  | beforeUpdate lifecycle method                                 |
| `vupdated`       | updated lifecycle method                                      |
| `vbeforedestroy` | beforeDestroy lifecycle method                                |
| `vdestroyed`     | destroyed lifecycle method                                    |
| `vprops`         | Props with type and default                                   |
| `vprops-required`| Props with type and required                                  |
| `vimport`        | Import one component into another                             |
| `vcomponents`    | Import one component into another within the export statement |
| `vmapstate`      | import mapState from Vuex into vue component component        |
| `vmapgetters`    | import mapGetters from Vuex into vue component component      |
| `vmapmutations`  | import mapMutations from Vuex into vue component component    |
| `vmapactions`    | import mapActions from Vuex into vue component component      |
| `vimport-lib`    | Import a library                                              |
| `vbasetest`      | Scaffolds a unit testing component                            |
| `vtest`          | A single unit test                                            |

### Vuex

| Snippet         | Purpose                        |
| --------------- | ------------------------------ |
| `vstore`        | Scaffold Base for Vuex store   |
| `vgetter`       | Vuex Getter                    |
| `vmutation`     | Vuex Mutation                  |
| `vaction`       | Vuex Action                    |
| `vmodule`       | Vuex Module                    |

## Contributing

This is an open source project open to anyone. Contributions are welcome [github](https://github.com/dannynpham/vue-airbnb-vscode-snippets)
