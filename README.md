# js-react-redux-yasnippets

## v0.0.1
Rewrote ES7 *React/Redux/GraphQL/React-Native snippets*
  ([marketplace](https://marketplace.visualstudio.com/items?itemName=dsznajder.es7-react-js-snippets),
  [github](https://github.com/dsznajder/vscode-es7-javascript-react-snippets))

## v0.0.2
Rewrote and integrated *Reactjs code snippets*
  ([marketplace](https://marketplace.visualstudio.com/items?itemName=xabikos.ReactSnippets),
  [github](https://github.com/xabikos/vscode-react))

**Changes:**  
All snippets matching pattern "static propTypes" are prepended with "p". This
stands for "proposal".
- prccp
- prrdpc
- prpcp
- prcep
- prncr

You should be able to find their corresponding ES6 versions in the integrated
package's description, or by their old name.

### INSTALLATION


The package can be installed from melpa.

After you've successfully installed latest versions of **yasnippet** and **js-react-redux-yasnippets** the snippets should be available in all modes derived from js-mode

**js-react-redux-yasnippets** will not register its snippets dir to yas-snippet-dirs automatically.

```
(use-package js-react-redux-yasnippets
    :after yasnippet ;; will not work if not adding this line
    )
```
After adding :after **yasnippet** as above, **js-react-redux-yasnippets** works.
