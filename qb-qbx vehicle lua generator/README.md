
# 🚗 Qbox `vehicles.lua` Generator

A simple, browser-based tool to automatically extract vehicle information from `vehicle.meta` or `vehicles.meta` files and generate a clean `vehicles.lua` file for Qbox-based FiveM servers.

Una herramienta simple basada en navegador para extraer información de vehículos desde archivos `vehicle.meta` o `vehicles.meta` y generar un archivo `vehicles.lua` limpio para servidores FiveM con Qbox.

---

## ✅ Features | Características

- 🔍 Recursively scans all subfolders (ignoring `/stream/`)
- 📄 Supports both `vehicle.meta` and `vehicles.meta`
- 🔑 Uses Lua-safe table keys (e.g. `['1016rwdevo']`)
- 📤 Exports a properly formatted `vehicles.lua` file
- 💻 100% browser-based (no installation or backend required)

---

## 📦 How to Use | Cómo usarlo

### English

1. Open the `Qbox-VehicleMeta-Panel.html` file in **Google Chrome** or **Microsoft Edge**.
2. Click **"📁 Select Folder"** and choose the main folder that contains all your vehicle subfolders.
3. The tool will scan and extract each vehicle's `modelName` and `vehicleMakeName`.
4. Click **"📤 Export vehicles.lua"** to download the result.

### Español

1. Abre el archivo `Qbox-VehicleMeta-Panel.html` en **Google Chrome** o **Microsoft Edge**.
2. Haz clic en **"📁 Select Folder"** y elige la carpeta principal con tus vehículos.
3. La herramienta extrae automáticamente los datos de `modelName` y `vehicleMakeName`.
4. Haz clic en **"📤 Export vehicles.lua"** para descargarlo.

---

## 📁 Output Format | Formato de salida

```lua
-- Folder: YourPackName
['1500ghoul'] = {
    name = '1500ghoul',
    brand = 'Dodge',
    model = '1500ghoul',
    price = 10000,
    category = 'ADDON',
    type = 'automobile',
    hash = `1500ghoul`,
},
```

---

## 🤝 License

Free to use and share. No backend. Built for Qbox/FiveM community.
