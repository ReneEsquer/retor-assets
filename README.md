# retor-assets

Imágenes públicas de las tarjetas de **Retor**.

Este repositorio es público **a propósito**: Apple Wallet y Google Wallet exigen
que las imágenes de un pase vivan en una dirección `https://` que sus servidores
puedan alcanzar. No hay nada privado aquí — solo el logotipo y las portadas de
marca, que ya son públicas.

⚠️ **Nunca subas aquí datos de clientes, certificados, `.env` ni credenciales.**
Eso vive en el repositorio privado del proyecto.

## Archivos

| Archivo | Medida | Para qué |
|---|---|---|
| `dragon-express-logo-google.png` | 1024 × 1024 | `programLogo` de Google Wallet. Google lo enmascara en círculo; el rombo lleva 18% de margen para no perder las puntas |
| `hero.png` | 1032 × 336 | `heroImage` de Google Wallet |

## Cómo se usan

Se referencian por su dirección directa:

```
https://raw.githubusercontent.com/ReneEsquer/retor-assets/main/<archivo>
```

Al reemplazar un archivo por otro con el mismo nombre, la dirección no cambia y
la tarjeta se actualiza sola.
