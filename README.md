# SignRush

Demo web de un corredor infinito educativo inspirado en la Lengua de Señas Ecuatoriana (LSE). Incluye tres carriles, salto, agacharse, obstáculos, monedas, fichas de señas con demostraciones ilustrativas y aumento progresivo de velocidad.

> **Importante:** los gestos de esta demo son marcadores visuales ilustrativos. No representan instrucción validada de LSE ni deben usarse para aprender señas reales sin acompañamiento de fuentes o docentes cualificados.

## Ejecutar localmente

Necesitas Node.js 20 o superior.

```bash
npm install
npm run dev
```

Abre la dirección local que aparece en la terminal (normalmente `http://localhost:3000`).

## Controles

- `←` / `→` o `A` / `D`: cambiar de carril
- `↑`, `W` o espacio: saltar
- `↓` o `S`: agacharse
- `P` o `Esc`: pausar
- En móvil: usa los cuatro botones en pantalla

## Verificación

```bash
npm run build
```

## Orden de commits sugerido

El proyecto se deja sin commits hasta que configures tu identidad Git. Para conservar una historia clara, registra los cambios en este orden: `chore: initialize web project`, `feat: add three-lane runner movement`, `feat: add jump and duck controls`, `feat: add obstacles and collision states`, `feat: add coins and score tracking`, `feat: add illustrative sign-token rewards`, `feat: increase pace with progress`, `feat: finish responsive Spanish game UI`, `docs: add local setup and demo disclaimer`.
