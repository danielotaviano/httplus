# httplus

formats a url by adding http. 

## Installation

Use the package manager to install httplus.

```bash
npm i httplus
yarn add httplus
```

## Usage

```js
const { addHttp } = require('httplus')

addHttp('www.google.com') // https://www.google.com
addHttp('https://www.google.com') // https://www.google.com

```

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License
[MIT](https://choosealicense.com/licenses/mit/)
