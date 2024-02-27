# v2ray-manager

Modulo pago que permite criar usuarios e testes V2ray com tempo de duração e facil gerenciamento.

![](https://cdn-server.discloud.app/cdn/uploads/image/3w71rczj621pt7qa025h.png)

# Criar um usuario com validade em dias:
```bash
v2ray-manager create_global_user --uuid "74da4900-3d9d-4469-9ede-037d01f73cbf" --email "user@email.com" --validate 30
```


# Deletar um usuario:
```bash
v2ray-manager delete_global_user --uuid "74da4900-3d9d-4469-9ede-037d01f73cbf"
```


# Criar um teste com validade em horas:
```bash
v2ray-manager create_global_test --uuid "74da4900-3d9d-4469-9ede-037d01f73cbf" --email "user@email.com" --validate 1
```

# Deletar um teste:
```bash
v2ray-manager delete_global_test --uuid "74da4900-3d9d-4469-9ede-037d01f73cbf"
```

# Habilitar auto removedor de usuarios expirados:
```bash
v2ray-manager enable_auto_remove
```

# Listar os usuarios criados:
```bash
v2ray-manager list_users
```

https://t.me/Bruno_VPN
