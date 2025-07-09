ControlComprasJava 💳

Descripción

Sistema básico de gestión de compras con tarjeta de crédito en Java, que permite:

- Registrar compras (descripción + valor)

- Validar saldo disponible

- Ordenar y mostrar transacciones

- Calcular saldo restante

Estructura

src/  

├── Compra.java            # Modelo de compra (implementa Comparable)  

├── TarjetaDeCredito.java  # Lógica de tarjeta y lista de compras  

└── Principal.java         # Interacción con usuario  

Funcionalidades clave

- Uso de ArrayList para almacenar compras

- Ordenamiento con Collections.sort()

- Validación en tiempo real de saldo

Cómo ejecutar

- Compilar y ejecutar Principal.java

- Ingresar límite de tarjeta

- Registrar compras hasta agotar saldo


