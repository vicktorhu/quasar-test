# Quasar Test App

Barebone testing app for Quasar Framework. Support building to various platforms.

```json
"scripts": {
    "dev": "quasar dev",
    "dev:pwa": "quasar dev -m pwa",
    "dev:android": "quasar dev -m capacitor -T android",
    "dev:ios": "quasar dev -m capacitor -T ios",
    "dev:elec": "quasar dev -m electron",
    "build": "quasar build",
    "build:pwa": "quasar build -m pwa",
    "build:android": "quasar build -m capacitor -T android",
    "build:ios": "quasar build -m capacitor -T ios",
    "build:elec": "quasar build -m electron",
}
```