# Miniapp Ganadores VIP

Miniapp estática para presentar los Planes V.I.P y mostrar pronósticos por plan (clave requerida).

Cómo usar

- Abrir `index.html` en un navegador.
- Para ver pronósticos: clic en "Ver pronóstico del día" e ingresa la clave que entregas por privado en @Trabajand0Ando.
  - Plan Básico: `1234`
  - Plan Tripletas (Especial): `5678`
  - Plan Premium: `9421`

Oferta de bienvenida

- Al afiliarte a cualquier plan recibirás 4 días totalmente GRATIS. Los fines de semana (sábado y domingo) no se cuentan dentro de los días gratis.
- Requiere un depósito de activación; al finalizar el periodo puedes renovar y obtener una bonificación extra por renovación.

Personalización

- Cambia las claves en la variable `KEYS` dentro de `index.html` si quieres otras claves.
- Actualiza los pronósticos estáticos dentro de la función `showForecastResults`.

Subir a GitHub

1. Inicializa el repo localmente (ya incluido en este repositorio):

```powershell
git init
git add .
git commit -m "Initial commit"
```

2. Crea un repositorio nuevo en GitHub y añade el remote (sustituye URL):

```powershell
git remote add origin https://github.com/tu-usuario/tu-repo.git
git branch -M main
git push -u origin main
```

Notas de seguridad

- Actualmente la validación de claves es en el cliente (JavaScript) — no es segura para producción; si quieres validación segura, puedo añadir un pequeño servicio (webhook/API) que verifique claves en el servidor.

Licencia

- Añade una licencia si lo deseas antes de publicar.
