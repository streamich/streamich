> [!IMPORTANT]
> If you or __your company__ are using any of my projects or like what I'm doing, please consider backing me
> up. I appreciate it! 🙏 Your support will help me allocate more time to the open source work.
> 
> - __[Become a sponsor](https://github.com/sponsors/streamich)__
> - __[Buy me a coffee](https://buymeacoffee.com/streamich)__ ☕️
> -  or send a Solana airdrop 🚀 🌘, SOL: `LJJwteDZjL8u2Uhh5giwVpRa5KcHLkDogYAZntYbMsD`


I maintain and contribute to OSS software, below is a list of my latest projects
and writings. My current focus is on developing CRDT and OT collaborative
editing solutions, local-first software, and Web3 apps.


---


#### My Projects

- UI and React
  - [`react-use`][react-use] and [`libreact`][libreact] &mdash; lots of React hooks and utility components.
  - [`nano-css`][nano-css] and [`nano-theme`][nano-theme] &mdash; the fastest and smallest CSS-in-JS library with lots of plugins (successor of [`freestyler`][freestyler]).
  - [`react-embed`][react-embed] &mdash; embed social widgets in your React app.
  - [`use-media`][use-media] &mdash; CSS media queries through React hook.
  - [`react-simple-player`][react-simple-player] &mdash; a minimalistic audio player React component.
  - [`clickable-json`][clickable-json] &mdash; JSON viewer and editor with hoverable and clickable objects.
  - [`flexible-input`][flexible-input] &mdash; React `<input>` and `<textarea>` components which stretch to fit the content.
  - [`awesome-styleguides`][awesome-styleguides] &mdash; index of style guides and design systems.
  - [`code-colors`][code-colors] and [`code-colors-react`][code-colors-react] &mdash; code syntax highlighting libraries.
  - [`use-t`][use-t] &mdash; a small internationalization library for React.
  - [`iconista`][iconista] &mdash; 100,000 free SVG icons, available on CDN and packaged as a React component.
  - [`react-router-lite`][react-router-lite] &mdash; a lightweight React router.
- Filesystem
  - [`memfs`][memfs] &mdash; a virtual filesystem for Node.js and browser, plus OPFS file system helpers.
  - [`unionfs`][unionfs] &mdash; creates a union of multiple filesystem volumes.
  - [`fs-monkey`][fs-monkey] &mdash; monkey-patches Node's `fs` module and `require` function.
  - [`linkfs`][linkfs] &mdash; redirects filesystem paths.
  - [`spyfs`][spyfs] &mdash; spies on filesystem actions.
  <!-- - `fs-zoo` 🔜 __soon__ &mdash; browser OPFS and other file system utilities. -->
- Collaborative editing
  - [`json-joy`](https://github.com/streamich/json-joy), a [JSON CRDT](https://jsonjoy.com/specs/json-crdt) implementation and collection of JSON awesomeness.
    - [`json-joy/json-crdt`](https://jsonjoy.com/libs/json-joy-js/json-crdt) &mdash; the fastest list CRDT implementation in JavaScript.
    - [`json-joy/json-patch`](https://jsonjoy.com/libs/json-joy-js/json-patch) &mdash; very fast JSON Patch (and JSON Pointer) implementation in JavaScript.
    - `json-joy/json-type` &mdash; the fastest JSON schema validation implementation in JavaScript.
  - [`collaborative-editor`][collaborative-editor] &mdash; General JSON CRDT `str` node sychnonization with any editor.
  - [`collaborative-input`][collaborative-input] &mdash; React `<input>` and `<textarea>` components with JSON CRDT real-time collaboration support.
  - `collaborative-ace` &mdash; JSON CRDT real-time collaboration bindings for Ace editor.
  - `collaborative-monaco` &mdash; JSON CRDT real-time collaboration bindings for the Monaco editor.
  - `collaborative-codemirror` &mdash; JSON CRDT real-time collaboration bindings for the CodeMirror editor.
  - [`json-pointer`][json-pointer] &mdash; JSON Pointer (RFC 6901) implementation with JIT compilation.
  - [`json-expression`][json-expression] &mdash; JSON Expression implementation with JIT compilation.
- Data structures, algorithms, and utilities
  - [`git-cz`][git-cz] &mdash; `feat: 🎸 emoji-fied Git commits`
  - [`sonic-forest`][sonic-forest] &mdash; very fast AVL, Splay, and Radix tree implementations in JavaScript.
  - [`thingies`][thingies] &mdash; a collection of useful TypeScript utilities.
  - [`rx-use`][rx-use] &mdash; useful RxJS observables for web apps.
  - [`tree-dump`][tree-dump] &mdash; utility to easily print tree-like structures.
  - [`cross-ci`][cross-ci] &mdash; env var normalization across CI/CD services.
  - `web4` 🔜 __soon__ &mdash; CRDT-based content-addressable local-first data repository.
- Parsing
  - [`json-pack`][json-pack] &mdash; the fastest CBOR, MessagePack, RESP3, UBJSON, JSON, and Bencode codecs in plain JavaScript.
  - [`jit-router`][jit-router] &mdash; the fastest HTTP router in JavaScript.
  - [`very-small-parser`][very-small-parser] &mdash; Small Markdown and HTML parser and formatter.
    - Supersedes [`md-mdast`](https://github.com/streamich/md-mdast) &mdash; extremely small and fast Markdown to MDAST parser.
  - [`mdast-flat`](https://github.com/streamich/mdast-flat) &mdash; MDAST format to flat-MDAST converter.
  - [`mqtt-codec`][mqtt-codec] 🧪💥 __experimental__ &mdash; the fastest MQTT packet parser for Node.js.
  - `jit-parser` 🧪💥 __experimental__ &mdash; PoC of PEG recursive descent backtracking JIT parser generator.
- Server & Networking
  - [`ass-js`][ass-js] 🧪💥 __experimental__ &mdash; X86_64 assembler compiler in JavaScript.
  - [`reactive-rcp`][reactive-rpc] 🧪💥 __experimental__ &mdash; a very fast and type safe [JSON Reactive RPC][spec-json-rx] server and client.
  - [`redis-joy`][redis-joy] 🧪💥 __experimental__ &mdash; a very fast Redis 7+ RESP3 standalone and cluster client.
  - [`node-multicore`][node-multicore] 🧪💥 __experimental__ &mdash; PoC of a very fast thread pool for Node.js.


[ass-js]: https://github.com/streamich/ass-js
[awesome-styleguides]: https://github.com/streamich/awesome-styleguides
[clickable-json]: https://github.com/streamich/clickable-json
[code-colors-react]: https://github.com/streamich/code-colors-react
[code-colors]: https://github.com/streamich/code-colors
[collaborative-editor]: https://github.com/streamich/collaborative-editor
[collaborative-input]: https://github.com/streamich/collaborative-input
[cross-ci]: https://github.com/streamich/cross-ci
[flexible-input]: https://github.com/streamich/flexible-input
[freestyler]: https://github.com/streamich/freestyler
[fs-monkey]: https://github.com/streamich/fs-monkey
[git-cz]: https://github.com/streamich/git-cz
[iconista]: https://github.com/streamich/iconista
[jit-router]: https://github.com/jsonjoy-com/jit-router
[json-pack]: https://github.com/jsonjoy-com/json-pack
[json-expression]: https://github.com/jsonjoy-com/json-expression
[json-pointer]: https://github.com/jsonjoy-com/json-pointer
[libreact]: https://github.com/streamich/libreact
[linkfs]: https://github.com/streamich/linkfs
[memfs]: https://github.com/streamich/memfs
[mqtt-codec]: https://github.com/streamich/mqtt-codec
[nano-css]: https://github.com/streamich/nano-css
[nano-theme]: https://github.com/streamich/nano-theme
[node-multicore]: https://github.com/streamich/node-multicore
[react-embed]: https://github.com/streamich/react-embed
[react-router-lite]: https://github.com/streamich/react-router-lite
[react-simple-player]: https://github.com/streamich/react-simple-player
[react-use]: https://github.com/streamich/react-use
[reactive-rpc]: https://github.com/jsonjoy-com/reactive-rpc
[redis-joy]: https://github.com/streamich/redis-joy
[sonic-forest]: https://github.com/streamich/sonic-forest
[spyfs]: https://github.com/streamich/spyfs
[thingies]: https://github.com/streamich/thingies
[tree-dump]: https://github.com/streamich/tree-dump
[tree-dump]: https://github.com/streamich/tree-dump
[unionfs]: https://github.com/streamich/unionfs
[use-media]: https://github.com/streamich/use-media
[use-t]: https://github.com/streamich/use-t
[rx-use]: https://github.com/streamich/rx-use
[very-small-parser]: https://github.com/streamich/very-small-parser


#### My Writings

- Specifications
  - `spec` [**JSON CRDT**][spec-json-crdt] &mdash; Full JSON implementation as a CRDT (Conflict-free Replicated Datatype).
  - `spec` [**JSON CRDT Patch**][spec-json-crdt-patch] &mdash; The patch format for JSON CRDT.
  - `spec` [**JSON Expression**][spec-json-expression] &mdash; s-expression specification for JSON.
  - `spec` [**JSON Reactive RPC**][spec-json-rx] &mdash; JSON Reactive RPC protocol (RPC with server push) implementation.
  - `encoding` [**Compact JSON**][spec-compact-json] &mdash; A compact *Tuple-Type-Value* (TTV) encoding for JSON.
- Blog posts
  - `blog` [_Fuzz Testing RGA CRDT_](https://jsonjoy.com/blog/fuzz-testing-rga-crdt)
  - `blog` [_Benchmarking JSON Serialization Codecs_](https://jsonjoy.com/blog/json-codec-benchmarks)
  - `blog` [_List CRDT Benchmarks_](https://jsonjoy.com/blog/list-crdt-benchmarks)
  - `blog` [_Blazing Fast List CRDT_](https://jsonjoy.com/blog/performant-rga-list-crdt-algorithm)
- My [random notes](https://onp4.com/@vadim)
  - `note` [Programming](https://onp4.com/@vadim/~programming)
  - `note` [JavaScript](https://onp4.com/@vadim/~js)
  - `note` [Collaborative editing](https://onp4.com/@vadim/~collaborative-editing)
  - `note` [Funny GitHub profiles](https://onp4.com/@vadim/~funny-github-profiles)

[spec-json-crdt]: https://jsonjoy.com/specs/json-crdt
[spec-json-crdt-patch]: https://jsonjoy.com/specs/json-crdt-patch
[spec-json-expression]: https://jsonjoy.com/specs/json-expression
[spec-json-rx]: https://jsonjoy.com/specs/json-rx
[spec-compact-json]: https://jsonjoy.com/specs/compact-json


---


#### Thank You

Your support means a lot to me and will help me to continue working on my projects!

[![streamich GitHub stats](https://github-readme-stats.vercel.app/api?username=streamich)](https://github.com/anuraghazra/github-readme-stats)

> **Support**
> - __[Become a sponsor](https://github.com/sponsors/streamich)__
> - __[Buy me a coffee](https://buymeacoffee.com/streamich)__ ☕️
> -  or send a Solana airdrop 🚀 🌘, SOL: `LJJwteDZjL8u2Uhh5giwVpRa5KcHLkDogYAZntYbMsD`
