# Más que Dinero — rediseño integral (primera iteración)

## Cómo probarlo
1. Descomprime el paquete completo en una carpeta.
2. Abre `index.html` en el navegador.
3. Prueba el selector «¿Qué te gustaría resolver hoy?» y comprueba que cada opción dirige a la herramienta correspondiente.
4. Navega a las seis herramientas desde la portada y prueba el formulario en escritorio y móvil.

## Qué se cambió
- Nueva portada centrada en acompañamiento sin juicios para jóvenes de 18 a 35 años.
- Navegación por intención: entender el dinero, ordenar deudas, ahorrar o tomar una decisión de compra.
- Recomendación contextual que dirige a la primera herramienta relevante, sin exigir registro.
- Herramientas presentadas con explicaciones más claras y recorridos sugeridos.
- Sección explícita sobre filosofía, privacidad y expectativas realistas.
- Diseño adaptable a móvil/tableta/escritorio, foco visible, botones táctiles y respeto a `prefers-reduced-motion`.
- Conservada la paleta original: azul marino, crema, verde y menta; tipografías DM Sans y Space Grotesk.
- Añadida una capa CSS de consistencia y accesibilidad a las seis herramientas existentes.

## Importante antes de publicar
Esta iteración conserva la lógica JavaScript de las calculadoras existentes; no afirma que las fórmulas financieras hayan sido auditadas. Antes de poner el portal en producción, validar cada fórmula, los casos límite, los mensajes de recomendación y el manejo de datos. La nota de privacidad debe ajustarse a la implementación real y a cualquier analítica o almacenamiento que se agregue.

## Archivos
- `index.html`: nueva portada.
- `diagnostico.html`, `diagnostico-deudas.html`, `cuanto-puedo-gastar.html`, `avalancha-vs-boladenieve.html`, `fondo-de-emergencia.html`, `puedo-comprarlo.html`: herramientas existentes con capa de experiencia compartida.
- `styles.css`: sistema visual base de referencia.
