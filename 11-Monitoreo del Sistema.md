# Monitoreo del Sistema 📊


## Herramientas de monitoreo en tiempo real

### top
Muestra una vista dinámica de los procesos en ejecución:
```bash
top
```

### htop
Una versión mejorada de top con una interfaz más amigable:
```bash
htop
```

## Monitoreo de recursos

### free
Muestra el uso de memoria:
```bash
free -h
```

### df
Muestra el uso del disco:
```bash
df -h
```

## Monitoreo de procesos

### ps
Muestra los procesos en ejecución:
```bash
ps aux
```

### pgrep
Busca procesos por nombre:
```bash
pgrep firefox
```

## Logs del sistema

### journalctl
Ver los logs del sistema:
```bash
journalctl
```

### tail
Ver las últimas líneas de un archivo de log:
```bash
tail -f /var/log/syslog
```

## Monitoreo de red

### netstat
Muestra las conexiones de red:
```bash
netstat -tuln
```

### iftop
Muestra el uso de ancho de banda en tiempo real:
```bash
sudo iftop
```

## Herramientas avanzadas

### Nagios
Sistema de monitoreo de red y servidores.

### Prometheus
Sistema de monitoreo y alerta de código abierto.

