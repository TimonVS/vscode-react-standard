> This is a fork of [vscode-react](https://github.com/xabikos/vscode-react) following [JavaScript Standard Style](http://standardjs.com/).

# VS Code React Standard Style snippets

This extension contains code snippets for [React][react] following the [JavaScript Standard Style](http://standardjs.com/) guidelines and is based on the awesome [babel-sublime-snippets][babelsublime] package.

[![Version](http://vsmarketplacebadge.apphb.com/version/TimonVS.ReactSnippetsStandard.svg)](https://marketplace.visualstudio.com/items?itemName=TimonVS.ReactSnippetsStandard)
[![Installs](http://vsmarketplacebadge.apphb.com/installs/TimonVS.ReactSnippetsStandard.svg)](https://marketplace.visualstudio.com/items?itemName=TimonVS.ReactSnippetsStandard)
[![Ratings](https://vsmarketplacebadge.apphb.com/rating/TimonVS.ReactSnippetsStandard.svg)](https://marketplace.visualstudio.com/items?itemName=TimonVS.ReactSnippetsStandard)

This extension contains code snippets for [Reactjs][react] and is based on the awesome [babel-sublime-snippets][babelsublime] package.

## Installation

In order to install an extension you need to launch the Command Pallete (Ctrl + Shift + P or Cmd + Shift + P) and type Extensions.
There you have either the option to show the already installed snippets or install new ones.

Launch VS Code Quick Open (Ctrl + P or Cmd + P), paste the following command, and press enter.

```javacript
ext install ReactSnippetsStandard
```

Alternatively you can open the extensions panel and search for 'React snippets Standard'.

## Supported languages (file extensions)
* JavaScript (.js)
* TypeScript (.ts)
* JavaScript React (.jsx)
* TypeScript React (.tsx)
* JSX after installing the [corresponding extension](https://marketplace.visualstudio.com/items?itemName=TwentyChung.jsx)

## Snippets

Below is a list of all available snippets and the triggers of each one. The **⇥** means the `TAB` key.

| Trigger  | Content |
| -------: | ------- |
| `rcc→`   | class component skeleton |
| `rccp→`  | class component skeleton with prop types after the class |
| `rcjc→`  | class component skeleton without import and default export lines |
| `rcfc→`  | class component skeleton that contains all the lifecycle methods |
| `rsc→`   | stateless component skeleton |
| `rscp→`  | stateless component with prop types skeleton |
| `rpt→`   | empty propTypes declaration |
| `con→`   | class default constructor with props|
| `conc→`  | class default constructor with props and context |
| `est→`   | empty state object |
| `cwm→`   | `componentWillMount method` |
| `cdm→`   | `componentDidMount method` |
| `cwr→`   | `componentWillReceiveProps method` |
| `scu→`   | `shouldComponentUpdate method` |
| `cwup→`  | `componentWillUpdate method` |
| `cdup→`  | `componentDidUpdate method` |
| `cwun→`  | `componentWillUnmount method` |
| `ren→`   | `render method` |
| `sst→`   | `this.setState with object as parameter` |
| `ssf→`   | `this.setState with function as parameter` |
| `props→` | `this.props` |
| `state→` | `this.state` |
| `bnd→`   | `binds the this of method inside the constructor` |

The following table lists all the snippets that can be used for prop types.
Every snippet regarding prop types begins with ```pt``` so it's easy to group it all together and explore all the available options.
On top of that each prop type snippets has one equivalent when we need to declare that this property is also required.
For example ```pta``` creates the ```PropTypes.array``` and ```ptar``` creates the ```PropTypes.array.isRequired```

| Trigger  | Content |
| -------: | ------- |
| `pta→`   | `PropTypes.array,` |
| `ptar→`  | `PropTypes.array.isRequired,` |
| `ptb→`   | `PropTypes.bool,` |
| `ptbr→`  | `PropTypes.bool.isRequired,` |
| `ptf→`   | `PropTypes.func,` |
| `ptfr→`  | `PropTypes.func.isRequired,` |
| `ptn→`   | `PropTypes.number,` |
| `ptnr→`  | `PropTypes.number.isRequired,` |
| `pto→`   | `PropTypes.object.,` |
| `ptor→`  | `PropTypes.object.isRequired,` |
| `pts→`   | `PropTypes.string,` |
| `ptsr→`  | `PropTypes.string.isRequired,` |
| `ptnd→`  | `PropTypes.node,` |
| `ptndr→` | `PropTypes.node.isRequired,` |
| `ptel→`  | `PropTypes.element,` |
| `ptelr→` | `PropTypes.element.isRequired,` |
| `pti→`   | `PropTypes.instanceOf(ClassName),` |
| `ptir→`  | `PropTypes.instanceOf(ClassName).isRequired,` |
| `pte→`   | `PropTypes.oneOf(['News', 'Photos']),` |
| `pter→`  | `PropTypes.oneOf(['News', 'Photos']).isRequired,` |
| `ptet→`  | `PropTypes.oneOfType([PropTypes.string, PropTypes.number]),` |
| `ptetr→` | `PropTypes.oneOfType([PropTypes.string, PropTypes.number]).isRequired,` |
| `ptao→`  | `PropTypes.arrayOf(PropTypes.number),` |
| `ptaor→` | `PropTypes.arrayOf(PropTypes.number).isRequired,` |
| `ptoo→`  | `PropTypes.objectOf(PropTypes.number),` |
| `ptoor→` | `PropTypes.objectOf(PropTypes.number).isRequired,` |
| `ptsh→`  | `PropTypes.shape({color: PropTypes.string, fontSize: PropTypes.number}),` |
| `ptshr→` | `PropTypes.shape({color: PropTypes.string, fontSize: PropTypes.number}).isRequired,` |


[react]: https://facebook.github.io/react/
[babelsublime]: https://github.com/babel/babel-sublime-snippets
[javacript]: https://github.com/TimonVS/vscode-react-standard
