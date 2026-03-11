# Contributing

Thanks for contributing.

## Before you open a PR

- Keep the extension read-only.
- Keep the scope tight.
- Prefer simple vanilla JavaScript over framework or build-step additions.
- Open an issue first if the change is large, opinionated, or changes the product direction.

## Good contributions

- Bug fixes
- Compatibility fixes when Polymarket changes DOM structure
- UI polish that improves clarity without adding clutter
- Performance improvements
- Safer reconnect and error handling
- Better documentation

## Out of scope for this public repo

- Trade automation
- Click automation
- Wallet interactions
- Account actions
- Directional entry or exit logic
- Hidden or paywalled behavior

## Development flow

1. Fork the repo and create a branch.
2. Make the smallest change that solves the issue.
3. Reload the unpacked extension locally.
4. Test on a compatible BTC price market page.
5. Include screenshots or screen recordings if the UI changed.

## Pull request checklist

- The change is read-only.
- The extension still loads as an unpacked Chrome extension.
- Any user-facing copy is neutral and clear.
- Documentation is updated when behavior changes.

## Style notes

- Keep comments short and high signal.
- Avoid dead code.
- Avoid adding dependencies unless there is a hard need.

By contributing, you agree that your contributions will be licensed under the MIT License.
