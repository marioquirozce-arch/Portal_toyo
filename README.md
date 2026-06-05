# Portal Toyo Soluciones Tecnologicas

Sitio web institucional de Toyo, orientado a comercializacion, integracion y administracion de tecnologia para empresas, instituciones y gobierno.

## Estructura

- `index.html`: entrada principal del sitio.
- `assets/`: imagenes y recursos estaticos.
- `robots.txt`: configuracion basica para buscadores.
- `sitemap.xml`: mapa del sitio.
- `.github/workflows/`: workflow de Azure Static Web Apps heredado de la base TKINOV.

## Enfoque del sitio

Toyo se posiciona como una comercializadora tecnologica mexicana especializada en:

- Equipo de computo e infraestructura.
- Impresion y fotocopiado administrado.
- Movilidad empresarial.
- Telefonia movil y conectividad.
- Licenciamiento y productividad.
- Servicios administrados.
- Financiamiento, arrendamiento y renovacion tecnologica.

## Partners y capacidades clave

- Lenovo: computo empresarial, estaciones de trabajo, accesorios, renovacion tecnologica y soporte para organizaciones.
- Ivanti: gestion de endpoints, inventario, automatizacion de servicios, seguridad operativa y administracion del ciclo de vida tecnologico.

## Ejecucion local

Este proyecto es un sitio estatico. Para verlo localmente:

```bash
python3 -m http.server 8080
```

Luego abrir:

```text
http://localhost:8080
```

## Publicacion recomendada

La opcion recomendada es crear una Azure Static Web App distinta a la de TKINOV y conectarla a un repositorio nuevo para Toyo, por ejemplo:

```text
marioquirozce-arch/Portal_toyo
```

Configuracion sugerida:

- App location: `/`
- Api location: vacio
- Output location: `/`

## Pendientes antes de produccion

- Reemplazar el wordmark temporal por el logotipo oficial de Toyo.
- Confirmar correo, telefono y WhatsApp de contacto.
- Crear una Azure Static Web App nueva para Toyo.
- Actualizar el workflow con el secret generado por Azure para Toyo.
- Apuntar `www.toyocm.com.mx` desde GoDaddy hacia la Static Web App nueva.
