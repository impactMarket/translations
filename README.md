# Impact Market translation files

## Instructions
- Add `[lang].json` file to `./translations` folder
- Required and add it to exported object in `./index.js`
- Usage - just import as module:
```javascript
import translations from 'translations';

const { en } = translations;

console.log(en.beneficiaries);
```

## notes
- Just keep it simple and create readable keys :smile:
