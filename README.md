# Desafío Mi Banco

   En este desafío validaremos nuestros conocimientos de Transacciones, Captura de errores en transacciones.

## Descripción

   La empresa Mi Banco SPA está recién registrada y está en búsqueda de un desarrollador fullstack developer que empiece a crear su sistema de transacciones. Previamente los dueños de esta empresa habían intentado crear una institución bancaria pero el software que compraron tenía vulnerabilidades y permitía hacer transacciones sin restricciones, por lo que están exigiendo de extrema necesidad controlar efectivamente los movimientos bancarios para no generar balances negativos y consecuencia con sus clientes.
   En este desafío deberás realizar una aplicación Node que se conecte con PostgreSQL, utilice transacciones para simular el comportamiento de una transacción bancaria.

## Hola, Aquí tenemos instrucciones para ejecutar el programa

    Orden de argumentos:
    node index.js 
    <tipo_transaccion> 
    <cuenta_origen> 
    <fecha> 
    <descripcion> 
    <monto> 
    <cuenta_destino> 
    -----------

## EJEMPLOS

1. - Nueva transacción:
    node index.js nueva 1 "16/10/2020" "Empanadas para el 18" 15000 2

2. - Consulta de últimas transferencias para la cuenta 1
    node index.js consulta 1

3. - Consulta de saldo para la cuenta 1
    node index.js consulta-saldo 1
