> [!IMPORTANT]
> If you or __your company__ are using any of my projects or like what I'm doing, please consider backing me
> up. I appreciate it! 🙏 Your support will help me allocate more time to the open source work.
> 
> - __[Become a sponsor](https://github.com/sponsors/streamich)__
> - __[Buy me a coffee](https://buymeacoffee.com/streamich)__ ☕️
> -  or send a Solana airdrop 🚀 🌘, SOL: `LJJwteDZjL8u2Uhh5giwVpRa5KcHLkDogYAZntYbMsD`


My current focus is on developing CRDT and OT collaborative editing solutions,
local-first software, and Web3 apps. I maintain and contribute to OSS software,
below is a list of my latest projects and writings.

---


#### Projects

- UI and React
  - [`react-use`][react-use] and [`libreact`][libreact] &mdash; lots of React hooks and utility components.
  - [`nano-css`][nano-css] &mdash; the fastest and smallest CSS-in-JS library with plenty of plugins.
  - [`react-embed`][react-embed] &mdash; embed social widgets in your React app.
  - [`use-media`][use-media] &mdash; CSS media queries through React hook.
  - [`react-simple-player`][react-simple-player] &mdash; a minimalistic audio player React component.
  - `awesome-styleguides` &mdash; index of style guides and design systems.
  - `code-colors` & `code-colors-react` &mdash; code syntax highlighting libraries.
- Filesystem
  - [`memfs`][memfs] &mdash; a virtual filesystem for Node.js and browser, plus OPFS file system helpers.
  - [`unionfs`][unionfs] &mdash; creates a union of multiple filesystem volumes.
  - [`fs-monkey`][fs-monkey] &mdash; monkey-patches Node's `fs` module and `require` function.
  - [`linkfs`][linkfs] &mdash; redirects filesystem paths.
  - [`spyfs`][spyfs] &mdash; spies on filesystem actions.
- Collaborative editing
  - [`json-joy`](https://github.com/streamich/json-joy), a [JSON CRDT](https://jsonjoy.com/specs/json-crdt) implementation and collection of JSON awesomeness.
    - `json-joy/json-crdt` &mdash; The fastest list CRDT implementation in JavaScript.
    - `json-joy/json-patch` &mdash; Very fast JSON Patch (and JSON Pointer) implementation in JavaScript, including many non-standard operations, and JSON Predicate implementation.
    - `json-joy/json-type` &mdash; The fastest JSON schema validation implementation in JavaScript.
  - [`clickable-json`][clickable-json] &mdash; JSON viewer and editor with hoverable and clickable objects.
  - [`flexible-input`] &mdash; React `<input>` and `<textarea>` components which stretch to fit the content.
  - [`collaborative-input`][collaborative-input] &mdash; React `<input>` and `<textarea>` components with JSON CRDT real-time collaboration support.
- Data structures & utilities
  - [`git-cz`][git-cz] &mdash; `feat: 🎸 emoji-fied Git commits`
  - [`sonic-forest`][sonic-forest] &mdash; a very fast AVL, Splay, and Radix tree implementations in JavaScript.
  - [`tree-dump`][tree-dump] &mdash; utility to easily print tree-like structures.
  - [`thingies`][thingies] &mdash; a collection of useful TypeScript utilities.
  - `utils`
- Parsing
  - [`json-pack`][json-pack] &mdash; the fastest CBOR, MessagePack, RESP3, UBJSON, and JSON codecs in JavaScript.
  - [`jit-router`][jit-router] &mdash; the fastest HTTP router in JavaScript.
  - [`md-mdast`](https://github.com/streamich/md-mdast) &mdash; extremely small and fast Markdown to MDAST parser.
  - [`mdast-flat`](https://github.com/streamich/mdast-flat) &mdash; MDAST format to flat-MDAST converter.
  - `jit-parser` 🧪 `experimental` &mdash; PoC of LL recursive descent JIT parser with backtracking.
- Servers
  - Reactive RPC server
  - Redis ...


[react-use]: https://github.com/streamich/react-use
[libreact]: https://github.com/streamich/libreact
[nano-css]: https://github.com/streamich/nano-css
[react-embed]: https://github.com/streamich/react-embed
[react-simple-player]: https://github.com/streamich/react-simple-player
[use-media]: https://github.com/streamich/use-media
[memfs]: https://github.com/streamich/memfs
[unionfs]: https://github.com/streamich/unionfs
[fs-monkey]: https://github.com/streamich/fs-monkey
[linkfs]: https://github.com/streamich/linkfs
[spyfs]: https://github.com/streamich/spyfs
[git-cz]: https://github.com/streamich/git-cz
[sonic-forest]: https://github.com/streamich/sonic-forest
[tree-dump]: https://github.com/streamich/tree-dump
[thingies]: https://github.com/streamich/thingies
[tree-dump]: https://github.com/streamich/tree-dump
[json-pack]: https://github.com/jsonjoy-com/json-pack
[jit-router]: https://github.com/jsonjoy-com/jit-router
[clickable-json]: https://github.com/streamich/clickable-json
[flexible-input]: https://github.com/streamich/flexible-input
[collaborative-input]: https://github.com/streamich/collaborative-input


#### Writings

- **Specifications**
  - `specification` [**JSON CRDT**][spec-json-crdt] &mdash; Full JSON implementation as a CRDT (Conflict-free Replicated Datatype).
  - `specification` [**JSON CRDT Patch**][spec-json-crdt-patch] &mdash; The patch format for JSON CRDT.
  - `specification` [**JSON Expression**][spec-json-expression] &mdash; s-expression specification for JSON.
  - `specification` [**JSON Reactive RPC**][spec-json-rx] &mdash; JSON Reactive RPC protocol (RPC with server push) implementation, for real-time collaborative apps.
  - `encoding` [**Compact JSON**][spec-compact-json] &mdash; A compact Tuple-Type-Value (TTV) encoding for JSON.
- _Blog posts_
  - `blog` [_Fuzz Testing RGA CRDT_](https://jsonjoy.com/blog/fuzz-testing-rga-crdt)
  - `blog` [_Benchmarking JSON Serialization Codecs_](https://jsonjoy.com/blog/json-codec-benchmarks)
  - `blog` [_List CRDT Benchmarks_](https://jsonjoy.com/blog/list-crdt-benchmarks)
  - `blog` [_Blazing Fast List CRDT_](https://jsonjoy.com/blog/performant-rga-list-crdt-algorithm)
- My [Random notes](https://onp4.com/@vadim)
  - `notes` [Programming](https://onp4.com/@vadim/~programming)
  - `notes` [JavaScript](https://onp4.com/@vadim/~js)
  - `notes` [Collaborative editing](https://onp4.com/@vadim/~collaborative-editing)
  - `notes` [Funny GitHub profiles](https://onp4.com/@vadim/~funny-github-profiles)

[spec-json-crdt]: https://jsonjoy.com/specs/json-crdt
[spec-json-crdt-patch]: https://jsonjoy.com/specs/json-crdt-patch
[spec-json-expression]: https://jsonjoy.com/specs/json-expression
[spec-json-rx]: https://jsonjoy.com/specs/json-rx
[spec-compact-json]: https://jsonjoy.com/specs/compact-json


---


#### Thank You

Your support means a lot to me and will help me to continue working on my projects!

> **Give back**
> - __[Become a sponsor](https://github.com/sponsors/streamich)__
> - __[Buy me a coffee](https://buymeacoffee.com/streamich)__ ☕️
> -  or send a Solana airdrop 🚀 🌘, SOL: `LJJwteDZjL8u2Uhh5giwVpRa5KcHLkDogYAZntYbMsD`

[![streamich GitHub stats](https://github-readme-stats.vercel.app/api?username=streamich)](https://github.com/anuraghazra/github-readme-stats)
