# 🐳 Ingeniería del Software

Resposotorio para el trabajo de ejemplo de Docker.

## 📋 Descripción

Este proyecto muestra un archivo HTML estático con **Nginx** dentro de un contenedor **Docker**.

---
## ✅ Prerrequisitos

- **Docker Desktop** instalado y ejecutándose
- **Git** instalado

---
## 🚀 Inicio rápido

### 1️⃣ Clonar el repositorio

```bash
git clone https://github.com/Lu-Schiaffi/Ingenieria-Software.git
```

### 2️⃣ Ubicarse en la carpeta del proyecto
```bash
cd docker-git
```

### 3️⃣ Construir la imagen Docker

```bash
docker build -t nginx-template .
```

### 4️⃣ Ejecutar el contenedor

```bash
docker run -d -p 8080:80 --name YOUR_USER_NAME nginx-template
```

### 5️⃣ Verificar el funcionamiento

Abrí tu navegador y visitá:

[http://localhost:8080](http://localhost:8080)



