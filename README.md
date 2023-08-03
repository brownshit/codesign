# CO:Design
2023.08.04 co:design webpage with django and react

![image](https://github.com/brownshit/Codesign/assets/100653363/56a9fd9b-e4b2-404b-98ce-ed48a02cf4de)
![image](https://github.com/brownshit/Codesign/assets/100653363/7c3626cc-01fc-41b8-8f75-ef9f97e92217)
![image](https://github.com/brownshit/Codesign/assets/100653363/b4f0c422-2e4c-4eca-9770-7af389240aeb)


we are here...

we are CO:Design


[Directory Arcchetecture]
├─codesign_back
│  └─__pycache__
├─node_modules
│  ├─.bin
│  ├─@remix-run
│  │  └─router
│  │      └─dist
│  ├─js-tokens
│  ├─loose-envify
│  ├─react
│  │  ├─cjs
│  │  └─umd
│  ├─react-dom
│  │  ├─cjs
│  │  └─umd
│  ├─react-router
│  │  └─dist
│  │      ├─lib
│  │      └─umd
│  ├─react-router-dom
│  │  └─dist
│  │      └─umd
│  └─scheduler
│      ├─cjs
│      └─umd
└─orders
    ├─co-design
    │  ├─build
    │  │  └─static
    │  │      ├─css
    │  │      └─js
    │  ├─node_modules
    │  │  ├─.bin
    │  │  ├─.cache
    │  │  │  ├─babel-loader
    │  │  │  └─default-development
    │  │  ├─@aashutoshrathi
    │  │  │  └─word-wrap
    │  │  ├─@adobe
    │  │  │  └─css-tools
    │  │  │      └─dist
    │  │  │          ├─cjs
    │  │  │          │  ├─parse
    │  │  │          │  └─stringify
    │  │  │          ├─esm
    │  │  │          │  ├─parse
    │  │  │          │  └─stringify
    │  │  │          └─umd
    │  │  ├─@alloc
    │  │  │  └─quick-lru
    │  │  ├─@ampproject
    │  │  │  └─remapping
    │  │  │      └─dist
    │  │  │          └─types
    │  │  ├─@babel
    │  │  │  ├─code-frame
    │  │  │  │  └─lib
    │  │  │  ├─compat-data
    │  │  │  │  └─data
    │  │  │  ├─core
    │  │  │  │  ├─lib
    │  │  │  │  │  ├─config
    │  │  │  │  │  │  ├─files
    │  │  │  │  │  │  ├─helpers
    │  │  │  │  │  │  └─validation
    │  │  │  │  │  ├─errors
    │  │  │  │  │  ├─gensync-utils
    │  │  │  │  │  ├─parser
    │  │  │  │  │  │  └─util
    │  │  │  │  │  ├─tools
    │  │  │  │  │  ├─transformation
    │  │  │  │  │  │  ├─file
    │  │  │  │  │  │  └─util
    │  │  │  │  │  └─vendor
    │  │  │  │  ├─node_modules
    │  │  │  │  │  ├─.bin
    │  │  │  │  │  └─semver
    │  │  │  │  │      └─bin
    │  │  │  │  └─src
    │  │  │  │      └─config
    │  │  │  │          └─files
    │  │  │  ├─eslint-parser
    │  │  │  │  ├─lib
    │  │  │  │  │  ├─convert
    │  │  │  │  │  ├─utils
    │  │  │  │  │  └─worker
    │  │  │  │  └─node_modules
    │  │  │  │      ├─.bin
    │  │  │  │      ├─eslint-visitor-keys
    │  │  │  │      │  └─lib
    │  │  │  │      └─semver
    │  │  │  │          └─bin
    │  │  │  ├─generator
    │  │  │  │  └─lib
    │  │  │  │      ├─generators
    │  │  │  │      └─node
    │  │  │  ├─helper-annotate-as-pure
    │  │  │  │  └─lib
    │  │  │  ├─helper-builder-binary-assignment-operator-visitor
    │  │  │  │  └─lib
    │  │  │  ├─helper-compilation-targets
    │  │  │  │  ├─lib
    │  │  │  │  └─node_modules
    │  │  │  │      ├─.bin
    │  │  │  │      └─semver
    │  │  │  │          └─bin
    │  │  │  ├─helper-create-class-features-plugin
    │  │  │  │  ├─lib
    │  │  │  │  └─node_modules
    │  │  │  │      ├─.bin
    │  │  │  │      └─semver
    │  │  │  │          └─bin
    │  │  │  ├─helper-create-regexp-features-plugin
    │  │  │  │  ├─lib
    │  │  │  │  └─node_modules
    │  │  │  │      ├─.bin
    │  │  │  │      └─semver
    │  │  │  │          └─bin
    │  │  │  ├─helper-define-polyfill-provider
    │  │  │  │  ├─esm
    │  │  │  │  └─lib
    │  │  │  │      ├─browser
    │  │  │  │      ├─node
    │  │  │  │      └─visitors
    │  │  │  ├─helper-environment-visitor
    │  │  │  │  └─lib
    │  │  │  ├─helper-function-name
    │  │  │  │  └─lib
    │  │  │  ├─helper-hoist-variables
    │  │  │  │  └─lib
    │  │  │  ├─helper-member-expression-to-functions
    │  │  │  │  └─lib
    │  │  │  ├─helper-module-imports
    │  │  │  │  └─lib
    │  │  │  ├─helper-module-transforms
    │  │  │  │  └─lib
    │  │  │  ├─helper-optimise-call-expression
    │  │  │  │  └─lib
    │  │  │  ├─helper-plugin-utils
    │  │  │  │  └─lib
    │  │  │  ├─helper-remap-async-to-generator
    │  │  │  │  └─lib
    │  │  │  ├─helper-replace-supers
    │  │  │  │  └─lib
    │  │  │  ├─helper-simple-access
    │  │  │  │  └─lib
    │  │  │  ├─helper-skip-transparent-expression-wrappers
    │  │  │  │  └─lib
    │  │  │  ├─helper-split-export-declaration
    │  │  │  │  └─lib
    │  │  │  ├─helper-string-parser
    │  │  │  │  └─lib
    │  │  │  ├─helper-validator-identifier
    │  │  │  │  ├─lib
    │  │  │  │  └─scripts
    │  │  │  ├─helper-validator-option
    │  │  │  │  └─lib
    │  │  │  ├─helper-wrap-function
    │  │  │  │  └─lib
    │  │  │  ├─helpers
    │  │  │  │  ├─lib
    │  │  │  │  │  └─helpers
    │  │  │  │  └─scripts
    │  │  │  ├─highlight
    │  │  │  │  └─lib
    │  │  │  ├─parser
    │  │  │  │  ├─bin
    │  │  │  │  ├─lib
    │  │  │  │  │  ├─parse-error
    │  │  │  │  │  ├─parser
    │  │  │  │  │  ├─plugins
    │  │  │  │  │  │  ├─flow
    │  │  │  │  │  │  ├─jsx
    │  │  │  │  │  │  └─typescript
    │  │  │  │  │  ├─tokenizer
    │  │  │  │  │  └─util
    │  │  │  │  └─typings
    │  │  │  ├─plugin-bugfix-safari-id-destructuring-collision-in-function-expression
    │  │  │  │  └─lib
    │  │  │  ├─plugin-bugfix-v8-spread-parameters-in-optional-chaining
    │  │  │  │  └─lib
    │  │  │  ├─plugin-proposal-class-properties
    │  │  │  │  └─lib
    │  │  │  ├─plugin-proposal-decorators
    │  │  │  │  └─lib
    │  │  │  ├─plugin-proposal-nullish-coalescing-operator
    │  │  │  │  └─lib
    │  │  │  ├─plugin-proposal-numeric-separator
    │  │  │  │  └─lib
    │  │  │  ├─plugin-proposal-optional-chaining
    │  │  │  │  └─lib
    │  │  │  ├─plugin-proposal-private-methods
    │  │  │  │  └─lib
    │  │  │  ├─plugin-proposal-private-property-in-object
    │  │  │  │  └─lib
    │  │  │  ├─plugin-proposal-unicode-property-regex
    │  │  │  │  └─lib
    │  │  │  ├─plugin-syntax-async-generators
    │  │  │  │  └─lib
    │  │  │  ├─plugin-syntax-bigint
    │  │  │  │  └─lib
    │  │  │  ├─plugin-syntax-class-properties
    │  │  │  │  └─lib
    │  │  │  ├─plugin-syntax-class-static-block
    │  │  │  │  └─lib
    │  │  │  ├─plugin-syntax-decorators
    │  │  │  │  └─lib
    │  │  │  ├─plugin-syntax-dynamic-import
    │  │  │  │  └─lib
    │  │  │  ├─plugin-syntax-export-namespace-from
    │  │  │  │  └─lib
    │  │  │  ├─plugin-syntax-flow
    │  │  │  │  └─lib
    │  │  │  ├─plugin-syntax-import-assertions
    │  │  │  │  └─lib
    │  │  │  ├─plugin-syntax-import-attributes
    │  │  │  │  └─lib
    │  │  │  ├─plugin-syntax-import-meta
    │  │  │  │  └─lib
    │  │  │  ├─plugin-syntax-json-strings
    │  │  │  │  └─lib
    │  │  │  ├─plugin-syntax-jsx
    │  │  │  │  └─lib
    │  │  │  ├─plugin-syntax-logical-assignment-operators
    │  │  │  │  └─lib
    │  │  │  ├─plugin-syntax-nullish-coalescing-operator
    │  │  │  │  └─lib
    │  │  │  ├─plugin-syntax-numeric-separator
    │  │  │  │  └─lib
    │  │  │  ├─plugin-syntax-object-rest-spread
    │  │  │  │  └─lib
    │  │  │  ├─plugin-syntax-optional-catch-binding
    │  │  │  │  └─lib
    │  │  │  ├─plugin-syntax-optional-chaining
    │  │  │  │  └─lib
    │  │  │  ├─plugin-syntax-private-property-in-object
    │  │  │  │  └─lib
    │  │  │  ├─plugin-syntax-top-level-await
    │  │  │  │  └─lib
    │  │  │  ├─plugin-syntax-typescript
    │  │  │  │  └─lib
    │  │  │  ├─plugin-syntax-unicode-sets-regex
    │  │  │  │  └─lib
    │  │  │  ├─plugin-transform-arrow-functions
    │  │  │  │  └─lib
    │  │  │  ├─plugin-transform-async-generator-functions
    │  │  │  │  └─lib
    │  │  │  ├─plugin-transform-async-to-generator
    │  │  │  │  └─lib
    │  │  │  ├─plugin-transform-block-scoped-functions
    │  │  │  │  └─lib
    │  │  │  ├─plugin-transform-block-scoping
    │  │  │  │  └─lib
    │  │  │  ├─plugin-transform-class-properties
    │  │  │  │  └─lib
    │  │  │  ├─plugin-transform-class-static-block
    │  │  │  │  └─lib
    │  │  │  ├─plugin-transform-classes
    │  │  │  │  └─lib
    │  │  │  ├─plugin-transform-computed-properties
    │  │  │  │  └─lib
    │  │  │  ├─plugin-transform-destructuring
    │  │  │  │  └─lib
    │  │  │  ├─plugin-transform-dotall-regex
    │  │  │  │  └─lib
    │  │  │  ├─plugin-transform-duplicate-keys
    │  │  │  │  └─lib
    │  │  │  ├─plugin-transform-dynamic-import
    │  │  │  │  └─lib
    │  │  │  ├─plugin-transform-exponentiation-operator
    │  │  │  │  └─lib
    │  │  │  ├─plugin-transform-export-namespace-from
    │  │  │  │  └─lib
    │  │  │  ├─plugin-transform-flow-strip-types
    │  │  │  │  └─lib
    │  │  │  ├─plugin-transform-for-of
    │  │  │  │  └─lib
    │  │  │  ├─plugin-transform-function-name
    │  │  │  │  └─lib
    │  │  │  ├─plugin-transform-json-strings
    │  │  │  │  └─lib
    │  │  │  ├─plugin-transform-literals
    │  │  │  │  └─lib
    │  │  │  ├─plugin-transform-logical-assignment-operators
    │  │  │  │  └─lib
    │  │  │  ├─plugin-transform-member-expression-literals
    │  │  │  │  └─lib
    │  │  │  ├─plugin-transform-modules-amd
    │  │  │  │  └─lib
    │  │  │  ├─plugin-transform-modules-commonjs
    │  │  │  │  └─lib
    │  │  │  ├─plugin-transform-modules-systemjs
    │  │  │  │  └─lib
    │  │  │  ├─plugin-transform-modules-umd
    │  │  │  │  └─lib
    │  │  │  ├─plugin-transform-named-capturing-groups-regex
    │  │  │  │  └─lib
    │  │  │  ├─plugin-transform-new-target
    │  │  │  │  └─lib
    │  │  │  ├─plugin-transform-nullish-coalescing-operator
    │  │  │  │  └─lib
    │  │  │  ├─plugin-transform-numeric-separator
    │  │  │  │  └─lib
    │  │  │  ├─plugin-transform-object-rest-spread
    │  │  │  │  └─lib
    │  │  │  ├─plugin-transform-object-super
    │  │  │  │  └─lib
    │  │  │  ├─plugin-transform-optional-catch-binding
    │  │  │  │  └─lib
    │  │  │  ├─plugin-transform-optional-chaining
    │  │  │  │  └─lib
    │  │  │  ├─plugin-transform-parameters
    │  │  │  │  └─lib
    │  │  │  ├─plugin-transform-private-methods
    │  │  │  │  └─lib
    │  │  │  ├─plugin-transform-private-property-in-object
    │  │  │  │  └─lib
    │  │  │  ├─plugin-transform-property-literals
    │  │  │  │  └─lib
    │  │  │  ├─plugin-transform-react-constant-elements
    │  │  │  │  └─lib
    │  │  │  ├─plugin-transform-react-display-name
    │  │  │  │  └─lib
    │  │  │  ├─plugin-transform-react-jsx
    │  │  │  │  └─lib
    │  │  │  ├─plugin-transform-react-jsx-development
    │  │  │  │  └─lib
    │  │  │  ├─plugin-transform-react-pure-annotations
    │  │  │  │  └─lib
    │  │  │  ├─plugin-transform-regenerator
    │  │  │  │  └─lib
    │  │  │  ├─plugin-transform-reserved-words
    │  │  │  │  └─lib
    │  │  │  ├─plugin-transform-runtime
    │  │  │  │  ├─lib
    │  │  │  │  │  └─get-runtime-path
    │  │  │  │  ├─node_modules
    │  │  │  │  │  ├─.bin
    │  │  │  │  │  └─semver
    │  │  │  │  │      └─bin
    │  │  │  │  └─src
    │  │  │  │      └─get-runtime-path
    │  │  │  ├─plugin-transform-shorthand-properties
    │  │  │  │  └─lib
    │  │  │  ├─plugin-transform-spread
    │  │  │  │  └─lib
    │  │  │  ├─plugin-transform-sticky-regex
    │  │  │  │  └─lib
    │  │  │  ├─plugin-transform-template-literals
    │  │  │  │  └─lib
    │  │  │  ├─plugin-transform-typeof-symbol
    │  │  │  │  └─lib
    │  │  │  ├─plugin-transform-typescript
    │  │  │  │  └─lib
    │  │  │  ├─plugin-transform-unicode-escapes
    │  │  │  │  └─lib
    │  │  │  ├─plugin-transform-unicode-property-regex
    │  │  │  │  └─lib
    │  │  │  ├─plugin-transform-unicode-regex
    │  │  │  │  └─lib
    │  │  │  ├─plugin-transform-unicode-sets-regex
    │  │  │  │  └─lib
    │  │  │  ├─preset-env
    │  │  │  │  ├─data
    │  │  │  │  ├─lib
    │  │  │  │  │  └─polyfills
    │  │  │  │  └─node_modules
    │  │  │  │      ├─.bin
    │  │  │  │      └─semver
    │  │  │  │          └─bin
    │  │  │  ├─preset-modules
    │  │  │  │  ├─lib
    │  │  │  │  │  └─plugins
    │  │  │  │  │      ├─transform-async-arrows-in-class
    │  │  │  │  │      ├─transform-edge-default-parameters
    │  │  │  │  │      ├─transform-edge-function-name
    │  │  │  │  │      ├─transform-jsx-spread
    │  │  │  │  │      ├─transform-safari-block-shadowing
    │  │  │  │  │      ├─transform-safari-for-shadowing
    │  │  │  │  │      └─transform-tagged-template-caching
    │  │  │  │  └─src
    │  │  │  │      └─plugins
    │  │  │  │          ├─transform-async-arrows-in-class
    │  │  │  │          ├─transform-edge-default-parameters
    │  │  │  │          ├─transform-edge-function-name
    │  │  │  │          ├─transform-jsx-spread
    │  │  │  │          ├─transform-safari-block-shadowing
    │  │  │  │          ├─transform-safari-for-shadowing
    │  │  │  │          └─transform-tagged-template-caching
    │  │  │  ├─preset-react
    │  │  │  │  └─lib
    │  │  │  ├─preset-typescript
    │  │  │  │  └─lib
    │  │  │  ├─regjsgen
    │  │  │  ├─runtime
    │  │  │  │  ├─helpers
    │  │  │  │  │  └─esm
    │  │  │  │  └─regenerator
    │  │  │  ├─template
    │  │  │  │  └─lib
    │  │  │  ├─traverse
    │  │  │  │  └─lib
    │  │  │  │      ├─path
    │  │  │  │      │  ├─inference
    │  │  │  │      │  └─lib
    │  │  │  │      └─scope
    │  │  │  │          └─lib
    │  │  │  └─types
    │  │  │      └─lib
    │  │  │          ├─asserts
    │  │  │          │  └─generated
    │  │  │          ├─ast-types
    │  │  │          │  └─generated
    │  │  │          ├─builders
    │  │  │          │  ├─flow
    │  │  │          │  ├─generated
    │  │  │          │  ├─react
    │  │  │          │  └─typescript
    │  │  │          ├─clone
    │  │  │          ├─comments
    │  │  │          ├─constants
    │  │  │          │  └─generated
    │  │  │          ├─converters
    │  │  │          ├─definitions
    │  │  │          ├─modifications
    │  │  │          │  ├─flow
    │  │  │          │  └─typescript
    │  │  │          ├─retrievers
    │  │  │          ├─traverse
    │  │  │          ├─utils
    │  │  │          │  └─react
    │  │  │          └─validators
    │  │  │              ├─generated
    │  │  │              └─react
    │  │  ├─@bcoe
    │  │  │  └─v8-coverage
    │  │  │      ├─dist
    │  │  │      │  └─lib
    │  │  │      │      └─_src
    │  │  │      └─src
    │  │  │          ├─lib
    │  │  │          └─test
    │  │  ├─@csstools
    │  │  │  ├─normalize.css
    │  │  │  ├─postcss-cascade-layers
    │  │  │  │  └─dist
    │  │  │  ├─postcss-color-function
    │  │  │  │  └─dist
    │  │  │  │      └─css-color-4
    │  │  │  ├─postcss-font-format-keywords
    │  │  │  │  └─dist
    │  │  │  ├─postcss-hwb-function
    │  │  │  │  └─dist
    │  │  │  ├─postcss-ic-unit
    │  │  │  │  └─dist
    │  │  │  ├─postcss-is-pseudo-class
    │  │  │  │  └─dist
    │  │  │  │      └─split-selectors
    │  │  │  │          └─complex
    │  │  │  ├─postcss-nested-calc
    │  │  │  │  └─dist
    │  │  │  ├─postcss-normalize-display-values
    │  │  │  │  └─dist
    │  │  │  ├─postcss-oklab-function
    │  │  │  │  └─dist
    │  │  │  │      └─css-color-4
    │  │  │  ├─postcss-progressive-custom-properties
    │  │  │  │  └─dist
    │  │  │  │      └─custom
    │  │  │  ├─postcss-stepped-value-functions
    │  │  │  │  └─dist
    │  │  │  ├─postcss-text-decoration-shorthand
    │  │  │  │  └─dist
    │  │  │  ├─postcss-trigonometric-functions
    │  │  │  │  └─dist
    │  │  │  ├─postcss-unset-value
    │  │  │  │  └─dist
    │  │  │  └─selector-specificity
    │  │  │      └─dist
    │  │  ├─@discoveryjs
    │  │  │  └─json-ext
    │  │  │      ├─dist
    │  │  │      └─src
    │  │  ├─@eslint
    │  │  │  ├─eslintrc
    │  │  │  │  ├─conf
    │  │  │  │  ├─dist
    │  │  │  │  ├─lib
    │  │  │  │  │  ├─config-array
    │  │  │  │  │  └─shared
    │  │  │  │  └─node_modules
    │  │  │  │      ├─.bin
    │  │  │  │      ├─argparse
    │  │  │  │      │  └─lib
    │  │  │  │      ├─globals
    │  │  │  │      ├─js-yaml
    │  │  │  │      │  ├─bin
    │  │  │  │      │  ├─dist
    │  │  │  │      │  └─lib
    │  │  │  │      │      ├─schema
    │  │  │  │      │      └─type
    │  │  │  │      └─type-fest
    │  │  │  │          ├─source
    │  │  │  │          └─ts41
    │  │  │  └─js
    │  │  │      └─src
    │  │  │          └─configs
    │  │  ├─@eslint-community
    │  │  │  ├─eslint-utils
    │  │  │  └─regexpp
    │  │  ├─@humanwhocodes
    │  │  │  ├─config-array
    │  │  │  ├─module-importer
    │  │  │  │  ├─dist
    │  │  │  │  └─src
    │  │  │  └─object-schema
    │  │  │      ├─.github
    │  │  │      │  └─workflows
    │  │  │      ├─src
    │  │  │      └─tests
    │  │  ├─@istanbuljs
    │  │  │  ├─load-nyc-config
    │  │  │  │  └─node_modules
    │  │  │  │      ├─camelcase
    │  │  │  │      ├─find-up
    │  │  │  │      ├─locate-path
    │  │  │  │      ├─p-limit
    │  │  │  │      └─p-locate
    │  │  │  └─schema
    │  │  ├─@jest
    │  │  │  ├─console
    │  │  │  │  ├─build
    │  │  │  │  └─node_modules
    │  │  │  │      ├─ansi-styles
    │  │  │  │      ├─chalk
    │  │  │  │      │  └─source
    │  │  │  │      ├─color-convert
    │  │  │  │      ├─color-name
    │  │  │  │      ├─has-flag
    │  │  │  │      └─supports-color
    │  │  │  ├─core
    │  │  │  │  ├─build
    │  │  │  │  │  ├─assets
    │  │  │  │  │  ├─cli
    │  │  │  │  │  ├─lib
    │  │  │  │  │  └─plugins
    │  │  │  │  └─node_modules
    │  │  │  │      ├─ansi-styles
    │  │  │  │      ├─chalk
    │  │  │  │      │  └─source
    │  │  │  │      ├─color-convert
    │  │  │  │      ├─color-name
    │  │  │  │      ├─has-flag
    │  │  │  │      └─supports-color
    │  │  │  ├─environment
    │  │  │  │  └─build
    │  │  │  ├─expect-utils
    │  │  │  │  ├─build
    │  │  │  │  └─node_modules
    │  │  │  │      └─jest-get-type
    │  │  │  │          └─build
    │  │  │  ├─fake-timers
    │  │  │  │  └─build
    │  │  │  ├─globals
    │  │  │  │  └─build
    │  │  │  ├─reporters
    │  │  │  │  ├─build
    │  │  │  │  └─node_modules
    │  │  │  │      ├─ansi-styles
    │  │  │  │      ├─chalk
    │  │  │  │      │  └─source
    │  │  │  │      ├─color-convert
    │  │  │  │      ├─color-name
    │  │  │  │      ├─has-flag
    │  │  │  │      ├─source-map
    │  │  │  │      │  ├─dist
    │  │  │  │      │  └─lib
    │  │  │  │      └─supports-color
    │  │  │  ├─schemas
    │  │  │  │  └─build
    │  │  │  ├─source-map
    │  │  │  │  ├─build
    │  │  │  │  └─node_modules
    │  │  │  │      └─source-map
    │  │  │  │          ├─dist
    │  │  │  │          └─lib
    │  │  │  ├─test-result
    │  │  │  │  └─build
    │  │  │  ├─test-sequencer
    │  │  │  │  └─build
    │  │  │  ├─transform
    │  │  │  │  ├─build
    │  │  │  │  └─node_modules
    │  │  │  │      ├─ansi-styles
    │  │  │  │      ├─chalk
    │  │  │  │      │  └─source
    │  │  │  │      ├─color-convert
    │  │  │  │      ├─color-name
    │  │  │  │      ├─has-flag
    │  │  │  │      ├─source-map
    │  │  │  │      │  ├─dist
    │  │  │  │      │  └─lib
    │  │  │  │      └─supports-color
    │  │  │  └─types
    │  │  │      ├─build
    │  │  │      └─node_modules
    │  │  │          ├─ansi-styles
    │  │  │          ├─chalk
    │  │  │          │  └─source
    │  │  │          ├─color-convert
    │  │  │          ├─color-name
    │  │  │          ├─has-flag
    │  │  │          └─supports-color
    │  │  ├─@jridgewell
    │  │  │  ├─gen-mapping
    │  │  │  │  └─dist
    │  │  │  │      └─types
    │  │  │  ├─resolve-uri
    │  │  │  │  └─dist
    │  │  │  │      └─types
    │  │  │  ├─set-array
    │  │  │  │  ├─dist
    │  │  │  │  │  └─types
    │  │  │  │  └─src
    │  │  │  ├─source-map
    │  │  │  │  └─dist
    │  │  │  │      └─types
    │  │  │  ├─sourcemap-codec
    │  │  │  │  └─dist
    │  │  │  │      └─types
    │  │  │  └─trace-mapping
    │  │  │      ├─dist
    │  │  │      │  └─types
    │  │  │      └─node_modules
    │  │  │          └─@jridgewell
    │  │  │              └─sourcemap-codec
    │  │  │                  ├─dist
    │  │  │                  │  └─types
    │  │  │                  └─src
    │  │  ├─@leichtgewicht
    │  │  │  └─ip-codec
    │  │  │      └─types
    │  │  ├─@nicolo-ribaudo
    │  │  │  ├─eslint-scope-5-internals
    │  │  │  │  └─node_modules
    │  │  │  │      ├─eslint-scope
    │  │  │  │      │  └─lib
    │  │  │  │      └─estraverse
    │  │  │  └─semver-v6
    │  │  │      └─bin
    │  │  ├─@nodelib
    │  │  │  ├─fs.scandir
    │  │  │  │  └─out
    │  │  │  │      ├─adapters
    │  │  │  │      ├─providers
    │  │  │  │      ├─types
    │  │  │  │      └─utils
    │  │  │  ├─fs.stat
    │  │  │  │  └─out
    │  │  │  │      ├─adapters
    │  │  │  │      ├─providers
    │  │  │  │      └─types
    │  │  │  └─fs.walk
    │  │  │      └─out
    │  │  │          ├─providers
    │  │  │          ├─readers
    │  │  │          └─types
    │  │  ├─@pmmmwh
    │  │  │  └─react-refresh-webpack-plugin
    │  │  │      ├─client
    │  │  │      │  └─utils
    │  │  │      ├─lib
    │  │  │      │  ├─runtime
    │  │  │      │  └─utils
    │  │  │      ├─loader
    │  │  │      │  └─utils
    │  │  │      ├─options
    │  │  │      ├─overlay
    │  │  │      │  ├─components
    │  │  │      │  └─containers
    │  │  │      ├─sockets
    │  │  │      │  └─utils
    │  │  │      └─types
    │  │  │          ├─lib
    │  │  │          ├─loader
    │  │  │          └─options
    │  │  ├─@remix-run
    │  │  │  └─router
    │  │  │      └─dist
    │  │  ├─@rollup
    │  │  │  ├─plugin-babel
    │  │  │  │  ├─dist
    │  │  │  │  └─types
    │  │  │  ├─plugin-node-resolve
    │  │  │  │  ├─dist
    │  │  │  │  │  ├─cjs
    │  │  │  │  │  └─es
    │  │  │  │  └─types
    │  │  │  ├─plugin-replace
    │  │  │  │  ├─dist
    │  │  │  │  ├─src
    │  │  │  │  └─types
    │  │  │  └─pluginutils
    │  │  │      ├─dist
    │  │  │      │  ├─cjs
    │  │  │      │  └─es
    │  │  │      ├─node_modules
    │  │  │      │  └─@types
    │  │  │      │      └─estree
    │  │  │      └─types
    │  │  ├─@rushstack
    │  │  │  └─eslint-patch
    │  │  │      └─lib
    │  │  ├─@sinclair
    │  │  │  └─typebox
    │  │  │      ├─compiler
    │  │  │      ├─conditional
    │  │  │      ├─errors
    │  │  │      ├─format
    │  │  │      ├─guard
    │  │  │      └─value
    │  │  ├─@sinonjs
    │  │  │  ├─commons
    │  │  │  │  ├─lib
    │  │  │  │  │  └─prototypes
    │  │  │  │  └─types
    │  │  │  │      └─prototypes
    │  │  │  └─fake-timers
    │  │  │      └─src
    │  │  ├─@surma
    │  │  │  └─rollup-plugin-off-main-thread
    │  │  │      └─tests
    │  │  │          └─fixtures
    │  │  │              ├─amd-function-name
    │  │  │              │  └─build
    │  │  │              ├─assets-in-worker
    │  │  │              │  └─build
    │  │  │              │      └─assets
    │  │  │              ├─dynamic-import
    │  │  │              │  └─build
    │  │  │              ├─import-meta
    │  │  │              │  └─build
    │  │  │              ├─import-meta-worker
    │  │  │              │  └─build
    │  │  │              ├─import-worker-url
    │  │  │              │  └─build
    │  │  │              ├─import-worker-url-custom-scheme
    │  │  │              │  └─build
    │  │  │              ├─module-worker
    │  │  │              │  └─build
    │  │  │              ├─more-workers
    │  │  │              │  └─build
    │  │  │              ├─public-path
    │  │  │              │  └─build
    │  │  │              ├─simple-bundle
    │  │  │              │  └─build
    │  │  │              ├─single-default
    │  │  │              │  └─build
    │  │  │              ├─url-import-meta-worker
    │  │  │              │  └─build
    │  │  │              └─worker
    │  │  │                  └─build
    │  │  ├─@svgr
    │  │  │  ├─babel-plugin-add-jsx-attribute
    │  │  │  │  └─lib
    │  │  │  ├─babel-plugin-remove-jsx-attribute
    │  │  │  │  └─lib
    │  │  │  ├─babel-plugin-remove-jsx-empty-expression
    │  │  │  │  └─lib
    │  │  │  ├─babel-plugin-replace-jsx-attribute-value
    │  │  │  │  └─lib
    │  │  │  ├─babel-plugin-svg-dynamic-title
    │  │  │  │  └─lib
    │  │  │  ├─babel-plugin-svg-em-dimensions
    │  │  │  │  └─lib
    │  │  │  ├─babel-plugin-transform-react-native-svg
    │  │  │  │  └─lib
    │  │  │  ├─babel-plugin-transform-svg-component
    │  │  │  │  └─lib
    │  │  │  ├─babel-preset
    │  │  │  │  └─lib
    │  │  │  ├─core
    │  │  │  │  └─lib
    │  │  │  ├─hast-util-to-babel-ast
    │  │  │  │  └─lib
    │  │  │  ├─plugin-jsx
    │  │  │  │  └─lib
    │  │  │  ├─plugin-svgo
    │  │  │  │  └─lib
    │  │  │  └─webpack
    │  │  │      └─lib
    │  │  ├─@testing-library
    │  │  │  ├─dom
    │  │  │  │  ├─dist
    │  │  │  │  │  ├─@testing-library
    │  │  │  │  │  └─queries
    │  │  │  │  ├─node_modules
    │  │  │  │  │  ├─ansi-styles
    │  │  │  │  │  ├─aria-query
    │  │  │  │  │  │  └─lib
    │  │  │  │  │  │      ├─etc
    │  │  │  │  │  │      │  └─roles
    │  │  │  │  │  │      │      ├─abstract
    │  │  │  │  │  │      │      ├─dpub
    │  │  │  │  │  │      │      ├─graphics
    │  │  │  │  │  │      │      └─literal
    │  │  │  │  │  │      └─util
    │  │  │  │  │  ├─chalk
    │  │  │  │  │  │  └─source
    │  │  │  │  │  ├─color-convert
    │  │  │  │  │  ├─color-name
    │  │  │  │  │  ├─has-flag
    │  │  │  │  │  └─supports-color
    │  │  │  │  └─types
    │  │  │  ├─jest-dom
    │  │  │  │  ├─dist
    │  │  │  │  └─node_modules
    │  │  │  │      ├─ansi-styles
    │  │  │  │      ├─chalk
    │  │  │  │      │  └─source
    │  │  │  │      ├─color-convert
    │  │  │  │      ├─color-name
    │  │  │  │      ├─has-flag
    │  │  │  │      └─supports-color
    │  │  │  ├─react
    │  │  │  │  ├─dist
    │  │  │  │  │  └─@testing-library
    │  │  │  │  ├─node_modules
    │  │  │  │  │  ├─@testing-library
    │  │  │  │  │  │  └─dom
    │  │  │  │  │  │      ├─dist
    │  │  │  │  │  │      │  ├─@testing-library
    │  │  │  │  │  │      │  └─queries
    │  │  │  │  │  │      └─types
    │  │  │  │  │  ├─ansi-styles
    │  │  │  │  │  ├─aria-query
    │  │  │  │  │  │  └─lib
    │  │  │  │  │  │      ├─etc
    │  │  │  │  │  │      │  └─roles
    │  │  │  │  │  │      │      ├─abstract
    │  │  │  │  │  │      │      ├─dpub
    │  │  │  │  │  │      │      ├─graphics
    │  │  │  │  │  │      │      └─literal
    │  │  │  │  │  │      └─util
    │  │  │  │  │  ├─chalk
    │  │  │  │  │  │  └─source
    │  │  │  │  │  ├─color-convert
    │  │  │  │  │  ├─color-name
    │  │  │  │  │  ├─has-flag
    │  │  │  │  │  └─supports-color
    │  │  │  │  └─types
    │  │  │  └─user-event
    │  │  │      └─dist
    │  │  │          ├─keyboard
    │  │  │          │  ├─plugins
    │  │  │          │  └─shared
    │  │  │          ├─type
    │  │  │          └─utils
    │  │  │              ├─click
    │  │  │              ├─edit
    │  │  │              ├─focus
    │  │  │              └─misc
    │  │  ├─@tootallnate
    │  │  │  └─once
    │  │  │      └─dist
    │  │  ├─@trysound
    │  │  │  └─sax
    │  │  │      └─lib
    │  │  ├─@types
    │  │  │  ├─aria-query
    │  │  │  ├─babel__core
    │  │  │  ├─babel__generator
    │  │  │  ├─babel__template
    │  │  │  ├─babel__traverse
    │  │  │  ├─body-parser
    │  │  │  ├─bonjour
    │  │  │  ├─connect
    │  │  │  ├─connect-history-api-fallback
    │  │  │  ├─eslint
    │  │  │  │  └─rules
    │  │  │  ├─eslint-scope
    │  │  │  ├─estree
    │  │  │  ├─express
    │  │  │  ├─express-serve-static-core
    │  │  │  ├─graceful-fs
    │  │  │  ├─html-minifier-terser
    │  │  │  ├─http-errors
    │  │  │  ├─http-proxy
    │  │  │  ├─istanbul-lib-coverage
    │  │  │  ├─istanbul-lib-report
    │  │  │  ├─istanbul-reports
    │  │  │  ├─jest
    │  │  │  │  └─node_modules
    │  │  │  │      ├─@jest
    │  │  │  │      │  ├─schemas
    │  │  │  │      │  │  └─build
    │  │  │  │      │  └─types
    │  │  │  │      │      └─build
    │  │  │  │      ├─@sinclair
    │  │  │  │      │  └─typebox
    │  │  │  │      │      ├─compiler
    │  │  │  │      │      ├─errors
    │  │  │  │      │      ├─system
    │  │  │  │      │      └─value
    │  │  │  │      ├─@types
    │  │  │  │      │  └─yargs
    │  │  │  │      ├─ansi-styles
    │  │  │  │      ├─chalk
    │  │  │  │      │  └─source
    │  │  │  │      ├─color-convert
    │  │  │  │      ├─color-name
    │  │  │  │      ├─diff-sequences
    │  │  │  │      │  └─build
    │  │  │  │      ├─expect
    │  │  │  │      │  └─build
    │  │  │  │      ├─has-flag
    │  │  │  │      ├─jest-diff
    │  │  │  │      │  └─build
    │  │  │  │      ├─jest-get-type
    │  │  │  │      │  └─build
    │  │  │  │      ├─jest-matcher-utils
    │  │  │  │      │  └─build
    │  │  │  │      ├─jest-message-util
    │  │  │  │      │  └─build
    │  │  │  │      ├─jest-util
    │  │  │  │      │  └─build
    │  │  │  │      ├─pretty-format
    │  │  │  │      │  ├─build
    │  │  │  │      │  │  └─plugins
    │  │  │  │      │  │      └─lib
    │  │  │  │      │  └─node_modules
    │  │  │  │      │      └─ansi-styles
    │  │  │  │      ├─react-is
    │  │  │  │      │  ├─cjs
    │  │  │  │      │  └─umd
    │  │  │  │      └─supports-color
    │  │  │  ├─json-schema
    │  │  │  ├─json5
    │  │  │  ├─mime
    │  │  │  ├─node
    │  │  │  │  ├─assert
    │  │  │  │  ├─dns
    │  │  │  │  ├─fs
    │  │  │  │  ├─readline
    │  │  │  │  ├─stream
    │  │  │  │  ├─timers
    │  │  │  │  └─ts4.8
    │  │  │  │      ├─assert
    │  │  │  │      ├─dns
    │  │  │  │      ├─fs
    │  │  │  │      ├─readline
    │  │  │  │      ├─stream
    │  │  │  │      └─timers
    │  │  │  ├─parse-json
    │  │  │  ├─prettier
    │  │  │  ├─prop-types
    │  │  │  ├─q
    │  │  │  ├─qs
    │  │  │  ├─range-parser
    │  │  │  ├─react
    │  │  │  │  └─ts5.0
    │  │  │  ├─react-dom
    │  │  │  │  └─test-utils
    │  │  │  ├─resolve
    │  │  │  ├─retry
    │  │  │  ├─scheduler
    │  │  │  ├─semver
    │  │  │  │  ├─classes
    │  │  │  │  ├─functions
    │  │  │  │  ├─internals
    │  │  │  │  └─ranges
    │  │  │  ├─send
    │  │  │  ├─serve-index
    │  │  │  ├─serve-static
    │  │  │  ├─sockjs
    │  │  │  ├─stack-utils
    │  │  │  ├─testing-library__jest-dom
    │  │  │  ├─trusted-types
    │  │  │  │  └─lib
    │  │  │  ├─ws
    │  │  │  ├─yargs
    │  │  │  └─yargs-parser
    │  │  ├─@typescript-eslint
    │  │  │  ├─eslint-plugin
    │  │  │  │  ├─dist
    │  │  │  │  │  ├─configs
    │  │  │  │  │  ├─rules
    │  │  │  │  │  │  ├─enum-utils
    │  │  │  │  │  │  └─naming-convention-utils
    │  │  │  │  │  └─util
    │  │  │  │  └─docs
    │  │  │  │      └─rules
    │  │  │  ├─experimental-utils
    │  │  │  │  ├─dist
    │  │  │  │  └─_ts3.4
    │  │  │  │      └─dist
    │  │  │  ├─parser
    │  │  │  │  ├─dist
    │  │  │  │  └─_ts3.4
    │  │  │  │      └─dist
    │  │  │  ├─scope-manager
    │  │  │  │  └─dist
    │  │  │  │      ├─definition
    │  │  │  │      ├─lib
    │  │  │  │      ├─referencer
    │  │  │  │      ├─scope
    │  │  │  │      └─variable
    │  │  │  ├─type-utils
    │  │  │  │  ├─dist
    │  │  │  │  └─_ts3.4
    │  │  │  │      └─dist
    │  │  │  ├─types
    │  │  │  │  ├─dist
    │  │  │  │  │  └─generated
    │  │  │  │  └─_ts3.4
    │  │  │  │      └─dist
    │  │  │  │          └─generated
    │  │  │  ├─typescript-estree
    │  │  │  │  ├─dist
    │  │  │  │  │  ├─create-program
    │  │  │  │  │  ├─jsx
    │  │  │  │  │  ├─parseSettings
    │  │  │  │  │  └─ts-estree
    │  │  │  │  └─_ts3.4
    │  │  │  │      └─dist
    │  │  │  │          ├─create-program
    │  │  │  │          ├─jsx
    │  │  │  │          ├─parseSettings
    │  │  │  │          └─ts-estree
    │  │  │  ├─utils
    │  │  │  │  ├─dist
    │  │  │  │  │  ├─ast-utils
    │  │  │  │  │  │  └─eslint-utils
    │  │  │  │  │  ├─eslint-utils
    │  │  │  │  │  │  └─rule-tester
    │  │  │  │  │  ├─ts-eslint
    │  │  │  │  │  └─ts-eslint-scope
    │  │  │  │  ├─node_modules
    │  │  │  │  │  ├─eslint-scope
    │  │  │  │  │  │  └─lib
    │  │  │  │  │  └─estraverse
    │  │  │  │  └─_ts3.4
    │  │  │  │      └─dist
    │  │  │  │          ├─ast-utils
    │  │  │  │          │  └─eslint-utils
    │  │  │  │          ├─eslint-utils
    │  │  │  │          │  └─rule-tester
    │  │  │  │          ├─ts-eslint
    │  │  │  │          └─ts-eslint-scope
    │  │  │  └─visitor-keys
    │  │  │      ├─dist
    │  │  │      └─_ts3.4
    │  │  │          └─dist
    │  │  ├─@webassemblyjs
    │  │  │  ├─ast
    │  │  │  │  ├─lib
    │  │  │  │  │  ├─transform
    │  │  │  │  │  │  ├─ast-module-to-module-context
    │  │  │  │  │  │  ├─denormalize-type-references
    │  │  │  │  │  │  └─wast-identifier-to-index
    │  │  │  │  │  └─types
    │  │  │  │  └─scripts
    │  │  │  ├─floating-point-hex-parser
    │  │  │  │  └─lib
    │  │  │  ├─helper-api-error
    │  │  │  │  └─lib
    │  │  │  ├─helper-buffer
    │  │  │  │  └─lib
    │  │  │  ├─helper-numbers
    │  │  │  │  ├─lib
    │  │  │  │  └─src
    │  │  │  ├─helper-wasm-bytecode
    │  │  │  │  └─lib
    │  │  │  ├─helper-wasm-section
    │  │  │  │  └─lib
    │  │  │  ├─ieee754
    │  │  │  │  ├─lib
    │  │  │  │  └─src
    │  │  │  ├─leb128
    │  │  │  │  └─lib
    │  │  │  ├─utf8
    │  │  │  │  ├─lib
    │  │  │  │  ├─src
    │  │  │  │  └─test
    │  │  │  ├─wasm-edit
    │  │  │  │  └─lib
    │  │  │  ├─wasm-gen
    │  │  │  │  └─lib
    │  │  │  │      └─encoder
    │  │  │  ├─wasm-opt
    │  │  │  │  └─lib
    │  │  │  ├─wasm-parser
    │  │  │  │  └─lib
    │  │  │  │      └─types
    │  │  │  └─wast-printer
    │  │  │      └─lib
    │  │  ├─@webpack-cli
    │  │  │  ├─configtest
    │  │  │  │  └─lib
    │  │  │  ├─info
    │  │  │  │  └─lib
    │  │  │  └─serve
    │  │  │      └─lib
    │  │  ├─@xtuc
    │  │  │  ├─ieee754
    │  │  │  │  └─dist
    │  │  │  └─long
    │  │  │      ├─dist
    │  │  │      └─src
    │  │  ├─abab
    │  │  │  └─lib
    │  │  ├─accepts
    │  │  ├─acorn
    │  │  │  ├─bin
    │  │  │  └─dist
    │  │  ├─acorn-globals
    │  │  │  └─node_modules
    │  │  │      ├─.bin
    │  │  │      └─acorn
    │  │  │          ├─bin
    │  │  │          └─dist
    │  │  ├─acorn-import-assertions
    │  │  │  ├─lib
    │  │  │  └─src
    │  │  ├─acorn-jsx
    │  │  ├─acorn-walk
    │  │  │  └─dist
    │  │  ├─address
    │  │  │  └─lib
    │  │  ├─adjust-sourcemap-loader
    │  │  │  ├─codec
    │  │  │  │  └─utility
    │  │  │  └─lib
    │  │  │      └─process
    │  │  ├─agent-base
    │  │  │  ├─dist
    │  │  │  │  └─src
    │  │  │  └─src
    │  │  ├─ajv
    │  │  │  ├─dist
    │  │  │  ├─lib
    │  │  │  │  ├─compile
    │  │  │  │  ├─dot
    │  │  │  │  ├─dotjs
    │  │  │  │  └─refs
    │  │  │  └─scripts
    │  │  ├─ajv-formats
    │  │  │  ├─dist
    │  │  │  ├─node_modules
    │  │  │  │  ├─ajv
    │  │  │  │  │  ├─dist
    │  │  │  │  │  │  ├─compile
    │  │  │  │  │  │  │  ├─codegen
    │  │  │  │  │  │  │  ├─jtd
    │  │  │  │  │  │  │  └─validate
    │  │  │  │  │  │  ├─refs
    │  │  │  │  │  │  │  ├─json-schema-2019-09
    │  │  │  │  │  │  │  │  └─meta
    │  │  │  │  │  │  │  └─json-schema-2020-12
    │  │  │  │  │  │  │      └─meta
    │  │  │  │  │  │  ├─runtime
    │  │  │  │  │  │  ├─standalone
    │  │  │  │  │  │  ├─types
    │  │  │  │  │  │  └─vocabularies
    │  │  │  │  │  │      ├─applicator
    │  │  │  │  │  │      ├─core
    │  │  │  │  │  │      ├─discriminator
    │  │  │  │  │  │      ├─dynamic
    │  │  │  │  │  │      ├─format
    │  │  │  │  │  │      ├─jtd
    │  │  │  │  │  │      ├─unevaluated
    │  │  │  │  │  │      └─validation
    │  │  │  │  │  └─lib
    │  │  │  │  │      ├─compile
    │  │  │  │  │      │  ├─codegen
    │  │  │  │  │      │  ├─jtd
    │  │  │  │  │      │  └─validate
    │  │  │  │  │      ├─refs
    │  │  │  │  │      │  ├─json-schema-2019-09
    │  │  │  │  │      │  │  └─meta
    │  │  │  │  │      │  └─json-schema-2020-12
    │  │  │  │  │      │      └─meta
    │  │  │  │  │      ├─runtime
    │  │  │  │  │      ├─standalone
    │  │  │  │  │      ├─types
    │  │  │  │  │      └─vocabularies
    │  │  │  │  │          ├─applicator
    │  │  │  │  │          ├─core
    │  │  │  │  │          ├─discriminator
    │  │  │  │  │          ├─dynamic
    │  │  │  │  │          ├─format
    │  │  │  │  │          ├─jtd
    │  │  │  │  │          ├─unevaluated
    │  │  │  │  │          └─validation
    │  │  │  │  └─json-schema-traverse
    │  │  │  │      ├─.github
    │  │  │  │      │  └─workflows
    │  │  │  │      └─spec
    │  │  │  │          └─fixtures
    │  │  │  └─src
    │  │  ├─ajv-keywords
    │  │  │  └─keywords
    │  │  │      ├─dot
    │  │  │      └─dotjs
    │  │  ├─ansi-escapes
    │  │  ├─ansi-html-community
    │  │  │  └─bin
    │  │  ├─ansi-regex
    │  │  ├─ansi-styles
    │  │  ├─any-promise
    │  │  │  └─register
    │  │  ├─anymatch
    │  │  ├─arg
    │  │  ├─argparse
    │  │  │  └─lib
    │  │  │      ├─action
    │  │  │      │  ├─append
    │  │  │      │  └─store
    │  │  │      ├─argument
    │  │  │      └─help
    │  │  ├─aria-query
    │  │  │  └─lib
    │  │  │      ├─etc
    │  │  │      │  └─roles
    │  │  │      │      ├─abstract
    │  │  │      │      ├─dpub
    │  │  │      │      ├─graphics
    │  │  │      │      └─literal
    │  │  │      └─util
    │  │  ├─array-buffer-byte-length
    │  │  │  ├─.github
    │  │  │  └─test
    │  │  ├─array-flatten
    │  │  ├─array-includes
    │  │  │  ├─.github
    │  │  │  └─test
    │  │  ├─array-union
    │  │  ├─array.prototype.flat
    │  │  │  ├─.github
    │  │  │  └─test
    │  │  ├─array.prototype.flatmap
    │  │  │  ├─.github
    │  │  │  └─test
    │  │  ├─array.prototype.reduce
    │  │  │  └─test
    │  │  ├─array.prototype.tosorted
    │  │  │  ├─.github
    │  │  │  └─test
    │  │  ├─arraybuffer.prototype.slice
    │  │  │  └─test
    │  │  ├─asap
    │  │  ├─ast-types-flow
    │  │  │  └─lib
    │  │  ├─async
    │  │  │  ├─dist
    │  │  │  └─internal
    │  │  ├─asynckit
    │  │  │  └─lib
    │  │  ├─at-least-node
    │  │  ├─autoprefixer
    │  │  │  ├─bin
    │  │  │  ├─data
    │  │  │  └─lib
    │  │  │      └─hacks
    │  │  ├─available-typed-arrays
    │  │  │  ├─.github
    │  │  │  └─test
    │  │  ├─axe-core
    │  │  │  └─locales
    │  │  ├─axobject-query
    │  │  │  └─lib
    │  │  │      ├─etc
    │  │  │      │  └─objects
    │  │  │      └─util
    │  │  ├─babel-jest
    │  │  │  ├─build
    │  │  │  └─node_modules
    │  │  │      ├─ansi-styles
    │  │  │      ├─chalk
    │  │  │      │  └─source
    │  │  │      ├─color-convert
    │  │  │      ├─color-name
    │  │  │      ├─has-flag
    │  │  │      └─supports-color
    │  │  ├─babel-loader
    │  │  │  ├─lib
    │  │  │  └─node_modules
    │  │  │      └─schema-utils
    │  │  │          ├─declarations
    │  │  │          │  ├─keywords
    │  │  │          │  └─util
    │  │  │          └─dist
    │  │  │              ├─keywords
    │  │  │              └─util
    │  │  ├─babel-plugin-istanbul
    │  │  │  └─lib
    │  │  ├─babel-plugin-jest-hoist
    │  │  │  └─build
    │  │  ├─babel-plugin-macros
    │  │  │  └─dist
    │  │  ├─babel-plugin-named-asset-import
    │  │  ├─babel-plugin-polyfill-corejs2
    │  │  │  ├─esm
    │  │  │  └─lib
    │  │  ├─babel-plugin-polyfill-corejs3
    │  │  │  ├─core-js-compat
    │  │  │  ├─esm
    │  │  │  └─lib
    │  │  ├─babel-plugin-polyfill-regenerator
    │  │  │  ├─esm
    │  │  │  └─lib
    │  │  ├─babel-plugin-transform-react-remove-prop-types
    │  │  │  ├─lib
    │  │  │  └─src
    │  │  ├─babel-preset-current-node-syntax
    │  │  │  ├─scripts
    │  │  │  └─src
    │  │  ├─babel-preset-jest
    │  │  ├─babel-preset-react-app
    │  │  ├─balanced-match
    │  │  │  └─.github
    │  │  ├─batch
    │  │  ├─bfj
    │  │  │  ├─src
    │  │  │  └─test
    │  │  │      └─unit
    │  │  ├─big.js
    │  │  ├─binary-extensions
    │  │  ├─bluebird
    │  │  │  └─js
    │  │  │      ├─browser
    │  │  │      └─release
    │  │  ├─body-parser
    │  │  │  ├─lib
    │  │  │  │  └─types
    │  │  │  └─node_modules
    │  │  │      ├─bytes
    │  │  │      ├─debug
    │  │  │      │  └─src
    │  │  │      ├─iconv-lite
    │  │  │      │  ├─encodings
    │  │  │      │  │  └─tables
    │  │  │      │  └─lib
    │  │  │      └─ms
    │  │  ├─bonjour-service
    │  │  │  ├─dist
    │  │  │  │  └─lib
    │  │  │  │      └─utils
    │  │  │  └─types
    │  │  ├─boolbase
    │  │  ├─brace-expansion
    │  │  ├─braces
    │  │  │  └─lib
    │  │  ├─browser-process-hrtime
    │  │  ├─browserslist
    │  │  ├─bser
    │  │  ├─buffer-from
    │  │  ├─builtin-modules
    │  │  ├─bytes
    │  │  ├─call-bind
    │  │  │  ├─.github
    │  │  │  └─test
    │  │  ├─callsites
    │  │  ├─camel-case
    │  │  │  ├─dist
    │  │  │  └─dist.es2015
    │  │  ├─camelcase
    │  │  ├─camelcase-css
    │  │  ├─caniuse-api
    │  │  │  └─dist
    │  │  ├─caniuse-lite
    │  │  │  ├─data
    │  │  │  │  ├─features
    │  │  │  │  └─regions
    │  │  │  └─dist
    │  │  │      ├─lib
    │  │  │      └─unpacker
    │  │  ├─case-sensitive-paths-webpack-plugin
    │  │  ├─chalk
    │  │  │  └─types
    │  │  ├─char-regex
    │  │  ├─check-types
    │  │  │  └─src
    │  │  ├─chokidar
    │  │  │  ├─lib
    │  │  │  ├─node_modules
    │  │  │  │  └─glob-parent
    │  │  │  └─types
    │  │  ├─chrome-trace-event
    │  │  │  └─dist
    │  │  ├─ci-info
    │  │  ├─cjs-module-lexer
    │  │  │  └─dist
    │  │  ├─clean-css
    │  │  │  ├─lib
    │  │  │  │  ├─optimizer
    │  │  │  │  │  ├─configuration
    │  │  │  │  │  │  └─properties
    │  │  │  │  │  ├─level-0
    │  │  │  │  │  ├─level-1
    │  │  │  │  │  │  ├─property-optimizers
    │  │  │  │  │  │  └─value-optimizers
    │  │  │  │  │  │      └─color
    │  │  │  │  │  └─level-2
    │  │  │  │  │      └─properties
    │  │  │  │  ├─options
    │  │  │  │  ├─reader
    │  │  │  │  ├─tokenizer
    │  │  │  │  ├─utils
    │  │  │  │  └─writer
    │  │  │  └─node_modules
    │  │  │      └─source-map
    │  │  │          ├─dist
    │  │  │          └─lib
    │  │  ├─cliui
    │  │  │  └─build
    │  │  │      └─lib
    │  │  ├─clone-deep
    │  │  ├─co
    │  │  ├─coa
    │  │  │  └─lib
    │  │  ├─collect-v8-coverage
    │  │  ├─color-convert
    │  │  ├─color-name
    │  │  ├─colord
    │  │  │  └─plugins
    │  │  ├─colorette
    │  │  ├─combined-stream
    │  │  │  └─lib
    │  │  ├─commander
    │  │  │  ├─lib
    │  │  │  └─typings
    │  │  ├─common-path-prefix
    │  │  ├─common-tags
    │  │  │  ├─dist
    │  │  │  ├─es
    │  │  │  │  ├─codeBlock
    │  │  │  │  ├─commaLists
    │  │  │  │  ├─commaListsAnd
    │  │  │  │  ├─commaListsOr
    │  │  │  │  ├─html
    │  │  │  │  ├─inlineArrayTransformer
    │  │  │  │  ├─inlineLists
    │  │  │  │  ├─oneLine
    │  │  │  │  ├─oneLineCommaLists
    │  │  │  │  ├─oneLineCommaListsAnd
    │  │  │  │  ├─oneLineCommaListsOr
    │  │  │  │  ├─oneLineInlineLists
    │  │  │  │  ├─oneLineTrim
    │  │  │  │  ├─removeNonPrintingValuesTransformer
    │  │  │  │  ├─replaceResultTransformer
    │  │  │  │  ├─replaceStringTransformer
    │  │  │  │  ├─replaceSubstitutionTransformer
    │  │  │  │  ├─safeHtml
    │  │  │  │  ├─source
    │  │  │  │  ├─splitStringTransformer
    │  │  │  │  ├─stripIndent
    │  │  │  │  ├─stripIndents
    │  │  │  │  ├─stripIndentTransformer
    │  │  │  │  ├─TemplateTag
    │  │  │  │  ├─trimResultTransformer
    │  │  │  │  └─utils
    │  │  │  │      └─readFromFixture
    │  │  │  └─lib
    │  │  │      ├─codeBlock
    │  │  │      ├─commaLists
    │  │  │      ├─commaListsAnd
    │  │  │      ├─commaListsOr
    │  │  │      ├─html
    │  │  │      ├─inlineArrayTransformer
    │  │  │      ├─inlineLists
    │  │  │      ├─oneLine
    │  │  │      ├─oneLineCommaLists
    │  │  │      ├─oneLineCommaListsAnd
    │  │  │      ├─oneLineCommaListsOr
    │  │  │      ├─oneLineInlineLists
    │  │  │      ├─oneLineTrim
    │  │  │      ├─removeNonPrintingValuesTransformer
    │  │  │      ├─replaceResultTransformer
    │  │  │      ├─replaceStringTransformer
    │  │  │      ├─replaceSubstitutionTransformer
    │  │  │      ├─safeHtml
    │  │  │      ├─source
    │  │  │      ├─splitStringTransformer
    │  │  │      ├─stripIndent
    │  │  │      ├─stripIndents
    │  │  │      ├─stripIndentTransformer
    │  │  │      ├─TemplateTag
    │  │  │      ├─trimResultTransformer
    │  │  │      └─utils
    │  │  │          └─readFromFixture
    │  │  ├─commondir
    │  │  │  ├─example
    │  │  │  └─test
    │  │  ├─compressible
    │  │  ├─compression
    │  │  │  └─node_modules
    │  │  │      ├─debug
    │  │  │      │  └─src
    │  │  │      ├─ms
    │  │  │      └─safe-buffer
    │  │  ├─concat-map
    │  │  │  ├─example
    │  │  │  └─test
    │  │  ├─confusing-browser-globals
    │  │  ├─connect-history-api-fallback
    │  │  │  └─lib
    │  │  ├─content-disposition
    │  │  ├─content-type
    │  │  ├─convert-source-map
    │  │  ├─cookie
    │  │  ├─cookie-signature
    │  │  ├─core-js
    │  │  │  ├─actual
    │  │  │  │  ├─array
    │  │  │  │  │  └─virtual
    │  │  │  │  ├─array-buffer
    │  │  │  │  ├─async-iterator
    │  │  │  │  ├─data-view
    │  │  │  │  ├─date
    │  │  │  │  ├─disposable-stack
    │  │  │  │  ├─dom-collections
    │  │  │  │  ├─dom-exception
    │  │  │  │  ├─error
    │  │  │  │  ├─function
    │  │  │  │  │  └─virtual
    │  │  │  │  ├─instance
    │  │  │  │  ├─iterator
    │  │  │  │  ├─json
    │  │  │  │  ├─map
    │  │  │  │  ├─math
    │  │  │  │  ├─number
    │  │  │  │  │  └─virtual
    │  │  │  │  ├─object
    │  │  │  │  ├─promise
    │  │  │  │  ├─reflect
    │  │  │  │  ├─regexp
    │  │  │  │  ├─set
    │  │  │  │  ├─string
    │  │  │  │  │  └─virtual
    │  │  │  │  ├─symbol
    │  │  │  │  ├─typed-array
    │  │  │  │  ├─url
    │  │  │  │  ├─url-search-params
    │  │  │  │  ├─weak-map
    │  │  │  │  └─weak-set
    │  │  │  ├─es
    │  │  │  │  ├─array
    │  │  │  │  │  └─virtual
    │  │  │  │  ├─array-buffer
    │  │  │  │  ├─data-view
    │  │  │  │  ├─date
    │  │  │  │  ├─error
    │  │  │  │  ├─function
    │  │  │  │  │  └─virtual
    │  │  │  │  ├─instance
    │  │  │  │  ├─json
    │  │  │  │  ├─map
    │  │  │  │  ├─math
    │  │  │  │  ├─number
    │  │  │  │  │  └─virtual
    │  │  │  │  ├─object
    │  │  │  │  ├─promise
    │  │  │  │  ├─reflect
    │  │  │  │  ├─regexp
    │  │  │  │  ├─set
    │  │  │  │  ├─string
    │  │  │  │  │  └─virtual
    │  │  │  │  ├─symbol
    │  │  │  │  ├─typed-array
    │  │  │  │  ├─weak-map
    │  │  │  │  └─weak-set
    │  │  │  ├─features
    │  │  │  │  ├─array
    │  │  │  │  │  └─virtual
    │  │  │  │  ├─array-buffer
    │  │  │  │  ├─async-disposable-stack
    │  │  │  │  ├─async-iterator
    │  │  │  │  ├─bigint
    │  │  │  │  ├─data-view
    │  │  │  │  ├─date
    │  │  │  │  ├─disposable-stack
    │  │  │  │  ├─dom-collections
    │  │  │  │  ├─dom-exception
    │  │  │  │  ├─error
    │  │  │  │  ├─function
    │  │  │  │  │  └─virtual
    │  │  │  │  ├─instance
    │  │  │  │  ├─iterator
    │  │  │  │  ├─json
    │  │  │  │  ├─map
    │  │  │  │  ├─math
    │  │  │  │  ├─number
    │  │  │  │  │  └─virtual
    │  │  │  │  ├─object
    │  │  │  │  ├─observable
    │  │  │  │  ├─promise
    │  │  │  │  ├─reflect
    │  │  │  │  ├─regexp
    │  │  │  │  ├─set
    │  │  │  │  ├─string
    │  │  │  │  │  └─virtual
    │  │  │  │  ├─symbol
    │  │  │  │  ├─typed-array
    │  │  │  │  ├─url
    │  │  │  │  ├─url-search-params
    │  │  │  │  ├─weak-map
    │  │  │  │  └─weak-set
    │  │  │  ├─full
    │  │  │  │  ├─array
    │  │  │  │  │  └─virtual
    │  │  │  │  ├─array-buffer
    │  │  │  │  ├─async-disposable-stack
    │  │  │  │  ├─async-iterator
    │  │  │  │  ├─bigint
    │  │  │  │  ├─data-view
    │  │  │  │  ├─date
    │  │  │  │  ├─disposable-stack
    │  │  │  │  ├─dom-collections
    │  │  │  │  ├─dom-exception
    │  │  │  │  ├─error
    │  │  │  │  ├─function
    │  │  │  │  │  └─virtual
    │  │  │  │  ├─instance
    │  │  │  │  ├─iterator
    │  │  │  │  ├─json
    │  │  │  │  ├─map
    │  │  │  │  ├─math
    │  │  │  │  ├─number
    │  │  │  │  │  └─virtual
    │  │  │  │  ├─object
    │  │  │  │  ├─observable
    │  │  │  │  ├─promise
    │  │  │  │  ├─reflect
    │  │  │  │  ├─regexp
    │  │  │  │  ├─set
    │  │  │  │  ├─string
    │  │  │  │  │  └─virtual
    │  │  │  │  ├─symbol
    │  │  │  │  ├─typed-array
    │  │  │  │  ├─url
    │  │  │  │  ├─url-search-params
    │  │  │  │  ├─weak-map
    │  │  │  │  └─weak-set
    │  │  │  ├─internals
    │  │  │  ├─modules
    │  │  │  ├─proposals
    │  │  │  ├─stable
    │  │  │  │  ├─array
    │  │  │  │  │  └─virtual
    │  │  │  │  ├─array-buffer
    │  │  │  │  ├─data-view
    │  │  │  │  ├─date
    │  │  │  │  ├─dom-collections
    │  │  │  │  ├─dom-exception
    │  │  │  │  ├─error
    │  │  │  │  ├─function
    │  │  │  │  │  └─virtual
    │  │  │  │  ├─instance
    │  │  │  │  ├─json
    │  │  │  │  ├─map
    │  │  │  │  ├─math
    │  │  │  │  ├─number
    │  │  │  │  │  └─virtual
    │  │  │  │  ├─object
    │  │  │  │  ├─promise
    │  │  │  │  ├─reflect
    │  │  │  │  ├─regexp
    │  │  │  │  ├─set
    │  │  │  │  ├─string
    │  │  │  │  │  └─virtual
    │  │  │  │  ├─symbol
    │  │  │  │  ├─typed-array
    │  │  │  │  ├─url
    │  │  │  │  ├─url-search-params
    │  │  │  │  ├─weak-map
    │  │  │  │  └─weak-set
    │  │  │  ├─stage
    │  │  │  └─web
    │  │  ├─core-js-compat
    │  │  ├─core-js-pure
    │  │  │  ├─actual
    │  │  │  │  ├─array
    │  │  │  │  │  └─virtual
    │  │  │  │  ├─array-buffer
    │  │  │  │  ├─async-iterator
    │  │  │  │  ├─data-view
    │  │  │  │  ├─date
    │  │  │  │  ├─disposable-stack
    │  │  │  │  ├─dom-collections
    │  │  │  │  ├─dom-exception
    │  │  │  │  ├─error
    │  │  │  │  ├─function
    │  │  │  │  │  └─virtual
    │  │  │  │  ├─instance
    │  │  │  │  ├─iterator
    │  │  │  │  ├─json
    │  │  │  │  ├─map
    │  │  │  │  ├─math
    │  │  │  │  ├─number
    │  │  │  │  │  └─virtual
    │  │  │  │  ├─object
    │  │  │  │  ├─promise
    │  │  │  │  ├─reflect
    │  │  │  │  ├─regexp
    │  │  │  │  ├─set
    │  │  │  │  ├─string
    │  │  │  │  │  └─virtual
    │  │  │  │  ├─symbol
    │  │  │  │  ├─typed-array
    │  │  │  │  ├─url
    │  │  │  │  ├─url-search-params
    │  │  │  │  ├─weak-map
    │  │  │  │  └─weak-set
    │  │  │  ├─es
    │  │  │  │  ├─array
    │  │  │  │  │  └─virtual
    │  │  │  │  ├─array-buffer
    │  │  │  │  ├─data-view
    │  │  │  │  ├─date
    │  │  │  │  ├─error
    │  │  │  │  ├─function
    │  │  │  │  │  └─virtual
    │  │  │  │  ├─instance
    │  │  │  │  ├─json
    │  │  │  │  ├─map
    │  │  │  │  ├─math
    │  │  │  │  ├─number
    │  │  │  │  │  └─virtual
    │  │  │  │  ├─object
    │  │  │  │  ├─promise
    │  │  │  │  ├─reflect
    │  │  │  │  ├─regexp
    │  │  │  │  ├─set
    │  │  │  │  ├─string
    │  │  │  │  │  └─virtual
    │  │  │  │  ├─symbol
    │  │  │  │  ├─typed-array
    │  │  │  │  ├─weak-map
    │  │  │  │  └─weak-set
    │  │  │  ├─features
    │  │  │  │  ├─array
    │  │  │  │  │  └─virtual
    │  │  │  │  ├─array-buffer
    │  │  │  │  ├─async-disposable-stack
    │  │  │  │  ├─async-iterator
    │  │  │  │  ├─bigint
    │  │  │  │  ├─data-view
    │  │  │  │  ├─date
    │  │  │  │  ├─disposable-stack
    │  │  │  │  ├─dom-collections
    │  │  │  │  ├─dom-exception
    │  │  │  │  ├─error
    │  │  │  │  ├─function
    │  │  │  │  │  └─virtual
    │  │  │  │  ├─instance
    │  │  │  │  ├─iterator
    │  │  │  │  ├─json
    │  │  │  │  ├─map
    │  │  │  │  ├─math
    │  │  │  │  ├─number
    │  │  │  │  │  └─virtual
    │  │  │  │  ├─object
    │  │  │  │  ├─observable
    │  │  │  │  ├─promise
    │  │  │  │  ├─reflect
    │  │  │  │  ├─regexp
    │  │  │  │  ├─set
    │  │  │  │  ├─string
    │  │  │  │  │  └─virtual
    │  │  │  │  ├─symbol
    │  │  │  │  ├─typed-array
    │  │  │  │  ├─url
    │  │  │  │  ├─url-search-params
    │  │  │  │  ├─weak-map
    │  │  │  │  └─weak-set
    │  │  │  ├─full
    │  │  │  │  ├─array
    │  │  │  │  │  └─virtual
    │  │  │  │  ├─array-buffer
    │  │  │  │  ├─async-disposable-stack
    │  │  │  │  ├─async-iterator
    │  │  │  │  ├─bigint
    │  │  │  │  ├─data-view
    │  │  │  │  ├─date
    │  │  │  │  ├─disposable-stack
    │  │  │  │  ├─dom-collections
    │  │  │  │  ├─dom-exception
    │  │  │  │  ├─error
    │  │  │  │  ├─function
    │  │  │  │  │  └─virtual
    │  │  │  │  ├─instance
    │  │  │  │  ├─iterator
    │  │  │  │  ├─json
    │  │  │  │  ├─map
    │  │  │  │  ├─math
    │  │  │  │  ├─number
    │  │  │  │  │  └─virtual
    │  │  │  │  ├─object
    │  │  │  │  ├─observable
    │  │  │  │  ├─promise
    │  │  │  │  ├─reflect
    │  │  │  │  ├─regexp
    │  │  │  │  ├─set
    │  │  │  │  ├─string
    │  │  │  │  │  └─virtual
    │  │  │  │  ├─symbol
    │  │  │  │  ├─typed-array
    │  │  │  │  ├─url
    │  │  │  │  ├─url-search-params
    │  │  │  │  ├─weak-map
    │  │  │  │  └─weak-set
    │  │  │  ├─internals
    │  │  │  ├─modules
    │  │  │  ├─proposals
    │  │  │  ├─stable
    │  │  │  │  ├─array
    │  │  │  │  │  └─virtual
    │  │  │  │  ├─array-buffer
    │  │  │  │  ├─data-view
    │  │  │  │  ├─date
    │  │  │  │  ├─dom-collections
    │  │  │  │  ├─dom-exception
    │  │  │  │  ├─error
    │  │  │  │  ├─function
    │  │  │  │  │  └─virtual
    │  │  │  │  ├─instance
    │  │  │  │  ├─json
    │  │  │  │  ├─map
    │  │  │  │  ├─math
    │  │  │  │  ├─number
    │  │  │  │  │  └─virtual
    │  │  │  │  ├─object
    │  │  │  │  ├─promise
    │  │  │  │  ├─reflect
    │  │  │  │  ├─regexp
    │  │  │  │  ├─set
    │  │  │  │  ├─string
    │  │  │  │  │  └─virtual
    │  │  │  │  ├─symbol
    │  │  │  │  ├─typed-array
    │  │  │  │  ├─url
    │  │  │  │  ├─url-search-params
    │  │  │  │  ├─weak-map
    │  │  │  │  └─weak-set
    │  │  │  ├─stage
    │  │  │  └─web
    │  │  ├─core-util-is
    │  │  │  └─lib
    │  │  ├─cosmiconfig
    │  │  │  └─dist
    │  │  ├─cross-spawn
    │  │  │  └─lib
    │  │  │      └─util
    │  │  ├─crypto-random-string
    │  │  ├─css-blank-pseudo
    │  │  │  └─dist
    │  │  ├─css-declaration-sorter
    │  │  │  ├─dist
    │  │  │  ├─orders
    │  │  │  └─src
    │  │  ├─css-has-pseudo
    │  │  │  └─dist
    │  │  ├─css-loader
    │  │  │  └─dist
    │  │  │      ├─plugins
    │  │  │      └─runtime
    │  │  ├─css-minimizer-webpack-plugin
    │  │  │  ├─dist
    │  │  │  ├─node_modules
    │  │  │  │  ├─ajv
    │  │  │  │  │  ├─dist
    │  │  │  │  │  │  ├─compile
    │  │  │  │  │  │  │  ├─codegen
    │  │  │  │  │  │  │  ├─jtd
    │  │  │  │  │  │  │  └─validate
    │  │  │  │  │  │  ├─refs
    │  │  │  │  │  │  │  ├─json-schema-2019-09
    │  │  │  │  │  │  │  │  └─meta
    │  │  │  │  │  │  │  └─json-schema-2020-12
    │  │  │  │  │  │  │      └─meta
    │  │  │  │  │  │  ├─runtime
    │  │  │  │  │  │  ├─standalone
    │  │  │  │  │  │  ├─types
    │  │  │  │  │  │  └─vocabularies
    │  │  │  │  │  │      ├─applicator
    │  │  │  │  │  │      ├─core
    │  │  │  │  │  │      ├─discriminator
    │  │  │  │  │  │      ├─dynamic
    │  │  │  │  │  │      ├─format
    │  │  │  │  │  │      ├─jtd
    │  │  │  │  │  │      ├─unevaluated
    │  │  │  │  │  │      └─validation
    │  │  │  │  │  └─lib
    │  │  │  │  │      ├─compile
    │  │  │  │  │      │  ├─codegen
    │  │  │  │  │      │  ├─jtd
    │  │  │  │  │      │  └─validate
    │  │  │  │  │      ├─refs
    │  │  │  │  │      │  ├─json-schema-2019-09
    │  │  │  │  │      │  │  └─meta
    │  │  │  │  │      │  └─json-schema-2020-12
    │  │  │  │  │      │      └─meta
    │  │  │  │  │      ├─runtime
    │  │  │  │  │      ├─standalone
    │  │  │  │  │      ├─types
    │  │  │  │  │      └─vocabularies
    │  │  │  │  │          ├─applicator
    │  │  │  │  │          ├─core
    │  │  │  │  │          ├─discriminator
    │  │  │  │  │          ├─dynamic
    │  │  │  │  │          ├─format
    │  │  │  │  │          ├─jtd
    │  │  │  │  │          ├─unevaluated
    │  │  │  │  │          └─validation
    │  │  │  │  ├─ajv-keywords
    │  │  │  │  │  ├─dist
    │  │  │  │  │  │  ├─definitions
    │  │  │  │  │  │  └─keywords
    │  │  │  │  │  └─src
    │  │  │  │  │      ├─definitions
    │  │  │  │  │      └─keywords
    │  │  │  │  ├─json-schema-traverse
    │  │  │  │  │  ├─.github
    │  │  │  │  │  │  └─workflows
    │  │  │  │  │  └─spec
    │  │  │  │  │      └─fixtures
    │  │  │  │  ├─schema-utils
    │  │  │  │  │  ├─declarations
    │  │  │  │  │  │  ├─keywords
    │  │  │  │  │  │  └─util
    │  │  │  │  │  └─dist
    │  │  │  │  │      ├─keywords
    │  │  │  │  │      └─util
    │  │  │  │  └─source-map
    │  │  │  │      ├─dist
    │  │  │  │      └─lib
    │  │  │  └─types
    │  │  ├─css-prefers-color-scheme
    │  │  │  └─dist
    │  │  ├─css-select
    │  │  │  └─lib
    │  │  │      └─pseudo-selectors
    │  │  ├─css-select-base-adapter
    │  │  │  └─test
    │  │  ├─css-tree
    │  │  │  ├─data
    │  │  │  ├─dist
    │  │  │  ├─lib
    │  │  │  │  ├─common
    │  │  │  │  ├─convertor
    │  │  │  │  ├─definition-syntax
    │  │  │  │  ├─generator
    │  │  │  │  ├─lexer
    │  │  │  │  ├─parser
    │  │  │  │  ├─syntax
    │  │  │  │  │  ├─atrule
    │  │  │  │  │  ├─config
    │  │  │  │  │  ├─function
    │  │  │  │  │  ├─node
    │  │  │  │  │  ├─pseudo
    │  │  │  │  │  │  └─common
    │  │  │  │  │  └─scope
    │  │  │  │  ├─tokenizer
    │  │  │  │  ├─utils
    │  │  │  │  └─walker
    │  │  │  └─node_modules
    │  │  │      └─source-map
    │  │  │          ├─dist
    │  │  │          └─lib
    │  │  ├─css-what
    │  │  │  └─lib
    │  │  │      ├─commonjs
    │  │  │      └─es
    │  │  ├─css.escape
    │  │  ├─cssdb
    │  │  ├─cssesc
    │  │  │  ├─bin
    │  │  │  └─man
    │  │  ├─cssnano
    │  │  │  ├─src
    │  │  │  │  ├─postcss-discard-comments
    │  │  │  │  ├─postcss-discard-empty
    │  │  │  │  └─postcss-normalize-whitespace
    │  │  │  └─types
    │  │  ├─cssnano-preset-default
    │  │  │  ├─src
    │  │  │  └─types
    │  │  ├─cssnano-utils
    │  │  │  ├─src
    │  │  │  └─types
    │  │  ├─csso
    │  │  │  ├─dist
    │  │  │  ├─lib
    │  │  │  │  ├─clean
    │  │  │  │  ├─replace
    │  │  │  │  │  ├─atrule
    │  │  │  │  │  └─property
    │  │  │  │  └─restructure
    │  │  │  │      └─prepare
    │  │  │  └─node_modules
    │  │  │      ├─css-tree
    │  │  │      │  ├─data
    │  │  │      │  ├─dist
    │  │  │      │  └─lib
    │  │  │      │      ├─common
    │  │  │      │      ├─convertor
    │  │  │      │      ├─definition-syntax
    │  │  │      │      ├─generator
    │  │  │      │      ├─lexer
    │  │  │      │      ├─parser
    │  │  │      │      ├─syntax
    │  │  │      │      │  ├─atrule
    │  │  │      │      │  ├─config
    │  │  │      │      │  ├─function
    │  │  │      │      │  ├─node
    │  │  │      │      │  ├─pseudo
    │  │  │      │      │  │  └─common
    │  │  │      │      │  └─scope
    │  │  │      │      ├─tokenizer
    │  │  │      │      ├─utils
    │  │  │      │      └─walker
    │  │  │      ├─mdn-data
    │  │  │      │  ├─api
    │  │  │      │  ├─css
    │  │  │      │  └─l10n
    │  │  │      └─source-map
    │  │  │          ├─dist
    │  │  │          └─lib
    │  │  ├─cssom
    │  │  │  └─lib
    │  │  ├─cssstyle
    │  │  │  ├─lib
    │  │  │  │  ├─properties
    │  │  │  │  └─utils
    │  │  │  └─node_modules
    │  │  │      └─cssom
    │  │  │          └─lib
    │  │  ├─csstype
    │  │  ├─damerau-levenshtein
    │  │  │  ├─scripts
    │  │  │  └─test
    │  │  ├─data-urls
    │  │  │  └─lib
    │  │  ├─debug
    │  │  │  └─src
    │  │  ├─decimal.js
    │  │  ├─dedent
    │  │  │  └─dist
    │  │  ├─deep-equal
    │  │  │  ├─example
    │  │  │  └─test
    │  │  ├─deep-is
    │  │  │  ├─example
    │  │  │  └─test
    │  │  ├─deepmerge
    │  │  │  └─dist
    │  │  ├─default-gateway
    │  │  ├─define-lazy-prop
    │  │  ├─define-properties
    │  │  │  └─.github
    │  │  ├─delayed-stream
    │  │  │  └─lib
    │  │  ├─depd
    │  │  │  └─lib
    │  │  │      └─browser
    │  │  ├─dequal
    │  │  │  ├─dist
    │  │  │  └─lite
    │  │  ├─destroy
    │  │  ├─detect-newline
    │  │  ├─detect-node
    │  │  ├─detect-port-alt
    │  │  │  ├─.vscode
    │  │  │  ├─bin
    │  │  │  ├─lib
    │  │  │  └─node_modules
    │  │  │      ├─debug
    │  │  │      │  └─src
    │  │  │      └─ms
    │  │  ├─didyoumean
    │  │  ├─diff-sequences
    │  │  │  ├─build
    │  │  │  └─perf
    │  │  ├─dir-glob
    │  │  ├─dlv
    │  │  │  └─dist
    │  │  ├─dns-equal
    │  │  ├─dns-packet
    │  │  ├─doctrine
    │  │  │  └─lib
    │  │  ├─dom-accessibility-api
    │  │  │  └─dist
    │  │  │      └─polyfills
    │  │  ├─dom-converter
    │  │  │  └─lib
    │  │  ├─dom-serializer
    │  │  │  └─lib
    │  │  │      └─esm
    │  │  ├─domelementtype
    │  │  │  └─lib
    │  │  │      └─esm
    │  │  ├─domexception
    │  │  │  ├─lib
    │  │  │  └─node_modules
    │  │  │      └─webidl-conversions
    │  │  │          └─lib
    │  │  ├─domhandler
    │  │  │  └─lib
    │  │  ├─domutils
    │  │  │  └─lib
    │  │  ├─dot-case
    │  │  │  ├─dist
    │  │  │  └─dist.es2015
    │  │  ├─dotenv
    │  │  │  ├─lib
    │  │  │  └─types
    │  │  ├─dotenv-expand
    │  │  │  └─lib
    │  │  ├─duplexer
    │  │  │  └─test
    │  │  ├─ee-first
    │  │  ├─ejs
    │  │  │  ├─bin
    │  │  │  └─lib
    │  │  ├─electron-to-chromium
    │  │  ├─emittery
    │  │  ├─emoji-regex
    │  │  │  └─es2015
    │  │  ├─emojis-list
    │  │  ├─encodeurl
    │  │  ├─enhanced-resolve
    │  │  │  └─lib
    │  │  │      └─util
    │  │  ├─entities
    │  │  │  └─lib
    │  │  │      └─maps
    │  │  ├─envinfo
    │  │  │  └─dist
    │  │  ├─error-ex
    │  │  ├─error-stack-parser
    │  │  │  └─dist
    │  │  ├─es-abstract
    │  │  │  ├─2015
    │  │  │  ├─2016
    │  │  │  ├─2017
    │  │  │  ├─2018
    │  │  │  ├─2019
    │  │  │  ├─2020
    │  │  │  │  ├─BigInt
    │  │  │  │  └─Number
    │  │  │  ├─2021
    │  │  │  │  ├─BigInt
    │  │  │  │  └─Number
    │  │  │  ├─2022
    │  │  │  │  ├─BigInt
    │  │  │  │  └─Number
    │  │  │  ├─2023
    │  │  │  │  ├─BigInt
    │  │  │  │  └─Number
    │  │  │  ├─5
    │  │  │  ├─helpers
    │  │  │  └─operations
    │  │  ├─es-array-method-boxes-properly
    │  │  │  ├─.github
    │  │  │  └─test
    │  │  ├─es-get-iterator
    │  │  │  ├─.github
    │  │  │  └─test
    │  │  ├─es-module-lexer
    │  │  │  ├─dist
    │  │  │  └─types
    │  │  ├─es-set-tostringtag
    │  │  │  └─test
    │  │  ├─es-shim-unscopables
    │  │  │  ├─.github
    │  │  │  └─test
    │  │  ├─es-to-primitive
    │  │  │  ├─.github
    │  │  │  ├─helpers
    │  │  │  └─test
    │  │  ├─escalade
    │  │  │  ├─dist
    │  │  │  └─sync
    │  │  ├─escape-html
    │  │  ├─escape-string-regexp
    │  │  ├─escodegen
    │  │  │  ├─bin
    │  │  │  └─node_modules
    │  │  │      └─source-map
    │  │  │          ├─dist
    │  │  │          └─lib
    │  │  ├─eslint
    │  │  │  ├─bin
    │  │  │  ├─conf
    │  │  │  ├─lib
    │  │  │  │  ├─cli-engine
    │  │  │  │  │  └─formatters
    │  │  │  │  ├─config
    │  │  │  │  ├─eslint
    │  │  │  │  ├─linter
    │  │  │  │  │  └─code-path-analysis
    │  │  │  │  ├─rule-tester
    │  │  │  │  ├─rules
    │  │  │  │  │  └─utils
    │  │  │  │  │      ├─patterns
    │  │  │  │  │      └─unicode
    │  │  │  │  ├─shared
    │  │  │  │  └─source-code
    │  │  │  │      └─token-store
    │  │  │  ├─messages
    │  │  │  └─node_modules
    │  │  │      ├─.bin
    │  │  │      ├─ansi-styles
    │  │  │      ├─argparse
    │  │  │      │  └─lib
    │  │  │      ├─chalk
    │  │  │      │  └─source
    │  │  │      ├─color-convert
    │  │  │      ├─color-name
    │  │  │      ├─escape-string-regexp
    │  │  │      ├─globals
    │  │  │      ├─has-flag
    │  │  │      ├─js-yaml
    │  │  │      │  ├─bin
    │  │  │      │  ├─dist
    │  │  │      │  └─lib
    │  │  │      │      ├─schema
    │  │  │      │      └─type
    │  │  │      ├─supports-color
    │  │  │      └─type-fest
    │  │  │          ├─source
    │  │  │          └─ts41
    │  │  ├─eslint-config-react-app
    │  │  ├─eslint-import-resolver-node
    │  │  │  └─node_modules
    │  │  │      └─debug
    │  │  │          └─src
    │  │  ├─eslint-module-utils
    │  │  │  └─node_modules
    │  │  │      └─debug
    │  │  │          └─src
    │  │  ├─eslint-plugin-flowtype
    │  │  │  └─dist
    │  │  │      ├─bin
    │  │  │      ├─configs
    │  │  │      ├─rules
    │  │  │      │  ├─arrayStyle
    │  │  │      │  └─typeColonSpacing
    │  │  │      └─utilities
    │  │  ├─eslint-plugin-import
    │  │  │  ├─config
    │  │  │  ├─docs
    │  │  │  │  └─rules
    │  │  │  ├─lib
    │  │  │  │  ├─core
    │  │  │  │  └─rules
    │  │  │  ├─memo-parser
    │  │  │  └─node_modules
    │  │  │      ├─.bin
    │  │  │      ├─debug
    │  │  │      │  └─src
    │  │  │      ├─doctrine
    │  │  │      │  └─lib
    │  │  │      └─semver
    │  │  │          └─bin
    │  │  ├─eslint-plugin-jest
    │  │  │  ├─docs
    │  │  │  │  └─rules
    │  │  │  └─lib
    │  │  │      ├─processors
    │  │  │      └─rules
    │  │  ├─eslint-plugin-jsx-a11y
    │  │  │  ├─docs
    │  │  │  │  └─rules
    │  │  │  ├─lib
    │  │  │  │  ├─rules
    │  │  │  │  └─util
    │  │  │  │      └─implicitRoles
    │  │  │  ├─node_modules
    │  │  │  │  ├─.bin
    │  │  │  │  └─semver
    │  │  │  │      └─bin
    │  │  │  ├─__mocks__
    │  │  │  └─__tests__
    │  │  │      ├─src
    │  │  │      │  ├─rules
    │  │  │      │  └─util
    │  │  │      │      └─implicitRoles
    │  │  │      └─__util__
    │  │  ├─eslint-plugin-react
    │  │  │  ├─configs
    │  │  │  ├─lib
    │  │  │  │  ├─rules
    │  │  │  │  └─util
    │  │  │  └─node_modules
    │  │  │      ├─.bin
    │  │  │      ├─doctrine
    │  │  │      │  └─lib
    │  │  │      ├─resolve
    │  │  │      │  ├─.github
    │  │  │      │  ├─bin
    │  │  │      │  ├─example
    │  │  │      │  ├─lib
    │  │  │      │  └─test
    │  │  │      │      ├─dotdot
    │  │  │      │      │  └─abc
    │  │  │      │      ├─module_dir
    │  │  │      │      │  ├─xmodules
    │  │  │      │      │  │  └─aaa
    │  │  │      │      │  ├─ymodules
    │  │  │      │      │  │  └─aaa
    │  │  │      │      │  └─zmodules
    │  │  │      │      │      └─bbb
    │  │  │      │      ├─node_path
    │  │  │      │      │  ├─x
    │  │  │      │      │  │  ├─aaa
    │  │  │      │      │  │  └─ccc
    │  │  │      │      │  └─y
    │  │  │      │      │      ├─bbb
    │  │  │      │      │      └─ccc
    │  │  │      │      ├─pathfilter
    │  │  │      │      │  └─deep_ref
    │  │  │      │      ├─precedence
    │  │  │      │      │  ├─aaa
    │  │  │      │      │  └─bbb
    │  │  │      │      ├─resolver
    │  │  │      │      │  ├─baz
    │  │  │      │      │  ├─browser_field
    │  │  │      │      │  ├─dot_main
    │  │  │      │      │  ├─dot_slash_main
    │  │  │      │      │  ├─empty_main
    │  │  │      │      │  ├─false_main
    │  │  │      │      │  ├─incorrect_main
    │  │  │      │      │  ├─invalid_main
    │  │  │      │      │  ├─malformed_package_json
    │  │  │      │      │  ├─missing_index
    │  │  │      │      │  ├─missing_main
    │  │  │      │      │  ├─multirepo
    │  │  │      │      │  │  └─packages
    │  │  │      │      │  │      ├─package-a
    │  │  │      │      │  │      └─package-b
    │  │  │      │      │  ├─nested_symlinks
    │  │  │      │      │  │  └─mylib
    │  │  │      │      │  ├─null_main
    │  │  │      │      │  ├─other_path
    │  │  │      │      │  │  └─lib
    │  │  │      │      │  ├─quux
    │  │  │      │      │  │  └─foo
    │  │  │      │      │  ├─same_names
    │  │  │      │      │  │  └─foo
    │  │  │      │      │  ├─symlinked
    │  │  │      │      │  │  ├─package
    │  │  │      │      │  │  └─_
    │  │  │      │      │  │      ├─node_modules
    │  │  │      │      │  │      └─symlink_target
    │  │  │      │      │  └─without_basedir
    │  │  │      │      └─shadowed_core
    │  │  │      │          └─node_modules
    │  │  │      │              └─util
    │  │  │      └─semver
    │  │  │          └─bin
    │  │  ├─eslint-plugin-react-hooks
    │  │  │  └─cjs
    │  │  ├─eslint-plugin-testing-library
    │  │  │  ├─configs
    │  │  │  ├─create-testing-library-rule
    │  │  │  ├─node-utils
    │  │  │  ├─rules
    │  │  │  └─utils
    │  │  ├─eslint-scope
    │  │  │  ├─dist
    │  │  │  └─lib
    │  │  ├─eslint-visitor-keys
    │  │  │  ├─dist
    │  │  │  └─lib
    │  │  ├─eslint-webpack-plugin
    │  │  │  ├─dist
    │  │  │  ├─node_modules
    │  │  │  │  ├─ajv
    │  │  │  │  │  ├─dist
    │  │  │  │  │  │  ├─compile
    │  │  │  │  │  │  │  ├─codegen
    │  │  │  │  │  │  │  ├─jtd
    │  │  │  │  │  │  │  └─validate
    │  │  │  │  │  │  ├─refs
    │  │  │  │  │  │  │  ├─json-schema-2019-09
    │  │  │  │  │  │  │  │  └─meta
    │  │  │  │  │  │  │  └─json-schema-2020-12
    │  │  │  │  │  │  │      └─meta
    │  │  │  │  │  │  ├─runtime
    │  │  │  │  │  │  ├─standalone
    │  │  │  │  │  │  ├─types
    │  │  │  │  │  │  └─vocabularies
    │  │  │  │  │  │      ├─applicator
    │  │  │  │  │  │      ├─core
    │  │  │  │  │  │      ├─discriminator
    │  │  │  │  │  │      ├─dynamic
    │  │  │  │  │  │      ├─format
    │  │  │  │  │  │      ├─jtd
    │  │  │  │  │  │      ├─unevaluated
    │  │  │  │  │  │      └─validation
    │  │  │  │  │  └─lib
    │  │  │  │  │      ├─compile
    │  │  │  │  │      │  ├─codegen
    │  │  │  │  │      │  ├─jtd
    │  │  │  │  │      │  └─validate
    │  │  │  │  │      ├─refs
    │  │  │  │  │      │  ├─json-schema-2019-09
    │  │  │  │  │      │  │  └─meta
    │  │  │  │  │      │  └─json-schema-2020-12
    │  │  │  │  │      │      └─meta
    │  │  │  │  │      ├─runtime
    │  │  │  │  │      ├─standalone
    │  │  │  │  │      ├─types
    │  │  │  │  │      └─vocabularies
    │  │  │  │  │          ├─applicator
    │  │  │  │  │          ├─core
    │  │  │  │  │          ├─discriminator
    │  │  │  │  │          ├─dynamic
    │  │  │  │  │          ├─format
    │  │  │  │  │          ├─jtd
    │  │  │  │  │          ├─unevaluated
    │  │  │  │  │          └─validation
    │  │  │  │  ├─ajv-keywords
    │  │  │  │  │  ├─dist
    │  │  │  │  │  │  ├─definitions
    │  │  │  │  │  │  └─keywords
    │  │  │  │  │  └─src
    │  │  │  │  │      ├─definitions
    │  │  │  │  │      └─keywords
    │  │  │  │  ├─has-flag
    │  │  │  │  ├─jest-worker
    │  │  │  │  │  └─build
    │  │  │  │  │      ├─base
    │  │  │  │  │      └─workers
    │  │  │  │  ├─json-schema-traverse
    │  │  │  │  │  ├─.github
    │  │  │  │  │  │  └─workflows
    │  │  │  │  │  └─spec
    │  │  │  │  │      └─fixtures
    │  │  │  │  ├─schema-utils
    │  │  │  │  │  ├─declarations
    │  │  │  │  │  │  ├─keywords
    │  │  │  │  │  │  └─util
    │  │  │  │  │  └─dist
    │  │  │  │  │      ├─keywords
    │  │  │  │  │      └─util
    │  │  │  │  └─supports-color
    │  │  │  └─types
    │  │  ├─espree
    │  │  │  ├─dist
    │  │  │  └─lib
    │  │  ├─esprima
    │  │  │  ├─bin
    │  │  │  └─dist
    │  │  ├─esquery
    │  │  │  └─dist
    │  │  ├─esrecurse
    │  │  ├─estraverse
    │  │  ├─estree-walker
    │  │  │  ├─dist
    │  │  │  ├─src
    │  │  │  └─types
    │  │  ├─esutils
    │  │  │  └─lib
    │  │  ├─etag
    │  │  ├─eventemitter3
    │  │  │  └─umd
    │  │  ├─events
    │  │  │  ├─.github
    │  │  │  └─tests
    │  │  ├─execa
    │  │  │  └─lib
    │  │  ├─exit
    │  │  │  ├─lib
    │  │  │  └─test
    │  │  │      └─fixtures
    │  │  ├─expect
    │  │  │  └─build
    │  │  ├─express
    │  │  │  ├─lib
    │  │  │  │  ├─middleware
    │  │  │  │  └─router
    │  │  │  └─node_modules
    │  │  │      ├─array-flatten
    │  │  │      ├─debug
    │  │  │      │  └─src
    │  │  │      └─ms
    │  │  ├─fast-deep-equal
    │  │  │  └─es6
    │  │  ├─fast-glob
    │  │  │  ├─node_modules
    │  │  │  │  └─glob-parent
    │  │  │  └─out
    │  │  │      ├─managers
    │  │  │      ├─providers
    │  │  │      │  ├─filters
    │  │  │      │  ├─matchers
    │  │  │      │  └─transformers
    │  │  │      ├─readers
    │  │  │      ├─types
    │  │  │      └─utils
    │  │  ├─fast-json-stable-stringify
    │  │  │  ├─.github
    │  │  │  ├─benchmark
    │  │  │  ├─example
    │  │  │  └─test
    │  │  ├─fast-levenshtein
    │  │  ├─fastest-levenshtein
    │  │  │  └─esm
    │  │  ├─fastq
    │  │  │  ├─.github
    │  │  │  │  └─workflows
    │  │  │  └─test
    │  │  ├─faye-websocket
    │  │  │  └─lib
    │  │  │      └─faye
    │  │  │          └─websocket
    │  │  │              └─api
    │  │  ├─fb-watchman
    │  │  ├─file-entry-cache
    │  │  ├─file-loader
    │  │  │  └─dist
    │  │  ├─filelist
    │  │  │  └─node_modules
    │  │  │      ├─brace-expansion
    │  │  │      │  └─.github
    │  │  │      └─minimatch
    │  │  │          └─lib
    │  │  ├─filesize
    │  │  │  └─lib
    │  │  ├─fill-range
    │  │  ├─finalhandler
    │  │  │  └─node_modules
    │  │  │      ├─debug
    │  │  │      │  └─src
    │  │  │      └─ms
    │  │  ├─find-cache-dir
    │  │  ├─find-up
    │  │  ├─flat-cache
    │  │  │  └─src
    │  │  ├─flatted
    │  │  │  ├─cjs
    │  │  │  ├─esm
    │  │  │  └─php
    │  │  ├─follow-redirects
    │  │  ├─for-each
    │  │  │  └─test
    │  │  ├─fork-ts-checker-webpack-plugin
    │  │  │  ├─lib
    │  │  │  │  ├─error
    │  │  │  │  ├─eslint-reporter
    │  │  │  │  │  ├─issue
    │  │  │  │  │  ├─reporter
    │  │  │  │  │  └─types
    │  │  │  │  ├─formatter
    │  │  │  │  │  └─types
    │  │  │  │  ├─hooks
    │  │  │  │  ├─issue
    │  │  │  │  ├─logger
    │  │  │  │  ├─profile
    │  │  │  │  ├─reporter
    │  │  │  │  │  └─reporter-rpc
    │  │  │  │  ├─rpc
    │  │  │  │  │  ├─error
    │  │  │  │  │  └─rpc-ipc
    │  │  │  │  │      └─error
    │  │  │  │  ├─typescript-reporter
    │  │  │  │  │  ├─extension
    │  │  │  │  │  │  └─vue
    │  │  │  │  │  │      └─types
    │  │  │  │  │  ├─file-system
    │  │  │  │  │  ├─issue
    │  │  │  │  │  ├─profile
    │  │  │  │  │  └─reporter
    │  │  │  │  ├─utils
    │  │  │  │  │  ├─array
    │  │  │  │  │  ├─async
    │  │  │  │  │  └─path
    │  │  │  │  └─watch
    │  │  │  └─node_modules
    │  │  │      ├─ansi-styles
    │  │  │      ├─chalk
    │  │  │      │  └─source
    │  │  │      ├─color-convert
    │  │  │      ├─color-name
    │  │  │      ├─cosmiconfig
    │  │  │      │  └─dist
    │  │  │      ├─fs-extra
    │  │  │      │  └─lib
    │  │  │      │      ├─copy
    │  │  │      │      ├─copy-sync
    │  │  │      │      ├─empty
    │  │  │      │      ├─ensure
    │  │  │      │      ├─fs
    │  │  │      │      ├─json
    │  │  │      │      ├─mkdirs
    │  │  │      │      ├─move
    │  │  │      │      ├─move-sync
    │  │  │      │      ├─output
    │  │  │      │      ├─path-exists
    │  │  │      │      ├─remove
    │  │  │      │      └─util
    │  │  │      ├─has-flag
    │  │  │      ├─schema-utils
    │  │  │      │  ├─declarations
    │  │  │      │  │  ├─keywords
    │  │  │      │  │  └─util
    │  │  │      │  └─dist
    │  │  │      │      ├─keywords
    │  │  │      │      └─util
    │  │  │      ├─supports-color
    │  │  │      └─tapable
    │  │  │          └─lib
    │  │  ├─form-data
    │  │  │  └─lib
    │  │  ├─forwarded
    │  │  ├─fraction.js
    │  │  ├─fresh
    │  │  ├─fs-extra
    │  │  │  └─lib
    │  │  │      ├─copy
    │  │  │      ├─empty
    │  │  │      ├─ensure
    │  │  │      ├─fs
    │  │  │      ├─json
    │  │  │      ├─mkdirs
    │  │  │      ├─move
    │  │  │      ├─output-file
    │  │  │      ├─path-exists
    │  │  │      ├─remove
    │  │  │      └─util
    │  │  ├─fs-monkey
    │  │  │  ├─docs
    │  │  │  │  └─api
    │  │  │  └─lib
    │  │  │      └─util
    │  │  ├─fs.realpath
    │  │  ├─function-bind
    │  │  │  └─test
    │  │  ├─function.prototype.name
    │  │  │  ├─.github
    │  │  │  ├─helpers
    │  │  │  └─test
    │  │  ├─functions-have-names
    │  │  │  ├─.github
    │  │  │  └─test
    │  │  ├─gensync
    │  │  │  └─test
    │  │  ├─get-caller-file
    │  │  ├─get-intrinsic
    │  │  │  ├─.github
    │  │  │  └─test
    │  │  ├─get-own-enumerable-property-symbols
    │  │  │  └─lib
    │  │  ├─get-package-type
    │  │  ├─get-stream
    │  │  ├─get-symbol-description
    │  │  │  ├─.github
    │  │  │  └─test
    │  │  ├─glob
    │  │  ├─glob-parent
    │  │  ├─glob-to-regexp
    │  │  ├─global-modules
    │  │  ├─global-prefix
    │  │  │  └─node_modules
    │  │  │      ├─.bin
    │  │  │      └─which
    │  │  │          └─bin
    │  │  ├─globals
    │  │  ├─globalthis
    │  │  │  └─test
    │  │  ├─globby
    │  │  ├─gopd
    │  │  │  ├─.github
    │  │  │  └─test
    │  │  ├─graceful-fs
    │  │  ├─graphemer
    │  │  │  └─lib
    │  │  ├─gzip-size
    │  │  ├─handle-thing
    │  │  │  ├─lib
    │  │  │  └─test
    │  │  ├─harmony-reflect
    │  │  ├─has
    │  │  │  ├─src
    │  │  │  └─test
    │  │  ├─has-bigints
    │  │  │  ├─.github
    │  │  │  └─test
    │  │  ├─has-flag
    │  │  ├─has-property-descriptors
    │  │  │  ├─.github
    │  │  │  └─test
    │  │  ├─has-proto
    │  │  │  ├─.github
    │  │  │  └─test
    │  │  ├─has-symbols
    │  │  │  ├─.github
    │  │  │  └─test
    │  │  │      └─shams
    │  │  ├─has-tostringtag
    │  │  │  ├─.github
    │  │  │  └─test
    │  │  │      └─shams
    │  │  ├─he
    │  │  │  ├─bin
    │  │  │  └─man
    │  │  ├─hoopy
    │  │  ├─hpack.js
    │  │  │  ├─bin
    │  │  │  ├─lib
    │  │  │  │  └─hpack
    │  │  │  ├─node_modules
    │  │  │  │  ├─isarray
    │  │  │  │  ├─readable-stream
    │  │  │  │  │  ├─doc
    │  │  │  │  │  │  └─wg-meetings
    │  │  │  │  │  └─lib
    │  │  │  │  │      └─internal
    │  │  │  │  │          └─streams
    │  │  │  │  ├─safe-buffer
    │  │  │  │  └─string_decoder
    │  │  │  │      └─lib
    │  │  │  ├─test
    │  │  │  └─tools
    │  │  ├─html-encoding-sniffer
    │  │  │  └─lib
    │  │  ├─html-entities
    │  │  │  └─lib
    │  │  ├─html-escaper
    │  │  │  ├─cjs
    │  │  │  ├─esm
    │  │  │  └─test
    │  │  ├─html-minifier-terser
    │  │  │  └─src
    │  │  ├─html-webpack-plugin
    │  │  │  └─lib
    │  │  ├─htmlparser2
    │  │  │  └─lib
    │  │  ├─http-deceiver
    │  │  │  ├─lib
    │  │  │  └─test
    │  │  ├─http-errors
    │  │  ├─http-parser-js
    │  │  ├─http-proxy
    │  │  │  └─lib
    │  │  │      └─http-proxy
    │  │  │          └─passes
    │  │  ├─http-proxy-agent
    │  │  │  └─dist
    │  │  ├─http-proxy-middleware
    │  │  │  └─dist
    │  │  │      └─handlers
    │  │  ├─https-proxy-agent
    │  │  │  └─dist
    │  │  ├─human-signals
    │  │  │  └─build
    │  │  │      └─src
    │  │  ├─iconv-lite
    │  │  │  ├─.github
    │  │  │  ├─encodings
    │  │  │  │  └─tables
    │  │  │  └─lib
    │  │  ├─icss-utils
    │  │  │  └─src
    │  │  ├─idb
    │  │  │  └─build
    │  │  ├─identity-obj-proxy
    │  │  │  └─src
    │  │  │      ├─test-redirections
    │  │  │      └─__tests__
    │  │  ├─ignore
    │  │  ├─immer
    │  │  │  ├─compat
    │  │  │  │  └─pre-3.7
    │  │  │  │      └─dist
    │  │  │  ├─dist
    │  │  │  │  ├─core
    │  │  │  │  ├─plugins
    │  │  │  │  ├─types
    │  │  │  │  └─utils
    │  │  │  └─src
    │  │  │      ├─core
    │  │  │      ├─plugins
    │  │  │      ├─types
    │  │  │      └─utils
    │  │  ├─import-fresh
    │  │  │  └─node_modules
    │  │  │      └─resolve-from
    │  │  ├─import-local
    │  │  │  └─fixtures
    │  │  ├─imurmurhash
    │  │  ├─indent-string
    │  │  ├─inflight
    │  │  ├─inherits
    │  │  ├─ini
    │  │  ├─internal-slot
    │  │  │  ├─.github
    │  │  │  └─test
    │  │  ├─interpret
    │  │  ├─ipaddr.js
    │  │  │  └─lib
    │  │  ├─is-arguments
    │  │  │  ├─.github
    │  │  │  └─test
    │  │  ├─is-array-buffer
    │  │  │  ├─.github
    │  │  │  └─test
    │  │  ├─is-arrayish
    │  │  ├─is-bigint
    │  │  │  ├─.github
    │  │  │  └─test
    │  │  ├─is-binary-path
    │  │  ├─is-boolean-object
    │  │  │  ├─.github
    │  │  │  └─test
    │  │  ├─is-callable
    │  │  │  ├─.github
    │  │  │  └─test
    │  │  ├─is-core-module
    │  │  │  └─test
    │  │  ├─is-date-object
    │  │  │  ├─.github
    │  │  │  └─test
    │  │  ├─is-docker
    │  │  ├─is-extglob
    │  │  ├─is-fullwidth-code-point
    │  │  ├─is-generator-fn
    │  │  ├─is-glob
    │  │  ├─is-map
    │  │  │  ├─.github
    │  │  │  └─test
    │  │  ├─is-module
    │  │  ├─is-negative-zero
    │  │  │  ├─.github
    │  │  │  └─test
    │  │  ├─is-number
    │  │  ├─is-number-object
    │  │  │  ├─.github
    │  │  │  └─test
    │  │  ├─is-obj
    │  │  ├─is-path-inside
    │  │  ├─is-plain-obj
    │  │  ├─is-plain-object
    │  │  ├─is-potential-custom-element-name
    │  │  ├─is-regex
    │  │  │  └─test
    │  │  ├─is-regexp
    │  │  ├─is-root
    │  │  ├─is-set
    │  │  │  ├─.github
    │  │  │  └─test
    │  │  ├─is-shared-array-buffer
    │  │  │  ├─.github
    │  │  │  └─test
    │  │  ├─is-stream
    │  │  ├─is-string
    │  │  │  ├─.github
    │  │  │  └─test
    │  │  ├─is-symbol
    │  │  │  ├─.github
    │  │  │  └─test
    │  │  ├─is-typed-array
    │  │  │  ├─.github
    │  │  │  └─test
    │  │  ├─is-typedarray
    │  │  ├─is-weakmap
    │  │  │  ├─.github
    │  │  │  │  └─workflows
    │  │  │  └─test
    │  │  ├─is-weakref
    │  │  │  ├─.github
    │  │  │  └─test
    │  │  ├─is-weakset
    │  │  │  ├─.github
    │  │  │  └─test
    │  │  ├─is-wsl
    │  │  ├─isarray
    │  │  ├─isexe
    │  │  │  └─test
    │  │  ├─isobject
    │  │  ├─istanbul-lib-coverage
    │  │  │  └─lib
    │  │  ├─istanbul-lib-instrument
    │  │  │  ├─node_modules
    │  │  │  │  ├─.bin
    │  │  │  │  └─semver
    │  │  │  │      └─bin
    │  │  │  └─src
    │  │  ├─istanbul-lib-report
    │  │  │  ├─lib
    │  │  │  └─node_modules
    │  │  │      ├─has-flag
    │  │  │      └─supports-color
    │  │  ├─istanbul-lib-source-maps
    │  │  │  ├─lib
    │  │  │  └─node_modules
    │  │  │      └─source-map
    │  │  │          ├─dist
    │  │  │          └─lib
    │  │  ├─istanbul-reports
    │  │  │  └─lib
    │  │  │      ├─clover
    │  │  │      ├─cobertura
    │  │  │      ├─html
    │  │  │      │  └─assets
    │  │  │      │      └─vendor
    │  │  │      ├─html-spa
    │  │  │      │  ├─assets
    │  │  │      │  └─src
    │  │  │      ├─json
    │  │  │      ├─json-summary
    │  │  │      ├─lcov
    │  │  │      ├─lcovonly
    │  │  │      ├─none
    │  │  │      ├─teamcity
    │  │  │      ├─text
    │  │  │      ├─text-lcov
    │  │  │      └─text-summary
    │  │  ├─jake
    │  │  │  ├─bin
    │  │  │  ├─lib
    │  │  │  │  ├─task
    │  │  │  │  └─utils
    │  │  │  ├─node_modules
    │  │  │  │  ├─ansi-styles
    │  │  │  │  ├─chalk
    │  │  │  │  │  └─source
    │  │  │  │  ├─color-convert
    │  │  │  │  ├─color-name
    │  │  │  │  ├─has-flag
    │  │  │  │  └─supports-color
    │  │  │  └─test
    │  │  │      ├─integration
    │  │  │      │  └─jakelib
    │  │  │      └─unit
    │  │  ├─jest
    │  │  │  ├─bin
    │  │  │  └─build
    │  │  ├─jest-changed-files
    │  │  │  └─build
    │  │  ├─jest-circus
    │  │  │  ├─build
    │  │  │  │  └─legacy-code-todo-rewrite
    │  │  │  └─node_modules
    │  │  │      ├─ansi-styles
    │  │  │      ├─chalk
    │  │  │      │  └─source
    │  │  │      ├─color-convert
    │  │  │      ├─color-name
    │  │  │      ├─has-flag
    │  │  │      └─supports-color
    │  │  ├─jest-cli
    │  │  │  ├─bin
    │  │  │  ├─build
    │  │  │  │  ├─cli
    │  │  │  │  └─init
    │  │  │  └─node_modules
    │  │  │      ├─ansi-styles
    │  │  │      ├─chalk
    │  │  │      │  └─source
    │  │  │      ├─color-convert
    │  │  │      ├─color-name
    │  │  │      ├─has-flag
    │  │  │      └─supports-color
    │  │  ├─jest-config
    │  │  │  ├─build
    │  │  │  └─node_modules
    │  │  │      ├─ansi-styles
    │  │  │      ├─chalk
    │  │  │      │  └─source
    │  │  │      ├─color-convert
    │  │  │      ├─color-name
    │  │  │      ├─has-flag
    │  │  │      └─supports-color
    │  │  ├─jest-diff
    │  │  │  ├─build
    │  │  │  └─node_modules
    │  │  │      ├─ansi-styles
    │  │  │      ├─chalk
    │  │  │      │  └─source
    │  │  │      ├─color-convert
    │  │  │      ├─color-name
    │  │  │      ├─has-flag
    │  │  │      └─supports-color
    │  │  ├─jest-docblock
    │  │  │  └─build
    │  │  ├─jest-each
    │  │  │  ├─build
    │  │  │  │  └─table
    │  │  │  └─node_modules
    │  │  │      ├─ansi-styles
    │  │  │      ├─chalk
    │  │  │      │  └─source
    │  │  │      ├─color-convert
    │  │  │      ├─color-name
    │  │  │      ├─has-flag
    │  │  │      └─supports-color
    │  │  ├─jest-environment-jsdom
    │  │  │  └─build
    │  │  ├─jest-environment-node
    │  │  │  └─build
    │  │  ├─jest-get-type
    │  │  │  └─build
    │  │  ├─jest-haste-map
    │  │  │  └─build
    │  │  │      ├─crawlers
    │  │  │      ├─lib
    │  │  │      └─watchers
    │  │  ├─jest-jasmine2
    │  │  │  ├─build
    │  │  │  │  └─jasmine
    │  │  │  └─node_modules
    │  │  │      ├─ansi-styles
    │  │  │      ├─chalk
    │  │  │      │  └─source
    │  │  │      ├─color-convert
    │  │  │      ├─color-name
    │  │  │      ├─has-flag
    │  │  │      └─supports-color
    │  │  ├─jest-leak-detector
    │  │  │  └─build
    │  │  ├─jest-matcher-utils
    │  │  │  ├─build
    │  │  │  └─node_modules
    │  │  │      ├─ansi-styles
    │  │  │      ├─chalk
    │  │  │      │  └─source
    │  │  │      ├─color-convert
    │  │  │      ├─color-name
    │  │  │      ├─has-flag
    │  │  │      └─supports-color
    │  │  ├─jest-message-util
    │  │  │  ├─build
    │  │  │  └─node_modules
    │  │  │      ├─ansi-styles
    │  │  │      ├─chalk
    │  │  │      │  └─source
    │  │  │      ├─color-convert
    │  │  │      ├─color-name
    │  │  │      ├─has-flag
    │  │  │      └─supports-color
    │  │  ├─jest-mock
    │  │  │  └─build
    │  │  ├─jest-pnp-resolver
    │  │  ├─jest-regex-util
    │  │  │  └─build
    │  │  ├─jest-resolve
    │  │  │  ├─build
    │  │  │  └─node_modules
    │  │  │      ├─ansi-styles
    │  │  │      ├─chalk
    │  │  │      │  └─source
    │  │  │      ├─color-convert
    │  │  │      ├─color-name
    │  │  │      ├─has-flag
    │  │  │      └─supports-color
    │  │  ├─jest-resolve-dependencies
    │  │  │  └─build
    │  │  ├─jest-runner
    │  │  │  ├─build
    │  │  │  └─node_modules
    │  │  │      ├─ansi-styles
    │  │  │      ├─chalk
    │  │  │      │  └─source
    │  │  │      ├─color-convert
    │  │  │      ├─color-name
    │  │  │      ├─has-flag
    │  │  │      └─supports-color
    │  │  ├─jest-runtime
    │  │  │  ├─build
    │  │  │  └─node_modules
    │  │  │      ├─ansi-styles
    │  │  │      ├─chalk
    │  │  │      │  └─source
    │  │  │      ├─color-convert
    │  │  │      ├─color-name
    │  │  │      ├─has-flag
    │  │  │      └─supports-color
    │  │  ├─jest-serializer
    │  │  │  └─build
    │  │  ├─jest-snapshot
    │  │  │  ├─build
    │  │  │  └─node_modules
    │  │  │      ├─ansi-styles
    │  │  │      ├─chalk
    │  │  │      │  └─source
    │  │  │      ├─color-convert
    │  │  │      ├─color-name
    │  │  │      ├─has-flag
    │  │  │      └─supports-color
    │  │  ├─jest-util
    │  │  │  ├─build
    │  │  │  └─node_modules
    │  │  │      ├─ansi-styles
    │  │  │      ├─chalk
    │  │  │      │  └─source
    │  │  │      ├─color-convert
    │  │  │      ├─color-name
    │  │  │      ├─has-flag
    │  │  │      └─supports-color
    │  │  ├─jest-validate
    │  │  │  ├─build
    │  │  │  └─node_modules
    │  │  │      ├─ansi-styles
    │  │  │      ├─chalk
    │  │  │      │  └─source
    │  │  │      ├─color-convert
    │  │  │      ├─color-name
    │  │  │      ├─has-flag
    │  │  │      └─supports-color
    │  │  ├─jest-watch-typeahead
    │  │  │  ├─build
    │  │  │  │  ├─file_name_plugin
    │  │  │  │  ├─lib
    │  │  │  │  ├─test_name_plugin
    │  │  │  │  └─types
    │  │  │  └─node_modules
    │  │  │      ├─@jest
    │  │  │      │  ├─console
    │  │  │      │  │  ├─build
    │  │  │      │  │  └─node_modules
    │  │  │      │  │      └─slash
    │  │  │      │  ├─test-result
    │  │  │      │  │  └─build
    │  │  │      │  └─types
    │  │  │      │      └─build
    │  │  │      ├─@types
    │  │  │      │  └─yargs
    │  │  │      ├─ansi-styles
    │  │  │      ├─chalk
    │  │  │      │  └─source
    │  │  │      ├─color-convert
    │  │  │      ├─color-name
    │  │  │      ├─emittery
    │  │  │      ├─has-flag
    │  │  │      ├─jest-message-util
    │  │  │      │  ├─build
    │  │  │      │  └─node_modules
    │  │  │      │      └─slash
    │  │  │      ├─jest-regex-util
    │  │  │      │  └─build
    │  │  │      ├─jest-util
    │  │  │      │  └─build
    │  │  │      ├─jest-watcher
    │  │  │      │  ├─build
    │  │  │      │  │  └─lib
    │  │  │      │  └─node_modules
    │  │  │      │      ├─string-length
    │  │  │      │      └─strip-ansi
    │  │  │      ├─pretty-format
    │  │  │      │  ├─build
    │  │  │      │  │  └─plugins
    │  │  │      │  │      └─lib
    │  │  │      │  └─node_modules
    │  │  │      │      └─ansi-styles
    │  │  │      ├─react-is
    │  │  │      │  ├─cjs
    │  │  │      │  └─umd
    │  │  │      ├─slash
    │  │  │      ├─string-length
    │  │  │      │  └─node_modules
    │  │  │      │      └─char-regex
    │  │  │      ├─strip-ansi
    │  │  │      │  └─node_modules
    │  │  │      │      └─ansi-regex
    │  │  │      └─supports-color
    │  │  ├─jest-watcher
    │  │  │  ├─build
    │  │  │  │  └─lib
    │  │  │  └─node_modules
    │  │  │      ├─ansi-styles
    │  │  │      ├─chalk
    │  │  │      │  └─source
    │  │  │      ├─color-convert
    │  │  │      ├─color-name
    │  │  │      ├─has-flag
    │  │  │      └─supports-color
    │  │  ├─jest-worker
    │  │  │  ├─build
    │  │  │  │  ├─base
    │  │  │  │  └─workers
    │  │  │  └─node_modules
    │  │  │      ├─has-flag
    │  │  │      └─supports-color
    │  │  ├─jiti
    │  │  │  ├─bin
    │  │  │  ├─dist
    │  │  │  │  └─plugins
    │  │  │  └─lib
    │  │  ├─js-tokens
    │  │  ├─js-yaml
    │  │  │  ├─bin
    │  │  │  ├─dist
    │  │  │  └─lib
    │  │  │      └─js-yaml
    │  │  │          ├─schema
    │  │  │          └─type
    │  │  │              └─js
    │  │  ├─jsdom
    │  │  │  └─lib
    │  │  │      └─jsdom
    │  │  │          ├─browser
    │  │  │          │  ├─parser
    │  │  │          │  └─resources
    │  │  │          ├─level2
    │  │  │          ├─level3
    │  │  │          └─living
    │  │  │              ├─aborting
    │  │  │              ├─attributes
    │  │  │              ├─constraint-validation
    │  │  │              ├─cssom
    │  │  │              ├─custom-elements
    │  │  │              ├─domparsing
    │  │  │              ├─events
    │  │  │              ├─fetch
    │  │  │              ├─file-api
    │  │  │              ├─generated
    │  │  │              ├─helpers
    │  │  │              │  └─svg
    │  │  │              ├─hr-time
    │  │  │              ├─mutation-observer
    │  │  │              ├─navigator
    │  │  │              ├─nodes
    │  │  │              ├─range
    │  │  │              ├─selection
    │  │  │              ├─svg
    │  │  │              ├─traversal
    │  │  │              ├─websockets
    │  │  │              ├─webstorage
    │  │  │              ├─window
    │  │  │              └─xhr
    │  │  ├─jsesc
    │  │  │  ├─bin
    │  │  │  └─man
    │  │  ├─json-parse-even-better-errors
    │  │  ├─json-schema
    │  │  │  └─lib
    │  │  ├─json-schema-traverse
    │  │  │  └─spec
    │  │  │      └─fixtures
    │  │  ├─json-stable-stringify-without-jsonify
    │  │  │  ├─example
    │  │  │  └─test
    │  │  ├─json5
    │  │  │  ├─dist
    │  │  │  └─lib
    │  │  ├─jsonfile
    │  │  ├─jsonpointer
    │  │  ├─jsx-ast-utils
    │  │  │  ├─.github
    │  │  │  ├─lib
    │  │  │  │  └─values
    │  │  │  │      └─expressions
    │  │  │  ├─src
    │  │  │  │  └─values
    │  │  │  │      └─expressions
    │  │  │  └─__tests__
    │  │  │      └─src
    │  │  ├─kind-of
    │  │  ├─kleur
    │  │  ├─klona
    │  │  │  ├─dist
    │  │  │  ├─full
    │  │  │  ├─json
    │  │  │  └─lite
    │  │  ├─language-subtag-registry
    │  │  │  └─data
    │  │  │      └─json
    │  │  ├─language-tags
    │  │  │  ├─lib
    │  │  │  └─test
    │  │  │      └─lib
    │  │  ├─launch-editor
    │  │  │  └─editor-info
    │  │  ├─leven
    │  │  ├─levn
    │  │  │  └─lib
    │  │  ├─lilconfig
    │  │  │  └─dist
    │  │  ├─lines-and-columns
    │  │  │  └─build
    │  │  ├─loader-runner
    │  │  │  └─lib
    │  │  ├─loader-utils
    │  │  │  └─lib
    │  │  │      └─hash
    │  │  ├─locate-path
    │  │  ├─lodash
    │  │  │  └─fp
    │  │  ├─lodash.debounce
    │  │  ├─lodash.memoize
    │  │  ├─lodash.merge
    │  │  ├─lodash.sortby
    │  │  ├─lodash.uniq
    │  │  ├─loose-envify
    │  │  ├─lower-case
    │  │  │  ├─dist
    │  │  │  └─dist.es2015
    │  │  ├─lru-cache
    │  │  ├─lz-string
    │  │  │  ├─bin
    │  │  │  ├─libs
    │  │  │  ├─reference
    │  │  │  ├─tests
    │  │  │  │  └─lib
    │  │  │  │      └─jasmine-1.3.1
    │  │  │  └─typings
    │  │  ├─magic-string
    │  │  │  └─dist
    │  │  ├─make-dir
    │  │  │  └─node_modules
    │  │  │      ├─.bin
    │  │  │      └─semver
    │  │  │          └─bin
    │  │  ├─makeerror
    │  │  │  └─lib
    │  │  ├─mdn-data
    │  │  │  ├─api
    │  │  │  ├─css
    │  │  │  └─l10n
    │  │  ├─media-typer
    │  │  ├─memfs
    │  │  │  └─lib
    │  │  │      └─internal
    │  │  ├─merge-descriptors
    │  │  ├─merge-stream
    │  │  ├─merge2
    │  │  ├─methods
    │  │  ├─micromatch
    │  │  ├─mime
    │  │  │  └─src
    │  │  ├─mime-db
    │  │  ├─mime-types
    │  │  ├─mimic-fn
    │  │  ├─min-indent
    │  │  ├─mini-css-extract-plugin
    │  │  │  ├─dist
    │  │  │  │  └─hmr
    │  │  │  ├─node_modules
    │  │  │  │  ├─ajv
    │  │  │  │  │  ├─dist
    │  │  │  │  │  │  ├─compile
    │  │  │  │  │  │  │  ├─codegen
    │  │  │  │  │  │  │  ├─jtd
    │  │  │  │  │  │  │  └─validate
    │  │  │  │  │  │  ├─refs
    │  │  │  │  │  │  │  ├─json-schema-2019-09
    │  │  │  │  │  │  │  │  └─meta
    │  │  │  │  │  │  │  └─json-schema-2020-12
    │  │  │  │  │  │  │      └─meta
    │  │  │  │  │  │  ├─runtime
    │  │  │  │  │  │  ├─standalone
    │  │  │  │  │  │  ├─types
    │  │  │  │  │  │  └─vocabularies
    │  │  │  │  │  │      ├─applicator
    │  │  │  │  │  │      ├─core
    │  │  │  │  │  │      ├─discriminator
    │  │  │  │  │  │      ├─dynamic
    │  │  │  │  │  │      ├─format
    │  │  │  │  │  │      ├─jtd
    │  │  │  │  │  │      ├─unevaluated
    │  │  │  │  │  │      └─validation
    │  │  │  │  │  └─lib
    │  │  │  │  │      ├─compile
    │  │  │  │  │      │  ├─codegen
    │  │  │  │  │      │  ├─jtd
    │  │  │  │  │      │  └─validate
    │  │  │  │  │      ├─refs
    │  │  │  │  │      │  ├─json-schema-2019-09
    │  │  │  │  │      │  │  └─meta
    │  │  │  │  │      │  └─json-schema-2020-12
    │  │  │  │  │      │      └─meta
    │  │  │  │  │      ├─runtime
    │  │  │  │  │      ├─standalone
    │  │  │  │  │      ├─types
    │  │  │  │  │      └─vocabularies
    │  │  │  │  │          ├─applicator
    │  │  │  │  │          ├─core
    │  │  │  │  │          ├─discriminator
    │  │  │  │  │          ├─dynamic
    │  │  │  │  │          ├─format
    │  │  │  │  │          ├─jtd
    │  │  │  │  │          ├─unevaluated
    │  │  │  │  │          └─validation
    │  │  │  │  ├─ajv-keywords
    │  │  │  │  │  ├─dist
    │  │  │  │  │  │  ├─definitions
    │  │  │  │  │  │  └─keywords
    │  │  │  │  │  └─src
    │  │  │  │  │      ├─definitions
    │  │  │  │  │      └─keywords
    │  │  │  │  ├─json-schema-traverse
    │  │  │  │  │  ├─.github
    │  │  │  │  │  │  └─workflows
    │  │  │  │  │  └─spec
    │  │  │  │  │      └─fixtures
    │  │  │  │  └─schema-utils
    │  │  │  │      ├─declarations
    │  │  │  │      │  ├─keywords
    │  │  │  │      │  └─util
    │  │  │  │      └─dist
    │  │  │  │          ├─keywords
    │  │  │  │          └─util
    │  │  │  └─types
    │  │  │      └─hmr
    │  │  ├─minimalistic-assert
    │  │  ├─minimatch
    │  │  ├─minimist
    │  │  │  ├─.github
    │  │  │  ├─example
    │  │  │  └─test
    │  │  ├─mkdirp
    │  │  │  └─bin
    │  │  ├─ms
    │  │  ├─multicast-dns
    │  │  ├─mz
    │  │  ├─nanoid
    │  │  │  ├─async
    │  │  │  ├─bin
    │  │  │  ├─non-secure
    │  │  │  └─url-alphabet
    │  │  ├─natural-compare
    │  │  ├─natural-compare-lite
    │  │  ├─negotiator
    │  │  │  └─lib
    │  │  ├─neo-async
    │  │  ├─no-case
    │  │  │  ├─dist
    │  │  │  └─dist.es2015
    │  │  ├─node-forge
    │  │  │  ├─dist
    │  │  │  ├─flash
    │  │  │  │  └─swf
    │  │  │  └─lib
    │  │  ├─node-int64
    │  │  ├─node-releases
    │  │  │  └─data
    │  │  │      ├─processed
    │  │  │      └─release-schedule
    │  │  ├─normalize-path
    │  │  ├─normalize-range
    │  │  ├─normalize-url
    │  │  ├─npm-run-path
    │  │  ├─nth-check
    │  │  │  └─lib
    │  │  │      └─esm
    │  │  ├─nwsapi
    │  │  │  ├─dist
    │  │  │  └─src
    │  │  │      └─modules
    │  │  ├─object-assign
    │  │  ├─object-hash
    │  │  │  └─dist
    │  │  ├─object-inspect
    │  │  │  ├─.github
    │  │  │  ├─example
    │  │  │  └─test
    │  │  │      └─browser
    │  │  ├─object-is
    │  │  │  └─test
    │  │  ├─object-keys
    │  │  │  └─test
    │  │  ├─object.assign
    │  │  │  ├─.github
    │  │  │  ├─dist
    │  │  │  └─test
    │  │  ├─object.entries
    │  │  │  └─test
    │  │  ├─object.fromentries
    │  │  │  └─test
    │  │  ├─object.getownpropertydescriptors
    │  │  │  └─test
    │  │  ├─object.hasown
    │  │  │  ├─.github
    │  │  │  └─test
    │  │  ├─object.values
    │  │  │  └─test
    │  │  ├─obuf
    │  │  │  └─test
    │  │  ├─on-finished
    │  │  ├─on-headers
    │  │  ├─once
    │  │  ├─onetime
    │  │  ├─open
    │  │  ├─optionator
    │  │  │  └─lib
    │  │  ├─p-limit
    │  │  ├─p-locate
    │  │  ├─p-retry
    │  │  ├─p-try
    │  │  ├─param-case
    │  │  │  ├─dist
    │  │  │  └─dist.es2015
    │  │  ├─parent-module
    │  │  ├─parse-json
    │  │  ├─parse5
    │  │  │  └─lib
    │  │  │      ├─common
    │  │  │      ├─extensions
    │  │  │      │  ├─error-reporting
    │  │  │      │  ├─location-info
    │  │  │      │  └─position-tracking
    │  │  │      ├─parser
    │  │  │      ├─serializer
    │  │  │      ├─tokenizer
    │  │  │      ├─tree-adapters
    │  │  │      └─utils
    │  │  ├─parseurl
    │  │  ├─pascal-case
    │  │  │  ├─dist
    │  │  │  └─dist.es2015
    │  │  ├─path-exists
    │  │  ├─path-is-absolute
    │  │  ├─path-key
    │  │  ├─path-parse
    │  │  ├─path-to-regexp
    │  │  ├─path-type
    │  │  ├─performance-now
    │  │  │  ├─lib
    │  │  │  ├─src
    │  │  │  └─test
    │  │  │      └─scripts
    │  │  ├─picocolors
    │  │  ├─picomatch
    │  │  │  └─lib
    │  │  ├─pify
    │  │  ├─pirates
    │  │  │  └─lib
    │  │  ├─pkg-dir
    │  │  │  └─node_modules
    │  │  │      ├─find-up
    │  │  │      ├─locate-path
    │  │  │      ├─p-limit
    │  │  │      └─p-locate
    │  │  ├─pkg-up
    │  │  │  └─node_modules
    │  │  │      ├─find-up
    │  │  │      ├─locate-path
    │  │  │      ├─p-limit
    │  │  │      ├─p-locate
    │  │  │      └─path-exists
    │  │  ├─postcss
    │  │  │  └─lib
    │  │  ├─postcss-attribute-case-insensitive
    │  │  │  └─dist
    │  │  ├─postcss-browser-comments
    │  │  ├─postcss-calc
    │  │  │  ├─src
    │  │  │  │  ├─lib
    │  │  │  │  └─__tests__
    │  │  │  └─types
    │  │  │      └─lib
    │  │  ├─postcss-clamp
    │  │  ├─postcss-color-functional-notation
    │  │  │  └─dist
    │  │  ├─postcss-color-hex-alpha
    │  │  │  └─dist
    │  │  ├─postcss-color-rebeccapurple
    │  │  │  └─dist
    │  │  ├─postcss-colormin
    │  │  │  ├─src
    │  │  │  └─types
    │  │  ├─postcss-convert-values
    │  │  │  ├─src
    │  │  │  │  └─lib
    │  │  │  └─types
    │  │  │      └─lib
    │  │  ├─postcss-custom-media
    │  │  │  └─dist
    │  │  ├─postcss-custom-properties
    │  │  │  └─dist
    │  │  │      └─lib
    │  │  ├─postcss-custom-selectors
    │  │  │  └─dist
    │  │  ├─postcss-dir-pseudo-class
    │  │  │  └─dist
    │  │  ├─postcss-discard-comments
    │  │  │  ├─src
    │  │  │  │  └─lib
    │  │  │  └─types
    │  │  │      └─lib
    │  │  ├─postcss-discard-duplicates
    │  │  │  ├─src
    │  │  │  └─types
    │  │  ├─postcss-discard-empty
    │  │  │  ├─src
    │  │  │  └─types
    │  │  ├─postcss-discard-overridden
    │  │  │  └─src
    │  │  ├─postcss-double-position-gradients
    │  │  │  └─dist
    │  │  ├─postcss-env-function
    │  │  │  └─dist
    │  │  ├─postcss-flexbugs-fixes
    │  │  │  └─bugs
    │  │  ├─postcss-focus-visible
    │  │  │  └─dist
    │  │  ├─postcss-focus-within
    │  │  │  └─dist
    │  │  ├─postcss-font-variant
    │  │  ├─postcss-gap-properties
    │  │  │  └─dist
    │  │  ├─postcss-image-set-function
    │  │  │  └─dist
    │  │  │      └─lib
    │  │  ├─postcss-import
    │  │  │  └─lib
    │  │  ├─postcss-initial
    │  │  │  ├─.github
    │  │  │  │  └─workflows
    │  │  │  ├─lib
    │  │  │  └─~
    │  │  │      └─.config
    │  │  │          └─configstore
    │  │  ├─postcss-js
    │  │  ├─postcss-lab-function
    │  │  │  └─dist
    │  │  │      └─css-color-4
    │  │  ├─postcss-load-config
    │  │  │  ├─node_modules
    │  │  │  │  └─yaml
    │  │  │  │      ├─browser
    │  │  │  │      │  └─dist
    │  │  │  │      │      ├─compose
    │  │  │  │      │      ├─doc
    │  │  │  │      │      ├─nodes
    │  │  │  │      │      ├─node_modules
    │  │  │  │      │      │  └─tslib
    │  │  │  │      │      ├─parse
    │  │  │  │      │      ├─schema
    │  │  │  │      │      │  ├─common
    │  │  │  │      │      │  ├─core
    │  │  │  │      │      │  ├─json
    │  │  │  │      │      │  └─yaml-1.1
    │  │  │  │      │      └─stringify
    │  │  │  │      └─dist
    │  │  │  │          ├─compose
    │  │  │  │          ├─doc
    │  │  │  │          ├─nodes
    │  │  │  │          ├─parse
    │  │  │  │          ├─schema
    │  │  │  │          │  ├─common
    │  │  │  │          │  ├─core
    │  │  │  │          │  ├─json
    │  │  │  │          │  └─yaml-1.1
    │  │  │  │          └─stringify
    │  │  │  └─src
    │  │  ├─postcss-loader
    │  │  │  └─dist
    │  │  ├─postcss-logical
    │  │  │  └─dist
    │  │  ├─postcss-media-minmax
    │  │  ├─postcss-merge-longhand
    │  │  │  ├─src
    │  │  │  │  └─lib
    │  │  │  │      └─decl
    │  │  │  └─types
    │  │  │      └─lib
    │  │  │          └─decl
    │  │  ├─postcss-merge-rules
    │  │  │  ├─src
    │  │  │  │  └─lib
    │  │  │  └─types
    │  │  │      └─lib
    │  │  ├─postcss-minify-font-values
    │  │  │  ├─src
    │  │  │  │  └─lib
    │  │  │  └─types
    │  │  │      └─lib
    │  │  ├─postcss-minify-gradients
    │  │  │  ├─src
    │  │  │  └─types
    │  │  ├─postcss-minify-params
    │  │  │  ├─src
    │  │  │  └─types
    │  │  ├─postcss-minify-selectors
    │  │  │  ├─src
    │  │  │  │  └─lib
    │  │  │  └─types
    │  │  │      └─lib
    │  │  ├─postcss-modules-extract-imports
    │  │  │  └─src
    │  │  ├─postcss-modules-local-by-default
    │  │  │  └─src
    │  │  ├─postcss-modules-scope
    │  │  │  └─src
    │  │  ├─postcss-modules-values
    │  │  │  └─src
    │  │  ├─postcss-nested
    │  │  ├─postcss-nesting
    │  │  │  └─dist
    │  │  │      └─lib
    │  │  │          └─merge-selectors
    │  │  ├─postcss-normalize
    │  │  ├─postcss-normalize-charset
    │  │  │  ├─src
    │  │  │  └─types
    │  │  ├─postcss-normalize-display-values
    │  │  │  ├─src
    │  │  │  │  └─lib
    │  │  │  └─types
    │  │  │      └─lib
    │  │  ├─postcss-normalize-positions
    │  │  │  ├─src
    │  │  │  └─types
    │  │  ├─postcss-normalize-repeat-style
    │  │  │  ├─src
    │  │  │  │  └─lib
    │  │  │  └─types
    │  │  │      └─lib
    │  │  ├─postcss-normalize-string
    │  │  │  ├─src
    │  │  │  └─types
    │  │  ├─postcss-normalize-timing-functions
    │  │  │  ├─src
    │  │  │  └─types
    │  │  ├─postcss-normalize-unicode
    │  │  │  ├─src
    │  │  │  └─types
    │  │  ├─postcss-normalize-url
    │  │  │  ├─src
    │  │  │  └─types
    │  │  ├─postcss-normalize-whitespace
    │  │  │  ├─src
    │  │  │  └─types
    │  │  ├─postcss-opacity-percentage
    │  │  ├─postcss-ordered-values
    │  │  │  ├─src
    │  │  │  │  ├─lib
    │  │  │  │  └─rules
    │  │  │  └─types
    │  │  │      ├─lib
    │  │  │      └─rules
    │  │  ├─postcss-overflow-shorthand
    │  │  │  └─dist
    │  │  ├─postcss-page-break
    │  │  ├─postcss-place
    │  │  │  └─dist
    │  │  ├─postcss-preset-env
    │  │  │  └─dist
    │  │  ├─postcss-pseudo-class-any-link
    │  │  │  └─dist
    │  │  ├─postcss-reduce-initial
    │  │  │  ├─src
    │  │  │  │  └─data
    │  │  │  └─types
    │  │  ├─postcss-reduce-transforms
    │  │  │  ├─src
    │  │  │  └─types
    │  │  ├─postcss-replace-overflow-wrap
    │  │  ├─postcss-selector-not
    │  │  │  └─dist
    │  │  ├─postcss-selector-parser
    │  │  │  └─dist
    │  │  │      ├─selectors
    │  │  │      └─util
    │  │  ├─postcss-svgo
    │  │  │  ├─node_modules
    │  │  │  │  ├─.bin
    │  │  │  │  ├─commander
    │  │  │  │  │  └─typings
    │  │  │  │  ├─css-tree
    │  │  │  │  │  ├─data
    │  │  │  │  │  ├─dist
    │  │  │  │  │  └─lib
    │  │  │  │  │      ├─common
    │  │  │  │  │      ├─convertor
    │  │  │  │  │      ├─definition-syntax
    │  │  │  │  │      ├─generator
    │  │  │  │  │      ├─lexer
    │  │  │  │  │      ├─parser
    │  │  │  │  │      ├─syntax
    │  │  │  │  │      │  ├─atrule
    │  │  │  │  │      │  ├─config
    │  │  │  │  │      │  ├─function
    │  │  │  │  │      │  ├─node
    │  │  │  │  │      │  ├─pseudo
    │  │  │  │  │      │  │  └─common
    │  │  │  │  │      │  └─scope
    │  │  │  │  │      ├─tokenizer
    │  │  │  │  │      ├─utils
    │  │  │  │  │      └─walker
    │  │  │  │  ├─mdn-data
    │  │  │  │  │  ├─api
    │  │  │  │  │  ├─css
    │  │  │  │  │  └─l10n
    │  │  │  │  ├─source-map
    │  │  │  │  │  ├─dist
    │  │  │  │  │  └─lib
    │  │  │  │  └─svgo
    │  │  │  │      ├─bin
    │  │  │  │      ├─dist
    │  │  │  │      ├─lib
    │  │  │  │      │  └─svgo
    │  │  │  │      └─plugins
    │  │  │  ├─src
    │  │  │  │  └─lib
    │  │  │  └─types
    │  │  │      └─lib
    │  │  ├─postcss-unique-selectors
    │  │  │  ├─src
    │  │  │  └─types
    │  │  ├─postcss-value-parser
    │  │  │  └─lib
    │  │  ├─prelude-ls
    │  │  │  └─lib
    │  │  ├─pretty-bytes
    │  │  ├─pretty-error
    │  │  │  ├─.github
    │  │  │  │  └─workflows
    │  │  │  ├─lib
    │  │  │  ├─src
    │  │  │  └─test
    │  │  ├─pretty-format
    │  │  │  ├─build
    │  │  │  │  └─plugins
    │  │  │  │      └─lib
    │  │  │  └─node_modules
    │  │  │      └─ansi-styles
    │  │  ├─process-nextick-args
    │  │  ├─promise
    │  │  │  ├─domains
    │  │  │  ├─lib
    │  │  │  ├─setimmediate
    │  │  │  └─src
    │  │  ├─prompts
    │  │  │  ├─dist
    │  │  │  │  ├─dateparts
    │  │  │  │  ├─elements
    │  │  │  │  └─util
    │  │  │  └─lib
    │  │  │      ├─dateparts
    │  │  │      ├─elements
    │  │  │      └─util
    │  │  ├─prop-types
    │  │  │  ├─lib
    │  │  │  └─node_modules
    │  │  │      └─react-is
    │  │  │          ├─cjs
    │  │  │          └─umd
    │  │  ├─proxy-addr
    │  │  │  └─node_modules
    │  │  │      └─ipaddr.js
    │  │  │          └─lib
    │  │  ├─psl
    │  │  │  ├─data
    │  │  │  └─dist
    │  │  ├─punycode
    │  │  ├─q
    │  │  ├─qs
    │  │  │  ├─.github
    │  │  │  ├─dist
    │  │  │  ├─lib
    │  │  │  └─test
    │  │  ├─querystringify
    │  │  ├─queue-microtask
    │  │  ├─raf
    │  │  ├─randombytes
    │  │  ├─range-parser
    │  │  ├─raw-body
    │  │  │  └─node_modules
    │  │  │      ├─bytes
    │  │  │      └─iconv-lite
    │  │  │          ├─encodings
    │  │  │          │  └─tables
    │  │  │          └─lib
    │  │  ├─react
    │  │  │  ├─cjs
    │  │  │  └─umd
    │  │  ├─react-app-polyfill
    │  │  ├─react-dev-utils
    │  │  │  └─node_modules
    │  │  │      ├─ansi-styles
    │  │  │      ├─chalk
    │  │  │      │  └─source
    │  │  │      ├─color-convert
    │  │  │      ├─color-name
    │  │  │      ├─escape-string-regexp
    │  │  │      ├─has-flag
    │  │  │      ├─loader-utils
    │  │  │      │  └─lib
    │  │  │      │      └─hash
    │  │  │      └─supports-color
    │  │  ├─react-dom
    │  │  │  ├─cjs
    │  │  │  └─umd
    │  │  ├─react-error-overlay
    │  │  │  └─lib
    │  │  ├─react-is
    │  │  │  ├─cjs
    │  │  │  └─umd
    │  │  ├─react-refresh
    │  │  │  └─cjs
    │  │  ├─react-router
    │  │  │  └─dist
    │  │  │      ├─lib
    │  │  │      └─umd
    │  │  ├─react-router-dom
    │  │  │  └─dist
    │  │  │      └─umd
    │  │  ├─react-scripts
    │  │  │  ├─bin
    │  │  │  ├─config
    │  │  │  │  ├─jest
    │  │  │  │  └─webpack
    │  │  │  │      └─persistentCache
    │  │  │  ├─lib
    │  │  │  ├─scripts
    │  │  │  │  └─utils
    │  │  │  ├─template
    │  │  │  └─template-typescript
    │  │  ├─read-cache
    │  │  ├─readable-stream
    │  │  │  └─lib
    │  │  │      └─internal
    │  │  │          └─streams
    │  │  ├─readdirp
    │  │  ├─rechoir
    │  │  │  └─lib
    │  │  ├─recursive-readdir
    │  │  ├─redent
    │  │  ├─regenerate
    │  │  ├─regenerate-unicode-properties
    │  │  │  ├─Binary_Property
    │  │  │  ├─General_Category
    │  │  │  ├─Property_of_Strings
    │  │  │  ├─Script
    │  │  │  └─Script_Extensions
    │  │  ├─regenerator-runtime
    │  │  ├─regenerator-transform
    │  │  │  ├─lib
    │  │  │  └─src
    │  │  ├─regex-parser
    │  │  │  └─lib
    │  │  │      └─typings
    │  │  ├─regexp.prototype.flags
    │  │  │  └─test
    │  │  ├─regexpu-core
    │  │  │  └─data
    │  │  ├─regjsparser
    │  │  │  ├─bin
    │  │  │  └─node_modules
    │  │  │      ├─.bin
    │  │  │      └─jsesc
    │  │  │          ├─bin
    │  │  │          └─man
    │  │  ├─relateurl
    │  │  │  └─lib
    │  │  │      ├─parse
    │  │  │      ├─relate
    │  │  │      └─util
    │  │  ├─renderkid
    │  │  │  ├─docs
    │  │  │  │  └─images
    │  │  │  └─lib
    │  │  │      ├─ansiPainter
    │  │  │      ├─layout
    │  │  │      │  └─block
    │  │  │      │      ├─blockAppendor
    │  │  │      │      ├─blockPrependor
    │  │  │      │      ├─lineAppendor
    │  │  │      │      ├─linePrependor
    │  │  │      │      └─lineWrapper
    │  │  │      └─renderKid
    │  │  │          ├─styleApplier
    │  │  │          └─styles
    │  │  │              └─rule
    │  │  │                  └─declarationBlock
    │  │  ├─require-directory
    │  │  ├─require-from-string
    │  │  ├─requires-port
    │  │  ├─resolve
    │  │  │  ├─.github
    │  │  │  ├─bin
    │  │  │  ├─example
    │  │  │  ├─lib
    │  │  │  └─test
    │  │  │      ├─dotdot
    │  │  │      │  └─abc
    │  │  │      ├─module_dir
    │  │  │      │  ├─xmodules
    │  │  │      │  │  └─aaa
    │  │  │      │  ├─ymodules
    │  │  │      │  │  └─aaa
    │  │  │      │  └─zmodules
    │  │  │      │      └─bbb
    │  │  │      ├─node_path
    │  │  │      │  ├─x
    │  │  │      │  │  ├─aaa
    │  │  │      │  │  └─ccc
    │  │  │      │  └─y
    │  │  │      │      ├─bbb
    │  │  │      │      └─ccc
    │  │  │      ├─pathfilter
    │  │  │      │  └─deep_ref
    │  │  │      ├─precedence
    │  │  │      │  ├─aaa
    │  │  │      │  └─bbb
    │  │  │      ├─resolver
    │  │  │      │  ├─baz
    │  │  │      │  ├─browser_field
    │  │  │      │  ├─dot_main
    │  │  │      │  ├─dot_slash_main
    │  │  │      │  ├─false_main
    │  │  │      │  ├─incorrect_main
    │  │  │      │  ├─invalid_main
    │  │  │      │  ├─malformed_package_json
    │  │  │      │  ├─multirepo
    │  │  │      │  │  └─packages
    │  │  │      │  │      ├─package-a
    │  │  │      │  │      └─package-b
    │  │  │      │  ├─nested_symlinks
    │  │  │      │  │  └─mylib
    │  │  │      │  ├─other_path
    │  │  │      │  │  └─lib
    │  │  │      │  ├─quux
    │  │  │      │  │  └─foo
    │  │  │      │  ├─same_names
    │  │  │      │  │  └─foo
    │  │  │      │  ├─symlinked
    │  │  │      │  │  ├─package
    │  │  │      │  │  └─_
    │  │  │      │  │      ├─node_modules
    │  │  │      │  │      └─symlink_target
    │  │  │      │  └─without_basedir
    │  │  │      └─shadowed_core
    │  │  │          └─node_modules
    │  │  │              └─util
    │  │  ├─resolve-cwd
    │  │  ├─resolve-from
    │  │  ├─resolve-url-loader
    │  │  │  ├─docs
    │  │  │  ├─lib
    │  │  │  │  ├─engine
    │  │  │  │  └─join-function
    │  │  │  └─node_modules
    │  │  │      ├─picocolors
    │  │  │      ├─postcss
    │  │  │      │  └─lib
    │  │  │      └─source-map
    │  │  │          ├─dist
    │  │  │          └─lib
    │  │  ├─resolve.exports
    │  │  │  └─dist
    │  │  ├─retry
    │  │  │  ├─example
    │  │  │  └─lib
    │  │  ├─reusify
    │  │  │  └─benchmarks
    │  │  ├─rimraf
    │  │  ├─rollup
    │  │  │  └─dist
    │  │  │      ├─bin
    │  │  │      ├─es
    │  │  │      │  └─shared
    │  │  │      └─shared
    │  │  ├─rollup-plugin-terser
    │  │  │  └─node_modules
    │  │  │      ├─has-flag
    │  │  │      ├─jest-worker
    │  │  │      │  └─build
    │  │  │      │      ├─base
    │  │  │      │      └─workers
    │  │  │      ├─serialize-javascript
    │  │  │      │  └─.vscode
    │  │  │      └─supports-color
    │  │  ├─run-parallel
    │  │  ├─safe-array-concat
    │  │  │  ├─.github
    │  │  │  └─test
    │  │  ├─safe-buffer
    │  │  ├─safe-regex-test
    │  │  │  ├─.github
    │  │  │  └─test
    │  │  ├─safer-buffer
    │  │  ├─sanitize.css
    │  │  ├─sass-loader
    │  │  │  └─dist
    │  │  ├─sax
    │  │  │  └─lib
    │  │  ├─saxes
    │  │  ├─scheduler
    │  │  │  ├─cjs
    │  │  │  └─umd
    │  │  ├─schema-utils
    │  │  │  ├─declarations
    │  │  │  │  ├─keywords
    │  │  │  │  └─util
    │  │  │  └─dist
    │  │  │      ├─keywords
    │  │  │      └─util
    │  │  ├─select-hose
    │  │  │  ├─lib
    │  │  │  └─test
    │  │  ├─selfsigned
    │  │  │  └─test
    │  │  ├─semver
    │  │  │  ├─bin
    │  │  │  ├─classes
    │  │  │  ├─functions
    │  │  │  ├─internal
    │  │  │  ├─node_modules
    │  │  │  │  ├─lru-cache
    │  │  │  │  └─yallist
    │  │  │  └─ranges
    │  │  ├─send
    │  │  │  └─node_modules
    │  │  │      ├─debug
    │  │  │      │  ├─node_modules
    │  │  │      │  │  └─ms
    │  │  │      │  └─src
    │  │  │      └─ms
    │  │  ├─serialize-javascript
    │  │  ├─serve-index
    │  │  │  ├─node_modules
    │  │  │  │  ├─debug
    │  │  │  │  │  └─src
    │  │  │  │  ├─depd
    │  │  │  │  │  └─lib
    │  │  │  │  │      ├─browser
    │  │  │  │  │      └─compat
    │  │  │  │  ├─http-errors
    │  │  │  │  ├─inherits
    │  │  │  │  ├─ms
    │  │  │  │  ├─setprototypeof
    │  │  │  │  └─statuses
    │  │  │  └─public
    │  │  │      └─icons
    │  │  ├─serve-static
    │  │  ├─setprototypeof
    │  │  │  └─test
    │  │  ├─shallow-clone
    │  │  ├─shebang-command
    │  │  ├─shebang-regex
    │  │  ├─shell-quote
    │  │  │  ├─.github
    │  │  │  ├─example
    │  │  │  └─test
    │  │  ├─side-channel
    │  │  │  ├─.github
    │  │  │  └─test
    │  │  ├─signal-exit
    │  │  ├─sisteransi
    │  │  │  └─src
    │  │  ├─slash
    │  │  ├─sockjs
    │  │  │  └─lib
    │  │  ├─source-list-map
    │  │  │  └─lib
    │  │  ├─source-map
    │  │  │  ├─dist
    │  │  │  └─lib
    │  │  ├─source-map-js
    │  │  │  └─lib
    │  │  ├─source-map-loader
    │  │  │  └─dist
    │  │  ├─source-map-support
    │  │  │  └─node_modules
    │  │  │      └─source-map
    │  │  │          ├─dist
    │  │  │          └─lib
    │  │  ├─sourcemap-codec
    │  │  │  └─dist
    │  │  │      └─types
    │  │  ├─spdy
    │  │  │  ├─lib
    │  │  │  │  └─spdy
    │  │  │  └─test
    │  │  ├─spdy-transport
    │  │  │  └─lib
    │  │  │      └─spdy-transport
    │  │  │          └─protocol
    │  │  │              ├─base
    │  │  │              ├─http2
    │  │  │              └─spdy
    │  │  ├─sprintf-js
    │  │  │  ├─demo
    │  │  │  ├─dist
    │  │  │  ├─src
    │  │  │  └─test
    │  │  ├─stable
    │  │  ├─stack-utils
    │  │  │  └─node_modules
    │  │  │      └─escape-string-regexp
    │  │  ├─stackframe
    │  │  │  └─dist
    │  │  ├─statuses
    │  │  ├─stop-iteration-iterator
    │  │  │  ├─.github
    │  │  │  └─test
    │  │  ├─string-length
    │  │  ├─string-natural-compare
    │  │  ├─string-width
    │  │  │  └─node_modules
    │  │  │      └─emoji-regex
    │  │  │          └─es2015
    │  │  ├─string.prototype.matchall
    │  │  │  ├─.github
    │  │  │  └─test
    │  │  ├─string.prototype.trim
    │  │  │  └─test
    │  │  ├─string.prototype.trimend
    │  │  │  └─test
    │  │  ├─string.prototype.trimstart
    │  │  │  └─test
    │  │  ├─stringify-object
    │  │  ├─string_decoder
    │  │  │  └─lib
    │  │  ├─strip-ansi
    │  │  ├─strip-bom
    │  │  ├─strip-comments
    │  │  │  └─lib
    │  │  ├─strip-final-newline
    │  │  ├─strip-indent
    │  │  ├─strip-json-comments
    │  │  ├─style-loader
    │  │  │  └─dist
    │  │  │      └─runtime
    │  │  ├─stylehacks
    │  │  │  ├─src
    │  │  │  │  ├─dictionary
    │  │  │  │  └─plugins
    │  │  │  └─types
    │  │  │      ├─dictionary
    │  │  │      └─plugins
    │  │  ├─sucrase
    │  │  │  ├─bin
    │  │  │  ├─dist
    │  │  │  │  ├─esm
    │  │  │  │  │  ├─parser
    │  │  │  │  │  │  ├─plugins
    │  │  │  │  │  │  │  └─jsx
    │  │  │  │  │  │  ├─tokenizer
    │  │  │  │  │  │  ├─traverser
    │  │  │  │  │  │  └─util
    │  │  │  │  │  ├─transformers
    │  │  │  │  │  └─util
    │  │  │  │  ├─parser
    │  │  │  │  │  ├─plugins
    │  │  │  │  │  │  └─jsx
    │  │  │  │  │  ├─tokenizer
    │  │  │  │  │  ├─traverser
    │  │  │  │  │  └─util
    │  │  │  │  ├─transformers
    │  │  │  │  ├─types
    │  │  │  │  │  ├─parser
    │  │  │  │  │  │  ├─plugins
    │  │  │  │  │  │  │  └─jsx
    │  │  │  │  │  │  ├─tokenizer
    │  │  │  │  │  │  ├─traverser
    │  │  │  │  │  │  └─util
    │  │  │  │  │  ├─transformers
    │  │  │  │  │  └─util
    │  │  │  │  └─util
    │  │  │  ├─node_modules
    │  │  │  │  ├─commander
    │  │  │  │  │  └─typings
    │  │  │  │  └─glob
    │  │  │  ├─register
    │  │  │  └─ts-node-plugin
    │  │  ├─supports-color
    │  │  ├─supports-hyperlinks
    │  │  │  └─node_modules
    │  │  │      ├─has-flag
    │  │  │      └─supports-color
    │  │  ├─supports-preserve-symlinks-flag
    │  │  │  ├─.github
    │  │  │  └─test
    │  │  ├─svg-parser
    │  │  │  └─dist
    │  │  ├─svgo
    │  │  │  ├─bin
    │  │  │  ├─lib
    │  │  │  │  └─svgo
    │  │  │  ├─node_modules
    │  │  │  │  ├─css-select
    │  │  │  │  │  └─lib
    │  │  │  │  ├─css-what
    │  │  │  │  │  └─lib
    │  │  │  │  ├─dom-serializer
    │  │  │  │  ├─domutils
    │  │  │  │  │  ├─lib
    │  │  │  │  │  ├─node_modules
    │  │  │  │  │  │  └─domelementtype
    │  │  │  │  │  └─test
    │  │  │  │  │      └─tests
    │  │  │  │  └─nth-check
    │  │  │  └─plugins
    │  │  ├─symbol-tree
    │  │  │  └─lib
    │  │  ├─tailwindcss
    │  │  │  ├─lib
    │  │  │  │  ├─cli
    │  │  │  │  │  ├─build
    │  │  │  │  │  ├─help
    │  │  │  │  │  └─init
    │  │  │  │  ├─css
    │  │  │  │  ├─lib
    │  │  │  │  ├─oxide
    │  │  │  │  │  └─cli
    │  │  │  │  │      ├─build
    │  │  │  │  │      ├─help
    │  │  │  │  │      └─init
    │  │  │  │  ├─postcss-plugins
    │  │  │  │  │  └─nesting
    │  │  │  │  ├─public
    │  │  │  │  ├─util
    │  │  │  │  └─value-parser
    │  │  │  ├─nesting
    │  │  │  ├─peers
    │  │  │  ├─scripts
    │  │  │  ├─src
    │  │  │  │  ├─cli
    │  │  │  │  │  ├─build
    │  │  │  │  │  ├─help
    │  │  │  │  │  └─init
    │  │  │  │  ├─css
    │  │  │  │  ├─lib
    │  │  │  │  ├─oxide
    │  │  │  │  │  └─cli
    │  │  │  │  │      ├─build
    │  │  │  │  │      ├─help
    │  │  │  │  │      └─init
    │  │  │  │  ├─postcss-plugins
    │  │  │  │  │  └─nesting
    │  │  │  │  ├─public
    │  │  │  │  ├─util
    │  │  │  │  └─value-parser
    │  │  │  ├─stubs
    │  │  │  └─types
    │  │  │      └─generated
    │  │  ├─tapable
    │  │  │  └─lib
    │  │  ├─temp-dir
    │  │  ├─tempy
    │  │  │  └─node_modules
    │  │  │      └─type-fest
    │  │  │          └─source
    │  │  ├─terminal-link
    │  │  ├─terser
    │  │  │  ├─bin
    │  │  │  ├─dist
    │  │  │  ├─lib
    │  │  │  │  ├─compress
    │  │  │  │  └─utils
    │  │  │  ├─node_modules
    │  │  │  │  └─commander
    │  │  │  │      └─typings
    │  │  │  └─tools
    │  │  ├─terser-webpack-plugin
    │  │  │  ├─dist
    │  │  │  └─types
    │  │  ├─test-exclude
    │  │  ├─text-table
    │  │  │  ├─example
    │  │  │  └─test
    │  │  ├─thenify
    │  │  ├─thenify-all
    │  │  ├─throat
    │  │  ├─thunky
    │  │  ├─tmpl
    │  │  │  └─lib
    │  │  ├─to-fast-properties
    │  │  ├─to-regex-range
    │  │  ├─toidentifier
    │  │  ├─tough-cookie
    │  │  │  ├─lib
    │  │  │  └─node_modules
    │  │  │      └─universalify
    │  │  ├─tr46
    │  │  │  └─lib
    │  │  ├─tryer
    │  │  │  ├─lib
    │  │  │  ├─src
    │  │  │  └─test
    │  │  ├─ts-interface-checker
    │  │  │  └─dist
    │  │  ├─tsconfig-paths
    │  │  │  ├─lib
    │  │  │  │  └─__tests__
    │  │  │  │      └─data
    │  │  │  ├─node_modules
    │  │  │  │  ├─.bin
    │  │  │  │  ├─json5
    │  │  │  │  │  ├─dist
    │  │  │  │  │  └─lib
    │  │  │  │  └─strip-bom
    │  │  │  └─src
    │  │  │      └─__tests__
    │  │  │          └─data
    │  │  ├─tslib
    │  │  │  └─modules
    │  │  ├─tsutils
    │  │  │  ├─node_modules
    │  │  │  │  └─tslib
    │  │  │  │      ├─modules
    │  │  │  │      └─test
    │  │  │  │          └─validateModuleExportsMatchCommonJS
    │  │  │  ├─typeguard
    │  │  │  │  ├─2.8
    │  │  │  │  ├─2.9
    │  │  │  │  ├─3.0
    │  │  │  │  ├─3.2
    │  │  │  │  └─next
    │  │  │  └─util
    │  │  ├─type-check
    │  │  │  └─lib
    │  │  ├─type-detect
    │  │  ├─type-fest
    │  │  │  ├─source
    │  │  │  └─ts41
    │  │  ├─type-is
    │  │  ├─typed-array-buffer
    │  │  │  ├─.github
    │  │  │  └─test
    │  │  ├─typed-array-byte-length
    │  │  │  ├─.github
    │  │  │  └─test
    │  │  ├─typed-array-byte-offset
    │  │  │  ├─.github
    │  │  │  └─test
    │  │  ├─typed-array-length
    │  │  │  ├─.github
    │  │  │  └─test
    │  │  ├─typedarray-to-buffer
    │  │  │  └─test
    │  │  ├─typescript
    │  │  │  ├─bin
    │  │  │  └─lib
    │  │  │      ├─cs
    │  │  │      ├─de
    │  │  │      ├─es
    │  │  │      ├─fr
    │  │  │      ├─it
    │  │  │      ├─ja
    │  │  │      ├─ko
    │  │  │      ├─pl
    │  │  │      ├─pt-br
    │  │  │      ├─ru
    │  │  │      ├─tr
    │  │  │      ├─zh-cn
    │  │  │      └─zh-tw
    │  │  ├─unbox-primitive
    │  │  │  ├─.github
    │  │  │  └─test
    │  │  ├─unicode-canonical-property-names-ecmascript
    │  │  ├─unicode-match-property-ecmascript
    │  │  ├─unicode-match-property-value-ecmascript
    │  │  │  └─data
    │  │  ├─unicode-property-aliases-ecmascript
    │  │  ├─unique-string
    │  │  ├─universalify
    │  │  ├─unpipe
    │  │  ├─unquote
    │  │  ├─upath
    │  │  │  └─build
    │  │  │      └─code
    │  │  ├─update-browserslist-db
    │  │  ├─uri-js
    │  │  │  └─dist
    │  │  │      ├─es5
    │  │  │      └─esnext
    │  │  │          └─schemes
    │  │  ├─url-parse
    │  │  │  └─dist
    │  │  ├─util-deprecate
    │  │  ├─util.promisify
    │  │  │  └─.github
    │  │  │      └─workflows
    │  │  ├─utila
    │  │  │  ├─lib
    │  │  │  └─test
    │  │  ├─utils-merge
    │  │  ├─uuid
    │  │  │  └─dist
    │  │  │      ├─bin
    │  │  │      ├─esm-browser
    │  │  │      ├─esm-node
    │  │  │      └─umd
    │  │  ├─v8-to-istanbul
    │  │  │  └─lib
    │  │  ├─vary
    │  │  ├─w3c-hr-time
    │  │  │  └─lib
    │  │  ├─w3c-xmlserializer
    │  │  │  └─lib
    │  │  ├─walker
    │  │  │  └─lib
    │  │  ├─watchpack
    │  │  │  └─lib
    │  │  ├─wbuf
    │  │  │  └─test
    │  │  ├─web-vitals
    │  │  │  ├─dist
    │  │  │  │  └─modules
    │  │  │  │      └─lib
    │  │  │  │          └─polyfills
    │  │  │  └─src
    │  │  │      └─lib
    │  │  │          └─polyfills
    │  │  ├─webidl-conversions
    │  │  │  └─lib
    │  │  ├─webpack
    │  │  │  ├─bin
    │  │  │  ├─hot
    │  │  │  ├─lib
    │  │  │  │  ├─asset
    │  │  │  │  ├─async-modules
    │  │  │  │  ├─cache
    │  │  │  │  ├─config
    │  │  │  │  ├─container
    │  │  │  │  ├─css
    │  │  │  │  ├─debug
    │  │  │  │  ├─dependencies
    │  │  │  │  ├─electron
    │  │  │  │  ├─errors
    │  │  │  │  ├─esm
    │  │  │  │  ├─hmr
    │  │  │  │  ├─ids
    │  │  │  │  ├─javascript
    │  │  │  │  ├─json
    │  │  │  │  ├─library
    │  │  │  │  ├─logging
    │  │  │  │  ├─node
    │  │  │  │  ├─optimize
    │  │  │  │  ├─performance
    │  │  │  │  ├─prefetch
    │  │  │  │  ├─rules
    │  │  │  │  ├─runtime
    │  │  │  │  ├─schemes
    │  │  │  │  ├─serialization
    │  │  │  │  ├─sharing
    │  │  │  │  ├─stats
    │  │  │  │  ├─util
    │  │  │  │  │  └─hash
    │  │  │  │  ├─wasm
    │  │  │  │  ├─wasm-async
    │  │  │  │  ├─wasm-sync
    │  │  │  │  ├─web
    │  │  │  │  └─webworker
    │  │  │  ├─node_modules
    │  │  │  │  ├─eslint-scope
    │  │  │  │  │  └─lib
    │  │  │  │  └─estraverse
    │  │  │  └─schemas
    │  │  │      └─plugins
    │  │  │          ├─asset
    │  │  │          ├─container
    │  │  │          ├─css
    │  │  │          ├─debug
    │  │  │          ├─ids
    │  │  │          ├─optimize
    │  │  │          ├─schemes
    │  │  │          └─sharing
    │  │  ├─webpack-cli
    │  │  │  ├─bin
    │  │  │  ├─lib
    │  │  │  │  ├─plugins
    │  │  │  │  └─utils
    │  │  │  └─node_modules
    │  │  │      └─commander
    │  │  │          ├─lib
    │  │  │          └─typings
    │  │  ├─webpack-dev-middleware
    │  │  │  ├─dist
    │  │  │  │  └─utils
    │  │  │  ├─node_modules
    │  │  │  │  ├─ajv
    │  │  │  │  │  ├─dist
    │  │  │  │  │  │  ├─compile
    │  │  │  │  │  │  │  ├─codegen
    │  │  │  │  │  │  │  ├─jtd
    │  │  │  │  │  │  │  └─validate
    │  │  │  │  │  │  ├─refs
    │  │  │  │  │  │  │  ├─json-schema-2019-09
    │  │  │  │  │  │  │  │  └─meta
    │  │  │  │  │  │  │  └─json-schema-2020-12
    │  │  │  │  │  │  │      └─meta
    │  │  │  │  │  │  ├─runtime
    │  │  │  │  │  │  ├─standalone
    │  │  │  │  │  │  ├─types
    │  │  │  │  │  │  └─vocabularies
    │  │  │  │  │  │      ├─applicator
    │  │  │  │  │  │      ├─core
    │  │  │  │  │  │      ├─discriminator
    │  │  │  │  │  │      ├─dynamic
    │  │  │  │  │  │      ├─format
    │  │  │  │  │  │      ├─jtd
    │  │  │  │  │  │      ├─unevaluated
    │  │  │  │  │  │      └─validation
    │  │  │  │  │  └─lib
    │  │  │  │  │      ├─compile
    │  │  │  │  │      │  ├─codegen
    │  │  │  │  │      │  ├─jtd
    │  │  │  │  │      │  └─validate
    │  │  │  │  │      ├─refs
    │  │  │  │  │      │  ├─json-schema-2019-09
    │  │  │  │  │      │  │  └─meta
    │  │  │  │  │      │  └─json-schema-2020-12
    │  │  │  │  │      │      └─meta
    │  │  │  │  │      ├─runtime
    │  │  │  │  │      ├─standalone
    │  │  │  │  │      ├─types
    │  │  │  │  │      └─vocabularies
    │  │  │  │  │          ├─applicator
    │  │  │  │  │          ├─core
    │  │  │  │  │          ├─discriminator
    │  │  │  │  │          ├─dynamic
    │  │  │  │  │          ├─format
    │  │  │  │  │          ├─jtd
    │  │  │  │  │          ├─unevaluated
    │  │  │  │  │          └─validation
    │  │  │  │  ├─ajv-keywords
    │  │  │  │  │  ├─dist
    │  │  │  │  │  │  ├─definitions
    │  │  │  │  │  │  └─keywords
    │  │  │  │  │  └─src
    │  │  │  │  │      ├─definitions
    │  │  │  │  │      └─keywords
    │  │  │  │  ├─json-schema-traverse
    │  │  │  │  │  ├─.github
    │  │  │  │  │  │  └─workflows
    │  │  │  │  │  └─spec
    │  │  │  │  │      └─fixtures
    │  │  │  │  └─schema-utils
    │  │  │  │      ├─declarations
    │  │  │  │      │  ├─keywords
    │  │  │  │      │  └─util
    │  │  │  │      └─dist
    │  │  │  │          ├─keywords
    │  │  │  │          └─util
    │  │  │  └─types
    │  │  │      └─utils
    │  │  ├─webpack-dev-server
    │  │  │  ├─bin
    │  │  │  ├─client
    │  │  │  │  ├─clients
    │  │  │  │  ├─modules
    │  │  │  │  │  ├─logger
    │  │  │  │  │  └─sockjs-client
    │  │  │  │  ├─overlay
    │  │  │  │  └─utils
    │  │  │  ├─lib
    │  │  │  │  └─servers
    │  │  │  ├─node_modules
    │  │  │  │  ├─ajv
    │  │  │  │  │  ├─dist
    │  │  │  │  │  │  ├─compile
    │  │  │  │  │  │  │  ├─codegen
    │  │  │  │  │  │  │  ├─jtd
    │  │  │  │  │  │  │  └─validate
    │  │  │  │  │  │  ├─refs
    │  │  │  │  │  │  │  ├─json-schema-2019-09
    │  │  │  │  │  │  │  │  └─meta
    │  │  │  │  │  │  │  └─json-schema-2020-12
    │  │  │  │  │  │  │      └─meta
    │  │  │  │  │  │  ├─runtime
    │  │  │  │  │  │  ├─standalone
    │  │  │  │  │  │  ├─types
    │  │  │  │  │  │  └─vocabularies
    │  │  │  │  │  │      ├─applicator
    │  │  │  │  │  │      ├─core
    │  │  │  │  │  │      ├─discriminator
    │  │  │  │  │  │      ├─dynamic
    │  │  │  │  │  │      ├─format
    │  │  │  │  │  │      ├─jtd
    │  │  │  │  │  │      ├─unevaluated
    │  │  │  │  │  │      └─validation
    │  │  │  │  │  └─lib
    │  │  │  │  │      ├─compile
    │  │  │  │  │      │  ├─codegen
    │  │  │  │  │      │  ├─jtd
    │  │  │  │  │      │  └─validate
    │  │  │  │  │      ├─refs
    │  │  │  │  │      │  ├─json-schema-2019-09
    │  │  │  │  │      │  │  └─meta
    │  │  │  │  │      │  └─json-schema-2020-12
    │  │  │  │  │      │      └─meta
    │  │  │  │  │      ├─runtime
    │  │  │  │  │      ├─standalone
    │  │  │  │  │      ├─types
    │  │  │  │  │      └─vocabularies
    │  │  │  │  │          ├─applicator
    │  │  │  │  │          ├─core
    │  │  │  │  │          ├─discriminator
    │  │  │  │  │          ├─dynamic
    │  │  │  │  │          ├─format
    │  │  │  │  │          ├─jtd
    │  │  │  │  │          ├─unevaluated
    │  │  │  │  │          └─validation
    │  │  │  │  ├─ajv-keywords
    │  │  │  │  │  ├─dist
    │  │  │  │  │  │  ├─definitions
    │  │  │  │  │  │  └─keywords
    │  │  │  │  │  └─src
    │  │  │  │  │      ├─definitions
    │  │  │  │  │      └─keywords
    │  │  │  │  ├─json-schema-traverse
    │  │  │  │  │  ├─.github
    │  │  │  │  │  │  └─workflows
    │  │  │  │  │  └─spec
    │  │  │  │  │      └─fixtures
    │  │  │  │  ├─schema-utils
    │  │  │  │  │  ├─declarations
    │  │  │  │  │  │  ├─keywords
    │  │  │  │  │  │  └─util
    │  │  │  │  │  └─dist
    │  │  │  │  │      ├─keywords
    │  │  │  │  │      └─util
    │  │  │  │  └─ws
    │  │  │  │      └─lib
    │  │  │  └─types
    │  │  │      ├─bin
    │  │  │      └─lib
    │  │  │          └─servers
    │  │  ├─webpack-manifest-plugin
    │  │  │  ├─dist
    │  │  │  └─node_modules
    │  │  │      ├─source-map
    │  │  │      │  ├─dist
    │  │  │      │  └─lib
    │  │  │      └─webpack-sources
    │  │  │          └─lib
    │  │  ├─webpack-merge
    │  │  │  └─dist
    │  │  ├─webpack-sources
    │  │  │  └─lib
    │  │  │      └─helpers
    │  │  ├─websocket-driver
    │  │  │  └─lib
    │  │  │      └─websocket
    │  │  │          └─driver
    │  │  │              └─hybi
    │  │  ├─websocket-extensions
    │  │  │  └─lib
    │  │  │      └─pipeline
    │  │  ├─whatwg-encoding
    │  │  │  ├─lib
    │  │  │  └─node_modules
    │  │  │      └─iconv-lite
    │  │  │          ├─encodings
    │  │  │          │  └─tables
    │  │  │          └─lib
    │  │  ├─whatwg-fetch
    │  │  │  └─dist
    │  │  ├─whatwg-mimetype
    │  │  │  └─lib
    │  │  ├─whatwg-url
    │  │  │  └─dist
    │  │  ├─which
    │  │  │  └─bin
    │  │  ├─which-boxed-primitive
    │  │  │  ├─.github
    │  │  │  └─test
    │  │  ├─which-collection
    │  │  │  ├─.github
    │  │  │  │  └─workflows
    │  │  │  └─test
    │  │  ├─which-typed-array
    │  │  │  ├─.github
    │  │  │  └─test
    │  │  ├─wildcard
    │  │  │  ├─.github
    │  │  │  │  └─workflows
    │  │  │  ├─examples
    │  │  │  └─test
    │  │  ├─workbox-background-sync
    │  │  │  ├─build
    │  │  │  ├─lib
    │  │  │  └─src
    │  │  │      └─lib
    │  │  ├─workbox-broadcast-update
    │  │  │  ├─build
    │  │  │  ├─src
    │  │  │  │  └─utils
    │  │  │  └─utils
    │  │  ├─workbox-build
    │  │  │  ├─build
    │  │  │  │  ├─lib
    │  │  │  │  ├─schema
    │  │  │  │  └─templates
    │  │  │  ├─node_modules
    │  │  │  │  ├─@apideck
    │  │  │  │  │  └─better-ajv-errors
    │  │  │  │  │      ├─dist
    │  │  │  │  │      │  ├─lib
    │  │  │  │  │      │  └─types
    │  │  │  │  │      └─src
    │  │  │  │  │          ├─lib
    │  │  │  │  │          └─types
    │  │  │  │  ├─ajv
    │  │  │  │  │  ├─dist
    │  │  │  │  │  │  ├─compile
    │  │  │  │  │  │  │  ├─codegen
    │  │  │  │  │  │  │  ├─jtd
    │  │  │  │  │  │  │  └─validate
    │  │  │  │  │  │  ├─refs
    │  │  │  │  │  │  │  ├─json-schema-2019-09
    │  │  │  │  │  │  │  │  └─meta
    │  │  │  │  │  │  │  └─json-schema-2020-12
    │  │  │  │  │  │  │      └─meta
    │  │  │  │  │  │  ├─runtime
    │  │  │  │  │  │  ├─standalone
    │  │  │  │  │  │  ├─types
    │  │  │  │  │  │  └─vocabularies
    │  │  │  │  │  │      ├─applicator
    │  │  │  │  │  │      ├─core
    │  │  │  │  │  │      ├─discriminator
    │  │  │  │  │  │      ├─dynamic
    │  │  │  │  │  │      ├─format
    │  │  │  │  │  │      ├─jtd
    │  │  │  │  │  │      ├─unevaluated
    │  │  │  │  │  │      └─validation
    │  │  │  │  │  └─lib
    │  │  │  │  │      ├─compile
    │  │  │  │  │      │  ├─codegen
    │  │  │  │  │      │  ├─jtd
    │  │  │  │  │      │  └─validate
    │  │  │  │  │      ├─refs
    │  │  │  │  │      │  ├─json-schema-2019-09
    │  │  │  │  │      │  │  └─meta
    │  │  │  │  │      │  └─json-schema-2020-12
    │  │  │  │  │      │      └─meta
    │  │  │  │  │      ├─runtime
    │  │  │  │  │      ├─standalone
    │  │  │  │  │      ├─types
    │  │  │  │  │      └─vocabularies
    │  │  │  │  │          ├─applicator
    │  │  │  │  │          ├─core
    │  │  │  │  │          ├─discriminator
    │  │  │  │  │          ├─dynamic
    │  │  │  │  │          ├─format
    │  │  │  │  │          ├─jtd
    │  │  │  │  │          ├─unevaluated
    │  │  │  │  │          └─validation
    │  │  │  │  ├─fs-extra
    │  │  │  │  │  └─lib
    │  │  │  │  │      ├─copy
    │  │  │  │  │      ├─copy-sync
    │  │  │  │  │      ├─empty
    │  │  │  │  │      ├─ensure
    │  │  │  │  │      ├─fs
    │  │  │  │  │      ├─json
    │  │  │  │  │      ├─mkdirs
    │  │  │  │  │      ├─move
    │  │  │  │  │      ├─move-sync
    │  │  │  │  │      ├─output
    │  │  │  │  │      ├─path-exists
    │  │  │  │  │      ├─remove
    │  │  │  │  │      └─util
    │  │  │  │  ├─json-schema-traverse
    │  │  │  │  │  ├─.github
    │  │  │  │  │  │  └─workflows
    │  │  │  │  │  └─spec
    │  │  │  │  │      └─fixtures
    │  │  │  │  ├─source-map
    │  │  │  │  │  └─lib
    │  │  │  │  ├─tr46
    │  │  │  │  │  └─lib
    │  │  │  │  ├─webidl-conversions
    │  │  │  │  │  └─lib
    │  │  │  │  └─whatwg-url
    │  │  │  │      └─lib
    │  │  │  └─src
    │  │  │      ├─lib
    │  │  │      ├─schema
    │  │  │      └─templates
    │  │  ├─workbox-cacheable-response
    │  │  │  ├─build
    │  │  │  └─src
    │  │  ├─workbox-core
    │  │  │  ├─build
    │  │  │  ├─models
    │  │  │  │  └─messages
    │  │  │  ├─src
    │  │  │  │  ├─models
    │  │  │  │  │  └─messages
    │  │  │  │  ├─utils
    │  │  │  │  └─_private
    │  │  │  ├─utils
    │  │  │  └─_private
    │  │  ├─workbox-expiration
    │  │  │  ├─build
    │  │  │  ├─models
    │  │  │  └─src
    │  │  │      └─models
    │  │  ├─workbox-google-analytics
    │  │  │  ├─build
    │  │  │  ├─src
    │  │  │  │  └─utils
    │  │  │  └─utils
    │  │  ├─workbox-navigation-preload
    │  │  │  ├─build
    │  │  │  └─src
    │  │  ├─workbox-precaching
    │  │  │  ├─build
    │  │  │  ├─src
    │  │  │  │  └─utils
    │  │  │  └─utils
    │  │  ├─workbox-range-requests
    │  │  │  ├─build
    │  │  │  ├─src
    │  │  │  │  └─utils
    │  │  │  └─utils
    │  │  ├─workbox-recipes
    │  │  │  ├─build
    │  │  │  └─src
    │  │  ├─workbox-routing
    │  │  │  ├─build
    │  │  │  ├─src
    │  │  │  │  └─utils
    │  │  │  └─utils
    │  │  ├─workbox-strategies
    │  │  │  ├─build
    │  │  │  ├─plugins
    │  │  │  ├─src
    │  │  │  │  ├─plugins
    │  │  │  │  └─utils
    │  │  │  └─utils
    │  │  ├─workbox-streams
    │  │  │  ├─build
    │  │  │  ├─src
    │  │  │  │  └─utils
    │  │  │  └─utils
    │  │  ├─workbox-sw
    │  │  │  ├─build
    │  │  │  └─controllers
    │  │  ├─workbox-webpack-plugin
    │  │  │  ├─build
    │  │  │  │  └─lib
    │  │  │  ├─node_modules
    │  │  │  │  ├─source-map
    │  │  │  │  │  ├─dist
    │  │  │  │  │  └─lib
    │  │  │  │  └─webpack-sources
    │  │  │  │      └─lib
    │  │  │  └─src
    │  │  │      └─lib
    │  │  ├─workbox-window
    │  │  │  ├─build
    │  │  │  ├─src
    │  │  │  │  └─utils
    │  │  │  └─utils
    │  │  ├─wrap-ansi
    │  │  │  └─node_modules
    │  │  │      ├─ansi-styles
    │  │  │      ├─color-convert
    │  │  │      └─color-name
    │  │  ├─wrappy
    │  │  ├─write-file-atomic
    │  │  ├─ws
    │  │  │  └─lib
    │  │  ├─xml-name-validator
    │  │  │  └─lib
    │  │  ├─xmlchars
    │  │  │  ├─xml
    │  │  │  │  ├─1.0
    │  │  │  │  └─1.1
    │  │  │  └─xmlns
    │  │  │      └─1.0
    │  │  ├─y18n
    │  │  │  └─build
    │  │  │      └─lib
    │  │  │          └─platform-shims
    │  │  ├─yallist
    │  │  ├─yaml
    │  │  │  ├─browser
    │  │  │  │  ├─dist
    │  │  │  │  └─types
    │  │  │  ├─dist
    │  │  │  └─types
    │  │  ├─yargs
    │  │  │  ├─build
    │  │  │  │  └─lib
    │  │  │  │      ├─typings
    │  │  │  │      └─utils
    │  │  │  ├─helpers
    │  │  │  ├─lib
    │  │  │  │  └─platform-shims
    │  │  │  └─locales
    │  │  ├─yargs-parser
    │  │  │  └─build
    │  │  │      └─lib
    │  │  └─yocto-queue
    │  ├─public
    │  └─src
    ├─migrations
    │  └─__pycache__
    └─__pycache__
