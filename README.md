# Comandos Windows

## CONTRASEÑA DE WIFI DE CUALQUIER USUARIO DE LA RED

Este comando sirve para ver todos los perfiles de red Wi-Fi registrados en el dispositivo.

```bash
netsh wlan show profile
```

Este comando dirve para ver la contraseña de ese perfil.

```bash
netsh wlan show profile nombre_wlan key=clear
```

## LICENCIA DE WINDOWS

Con este comando podremos obtener la clave del producto de la edición de Windows actual.

```bash
wmic path softwarelicensingservice get OA3xOriginalProductKey
```

Este comando desinstala la clave del producto de la edición de Windowsa actual.

```bash
slmgr /upk
```

Este comando sirve para borrar del registro la clave del producto.

```bash
slmgr /cpky
```
