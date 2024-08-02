# IMPLEMENTACIÓN DE LA CIBERSEGURIDAD

Aunque en el capítulo 1 se menciona que la ciberseguridad no tiene por qué ser costosa y que su implementación no tiene por qué llevar mucho tiempo, puede ser difícil saber por dónde empezar.

En realidad, existen muchas formas diferentes y válidas de implementar la seguridad cibernética. La elección correcta para su organización dependerá de sus objetivos y requisitos, por lo que un buen punto de partida es definir claramente cuáles son. Nuestro enfoque de ocho pasos para implementar la seguridad cibernética, presentado en la parte 4 de este libro, discutirá con más detalle cómo podría hacer esto. Por ahora, considere preguntas básicas como:

- ¿Cómo identificar las amenazas y vulnerabilidades? ¿Se aplica ese proceso de manera consistente?
- ¿Cuáles son sus activos más importantes y qué nivel de protección necesitan?
- ¿Existen regulaciones específicas o requisitos contractuales de ciberseguridad que debe cumplir?
- ¿Qué nivel de seguridad esperan sus clientes?
- ¿Qué hacen sus competidores en términos de seguridad?
- ¿Confía y/o ofrece servicios que deben cumplir con un nivel mínimo de disponibilidad?
- Si sufriera un incidente cibernético o una violación de datos, ¿cuáles serían las consecuencias?
- ¿Cómo sabría si ha ocurrido un incidente?

En esta etapa, no se preocupe por encontrar respuestas completas: estas preguntas solo están destinadas a estimular su reflexión."

**5.1 Hacer concesiones**
Cualquier enfoque de seguridad, incluso si implica no hacer nada en absoluto, requiere concesiones. A corto plazo, la inacción puede parecer más económica y conveniente, pero a largo plazo, enfrentar ataques inevitables puede resultar en costos significativos y molestias (como tratar con reguladores y la prensa, o impacto operativo). Por otro lado, implementar medidas de seguridad también implica compromisos. Por ejemplo, algunas soluciones pueden ser más económicas pero proteger solo contra un tipo de ataque, mientras que otras más costosas podrían ser más fáciles de implementar o más convenientes de usar y mantener. Al tomar decisiones de seguridad, factores como el presupuesto, la privacidad, la comodidad, la complejidad, los recursos y el tiempo deben considerarse cuidadosamente. En última instancia, este proceso es fundamental para la seguridad, ya sea cibernética o de otro tipo: decidir qué sacrificios son necesarios para cumplir con los requisitos de seguridad. En resumen, como en muchas decisiones de la vida, se trata de sopesar pros y contras. Aunque no existe la seguridad perfecta, sí existen soluciones que son perfectas para satisfacer las necesidades de seguridad específicas. 

**5.2 Tres pilares de seguridad**
Cuando se trata de seguridad, es fundamental considerar los tres “pilares”: personas, procesos y tecnología. A menudo, al invertir en seguridad cibernética, las personas se centran exclusivamente en la tecnología, pasando por alto que cualquier medida técnica debe ser implementada y mantenida por personas que sigan procesos definidos. El elemento “personas” no se limita al personal especializado; incluso los usuarios autorizados pueden representar un riesgo debido a errores involuntarios o caer en sofisticados ataques de phishing. La tecnología, como software antimalware y firewalls, puede mitigar amenazas, pero no es perfecta. La formación y concienciación del personal son esenciales para reconocer intentos de phishing y responder adecuadamente. Los tres pilares interactúan en ejemplos cotidianos, como armarios con cerradura que no sirven si no se cierran correctamente o políticas de contraseñas ineficaces. Además, la percepción de seguridad puede diferir de la realidad; el conocimiento de un software antivirus instalado puede generar confianza, pero no debe descuidarse al navegar por la web. Al seleccionar medidas de seguridad, es crucial considerar tanto el aspecto técnico como el humano. 

