# LATI-MEC local server

## Instalación

```bash
npm install
```

## Ejecutar

```bash
npm start
```

La app servirá en:

```bash
http://localhost:3000
```

## Endpoints

- `GET /api/health` → verifica que el servidor está activo
- `GET /api/diagnostic?frequency=3200` → devuelve un diagnóstico simulado según la frecuencia
