## 0.9.2

- Bug fixes in property definitions
- Make sure that argument parsing doesn't crash the app

## 0.9.1

- Fixing startup error

## 0.9.0

- Toast when actions are fired (generate code, copy URL to clipboard, etc)
- CLI now accepts cwd to set a project root outside of the current directory open in terminal
- Generated code includes logs when events are sent in dev

## 0.8.0

- Commit `analytics.avo` and `.avorc` with hardcoded message `[avo] Update event schema` and push to current branch with cmd+p

## 0.7.0

- Add sentry for bug tracking
- Application menu
- Enable standard keyboard shortcuts
- Add `Generate Analytics Library` to `File` menu
- Update to Electron 2.0.0 beta
- Project settings generates a config file (`.avorc`) on every change
- Icons don't randomly disappear any more
- Support for codegen outside of project root

## 0.6.0

- Stop generating `Js.Nullable.from_opt` in favour of `Js.Nullable.fromOption` in Reason. This removes a compiler warning from the generated code.

## 0.5.0

- Add --debug flag to open devtools when launching app

## 0.4.1

- Support both ctrl+k and cmd+k (windows support)

## 0.4.0

- Press cmd+k get new codegen files (only tested on macOS at the moment)

## 0.3.0

- Don't open devtools in prod
- Add traffic lights
- Dragable header
- Layout improvements

## 0.2.0

- Beautify app based on new brand - [@logason](https://github.com/logason)


## 0.1.0

- Init electron project
