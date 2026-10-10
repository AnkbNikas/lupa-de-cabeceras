# Lupa de cabeceras

**¿Este correo es phishing?** Herramienta web gratuita para comprobar un correo sospechoso, saber qué hacer si ya has hecho clic y obtener un informe del análisis.

👉 **Úsala aquí:** https://ankbnikas.github.io/lupa-de-cabeceras/

## Para quién es

- **Cualquier persona** que reciba un correo raro en su buzón personal.
- **Empleados de empresas** que dudan de un correo del trabajo y necesitan avisar a informática.
- **Analistas de seguridad y peritos**, que tienen el análisis técnico completo y un informe para el expediente.

## Qué hace

- Te dice si el correo tiene pinta de engaño y **por qué**, en lenguaje sencillo, comparando «lo que ves» con «lo que hay detrás».
- **Guía según lo que hayas hecho**: hacer clic, escribir la contraseña, dar datos bancarios, abrir un adjunto, escanear un QR o responder. Los pasos urgentes van primero y cambian si el correo es personal o del trabajo.
- Revisa remitente, Reply-To y Return-Path, SPF/DKIM/DMARC y su alineación, la ruta de entrega, dominios parecidos (homógrafos, punycode, `rn`→`m`), enlaces, adjuntos peligrosos, **códigos QR** en imágenes y PDF, y señales de fraude del CEO (BEC).
- Abre archivos **.eml** y **.msg** de Outlook, incluidos los correos reenviados como adjunto.
- Modo empresa: detecta suplantación de tus directivos y dominios parecidos al tuyo.
- Genera un **informe en PDF**, un mensaje para informática o un aviso para otras personas, y consultas KQL para Microsoft Defender.

## Privacidad

Todo el análisis se hace **en tu navegador**. El correo no se envía a ningún servidor. Solo se descargan, si hacen falta, las librerías para leer QR, PDF y .msg (jsQR, pdf.js y cfb desde jsDelivr). La configuración de tu empresa se guarda únicamente en tu navegador.

## Limitaciones

Es una ayuda, no un veredicto definitivo. No consulta en directo la reputación de dominios o IPs ni la antigüedad de un dominio: ofrece enlaces para hacerlo en VirusTotal, AbuseIPDB y urlscan.

## Autora

Creada por [Nieves Casquero](https://nievescasquero.github.io/), consultora de ciberseguridad y perito informática colegiada (AEPEJU). Para revisar un enlace o un QR suelto: [Antes del Clic](https://ankbnikas.github.io/antes-del-clic/).
