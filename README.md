# RAGEMP Server Natives

Этот ресурс поможет Вам комфортно использовать нативки на серверной части, теперь не нужно лезть в документацию и искать хэш, просто установите себе этот пакет

## Установка
```
npm i @aspidemon/ragemp-natives@latest
```

## Использование
```js
// ECMA SCRIPT 6
import * as native from '@aspidemon/ragemp-natives';

// ECMA SCRIPT 5
let native = require('@aspidemon/ragemp-natives');

player.invoke(native.WAIT, 100); // Делает задержку скрипта на время, которое Вы указываете
```
