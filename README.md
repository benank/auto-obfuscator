# Auto Obfuscator
A simple NodeJS program that obfuscates HTML and Javascript and minifies/uglifies CSS. Originally written for use with *Just Cause 3 Multiplayer*. It recursively iterates through directories and modifies files in the client_package directory. It uses [Javascript Obfuscator](https://www.npmjs.com/package/javascript-obfuscator), [Clean CSS](https://www.npmjs.com/package/clean-css), and [an HTML source code obfuscator](http://snapbuilder.com/code_snippet_generator/obfuscate_html_source_code/). After obfuscation, it takes any files in a `/ui/` directory and puts them in `ObfuscatedUI`.

## Installation
1. Install the required node modules using `npm install`.

## Usage
1. Copy your files to `ToObfuscate`. It should look like `ToObfuscate/mypackage/client_package/...`.
2. Run the auto obfuscator using `node obfuscator.js`.
3. The program should tell you what files were obfuscated.