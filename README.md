# Portafolio — Sergio Gabriel Rueda Piñón

Portafolio personal construido con Astro. Todo el contenido vive en [`cv.json`](./cv.json) — editar ese archivo actualiza el sitio completo.

## Stack

- [Astro](https://astro.build/) — framework web estático
- TypeScript — tipado en componentes y esquema del CV
- CSS nativo — sin framework de estilos

## Correr localmente

```bash
npm install
npm run dev
```

Abre [http://localhost:4321](http://localhost:4321).

## Personalizar

Edita `cv.json` para actualizar datos personales, experiencia, proyectos y habilidades. El esquema sigue la especificación de [jsonresume.org](https://jsonresume.org/schema/).

## Comandos

| Comando       | Acción                                      |
| :------------ | :------------------------------------------ |
| `npm run dev` | Servidor de desarrollo en `localhost:4321`  |
| `npm run build` | Build de producción en `./dist/`          |
| `npm run preview` | Vista previa del build                  |

## Licencia

MIT
