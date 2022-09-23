# Webpack
- Require assets, loaded when needed
- Code splitting
- Minimizes (Loading time)
- Transformation
## New features in webpack 4
- No longer support of Node.js 4
- Upto 98% faster.
- Dev and production mode.
- Dev - Speed of build is optimized.
- Production mode build size is prioritized.
- Support for WebAssembly

	mkdir Practice
	cd mkdir
	cd Practice
	mkdir 01_03
	cd 01_03
	npm -v
	node -v
	mkdir start
	cd start
	npm init
	clear
	npm install webpack@4.28.4 --save-dev
	npm install webpack-cli
	npm install webpack-cli@3.2.1 --save-dev
	vi package.json
	npm install jquery --save
	webpack
	node_modules\.bin\webpack
	npx webpack
	npx webpack --config my.custom.webpack.config.js
	npm run build
## Webpack Loaders
- Perform transformations on files
- Help load files and images
- Deal with dialects
- Transpiling
  - JSX must be transformed to plain JS
  - ECMAScript 6 --||--
- babel
  - babel-loader transforms to plain JS.
  - babel-loader is loader babel/core is actual babel package that handles transformation

	npm install babel-loader @babel/core --save-dev
	npm run build
	npm install @babel/preset-env
	npm run build
	npm install react react-dom --save
