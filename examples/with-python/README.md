<p align="center"><img src="https://i.imgur.com/ZWNgF2C.png"></p>

## Requirements

- pyinstaller (`pip install pyinstaller`)

## Usage

### Create an App

```bash
# with `nextron`
$ nextron init my-app --template with-python

# with npx
$ npx create-nextron-app my-app --example with-python

# with yarn
$ yarn create nextron-app my-app --example with-python
```

### Use it

```bash
$ cd my-app

# Install dependencies
$ yarn (or `npm install`)

# Run development mode
$ yarn dev (or `npm run dev`)

# Build packages
$ yarn build (or `npm run build`)
```
