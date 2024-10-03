# SSH y Conexiones Remotas 🌐🔒

## Introducción a SSH

SSH (Secure Shell) es un protocolo de red que permite a los usuarios conectarse de forma segura a sistemas remotos. Es ampliamente utilizado para:

- Acceso remoto a servidores
- Ejecución de comandos en sistemas remotos
- Transferencia segura de archivos

## Configuración de SSH

Para configurar SSH en tu sistema Linux:

1. Instala el servidor SSH:
   ```bash
   sudo apt-get install openssh-server
   ```

2. Inicia el servicio SSH:
   ```bash
   sudo systemctl start ssh
   ```

3. Habilita SSH para que se inicie automáticamente:
   ```bash
   sudo systemctl enable ssh
   ```

## Conexión a un servidor remoto

Para conectarte a un servidor remoto:

```bash
ssh usuario@direccion_ip
```

Por ejemplo:
```bash
ssh john@192.168.1.100
```

## Transferencia de archivos con SCP

SCP (Secure Copy) te permite transferir archivos de forma segura:

```bash
scp archivo.txt usuario@direccion_ip:/ruta/destino/
```

## Túneles SSH

Los túneles SSH permiten redirigir tráfico de red de forma segura:

```bash
ssh -L puerto_local:host_remoto:puerto_remoto usuario@servidor_ssh
```

## Consejos de seguridad

1. Usa claves SSH en lugar de contraseñas
2. Cambia el puerto SSH predeterminado (22)
3. Limita el acceso SSH a direcciones IP específicas
4. Utiliza autenticación de dos factores

---

🔍 **Próximos pasos**: Aprende sobre [Gestión de Paquetes](9-Gestion%20de%20Paquetes.md) para mantener tu sistema actualizado y seguro.
