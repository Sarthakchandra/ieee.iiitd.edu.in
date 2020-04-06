# [ieee.iiitd.edu.in](http://ieee.iiitd.edu.in)

> Official website for IIIT Delhi's IEEE Student Branch.

## Build

Node.js and npm are required to install dependencies and build the files. Once installed,

1. Install dependencies: `npm install`.
1. Install `stylus` globally to compile `.styl` files: `npm i -g stylus`.
1. To start the dev-server: `npm run start`, which will build files with webpack in `dist/` and start a local server.
1. For production: `npm run build`, and copy these files to the desired location.

To create a new page: `node ./scripts/create-new-page <PAGE-NAME>`.

## License

[MIT](LICENSE)
