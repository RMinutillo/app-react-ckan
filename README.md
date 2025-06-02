# 🚀 Aplicación React Dockerizada (Imagen empaquetada)

Este repositorio contiene una imagen Docker preconstruida de una aplicación React, lista para ejecutar.  
No se incluye el código fuente, solo la imagen comprimida en formato `.tar`.

---

## 📦 Contenido

- `mi-app.tar`: imagen Docker exportada, lista para cargar y ejecutar.
- Este archivo contiene una app React ya compilada y servida con Nginx.

---

## 🐳 Instrucciones para usar la imagen

### 1. Cloná este repositorio

```bash
git clone https://github.com/tu-usuario/mi-repo-dockerizado.git
cd mi-repo-dockerizado
```
### 2. Cargá la imagen Docker desde el archivo .tar
```bash
docker load < mi-app.tar
```
Esto importará la imagen como mi-app.
### 3. Ejecutá la imagen
```bash
docker run -p 80:80 mi-app
```

##ℹ️ Notas
### El contenido fue empaquetado para proteger el código fuente.
### La aplicación está servida por Nginx en un contenedor liviano (nginx:alpine).
### Compatible con Docker Desktop en Windows, macOS y Linux.
