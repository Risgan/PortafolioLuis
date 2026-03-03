# 🚀 Portafolio Luis León - GitHub Pages

## ✅ Todo está listo para publicar

Esta carpeta contiene los 7 proyectos compilados y listos para GitHub Pages.

## 📋 Estructura

```
gh-pages/
├── index.html          # Página de inicio
├── .nojekyll          # Archivo para GitHub Pages
├── 1/                 # page1 - Technik Automation (Vite)
├── 2/                 # page2 - Portfolio Web (Next.js)
├── 3/                 # page3 - Business Site (Next.js)
├── 4/                 # page4 - Services Platform (Next.js)
├── 5/                 # page5 - AI Assistant (Vite)
├── 6/                 # page6 - Full Stack App (Next.js)*
└── 7/                 # project - Main Project (Next.js)*
```

**⚠️ Nota**: Los proyectos 6 y 7 tienen bases de datos (Prisma). El frontend funcionará pero las funciones de BD no estarán activas en GitHub Pages.

## 🎯 Pasos para Publicar

### 1. Inicializar Git y subir a GitHub

```powershell
# Asegúrate de estar en la carpeta gh-pages
cd gh-pages

# Inicializa git
git init

# Agrega todos los archivos
git add .

# Haz el commit
git commit -m "Deploy portafolio con 5 proyectos"

# Conecta con tu repositorio (ya existe en GitHub)
git remote add origin https://github.com/Risgan/PortafolioLuis.git

# Renombra la rama
git branch -M main

# Sube a GitHub
git push -u origin main --force
```

### 2. Activar GitHub Pages

1. Ve a: https://github.com/Risgan/PortafolioLuis/settings/pages
2. En **Source**, selecciona: **Deploy from a branch**
3. En **Branch**, selecciona: **main** y carpeta **/ (root)**
4. Click en **Save**

### 3. ¡Espera 2-3 minutos!

Tu sitio estará disponible en:
**https://Risgan.github.io/PortafolioLuis**

## 🌐 URLs de cada proyecto

- **Página Principal**: https://Risgan.github.io/PortafolioLuis
- **Proyecto 1**: https://Risgan.github.io/PortafolioLuis/1
- **Proyecto 2**: https://Risgan.github.io/PortafolioLuis/2
- **Proyecto 3**: https://Risgan.github.io/PortafolioLuis/3
- **Proyecto 4**: https://Risgan.github.io/PortafolioLuis/4
- **Proyecto 5**: https://Risgan.github.io/PortafolioLuis/5
- **Proyecto 6**: https://Risgan.github.io/PortafolioLuis/6 ⚠️
- **Proyecto 7**: https://Risgan.github.io/PortafolioLuis/7 ⚠️

⚠️ = Sin funcionalidad de backend/base de datos

## 📝 Notas

- ✅ Todos los proyectos están configurados correctamente
- ✅ Los builds están optimizados para producción
- ✅ Las rutas están configuradas para GitHub Pages
- ⚠️ Proyectos 6 y 7: El diseño funcionará pero las funciones de base de datos no

## 🔄 Para actualizar en el futuro

Cuando hagas cambios en algún proyecto:

1. Recompila el proyecto modificado
2. Copia el build actualizado a la carpeta correspondiente
3. Haz commit y push de los cambios

```powershell
cd gh-pages
git add .
git commit -m "Actualizar proyecto X"
git push
```

---

**¡Todo listo para publicar! 🎉**
