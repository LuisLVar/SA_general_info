# Información General - Proyecto de laboratorio


```jsx
Servicios: 

- Registrar Cliente
- Registrar Proveedores
- Registrar categorías
- Registrar Productos
- Login
- Modificar Usuario
- Añadir tarjeta de crédito
```


```jsx
Usuario: {
	nombre: string
	apellido: string
	foto: string
	correo: string
	password: string
	tipo: 'P' | 'C'
	tarjetas: <Tarjeta>[]
}

Tarjeta: {
	titular: string
	numero: int
	vencimiento: string
}
```

```jsx
Categorias: <Categoria>[]

Categoria: {
	nombre: "categoria",
	productos: <Producto>[]
}

Producto: {
 precio: float
 stock: integer
 nombre: string
 descripcion: string
 foto: string
}
```
