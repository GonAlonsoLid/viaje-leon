# Fin de Semana en León

Landing page moderna para un viaje a León y la Maragatería.

## 🖼️ Imagen pendiente

Falta la imagen de **Castrillo de los Polvazares**. Para agregarla:

1. Busca "Castrillo de los Polvazares" en Google Images
2. Descarga la imagen que más te guste
3. Guárdala como: `images/castrillo-polvazares.jpg`
4. Refresca el navegador

## 🚀 Ver localmente

```bash
# Opción 1: Servidor Python
python3 -m http.server 8000
# Abre http://localhost:8000

# Opción 2: Abrir directamente
open index.html
```

## 📦 Desplegar en Vercel

```bash
# 1. Autenticarse (solo la primera vez)
npx vercel login

# 2. Desplegar
npx vercel --prod --yes
```

## 🎨 Características

- ✨ Hero a pantalla completa con imagen de fondo
- 🎯 Navegación sticky con efecto glassmorphism
- 📱 Diseño responsive
- 🎭 Animaciones suaves al cambiar de pestaña
- 🖼️ Imágenes reales de León (Catedral, Hostal San Marcos, Palacio de Gaudí, Basílica San Isidoro)
- 🎨 Tema oscuro moderno con acentos dorados

## 📁 Estructura

```
viaje-leon/
├── index.html          # Página principal
├── images/             # Imágenes locales
│   ├── catedral-leon.jpg
│   ├── hostal-san-marcos.jpg
│   ├── palacio-gaudi.jpg
│   ├── basilica-san-isidoro.jpg
│   └── castrillo-polvazares.jpg  ← Agregar esta
└── README.md
```
