 
 
## Inicio de proyecto con template Typescript
```bash
 npx react-native init AppAgroVision --template react-native-template-typescript
```


```bash
 Run instructions for Android:
    • Have an Android emulator running (quickest way to get started), or a device connected.
    • cd "C:\Users\guill\Desktop\App AgrovisionIA\AppAgroVision" && npx react-native run-android
```


```bash
  Run instructions for Windows:
    • See https://aka.ms/ReactNativeGuideWindows for the latest up-to-date instructions.
```

## Dependencias

### React Navigation 5.x
```bash
yarn add @react-navigation/native@^5.x
```

### React Stack-Navigation
```bash
yarn add @react-navigation/stack@^5.x
```

### React Axios
```bash
yarn add axios
```

### React react-native-maps
```bash
yarn add react-native-maps
```

### Instalar camara Solo Android
```bash
npm i react-native-camera

../android -> app -> src -> buils.gradle

 defaultConfig {
        applicationId "com.themoviedb"
        minSdkVersion rootProject.ext.minSdkVersion
        targetSdkVersion rootProject.ext.targetSdkVersion
        versionCode 1
        versionName "1.0"
        missingDimensionStrategy 'react-native-camera', 'general'
        multiDexEnabled true
    }
```

##  En caso de Error (una posible solución)

error Failed to install the app. Make sure you have the Android development environment set up: https://reactnative.dev/docs/environment-setup. Run CLI with --verbose flag for more details.
Error: Command failed: gradlew.bat app:installDebug -PreactNativeDevServerPort=8081


Ejecutar

```bash
npx --quiet react-native config  
npx.cmd --quiet react-native config

npm install

Ejecutar 
$ npx react-native run-android 
```


## Revisar logs 

```bash
git log --pretty=oneline
```
## Cargar cambios y versiones

```bash
git branch -M main
git push -u origin main

           (Version) 
git tag -a V1.0.0 -m "Mensaje"
git push --tags
```


### Login de App
![](Img/1.png)

### Inicio de Sesión
![](Img/2.png)

### Mapa con puntos
![](Img/3.png)

### Lista con puntos
![](Img/4.png)

## Tabulación del Código
```bash
alt+shift+f
```