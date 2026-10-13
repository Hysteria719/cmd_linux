# Commande pour la clé usb boot 
**Mettre mot de passe root**
```bash
passwd root
```

**Voir adresse ip**
```bash
ip addr
```

 **Changer le pare feu pour autoriser le port 22**
```bash
iptables -I INPUT -p tcp --dport 22 -j ACCEPT
```

**Vérifie s'il écoute sur le port 22**
```bash
ss -lntp | grep :22
```

**Changer claver pour le mettre en azerty**
```bash
loadkeys fr
```

**Voir si le ssh est activé**
```bash
systemctl status sshd
```

**Activer le ssh**
```bash
systemctl start sshd
```

**Voir la version de linux et plus**
```bash
cat /etc/os-release
```