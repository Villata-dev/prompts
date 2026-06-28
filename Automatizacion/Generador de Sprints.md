# Script Bash para generar archivos de infraestructura con commits automáticos

## Rol

Actúa como un **Senior Staff Engineer** experto en metodologías **DevOps** y **Open Source**.

## Objetivo

Genera un script de consola (**Bash**) que automatice la creación y confirmación (**commit**) de **[CANTIDAD]** archivos de infraestructura, configuración y documentación estándar para un repositorio.

## Contexto del proyecto

- **Nombre:** `[NOMBRE DEL PROYECTO]`
- **Lenguajes/Tecnologías:** `[TECNOLOGÍAS]`
  - Ejemplo: `Go`, `React`, `Python`, `Node.js`, `Docker`
- **Enfoque del Sprint:** `[ENFOQUE]`
  - Ejemplo:
    - Pruebas unitarias
    - Integración continua
    - Estandarización de la comunidad
    - Seguridad
    - Observabilidad

## Requisitos técnicos

- Genera un script completamente funcional en **Bash**.
- Utiliza el formato:

```bash
cat << 'EOF' > nombre_archivo
...
EOF
```

para crear cada archivo.

- El contenido de cada archivo debe ser **real, funcional y profesional**.
- **No utilices placeholders vacíos** ni contenido de ejemplo irrelevante.
- Las configuraciones deben estar adaptadas al stack tecnológico indicado.
- Después de crear cada archivo, ejecuta:

```bash
git add nombre_archivo
git commit -m "mensaje"
```

- Todos los mensajes de commit deben seguir estrictamente la especificación **Conventional Commits**, utilizando únicamente alguno de los siguientes prefijos:

- `chore:`
- `docs:`
- `ci:`
- `test:`
- `build:`

## Salida esperada

Devuelve **únicamente** el script Bash completo, listo para copiar y pegar en la terminal.

No incluyas:

- Explicaciones.
- Introducciones.
- Comentarios adicionales.
- Bloques de texto fuera del script.