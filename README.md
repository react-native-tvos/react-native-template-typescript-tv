# React Native TypeScript Template for TV

Clean and minimalist React Native template for a quick start with TypeScript.

> This template is based on the original [community Typescript template for React Native](https://github.com/react-native-community/react-native-template-typescript). Since React Native added [first-class support for Typescript in version 0.71](https://reactnative.dev/blog/2023/01/03/typescript-first), the original template is no longer being maintained. The maintainers of the [React Native for TV](https://github.com/react-native-tvos/react-native-tvos) will continue to support this template, to allow new app creation with both the React Native CLI and the Expo CLI.

## :star: Features

- Use directly within the [React Native CLI](https://github.com/react-native-community/cli)
- Use directly with the [Expo CLI](https://docs.expo.dev/more/expo-cli/)
- Consistent with the default React Native template
- Minimal additional dependencies

## :arrow_forward: Usage (React Native CLI)

```sh
npx react-native init MyApp --template react-native-template-typescript-tv
cd MyApp
react-native run-android
react-native run-ios
react-native run-ios --scheme=MyApp-tvOS --simulator="Apple TV"
```

## :arrow_forward: Usage (Expo CLI)

```sh
yarn create react-native-app MyApp --template react-native-template-typescript-tv
cd MyApp
npx expo run:android
npx expo run:ios
npx expo run:ios --scheme MyApp-tvOS --device "Apple TV"
```
### Usage with older versions of React Native for TV

#### e.g. `react-native-tvos@0.63.1-3` (previous versions do not have TS types for TV props)

```sh
npx react-native init MyApp --template react-native-template-typescript-tv@6.5.8
```

> Versions prior to 6.12.0 do not support the Expo CLI.

See the below table to find out which version of the template to use.

#### react-native-tvos Version <=> Template Version

| React Native  	| Template  	|
|---	            |---	        |
| 0.63.1-3  	    | 6.5.8-0     |
| 0.66.3-0  	    | 6.5.8-3     |
| 0.68.1-1  	    | 6.5.8-4     |
| 0.69.8-2        | 6.11.9-0    |
| 0.71.10-x       | 6.12.0      |

## :warning: React Native CLI

This template only works with the new React Native CLI. Make sure you have uninstalled the legacy `react-native-cli` first (`npm uninstall -g react-native-cli`) for the below command to work. If you wish to not use `npx`, you can also install the new CLI globally (`npm i -g @react-native-community/cli` or `yarn global add @react-native-community/cli`).

If you tried the above and still get the react-native-template-react- native-template-typescript: Not found error, please try adding the `--ignore-existing` flag to [force npx to ignore](https://github.com/npm/npx#description) any locally installed versions of the CLI and use the latest.

Further information can be found here: https://github.com/react-native-community/cli#about

## :computer: Contributing

Contributions are very welcome. Please check out the [contributing document](CONTRIBUTING.md).

## :bookmark: License

This project is [MIT](LICENSE) licensed.
