from pathlib import Path
import pypandoc

md = r"""# Práctica 4 - Pruebas de Rendimiento con Apache JMeter

## Materia
INF780 – Verificación y Validación de Software

## Herramientas
- Apache JMeter 5.6.3
- Java OpenJDK 21
- NestJS
- PostgreSQL

## API utilizada
Movies API ejecutándose en:

`http://localhost:3000`

## Archivos JMeter

- `smoke.jmx`
- `carga.jmx`
- `estres.jmx`
- `picos.jmx`

## Cómo ejecutar

1. Iniciar PostgreSQL.
2. Levantar la API:

```bash
npm run start:dev