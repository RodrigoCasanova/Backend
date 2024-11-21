# arquitectura
Instalar mariadb con
    usuario: root
    contraseña: duoc

Crear base de datos en mariadb:
    CREATE DATABASE elmirador

JSON para consultas:

marcar_pagado
{
  "CodDepto": "D001",
  "mes": 11,
  "anio": 2024,
  "fecha_pago": "2024-11-15"
}

listar_gastos_pendientes:
{
  "mes": 11,
  "anio": 2024
}

crear_gastos_comunes:
{
  "mes": 11,
  "anio": 2024
}
