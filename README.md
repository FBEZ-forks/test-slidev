# Slid-dev template comments

* Installing: why not using `brew install npm` or `sudo apt-get install npm`?
* Change favicon to devcon   
   * Put favicon.png in `/public``
   * add `favicon: /favicon.png` in front matter
   * wait random or put another image inside public

* Warning in `pnpm install`

```bash
➜  test-slidev git:(main) ✗ pnpm install
Packages: +641
++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++
Progress: resolved 684, reused 605, downloaded 36, added 641, done
 WARN  Issues with peer dependencies found
.
├─┬ slidev-addon-sync 0.1.0
│ └── ✕ unmet peer @slidev/client@^0.50.0-beta.3: found 51.8.2
└─┬ slidev-component-poll 3.0.0
  └── ✕ unmet peer @slidev/client@^0.50.0-beta.3: found 51.8.2

dependencies:
+ @slidev/cli 51.8.2 (52.0.0 is available)
+ @slidev/theme-default 0.25.0
+ @slidev/theme-seriph 0.25.0
+ slidev-addon-sync 0.1.0
+ slidev-component-poll 3.0.0
+ vue 3.5.17

╭ Warning ───────────────────────────────────────────────────────────────────────────────────╮
│                                                                                            │
│   Ignored build scripts: esbuild, vue-demi.                                                │
│   Run "pnpm approve-builds" to pick which dependencies should be allowed to run scripts.   │
│                                                                                            │
╰────────────────────────────────────────────────────────────────────────────────────────────╯

Done in 5.6s using pnpm v10.12.4
```

* Refresh needed when showing polling result
* Layout cheat sheet
* component cheatsheet 