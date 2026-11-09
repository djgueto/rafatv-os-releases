# RAFA TV OS: releases

Actualizaciones firmadas de RAFA TV OS para decodificadores Zgemma. Este repositorio **solo contiene paquetes ya compilados y
firmados**; el código fuente es privado. Cada decodificador comprueba `<modelo>/<canal>/manifest.txt`, verifica su firma ed25519
con la clave pública que lleva la imagen y solo entonces instala. Una actualización sin la firma correcta no se instala.

Estructura: `h17/stable/manifest.txt`, `h17/stable/manifest.txt.sig` y `h17/stable/rafatv-app-X.Y.Z-h17.tar.gz`.
