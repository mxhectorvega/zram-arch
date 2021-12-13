# zram-arch
Implementacion de Zram optimizada para pc's de bajos recursos xD

**Instrucciones**

**Modo facil**
```bash <(curl -L is.gd/zrammx)```

**Modo manual**
1. Copiar archivo **zram-config-on** y **zram-config-off** en el directorio ```/usr/local/bin/```
2. Copiar archivo **zram-config.service** en el directorio ```/etc/systemd/system```
3. Otorgar los permisos de ejecucion con sudo ```chmod +x``` a los archivos del punto **1 y 2**
4. Habilitar el servicio ```systemctl enable zram-config```
5. Reiniciar o iniciar el servicio ```systemctl start zram-config```

**Web:**
youtube.com/mxhectorvega
