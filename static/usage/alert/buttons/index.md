import Playground from '@site/src/components/global/Playground';

import javascript from './javascript.md';
import react from './react.md';
import vue from './vue.md';

import angularHTML from './angular/angular_html.md';
import angularTS from './angular/angular_ts.md';

<Playground
  size="300px"
  code={{
    javascript,
    react,
    vue,
    angular: {
      files: {
        'src/app/example.component.html': angularHTML,
        'src/app/example.component.ts': angularTS,
      },
    },
  }}
  src="usage/alert/buttons/demo.html"
/>