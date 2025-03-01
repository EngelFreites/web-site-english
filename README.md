# 📌 Convenciones para Commits

✅ **Estructura Recomendada**

Cada commit debe seguir este formato:

```sh
  tipo(scope): mensaje breve en presente
```

📌 **Ejemplo**

```sh
refactor(backend): improve route structure

```

## 🎯 Tipos de Commits

- **feat** : ✨ Nueva funcionalidad o característica
- **fix** :🐛 Corrección de errores
- **refactor** : 🔨 Reestructuración del código sin cambiar su funcionalidad
- **docs** : 📖 Cambios en la documentación (README, comentarios, etc.)
- **style** : 🎨 Cambios de formato, espacios, comas. (sin afectar el código)
- **test** : ✅ Agregar o modificar pruebas
- **chore** : 🔧 Mantenimiento, configuración o tareas automáticas
- **ci** : 🔄 Cambios en integración continua (GitHub Actions, Docker, etc.)
- **build** : 🏗 Cambios en dependencias, compilación o herramientas de construcción

## ⚡ Ejemplos de Commits Correctos

```sh
feat(ui): add custom buttons component
fix(api): Fix error in authentication endpoint
docs(readme): Improve the installation guide
test(backend): Add tests for the service layer
chore(linter): Update ESLint configuration
```

## Convención de Nombres de Ramas 🚀

Para una mejor organización en Git, usa esta estructura:

### 📌 Formato

```
<tipo>/<descripcion>
```

Ejemplos:

```
feat/new-feature
```

### ✅ Reglas

✔ Usa **minúsculas y guiones (`-`)**
✔ Sé **claro y preciso**
✔ Evita caracteres especiales

Con esta convención, el repositorio será más ordenado y fácil de gestionar. 🚀
