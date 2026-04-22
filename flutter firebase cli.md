# 🚀 Instalación de Firebase CLI para Flutter

Guía rápida para instalar y configurar Firebase CLI en un proyecto Flutter desde consola (CMD o Bash).

---

## 📦 1. Instalar Node.js y npm

Firebase CLI depende de Node.js, así que primero debes instalarlo.

### 🐧 En Linux (Fedora)

```bash
sudo dnf install nodejs npm
```

---

### 🪟 En Windows

```bash
curl -L --retry 5 https://npmmirror.com/mirrors/node/latest-v20.x/node-v20.12.2-win-x64.zip -o %USERPROFILE%\node.zip && powershell -Command "Expand-Archive -Force $env:USERPROFILE\node.zip -DestinationPath $env:USERPROFILE\nodejs" && setx PATH "%PATH%;%USERPROFILE%\nodejs\node-v20.12.2-win-x64"
```

⚠️ **Importante:**
Después de instalar Node.js en Windows, debes **cerrar y volver a abrir la consola** para que los cambios en el PATH surtan efecto.

---

### ✅ Verificar instalación

```bash
npm -v
```

---

## 🔥 2. Instalar Firebase CLI

```bash
npm install -g firebase-tools
```

---

### ✅ Verificar instalación

```bash
firebase --version
```

---

## 🔐 3. Iniciar sesión en Firebase

```bash
firebase login
```

Esto abrirá tu navegador para autenticarte con tu cuenta de Firebase.

---

## 📱 4. Configurar Firebase en Flutter

1. Ve a la consola de Firebase:
   👉 [https://console.firebase.google.com/](https://console.firebase.google.com/)

2. Crea un proyecto o selecciona uno existente.

3. Haz clic en **"Agregar app"** y selecciona **Flutter**.

4. Sigue las instrucciones que aparecen en pantalla.

---

## 🎯 5. (Opcional pero recomendado) Instalar FlutterFire CLI

```bash
dart pub global activate flutterfire_cli
```

---

### ✅ Verificar instalación

```bash
flutterfire --version
```

---

## 🧠 Notas adicionales

* Asegúrate de tener Flutter correctamente instalado:

  ```bash
  flutter doctor
  ```
* Si algún comando no funciona, intenta reiniciar la terminal.
* En Linux, puede que necesites permisos adicionales (`sudo`) dependiendo de tu configuración.

---
