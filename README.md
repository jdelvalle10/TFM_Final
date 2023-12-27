# Caso de uso de Hyperledger Aries y VON Networks para la Credenciales Educactivas <!-- omit in toc -->

## Introduccion
El uso de tecnología blockchain ofrece un enfoque descentralizado y seguro para proteger la integridad y privacidad de los datos. En el entorno escolar, la aplicación de blockchain puede ser especialmente relevante para garantizar la autenticidad de los registros académicos, la protección de la privacidad de los estudiantes y la reducción de fraudes en la emisión de certificados y calificaciones. Este trabajo se centra en explorar cómo blockchain puede ser implementado en las escuelas para fortalecer la seguridad de los datos de estudiantes y proporcionar un sistema de almacenamiento descentralizado y de verificación confiable. Asimismo, se busca desarrollar una prueba de concepto que permita confirmar la factibilidad de una implementación con estas características. Por último, este trabajo intentará evaluar la seguridad, privacidad y habilidad para prevenir fraudes mediante la verificación manual de credenciales, la revisión de la configuración de privacidad de la plataforma seleccionada y pruebas de acceso no autorizado.
## Justificacion

Al permitir la verificación digital y segura de títulos académicos, se reduce la necesidad de imprimir y distribuir documentos en papel, lo que contribuye a la reducción del consumo de recursos naturales y la emisión de gases de efecto invernadero asociados con la producción de papel. Asimismo, la implementación de sistemas blockchain en instituciones educativas puede mejorar la eficiencia administrativa al reducir la carga de trabajo asociada con la verificación manual de credenciales haciendo la actividad administrativa asociada más sostenible. 

La adopción de soluciones basadas en blockchain para la emisión y verificación de credenciales promueve la transparencia y la confianza en el sistema educativo lo cual es esencial para garantizar que los logros académicos se basen en mérito y competencia. Por último, la verificación de títulos basada en blockchain puede ser especialmente útil para estudiantes y profesionales que han obtenido títulos en instituciones extranjeras facilitando la validación de cualificaciones internacionales y promoviendo la diversidad cultural y la movilidad académica y laboral.

Respecto al tema de consumo energético y su correspondiente impacto ambiental, al usar una blockchain como plataforma es importante tomar en cuenta su huella energética. Para el desarrollo del presente trabajo se prevé usar una blockchain que, en contraste con Bitcoin y Ethereum, utilice un enfoque diferente para el consenso y no se base en un algoritmo de Prueba de Trabajo (Proof of Work, PoW), que es reconocido como de muy alto consumo energético por la naturaleza de la prueba criptográfica que usa para validar transacciones y generar bloques nuevos en la blockchain (Johnston, 2017). En lugar de PoW, en este trabajo se buscará utilizar una blockchain que use el enfoque conocido como Prueba de Autoridad (Proof of Authority, PoA). Según Tang, (Tang, 2017) PoA es el algoritmo más eficiente en términos de energía y costo, y también es el más seguro contra ataques.

En PoA, la validación de bloques y la generación de nuevos bloques no dependen de la resolución de algoritmos matemáticos intensivos que requieran una gran cantidad de potencia de cómputo y, por lo tanto, energía. En cambio, los nodos de la red son operados por actores de confianza que se llaman "autoridades" y se les otorga el derecho a validar y crear bloques basados en su identidad y reputación en lugar de resolver desafíos criptográficos costosos en términos de energía.



## Credit

La implementacion inicial ACA-Py fue desarrolada por rl Gobierno de Columbia Britanica y el Trust Team en Canada.


