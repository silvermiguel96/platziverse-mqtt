## Platziverse-mqtt

## `agent/connected`

```js
{
  agent: {
    uuid, // Auto generar
    username, // Definir por configuración
    name,  // Definir por configuración
    hostname,  // obtener del sistema operativo
    pid // Obtener del proceso
  }
}

```
## `agent/disconnected`

```js
{
  agent: {
    uuid
  }
}
```

## `agent/message`

```js 
{
  agent,
  metrics: [
    {
      type,
      value
    }
  ],
  timestamp // Generar cuando creamos el mensaje
}
```
