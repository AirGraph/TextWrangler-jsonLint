# TextWrangler-jsonLint
Applescript for linting json documents in TextWrangler

## Questions and Bug Reports
* mailing list: Victor.Vazin@gmail.com

## Installation
Install NodeJS and NPM (https://nodejs.org/en/download/) 

Install jsonlint (https://www.npmjs.com/package/jsonlint)
```
npm install jsonlint -g
```
Place symbolic link to NodeJS in /usr/bin
```
cd /usr/bin
sudo ln -s /usr/local/bin/node ./node
```
Copy jsonLint text to Script Editor and save it as jsonLint.scpt to
```
~/Library/Application Support/TextWrangler/Scripts
```
Launch TextWrangler, open json document, select jsonLint in script menu and enjoy...

## TextWrangler-jsLint
https://github.com/AirGraph/TextWrangler-jsLint

## QuickStart
You can add any jsonlint iptions in source script like this:
```
set shellScript to "cd /usr/local/bin" & ";" & "./jsonlint " & POSIX path of scriptFile & " -c"
```

## TextWrangler-jsLint
https://github.com/AirGraph/TextWrangler-jsLint
