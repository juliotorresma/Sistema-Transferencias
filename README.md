# Sistema-Transferencias
Repositorio dedicado al desarrollo de un sistema de transferencias bancarias

Sistema de Transferencias
Introducción
Actualmente no se cuenta con un sistema de transferencias de dinero entre los clientes del banco, por lo que se requiere la creación de un sistema por el cuál un cliente pueda hacerle una transferencia a otro cliente de su cuenta bancaria.
Cada cliente cuenta con una cuenta bancaria donde tiene su dinero, dichas cuentas tienen un límite de dinero que puede tener almacenado, por lo que se deberá tener en cuenta dicha restricción cuando se haga la transferencia.
Especificaciones
Se requerirá de las siguientes funcionalidades para poder manejar las transferencias:
1)	Una pantalla para identificar que el cliente ya cuenta con usuario y contraseña para poder acceder a realizar la transferencia
2)	Una pantalla para realizar la transferencia a otro cliente, en la cuál se deberá pedir los siguientes datos:
a)	Cantidad a transferir
b)	No. de cuenta del cliente a quién se realizará la transferencia
Se deberá validar que el cliente cuenta con los fondos suficientes para realizar la transferencia, así como también se deberá validar que el número de cuenta al que se quiere transferir exista.
3)	Una pantalla donde el cliente podrá ver la cantidad disponible con que cuenta actualmente y el listado de transferencias que ha realizado.
Consideraciones
Los clientes y su información ya están dados de alta en la base de datos, por lo que no se requiere de una pantalla para dar de alta a dichos clientes ya que actualmente se cuenta con un sistema de manejo de clientes.
Las cuentas de usuario de los clientes para acceder al sistema también ya se tienen registradas en la base de datos.
