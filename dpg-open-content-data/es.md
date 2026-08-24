---
layout: default
title: Mejores prácticas para prevenir la explotación de la IA sobre contenidos y datos abiertos de los Bienes Públicos Digitales (DPG)
permalink: /dpg-open-content-data/es/
---

# {{ page.title }}

---

| Índice |
| :--- |
| [1.0 Introducción y objetivo](#10-introducción-y-propósito) |
| [2.0 Contexto: los retos comunes](#20-contexto-los-retos-comunes) |
| [3.0 Recomendaciones](#30-recomendaciones) |
| &nbsp;&nbsp;[3.1 Transparencia y trazabilidad](#31-transparencia-y-trazabilidad) |
| &nbsp;&nbsp;[3.2 Reciprocidad y reparto de valor](#32-reciprocidad-y-reparto-de-valor) |
| &nbsp;&nbsp;[3.3 Licencias, gobernanza y herramientas jurídicas](#33-licencias-gobernanza-y-herramientas-jurídicas) |
| &nbsp;&nbsp;[3.4 Mecanismos técnicos para los DPG](#34-mecanismos-técnicos-para-los-dpg) |
| [4.0 Conclusión](#40-conclusión) |
| [5.0 Agradecimientos](#50-agradecimientos) |
| [6.0 Referencias](#60-referencias) |

## 1.0 Introducción y objetivo 

Esta nota conceptual presenta las recomendaciones, los mecanismos y el posicionamiento inicial elaborados por los responsables de producto de diversos Bienes Públicos Digitales (DPG) en contenidos y datos abiertos. El documento responde a retos y preocupaciones comunes, detallados en las secciones siguientes. Su objetivo principal es abordar los desafíos prácticos asociados al consumo, procesamiento y uso de contenidos y datos abiertos por parte de: empresas comerciales de modelos de lenguaje a gran escala (LLM), entidades de inteligencia artificial y otras organizaciones de investigación no comerciales <sup>**1**</sup>.

Las recomendaciones expuestas surgen de la necesidad consensuada de salvaguardar el carácter abierto y de bien público de los datos y contenidos de los DPG. Concretamente, buscan asegurar el respeto a la intención original y las licencias vigentes; garantizar que el valor generado por estos recursos se reinvierta y reconozca de manera justa; y beneficiar a las comunidades y partes interesadas responsables de su creación. <sup>**2**</sup>. 

## 2.0 Contexto: los retos comunes

La rápida proliferación y la creciente comercialización de la IA generativa, en particular de los grandes modelos de lenguaje, plantean una serie de retos inéditos para los DPG, que, por definición, funcionan según los principios de apertura, beneficio público y no-exclusividad <sup>**3**</sup>. 

Los modelos de lenguaje a gran escala (LLM) generan beneficios comerciales masivos al recopilar, entrenar y transformar contenidos de bien público en productos propietarios. Mientras el sector del bien público provee la materia prima esencial, persiste una asimetría crítica: no existe retorno de valor hacia quienes crearon dichos recursos. Actualmente falta un mecanismo que garantice reciprocidad, reconocimiento y reinversión sostenible en el ecosistema de los DPG.<sup>**4**</sup>. 

Entre los principales retos a los que se enfrentan los responsables de producto de diversos DPG se incluyen:

1. **Retos técnicos y de infraestructura**: El scraping mediante bots y el uso indebido de rastreadores sobrecargan las API, consumen una cantidad significativa de recursos, aumentan los costes operativos y reducen la usabilidad de las plataformas para los colaboradores y usuarios legítimos.

2. **Impacto de la IA y la tecnología generativa**: Los usuarios acceden cada vez más a la información a través de chatbots con IA en lugar de visitar los proyectos originales, mientras que el contenido abierto es extraído, reempaquetado y relicenciado sin la atribución, compensación o transparencia adecuadas, lo que suscita una preocupación creciente entre los colaboradores y creadores.
   
3. **Sostenibilidad financiera**: La financiación tradicional mediante subvenciones es cada vez menos viable, y la recaudación de fondos resulta más difícil, ya que los donantes están orientando sus programas hacia iniciativas de IA. Al mismo tiempo el declive en métricas cómo tráfico y número de visitas, compromete el argumento de sostenibilidad basado en la existencia de una comunidad de usuarios consolidada. A estas presiones se suma una creciente cautela organizacional frente a compartir datos o contenido abierto ante el riesgo de extracción de valor sin retorno al ecosistema.
  
4. **Falta de transparencia y de mecanismos de exclusión voluntaria**: No existe normativa vigente ni práctica establecida que obligue a declarar el uso de datos, consciente o inadvertido, en el entrenamiento de sistemas de IA. Los DPGs a menudo carecen de visibilidad sobre qué entidades comerciales o no comerciales de modelos de lenguaje a gran escala (LLM) están utilizando su contenido, cómo se está utilizando, o no poseen un mecanismo sencillo para entablar un diálogo, colaborar en objetivos comunes, solicitar el cumplimiento de directrices éticas específicas o "excluirse" (opt-out) de manera efectiva de determinados usos de alto riesgo. La escasa divulgación por parte de las principales empresas de IA sobre cómo y con qué finalidad utilizan los datos dificulta que las organizaciones DPG midan su impacto, protejan sus activos y aseguren financiamiento a largo plazo.

5. **Amenazas al modelo de contribución**: Los modelos de contribución comunitaria están en peligro, cuando actores corporativos extraen datos y contenidos creados por voluntarios sin hacer una inversión recíproca en la sostenibilidad del proyecto, generar incentivos para los colaboradores o respetar la gobernanza abierta. Del mismo modo, cuando los LLM se interponen entre el DPG y su usuario final, el contacto y la buena voluntad o motivación que generaron y sostienen el DPG comienzan a desvanecerse. Si los colaboradores perciben que su trabajo ya no es respetado, reconocido o recompensado, es posible que no vean ningún beneficio en participar y apoyar el desarrollo de los DPG.

6. **Impacto negativo en la comunidad de los DPG**: El uso no consensuado de modelos de lenguaje grande (LLM) está forzando a las comunidades de DPG a crear nuevas políticas y medidas de protección. Esto desvía la capacidad limitada de equipos y voluntarios hacia la resolución de desafíos relacionados con la IA, restando tiempo necesario para el mantenimiento y desarrollo de datos y contenidos abiertos. Además, las posibles medidas para prohibir a empresas comerciales el acceso a estos recursos estarían en tensión con los principios del código abierto y las licencias que rigen los DPG, afectando también a usuarios legítimos que desean apoyar de forma justa a la iniciativa. Si el apoyo comunitario disminuye o la participación se vuelve más compleja, la infraestructura humana detrás de los DPG corre riesgo de colapso.

## 3.0 Recomendaciones

A la luz de los retos comunes descritos anteriormente, se proponen las siguientes recomendaciones no exhaustivas para la colaboración con empresas comerciales de modelos de lenguaje a gran escala, organizaciones de investigación no comerciales y el ecosistema más amplio de la IA, junto con los mecanismos que están explorando los DPG:

### 3.1. Transparencia y trazabilidad

* **Divulgación obligatoria del índice de contenidos:** Se debe instar a las empresas de modelos de lenguaje a gran escala (LLM) a publicar, de forma resumida, las principales fuentes de datos extraídos utilizados en sus corpus de entrenamiento, lo que permitiría a los DPG confirmar si se ha utilizado su contenido.
* **Mecanismo de atribución:** Es necesario avanzar en la definición de estándares que exijan que los resultados generados por IA enlacen y citen los conjuntos de datos originales en los que se basan. Para ello, se debe recurrir a marcos de atribución y guías de buenas prácticas, como los desarrollados por Creative Commons <sup>**5**</sup>. Esto garantiza que el contenido generado por máquinas mantenga una trazabilidad clara hasta sus orígenes de autoría humana, reforzando así el valor de los bienes comunes digitales.

### 3.2. Reciprocidad y reparto de valor

* **Reinversión financiera:** Las empresas comerciales de modelos de lenguaje a gran escala (LLM) que dependen en gran medida del contenido extraído de los DPG, deben establecer un fondo o mecanismo mutuamente sostenible para proporcionar subvenciones, financiación sin restricciones o recursos técnicos a las organizaciones DPG cuyo contenido contribuye a su éxito comercial.
* **Acceso ético a datos para la investigación:** Las empresas comerciales de modelos de lenguaje a gran escala (LLM) deben comprometerse a proporcionar un acceso gratuito, específico y de alta fidelidad a sus modelos avanzados para la investigación y el desarrollo sin ánimo de lucro en los grupos de desarrollo de datos (DPG) y otras comunidades de interés público.

### 3.3. Licencias, gobernanza y herramientas jurídicas

* **Respeto de las políticas de robots (robots.txt):** Los DPG deben mantener actualizados los archivos *robots.txt* que especifiquen claramente las restricciones para los rastreadores automatizados y los bots de IA, definan los parámetros de uso, y protejan los recursos del servidor frente a la extracción indiscriminada de datos. Del mismo modo, las empresas comerciales de LLM y las organizaciones de investigación no comerciales deben comprometerse a desarrollar medidas de protección técnicas y normativas para garantizar su cumplimiento.
* **Cláusulas contra la extracción de datos (scraping) en los Términos y Condiciones de Uso (ToS):** Las organizaciones deben implementar Términos y Condiciones de Uso claros que prohíban explícitamente la recopilación no autorizada de datos a gran escala y el scraping automatizado, estableciendo así una base jurídica para gestionar las interacciones comerciales y proteger los activos de datos de propiedad exclusiva.

### 3.4 Mecanismos técnicos para los DPG

* **Esquema de API por niveles:** Implementar un modelo de acceso por niveles en el que los usuarios públicos, no comerciales y de investigación mantengan un acceso gratuito y sin restricciones, mientras que las entidades comerciales con un gran volumen de tráfico sean dirigidos a un nivel de API de pago que proporcione puntos de conexión dedicados <sup>**6**</sup>. Bajo este modelo, las entidades comerciales pueden pagar por otras funciones especializadas, como flujos de datos en tiempo real y metadatos estructurados. Este mecanismo transforma de manera efectiva la extracción de recursos abiertos en un ciclo de financiación sostenible que se reinvierte en el mantenimiento y la infraestructura humana del ecosistema de los DPG.
* **Implementación de CAPTCHA:** Implementar CAPTCHA o pruebas similares de desafío-respuesta para el tráfico sospechoso con el fin de verificar la interacción humana, mitigando de manera efectiva el acceso automatizado de bots y manteniendo al mismo tiempo la accesibilidad para los usuarios legítimos.
* **Limitación de la tasa de solicitudes con alta puntuación de bot:** Configurar límites dinámicos de tasa de la API basados en patrones de tráfico para evitar el deterioro del servidor debido a una extracción agresiva de datos, garantizando la estabilidad para los usuarios humanos legítimos y los investigadores de ciencia abierta.
* **Firewall de aplicaciones web (WAF):** Implementar soluciones WAF para supervisar y filtrar el tráfico, bloqueando automáticamente los bots de rastreo automatizados conocidos y las fuentes de tráfico malicioso que superen los umbrales de seguridad definidos.

## 4.0 Conclusión

Estas recomendaciones sirven como punto de partida para el diálogo y como marco normativo para regular una relación más equitativa y ética entre los gestores de los Bienes Públicos Digitales (DPG) y los desarrolladores de tecnologías comerciales de IA. 

Los responsables de producto de los Bienes Públicos Digitales (DPG) requieren un apoyo deliberado para reafirmar el valor de la infraestructura humana que sostiene estos recursos. Asimismo, es necesario diseñar mecanismos más seguros que protejan los datos sin obstaculizar la innovación legítima, al tiempo que se motiva a los colaboradores de la comunidad a mantener su compromiso con el ecosistema. Necesitamos un diálogo abierto que no obligue a los miembros de la comunidad a posicionarse a favor o en contra del uso de la IA, sino que les permita colaborar con entidades comerciales y no comerciales para identificar conjuntamente un camino a seguir.

> El Secretariado de la DPGA ha elaborado un [Manual de defensa de la DPG (inglés)](https://strapi.digitalpublicgoods.net/uploads/The_DPG_Defence_Playbook_90d076d138.pdf), una visión general de los mecanismos disponibles para protegerse contra la explotación de la IA y de cómo se ajustan a la definición abierta actual y, por extensión, al estándar DPG. El objetivo del manual es profundizar en la comprensión y la claridad conceptual en torno a la tensión existente entre mantener el acceso abierto y garantizar la supervivencia de un recurso abierto. Seguiremos colaborando con todas las partes interesadas pertinentes y con los responsables de producto de Bienes Públicos Digitales para seguir avanzando en esta labor.

> Si eres experto en alguna de las recomendaciones o retos descritos anteriormente y te gustaría compartir recursos o ideas con los responsables de producto de Bienes Públicos Digitales en el ámbito de los contenidos y datos abiertos a través de sus reuniones comunitarias (específicamente sobre los temas que se indican a continuación), por favor, [envía un correo electrónico](mailto:community@digitalpublicgoods.net).
>  - Medición del impacto de los DPG sobre contenidos y datos abiertos.
>  - Uso ético de la IA para los DPG sobre contenidos y datos abiertos.
>  - Sostenibilidad financiera de los DPG sobre contenidos y datos abiertos.

## 5.0 Agradecimientos

Los siguientes Bienes Públicos Digitales (DPG) participaron en la recopilación de datos y en la elaboración de las conclusiones que han servido de base para esta nota conceptual, con revisiones puntuales por parte de responsables de producto, entre ellos Malvika Sharan, Lucía Ixtacuy, Sergio Bogazzi, Miguelángel Verde, Alicia Seidle y Marc McGowan.

1. [Govdirectory](https://digitalpublicgoods.net/r/govdirectory)  
2. [Storyweaver](https://www.digitalpublicgoods.net/r/storyweaver)  
3. [Wikirate Data](https://www.digitalpublicgoods.net/r/wikirateorg)  
4. [Advocacy Training for Community Health Workers](https://www.digitalpublicgoods.net/r/advocacy-training-for-community-health-workers)  
5. [Global Healthsites Mapping Project](https://www.digitalpublicgoods.net/r/global-healthsites-mapping-project)  
6. [The Land Portal](https://www.digitalpublicgoods.net/r/the-land-portal)  
7. [Open Food Facts](https://www.digitalpublicgoods.net/r/open-food-facts)  
8. [Open Sustainable Technology](https://www.digitalpublicgoods.net/r/open-sustainable-technology)  
9. [Wikipedia](https://www.digitalpublicgoods.net/r/wikipedia)  
10. [The Turing Way](https://www.digitalpublicgoods.net/r/the-turing-way)

## 6.0 Referencias

{% include references/dpg-open-content-data/references.md %}

