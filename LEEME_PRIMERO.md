# 🚀 INSTRUCCIONES ULTRA SIMPLES - GLISH VSL

## ✅ YA ESTÁ TODO LISTO

Solo sigue estos 3 pasos y tu VSL estará online en **10 minutos**.

---

## 📋 PASO 1: SUBIR A GITHUB (3 minutos)

1. **Ir a:** https://github.com/new

2. **Llenar:**
   - Repository name: `glish-vsl`
   - ✅ Public
   - Click **"Create repository"**

3. **Subir archivos:**
   - Click **"uploading an existing file"**
   - Arrastra TODOS los archivos de esta carpeta
   - Click **"Commit changes"**

✅ **Listo!**

---

## 🌐 PASO 2: DEPLOY EN VERCEL (2 minutos)

1. **Ir a:** https://vercel.com

2. **Sign up con GitHub**

3. **Importar:**
   - Click **"Add New..."** → **"Project"**
   - Selecciona `glish-vsl`
   - Click **"Import"**
   - Click **"Deploy"**

4. **Esperar 30 segundos**

5. **Copiar tu URL:** `https://glish-vsl-xxx.vercel.app`

✅ **Tu sitio ya está online!**

---

## ⚙️ PASO 3: CONFIGURAR (5 minutos)

Ahora necesitas poner TUS datos:

### A. Video de YouTube

**Dónde:** Línea 565 del `index.html`

**Busca:**
```html
src="https://www.youtube.com/embed/WTy3utex21w?
```

**Cambia:** `WTy3utex21w` por el ID de TU video

**Ejemplo:**
- Tu video: `youtube.com/watch?v=ABC123`
- Tu ID: `ABC123`

---

### B. HubSpot Meeting

**Dónde:** Línea 629

**Busca:**
```html
data-src="https://meetings.hubspot.com/TU-USUARIO/clase-muestra
```

**Cambia:** `TU-USUARIO` por tu usuario de HubSpot

**Ejemplo:**
- `https://meetings.hubspot.com/diego-roman/clase-muestra?embed=true`

---

### C. WhatsApp

**Dónde:** Línea 518

**Busca:**
```javascript
const manychatURL = 'https://m.me/TU_PAGE_ID?ref=vsl_dudas';
```

**Cambia a:**
```javascript
const manychatURL = 'https://wa.me/52TU_NUMERO?text=Hola,%20vengo%20del%20VSL';
```

**Ejemplo:**
- Tu número: 33 1234 5678
- Pones: `https://wa.me/523312345678?text=Hola,%20vengo%20del%20VSL`

---

### D. Meta Pixel

**Dónde:** Línea 29

**Busca:**
```javascript
fbq('init', 'TU_PIXEL_ID');
```

**Cambia:** `TU_PIXEL_ID` por tu número de pixel

**Dónde encontrarlo:**
- Facebook Events Manager → Pixels → Copiar ID

---

### E. Google Analytics

**Dónde:** Línea 36

**Busca:**
```javascript
gtag('config', 'G-XXXXXXXXXX');
```

**Cambia:** `G-XXXXXXXXXX` por tu Measurement ID

**Dónde encontrarlo:**
- Google Analytics → Admin → Data Streams

---

## 🔄 ACTUALIZAR

Después de hacer los cambios:

1. **GitHub:** Abre `index.html` → Edit (lápiz) → Pega cambios → Commit
2. **Vercel actualiza automático en 30 segundos**

---

## ✅ PROBAR

1. Abre tu URL de Vercel
2. ✅ Video reproduce
3. ✅ Botón "Agenda Clase" abre HubSpot
4. ✅ Botón "Hablar asesor" abre WhatsApp
5. ✅ Todo se ve bien en mobile

---

## 🎯 LANZAR TRÁFICO

1. **Facebook Ads Manager**
2. **Nueva campaña** → Tráfico
3. **URL:** Tu link de Vercel
4. **Presupuesto:** $10-20/día

---

## 🆘 AYUDA RÁPIDA

**Video no carga:**
- Verifica el Video ID
- Que sea video público

**Modal no abre:**
- F12 → Busca errores
- Verifica HubSpot link

**WhatsApp no funciona:**
- Formato: `52` + número sin espacios

---

## 📊 GOOGLE SHEETS (Opcional)

Si quieres backup automático, lee `CONFIGURACION_SHEETS.md`

Tiempo: 15 minutos extra

---

## ✅ RESUMEN

```
1. GitHub: Subir archivos (3 min)
2. Vercel: Deploy (2 min)
3. Configurar: Editar IDs (5 min)

TOTAL: 10 minutos
```

**¡Listo para capturar leads!** 🚀
