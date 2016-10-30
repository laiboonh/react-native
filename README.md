# React Native

#### Setup for Mac
1. Install XCode, make sure its updated
2. Install homebrew
3. `homebrew install node`
4. `homebrew install npm`
5. `npm install -g react-native-cli`
6. `react-native init albums`
7. `react-native run-ios`

#### Install lint for Atom
1. Search for linter-eslint
2. Install linter-eslint and linter

#### Install project specific lint config
1. `npm install --save-dev eslint-config-rallycoding`
2. create .eslintrc in project
```
{
  "extends" : "rallycoding"
}
```
