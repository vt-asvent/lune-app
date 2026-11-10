# Lune

Lune es el asistente de escritorio de Asvent para Windows 10 y 11 (64 bits). Aquí se publican sus instaladores; la Lune instalada busca aquí las versiones nuevas y se actualiza con un clic.

## Descargar

[Descargar la última versión](https://github.com/vt-asvent/lune-app/releases/latest/download/Lune-Setup.exe)

Cada versión trae su huella SHA-256 en la página de [versiones](https://github.com/vt-asvent/lune-app/releases). Para comprobar la descarga:

```powershell
Get-FileHash .\Lune-Setup.exe -Algorithm SHA256
```

## Qué hace

- **Classroom:** trae a tu laptop los archivos de tus cursos y los ordena por curso.
- **Ordenar:** lo que llega a Descargas, al Escritorio o desde Classroom va a la carpeta donde tú lo habrías puesto. Trabaja sin internet, no borra ni pisa nada y todo se puede deshacer.
- **MCP:** una IA puede consultar a Lune; lo que mueve archivos pide antes tu visto bueno.

Las actualizaciones van firmadas: Lune solo instala las que llevan la firma de Asvent.

Un producto de Asvent.
