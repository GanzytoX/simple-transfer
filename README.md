# Simple Transfer

> **Generador de Layouts Bancarios para BBVA**

Aplicación de escritorio diseñada para facilitar la creación de archivos de pagos masivos (Layouts) para la banca en línea de BBVA. Permite capturar, validar y exportar transferencias de forma segura y sin errores manuales.

---

## 🚀 Funcionalidades Principales

* **Generación de Archivos TXT:** Archivos listos para el portal bancario cumpliendo con las especificaciones de BBVA.
* **Validación Automática:** Detección instantánea de errores (cuentas incorrectas, caracteres inválidos, montos erróneos).
* **Soporte Completo:** Transferencias a cuentas BBVA (Mismo Banco) y otros bancos (SPEI).
* **Importación Masiva:** Carga masiva desde archivos **Excel** (`.xlsx`) y **CSV**.
* **Modo Oscuro / Claro:** Adaptación automática a la apariencia del sistema.
* **Seguridad y Privacidad:** Procesamiento 100% local sin envío de datos a servidores externos.

---

## 📥 Instalación

1. Descarga el instalador `Simple Transfer Setup 3.0.0.exe` (ubicado en la carpeta `dist`).
2. Ejecuta el archivo `.exe`.
3. Abre el acceso directo **Simple Transfer** en tu escritorio.

---

## 🛠️ Desarrollo

### Requisitos
* **Node.js** y **pnpm**

### Instalación de dependencias
```bash
pnpm install
```

### Comandos disponibles
```bash
# Iniciar modo desarrollo
pnpm dev

# Generar instalador para Windows (.exe)
pnpm build:win
```

---

Desarrollado por **GonzaDev** - 2026.
