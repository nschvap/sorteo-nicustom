# Sorteo Instagram

Una app web para hacer sorteos de Instagram con animaciones epicas

## Versión Actual (Custom)

Esta es una versión hecha a medida para el primer caso específico, subi 3 publicaciones y tendria que haber hecho una sola. Funciona de forma **manual**: copiás los nombres de los comentarios a mano en orden y los pegás en la app.

### Cómo usar

1. **Abrí el archivo** - Simplemente abrí `sorteo.html` con doble click. Se abre en tu navegador y listo, no necesitás instalar nada.

2. **Copiá los nombres** de los comentarios de tus posts de Instagram
   - Un nombre por línea
   - Si alguien comentó varias veces, repetí su nombre

3. **Pegá en los 3 campos** (uno por publicación)

4. **PREPARAR SORTEO** → espera que cargue

5. **EMPEZAR SORTEO** → ⚠️ **EMPEZÁ A GRABAR ACÁ**

6. Dura ~30 segundos, todo automático

### Limitaciones

- Solo 3 ganadores fijos
- Nombres manuales (no conecta con Instagram)
- Avatares generados (iniciales con colores, no fotos reales)
- Optimizado para celular (480px)

---

## Roadmap - Versión General (TODO)

Checklist de lo que falta para que sea una app completa y automática:

### Automatización
- [ ] Conectar con una api de ig
- [ ] Obtener comentarios automáticamente de los posts sin importar cuantos
- [ ] Descargar fotos de perfil reales de los usuarios
- [ ] Detectar usuarios únicos automáticamente
- [ ] Filtrar comentarios spam/bots (opcional)

### Configuración
- [ ] Elegir cantidad de ganadores (1, 3, 5, 10, etc.)
- [ ] Personalizar nombres de premios ("1er lugar", "Ganador", etc.)
- [ ] Customizar colores y tema
- [ ] Subir logo/marca propia
- [ ] Elegir entre diferentes estilos de animación
- [ ] Configurar duración de cada etapa

### Features
- [ ] Exportar video del sorteo directamente
- [ ] Agregar música/sonidos
- [ ] Responsive (desktop + mobile)
- [ ] Guardar configuraciones para reutilizar
- [ ] Historial de sorteos realizados
- [ ] Excluir participantes manualmente
- [ ] Sorteo con requisitos (seguir + comentar + etiquetar)

### Integración
- [ ] Login con Instagram
- [ ] Seleccionar posts desde la app
- [ ] Preview de comentarios antes de sortear
- [ ] Verificar que cumplan requisitos
- [ ] Notificar ganadores automáticamente (DM)
- [ ] Publicar resultados en historias desde la app

### UX/UI
- [ ] Vista previa antes de grabar
- [ ] Pausar/reiniciar sorteo
- [ ] Modo oscuro / colores

---

## Tech Stack Actual

- HTML/CSS/JavaScript vanilla
- Font Awesome (iconos)
- UI Avatars (avatares)

## Tech Stack Futuro

- React para la UI
- Python + Django para backend
- Meta Graph API para Instagram
- PostgreSQL para DB
- AWS/Vercel para deploy
