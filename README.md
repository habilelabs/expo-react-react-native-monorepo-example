# expo-react-react-native-monorepo-example
Starter Kit for Monorepo containing react and react native projects.

## Installation
```
git@github.com:habilelabs/expo-react-react-native-monorepo-example.git <project_folder>
cd <project_folder>
yarn install
```
To start web application
```
lerna --scope=web-app run start
```
I also added quick commands. you can use 
```
yarn web
```

To start Native android app
```
lerna --scope=NativeApp run android 
```
or  quick command
```
yarn android
```

To start Native ios App
```
lerna --scope=NativeApp run ios
```

or  quick command
```
yarn ios
```

To start Expo app

```
lerna --scope=ExpoApp run start
```

or  quick command
```
yarn expo
```