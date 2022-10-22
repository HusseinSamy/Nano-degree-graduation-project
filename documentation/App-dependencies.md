## Front-end dependencies

```
+-- @angular-devkit/architect@0.12.4
| +-- @angular-devkit/core@7.2.4 deduped
| `-- rxjs@6.3.3
|   `-- tslib@1.10.0 deduped
+-- @angular-devkit/build-angular@0.803.24
| +-- @angular-devkit/architect@0.803.24
| | +-- @angular-devkit/core@8.3.24 deduped
| | `-- rxjs@6.4.0 deduped
| +-- @angular-devkit/build-optimizer@0.803.24
| | +-- loader-utils@1.2.3 deduped
| | +-- source-map@0.7.3 deduped
| | +-- tslib@1.10.0 deduped
| | +-- typescript@3.5.3 deduped
| | `-- webpack-sources@1.4.3 deduped
| +-- @angular-devkit/build-webpack@0.803.24
| | +-- @angular-devkit/architect@0.803.24
| | | +-- @angular-devkit/core@8.3.24 deduped
| | | `-- rxjs@6.4.0 deduped
| | +-- @angular-devkit/core@8.3.24
| | | +-- ajv@6.10.2
| | | | +-- fast-deep-equal@2.0.1 deduped
| | | | +-- fast-json-stable-stringify@2.0.0 deduped
| | | | +-- json-schema-traverse@0.4.1 deduped
| | | | `-- uri-js@4.2.2 deduped
| | | +-- fast-json-stable-stringify@2.0.0 deduped
| | | +-- magic-string@0.25.3 deduped
| | | +-- rxjs@6.4.0 deduped
| | | `-- source-map@0.7.3 deduped
| | `-- rxjs@6.4.0
| |   `-- tslib@1.10.0 deduped
| +-- @angular-devkit/core@8.3.24
| | +-- ajv@6.10.2 deduped
| | +-- fast-json-stable-stringify@2.0.0 deduped
| | +-- magic-string@0.25.3 deduped
| | +-- rxjs@6.4.0 deduped
| | `-- source-map@0.7.3 deduped
| +-- @babel/core@7.8.3
| | +-- @babel/code-frame@7.8.3
| | | `-- @babel/highlight@7.8.3
| | |   +-- chalk@2.4.2 deduped
| | |   +-- esutils@2.0.2 deduped
| | |   `-- js-tokens@4.0.0
| | +-- @babel/generator@7.8.4
| | | +-- @babel/types@7.8.3 deduped
| | | +-- jsesc@2.5.2
| | | +-- lodash@4.17.20 deduped
| | | `-- source-map@0.5.7 deduped
| | +-- @babel/helpers@7.8.4
| | | +-- @babel/template@7.8.3
| | | | +-- @babel/code-frame@7.8.3
| | | | | `-- @babel/highlight@7.8.3
| | | | |   +-- chalk@2.4.2 deduped
| | | | |   +-- esutils@2.0.2 deduped
| | | | |   `-- js-tokens@4.0.0
| | | | +-- @babel/parser@7.8.4
| | | | `-- @babel/types@7.8.3 deduped
| | | +-- @babel/traverse@7.8.4
| | | | +-- @babel/code-frame@7.8.3 deduped
| | | | +-- @babel/generator@7.8.4
| | | | | +-- @babel/types@7.8.3 deduped
| | | | | +-- jsesc@2.5.2 deduped
| | | | | +-- lodash@4.17.20 deduped
| | | | | `-- source-map@0.5.7
| | | | +-- @babel/helper-function-name@7.8.3
| | | | | +-- @babel/helper-get-function-arity@7.8.3
| | | | | | `-- @babel/types@7.8.3 deduped
| | | | | +-- @babel/template@7.8.3 deduped
| | | | | `-- @babel/types@7.8.3 deduped
| | | | +-- @babel/helper-split-export-declaration@7.8.3
| | | | | `-- @babel/types@7.8.3 deduped
| | | | +-- @babel/parser@7.8.4 deduped
| | | | +-- @babel/types@7.8.3 deduped
| | | | +-- debug@4.1.1
| | | | | `-- ms@2.1.2
| | | | +-- globals@11.12.0 deduped
| | | | `-- lodash@4.17.20 deduped
| | | `-- @babel/types@7.8.3
| | |   +-- esutils@2.0.2 deduped
| | |   +-- lodash@4.17.20 deduped
| | |   `-- to-fast-properties@2.0.0 deduped
| | +-- @babel/parser@7.8.4
| | +-- @babel/template@7.8.3
| | | +-- @babel/code-frame@7.8.3 deduped
| | | +-- @babel/parser@7.8.4 deduped
| | | `-- @babel/types@7.8.3 deduped
| | +-- @babel/traverse@7.8.4
| | | +-- @babel/code-frame@7.8.3 deduped
| | | +-- @babel/generator@7.8.4 deduped
| | | +-- @babel/helper-function-name@7.8.3
| | | | +-- @babel/helper-get-function-arity@7.8.3
| | | | | `-- @babel/types@7.8.3 deduped
| | | | +-- @babel/template@7.8.3 deduped
| | | | `-- @babel/types@7.8.3 deduped
| | | +-- @babel/helper-split-export-declaration@7.8.3
| | | | `-- @babel/types@7.8.3 deduped
| | | +-- @babel/parser@7.8.4 deduped
| | | +-- @babel/types@7.8.3 deduped
| | | +-- debug@4.1.1 deduped
| | | +-- globals@11.12.0
| | | `-- lodash@4.17.20 deduped
| | +-- @babel/types@7.8.3
| | | +-- esutils@2.0.2 deduped
| | | +-- lodash@4.17.20 deduped
| | | `-- to-fast-properties@2.0.0
| | +-- convert-source-map@1.7.0 deduped
| | +-- debug@4.1.1
| | | `-- ms@2.1.2
| | +-- gensync@1.0.0-beta.1
| | +-- json5@2.1.1
| | | `-- minimist@1.2.0 deduped
| | +-- lodash@4.17.20 deduped
| | +-- resolve@1.11.0 deduped
| | +-- semver@5.7.1
| | `-- source-map@0.5.7
| +-- @babel/preset-env@7.8.3
| | +-- @babel/compat-data@7.8.5
| | | +-- browserslist@4.8.6
| | | | +-- caniuse-lite@1.0.30001027
| | | | +-- electron-to-chromium@1.3.349 deduped
| | | | `-- node-releases@1.1.49 deduped
| | | +-- invariant@2.2.4 deduped
| | | `-- semver@5.7.1
| | +-- @babel/helper-compilation-targets@7.8.4
| | | +-- @babel/compat-data@7.8.5 deduped
| | | +-- browserslist@4.8.6
| | | | +-- caniuse-lite@1.0.30001027
| | | | +-- electron-to-chromium@1.3.349 deduped
| | | | `-- node-releases@1.1.49 deduped
| | | +-- invariant@2.2.4 deduped
| | | +-- levenary@1.1.1 deduped
| | | `-- semver@5.7.1
| | +-- @babel/helper-module-imports@7.8.3
| | | `-- @babel/types@7.8.3
| | |   +-- esutils@2.0.2 deduped
| | |   +-- lodash@4.17.20 deduped
| | |   `-- to-fast-properties@2.0.0 deduped
| | +-- @babel/helper-plugin-utils@7.8.3
| | +-- @babel/plugin-proposal-async-generator-functions@7.8.3
| | | +-- @babel/helper-plugin-utils@7.8.3 deduped
| | | +-- @babel/helper-remap-async-to-generator@7.8.3
| | | | +-- @babel/helper-annotate-as-pure@7.8.3 deduped
| | | | +-- @babel/helper-wrap-function@7.8.3
| | | | | +-- @babel/helper-function-name@7.8.3
| | | | | | +-- @babel/helper-get-function-arity@7.8.3
| | | | | | | `-- @babel/types@7.8.3 deduped
| | | | | | +-- @babel/template@7.8.3 deduped
| | | | | | `-- @babel/types@7.8.3 deduped
| | | | | +-- @babel/template@7.8.3
| | | | | | +-- @babel/code-frame@7.8.3
| | | | | | | `-- @babel/highlight@7.8.3
| | | | | | |   +-- chalk@2.4.2 deduped
| | | | | | |   +-- esutils@2.0.2 deduped
| | | | | | |   `-- js-tokens@4.0.0
| | | | | | +-- @babel/parser@7.8.4
| | | | | | `-- @babel/types@7.8.3 deduped
| | | | | +-- @babel/traverse@7.8.4
| | | | | | +-- @babel/code-frame@7.8.3 deduped
| | | | | | +-- @babel/generator@7.8.4
| | | | | | | +-- @babel/types@7.8.3 deduped
| | | | | | | +-- jsesc@2.5.2 deduped
| | | | | | | +-- lodash@4.17.20 deduped
| | | | | | | `-- source-map@0.5.7
| | | | | | +-- @babel/helper-function-name@7.8.3 deduped
| | | | | | +-- @babel/helper-split-export-declaration@7.8.3
| | | | | | | `-- @babel/types@7.8.3 deduped
| | | | | | +-- @babel/parser@7.8.4 deduped
| | | | | | +-- @babel/types@7.8.3 deduped
| | | | | | +-- debug@4.1.1
| | | | | | | `-- ms@2.1.2
| | | | | | +-- globals@11.12.0 deduped
| | | | | | `-- lodash@4.17.20 deduped
| | | | | `-- @babel/types@7.8.3
| | | | |   +-- esutils@2.0.2 deduped
| | | | |   +-- lodash@4.17.20 deduped
| | | | |   `-- to-fast-properties@2.0.0 deduped
| | | | +-- @babel/template@7.8.3
| | | | | +-- @babel/code-frame@7.8.3
| | | | | | `-- @babel/highlight@7.8.3
| | | | | |   +-- chalk@2.4.2 deduped
| | | | | |   +-- esutils@2.0.2 deduped
| | | | | |   `-- js-tokens@4.0.0
| | | | | +-- @babel/parser@7.8.4
| | | | | `-- @babel/types@7.8.3 deduped
| | | | +-- @babel/traverse@7.8.4
| | | | | +-- @babel/code-frame@7.8.3 deduped
| | | | | +-- @babel/generator@7.8.4
| | | | | | +-- @babel/types@7.8.3 deduped
| | | | | | +-- jsesc@2.5.2 deduped
| | | | | | +-- lodash@4.17.20 deduped
| | | | | | `-- source-map@0.5.7
| | | | | +-- @babel/helper-function-name@7.8.3
| | | | | | +-- @babel/helper-get-function-arity@7.8.3
| | | | | | | `-- @babel/types@7.8.3 deduped
| | | | | | +-- @babel/template@7.8.3 deduped
| | | | | | `-- @babel/types@7.8.3 deduped
| | | | | +-- @babel/helper-split-export-declaration@7.8.3
| | | | | | `-- @babel/types@7.8.3 deduped
| | | | | +-- @babel/parser@7.8.4 deduped
| | | | | +-- @babel/types@7.8.3 deduped
| | | | | +-- debug@4.1.1
| | | | | | `-- ms@2.1.2
| | | | | +-- globals@11.12.0 deduped
| | | | | `-- lodash@4.17.20 deduped
| | | | `-- @babel/types@7.8.3
| | | |   +-- esutils@2.0.2 deduped
| | | |   +-- lodash@4.17.20 deduped
| | | |   `-- to-fast-properties@2.0.0 deduped
| | | `-- @babel/plugin-syntax-async-generators@7.8.4 deduped
| | +-- @babel/plugin-proposal-dynamic-import@7.8.3
| | | +-- @babel/helper-plugin-utils@7.8.3 deduped
| | | `-- @babel/plugin-syntax-dynamic-import@7.8.3 deduped
| | +-- @babel/plugin-proposal-json-strings@7.8.3
| | | +-- @babel/helper-plugin-utils@7.8.3 deduped
| | | `-- @babel/plugin-syntax-json-strings@7.8.3 deduped
| | +-- @babel/plugin-proposal-nullish-coalescing-operator@7.8.3
| | | +-- @babel/helper-plugin-utils@7.8.3 deduped
| | | `-- @babel/plugin-syntax-nullish-coalescing-operator@7.8.3 deduped
| | +-- @babel/plugin-proposal-object-rest-spread@7.8.3
| | | +-- @babel/helper-plugin-utils@7.8.3 deduped
| | | `-- @babel/plugin-syntax-object-rest-spread@7.8.3 deduped
| | +-- @babel/plugin-proposal-optional-catch-binding@7.8.3
| | | +-- @babel/helper-plugin-utils@7.8.3 deduped
| | | `-- @babel/plugin-syntax-optional-catch-binding@7.8.3 deduped
| | +-- @babel/plugin-proposal-optional-chaining@7.8.3
| | | +-- @babel/helper-plugin-utils@7.8.3 deduped
| | | `-- @babel/plugin-syntax-optional-chaining@7.8.3 deduped
| | +-- @babel/plugin-proposal-unicode-property-regex@7.8.3
| | | +-- @babel/helper-create-regexp-features-plugin@7.8.3
| | | | +-- @babel/helper-regex@7.8.3 deduped
| | | | `-- regexpu-core@4.6.0
| | | |   +-- regenerate@1.4.0 deduped
| | | |   +-- regenerate-unicode-properties@8.1.0
| | | |   | `-- regenerate@1.4.0 deduped
| | | |   +-- regjsgen@0.5.1
| | | |   +-- regjsparser@0.6.2
| | | |   | `-- jsesc@0.5.0
| | | |   +-- unicode-match-property-ecmascript@1.0.4
| | | |   | +-- unicode-canonical-property-names-ecmascript@1.0.4
| | | |   | `-- unicode-property-aliases-ecmascript@1.0.5
| | | |   `-- unicode-match-property-value-ecmascript@1.1.0
| | | `-- @babel/helper-plugin-utils@7.8.3 deduped
| | +-- @babel/plugin-syntax-async-generators@7.8.4
| | | `-- @babel/helper-plugin-utils@7.8.3 deduped
| | +-- @babel/plugin-syntax-dynamic-import@7.8.3
| | | `-- @babel/helper-plugin-utils@7.8.3 deduped
| | +-- @babel/plugin-syntax-json-strings@7.8.3
| | | `-- @babel/helper-plugin-utils@7.8.3 deduped
| | +-- @babel/plugin-syntax-nullish-coalescing-operator@7.8.3
| | | `-- @babel/helper-plugin-utils@7.8.3 deduped
| | +-- @babel/plugin-syntax-object-rest-spread@7.8.3
| | | `-- @babel/helper-plugin-utils@7.8.3 deduped
| | +-- @babel/plugin-syntax-optional-catch-binding@7.8.3
| | | `-- @babel/helper-plugin-utils@7.8.3 deduped
| | +-- @babel/plugin-syntax-optional-chaining@7.8.3
| | | `-- @babel/helper-plugin-utils@7.8.3 deduped
| | +-- @babel/plugin-syntax-top-level-await@7.8.3
| | | `-- @babel/helper-plugin-utils@7.8.3 deduped
| | +-- @babel/plugin-transform-arrow-functions@7.8.3
| | | `-- @babel/helper-plugin-utils@7.8.3 deduped
| | +-- @babel/plugin-transform-async-to-generator@7.8.3
| | | +-- @babel/helper-module-imports@7.8.3 deduped
| | | +-- @babel/helper-plugin-utils@7.8.3 deduped
| | | `-- @babel/helper-remap-async-to-generator@7.8.3 deduped
| | +-- @babel/plugin-transform-block-scoped-functions@7.8.3
| | | `-- @babel/helper-plugin-utils@7.8.3 deduped
| | +-- @babel/plugin-transform-block-scoping@7.8.3
| | | +-- @babel/helper-plugin-utils@7.8.3 deduped
| | | `-- lodash@4.17.20 deduped
| | +-- @babel/plugin-transform-classes@7.8.3
| | | +-- @babel/helper-annotate-as-pure@7.8.3
| | | | `-- @babel/types@7.8.3
| | | |   +-- esutils@2.0.2 deduped
| | | |   +-- lodash@4.17.20 deduped
| | | |   `-- to-fast-properties@2.0.0 deduped
| | | +-- @babel/helper-define-map@7.8.3
| | | | +-- @babel/helper-function-name@7.8.3
| | | | | +-- @babel/helper-get-function-arity@7.8.3
| | | | | | `-- @babel/types@7.8.3 deduped
| | | | | +-- @babel/template@7.8.3
| | | | | | +-- @babel/code-frame@7.8.3
| | | | | | | `-- @babel/highlight@7.8.3
| | | | | | |   +-- chalk@2.4.2 deduped
| | | | | | |   +-- esutils@2.0.2 deduped
| | | | | | |   `-- js-tokens@4.0.0
| | | | | | +-- @babel/parser@7.8.4
| | | | | | `-- @babel/types@7.8.3 deduped
| | | | | `-- @babel/types@7.8.3 deduped
| | | | +-- @babel/types@7.8.3
| | | | | +-- esutils@2.0.2 deduped
| | | | | +-- lodash@4.17.20 deduped
| | | | | `-- to-fast-properties@2.0.0 deduped
| | | | `-- lodash@4.17.20 deduped
| | | +-- @babel/helper-function-name@7.8.3
| | | | +-- @babel/helper-get-function-arity@7.8.3
| | | | | `-- @babel/types@7.8.3 deduped
| | | | +-- @babel/template@7.8.3
| | | | | +-- @babel/code-frame@7.8.3
| | | | | | `-- @babel/highlight@7.8.3
| | | | | |   +-- chalk@2.4.2 deduped
| | | | | |   +-- esutils@2.0.2 deduped
| | | | | |   `-- js-tokens@4.0.0
| | | | | +-- @babel/parser@7.8.4
| | | | | `-- @babel/types@7.8.3 deduped
| | | | `-- @babel/types@7.8.3
| | | |   +-- esutils@2.0.2 deduped
| | | |   +-- lodash@4.17.20 deduped
| | | |   `-- to-fast-properties@2.0.0 deduped
| | | +-- @babel/helper-optimise-call-expression@7.8.3
| | | | `-- @babel/types@7.8.3
| | | |   +-- esutils@2.0.2 deduped
| | | |   +-- lodash@4.17.20 deduped
| | | |   `-- to-fast-properties@2.0.0 deduped
| | | +-- @babel/helper-plugin-utils@7.8.3 deduped
| | | +-- @babel/helper-replace-supers@7.8.3
| | | | +-- @babel/helper-member-expression-to-functions@7.8.3
| | | | | `-- @babel/types@7.8.3
| | | | |   +-- esutils@2.0.2 deduped
| | | | |   +-- lodash@4.17.20 deduped
| | | | |   `-- to-fast-properties@2.0.0 deduped
| | | | +-- @babel/helper-optimise-call-expression@7.8.3 deduped
| | | | +-- @babel/traverse@7.8.4
| | | | | +-- @babel/code-frame@7.8.3
| | | | | | `-- @babel/highlight@7.8.3
| | | | | |   +-- chalk@2.4.2 deduped
| | | | | |   +-- esutils@2.0.2 deduped
| | | | | |   `-- js-tokens@4.0.0
| | | | | +-- @babel/generator@7.8.4
| | | | | | +-- @babel/types@7.8.3 deduped
| | | | | | +-- jsesc@2.5.2 deduped
| | | | | | +-- lodash@4.17.20 deduped
| | | | | | `-- source-map@0.5.7
| | | | | +-- @babel/helper-function-name@7.8.3
| | | | | | +-- @babel/helper-get-function-arity@7.8.3
| | | | | | | `-- @babel/types@7.8.3 deduped
| | | | | | +-- @babel/template@7.8.3
| | | | | | | +-- @babel/code-frame@7.8.3 deduped
| | | | | | | +-- @babel/parser@7.8.4 deduped
| | | | | | | `-- @babel/types@7.8.3 deduped
| | | | | | `-- @babel/types@7.8.3 deduped
| | | | | +-- @babel/helper-split-export-declaration@7.8.3
| | | | | | `-- @babel/types@7.8.3 deduped
| | | | | +-- @babel/parser@7.8.4
| | | | | +-- @babel/types@7.8.3 deduped
| | | | | +-- debug@4.1.1
| | | | | | `-- ms@2.1.2
| | | | | +-- globals@11.12.0 deduped
| | | | | `-- lodash@4.17.20 deduped
| | | | `-- @babel/types@7.8.3
| | | |   +-- esutils@2.0.2 deduped
| | | |   +-- lodash@4.17.20 deduped
| | | |   `-- to-fast-properties@2.0.0 deduped
| | | +-- @babel/helper-split-export-declaration@7.8.3
| | | | `-- @babel/types@7.8.3 deduped
| | | `-- globals@11.12.0 deduped
| | +-- @babel/plugin-transform-computed-properties@7.8.3
| | | `-- @babel/helper-plugin-utils@7.8.3 deduped
| | +-- @babel/plugin-transform-destructuring@7.8.3
| | | `-- @babel/helper-plugin-utils@7.8.3 deduped
| | +-- @babel/plugin-transform-dotall-regex@7.8.3
| | | +-- @babel/helper-create-regexp-features-plugin@7.8.3 deduped
| | | `-- @babel/helper-plugin-utils@7.8.3 deduped
| | +-- @babel/plugin-transform-duplicate-keys@7.8.3
| | | `-- @babel/helper-plugin-utils@7.8.3 deduped
| | +-- @babel/plugin-transform-exponentiation-operator@7.8.3
| | | +-- @babel/helper-builder-binary-assignment-operator-visitor@7.8.3
| | | | +-- @babel/helper-explode-assignable-expression@7.8.3
| | | | | +-- @babel/traverse@7.8.4
| | | | | | +-- @babel/code-frame@7.8.3
| | | | | | | `-- @babel/highlight@7.8.3
| | | | | | |   +-- chalk@2.4.2 deduped
| | | | | | |   +-- esutils@2.0.2 deduped
| | | | | | |   `-- js-tokens@4.0.0
| | | | | | +-- @babel/generator@7.8.4
| | | | | | | +-- @babel/types@7.8.3 deduped
| | | | | | | +-- jsesc@2.5.2 deduped
| | | | | | | +-- lodash@4.17.20 deduped
| | | | | | | `-- source-map@0.5.7
| | | | | | +-- @babel/helper-function-name@7.8.3
| | | | | | | +-- @babel/helper-get-function-arity@7.8.3
| | | | | | | | `-- @babel/types@7.8.3 deduped
| | | | | | | +-- @babel/template@7.8.3
| | | | | | | | +-- @babel/code-frame@7.8.3 deduped
| | | | | | | | +-- @babel/parser@7.8.4 deduped
| | | | | | | | `-- @babel/types@7.8.3 deduped
| | | | | | | `-- @babel/types@7.8.3 deduped
| | | | | | +-- @babel/helper-split-export-declaration@7.8.3
| | | | | | | `-- @babel/types@7.8.3 deduped
| | | | | | +-- @babel/parser@7.8.4
| | | | | | +-- @babel/types@7.8.3 deduped
| | | | | | +-- debug@4.1.1
| | | | | | | `-- ms@2.1.2
| | | | | | +-- globals@11.12.0 deduped
| | | | | | `-- lodash@4.17.20 deduped
| | | | | `-- @babel/types@7.8.3
| | | | |   +-- esutils@2.0.2 deduped
| | | | |   +-- lodash@4.17.20 deduped
| | | | |   `-- to-fast-properties@2.0.0 deduped
| | | | `-- @babel/types@7.8.3
| | | |   +-- esutils@2.0.2 deduped
| | | |   +-- lodash@4.17.20 deduped
| | | |   `-- to-fast-properties@2.0.0 deduped
| | | `-- @babel/helper-plugin-utils@7.8.3 deduped
| | +-- @babel/plugin-transform-for-of@7.8.4
| | | `-- @babel/helper-plugin-utils@7.8.3 deduped
| | +-- @babel/plugin-transform-function-name@7.8.3
| | | +-- @babel/helper-function-name@7.8.3
| | | | +-- @babel/helper-get-function-arity@7.8.3
| | | | | `-- @babel/types@7.8.3 deduped
| | | | +-- @babel/template@7.8.3
| | | | | +-- @babel/code-frame@7.8.3
| | | | | | `-- @babel/highlight@7.8.3
| | | | | |   +-- chalk@2.4.2 deduped
| | | | | |   +-- esutils@2.0.2 deduped
| | | | | |   `-- js-tokens@4.0.0
| | | | | +-- @babel/parser@7.8.4
| | | | | `-- @babel/types@7.8.3 deduped
| | | | `-- @babel/types@7.8.3
| | | |   +-- esutils@2.0.2 deduped
| | | |   +-- lodash@4.17.20 deduped
| | | |   `-- to-fast-properties@2.0.0 deduped
| | | `-- @babel/helper-plugin-utils@7.8.3 deduped
| | +-- @babel/plugin-transform-literals@7.8.3
| | | `-- @babel/helper-plugin-utils@7.8.3 deduped
| | +-- @babel/plugin-transform-member-expression-literals@7.8.3
| | | `-- @babel/helper-plugin-utils@7.8.3 deduped
| | +-- @babel/plugin-transform-modules-amd@7.8.3
| | | +-- @babel/helper-module-transforms@7.8.3
| | | | +-- @babel/helper-module-imports@7.8.3 deduped
| | | | +-- @babel/helper-simple-access@7.8.3 deduped
| | | | +-- @babel/helper-split-export-declaration@7.8.3
| | | | | `-- @babel/types@7.8.3 deduped
| | | | +-- @babel/template@7.8.3
| | | | | +-- @babel/code-frame@7.8.3
| | | | | | `-- @babel/highlight@7.8.3
| | | | | |   +-- chalk@2.4.2 deduped
| | | | | |   +-- esutils@2.0.2 deduped
| | | | | |   `-- js-tokens@4.0.0
| | | | | +-- @babel/parser@7.8.4
| | | | | `-- @babel/types@7.8.3 deduped
| | | | +-- @babel/types@7.8.3
| | | | | +-- esutils@2.0.2 deduped
| | | | | +-- lodash@4.17.20 deduped
| | | | | `-- to-fast-properties@2.0.0 deduped
| | | | `-- lodash@4.17.20 deduped
| | | +-- @babel/helper-plugin-utils@7.8.3 deduped
| | | `-- babel-plugin-dynamic-import-node@2.3.0
| | |   `-- object.assign@4.1.0
| | |     +-- define-properties@1.1.3 deduped
| | |     +-- function-bind@1.1.1
| | |     +-- has-symbols@1.0.1
| | |     `-- object-keys@1.1.1 deduped
| | +-- @babel/plugin-transform-modules-commonjs@7.8.3
| | | +-- @babel/helper-module-transforms@7.8.3 deduped
| | | +-- @babel/helper-plugin-utils@7.8.3 deduped
| | | +-- @babel/helper-simple-access@7.8.3
| | | | +-- @babel/template@7.8.3
| | | | | +-- @babel/code-frame@7.8.3
| | | | | | `-- @babel/highlight@7.8.3
| | | | | |   +-- chalk@2.4.2 deduped
| | | | | |   +-- esutils@2.0.2 deduped
| | | | | |   `-- js-tokens@4.0.0
| | | | | +-- @babel/parser@7.8.4
| | | | | `-- @babel/types@7.8.3 deduped
| | | | `-- @babel/types@7.8.3
| | | |   +-- esutils@2.0.2 deduped
| | | |   +-- lodash@4.17.20 deduped
| | | |   `-- to-fast-properties@2.0.0 deduped
| | | `-- babel-plugin-dynamic-import-node@2.3.0 deduped
| | +-- @babel/plugin-transform-modules-systemjs@7.8.3
| | | +-- @babel/helper-hoist-variables@7.8.3
| | | | `-- @babel/types@7.8.3
| | | |   +-- esutils@2.0.2 deduped
| | | |   +-- lodash@4.17.20 deduped
| | | |   `-- to-fast-properties@2.0.0 deduped
| | | +-- @babel/helper-module-transforms@7.8.3 deduped
| | | +-- @babel/helper-plugin-utils@7.8.3 deduped
| | | `-- babel-plugin-dynamic-import-node@2.3.0 deduped
| | +-- @babel/plugin-transform-modules-umd@7.8.3
| | | +-- @babel/helper-module-transforms@7.8.3 deduped
| | | `-- @babel/helper-plugin-utils@7.8.3 deduped
| | +-- @babel/plugin-transform-named-capturing-groups-regex@7.8.3
| | | `-- @babel/helper-create-regexp-features-plugin@7.8.3 deduped
| | +-- @babel/plugin-transform-new-target@7.8.3
| | | `-- @babel/helper-plugin-utils@7.8.3 deduped
| | +-- @babel/plugin-transform-object-super@7.8.3
| | | +-- @babel/helper-plugin-utils@7.8.3 deduped
| | | `-- @babel/helper-replace-supers@7.8.3 deduped
| | +-- @babel/plugin-transform-parameters@7.8.4
| | | +-- @babel/helper-call-delegate@7.8.3
| | | | +-- @babel/helper-hoist-variables@7.8.3 deduped
| | | | +-- @babel/traverse@7.8.4
| | | | | +-- @babel/code-frame@7.8.3
| | | | | | `-- @babel/highlight@7.8.3
| | | | | |   +-- chalk@2.4.2 deduped
| | | | | |   +-- esutils@2.0.2 deduped
| | | | | |   `-- js-tokens@4.0.0
| | | | | +-- @babel/generator@7.8.4
| | | | | | +-- @babel/types@7.8.3 deduped
| | | | | | +-- jsesc@2.5.2 deduped
| | | | | | +-- lodash@4.17.20 deduped
| | | | | | `-- source-map@0.5.7
| | | | | +-- @babel/helper-function-name@7.8.3
| | | | | | +-- @babel/helper-get-function-arity@7.8.3
| | | | | | | `-- @babel/types@7.8.3 deduped
| | | | | | +-- @babel/template@7.8.3
| | | | | | | +-- @babel/code-frame@7.8.3 deduped
| | | | | | | +-- @babel/parser@7.8.4 deduped
| | | | | | | `-- @babel/types@7.8.3 deduped
| | | | | | `-- @babel/types@7.8.3 deduped
| | | | | +-- @babel/helper-split-export-declaration@7.8.3
| | | | | | `-- @babel/types@7.8.3 deduped
| | | | | +-- @babel/parser@7.8.4
| | | | | +-- @babel/types@7.8.3 deduped
| | | | | +-- debug@4.1.1
| | | | | | `-- ms@2.1.2
| | | | | +-- globals@11.12.0 deduped
| | | | | `-- lodash@4.17.20 deduped
| | | | `-- @babel/types@7.8.3
| | | |   +-- esutils@2.0.2 deduped
| | | |   +-- lodash@4.17.20 deduped
| | | |   `-- to-fast-properties@2.0.0 deduped
| | | +-- @babel/helper-get-function-arity@7.8.3
| | | | `-- @babel/types@7.8.3
| | | |   +-- esutils@2.0.2 deduped
| | | |   +-- lodash@4.17.20 deduped
| | | |   `-- to-fast-properties@2.0.0 deduped
| | | `-- @babel/helper-plugin-utils@7.8.3 deduped
| | +-- @babel/plugin-transform-property-literals@7.8.3
| | | `-- @babel/helper-plugin-utils@7.8.3 deduped
| | +-- @babel/plugin-transform-regenerator@7.8.3
| | | `-- regenerator-transform@0.14.1
| | |   `-- private@0.1.8
| | +-- @babel/plugin-transform-reserved-words@7.8.3
| | | `-- @babel/helper-plugin-utils@7.8.3 deduped
| | +-- @babel/plugin-transform-shorthand-properties@7.8.3
| | | `-- @babel/helper-plugin-utils@7.8.3 deduped
| | +-- @babel/plugin-transform-spread@7.8.3
| | | `-- @babel/helper-plugin-utils@7.8.3 deduped
| | +-- @babel/plugin-transform-sticky-regex@7.8.3
| | | +-- @babel/helper-plugin-utils@7.8.3 deduped
| | | `-- @babel/helper-regex@7.8.3
| | |   `-- lodash@4.17.20 deduped
| | +-- @babel/plugin-transform-template-literals@7.8.3
| | | +-- @babel/helper-annotate-as-pure@7.8.3 deduped
| | | `-- @babel/helper-plugin-utils@7.8.3 deduped
| | +-- @babel/plugin-transform-typeof-symbol@7.8.4
| | | `-- @babel/helper-plugin-utils@7.8.3 deduped
| | +-- @babel/plugin-transform-unicode-regex@7.8.3
| | | +-- @babel/helper-create-regexp-features-plugin@7.8.3 deduped
| | | `-- @babel/helper-plugin-utils@7.8.3 deduped
| | +-- @babel/types@7.8.3
| | | +-- esutils@2.0.2 deduped
| | | +-- lodash@4.17.20 deduped
| | | `-- to-fast-properties@2.0.0 deduped
| | +-- browserslist@4.8.3 deduped
| | +-- core-js-compat@3.6.4
| | | +-- browserslist@4.8.3 deduped
| | | `-- semver@7.0.0
| | +-- invariant@2.2.4
| | | `-- loose-envify@1.4.0
| | |   `-- js-tokens@3.0.2 deduped
| | +-- levenary@1.1.1
| | | `-- leven@3.1.0
| | `-- semver@5.7.1
| +-- @ngtools/webpack@8.3.24
| | +-- @angular-devkit/core@8.3.24
| | | +-- ajv@6.10.2
| | | | +-- fast-deep-equal@2.0.1 deduped
| | | | +-- fast-json-stable-stringify@2.0.0 deduped
| | | | +-- json-schema-traverse@0.4.1 deduped
| | | | `-- uri-js@4.2.2 deduped
| | | +-- fast-json-stable-stringify@2.0.0 deduped
| | | +-- magic-string@0.25.3 deduped
| | | +-- rxjs@6.4.0 deduped
| | | `-- source-map@0.7.3 deduped
| | +-- enhanced-resolve@4.1.0
| | | +-- graceful-fs@4.1.15 deduped
| | | +-- memory-fs@0.4.1 deduped
| | | `-- tapable@1.1.3 deduped
| | +-- rxjs@6.4.0
| | | `-- tslib@1.10.0 deduped
| | +-- tree-kill@1.2.2 deduped
| | `-- webpack-sources@1.4.3 deduped
| +-- ajv@6.10.2
| | +-- fast-deep-equal@2.0.1
| | +-- fast-json-stable-stringify@2.0.0 deduped
| | +-- json-schema-traverse@0.4.1
| | `-- uri-js@4.2.2
| |   `-- punycode@2.1.1
| +-- autoprefixer@9.6.1
| | +-- browserslist@4.8.3 deduped
| | +-- caniuse-lite@1.0.30001019 deduped
| | +-- chalk@2.4.2 deduped
| | +-- normalize-range@0.1.2
| | +-- num2fraction@1.2.2
| | +-- postcss@7.0.17 deduped
| | `-- postcss-value-parser@4.0.2
| +-- browserslist@4.8.3
| | +-- caniuse-lite@1.0.30001019 deduped
| | +-- electron-to-chromium@1.3.349
| | `-- node-releases@1.1.49
| |   `-- semver@6.3.0
| +-- cacache@12.0.2
| | +-- bluebird@3.5.5 deduped
| | +-- chownr@1.1.1
| | +-- figgy-pudding@3.5.1
| | +-- glob@7.1.4 deduped
| | +-- graceful-fs@4.1.15 deduped
| | +-- infer-owner@1.0.4
| | +-- lru-cache@5.1.1
| | | `-- yallist@3.0.3
| | +-- mississippi@3.0.0
| | | +-- concat-stream@1.6.2
| | | | +-- buffer-from@1.1.1 deduped
| | | | +-- inherits@2.0.3 deduped
| | | | +-- readable-stream@2.3.6 deduped
| | | | `-- typedarray@0.0.6
| | | +-- duplexify@3.7.1
| | | | +-- end-of-stream@1.4.1 deduped
| | | | +-- inherits@2.0.3 deduped
| | | | +-- readable-stream@2.3.6 deduped
| | | | `-- stream-shift@1.0.0
| | | +-- end-of-stream@1.4.1
| | | | `-- once@1.4.0 deduped
| | | +-- flush-write-stream@1.1.1
| | | | +-- inherits@2.0.3 deduped
| | | | `-- readable-stream@2.3.6 deduped
| | | +-- from2@2.3.0
| | | | +-- inherits@2.0.3 deduped
| | | | `-- readable-stream@2.3.6 deduped
| | | +-- parallel-transform@1.1.0
| | | | +-- cyclist@0.2.2
| | | | +-- inherits@2.0.3 deduped
| | | | `-- readable-stream@2.3.6 deduped
| | | +-- pump@3.0.0
| | | | +-- end-of-stream@1.4.1 deduped
| | | | `-- once@1.4.0 deduped
| | | +-- pumpify@1.5.1
| | | | +-- duplexify@3.7.1 deduped
| | | | +-- inherits@2.0.3 deduped
| | | | `-- pump@2.0.1
| | | |   +-- end-of-stream@1.4.1 deduped
| | | |   `-- once@1.4.0 deduped
| | | +-- stream-each@1.2.3
| | | | +-- end-of-stream@1.4.1 deduped
| | | | `-- stream-shift@1.0.0 deduped
| | | `-- through2@2.0.5
| | |   +-- readable-stream@2.3.6 deduped
| | |   `-- xtend@4.0.1
| | +-- mkdirp@0.5.1
| | | `-- minimist@0.0.8
| | +-- move-concurrently@1.0.1
| | | +-- aproba@1.2.0
| | | +-- copy-concurrently@1.0.5
| | | | +-- aproba@1.2.0 deduped
| | | | +-- fs-write-stream-atomic@1.0.10 deduped
| | | | +-- iferr@0.1.5
| | | | +-- mkdirp@0.5.1 deduped
| | | | +-- rimraf@2.6.3 deduped
| | | | `-- run-queue@1.0.3 deduped
| | | +-- fs-write-stream-atomic@1.0.10
| | | | +-- graceful-fs@4.1.15 deduped
| | | | +-- iferr@0.1.5 deduped
| | | | +-- imurmurhash@0.1.4
| | | | `-- readable-stream@2.3.6 deduped
| | | +-- mkdirp@0.5.1 deduped
| | | +-- rimraf@2.6.3 deduped
| | | `-- run-queue@1.0.3
| | |   `-- aproba@1.2.0 deduped
| | +-- promise-inflight@1.0.1
| | +-- rimraf@2.6.3 deduped
| | +-- ssri@6.0.1
| | | `-- figgy-pudding@3.5.1 deduped
| | +-- unique-filename@1.1.1
| | | `-- unique-slug@2.0.2
| | |   `-- imurmurhash@0.1.4 deduped
| | `-- y18n@4.0.0
| +-- caniuse-lite@1.0.30001019
| +-- circular-dependency-plugin@5.2.0
| +-- clean-css@4.2.1
| | `-- source-map@0.6.1
| +-- copy-webpack-plugin@5.1.1
| | +-- cacache@12.0.3
| | | +-- bluebird@3.5.5 deduped
| | | +-- chownr@1.1.1 deduped
| | | +-- figgy-pudding@3.5.1 deduped
| | | +-- glob@7.1.6
| | | | +-- fs.realpath@1.0.0 deduped
| | | | +-- inflight@1.0.6 deduped
| | | | +-- inherits@2.0.3 deduped
| | | | +-- minimatch@3.0.4 deduped
| | | | +-- once@1.4.0 deduped
| | | | `-- path-is-absolute@1.0.1 deduped
| | | +-- graceful-fs@4.1.15 deduped
| | | +-- infer-owner@1.0.4 deduped
| | | +-- lru-cache@5.1.1 deduped
| | | +-- mississippi@3.0.0 deduped
| | | +-- mkdirp@0.5.1 deduped
| | | +-- move-concurrently@1.0.1 deduped
| | | +-- promise-inflight@1.0.1 deduped
| | | +-- rimraf@2.6.3 deduped
| | | +-- ssri@6.0.1 deduped
| | | +-- unique-filename@1.1.1 deduped
| | | `-- y18n@4.0.0 deduped
| | +-- find-cache-dir@2.1.0
| | | +-- commondir@1.0.1 deduped
| | | +-- make-dir@2.1.0 deduped
| | | `-- pkg-dir@3.0.0
| | |   `-- find-up@3.0.0 deduped
| | +-- glob-parent@3.1.0
| | | +-- is-glob@3.1.0
| | | | `-- is-extglob@2.1.1 deduped
| | | `-- path-dirname@1.0.2
| | +-- globby@7.1.1
| | | +-- array-union@1.0.2
| | | | `-- array-uniq@1.0.3
| | | +-- dir-glob@2.2.2
| | | | `-- path-type@3.0.0
| | | |   `-- pify@3.0.0
| | | +-- glob@7.1.3 deduped
| | | +-- ignore@3.3.10
| | | +-- pify@3.0.0
| | | `-- slash@1.0.0
| | +-- is-glob@4.0.1
| | | `-- is-extglob@2.1.1
| | +-- loader-utils@1.2.3 deduped
| | +-- minimatch@3.0.4 deduped
| | +-- normalize-path@3.0.0
| | +-- p-limit@2.2.2
| | | `-- p-try@2.2.0
| | +-- schema-utils@1.0.0
| | | +-- UNMET PEER DEPENDENCY ajv@6.6.2 deduped
| | | +-- ajv-errors@1.0.1
| | | `-- ajv-keywords@3.4.1 deduped
| | +-- serialize-javascript@2.1.2
| | `-- webpack-log@2.0.0
| |   +-- ansi-colors@3.2.4
| |   `-- uuid@3.3.2 deduped
| +-- core-js@3.6.4
| +-- coverage-istanbul-loader@2.0.3
| | +-- convert-source-map@1.7.0 deduped
| | +-- istanbul-lib-instrument@4.0.1
| | | +-- @babel/core@7.8.3 deduped
| | | +-- @babel/parser@7.8.4
| | | +-- @babel/template@7.8.3
| | | | +-- @babel/code-frame@7.8.3
| | | | | `-- @babel/highlight@7.8.3
| | | | |   +-- chalk@2.4.2 deduped
| | | | |   +-- esutils@2.0.2 deduped
| | | | |   `-- js-tokens@4.0.0
| | | | +-- @babel/parser@7.8.4 deduped
| | | | `-- @babel/types@7.8.3
| | | |   +-- esutils@2.0.2 deduped
| | | |   +-- lodash@4.17.20 deduped
| | | |   `-- to-fast-properties@2.0.0 deduped
| | | +-- @babel/traverse@7.8.4
| | | | +-- @babel/code-frame@7.8.3 deduped
| | | | +-- @babel/generator@7.8.4
| | | | | +-- @babel/types@7.8.3 deduped
| | | | | +-- jsesc@2.5.2 deduped
| | | | | +-- lodash@4.17.20 deduped
| | | | | `-- source-map@0.5.7
| | | | +-- @babel/helper-function-name@7.8.3
| | | | | +-- @babel/helper-get-function-arity@7.8.3
| | | | | | `-- @babel/types@7.8.3 deduped
| | | | | +-- @babel/template@7.8.3 deduped
| | | | | `-- @babel/types@7.8.3 deduped
| | | | +-- @babel/helper-split-export-declaration@7.8.3
| | | | | `-- @babel/types@7.8.3 deduped
| | | | +-- @babel/parser@7.8.4 deduped
| | | | +-- @babel/types@7.8.3 deduped
| | | | +-- debug@4.1.1
| | | | | `-- ms@2.1.2
| | | | +-- globals@11.12.0 deduped
| | | | `-- lodash@4.17.20 deduped
| | | +-- @istanbuljs/schema@0.1.2
| | | +-- istanbul-lib-coverage@3.0.0
| | | `-- semver@6.3.0
| | +-- loader-utils@1.2.3 deduped
| | +-- merge-source-map@1.1.0
| | | `-- source-map@0.6.1
| | `-- schema-utils@2.6.4
| |   +-- UNMET PEER DEPENDENCY ajv@6.11.0
| |   | +-- fast-deep-equal@3.1.1
| |   | +-- fast-json-stable-stringify@2.0.0 deduped
| |   | +-- json-schema-traverse@0.4.1 deduped
| |   | `-- uri-js@4.2.2 deduped
| |   `-- ajv-keywords@3.4.1 deduped
| +-- file-loader@4.2.0
| | +-- loader-utils@1.2.3 deduped
| | `-- schema-utils@2.6.4
| |   +-- UNMET PEER DEPENDENCY ajv@6.11.0
| |   | +-- fast-deep-equal@3.1.1
| |   | +-- fast-json-stable-stringify@2.0.0 deduped
| |   | +-- json-schema-traverse@0.4.1 deduped
| |   | `-- uri-js@4.2.2 deduped
| |   `-- ajv-keywords@3.4.1 deduped
| +-- find-cache-dir@3.0.0
| | +-- commondir@1.0.1
| | +-- make-dir@3.0.2
| | | `-- semver@6.0.0
| | `-- pkg-dir@4.2.0
| |   `-- find-up@4.1.0
| |     +-- locate-path@5.0.0
| |     | `-- p-locate@4.1.0
| |     |   `-- p-limit@2.2.2 deduped
| |     `-- path-exists@4.0.0
| +-- glob@7.1.4
| | +-- fs.realpath@1.0.0
| | +-- inflight@1.0.6
| | | +-- once@1.4.0 deduped
| | | `-- wrappy@1.0.2
| | +-- inherits@2.0.3
| | +-- minimatch@3.0.4 deduped
| | +-- once@1.4.0
| | | `-- wrappy@1.0.2 deduped
| | `-- path-is-absolute@1.0.1
| +-- jest-worker@24.9.0
| | +-- merge-stream@2.0.0
| | `-- supports-color@6.1.0
| |   `-- has-flag@3.0.0
| +-- karma-source-map-support@1.4.0
| | `-- source-map-support@0.5.12 deduped
| +-- less@3.9.0
| | +-- clone@2.1.2
| | +-- errno@0.1.7
| | | `-- prr@1.0.1
| | +-- graceful-fs@4.1.15 deduped
| | +-- image-size@0.5.5
| | +-- mime@1.6.0
| | +-- mkdirp@0.5.1 deduped
| | +-- promise@7.3.1
| | | `-- asap@2.0.6
| | +-- request@2.88.0
| | | +-- aws-sign2@0.7.0
| | | +-- aws4@1.8.0
| | | +-- caseless@0.12.0
| | | +-- combined-stream@1.0.8
| | | | `-- delayed-stream@1.0.0
| | | +-- extend@3.0.2 deduped
| | | +-- forever-agent@0.6.1
| | | +-- form-data@2.3.3
| | | | +-- asynckit@0.4.0
| | | | +-- combined-stream@1.0.8 deduped
| | | | `-- mime-types@2.1.24 deduped
| | | +-- har-validator@5.1.3
| | | | +-- UNMET PEER DEPENDENCY ajv@6.6.2 deduped
| | | | `-- har-schema@2.0.0
| | | +-- http-signature@1.2.0
| | | | +-- assert-plus@1.0.0
| | | | +-- jsprim@1.4.1
| | | | | +-- assert-plus@1.0.0 deduped
| | | | | +-- extsprintf@1.3.0
| | | | | +-- json-schema@0.2.3
| | | | | `-- verror@1.10.0
| | | | |   +-- assert-plus@1.0.0 deduped
| | | | |   +-- core-util-is@1.0.2 deduped
| | | | |   `-- extsprintf@1.3.0 deduped
| | | | `-- sshpk@1.16.1
| | | |   +-- asn1@0.2.4
| | | |   | `-- safer-buffer@2.1.2 deduped
| | | |   +-- assert-plus@1.0.0 deduped
| | | |   +-- bcrypt-pbkdf@1.0.2
| | | |   | `-- tweetnacl@0.14.5 deduped
| | | |   +-- dashdash@1.14.1
| | | |   | `-- assert-plus@1.0.0 deduped
| | | |   +-- ecc-jsbn@0.1.2
| | | |   | +-- jsbn@0.1.1 deduped
| | | |   | `-- safer-buffer@2.1.2 deduped
| | | |   +-- getpass@0.1.7
| | | |   | `-- assert-plus@1.0.0 deduped
| | | |   +-- jsbn@0.1.1
| | | |   +-- safer-buffer@2.1.2 deduped
| | | |   `-- tweetnacl@0.14.5
| | | +-- is-typedarray@1.0.0
| | | +-- isstream@0.1.2
| | | +-- json-stringify-safe@5.0.1
| | | +-- mime-types@2.1.24
| | | | `-- mime-db@1.40.0
| | | +-- oauth-sign@0.9.0
| | | +-- performance-now@2.1.0
| | | +-- qs@6.5.2
| | | +-- safe-buffer@5.1.2 deduped
| | | +-- tough-cookie@2.4.3
| | | | +-- psl@1.1.32
| | | | `-- punycode@1.4.1
| | | +-- tunnel-agent@0.6.0
| | | | `-- safe-buffer@5.1.2 deduped
| | | `-- uuid@3.3.2 deduped
| | `-- source-map@0.6.1
| +-- less-loader@5.0.0
| | +-- clone@2.1.2 deduped
| | +-- loader-utils@1.2.3 deduped
| | `-- pify@4.0.1
| +-- license-webpack-plugin@2.1.2
| | +-- @types/webpack-sources@0.1.6
| | | +-- @types/node@10.12.30 deduped
| | | +-- @types/source-list-map@0.1.2
| | | `-- source-map@0.6.1
| | `-- webpack-sources@1.4.3 deduped
| +-- loader-utils@1.2.3
| | +-- big.js@5.2.2
| | +-- emojis-list@2.1.0
| | `-- json5@1.0.1
| |   `-- minimist@1.2.0 deduped
| +-- mini-css-extract-plugin@0.8.0
| | +-- loader-utils@1.2.3 deduped
| | +-- normalize-url@1.9.1
| | | +-- object-assign@4.1.1
| | | +-- prepend-http@1.0.4
| | | +-- query-string@4.3.4
| | | | +-- object-assign@4.1.1 deduped
| | | | `-- strict-uri-encode@1.1.0
| | | `-- sort-keys@1.1.2
| | |   `-- is-plain-obj@1.1.0
| | +-- schema-utils@1.0.0 deduped
| | `-- webpack-sources@1.4.3 deduped
| +-- minimatch@3.0.4
| | `-- brace-expansion@1.1.11
| |   +-- balanced-match@1.0.0
| |   `-- concat-map@0.0.1
| +-- open@6.4.0
| | `-- is-wsl@1.1.0
| +-- parse5@4.0.0
| +-- postcss@7.0.17
| | +-- chalk@2.4.2 deduped
| | +-- source-map@0.6.1
| | `-- supports-color@6.1.0 deduped
| +-- postcss-import@12.0.1
| | +-- postcss@7.0.17 deduped
| | +-- postcss-value-parser@3.3.1
| | +-- read-cache@1.0.0
| | | `-- pify@2.3.0
| | `-- resolve@1.11.0 deduped
| +-- postcss-loader@3.0.0
| | +-- loader-utils@1.2.3 deduped
| | +-- postcss@7.0.17 deduped
| | +-- postcss-load-config@2.1.0
| | | +-- cosmiconfig@5.2.1
| | | | +-- import-fresh@2.0.0
| | | | | +-- caller-path@2.0.0
| | | | | | `-- caller-callsite@2.0.0
| | | | | |   `-- callsites@2.0.0
| | | | | `-- resolve-from@3.0.0 deduped
| | | | +-- is-directory@0.3.1
| | | | +-- js-yaml@3.13.1 deduped
| | | | `-- parse-json@4.0.0
| | | |   +-- error-ex@1.3.2
| | | |   | `-- is-arrayish@0.2.1
| | | |   `-- json-parse-better-errors@1.0.2 deduped
| | | `-- import-cwd@2.1.0
| | |   `-- import-from@2.1.0
| | |     `-- resolve-from@3.0.0 deduped
| | `-- schema-utils@1.0.0 deduped
| +-- raw-loader@3.1.0
| | +-- loader-utils@1.2.3 deduped
| | `-- schema-utils@2.6.4
| |   +-- UNMET PEER DEPENDENCY ajv@6.11.0
| |   | +-- fast-deep-equal@3.1.1
| |   | +-- fast-json-stable-stringify@2.0.0 deduped
| |   | +-- json-schema-traverse@0.4.1 deduped
| |   | `-- uri-js@4.2.2 deduped
| |   `-- ajv-keywords@3.4.1 deduped
| +-- regenerator-runtime@0.13.3
| +-- rxjs@6.4.0
| | `-- tslib@1.10.0 deduped
| +-- sass@1.22.9
| | `-- chokidar@2.0.4 deduped
| +-- sass-loader@7.2.0
| | +-- clone-deep@4.0.1
| | | +-- is-plain-object@2.0.4
| | | | `-- isobject@3.0.1 deduped
| | | +-- kind-of@6.0.2
| | | `-- shallow-clone@3.0.1
| | |   `-- kind-of@6.0.2 deduped
| | +-- loader-utils@1.2.3 deduped
| | +-- neo-async@2.6.1
| | +-- pify@4.0.1 deduped
| | `-- semver@5.7.1
| +-- semver@6.3.0
| +-- source-map@0.7.3
| +-- source-map-loader@0.2.4
| | +-- async@2.6.2
| | | `-- lodash@4.17.20 deduped
| | `-- loader-utils@1.2.3 deduped
| +-- source-map-support@0.5.13
| | +-- buffer-from@1.1.1
| | `-- source-map@0.6.1
| +-- speed-measure-webpack-plugin@1.3.1
| | `-- chalk@2.4.2 deduped
| +-- style-loader@1.0.0
| | +-- loader-utils@1.2.3 deduped
| | `-- schema-utils@2.6.4
| |   +-- UNMET PEER DEPENDENCY ajv@6.11.0
| |   | +-- fast-deep-equal@3.1.1
| |   | +-- fast-json-stable-stringify@2.0.0 deduped
| |   | +-- json-schema-traverse@0.4.1 deduped
| |   | `-- uri-js@4.2.2 deduped
| |   `-- ajv-keywords@3.4.1 deduped
| +-- stylus@0.54.5
| | +-- css-parse@1.7.0
| | +-- debug@2.6.9
| | | `-- ms@2.0.0
| | +-- glob@7.0.6
| | | +-- fs.realpath@1.0.0 deduped
| | | +-- inflight@1.0.6 deduped
| | | +-- inherits@2.0.3 deduped
| | | +-- minimatch@3.0.4 deduped
| | | +-- once@1.4.0 deduped
| | | `-- path-is-absolute@1.0.1 deduped
| | +-- mkdirp@0.5.1 deduped
| | +-- sax@0.5.8
| | `-- source-map@0.1.43
| |   `-- amdefine@1.0.1
| +-- stylus-loader@3.0.2
| | +-- loader-utils@1.2.3 deduped
| | +-- lodash.clonedeep@4.5.0
| | `-- when@3.6.4
| +-- terser@4.6.3
| | +-- commander@2.20.0 deduped
| | +-- source-map@0.6.1
| | `-- source-map-support@0.5.12 deduped
| +-- terser-webpack-plugin@1.4.3
| | +-- cacache@12.0.3 deduped
| | +-- find-cache-dir@2.1.0
| | | +-- commondir@1.0.1 deduped
| | | +-- make-dir@2.1.0 deduped
| | | `-- pkg-dir@3.0.0 deduped
| | +-- is-wsl@1.1.0 deduped
| | +-- schema-utils@1.0.0 deduped
| | +-- serialize-javascript@2.1.2 deduped
| | +-- source-map@0.6.1
| | +-- terser@4.6.3 deduped
| | +-- webpack-sources@1.4.3 deduped
| | `-- worker-farm@1.7.0
| |   `-- errno@0.1.7 deduped
| +-- tree-kill@1.2.2
| +-- webpack@4.39.2
| | +-- @webassemblyjs/ast@1.8.5
| | | +-- @webassemblyjs/helper-module-context@1.8.5 deduped
| | | +-- @webassemblyjs/helper-wasm-bytecode@1.8.5
| | | `-- @webassemblyjs/wast-parser@1.8.5
| | |   +-- @webassemblyjs/ast@1.8.5 deduped
| | |   +-- @webassemblyjs/floating-point-hex-parser@1.8.5
| | |   +-- @webassemblyjs/helper-api-error@1.8.5 deduped
| | |   +-- @webassemblyjs/helper-code-frame@1.8.5
| | |   | `-- @webassemblyjs/wast-printer@1.8.5 deduped
| | |   +-- @webassemblyjs/helper-fsm@1.8.5
| | |   `-- @xtuc/long@4.2.2
| | +-- @webassemblyjs/helper-module-context@1.8.5
| | | +-- @webassemblyjs/ast@1.8.5 deduped
| | | `-- mamacro@0.0.3
| | +-- @webassemblyjs/wasm-edit@1.8.5
| | | +-- @webassemblyjs/ast@1.8.5 deduped
| | | +-- @webassemblyjs/helper-buffer@1.8.5
| | | +-- @webassemblyjs/helper-wasm-bytecode@1.8.5 deduped
| | | +-- @webassemblyjs/helper-wasm-section@1.8.5
| | | | +-- @webassemblyjs/ast@1.8.5 deduped
| | | | +-- @webassemblyjs/helper-buffer@1.8.5 deduped
| | | | +-- @webassemblyjs/helper-wasm-bytecode@1.8.5 deduped
| | | | `-- @webassemblyjs/wasm-gen@1.8.5 deduped
| | | +-- @webassemblyjs/wasm-gen@1.8.5
| | | | +-- @webassemblyjs/ast@1.8.5 deduped
| | | | +-- @webassemblyjs/helper-wasm-bytecode@1.8.5 deduped
| | | | +-- @webassemblyjs/ieee754@1.8.5 deduped
| | | | +-- @webassemblyjs/leb128@1.8.5 deduped
| | | | `-- @webassemblyjs/utf8@1.8.5 deduped
| | | +-- @webassemblyjs/wasm-opt@1.8.5
| | | | +-- @webassemblyjs/ast@1.8.5 deduped
| | | | +-- @webassemblyjs/helper-buffer@1.8.5 deduped
| | | | +-- @webassemblyjs/wasm-gen@1.8.5 deduped
| | | | `-- @webassemblyjs/wasm-parser@1.8.5 deduped
| | | +-- @webassemblyjs/wasm-parser@1.8.5 deduped
| | | `-- @webassemblyjs/wast-printer@1.8.5
| | |   +-- @webassemblyjs/ast@1.8.5 deduped
| | |   +-- @webassemblyjs/wast-parser@1.8.5 deduped
| | |   `-- @xtuc/long@4.2.2 deduped
| | +-- @webassemblyjs/wasm-parser@1.8.5
| | | +-- @webassemblyjs/ast@1.8.5 deduped
| | | +-- @webassemblyjs/helper-api-error@1.8.5
| | | +-- @webassemblyjs/helper-wasm-bytecode@1.8.5 deduped
| | | +-- @webassemblyjs/ieee754@1.8.5
| | | | `-- @xtuc/ieee754@1.2.0
| | | +-- @webassemblyjs/leb128@1.8.5
| | | | `-- @xtuc/long@4.2.2 deduped
| | | `-- @webassemblyjs/utf8@1.8.5
| | +-- acorn@6.4.2
| | +-- UNMET PEER DEPENDENCY ajv@6.11.0
| | | +-- fast-deep-equal@3.1.1
| | | +-- fast-json-stable-stringify@2.0.0 deduped
| | | +-- json-schema-traverse@0.4.1 deduped
| | | `-- uri-js@4.2.2 deduped
| | +-- ajv-keywords@3.4.1
| | +-- chrome-trace-event@1.0.2
| | | `-- tslib@1.10.0 deduped
| | +-- enhanced-resolve@4.1.0 deduped
| | +-- eslint-scope@4.0.3
| | | +-- esrecurse@4.2.1
| | | | `-- estraverse@4.3.0 deduped
| | | `-- estraverse@4.3.0
| | +-- json-parse-better-errors@1.0.2
| | +-- loader-runner@2.4.0
| | +-- loader-utils@1.2.3 deduped
| | +-- memory-fs@0.4.1
| | | +-- errno@0.1.7 deduped
| | | `-- readable-stream@2.3.6
| | |   +-- core-util-is@1.0.2
| | |   +-- inherits@2.0.3 deduped
| | |   +-- isarray@1.0.0
| | |   +-- process-nextick-args@2.0.0
| | |   +-- safe-buffer@5.1.2 deduped
| | |   +-- string_decoder@1.1.1 deduped
| | |   `-- util-deprecate@1.0.2
| | +-- micromatch@3.1.10
| | | +-- arr-diff@4.0.0
| | | +-- array-unique@0.3.2
| | | +-- braces@2.3.2 deduped
| | | +-- define-property@2.0.2
| | | | +-- is-descriptor@1.0.2
| | | | | +-- is-accessor-descriptor@1.0.0
| | | | | | `-- kind-of@6.0.2 deduped
| | | | | +-- is-data-descriptor@1.0.0
| | | | | | `-- kind-of@6.0.2 deduped
| | | | | `-- kind-of@6.0.2 deduped
| | | | `-- isobject@3.0.1 deduped
| | | +-- extend-shallow@3.0.2
| | | | +-- assign-symbols@1.0.0
| | | | `-- is-extendable@1.0.1
| | | |   `-- is-plain-object@2.0.4 deduped
| | | +-- extglob@2.0.4
| | | | +-- array-unique@0.3.2 deduped
| | | | +-- define-property@1.0.0
| | | | | `-- is-descriptor@1.0.2
| | | | |   +-- is-accessor-descriptor@1.0.0
| | | | |   | `-- kind-of@6.0.2 deduped
| | | | |   +-- is-data-descriptor@1.0.0
| | | | |   | `-- kind-of@6.0.2 deduped
| | | | |   `-- kind-of@6.0.2 deduped
| | | | +-- expand-brackets@2.1.4
| | | | | +-- debug@2.6.9 deduped
| | | | | +-- define-property@0.2.5
| | | | | | `-- is-descriptor@0.1.6 deduped
| | | | | +-- extend-shallow@2.0.1
| | | | | | `-- is-extendable@0.1.1 deduped
| | | | | +-- posix-character-classes@0.1.1
| | | | | +-- regex-not@1.0.2 deduped
| | | | | +-- snapdragon@0.8.2 deduped
| | | | | `-- to-regex@3.0.2 deduped
| | | | +-- extend-shallow@2.0.1
| | | | | `-- is-extendable@0.1.1 deduped
| | | | +-- fragment-cache@0.2.1 deduped
| | | | +-- regex-not@1.0.2 deduped
| | | | +-- snapdragon@0.8.2 deduped
| | | | `-- to-regex@3.0.2 deduped
| | | +-- fragment-cache@0.2.1
| | | | `-- map-cache@0.2.2
| | | +-- kind-of@6.0.2 deduped
| | | +-- nanomatch@1.2.13
| | | | +-- arr-diff@4.0.0 deduped
| | | | +-- array-unique@0.3.2 deduped
| | | | +-- define-property@2.0.2 deduped
| | | | +-- extend-shallow@3.0.2 deduped
| | | | +-- fragment-cache@0.2.1 deduped
| | | | +-- is-windows@1.0.2
| | | | +-- kind-of@6.0.2 deduped
| | | | +-- object.pick@1.3.0 deduped
| | | | +-- regex-not@1.0.2 deduped
| | | | +-- snapdragon@0.8.2 deduped
| | | | `-- to-regex@3.0.2 deduped
| | | +-- object.pick@1.3.0
| | | | `-- isobject@3.0.1 deduped
| | | +-- regex-not@1.0.2
| | | | +-- extend-shallow@3.0.2 deduped
| | | | `-- safe-regex@1.1.0
| | | |   `-- ret@0.1.15
| | | +-- snapdragon@0.8.2
| | | | +-- base@0.11.2
| | | | | +-- cache-base@1.0.1
| | | | | | +-- collection-visit@1.0.0
| | | | | | | +-- map-visit@1.0.0
| | | | | | | | `-- object-visit@1.0.1 deduped
| | | | | | | `-- object-visit@1.0.1
| | | | | | |   `-- isobject@3.0.1 deduped
| | | | | | +-- component-emitter@1.3.0 deduped
| | | | | | +-- get-value@2.0.6
| | | | | | +-- has-value@1.0.0
| | | | | | | +-- get-value@2.0.6 deduped
| | | | | | | +-- has-values@1.0.0
| | | | | | | | +-- is-number@3.0.0 deduped
| | | | | | | | `-- kind-of@4.0.0
| | | | | | | |   `-- is-buffer@1.1.6 deduped
| | | | | | | `-- isobject@3.0.1 deduped
| | | | | | +-- isobject@3.0.1 deduped
| | | | | | +-- set-value@2.0.1
| | | | | | | +-- extend-shallow@2.0.1
| | | | | | | | `-- is-extendable@0.1.1 deduped
| | | | | | | +-- is-extendable@0.1.1 deduped
| | | | | | | +-- is-plain-object@2.0.4 deduped
| | | | | | | `-- split-string@3.1.0 deduped
| | | | | | +-- to-object-path@0.3.0
| | | | | | | `-- kind-of@3.2.2
| | | | | | |   `-- is-buffer@1.1.6 deduped
| | | | | | +-- union-value@1.0.1
| | | | | | | +-- arr-union@3.1.0 deduped
| | | | | | | +-- get-value@2.0.6 deduped
| | | | | | | +-- is-extendable@0.1.1 deduped
| | | | | | | `-- set-value@2.0.1 deduped
| | | | | | `-- unset-value@1.0.0
| | | | | |   +-- has-value@0.3.1
| | | | | |   | +-- get-value@2.0.6 deduped
| | | | | |   | +-- has-values@0.1.4
| | | | | |   | `-- isobject@2.1.0
| | | | | |   |   `-- isarray@1.0.0 deduped
| | | | | |   `-- isobject@3.0.1 deduped
| | | | | +-- class-utils@0.3.6
| | | | | | +-- arr-union@3.1.0
| | | | | | +-- define-property@0.2.5
| | | | | | | `-- is-descriptor@0.1.6 deduped
| | | | | | +-- isobject@3.0.1 deduped
| | | | | | `-- static-extend@0.1.2
| | | | | |   +-- define-property@0.2.5
| | | | | |   | `-- is-descriptor@0.1.6 deduped
| | | | | |   `-- object-copy@0.1.0
| | | | | |     +-- copy-descriptor@0.1.1
| | | | | |     +-- define-property@0.2.5
| | | | | |     | `-- is-descriptor@0.1.6 deduped
| | | | | |     `-- kind-of@3.2.2
| | | | | |       `-- is-buffer@1.1.6 deduped
| | | | | +-- component-emitter@1.3.0
| | | | | +-- define-property@1.0.0
| | | | | | `-- is-descriptor@1.0.2
| | | | | |   +-- is-accessor-descriptor@1.0.0
| | | | | |   | `-- kind-of@6.0.2 deduped
| | | | | |   +-- is-data-descriptor@1.0.0
| | | | | |   | `-- kind-of@6.0.2 deduped
| | | | | |   `-- kind-of@6.0.2 deduped
| | | | | +-- isobject@3.0.1 deduped
| | | | | +-- mixin-deep@1.3.2
| | | | | | +-- for-in@1.0.2
| | | | | | `-- is-extendable@1.0.1
| | | | | |   `-- is-plain-object@2.0.4 deduped
| | | | | `-- pascalcase@0.1.1
| | | | +-- debug@2.6.9 deduped
| | | | +-- define-property@0.2.5
| | | | | `-- is-descriptor@0.1.6
| | | | |   +-- is-accessor-descriptor@0.1.6
| | | | |   | `-- kind-of@3.2.2
| | | | |   |   `-- is-buffer@1.1.6 deduped
| | | | |   +-- is-data-descriptor@0.1.4
| | | | |   | `-- kind-of@3.2.2
| | | | |   |   `-- is-buffer@1.1.6 deduped
| | | | |   `-- kind-of@5.1.0
| | | | +-- extend-shallow@2.0.1
| | | | | `-- is-extendable@0.1.1 deduped
| | | | +-- map-cache@0.2.2 deduped
| | | | +-- source-map@0.5.7
| | | | +-- source-map-resolve@0.5.2
| | | | | +-- atob@2.1.2
| | | | | +-- decode-uri-component@0.2.0
| | | | | +-- resolve-url@0.2.1
| | | | | +-- source-map-url@0.4.0
| | | | | `-- urix@0.1.0
| | | | `-- use@3.1.1
| | | `-- to-regex@3.0.2
| | |   +-- define-property@2.0.2 deduped
| | |   +-- extend-shallow@3.0.2 deduped
| | |   +-- regex-not@1.0.2 deduped
| | |   `-- safe-regex@1.1.0 deduped
| | +-- mkdirp@0.5.1 deduped
| | +-- neo-async@2.6.1 deduped
| | +-- node-libs-browser@2.2.1
| | | +-- assert@1.5.0
| | | | +-- object-assign@4.1.1 deduped
| | | | `-- util@0.10.3
| | | |   `-- inherits@2.0.1
| | | +-- browserify-zlib@0.2.0
| | | | `-- pako@1.0.10 deduped
| | | +-- buffer@4.9.2
| | | | +-- base64-js@1.3.1
| | | | +-- ieee754@1.1.13
| | | | `-- isarray@1.0.0 deduped
| | | +-- console-browserify@1.2.0
| | | +-- constants-browserify@1.0.0
| | | +-- crypto-browserify@3.12.0
| | | | +-- browserify-cipher@1.0.1
| | | | | +-- browserify-aes@1.2.0
| | | | | | +-- buffer-xor@1.0.3
| | | | | | +-- cipher-base@1.0.4 deduped
| | | | | | +-- create-hash@1.2.0 deduped
| | | | | | +-- evp_bytestokey@1.0.3 deduped
| | | | | | +-- inherits@2.0.3 deduped
| | | | | | `-- safe-buffer@5.1.2 deduped
| | | | | +-- browserify-des@1.0.2
| | | | | | +-- cipher-base@1.0.4 deduped
| | | | | | +-- des.js@1.0.1
| | | | | | | +-- inherits@2.0.3 deduped
| | | | | | | `-- minimalistic-assert@1.0.1 deduped
| | | | | | +-- inherits@2.0.3 deduped
| | | | | | `-- safe-buffer@5.1.2 deduped
| | | | | `-- evp_bytestokey@1.0.3
| | | | |   +-- md5.js@1.3.5 deduped
| | | | |   `-- safe-buffer@5.1.2 deduped
| | | | +-- browserify-sign@4.0.4
| | | | | +-- bn.js@4.11.8
| | | | | +-- browserify-rsa@4.0.1
| | | | | | +-- bn.js@4.11.8 deduped
| | | | | | `-- randombytes@2.1.0 deduped
| | | | | +-- create-hash@1.2.0 deduped
| | | | | +-- create-hmac@1.1.7 deduped
| | | | | +-- elliptic@6.5.3
| | | | | | +-- bn.js@4.11.8 deduped
| | | | | | +-- brorand@1.1.0
| | | | | | +-- hash.js@1.1.7
| | | | | | | +-- inherits@2.0.3 deduped
| | | | | | | `-- minimalistic-assert@1.0.1 deduped
| | | | | | +-- hmac-drbg@1.0.1
| | | | | | | +-- hash.js@1.1.7 deduped
| | | | | | | +-- minimalistic-assert@1.0.1 deduped
| | | | | | | `-- minimalistic-crypto-utils@1.0.1 deduped
| | | | | | +-- inherits@2.0.3 deduped
| | | | | | +-- minimalistic-assert@1.0.1 deduped
| | | | | | `-- minimalistic-crypto-utils@1.0.1
| | | | | +-- inherits@2.0.3 deduped
| | | | | `-- parse-asn1@5.1.5
| | | | |   +-- asn1.js@4.10.1
| | | | |   | +-- bn.js@4.11.8 deduped
| | | | |   | +-- inherits@2.0.3 deduped
| | | | |   | `-- minimalistic-assert@1.0.1 deduped
| | | | |   +-- browserify-aes@1.2.0 deduped
| | | | |   +-- create-hash@1.2.0 deduped
| | | | |   +-- evp_bytestokey@1.0.3 deduped
| | | | |   +-- pbkdf2@3.0.17 deduped
| | | | |   `-- safe-buffer@5.1.2 deduped
| | | | +-- create-ecdh@4.0.3
| | | | | +-- bn.js@4.11.8 deduped
| | | | | `-- elliptic@6.5.3 deduped
| | | | +-- create-hash@1.2.0
| | | | | +-- cipher-base@1.0.4
| | | | | | +-- inherits@2.0.3 deduped
| | | | | | `-- safe-buffer@5.1.2 deduped
| | | | | +-- inherits@2.0.3 deduped
| | | | | +-- md5.js@1.3.5
| | | | | | +-- hash-base@3.0.4
| | | | | | | +-- inherits@2.0.3 deduped
| | | | | | | `-- safe-buffer@5.1.2 deduped
| | | | | | +-- inherits@2.0.3 deduped
| | | | | | `-- safe-buffer@5.1.2 deduped
| | | | | +-- ripemd160@2.0.2
| | | | | | +-- hash-base@3.0.4 deduped
| | | | | | `-- inherits@2.0.3 deduped
| | | | | `-- sha.js@2.4.11
| | | | |   +-- inherits@2.0.3 deduped
| | | | |   `-- safe-buffer@5.1.2 deduped
| | | | +-- create-hmac@1.1.7
| | | | | +-- cipher-base@1.0.4 deduped
| | | | | +-- create-hash@1.2.0 deduped
| | | | | +-- inherits@2.0.3 deduped
| | | | | +-- ripemd160@2.0.2 deduped
| | | | | +-- safe-buffer@5.1.2 deduped
| | | | | `-- sha.js@2.4.11 deduped
| | | | +-- diffie-hellman@5.0.3
| | | | | +-- bn.js@4.11.8 deduped
| | | | | +-- miller-rabin@4.0.1
| | | | | | +-- bn.js@4.11.8 deduped
| | | | | | `-- brorand@1.1.0 deduped
| | | | | `-- randombytes@2.1.0 deduped
| | | | +-- inherits@2.0.3 deduped
| | | | +-- pbkdf2@3.0.17
| | | | | +-- create-hash@1.2.0 deduped
| | | | | +-- create-hmac@1.1.7 deduped
| | | | | +-- ripemd160@2.0.2 deduped
| | | | | +-- safe-buffer@5.1.2 deduped
| | | | | `-- sha.js@2.4.11 deduped
| | | | +-- public-encrypt@4.0.3
| | | | | +-- bn.js@4.11.8 deduped
| | | | | +-- browserify-rsa@4.0.1 deduped
| | | | | +-- create-hash@1.2.0 deduped
| | | | | +-- parse-asn1@5.1.5 deduped
| | | | | +-- randombytes@2.1.0 deduped
| | | | | `-- safe-buffer@5.1.2 deduped
| | | | +-- randombytes@2.1.0
| | | | | `-- safe-buffer@5.1.2 deduped
| | | | `-- randomfill@1.0.4
| | | |   +-- randombytes@2.1.0 deduped
| | | |   `-- safe-buffer@5.1.2 deduped
| | | +-- domain-browser@1.2.0
| | | +-- events@3.1.0
| | | +-- https-browserify@1.0.0
| | | +-- os-browserify@0.3.0
| | | +-- path-browserify@0.0.1
| | | +-- process@0.11.10
| | | +-- punycode@1.4.1
| | | +-- querystring-es3@0.2.1
| | | +-- readable-stream@2.3.6 deduped
| | | +-- stream-browserify@2.0.2
| | | | +-- inherits@2.0.3 deduped
| | | | `-- readable-stream@2.3.6 deduped
| | | +-- stream-http@2.8.3
| | | | +-- builtin-status-codes@3.0.0
| | | | +-- inherits@2.0.3 deduped
| | | | +-- readable-stream@2.3.6 deduped
| | | | +-- to-arraybuffer@1.0.1
| | | | `-- xtend@4.0.1 deduped
| | | +-- string_decoder@1.1.1
| | | | `-- safe-buffer@5.1.2 deduped
| | | +-- timers-browserify@2.0.11
| | | | `-- setimmediate@1.0.5
| | | +-- tty-browserify@0.0.0
| | | +-- url@0.11.0 deduped
| | | +-- util@0.11.1
| | | | `-- inherits@2.0.3 deduped
| | | `-- vm-browserify@1.1.2
| | +-- schema-utils@1.0.0 deduped
| | +-- tapable@1.1.3
| | +-- terser-webpack-plugin@1.4.3 deduped
| | +-- watchpack@1.6.0
| | | +-- chokidar@2.0.4 deduped
| | | +-- graceful-fs@4.1.15 deduped
| | | `-- neo-async@2.6.1 deduped
| | `-- webpack-sources@1.4.3 deduped
| +-- webpack-dev-middleware@3.7.2
| | +-- memory-fs@0.4.1 deduped
| | +-- mime@2.4.4
| | +-- mkdirp@0.5.1 deduped
| | +-- range-parser@1.2.1 deduped
| | `-- webpack-log@2.0.0 deduped
| +-- webpack-dev-server@3.9.0
| | +-- ansi-html@0.0.7
| | +-- bonjour@3.5.0
| | | +-- array-flatten@2.1.2
| | | +-- deep-equal@1.1.1
| | | | +-- is-arguments@1.0.4
| | | | +-- is-date-object@1.0.2
| | | | +-- is-regex@1.0.5
| | | | | `-- has@1.0.3
| | | | |   `-- function-bind@1.1.1 deduped
| | | | +-- object-is@1.0.2
| | | | +-- object-keys@1.1.1
| | | | `-- regexp.prototype.flags@1.3.0
| | | |   +-- define-properties@1.1.3 deduped
| | | |   `-- es-abstract@1.17.4 deduped
| | | +-- dns-equal@1.0.0
| | | +-- dns-txt@2.0.2
| | | | `-- buffer-indexof@1.1.1
| | | +-- multicast-dns@6.2.3
| | | | +-- dns-packet@1.3.1
| | | | | +-- ip@1.1.5 deduped
| | | | | `-- safe-buffer@5.1.2 deduped
| | | | `-- thunky@1.1.0
| | | `-- multicast-dns-service-types@1.1.0
| | +-- chokidar@2.1.8
| | | +-- anymatch@2.0.0 deduped
| | | +-- async-each@1.0.3 deduped
| | | +-- braces@2.3.2 deduped
| | | +-- fsevents@1.2.9 deduped
| | | +-- glob-parent@3.1.0 deduped
| | | +-- inherits@2.0.3 deduped
| | | +-- is-binary-path@1.0.1 deduped
| | | +-- is-glob@4.0.1 deduped
| | | +-- normalize-path@3.0.0
| | | +-- path-is-absolute@1.0.1 deduped
| | | +-- readdirp@2.2.1 deduped
| | | `-- upath@1.1.2 deduped
| | +-- compression@1.7.4
| | | +-- accepts@1.3.7
| | | | +-- mime-types@2.1.24 deduped
| | | | `-- negotiator@0.6.2
| | | +-- bytes@3.0.0
| | | +-- compressible@2.0.18
| | | | `-- mime-db@1.43.0
| | | +-- debug@2.6.9 deduped
| | | +-- on-headers@1.0.2
| | | +-- safe-buffer@5.1.2 deduped
| | | `-- vary@1.1.2
| | +-- connect-history-api-fallback@1.6.0
| | +-- debug@4.1.1
| | | `-- ms@2.1.2
| | +-- del@4.1.1
| | | +-- @types/glob@7.1.1
| | | | +-- @types/events@3.0.0
| | | | +-- @types/minimatch@3.0.3
| | | | `-- @types/node@10.12.30 deduped
| | | +-- globby@6.1.0
| | | | +-- array-union@1.0.2 deduped
| | | | +-- glob@7.1.3 deduped
| | | | +-- object-assign@4.1.1 deduped
| | | | +-- pify@2.3.0
| | | | `-- pinkie-promise@2.0.1 deduped
| | | +-- is-path-cwd@2.2.0
| | | +-- is-path-in-cwd@2.1.0
| | | | `-- is-path-inside@2.1.0
| | | |   `-- path-is-inside@1.0.2
| | | +-- p-map@2.1.0
| | | +-- pify@4.0.1 deduped
| | | `-- rimraf@2.6.3 deduped
| | +-- express@4.17.1
| | | +-- accepts@1.3.7 deduped
| | | +-- array-flatten@1.1.1
| | | +-- body-parser@1.19.0 deduped
| | | +-- content-disposition@0.5.3
| | | | `-- safe-buffer@5.1.2 deduped
| | | +-- content-type@1.0.4 deduped
| | | +-- cookie@0.4.0
| | | +-- cookie-signature@1.0.6
| | | +-- debug@2.6.9 deduped
| | | +-- depd@1.1.2 deduped
| | | +-- encodeurl@1.0.2
| | | +-- escape-html@1.0.3
| | | +-- etag@1.8.1
| | | +-- finalhandler@1.1.2 deduped
| | | +-- fresh@0.5.2
| | | +-- merge-descriptors@1.0.1
| | | +-- methods@1.1.2
| | | +-- on-finished@2.3.0 deduped
| | | +-- parseurl@1.3.3 deduped
| | | +-- path-to-regexp@0.1.7
| | | +-- proxy-addr@2.0.5
| | | | +-- forwarded@0.1.2
| | | | `-- ipaddr.js@1.9.0 deduped
| | | +-- qs@6.7.0
| | | +-- range-parser@1.2.1 deduped
| | | +-- safe-buffer@5.1.2 deduped
| | | +-- send@0.17.1
| | | | +-- debug@2.6.9 deduped
| | | | +-- depd@1.1.2 deduped
| | | | +-- destroy@1.0.4
| | | | +-- encodeurl@1.0.2 deduped
| | | | +-- escape-html@1.0.3 deduped
| | | | +-- etag@1.8.1 deduped
| | | | +-- fresh@0.5.2 deduped
| | | | +-- http-errors@1.7.2 deduped
| | | | +-- mime@1.6.0 deduped
| | | | +-- ms@2.1.1
| | | | +-- on-finished@2.3.0 deduped
| | | | +-- range-parser@1.2.1 deduped
| | | | `-- statuses@1.5.0 deduped
| | | +-- serve-static@1.14.1
| | | | +-- encodeurl@1.0.2 deduped
| | | | +-- escape-html@1.0.3 deduped
| | | | +-- parseurl@1.3.3 deduped
| | | | `-- send@0.17.1 deduped
| | | +-- setprototypeof@1.1.1
| | | +-- statuses@1.5.0
| | | +-- type-is@1.6.18 deduped
| | | +-- utils-merge@1.0.1 deduped
| | | `-- vary@1.1.2 deduped
| | +-- html-entities@1.2.1
| | +-- http-proxy-middleware@0.19.1
| | | +-- http-proxy@1.18.1 deduped
| | | +-- is-glob@4.0.1 deduped
| | | +-- lodash@4.17.20 deduped
| | | `-- micromatch@3.1.10 deduped
| | +-- import-local@2.0.0
| | | +-- pkg-dir@3.0.0 deduped
| | | `-- resolve-cwd@2.0.0
| | |   `-- resolve-from@3.0.0
| | +-- internal-ip@4.3.0
| | | +-- default-gateway@4.2.0
| | | | +-- execa@1.0.0 deduped
| | | | `-- ip-regex@2.1.0
| | | `-- ipaddr.js@1.9.0
| | +-- ip@1.1.5
| | +-- is-absolute-url@3.0.3
| | +-- killable@1.0.1
| | +-- loglevel@1.6.7
| | +-- opn@5.5.0
| | | `-- is-wsl@1.1.0 deduped
| | +-- p-retry@3.0.1
| | | `-- retry@0.12.0
| | +-- portfinder@1.0.25
| | | +-- async@2.6.2 deduped
| | | +-- debug@3.2.6
| | | | `-- ms@2.1.2
| | | `-- mkdirp@0.5.1 deduped
| | +-- schema-utils@1.0.0 deduped
| | +-- selfsigned@1.10.7
| | | `-- node-forge@0.9.0
| | +-- semver@6.3.0
| | +-- serve-index@1.9.1
| | | +-- accepts@1.3.7 deduped
| | | +-- batch@0.6.1
| | | +-- debug@2.6.9 deduped
| | | +-- escape-html@1.0.3 deduped
| | | +-- http-errors@1.6.3
| | | | +-- depd@1.1.2 deduped
| | | | +-- inherits@2.0.3 deduped
| | | | +-- setprototypeof@1.1.0
| | | | `-- statuses@1.5.0 deduped
| | | +-- mime-types@2.1.24 deduped
| | | `-- parseurl@1.3.3 deduped
| | +-- sockjs@0.3.19
| | | +-- faye-websocket@0.10.0
| | | | `-- websocket-driver@0.7.3
| | | |   +-- http-parser-js@0.4.10
| | | |   +-- safe-buffer@5.1.2 deduped
| | | |   `-- websocket-extensions@0.1.4
| | | `-- uuid@3.3.2 deduped
| | +-- sockjs-client@1.4.0
| | | +-- debug@3.2.6
| | | | `-- ms@2.1.2
| | | +-- eventsource@1.0.7
| | | | `-- original@1.0.2
| | | |   `-- url-parse@1.4.7 deduped
| | | +-- faye-websocket@0.11.3
| | | | `-- websocket-driver@0.7.3 deduped
| | | +-- inherits@2.0.3 deduped
| | | +-- json3@3.3.3
| | | `-- url-parse@1.4.7
| | |   +-- querystringify@2.1.1
| | |   `-- requires-port@1.0.0 deduped
| | +-- spdy@4.0.1
| | | +-- debug@4.1.1
| | | | `-- ms@2.1.2
| | | +-- handle-thing@2.0.0
| | | +-- http-deceiver@1.2.7
| | | +-- select-hose@2.0.0
| | | `-- spdy-transport@3.0.0
| | |   +-- debug@4.1.1
| | |   | `-- ms@2.1.2
| | |   +-- detect-node@2.0.4
| | |   +-- hpack.js@2.1.6
| | |   | +-- inherits@2.0.3 deduped
| | |   | +-- obuf@1.1.2 deduped
| | |   | +-- readable-stream@2.3.6 deduped
| | |   | `-- wbuf@1.7.3 deduped
| | |   +-- obuf@1.1.2
| | |   +-- readable-stream@3.5.0
| | |   | +-- inherits@2.0.3 deduped
| | |   | +-- string_decoder@1.1.1 deduped
| | |   | `-- util-deprecate@1.0.2 deduped
| | |   `-- wbuf@1.7.3
| | |     `-- minimalistic-assert@1.0.1
| | +-- strip-ansi@3.0.1
| | | `-- ansi-regex@2.1.1
| | +-- supports-color@6.1.0 deduped
| | +-- url@0.11.0
| | | +-- punycode@1.3.2
| | | `-- querystring@0.2.0
| | +-- webpack-dev-middleware@3.7.2 deduped
| | +-- webpack-log@2.0.0 deduped
| | +-- ws@6.2.1
| | | `-- async-limiter@1.0.0
| | `-- yargs@12.0.5
| |   +-- cliui@4.1.0 deduped
| |   +-- decamelize@1.2.0
| |   +-- find-up@3.0.0 deduped
| |   +-- get-caller-file@1.0.3
| |   +-- os-locale@3.1.0 deduped
| |   +-- require-directory@2.1.1 deduped
| |   +-- require-main-filename@1.0.1
| |   +-- set-blocking@2.0.0 deduped
| |   +-- string-width@2.1.1
| |   | +-- is-fullwidth-code-point@2.0.0 deduped
| |   | `-- strip-ansi@4.0.0
| |   |   `-- ansi-regex@3.0.0
| |   +-- which-module@2.0.0 deduped
| |   +-- y18n@4.0.0 deduped
| |   `-- yargs-parser@11.1.1
| |     +-- camelcase@5.3.1 deduped
| |     `-- decamelize@1.2.0 deduped
| +-- webpack-merge@4.2.1
| | `-- lodash@4.17.20 deduped
| +-- webpack-sources@1.4.3
| | +-- source-list-map@2.0.1
| | `-- source-map@0.6.1
| +-- webpack-subresource-integrity@1.1.0-rc.6
| | `-- webpack-core@0.6.9
| |   +-- source-list-map@0.1.8
| |   `-- source-map@0.4.4
| |     `-- amdefine@1.0.1 deduped
| `-- worker-plugin@3.2.0
|   `-- loader-utils@1.2.3 deduped
+-- @angular-devkit/core@7.2.4
| +-- UNMET PEER DEPENDENCY ajv@6.6.2
| | +-- fast-deep-equal@2.0.1 deduped
| | +-- fast-json-stable-stringify@2.0.0 deduped
| | +-- json-schema-traverse@0.4.1 deduped
| | `-- uri-js@4.2.2 deduped
| +-- chokidar@2.0.4
| | +-- anymatch@2.0.0
| | | +-- micromatch@3.1.10 deduped
| | | `-- normalize-path@2.1.1 deduped
| | +-- async-each@1.0.3
| | +-- braces@2.3.2
| | | +-- arr-flatten@1.1.0
| | | +-- array-unique@0.3.2 deduped
| | | +-- extend-shallow@2.0.1
| | | | `-- is-extendable@0.1.1
| | | +-- fill-range@4.0.0
| | | | +-- extend-shallow@2.0.1
| | | | | `-- is-extendable@0.1.1 deduped
| | | | +-- is-number@3.0.0
| | | | | `-- kind-of@3.2.2
| | | | |   `-- is-buffer@1.1.6
| | | | +-- repeat-string@1.6.1
| | | | `-- to-regex-range@2.1.1
| | | |   +-- is-number@3.0.0 deduped
| | | |   `-- repeat-string@1.6.1 deduped
| | | +-- isobject@3.0.1
| | | +-- repeat-element@1.1.3
| | | +-- snapdragon@0.8.2 deduped
| | | +-- snapdragon-node@2.1.1
| | | | +-- define-property@1.0.0
| | | | | `-- is-descriptor@1.0.2
| | | | |   +-- is-accessor-descriptor@1.0.0
| | | | |   | `-- kind-of@6.0.2 deduped
| | | | |   +-- is-data-descriptor@1.0.0
| | | | |   | `-- kind-of@6.0.2 deduped
| | | | |   `-- kind-of@6.0.2 deduped
| | | | +-- isobject@3.0.1 deduped
| | | | `-- snapdragon-util@3.0.1
| | | |   `-- kind-of@3.2.2
| | | |     `-- is-buffer@1.1.6 deduped
| | | +-- split-string@3.1.0
| | | | `-- extend-shallow@3.0.2 deduped
| | | `-- to-regex@3.0.2 deduped
| | +-- fsevents@1.2.9
| | | +-- nan@2.14.0
| | | `-- node-pre-gyp@0.12.0
| | |   +-- detect-libc@1.0.3
| | |   +-- mkdirp@0.5.1
| | |   | `-- minimist@0.0.8
| | |   +-- needle@2.3.0
| | |   | +-- debug@4.1.1
| | |   | | `-- ms@2.1.1
| | |   | +-- iconv-lite@0.4.24
| | |   | | `-- safer-buffer@2.1.2
| | |   | `-- sax@1.2.4
| | |   +-- nopt@4.0.1
| | |   | +-- abbrev@1.1.1
| | |   | `-- osenv@0.1.5
| | |   |   +-- os-homedir@1.0.2
| | |   |   `-- os-tmpdir@1.0.2
| | |   +-- npm-packlist@1.4.1
| | |   | +-- ignore-walk@3.0.1
| | |   | | `-- minimatch@3.0.4
| | |   | |   `-- brace-expansion@1.1.11
| | |   | |     +-- balanced-match@1.0.0
| | |   | |     `-- concat-map@0.0.1
| | |   | `-- npm-bundled@1.0.6
| | |   +-- npmlog@4.1.2
| | |   | +-- are-we-there-yet@1.1.5
| | |   | | +-- delegates@1.0.0
| | |   | | `-- readable-stream@2.3.6
| | |   | |   +-- core-util-is@1.0.2
| | |   | |   +-- inherits@2.0.3 deduped
| | |   | |   +-- isarray@1.0.0
| | |   | |   +-- process-nextick-args@2.0.0
| | |   | |   +-- safe-buffer@5.1.2 deduped
| | |   | |   +-- string_decoder@1.1.1
| | |   | |   | `-- safe-buffer@5.1.2 deduped
| | |   | |   `-- util-deprecate@1.0.2
| | |   | +-- console-control-strings@1.1.0
| | |   | +-- gauge@2.7.4
| | |   | | +-- aproba@1.2.0
| | |   | | +-- console-control-strings@1.1.0 deduped
| | |   | | +-- has-unicode@2.0.1
| | |   | | +-- object-assign@4.1.1
| | |   | | +-- signal-exit@3.0.2
| | |   | | +-- string-width@1.0.2
| | |   | | | +-- code-point-at@1.1.0
| | |   | | | +-- is-fullwidth-code-point@1.0.0
| | |   | | | | `-- number-is-nan@1.0.1
| | |   | | | `-- strip-ansi@3.0.1 deduped
| | |   | | +-- strip-ansi@3.0.1
| | |   | | | `-- ansi-regex@2.1.1
| | |   | | `-- wide-align@1.1.3
| | |   | |   `-- string-width@1.0.2 deduped
| | |   | `-- set-blocking@2.0.0
| | |   +-- rc@1.2.8
| | |   | +-- deep-extend@0.6.0
| | |   | +-- ini@1.3.5
| | |   | +-- minimist@1.2.0
| | |   | `-- strip-json-comments@2.0.1
| | |   +-- rimraf@2.6.3
| | |   | `-- glob@7.1.3
| | |   |   +-- fs.realpath@1.0.0
| | |   |   +-- inflight@1.0.6
| | |   |   | +-- once@1.4.0 deduped
| | |   |   | `-- wrappy@1.0.2
| | |   |   +-- inherits@2.0.3
| | |   |   +-- minimatch@3.0.4 deduped
| | |   |   +-- once@1.4.0
| | |   |   | `-- wrappy@1.0.2 deduped
| | |   |   `-- path-is-absolute@1.0.1
| | |   +-- semver@5.7.0
| | |   `-- tar@4.4.8
| | |     +-- chownr@1.1.1
| | |     +-- fs-minipass@1.2.5
| | |     | `-- minipass@2.3.5 deduped
| | |     +-- minipass@2.3.5
| | |     | +-- safe-buffer@5.1.2 deduped
| | |     | `-- yallist@3.0.3 deduped
| | |     +-- minizlib@1.2.1
| | |     | `-- minipass@2.3.5 deduped
| | |     +-- mkdirp@0.5.1 deduped
| | |     +-- safe-buffer@5.1.2
| | |     `-- yallist@3.0.3
| | +-- glob-parent@3.1.0 deduped
| | +-- inherits@2.0.3 deduped
| | +-- is-binary-path@1.0.1
| | | `-- binary-extensions@1.13.1
| | +-- is-glob@4.0.1 deduped
| | +-- lodash.debounce@4.0.8
| | +-- normalize-path@2.1.1
| | | `-- remove-trailing-separator@1.1.0
| | +-- path-is-absolute@1.0.1 deduped
| | +-- readdirp@2.2.1
| | | +-- graceful-fs@4.1.15 deduped
| | | +-- micromatch@3.1.10 deduped
| | | `-- readable-stream@2.3.6 deduped
| | `-- upath@1.1.2
| +-- fast-json-stable-stringify@2.0.0
| +-- rxjs@6.3.3
| | `-- tslib@1.10.0 deduped
| `-- source-map@0.7.3 deduped
+-- @angular-devkit/schematics@7.2.4
| +-- @angular-devkit/core@7.2.4 deduped
| `-- rxjs@6.3.3
|   `-- tslib@1.10.0 deduped
+-- @angular/cli@8.3.25
| +-- @angular-devkit/architect@0.803.25
| | +-- @angular-devkit/core@8.3.25 deduped
| | `-- rxjs@6.4.0
| |   `-- tslib@1.10.0 deduped
| +-- @angular-devkit/core@8.3.25
| | +-- ajv@6.10.2
| | | +-- fast-deep-equal@2.0.1 deduped
| | | +-- fast-json-stable-stringify@2.0.0 deduped
| | | +-- json-schema-traverse@0.4.1 deduped
| | | `-- uri-js@4.2.2 deduped
| | +-- fast-json-stable-stringify@2.0.0 deduped
| | +-- magic-string@0.25.3 deduped
| | +-- rxjs@6.4.0 deduped
| | `-- source-map@0.7.3 deduped
| +-- @angular-devkit/schematics@8.3.25
| | +-- @angular-devkit/core@8.3.25 deduped
| | `-- rxjs@6.4.0 deduped
| +-- @schematics/angular@8.3.25
| | +-- @angular-devkit/core@8.3.25 deduped
| | `-- @angular-devkit/schematics@8.3.25 deduped
| +-- @schematics/update@0.803.25
| | +-- @angular-devkit/core@8.3.25
| | | +-- ajv@6.10.2
| | | | +-- fast-deep-equal@2.0.1 deduped
| | | | +-- fast-json-stable-stringify@2.0.0 deduped
| | | | +-- json-schema-traverse@0.4.1 deduped
| | | | `-- uri-js@4.2.2 deduped
| | | +-- fast-json-stable-stringify@2.0.0 deduped
| | | +-- magic-string@0.25.3 deduped
| | | +-- rxjs@6.4.0 deduped
| | | `-- source-map@0.7.3 deduped
| | +-- @angular-devkit/schematics@8.3.25
| | | +-- @angular-devkit/core@8.3.25 deduped
| | | `-- rxjs@6.4.0 deduped
| | +-- @yarnpkg/lockfile@1.1.0 deduped
| | +-- ini@1.3.5 deduped
| | +-- pacote@9.5.5 deduped
| | +-- rxjs@6.4.0
| | | `-- tslib@1.10.0 deduped
| | +-- semver@6.3.0
| | `-- semver-intersect@1.4.0
| |   `-- semver@5.7.1
| +-- @yarnpkg/lockfile@1.1.0
| +-- ansi-colors@4.1.1
| +-- debug@4.1.1
| | `-- ms@2.1.2
| +-- ini@1.3.5
| +-- inquirer@6.5.1
| | +-- ansi-escapes@4.3.0
| | | `-- type-fest@0.8.1
| | +-- chalk@2.4.2 deduped
| | +-- cli-cursor@3.1.0
| | | `-- restore-cursor@3.1.0
| | |   +-- onetime@5.1.0
| | |   | `-- mimic-fn@2.1.0 deduped
| | |   `-- signal-exit@3.0.2
| | +-- cli-width@2.2.0
| | +-- external-editor@3.1.0
| | | +-- chardet@0.7.0
| | | +-- iconv-lite@0.4.24 deduped
| | | `-- tmp@0.0.33 deduped
| | +-- figures@3.1.0
| | | `-- escape-string-regexp@1.0.5 deduped
| | +-- lodash@4.17.20 deduped
| | +-- mute-stream@0.0.8
| | +-- run-async@2.3.0
| | | `-- is-promise@2.1.0
| | +-- rxjs@6.5.4 deduped
| | +-- string-width@4.2.0
| | | +-- emoji-regex@8.0.0
| | | +-- is-fullwidth-code-point@3.0.0
| | | `-- strip-ansi@6.0.0
| | |   `-- ansi-regex@5.0.0
| | +-- strip-ansi@5.2.0
| | | `-- ansi-regex@4.1.0
| | `-- through@2.3.8
| +-- npm-package-arg@6.1.0
| | +-- hosted-git-info@2.8.5
| | +-- osenv@0.1.5
| | | +-- os-homedir@1.0.2
| | | `-- os-tmpdir@1.0.2 deduped
| | +-- semver@5.7.1
| | `-- validate-npm-package-name@3.0.0
| |   `-- builtins@1.0.3
| +-- npm-pick-manifest@3.0.2
| | +-- figgy-pudding@3.5.1 deduped
| | +-- npm-package-arg@6.1.0 deduped
| | `-- semver@5.7.1
| +-- open@6.4.0
| | `-- is-wsl@1.1.0 deduped
| +-- pacote@9.5.5
| | +-- bluebird@3.5.5 deduped
| | +-- cacache@12.0.3 deduped
| | +-- figgy-pudding@3.5.1 deduped
| | +-- get-stream@4.1.0
| | | `-- pump@3.0.0 deduped
| | +-- glob@7.1.3 deduped
| | +-- infer-owner@1.0.4 deduped
| | +-- lru-cache@5.1.1 deduped
| | +-- make-fetch-happen@5.0.2
| | | +-- agentkeepalive@3.5.2
| | | | `-- humanize-ms@1.2.1
| | | |   `-- ms@2.0.0 deduped
| | | +-- cacache@12.0.3 deduped
| | | +-- http-cache-semantics@3.8.1
| | | +-- http-proxy-agent@2.1.0
| | | | +-- agent-base@4.3.0 deduped
| | | | `-- debug@3.1.0
| | | |   `-- ms@2.0.0 deduped
| | | +-- https-proxy-agent@2.2.4 deduped
| | | +-- lru-cache@5.1.1 deduped
| | | +-- mississippi@3.0.0 deduped
| | | +-- node-fetch-npm@2.0.2
| | | | +-- encoding@0.1.12
| | | | | `-- iconv-lite@0.4.24 deduped
| | | | +-- json-parse-better-errors@1.0.2 deduped
| | | | `-- safe-buffer@5.1.2 deduped
| | | +-- promise-retry@1.1.1 deduped
| | | +-- socks-proxy-agent@4.0.2
| | | | +-- agent-base@4.2.1
| | | | | `-- es6-promisify@5.0.0 deduped
| | | | `-- socks@2.3.3
| | | |   +-- ip@1.1.5 deduped
| | | |   `-- smart-buffer@4.1.0
| | | `-- ssri@6.0.1 deduped
| | +-- minimatch@3.0.4 deduped
| | +-- minipass@2.9.0
| | | +-- safe-buffer@5.1.2 deduped
| | | `-- yallist@3.0.3 deduped
| | +-- mississippi@3.0.0 deduped
| | +-- mkdirp@0.5.1 deduped
| | +-- normalize-package-data@2.5.0
| | | +-- hosted-git-info@2.8.5 deduped
| | | +-- resolve@1.11.0 deduped
| | | +-- semver@5.7.1
| | | `-- validate-npm-package-license@3.0.4
| | |   +-- spdx-correct@3.1.0
| | |   | +-- spdx-expression-parse@3.0.0 deduped
| | |   | `-- spdx-license-ids@3.0.5
| | |   `-- spdx-expression-parse@3.0.0
| | |     +-- spdx-exceptions@2.2.0
| | |     `-- spdx-license-ids@3.0.5 deduped
| | +-- npm-package-arg@6.1.0 deduped
| | +-- npm-packlist@1.4.8
| | | +-- ignore-walk@3.0.3
| | | | `-- minimatch@3.0.4 deduped
| | | +-- npm-bundled@1.1.1
| | | | `-- npm-normalize-package-bin@1.0.1 deduped
| | | `-- npm-normalize-package-bin@1.0.1
| | +-- npm-pick-manifest@2.2.3
| | | +-- figgy-pudding@3.5.1 deduped
| | | +-- npm-package-arg@6.1.0 deduped
| | | `-- semver@5.7.1 deduped
| | +-- npm-registry-fetch@4.0.7
| | | +-- bluebird@3.5.5 deduped
| | | +-- figgy-pudding@3.5.1 deduped
| | | +-- JSONStream@1.3.5
| | | | +-- jsonparse@1.3.1
| | | | `-- through@2.3.8 deduped
| | | +-- lru-cache@5.1.1 deduped
| | | +-- make-fetch-happen@5.0.2 deduped
| | | +-- npm-package-arg@6.1.0 deduped
| | | `-- safe-buffer@5.2.1
| | +-- osenv@0.1.5 deduped
| | +-- promise-inflight@1.0.1 deduped
| | +-- promise-retry@1.1.1
| | | +-- err-code@1.1.2
| | | `-- retry@0.10.1
| | +-- protoduck@5.0.1
| | | `-- genfun@5.0.0
| | +-- rimraf@2.6.3 deduped
| | +-- safe-buffer@5.1.2 deduped
| | +-- semver@5.7.1
| | +-- ssri@6.0.1 deduped
| | +-- tar@4.4.13
| | | +-- chownr@1.1.1 deduped
| | | +-- fs-minipass@1.2.7
| | | | `-- minipass@2.9.0 deduped
| | | +-- minipass@2.9.0 deduped
| | | +-- minizlib@1.3.3
| | | | `-- minipass@2.9.0 deduped
| | | +-- mkdirp@0.5.1 deduped
| | | +-- safe-buffer@5.1.2 deduped
| | | `-- yallist@3.0.3 deduped
| | +-- unique-filename@1.1.1 deduped
| | `-- which@1.3.1 deduped
| +-- read-package-tree@5.3.1
| | +-- read-package-json@2.1.1
| | | +-- glob@7.1.3 deduped
| | | +-- graceful-fs@4.1.15 deduped
| | | +-- json-parse-better-errors@1.0.2 deduped
| | | +-- normalize-package-data@2.5.0 deduped
| | | `-- npm-normalize-package-bin@1.0.1 deduped
| | +-- readdir-scoped-modules@1.1.0
| | | +-- debuglog@1.0.1
| | | +-- dezalgo@1.0.3
| | | | +-- asap@2.0.6 deduped
| | | | `-- wrappy@1.0.2 deduped
| | | +-- graceful-fs@4.1.15 deduped
| | | `-- once@1.4.0 deduped
| | `-- util-promisify@2.1.0
| |   `-- object.getownpropertydescriptors@2.1.0
| |     +-- define-properties@1.1.3
| |     | `-- object-keys@1.1.1 deduped
| |     `-- es-abstract@1.17.4
| |       +-- es-to-primitive@1.2.1
| |       | +-- is-callable@1.1.5 deduped
| |       | +-- is-date-object@1.0.2 deduped
| |       | `-- is-symbol@1.0.3
| |       |   `-- has-symbols@1.0.1 deduped
| |       +-- function-bind@1.1.1 deduped
| |       +-- has@1.0.3 deduped
| |       +-- has-symbols@1.0.1 deduped
| |       +-- is-callable@1.1.5
| |       +-- is-regex@1.0.5 deduped
| |       +-- object-inspect@1.7.0
| |       +-- object-keys@1.1.1 deduped
| |       +-- object.assign@4.1.0 deduped
| |       +-- string.prototype.trimleft@2.1.1
| |       | +-- define-properties@1.1.3 deduped
| |       | `-- function-bind@1.1.1 deduped
| |       `-- string.prototype.trimright@2.1.1
| |         +-- define-properties@1.1.3 deduped
| |         `-- function-bind@1.1.1 deduped
| +-- rimraf@3.0.0
| | `-- glob@7.1.3 deduped
| +-- semver@6.3.0
| +-- symbol-observable@1.2.0
| +-- universal-analytics@0.4.20
| | +-- debug@3.2.6
| | | `-- ms@2.1.2
| | +-- request@2.88.0 deduped
| | `-- uuid@3.3.2 deduped
| `-- uuid@3.3.2
+-- UNMET PEER DEPENDENCY @angular/common@8.2.14
| `-- tslib@1.10.0
+-- UNMET PEER DEPENDENCY @angular/compiler@8.2.14
| `-- tslib@1.10.0 deduped
+-- UNMET PEER DEPENDENCY @angular/compiler-cli@8.2.14
| +-- canonical-path@1.0.0
| +-- chokidar@2.1.8
| | +-- anymatch@2.0.0 deduped
| | +-- async-each@1.0.3 deduped
| | +-- braces@2.3.2 deduped
| | +-- fsevents@1.2.9 deduped
| | +-- glob-parent@3.1.0 deduped
| | +-- inherits@2.0.3 deduped
| | +-- is-binary-path@1.0.1 deduped
| | +-- is-glob@4.0.1 deduped
| | +-- normalize-path@3.0.0
| | +-- path-is-absolute@1.0.1 deduped
| | +-- readdirp@2.2.1 deduped
| | `-- upath@1.1.2 deduped
| +-- convert-source-map@1.7.0
| | `-- safe-buffer@5.1.2 deduped
| +-- dependency-graph@0.7.2
| +-- magic-string@0.25.3
| | `-- sourcemap-codec@1.4.4
| +-- minimist@1.2.0
| +-- reflect-metadata@0.1.13
| +-- source-map@0.6.1
| +-- tslib@1.10.0 deduped
| `-- yargs@13.1.0
|   +-- cliui@4.1.0
|   | +-- string-width@2.1.1 deduped
|   | +-- strip-ansi@4.0.0
|   | | `-- ansi-regex@3.0.0
|   | `-- wrap-ansi@2.1.0
|   |   +-- string-width@1.0.2
|   |   | +-- code-point-at@1.1.0
|   |   | +-- is-fullwidth-code-point@1.0.0
|   |   | | `-- number-is-nan@1.0.1
|   |   | `-- strip-ansi@3.0.1 deduped
|   |   `-- strip-ansi@3.0.1 deduped
|   +-- find-up@3.0.0
|   | `-- locate-path@3.0.0
|   |   +-- p-locate@3.0.0
|   |   | `-- p-limit@2.2.2 deduped
|   |   `-- path-exists@3.0.0
|   +-- get-caller-file@2.0.5
|   +-- os-locale@3.1.0
|   | +-- execa@1.0.0
|   | | +-- cross-spawn@6.0.5
|   | | | +-- nice-try@1.0.5
|   | | | +-- path-key@2.0.1
|   | | | +-- semver@5.7.1
|   | | | +-- shebang-command@1.2.0
|   | | | | `-- shebang-regex@1.0.0
|   | | | `-- which@1.3.1 deduped
|   | | +-- get-stream@4.1.0 deduped
|   | | +-- is-stream@1.1.0
|   | | +-- npm-run-path@2.0.2
|   | | | `-- path-key@2.0.1 deduped
|   | | +-- p-finally@1.0.0
|   | | +-- signal-exit@3.0.2 deduped
|   | | `-- strip-eof@1.0.0
|   | +-- lcid@2.0.0
|   | | `-- invert-kv@2.0.0
|   | `-- mem@4.3.0
|   |   +-- map-age-cleaner@0.1.3
|   |   | `-- p-defer@1.0.0
|   |   +-- mimic-fn@2.1.0
|   |   `-- p-is-promise@2.1.0
|   +-- require-directory@2.1.1
|   +-- require-main-filename@2.0.0
|   +-- set-blocking@2.0.0
|   +-- string-width@3.1.0
|   | +-- emoji-regex@7.0.3
|   | +-- is-fullwidth-code-point@2.0.0
|   | `-- strip-ansi@5.2.0
|   |   `-- ansi-regex@4.1.0
|   +-- which-module@2.0.0
|   +-- y18n@4.0.0 deduped
|   `-- yargs-parser@13.1.1
|     +-- camelcase@5.3.1
|     `-- decamelize@1.2.0 deduped
+-- UNMET PEER DEPENDENCY @angular/core@8.2.14
| `-- tslib@1.10.0 deduped
+-- UNMET PEER DEPENDENCY @angular/forms@8.2.14
| `-- tslib@1.10.0 deduped
+-- @angular/http@7.2.16
| `-- tslib@1.10.0 deduped
+-- @angular/language-service@8.2.14
+-- UNMET PEER DEPENDENCY @angular/platform-browser@8.2.14
| `-- tslib@1.10.0 deduped
+-- UNMET PEER DEPENDENCY @angular/platform-browser-dynamic@8.2.14
| `-- tslib@1.10.0 deduped
+-- UNMET PEER DEPENDENCY @angular/router@8.2.14
| `-- tslib@1.10.0 deduped
+-- @ionic-native/core@5.8.0
| `-- @types/cordova@0.0.34
+-- @ionic-native/splash-screen@5.8.0
| `-- @types/cordova@0.0.34 deduped
+-- @ionic-native/status-bar@5.8.0
| `-- @types/cordova@0.0.34 deduped
+-- @ionic/angular@4.5.0
| +-- @ionic/core@4.5.0
| | `-- ionicons@4.5.8
| `-- tslib@1.10.0 deduped
+-- @ionic/angular-toolkit@1.4.1
| +-- @schematics/angular@7.3.9
| | +-- @angular-devkit/core@7.3.9
| | | +-- ajv@6.9.1
| | | | +-- fast-deep-equal@2.0.1 deduped
| | | | +-- fast-json-stable-stringify@2.0.0 deduped
| | | | +-- json-schema-traverse@0.4.1 deduped
| | | | `-- uri-js@4.2.2 deduped
| | | +-- chokidar@2.0.4 deduped
| | | +-- fast-json-stable-stringify@2.0.0 deduped
| | | +-- rxjs@6.3.3
| | | | `-- tslib@1.10.0 deduped
| | | `-- source-map@0.7.3 deduped
| | +-- @angular-devkit/schematics@7.3.9
| | | +-- @angular-devkit/core@7.3.9 deduped
| | | `-- rxjs@6.3.3
| | |   `-- tslib@1.10.0 deduped
| | `-- typescript@3.2.4
| +-- tslib@1.10.0 deduped
| `-- typescript@3.5.2
+-- @types/jasmine@2.8.16
+-- @types/jasminewd2@2.0.6
| `-- @types/jasmine@2.8.16 deduped
+-- @types/node@10.12.30
+-- @typescript-eslint/eslint-plugin@2.20.0
| +-- @typescript-eslint/experimental-utils@2.20.0
| | +-- @types/json-schema@7.0.4
| | +-- @typescript-eslint/typescript-estree@2.20.0 deduped
| | `-- eslint-scope@5.0.0
| |   +-- esrecurse@4.2.1 deduped
| |   `-- estraverse@4.3.0 deduped
| +-- UNMET PEER DEPENDENCY eslint@*
| +-- eslint-utils@1.4.3
| | `-- eslint-visitor-keys@1.1.0 deduped
| +-- functional-red-black-tree@1.0.1
| +-- regexpp@3.0.0
| `-- tsutils@3.17.1
|   `-- tslib@1.10.0 deduped
+-- @typescript-eslint/parser@2.20.0
| +-- @types/eslint-visitor-keys@1.0.0
| +-- @typescript-eslint/experimental-utils@2.20.0 deduped
| +-- @typescript-eslint/typescript-estree@2.20.0
| | +-- debug@4.1.1
| | | `-- ms@2.1.2
| | +-- eslint-visitor-keys@1.1.0 deduped
| | +-- glob@7.1.6
| | | +-- fs.realpath@1.0.0 deduped
| | | +-- inflight@1.0.6 deduped
| | | +-- inherits@2.0.3 deduped
| | | +-- minimatch@3.0.4 deduped
| | | +-- once@1.4.0 deduped
| | | `-- path-is-absolute@1.0.1 deduped
| | +-- is-glob@4.0.1 deduped
| | +-- lodash@4.17.20 deduped
| | +-- semver@6.3.0
| | `-- tsutils@3.17.1
| |   `-- tslib@1.10.0 deduped
| +-- UNMET PEER DEPENDENCY eslint@*
| `-- eslint-visitor-keys@1.1.0
+-- codelyzer@4.5.0
| +-- app-root-path@2.2.1
| +-- css-selector-tokenizer@0.7.1
| | +-- cssesc@0.1.0
| | +-- fastparse@1.1.2
| | `-- regexpu-core@1.0.0
| |   +-- regenerate@1.4.0
| |   +-- regjsgen@0.2.0
| |   `-- regjsparser@0.1.5
| |     `-- jsesc@0.5.0
| +-- cssauron@1.4.0
| | `-- through@2.3.8 deduped
| +-- semver-dsl@1.0.1
| | `-- semver@5.7.0
| +-- source-map@0.5.7
| `-- sprintf-js@1.1.2
+-- core-js@2.6.9
+-- UNMET PEER DEPENDENCY eslint@^5.0.0 || ^6.0.0
+-- jasmine-core@2.99.1
+-- jasmine-spec-reporter@4.2.1
| `-- colors@1.1.2
+-- karma@3.1.4
| +-- bluebird@3.5.5
| +-- body-parser@1.19.0
| | +-- bytes@3.1.0
| | +-- content-type@1.0.4
| | +-- debug@2.6.9 deduped
| | +-- depd@1.1.2
| | +-- http-errors@1.7.2
| | | +-- depd@1.1.2 deduped
| | | +-- inherits@2.0.3 deduped
| | | +-- setprototypeof@1.1.1 deduped
| | | +-- statuses@1.5.0 deduped
| | | `-- toidentifier@1.0.0
| | +-- iconv-lite@0.4.24
| | | `-- safer-buffer@2.1.2
| | +-- on-finished@2.3.0
| | | `-- ee-first@1.1.1
| | +-- qs@6.7.0
| | +-- raw-body@2.4.0
| | | +-- bytes@3.1.0
| | | +-- http-errors@1.7.2 deduped
| | | +-- iconv-lite@0.4.24 deduped
| | | `-- unpipe@1.0.0
| | `-- type-is@1.6.18
| |   +-- media-typer@0.3.0
| |   `-- mime-types@2.1.24 deduped
| +-- chokidar@2.0.4 deduped
| +-- colors@1.1.2 deduped
| +-- combine-lists@1.0.1
| | `-- lodash@4.17.20 deduped
| +-- connect@3.7.0
| | +-- debug@2.6.9 deduped
| | +-- finalhandler@1.1.2
| | | +-- debug@2.6.9 deduped
| | | +-- encodeurl@1.0.2 deduped
| | | +-- escape-html@1.0.3 deduped
| | | +-- on-finished@2.3.0 deduped
| | | +-- parseurl@1.3.3 deduped
| | | +-- statuses@1.5.0 deduped
| | | `-- unpipe@1.0.0 deduped
| | +-- parseurl@1.3.3
| | `-- utils-merge@1.0.1
| +-- core-js@2.6.9 deduped
| +-- di@0.0.1
| +-- dom-serialize@2.2.1
| | +-- custom-event@1.0.1
| | +-- ent@2.2.0
| | +-- extend@3.0.2
| | `-- void-elements@2.0.1
| +-- expand-braces@0.1.2
| | +-- array-slice@0.2.3
| | +-- array-unique@0.2.1
| | `-- braces@0.1.5
| |   `-- expand-range@0.1.1
| |     +-- is-number@0.1.1
| |     `-- repeat-string@0.2.2
| +-- flatted@2.0.0
| +-- glob@7.1.3
| | +-- fs.realpath@1.0.0 deduped
| | +-- inflight@1.0.6 deduped
| | +-- inherits@2.0.3 deduped
| | +-- minimatch@3.0.4 deduped
| | +-- once@1.4.0 deduped
| | `-- path-is-absolute@1.0.1 deduped
| +-- graceful-fs@4.1.15
| +-- http-proxy@1.18.1
| | +-- eventemitter3@4.0.7
| | +-- follow-redirects@1.7.0
| | | `-- debug@3.2.6
| | |   `-- ms@2.1.2
| | `-- requires-port@1.0.0
| +-- isbinaryfile@3.0.3
| | `-- buffer-alloc@1.2.0
| |   +-- buffer-alloc-unsafe@1.1.0
| |   `-- buffer-fill@1.0.0
| +-- lodash@4.17.20
| +-- log4js@3.0.6
| | +-- circular-json@0.5.9
| | +-- date-format@1.2.0
| | +-- debug@3.2.6
| | | `-- ms@2.1.2
| | +-- rfdc@1.1.4
| | `-- streamroller@0.7.0
| |   +-- date-format@1.2.0 deduped
| |   +-- debug@3.2.6
| |   | `-- ms@2.1.2
| |   +-- mkdirp@0.5.1 deduped
| |   `-- readable-stream@2.3.6 deduped
| +-- mime@2.4.4
| +-- minimatch@3.0.4 deduped
| +-- optimist@0.6.1
| | +-- minimist@0.0.10
| | `-- wordwrap@0.0.3
| +-- qjobs@1.2.0
| +-- range-parser@1.2.1
| +-- rimraf@2.6.3
| | `-- glob@7.1.3 deduped
| +-- safe-buffer@5.1.2
| +-- socket.io@2.1.1
| | +-- debug@3.1.0
| | | `-- ms@2.0.0 deduped
| | +-- engine.io@3.2.1
| | | +-- accepts@1.3.7 deduped
| | | +-- base64id@1.0.0
| | | +-- cookie@0.3.1
| | | +-- debug@3.1.0
| | | | `-- ms@2.0.0 deduped
| | | +-- engine.io-parser@2.1.3
| | | | +-- after@0.8.2
| | | | +-- arraybuffer.slice@0.0.7
| | | | +-- base64-arraybuffer@0.1.5 deduped
| | | | +-- blob@0.0.5
| | | | `-- has-binary2@1.0.3 deduped
| | | `-- ws@3.3.3
| | |   +-- async-limiter@1.0.0 deduped
| | |   +-- safe-buffer@5.1.2 deduped
| | |   `-- ultron@1.1.1
| | +-- has-binary2@1.0.3
| | | `-- isarray@2.0.1
| | +-- socket.io-adapter@1.1.1
| | +-- socket.io-client@2.1.1
| | | +-- backo2@1.0.2
| | | +-- base64-arraybuffer@0.1.5
| | | +-- component-bind@1.0.0
| | | +-- component-emitter@1.2.1
| | | +-- debug@3.1.0
| | | | `-- ms@2.0.0 deduped
| | | +-- engine.io-client@3.2.1
| | | | +-- component-emitter@1.2.1
| | | | +-- component-inherit@0.0.3
| | | | +-- debug@3.1.0
| | | | | `-- ms@2.0.0 deduped
| | | | +-- engine.io-parser@2.1.3 deduped
| | | | +-- has-cors@1.1.0 deduped
| | | | +-- indexof@0.0.1 deduped
| | | | +-- parseqs@0.0.5 deduped
| | | | +-- parseuri@0.0.5 deduped
| | | | +-- ws@3.3.3 deduped
| | | | +-- xmlhttprequest-ssl@1.5.5
| | | | `-- yeast@0.1.2
| | | +-- has-binary2@1.0.3 deduped
| | | +-- has-cors@1.1.0
| | | +-- indexof@0.0.1
| | | +-- object-component@0.0.3
| | | +-- parseqs@0.0.5
| | | | `-- better-assert@1.0.2
| | | |   `-- callsite@1.0.0
| | | +-- parseuri@0.0.5
| | | | `-- better-assert@1.0.2 deduped
| | | +-- socket.io-parser@3.2.0 deduped
| | | `-- to-array@0.1.4
| | `-- socket.io-parser@3.2.0
| |   +-- component-emitter@1.2.1
| |   +-- debug@3.1.0
| |   | `-- ms@2.0.0 deduped
| |   `-- isarray@2.0.1
| +-- source-map@0.6.1
| +-- tmp@0.0.33
| | `-- os-tmpdir@1.0.2
| `-- useragent@2.3.0
|   +-- lru-cache@4.1.5
|   | +-- pseudomap@1.0.2
|   | `-- yallist@2.1.2
|   `-- tmp@0.0.33 deduped
+-- karma-chrome-launcher@2.2.0
| +-- fs-access@1.0.1
| | `-- null-check@1.0.0
| `-- which@1.3.1
|   `-- isexe@2.0.0
+-- karma-coverage-istanbul-reporter@2.0.5
| +-- istanbul-api@2.1.6
| | +-- async@2.6.2 deduped
| | +-- compare-versions@3.4.0
| | +-- fileset@2.0.3
| | | +-- glob@7.1.3 deduped
| | | `-- minimatch@3.0.4 deduped
| | +-- istanbul-lib-coverage@2.0.5
| | +-- istanbul-lib-hook@2.0.7
| | | `-- append-transform@1.0.0
| | |   `-- default-require-extensions@2.0.0
| | |     `-- strip-bom@3.0.0
| | +-- istanbul-lib-instrument@3.3.0
| | | +-- @babel/generator@7.4.4
| | | | +-- @babel/types@7.4.4 deduped
| | | | +-- jsesc@2.5.2
| | | | +-- lodash@4.17.20 deduped
| | | | +-- source-map@0.5.7
| | | | `-- trim-right@1.0.1
| | | +-- @babel/parser@7.4.5
| | | +-- @babel/template@7.4.4
| | | | +-- @babel/code-frame@7.0.0
| | | | | `-- @babel/highlight@7.0.0
| | | | |   +-- chalk@2.4.2 deduped
| | | | |   +-- esutils@2.0.2 deduped
| | | | |   `-- js-tokens@4.0.0
| | | | +-- @babel/parser@7.4.5 deduped
| | | | `-- @babel/types@7.4.4 deduped
| | | +-- @babel/traverse@7.4.5
| | | | +-- @babel/code-frame@7.0.0 deduped
| | | | +-- @babel/generator@7.4.4 deduped
| | | | +-- @babel/helper-function-name@7.1.0
| | | | | +-- @babel/helper-get-function-arity@7.0.0
| | | | | | `-- @babel/types@7.4.4 deduped
| | | | | +-- @babel/template@7.4.4 deduped
| | | | | `-- @babel/types@7.4.4 deduped
| | | | +-- @babel/helper-split-export-declaration@7.4.4
| | | | | `-- @babel/types@7.4.4 deduped
| | | | +-- @babel/parser@7.4.5 deduped
| | | | +-- @babel/types@7.4.4 deduped
| | | | +-- debug@4.1.1
| | | | | `-- ms@2.1.2
| | | | +-- globals@11.12.0
| | | | `-- lodash@4.17.20 deduped
| | | +-- @babel/types@7.4.4
| | | | +-- esutils@2.0.2 deduped
| | | | +-- lodash@4.17.20 deduped
| | | | `-- to-fast-properties@2.0.0
| | | +-- istanbul-lib-coverage@2.0.5 deduped
| | | `-- semver@6.0.0 deduped
| | +-- istanbul-lib-report@2.0.8
| | | +-- istanbul-lib-coverage@2.0.5
| | | +-- make-dir@2.1.0 deduped
| | | `-- supports-color@6.1.0 deduped
| | +-- istanbul-lib-source-maps@3.0.6
| | | +-- debug@4.1.1
| | | | `-- ms@2.1.2
| | | +-- istanbul-lib-coverage@2.0.5
| | | +-- make-dir@2.1.0 deduped
| | | +-- rimraf@2.6.3 deduped
| | | `-- source-map@0.6.1
| | +-- istanbul-reports@2.2.6
| | | `-- handlebars@4.7.3
| | |   +-- neo-async@2.6.1 deduped
| | |   +-- optimist@0.6.1 deduped
| | |   +-- source-map@0.6.1
| | |   `-- uglify-js@3.6.0
| | |     +-- commander@2.20.0 deduped
| | |     `-- source-map@0.6.1
| | +-- js-yaml@3.13.1 deduped
| | +-- make-dir@2.1.0
| | | +-- pify@4.0.1 deduped
| | | `-- semver@5.7.0
| | +-- minimatch@3.0.4 deduped
| | `-- once@1.4.0 deduped
| `-- minimatch@3.0.4 deduped
+-- karma-jasmine@1.1.2
+-- karma-jasmine-html-reporter@0.2.2
| `-- karma-jasmine@1.1.2 deduped
+-- protractor@5.4.2
| +-- @types/q@0.0.32
| +-- @types/selenium-webdriver@3.0.16
| +-- blocking-proxy@1.0.1
| | `-- minimist@1.2.0 deduped
| +-- browserstack@1.5.2
| | `-- https-proxy-agent@2.2.4
| |   +-- agent-base@4.3.0
| |   | `-- es6-promisify@5.0.0
| |   |   `-- es6-promise@4.2.8
| |   `-- debug@3.2.6
| |     `-- ms@2.1.2
| +-- chalk@1.1.3
| | +-- ansi-styles@2.2.1
| | +-- escape-string-regexp@1.0.5
| | +-- has-ansi@2.0.0
| | | `-- ansi-regex@2.1.1 deduped
| | +-- strip-ansi@3.0.1 deduped
| | `-- supports-color@2.0.0
| +-- glob@7.1.3 deduped
| +-- jasmine@2.8.0
| | +-- exit@0.1.2
| | +-- glob@7.1.3 deduped
| | `-- jasmine-core@2.8.0
| +-- jasminewd2@2.2.0
| +-- optimist@0.6.1 deduped
| +-- q@1.4.1
| +-- saucelabs@1.5.0
| | `-- https-proxy-agent@2.2.4 deduped
| +-- selenium-webdriver@3.6.0
| | +-- jszip@3.2.1
| | | +-- lie@3.3.0
| | | | `-- immediate@3.0.6
| | | +-- pako@1.0.10
| | | +-- readable-stream@2.3.6 deduped
| | | `-- set-immediate-shim@1.0.1
| | +-- rimraf@2.6.3 deduped
| | +-- tmp@0.0.30
| | | `-- os-tmpdir@1.0.2 deduped
| | `-- xml2js@0.4.19 deduped
| +-- source-map-support@0.4.18
| | `-- source-map@0.5.7
| +-- webdriver-js-extender@2.1.0
| | +-- @types/selenium-webdriver@3.0.16 deduped
| | `-- selenium-webdriver@3.6.0 deduped
| `-- webdriver-manager@12.1.5
|   +-- adm-zip@0.4.13
|   +-- chalk@1.1.3 deduped
|   +-- del@2.2.2
|   | +-- globby@5.0.0
|   | | +-- array-union@1.0.2 deduped
|   | | +-- arrify@1.0.1
|   | | +-- glob@7.1.3 deduped
|   | | +-- object-assign@4.1.1 deduped
|   | | +-- pify@2.3.0 deduped
|   | | `-- pinkie-promise@2.0.1 deduped
|   | +-- is-path-cwd@1.0.0
|   | +-- is-path-in-cwd@1.0.1
|   | | `-- is-path-inside@1.0.1
|   | |   `-- path-is-inside@1.0.2 deduped
|   | +-- object-assign@4.1.1 deduped
|   | +-- pify@2.3.0
|   | +-- pinkie-promise@2.0.1
|   | | `-- pinkie@2.0.4
|   | `-- rimraf@2.6.3 deduped
|   +-- glob@7.1.3 deduped
|   +-- ini@1.3.5 deduped
|   +-- minimist@1.2.0 deduped
|   +-- q@1.4.1 deduped
|   +-- request@2.88.0 deduped
|   +-- rimraf@2.6.3 deduped
|   +-- semver@5.7.0
|   `-- xml2js@0.4.19
|     +-- sax@1.2.4
|     `-- xmlbuilder@9.0.7
+-- rxjs@6.5.4
| `-- tslib@1.10.0 deduped
+-- ts-node@8.0.3
| +-- arg@4.1.0
| +-- diff@3.5.0
| +-- make-error@1.3.5
| +-- source-map-support@0.5.12
| | +-- buffer-from@1.1.1 deduped
| | `-- source-map@0.6.1
| `-- yn@3.1.0
+-- tslint@5.12.1
| +-- babel-code-frame@6.26.0
| | +-- chalk@1.1.3
| | | +-- ansi-styles@2.2.1
| | | +-- escape-string-regexp@1.0.5 deduped
| | | +-- has-ansi@2.0.0 deduped
| | | +-- strip-ansi@3.0.1 deduped
| | | `-- supports-color@2.0.0
| | +-- esutils@2.0.2
| | `-- js-tokens@3.0.2
| +-- builtin-modules@1.1.1
| +-- chalk@2.4.2
| | +-- ansi-styles@3.2.1
| | | `-- color-convert@1.9.3
| | |   `-- color-name@1.1.3
| | +-- escape-string-regexp@1.0.5 deduped
| | `-- supports-color@5.5.0
| |   `-- has-flag@3.0.0 deduped
| +-- commander@2.20.0
| +-- diff@3.5.0 deduped
| +-- glob@7.1.3 deduped
| +-- js-yaml@3.13.1
| | +-- argparse@1.0.10
| | | `-- sprintf-js@1.0.3
| | `-- esprima@4.0.1
| +-- minimatch@3.0.4 deduped
| +-- resolve@1.11.0
| | `-- path-parse@1.0.6
| +-- semver@5.7.0
| +-- tslib@1.10.0 deduped
| `-- tsutils@2.29.0
|   `-- tslib@1.10.0 deduped
+-- typescript@3.5.3

