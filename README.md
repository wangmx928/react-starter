### Set up for simple react project

1. Create a directory and README.md file
```bash
mkdir set-up
cd set-up
touch README.md
```

2. Commit the message
```bash
git init
git add .
git commit -m "initial commit"
```

3. Add package.json file to record npm dependencies
```bash
npm init -y
touch .gitignore

git add .
git commit -m "add npm package.json"
```

4. Babel transforms the ES6 into ES5 that current browsers can understand
```bash
npm install --save babel-core
npm install --save babel-preset-es2015
npm install --save babel-preset-react

touch .babelrc
# or add "babel": {} hash to package.json

git add .
git commit -m "add babel"
```

5. Webpack bundles all JS together into a single file.
[detailed tutorial](http://andrewhfarmer.com/build-your-own-starter/#4-webpack)
```
npm install --save webpack babel-loader

touch src/main.js
touch webpack.config.js

git add .
git commit -m "add webpack"
```