**5.3 El Marco de Resiliencia Cibernética (CRF) de la Gobernanza de TI**
Cuando se trata de ciberseguridad, hay mucho que asimilar. Sin embargo, no es necesario que realice todo el trabajo preliminar por sí mismo. Los libros, como el que mencionó, pueden proporcionar consejos prácticos y orientación valiosa. Además, existen varios marcos disponibles que ofrecen estructuras probadas para trabajar en la dirección correcta. En el Reino Unido, dos marcos comunes son Cyber Essentials, que se centra en cinco controles básicos, e ISO 27001, que incluye 114 controles sustanciales (aunque solo se espera que implemente los relevantes para su organización). En la parte 5 de este libro, se resumen diez marcos de mejores prácticas diferentes, lo que le ayudará a evaluar las opciones disponibles y encontrar la más adecuada para su organización.

Si estos marcos no son adecuados para usted, tenga en cuenta que este libro se basa principalmente en las mejores prácticas sin hacer referencia a estándares o marcos externos. Sin embargo, los controles de seguridad y los pasos de implementación se basan en el Marco de Gobernanza de TI (CRF), que ofrece una sólida base para proyectos de ciberseguridad. El CRF presenta una amplia selección de procesos, lo que reduce las posibilidades de pasar por alto áreas que requieren controles de seguridad. Además, su flexibilidad le permite implementar solo las medidas necesarias según sus requisitos comerciales y de cumplimiento. El CRF también ofrece niveles de madurez, lo que significa que puede adaptar su enfoque según su sofisticación y necesidades específicas. Además, proporciona un mapeo detallado de procesos en relación con requisitos de cumplimiento. En resumen, el CRF es una herramienta valiosa para cualquier organización que busque fortalecer su seguridad cibernética.

**Cuadro 1: FCI de gobernanza de TI (excluidos los marcos de referencia)**

### Gestiona y proteja

|                                               | RGPD | PCI DSS | Normativa NIS | DSP toolkit |
| --------------------------------------------- | ---- | ------- | ------------- | ----------- |
| Gestión de activos                            | ü    | ü       | ü             | ü           |
| Políticas de seguridad de la información      | ü    | ü       | ü             | ü           |
| Seguridad física y ambiental                  | ü    | ü       | ü             | ü           |
| Control de identidad y acceso                 | ü    | ü       | ü             | ü           |
| Malware                                       | ü    | ü       | ü             | ü           |
| protección                                    |      |         |               |             |
| Configuración y gestión de parches            | ü    | ü       | ü             | ü           |
| Encriptación                                  | ü    | ü       | ü             |             |
| Seguridad del sistema                         | ü    | ü       | ü             | ü           |
| Redes y comunicaciones                        | ü    | ü       | ü             | ü           |
| seguridad                                     |      |         |               |             |
| Competencia en materia de seguridad y         | ü    | ü       | ü             | ü           |
| adiestramiento                                |      |         |               |             |
| Capacitación de concientización del personal  | ü    | ü       | ü             | ü           |
| Programa integral de gestión de riesgos       | ü    | ü       | ü             |             |
| Gestión de riesgos de la cadena de suministro | ü    | ü       | ü             |             |

### Responder y recuperar

|                                       | RGPD | PCI DSS | Normativa NIS | DSP toolkit |
| ------------------------------------- | ---- | ------- | ------------- | ----------- |
| Gestión de respuesta a incidentes     | ü    | ü       | ü             | ü           |
| Gestión de la continuidad de las TIC  |      | ü       | ü             | ü           |
| Gestión de la continuidad del negocio |      | ü       | ü             |             |

### Gobernar y asegurar

|                                                    | RGPD | PCI DSS | Normativa NIS | DSP toolkit |
| -------------------------------------------------- | ---- | ------- | ------------- | ----------- |
| Información formal, seguridad, Programa de gestión | ü    | ü       | ü             | ü           |
| Proceso de mejora continua                         |      |         |               |             |
| Compromiso e implicación de la junta directiva     |      | ü       | ü             | ü           |
| Estructura y procesos de gobernanza                |      |         | ü             | ü           |
| Auditoría interna                                  |      | ü       | ü             |             |
| Certificación/validación externa                   |      | ü       | ü             | ü           |
