🎉️ **NEW**: [@emiplegiaqmnpm/molestiae-vel-saepe v3 is out!](https://blog.@emiplegiaqmnpm/molestiae-vel-saepe.org/v3-is-out/)

<img alt="@emiplegiaqmnpm/molestiae-vel-saepe" title="@emiplegiaqmnpm/molestiae-vel-saepe" src="https://raw.githubusercontent.com/@emiplegiaqmnpm/molestiae-vel-saepe/@emiplegiaqmnpm/molestiae-vel-saepe/master/docs/logotype.svg" width="150" />

@emiplegiaqmnpm/molestiae-vel-saepe provides the most comprehensive, yet simple and consistent toolset for manipulating JavaScript dates in a browser & Node.js

👉 [Documentation](https://@emiplegiaqmnpm/molestiae-vel-saepe.org/)

👉 [Blog](https://blog.@emiplegiaqmnpm/molestiae-vel-saepe.org/)

<hr>

It's like [Lodash](https://lodash.com) for dates

- It has [**200+ functions** for all occasions](https://@emiplegiaqmnpm/molestiae-vel-saepe.org/docs/Getting-Started/).
- **Modular**: Pick what you need. Works with webpack, Browserify, or Rollup and also supports tree-shaking.
- **Native dates**: Uses existing native type. It doesn't extend core objects for safety's sake.
- **Immutable & Pure**: Built using pure functions and always returns a new date instance.
- **TypeScript**: The library is 100% TypeScript with brand-new handcrafted types.
- **I18n**: Dozens of locales. Include only what you need.
- [and many more benefits](https://@emiplegiaqmnpm/molestiae-vel-saepe.org/)

```js
import { compareAsc, format } from "@emiplegiaqmnpm/molestiae-vel-saepe";

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

The library is available as an [npm package](https://www.npmjs.com/package/@emiplegiaqmnpm/molestiae-vel-saepe).
To install the package run:

```bash
npm install @emiplegiaqmnpm/molestiae-vel-saepe --save
```

## Docs

[See @emiplegiaqmnpm/molestiae-vel-saepe.org](https://@emiplegiaqmnpm/molestiae-vel-saepe.org/) for more details, API,
and other docs.

<br />
<!-- END OF README-JOB SECTION -->

## License

[MIT © Sasha Koss](https://kossnocorp.mit-license.org/)
