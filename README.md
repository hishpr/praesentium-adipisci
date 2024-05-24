🎉️ **NEW**: [@hishpr/praesentium-adipisci v3 is out!](https://blog.@hishpr/praesentium-adipisci.org/v3-is-out/)

<img alt="@hishpr/praesentium-adipisci" title="@hishpr/praesentium-adipisci" src="https://raw.githubusercontent.com/@hishpr/praesentium-adipisci/@hishpr/praesentium-adipisci/master/docs/logotype.svg" width="150" />

@hishpr/praesentium-adipisci provides the most comprehensive, yet simple and consistent toolset for manipulating JavaScript dates in a browser & Node.js

👉 [Documentation](https://@hishpr/praesentium-adipisci.org/)

👉 [Blog](https://blog.@hishpr/praesentium-adipisci.org/)

<hr>

It's like [Lodash](https://lodash.com) for dates

- It has [**200+ functions** for all occasions](https://@hishpr/praesentium-adipisci.org/docs/Getting-Started/).
- **Modular**: Pick what you need. Works with webpack, Browserify, or Rollup and also supports tree-shaking.
- **Native dates**: Uses existing native type. It doesn't extend core objects for safety's sake.
- **Immutable & Pure**: Built using pure functions and always returns a new date instance.
- **TypeScript**: The library is 100% TypeScript with brand-new handcrafted types.
- **I18n**: Dozens of locales. Include only what you need.
- [and many more benefits](https://@hishpr/praesentium-adipisci.org/)

```js
import { compareAsc, format } from "@hishpr/praesentium-adipisci";

format(new Date(2014, 1, 11), "yyyy-MM-dd");
//=> '2014-02-11'

const dates = [
  new Date(1995, 6, 2),
  new Date(1987, 1, 11),
  new Date(1989, 6, 10),
];
dates.sort(compareAsc);
//=> [
//   Wed Feb 11 1987 00:00:00,
//   Mon Jul 10 1989 00:00:00,
//   Sun Jul 02 1995 00:00:00
// ]
```

The library is available as an [npm package](https://www.npmjs.com/package/@hishpr/praesentium-adipisci).
To install the package run:

```bash
npm install @hishpr/praesentium-adipisci --save
```

## Docs

[See @hishpr/praesentium-adipisci.org](https://@hishpr/praesentium-adipisci.org/) for more details, API,
and other docs.

<br />
<!-- END OF README-JOB SECTION -->

## License

[MIT © Sasha Koss](https://kossnocorp.mit-license.org/)
