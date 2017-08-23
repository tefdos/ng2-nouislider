# ng2-nouislider
[![All Contributors](https://img.shields.io/badge/all_contributors-5-orange.svg?style=flat-square)](#contributors)

[![Build Status](https://travis-ci.org/tb/ng2-nouislider.svg?branch=master)](https://travis-ci.org/tb/ng2-nouislider)
[![npm version](https://badge.fury.io/js/ng2-nouislider.svg)](http://badge.fury.io/js/ng2-nouislider)
[![Downloads](http://img.shields.io/npm/dm/ng2-nouislider.svg)](https://npmjs.org/package/ng2-nouislider)

Angular2 nouislider component

See [demos](http://tb.github.io/ng2-nouislider/)

## Install

    npm i --save nouislider ng2-nouislider

## Import

    import { NouisliderModule } from 'ng2-nouislider';

### Styles

    @import "~nouislider/distribute/nouislider.min.css";

### SystemJS config

Add to map:

    'nouislider': 'node_modules/nouislider',
    'ng2-nouislider': 'node_modules/ng2-nouislider',

Add to packages:

    'nouislider': { main: 'distribute/nouislider.js', defaultExtension: 'js' },
    'ng2-nouislider': { main: 'src/nouislider.js', defaultExtension: 'js' },

## Usage

### Using ngModel

    <nouislider [connect]="true" [min]="0" [max]="15" [(ngModel)]="someRange"></nouislider>

### Within reactive forms

```js
this.form1 = this.formBuilder.group({ 'single': [ 10 ] });
```

```html
<form [formGroup]="form">
    <nouislider [min]="0" [max]="20" [step]="0.5" [formControl]="form.controls.single"></nouislider>
</form>
```

## Start development

    npm i
    npm start
    open http://localhost:8080

## License

MIT

## Contributors

<!-- ALL-CONTRIBUTORS-LIST:START - Do not remove or modify this section -->
| [<img src="https://avatars2.githubusercontent.com/u/71683?v=4" width="100px;"/><br /><sub>Tomasz Bak</sub>](http://twitter.com/tomaszbak)<br />[💻](https://github.com/tb/ng2-nouislider/commits?author=tb "Code") [👀](#review-tb "Reviewed Pull Requests") | [<img src="https://avatars2.githubusercontent.com/u/18688794?v=4" width="100px;"/><br /><sub>Giacomo Mazzamuto</sub>](https://github.com/gmazzamuto)<br />[💻](https://github.com/tb/ng2-nouislider/commits?author=gmazzamuto "Code") [👀](#review-gmazzamuto "Reviewed Pull Requests") | [<img src="https://avatars3.githubusercontent.com/u/7102450?v=4" width="100px;"/><br /><sub>Ryan Morris</sub>](https://github.com/ryan-morris)<br />[💻](https://github.com/tb/ng2-nouislider/commits?author=ryan-morris "Code") | [<img src="https://avatars2.githubusercontent.com/u/2569015?v=4" width="100px;"/><br /><sub>Sven Flickinger</sub>](https://github.com/naeramarth7)<br />[💻](https://github.com/tb/ng2-nouislider/commits?author=naeramarth7 "Code") | [<img src="https://avatars0.githubusercontent.com/u/8615481?v=4" width="100px;"/><br /><sub>Riku Kallio</sub>](https://github.com/RichieRock)<br />[💻](https://github.com/tb/ng2-nouislider/commits?author=RichieRock "Code") |
| :---: | :---: | :---: | :---: | :---: |
<!-- ALL-CONTRIBUTORS-LIST:END -->