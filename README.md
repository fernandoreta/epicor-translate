# Translate-script // json file with Google Translate API

## Usage
1. Clone this repo
2. Run `npm install`
3. Paste your json file content into fixtures/translate-json/en.json
4. Execute in the folder project: node translate-json APIKEY fileStringsToTranslate languages. 
    * EXAMPLE: `node translate-json APIKEY fixtures/translate-json/en.json es,fr,ru,zh`
5. All files goes into fixtures/translate-json

## Libraries used
* moment
* loadash
* path
* superagent
* superagent-promise