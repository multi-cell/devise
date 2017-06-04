# devise

## Commands

To install dependencies:

```bash
$ yarn
```

To develop:

```bash
$ yarn run dev```

To build for production:

```bash
$ yarn run build
```

To build typedefs for Vue components:

```bash
$ yarn run build:types
```

To watch and build typedefs for Vue components:

```bash
$ yarn run watch:types
```

To lint your code:

```bash
$ yarn run lint
```

To launch Vorlon to inspect your app:

```bash
$ yarn run vorlon
```

## Known Caveats

When you build for production, UglifyJS will return an error, but your app will build properly. If you can figure out
how to fix the error (because as long as everything works I don't care to try), please do so and file a merge request.

---

Generated by [VuePack](https://github.com/egoist/vuepack) and modified for typescript.
