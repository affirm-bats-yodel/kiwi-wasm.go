# kiwi-wasm.go

A Kiwi NLP Analyzer with Go &amp; WASM (WebAssembly, wasmer-go)

## How to

### Grab WASM from npm

* npm package to grab: https://www.npmjs.com/package/kiwi-nlp
* https://stackoverflow.com/a/50935081

```bash
curl -vvv https://registry.npmjs.org/kiwi-nlp/0.18.1 | jq .dist.tarball
```

```
"https://registry.npmjs.org/kiwi-nlp/-/kiwi-nlp-0.18.1.tgz"
```

* Download `*.tgz` link.
* For Example:

```bash
curl -LO "https://registry.npmjs.org/kiwi-nlp/-/kiwi-nlp-0.18.1.tgz"
```

* Verify HashSum of `*.tgz` if necessary.
* For Example:

```bash
# TODO
```

* Decompress `*.tgz`.
* For Example:

```bash
tar -xzvf "https://registry.npmjs.org/kiwi-nlp/-/kiwi-nlp-0.18.1.tgz"
```