```

## Back-end dependencies

```

+-- @types/bcryptjs@2.4.2
+-- @types/bluebird@3.5.26
+-- @types/cors@2.8.6
| `-- @types/express@4.16.1 deduped
+-- @types/express@4.16.1
| +-- @types/body-parser@1.17.0
| | +-- @types/connect@3.4.32
| | | `-- @types/node@11.11.3 deduped
| | `-- @types/node@11.11.3 deduped
| +-- @types/express-serve-static-core@4.16.2
| | +-- @types/node@11.11.3 deduped
| | `-- @types/range-parser@1.2.3
| `-- @types/serve-static@1.13.2
|   +-- @types/express-serve-static-core@4.16.2 deduped
|   `-- @types/mime@2.0.1
+-- @types/jsonwebtoken@8.3.2
| `-- @types/node@11.11.3 deduped
+-- @types/node@11.11.3
+-- @types/sequelize@4.28.14
| +-- @types/bluebird@3.5.26 deduped
| +-- @types/continuation-local-storage@3.2.4
| | `-- @types/node@11.11.3 deduped
| +-- @types/lodash@4.14.186
| `-- @types/validator@13.7.9 deduped
+-- @types/validator@13.7.9
+-- @typescript-eslint/eslint-plugin@2.19.2
| +-- @typescript-eslint/experimental-utils@2.19.2
| | +-- @types/json-schema@7.0.4
| | +-- @typescript-eslint/typescript-estree@2.19.2 deduped
| | `-- eslint-scope@5.0.0 deduped
| +-- eslint-utils@1.4.3
| | `-- eslint-visitor-keys@1.1.0 deduped
| +-- functional-red-black-tree@1.0.1
| +-- regexpp@3.0.0
| `-- tsutils@3.17.1
|   `-- tslib@1.10.0
+-- @typescript-eslint/parser@2.19.2
| +-- @types/eslint-visitor-keys@1.0.0
| +-- @typescript-eslint/experimental-utils@2.19.2 deduped
| +-- @typescript-eslint/typescript-estree@2.19.2
| | +-- debug@4.1.1
| | | `-- ms@2.1.2
| | +-- eslint-visitor-keys@1.1.0 deduped
| | +-- glob@7.1.6
| | | +-- fs.realpath@1.0.0 deduped
| | | +-- inflight@1.0.6 deduped
| | | +-- inherits@2.0.3 deduped
| | | +-- minimatch@3.0.4 deduped
| | | +-- once@1.4.0 deduped
| | | `-- path-is-absolute@1.0.1 deduped
| | +-- is-glob@4.0.1 deduped
| | +-- lodash@4.17.15
| | +-- semver@6.3.0
| | `-- tsutils@3.17.1 deduped
| `-- eslint-visitor-keys@1.1.0
+-- aws-sdk@2.429.0
| +-- buffer@4.9.1
| | +-- base64-js@1.3.0
| | +-- ieee754@1.1.8 deduped
| | `-- isarray@1.0.0
| +-- events@1.1.1
| +-- ieee754@1.1.8
| +-- jmespath@0.15.0
| +-- querystring@0.2.0
| +-- sax@1.2.1
| +-- url@0.10.3
| | +-- punycode@1.3.2
| | `-- querystring@0.2.0 deduped
| +-- uuid@3.3.2
| `-- xml2js@0.4.19
|   +-- sax@1.2.1 deduped
|   `-- xmlbuilder@9.0.7
+-- bcryptjs@2.4.3
+-- body-parser@1.18.3
| +-- bytes@3.0.0
| +-- content-type@1.0.4
| +-- debug@2.6.9
| | `-- ms@2.0.0
| +-- depd@1.1.2
| +-- http-errors@1.6.3
| | +-- depd@1.1.2 deduped
| | +-- inherits@2.0.3
| | +-- setprototypeof@1.1.0 deduped
| | `-- statuses@1.4.0 deduped
| +-- iconv-lite@0.4.23
| | `-- safer-buffer@2.1.2
| +-- on-finished@2.3.0
| | `-- ee-first@1.1.1
| +-- qs@6.5.2
| +-- raw-body@2.3.3
| | +-- bytes@3.0.0 deduped
| | +-- http-errors@1.6.3 deduped
| | +-- iconv-lite@0.4.23 deduped
| | `-- unpipe@1.0.0
| `-- type-is@1.6.16
|   +-- media-typer@0.3.0
|   `-- mime-types@2.1.22
|     `-- mime-db@1.38.0
+-- chai@4.2.0
| +-- assertion-error@1.1.0
| +-- check-error@1.0.2
| +-- deep-eql@3.0.1
| | `-- type-detect@4.0.8 deduped
| +-- get-func-name@2.0.0
| +-- pathval@1.1.0
| `-- type-detect@4.0.8
+-- chai-http@4.2.1
| +-- @types/chai@4.1.7
| +-- @types/superagent@3.8.7
| | +-- @types/cookiejar@2.1.1
| | `-- @types/node@11.11.3 deduped
| +-- cookiejar@2.1.2
| +-- is-ip@2.0.0
| | `-- ip-regex@2.1.0
| +-- methods@1.1.2
| +-- qs@6.5.2 deduped
| `-- superagent@3.8.3
|   +-- component-emitter@1.2.1
|   +-- cookiejar@2.1.2 deduped
|   +-- debug@3.2.6
|   | `-- ms@2.1.1
|   +-- extend@3.0.2
|   +-- form-data@2.3.3
|   | +-- asynckit@0.4.0
|   | +-- combined-stream@1.0.7
|   | | `-- delayed-stream@1.0.0
|   | `-- mime-types@2.1.22 deduped
|   +-- formidable@1.2.1
|   +-- methods@1.1.2 deduped
|   +-- mime@1.4.1
|   +-- qs@6.5.2 deduped
|   `-- readable-stream@2.3.6
|     +-- core-util-is@1.0.2
|     +-- inherits@2.0.3 deduped
|     +-- isarray@1.0.0 deduped
|     +-- process-nextick-args@2.0.0
|     +-- safe-buffer@5.1.2 deduped
|     +-- string_decoder@1.1.1
|     | `-- safe-buffer@5.1.2 deduped
|     `-- util-deprecate@1.0.2
+-- cors@2.8.5
| +-- object-assign@4.1.1
| `-- vary@1.1.2
+-- dotenv@8.6.0
+-- email-validator@2.0.4
+-- eslint@6.8.0
| +-- @babel/code-frame@7.8.3
| | `-- @babel/highlight@7.8.3
| |   +-- chalk@2.4.2 deduped
| |   +-- esutils@2.0.3 deduped
| |   `-- js-tokens@4.0.0
| +-- ajv@6.11.0
| | +-- fast-deep-equal@3.1.1
| | +-- fast-json-stable-stringify@2.1.0
| | +-- json-schema-traverse@0.4.1
| | `-- uri-js@4.2.2
| |   `-- punycode@2.1.1
| +-- chalk@2.4.2
| | +-- ansi-styles@3.2.1
| | | `-- color-convert@1.9.3
| | |   `-- color-name@1.1.3
| | +-- escape-string-regexp@1.0.5 deduped
| | `-- supports-color@5.5.0
| |   `-- has-flag@3.0.0 deduped
| +-- cross-spawn@6.0.5
| | +-- nice-try@1.0.5
| | +-- path-key@2.0.1
| | +-- semver@5.6.0 deduped
| | +-- shebang-command@1.2.0
| | | `-- shebang-regex@1.0.0
| | `-- which@1.3.1 deduped
| +-- debug@4.1.1
| | `-- ms@2.1.2
| +-- doctrine@3.0.0
| | `-- esutils@2.0.3 deduped
| +-- eslint-scope@5.0.0
| | +-- esrecurse@4.2.1
| | | `-- estraverse@4.3.0 deduped
| | `-- estraverse@4.3.0
| +-- eslint-utils@1.4.3 deduped
| +-- eslint-visitor-keys@1.1.0 deduped
| +-- espree@6.1.2
| | +-- acorn@7.1.0
| | +-- acorn-jsx@5.1.0
| | `-- eslint-visitor-keys@1.1.0 deduped
| +-- esquery@1.1.0
| | `-- estraverse@4.3.0 deduped
| +-- esutils@2.0.3
| +-- file-entry-cache@5.0.1
| | `-- flat-cache@2.0.1
| |   +-- flatted@2.0.1
| |   +-- rimraf@2.6.3 deduped
| |   `-- write@1.0.3
| |     `-- mkdirp@0.5.1 deduped
| +-- functional-red-black-tree@1.0.1 deduped
| +-- glob-parent@5.1.0
| | `-- is-glob@4.0.1 deduped
| +-- globals@12.3.0
| | `-- type-fest@0.8.1
| +-- ignore@4.0.6
| +-- import-fresh@3.2.1
| | +-- parent-module@1.0.1
| | | `-- callsites@3.1.0
| | `-- resolve-from@4.0.0
| +-- imurmurhash@0.1.4
| +-- inquirer@7.0.4
| | +-- ansi-escapes@4.3.0
| | | `-- type-fest@0.8.1 deduped
| | +-- chalk@2.4.2 deduped
| | +-- cli-cursor@3.1.0
| | | `-- restore-cursor@3.1.0
| | |   +-- onetime@5.1.0
| | |   | `-- mimic-fn@2.1.0 deduped
| | |   `-- signal-exit@3.0.2
| | +-- cli-width@2.2.0
| | +-- external-editor@3.1.0
| | | +-- chardet@0.7.0
| | | +-- iconv-lite@0.4.24
| | | | `-- safer-buffer@2.1.2 deduped
| | | `-- tmp@0.0.33
| | |   `-- os-tmpdir@1.0.2
| | +-- figures@3.1.0
| | | `-- escape-string-regexp@1.0.5 deduped
| | +-- lodash@4.17.15
| | +-- mute-stream@0.0.8
| | +-- run-async@2.3.0
| | | `-- is-promise@2.1.0
| | +-- rxjs@6.5.4
| | | `-- tslib@1.10.0 deduped
| | +-- string-width@4.2.0
| | | +-- emoji-regex@8.0.0
| | | +-- is-fullwidth-code-point@3.0.0
| | | `-- strip-ansi@6.0.0
| | |   `-- ansi-regex@5.0.0
| | +-- strip-ansi@5.2.0
| | | `-- ansi-regex@4.1.0
| | `-- through@2.3.8
| +-- is-glob@4.0.1
| | `-- is-extglob@2.1.1
| +-- js-yaml@3.13.1
| | +-- argparse@1.0.10
| | | `-- sprintf-js@1.0.3
| | `-- esprima@4.0.1
| +-- json-stable-stringify-without-jsonify@1.0.1
| +-- levn@0.3.0
| | +-- prelude-ls@1.1.2
| | `-- type-check@0.3.2
| |   `-- prelude-ls@1.1.2 deduped
| +-- lodash@4.17.15
| +-- minimatch@3.0.4
| | `-- brace-expansion@1.1.11
| |   +-- balanced-match@1.0.0
| |   `-- concat-map@0.0.1
| +-- mkdirp@0.5.1
| | `-- minimist@0.0.8
| +-- natural-compare@1.4.0
| +-- optionator@0.8.3
| | +-- deep-is@0.1.3
| | +-- fast-levenshtein@2.0.6
| | +-- levn@0.3.0 deduped
| | +-- prelude-ls@1.1.2 deduped
| | +-- type-check@0.3.2 deduped
| | `-- word-wrap@1.2.3
| +-- progress@2.0.3
| +-- regexpp@2.0.1
| +-- semver@6.3.0
| +-- strip-ansi@5.2.0
| | `-- ansi-regex@4.1.0
| +-- strip-json-comments@3.0.1
| +-- table@5.4.6
| | +-- ajv@6.11.0 deduped
| | +-- lodash@4.17.15
| | +-- slice-ansi@2.1.0
| | | +-- ansi-styles@3.2.1
| | | | `-- color-convert@1.9.3 deduped
| | | +-- astral-regex@1.0.0
| | | `-- is-fullwidth-code-point@2.0.0
| | `-- string-width@3.1.0
| |   +-- emoji-regex@7.0.3
| |   +-- is-fullwidth-code-point@2.0.0 deduped
| |   `-- strip-ansi@5.2.0
| |     `-- ansi-regex@4.1.0
| +-- text-table@0.2.0
| `-- v8-compile-cache@2.1.0
+-- eslint-config-google@0.14.0
+-- express@4.16.4
| +-- accepts@1.3.5
| | +-- mime-types@2.1.22 deduped
| | `-- negotiator@0.6.1
| +-- array-flatten@1.1.1
| +-- body-parser@1.18.3 deduped
| +-- content-disposition@0.5.2
| +-- content-type@1.0.4 deduped
| +-- cookie@0.3.1
| +-- cookie-signature@1.0.6
| +-- debug@2.6.9 deduped
| +-- depd@1.1.2 deduped
| +-- encodeurl@1.0.2
| +-- escape-html@1.0.3
| +-- etag@1.8.1
| +-- finalhandler@1.1.1
| | +-- debug@2.6.9 deduped
| | +-- encodeurl@1.0.2 deduped
| | +-- escape-html@1.0.3 deduped
| | +-- on-finished@2.3.0 deduped
| | +-- parseurl@1.3.2 deduped
| | +-- statuses@1.4.0 deduped
| | `-- unpipe@1.0.0 deduped
| +-- fresh@0.5.2
| +-- merge-descriptors@1.0.1
| +-- methods@1.1.2 deduped
| +-- on-finished@2.3.0 deduped
| +-- parseurl@1.3.2
| +-- path-to-regexp@0.1.7
| +-- proxy-addr@2.0.4
| | +-- forwarded@0.1.2
| | `-- ipaddr.js@1.8.0
| +-- qs@6.5.2 deduped
| +-- range-parser@1.2.0
| +-- safe-buffer@5.1.2
| +-- send@0.16.2
| | +-- debug@2.6.9 deduped
| | +-- depd@1.1.2 deduped
| | +-- destroy@1.0.4
| | +-- encodeurl@1.0.2 deduped
| | +-- escape-html@1.0.3 deduped
| | +-- etag@1.8.1 deduped
| | +-- fresh@0.5.2 deduped
| | +-- http-errors@1.6.3 deduped
| | +-- mime@1.4.1 deduped
| | +-- ms@2.0.0 deduped
| | +-- on-finished@2.3.0 deduped
| | +-- range-parser@1.2.0 deduped
| | `-- statuses@1.4.0 deduped
| +-- serve-static@1.13.2
| | +-- encodeurl@1.0.2 deduped
| | +-- escape-html@1.0.3 deduped
| | +-- parseurl@1.3.2 deduped
| | `-- send@0.16.2 deduped
| +-- setprototypeof@1.1.0
| +-- statuses@1.4.0
| +-- type-is@1.6.16 deduped
| +-- utils-merge@1.0.1
| `-- vary@1.1.2 deduped
+-- jsonwebtoken@8.5.1
| +-- jws@3.2.2
| | +-- jwa@1.4.1
| | | +-- buffer-equal-constant-time@1.0.1
| | | +-- ecdsa-sig-formatter@1.0.11
| | | | `-- safe-buffer@5.1.2 deduped
| | | `-- safe-buffer@5.1.2 deduped
| | `-- safe-buffer@5.1.2 deduped
| +-- lodash.includes@4.3.0
| +-- lodash.isboolean@3.0.3
| +-- lodash.isinteger@4.0.4
| +-- lodash.isnumber@3.0.3
| +-- lodash.isplainobject@4.0.6
| +-- lodash.isstring@4.0.1
| +-- lodash.once@4.1.1
| +-- ms@2.1.1
| `-- semver@5.6.0
+-- mocha@6.1.4
| +-- ansi-colors@3.2.3
| +-- browser-stdout@1.3.1
| +-- debug@3.2.6
| | `-- ms@2.1.1 deduped
| +-- diff@3.5.0
| +-- escape-string-regexp@1.0.5
| +-- find-up@3.0.0
| | `-- locate-path@3.0.0
| |   +-- p-locate@3.0.0
| |   | `-- p-limit@2.2.0
| |   |   `-- p-try@2.2.0
| |   `-- path-exists@3.0.0
| +-- glob@7.1.3
| | +-- fs.realpath@1.0.0
| | +-- inflight@1.0.6
| | | +-- once@1.4.0 deduped
| | | `-- wrappy@1.0.2
| | +-- inherits@2.0.3 deduped
| | +-- minimatch@3.0.4 deduped
| | +-- once@1.4.0
| | | `-- wrappy@1.0.2 deduped
| | `-- path-is-absolute@1.0.1
| +-- growl@1.10.5
| +-- he@1.2.0
| +-- js-yaml@3.13.1 deduped
| +-- log-symbols@2.2.0
| | `-- chalk@2.4.2 deduped
| +-- minimatch@3.0.4 deduped
| +-- mkdirp@0.5.1 deduped
| +-- ms@2.1.1
| +-- node-environment-flags@1.0.5
| | +-- object.getownpropertydescriptors@2.0.3
| | | +-- define-properties@1.1.3 deduped
| | | `-- es-abstract@1.13.0
| | |   +-- es-to-primitive@1.2.0
| | |   | +-- is-callable@1.1.4 deduped
| | |   | +-- is-date-object@1.0.1
| | |   | `-- is-symbol@1.0.2
| | |   |   `-- has-symbols@1.0.0 deduped
| | |   +-- function-bind@1.1.1 deduped
| | |   +-- has@1.0.3
| | |   | `-- function-bind@1.1.1 deduped
| | |   +-- is-callable@1.1.4
| | |   +-- is-regex@1.0.4
| | |   | `-- has@1.0.3 deduped
| | |   `-- object-keys@1.1.1 deduped
| | `-- semver@5.7.0
| +-- object.assign@4.1.0
| | +-- define-properties@1.1.3
| | | `-- object-keys@1.1.1 deduped
| | +-- function-bind@1.1.1
| | +-- has-symbols@1.0.0
| | `-- object-keys@1.1.1
| +-- strip-json-comments@2.0.1
| +-- supports-color@6.0.0
| | `-- has-flag@3.0.0
| +-- which@1.3.1
| | `-- isexe@2.0.0
| +-- wide-align@1.1.3
| | `-- string-width@2.1.1
| |   +-- is-fullwidth-code-point@2.0.0 deduped
| |   `-- strip-ansi@4.0.0
| |     `-- ansi-regex@3.0.0
| +-- yargs@13.2.2
| | +-- cliui@4.1.0
| | | +-- string-width@2.1.1 deduped
| | | +-- strip-ansi@4.0.0
| | | | `-- ansi-regex@3.0.0
| | | `-- wrap-ansi@2.1.0
| | |   +-- string-width@1.0.2
| | |   | +-- code-point-at@1.1.0
| | |   | +-- is-fullwidth-code-point@1.0.0
| | |   | | `-- number-is-nan@1.0.1
| | |   | `-- strip-ansi@3.0.1 deduped
| | |   `-- strip-ansi@3.0.1
| | |     `-- ansi-regex@2.1.1
| | +-- find-up@3.0.0
| | | `-- locate-path@3.0.0 deduped
| | +-- get-caller-file@2.0.5
| | +-- os-locale@3.1.0
| | | +-- execa@1.0.0
| | | | +-- cross-spawn@6.0.5 deduped
| | | | +-- get-stream@4.1.0
| | | | | `-- pump@3.0.0
| | | | |   +-- end-of-stream@1.4.1
| | | | |   | `-- once@1.4.0 deduped
| | | | |   `-- once@1.4.0 deduped
| | | | +-- is-stream@1.1.0
| | | | +-- npm-run-path@2.0.2
| | | | | `-- path-key@2.0.1 deduped
| | | | +-- p-finally@1.0.0
| | | | +-- signal-exit@3.0.2 deduped
| | | | `-- strip-eof@1.0.0
| | | +-- lcid@2.0.0
| | | | `-- invert-kv@2.0.0
| | | `-- mem@4.3.0
| | |   +-- map-age-cleaner@0.1.3
| | |   | `-- p-defer@1.0.0
| | |   +-- mimic-fn@2.1.0
| | |   `-- p-is-promise@2.1.0
| | +-- require-directory@2.1.1
| | +-- require-main-filename@2.0.0
| | +-- set-blocking@2.0.0
| | +-- string-width@3.1.0
| | | +-- emoji-regex@7.0.3 deduped
| | | +-- is-fullwidth-code-point@2.0.0 deduped
| | | `-- strip-ansi@5.2.0
| | |   `-- ansi-regex@4.1.0
| | +-- which-module@2.0.0
| | +-- y18n@4.0.0
| | `-- yargs-parser@13.0.0 deduped
| +-- yargs-parser@13.0.0
| | +-- camelcase@5.3.1
| | `-- decamelize@1.2.0
| `-- yargs-unparser@1.5.0
|   +-- flat@4.1.0
|   | `-- is-buffer@2.0.3
|   +-- lodash@4.17.15
|   `-- yargs@12.0.5
|     +-- cliui@4.1.0 deduped
|     +-- decamelize@1.2.0 deduped
|     +-- find-up@3.0.0
|     | `-- locate-path@3.0.0 deduped
|     +-- get-caller-file@1.0.3
|     +-- os-locale@3.1.0 deduped
|     +-- require-directory@2.1.1 deduped
|     +-- require-main-filename@1.0.1
|     +-- set-blocking@2.0.0 deduped
|     +-- string-width@2.1.1 deduped
|     +-- which-module@2.0.0 deduped
|     +-- y18n@4.0.0 deduped
|     `-- yargs-parser@11.1.1
|       +-- camelcase@5.3.1
|       `-- decamelize@1.2.0 deduped
+-- pg@8.7.3
| +-- buffer-writer@2.0.0
| +-- packet-reader@1.0.0
| +-- pg-connection-string@2.5.0
| +-- pg-pool@3.5.1
| +-- pg-protocol@1.5.0
| +-- pg-types@2.2.0
| | +-- pg-int8@1.0.1
| | +-- postgres-array@2.0.0
| | +-- postgres-bytea@1.0.0
| | +-- postgres-date@1.0.7
| | `-- postgres-interval@1.2.0
| |   `-- xtend@4.0.1 deduped
| `-- pgpass@1.0.5
|   `-- split2@4.1.0
+-- reflect-metadata@0.1.13
+-- sequelize@6.25.2
| +-- @types/debug@4.1.7
| | `-- @types/ms@0.7.31
| +-- @types/validator@13.7.8
| +-- debug@4.3.4
| | `-- ms@2.1.2
| +-- dottie@2.0.2
| +-- inflection@1.13.4
| +-- lodash@4.17.21
| +-- moment@2.29.4
| +-- moment-timezone@0.5.38
| | `-- moment@2.29.4 deduped
| +-- pg-connection-string@2.5.0 deduped
| +-- retry-as-promised@6.1.0
| +-- semver@7.3.8
| | `-- lru-cache@6.0.0
| |   `-- yallist@4.0.0
| +-- sequelize-pool@7.1.0
| +-- toposort-class@1.0.1
| +-- uuid@8.3.2
| +-- validator@13.7.0
| `-- wkx@0.5.0
|   `-- @types/node@11.11.3 deduped
+-- sequelize-typescript@2.1.5
| `-- glob@7.2.0
|   +-- fs.realpath@1.0.0 deduped
|   +-- inflight@1.0.6 deduped
|   +-- inherits@2.0.3 deduped
|   +-- minimatch@3.0.4 deduped
|   +-- once@1.4.0 deduped
|   `-- path-is-absolute@1.0.1 deduped
+-- ts-node@10.9.1
| +-- @cspotcode/source-map-support@0.8.1
| | `-- @jridgewell/trace-mapping@0.3.9
| |   +-- @jridgewell/resolve-uri@3.1.0
| |   `-- @jridgewell/sourcemap-codec@1.4.14
| +-- @tsconfig/node10@1.0.9
| +-- @tsconfig/node12@1.0.11
| +-- @tsconfig/node14@1.0.3
| +-- @tsconfig/node16@1.0.3
| +-- acorn@8.8.0
| +-- acorn-walk@8.2.0
| +-- arg@4.1.3
| +-- create-require@1.1.1
| +-- diff@4.0.2
| +-- make-error@1.3.6
| +-- v8-compile-cache-lib@3.0.1
| `-- yn@3.1.1
+-- ts-node-dev@1.0.0-pre.32
| +-- dateformat@1.0.12
| | +-- get-stdin@4.0.1
| | `-- meow@3.7.0
| |   +-- camelcase-keys@2.1.0
| |   | +-- camelcase@2.1.1
| |   | `-- map-obj@1.0.1 deduped
| |   +-- decamelize@1.2.0 deduped
| |   +-- loud-rejection@1.6.0
| |   | +-- currently-unhandled@0.4.1
| |   | | `-- array-find-index@1.0.2
| |   | `-- signal-exit@3.0.2 deduped
| |   +-- map-obj@1.0.1
| |   +-- minimist@1.2.0
| |   +-- normalize-package-data@2.5.0
| |   | +-- hosted-git-info@2.7.1
| |   | +-- resolve@1.10.0 deduped
| |   | +-- semver@5.6.0 deduped
| |   | `-- validate-npm-package-license@3.0.4
| |   |   +-- spdx-correct@3.1.0
| |   |   | +-- spdx-expression-parse@3.0.0 deduped
| |   |   | `-- spdx-license-ids@3.0.3
| |   |   `-- spdx-expression-parse@3.0.0
| |   |     +-- spdx-exceptions@2.2.0
| |   |     `-- spdx-license-ids@3.0.3 deduped
| |   +-- object-assign@4.1.1 deduped
| |   +-- read-pkg-up@1.0.1
| |   | +-- find-up@1.1.2
| |   | | +-- path-exists@2.1.0
| |   | | | `-- pinkie-promise@2.0.1 deduped
| |   | | `-- pinkie-promise@2.0.1
| |   | |   `-- pinkie@2.0.4
| |   | `-- read-pkg@1.1.0
| |   |   +-- load-json-file@1.1.0
| |   |   | +-- graceful-fs@4.1.15
| |   |   | +-- parse-json@2.2.0
| |   |   | | `-- error-ex@1.3.2
| |   |   | |   `-- is-arrayish@0.2.1
| |   |   | +-- pify@2.3.0
| |   |   | +-- pinkie-promise@2.0.1 deduped
| |   |   | `-- strip-bom@2.0.0
| |   |   |   `-- is-utf8@0.2.1
| |   |   +-- normalize-package-data@2.5.0 deduped
| |   |   `-- path-type@1.1.0
| |   |     +-- graceful-fs@4.1.15 deduped
| |   |     +-- pify@2.3.0 deduped
| |   |     `-- pinkie-promise@2.0.1 deduped
| |   +-- redent@1.0.0
| |   | +-- indent-string@2.1.0
| |   | | `-- repeating@2.0.1
| |   | |   `-- is-finite@1.0.2
| |   | |     `-- number-is-nan@1.0.1 deduped
| |   | `-- strip-indent@1.0.1
| |   |   `-- get-stdin@4.0.1 deduped
| |   `-- trim-newlines@1.0.0
| +-- dynamic-dedupe@0.3.0
| | `-- xtend@4.0.1
| +-- filewatcher@3.0.1
| | `-- debounce@1.2.0
| +-- minimist@1.2.0
| +-- mkdirp@0.5.1 deduped
| +-- node-notifier@4.6.1
| | +-- cli-usage@0.1.10
| | | +-- marked@0.7.0
| | | `-- marked-terminal@3.3.0
| | |   +-- ansi-escapes@3.2.0
| | |   +-- cardinal@2.1.1
| | |   | +-- ansicolors@0.3.2
| | |   | `-- redeyed@2.1.1
| | |   |   `-- esprima@4.0.1 deduped
| | |   +-- chalk@2.4.2 deduped
| | |   +-- cli-table@0.3.1
| | |   | `-- colors@1.0.3
| | |   +-- node-emoji@1.10.0
| | |   | `-- lodash.toarray@4.4.0
| | |   `-- supports-hyperlinks@1.0.1
| | |     +-- has-flag@2.0.0
| | |     `-- supports-color@5.5.0
| | |       `-- has-flag@3.0.0
| | +-- growly@1.3.0
| | +-- lodash.clonedeep@3.0.2
| | | +-- lodash._baseclone@3.3.0
| | | | +-- lodash._arraycopy@3.0.0
| | | | +-- lodash._arrayeach@3.0.0
| | | | +-- lodash._baseassign@3.2.0
| | | | | +-- lodash._basecopy@3.0.1
| | | | | `-- lodash.keys@3.1.2 deduped
| | | | +-- lodash._basefor@3.0.3
| | | | +-- lodash.isarray@3.0.4
| | | | `-- lodash.keys@3.1.2
| | | |   +-- lodash._getnative@3.9.1
| | | |   +-- lodash.isarguments@3.1.0
| | | |   `-- lodash.isarray@3.0.4 deduped
| | | `-- lodash._bindcallback@3.0.1
| | +-- minimist@1.2.0
| | +-- semver@5.6.0 deduped
| | +-- shellwords@0.1.1
| | `-- which@1.3.1 deduped
| +-- resolve@1.10.0
| | `-- path-parse@1.0.6
| +-- rimraf@2.6.3
| | `-- glob@7.1.3 deduped
| +-- ts-node@10.9.1 deduped
| `-- tsconfig@7.0.0
|   +-- @types/strip-bom@3.0.0
|   +-- @types/strip-json-comments@0.0.30
|   +-- strip-bom@3.0.0
|   `-- strip-json-comments@2.0.1 deduped
`-- typescript@4.8.4

```
