# Emacs Solidity Mode Changelog

The changelog starts from version 0.1.4 as too much was added in each version before that.

## Version 0.1.6

- Add gas estimation code. User facing function is `solidity-estimate-gas-at-point`.

## Version 0.1.5

- Add ability to chain flycheck checkers for solidity.
- Add `solidity-flycheck-chaining-error-level` so that user can customize
  the level at which chaining will happen.

## Version 0.1.4

- Integrate with the solium linter
- Allow specification of solium config file via `flycheck-solidity-solium-soliumrcfile`
