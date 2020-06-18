---
layout: default
title: Términos de bases de datos
---

En el mundo de base de datos existe una gran variedad de términos técnicos que deberiamos estar familiarizados:

- **Asincrono:** Es la comunicación más rápida. Quien envía al receptor no espera y continúa con su ejecución inmediatamente.
- **Atómico:** Es uno de los términos que conforma el acronimo del ACID. Hace referencia a todo o nada de una transacción. Como una transacción puede estar conformada por varios pasos, para garantizar la Integridad, hay mecanismos de controles internos que permiten aplicar un cambio sino hay interrupciones en el flujo.
- **CatchUp:** Acción que realiza un slave para actualizarse y tener el lag a cero.
- **Contención:** Hace referencia a la acción producida por el bloqueo. Esto ocurre cuando multiples procesos intentan acceder al mismo recurso simultaneamente y se encuentra bloqueado por otro proceso, y así se apilan los procesos. Esto es debido a que el tiempo de espera para liberar el recurso es muy prolongado.
- **Crawler:** Son aquellos servicios que se encargan de ir extrayendo los datos constantemente para luego ser procesados por otros servicios.
- **DDL:** is Data Definition Language : it is used to define data structures.
- **DML:** is Data Manipulation Language : it is used to manipulate data itself.
- **Fetcher:** Es un crawler.
- **Latencia:** quiere decir que no hay retrazo Which means that there is no lag when the write operations are being written to the disk.
- **Transacción:** Son un conjunto de órdenes que se ejecutan en la DB formando una unidad lógica de trabajo (a esto se le llama atomicidad). transacciones no finalicen en un estado intermedio.
- **Tupla:** Es el termino usado para referirse a un registro de una tabla, dicho termino se utiliza en el lenguaje de base de datos relacional, difiere del termino usado como Row porque es un termino de lexico del SQL.
- **Sincrono:** Quien envía permanece bloqueado esperando a que llegue una respuesta del receptor antes de realizar cualquier otra tarea. Se puede decir que la realización estándar de MySQL es síncrona. Cuando hay escrituras paralelas, se aplican de forma paralela en todos los nodos, mientras en la realización estándar de MySQL es una a la ves.