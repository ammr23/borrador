**Nombre del Caso de Uso**: Realizar Pedido  
**Actor Principal**: Cliente  
**Descripción**: Permite al cliente seleccionar productos y confirmar un pedido.  
**Precondiciones**: El cliente debe estar autenticado.  
**Flujo Principal**:  
1. El cliente selecciona "Realizar Pedido".  
2. El sistema muestra el carrito de compras.  
3. El cliente confirma los productos.  
4. El sistema solicita dirección de envío.  
5. El cliente ingresa los datos y confirma.  
6. El sistema genera el pedido y notifica al cliente.  

**Flujos Alternativos**:  
- **FA1: Aplicar cupón** (Extensión)  
  3.1. El cliente ingresa un código de descuento.  
  3.2. El sistema valida y aplica el descuento.  

**Excepciones**:  
- **E1: Producto agotado**  
  Si un producto no está disponible, el sistema notifica y sugiere alternativas.  

**Postcondiciones**:  
- Se registra el pedido en el sistema.  
- El cliente recibe un correo de confirmación.  
