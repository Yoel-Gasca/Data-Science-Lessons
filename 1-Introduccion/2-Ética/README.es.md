# Introducción a la ética de los datos

|![Alt text](./img/image.png)|
|:---:|
| Ética de la ciencia de datos: nota de boceto de [@nitya](https://twitter.com/nitya)_ |

---

We are all data citizens living in a datafied world.

Todos somos ciudadanos de datos que vivimos en un mundo con datos.

Las tendencias del mercado nos dicen que en el año 2022, 1 de cada 3 organizaciones grandes compro y vendio sus datos a través de [mercados e intercambios](https://www.gartner.com/smarterwithgartner/gartner-top-10-trends-in-data-and-analytics-for-2020/) en línea. Como **desarrolladores de aplicaciones**, nos resultará más fácil y económico integrar conocimientos basados ​​en datos y automatización basada en algoritmos en las experiencias diarias de los usuarios. Pero a medida que la IA se vuelve omnipresente, también necesitaremos comprender los daños potenciales causados ​​por la [utilización](https://www.youtube.com/watch?v=TQHs8SA1qpk) de tales algoritmos como armas a escala.

Las tendencias también indican que crearemos y consumiremos más de [180 zettabytes](https://www.statista.com/statistics/871513/worldwide-data-created/) de datos para 2025. Como **científicos de datos**,esto nos brinda niveles de acceso a datos personales sin precedentes. Esto significa que podemos crear perfiles de comportamiento de los usuarios e influir en la toma de decisiones de manera que creen una [ilusión de libre elección](https://www.datasciencecentral.com/profiles/blogs/the-illusion-of-choice) y al mismo tiempo, impulsen potencialmente a los usuarios hacia los resultados que preferimos. También plantea preguntas más amplias sobre la privacidad de los datos y la protección de los usuarios.

La ética de los datos es ahora una barrera necesaria para la ciencia y la ingeniería de datos, y nos ayuda a minimizar los daños potenciales y las consecuencias no deseadas de nuestras acciones basadas en datos. El [Gartner Hype Cycle for AI](https://www.gartner.com/smarterwithgartner/2-megatrends-dominate-the-gartner-hype-cycle-for-artificial-intelligence-2020/) dentifica tendencias relevantes en ética digital, IA responsable y gobernanza de la IA como impulsores clave de megatendencias más amplias en torno a la _democratización_ e _industrialización_ de la IA.

![Gartner's Hype Cycle for AI - 2020](https://images-cdn.newscred.com/Zz1mOWJhNzlkNDA2ZTMxMWViYjRiOGFiM2IyMjQ1YmMwZQ==)

En esta lección, exploraremos el fascinante área de la ética de los datos, desde conceptos y desafíos centrales hasta estudios de casos y conceptos de IA aplicados como la gobernanza, que ayudan a establecer una cultura ética en equipos y organizaciones que trabajan con datos e IA.


## [Pre-lecture quiz](https://purple-hill-04aebfb03.1.azurestaticapps.net/quiz/2) 🎯

## Definiciones basicas

Comencemos por comprender la terminología básica.

La palabra “ética” proviene del [vocablo griego “ethikos”](https://en.wikipedia.org/wiki/Ethics) (y su raíz “ethos”) que significa carácter o naturaleza moral .

**La ética** se trata de los valores compartidos y los principios morales que gobiernan nuestro comportamiento en la sociedad. La ética no se basa en leyes sino en normas ampliamente aceptadas sobre lo que es "lo correcto y lo incorrecto". Sin embargo, las consideraciones éticas pueden influir en las iniciativas de gobierno corporativo y las regulaciones gubernamentales que crean más incentivos para el cumplimiento.

**La Ética de Datos** es una [nueva rama de la ética](https://royalsocietypublishing.org/doi/full/10.1098/rsta.2016.0360#sec-1) que "estudia y evalúa problemas morales relacionados con  _datos, algoritmos y prácticas correspondientes_". Aquí, **"los datos"**  se centran en acciones relacionadas con la generación, el registro, la conservación, el procesamiento, la difusión, el intercambio y el uso de los **"algoritmos"** se centran en la IA, los agentes, el aprendizaje automático y los robots, y las **"prácticas"**  se centran en temas como la innovación responsable. programación, hacking y códigos de ética.

**La Ética Aplicada** es la [aplicación práctica de consideraciones morales](https://en.wikipedia.org/wiki/Applied_ethics). Es el proceso de investigar activamente cuestiones éticas en el contexto de _acciones, productos y procesos del mundo real_,  y tomar medidas correctivas para que estos permanezcan alineados con nuestros valores éticos definidos.

**La cultura ética** consiste en [_poner en práctica la ética aplicada_](https://hbr.org/2019/05/how-to-design-an-ethical-organization) para garantizar que nuestros principios y prácticas éticos se adopten de manera consistente y escalable en toda la organización. Las culturas éticas exitosas definen principios éticos en toda la organización, brindan incentivos significativos para el cumplimiento y refuerzan las normas éticas al alentar y amplificar los comportamientos deseados en todos los niveles de la organización.

## Conceptos de ética

En esta sección, discutiremos conceptos como **valores compartidos** (principios) y **desafíos éticos** (problemas) para la ética de los datos, y exploraremos **estudios de casos**que lo ayudarán a comprender estos conceptos en contextos del mundo real.

### 1. Principios éticos

Cada estrategia de ética de datos comienza con la definición de _principios éticos_ - los "valores compartidos" que describen comportamientos aceptables y guían acciones de cumplimiento en nuestros proyectos de datos e inteligencia artificial. Puede definirlos a nivel individual o de equipo. Sin embargo, la mayoría de las organizaciones grandes los describen en una declaración o marco de misión ética de la IA que se define a nivel corporativo y se aplica de manera consistente en todos los equipos.

**Ejemplo:** la declaración de misión [Responsible AI](https://www.microsoft.com/en-us/ai/responsible-ai) de Microsoft dice: _"Estamos comprometidos con el avance de la IA impulsada por principios éticos que ponen a las personas en primer lugar"_ -  identificando seis principios éticos en el marco a continuación:

![Responsible AI at Microsoft](https://docs.microsoft.com/en-gb/azure/cognitive-services/personalizer/media/ethics-and-responsible-use/ai-values-future-computed.png)

Exploremos brevemente estos principios. _La transparencia_ y _la rendición de cuentas_ on valores fundamentales sobre los que se basan otros principios, así que comencemos por ahí:

* [**La rendición de cuentas**](https://www.microsoft.com/en-us/ai/responsible-ai?activetab=pivot1:primaryr6) hace que los profesionales sean responsables de sus operaciones de datos e inteligencia artificial, y del cumplimiento de estos principios éticos.
* [**La transparencia**](https://www.microsoft.com/en-us/ai/responsible-ai?activetab=pivot1:primaryr6)  garantiza que los datos y las acciones de la IA sean comprensibles (interpretables) para los usuarios, explicando el qué y el por qué detrás de las decisiones.
* [**Equidad**](https://www.microsoft.com/en-us/ai/responsible-ai?activetab=pivot1%3aprimaryr6) - se centra en garantizar que la IA trate a todas las personas de manera justa, abordando cualquier sesgo sociotécnico sistémico o implícito en los datos y sistemas.
* [**Fiabilidad y seguridad**](https://www.microsoft.com/en-us/ai/responsible-ai?activetab=pivot1:primaryr6) - garantiza que la IA se comporte de forma coherente con los valores definidos, minimizando posibles daños o consecuencias no deseadas.
* [**Privacidad y seguridad**](https://www.microsoft.com/en-us/ai/responsible-ai?activetab=pivot1:primaryr6) - se trata de comprender el linaje de datos y brindar privacidad de datos y protecciones relacionadas a los usuarios.
* [**Inclusión**](https://www.microsoft.com/en-us/ai/responsible-ai?activetab=pivot1:primaryr6) - se trata de diseñar soluciones de IA con intención, adaptándolas para satisfacer una amplia gama de necesidades y capacidades humanas.

> 🚨 Piense en cuál podría ser su declaración de misión de ética de datos. Explore los marcos éticos de IA de otras organizaciones: aquí hay ejemplos de [IBM](https://www.ibm.com/cloud/learn/ai-ethics), [Google](https://ai.google/principles) y [Facebook](https://ai.facebook.com/blog/facebooks-five-pillars-of-responsible-ai/). ¿Qué valores compartidos tienen en común? ¿Cómo se relacionan estos principios con el producto o la industria de IA en la que operan?

### 2. Desafíos éticos

Una vez que hayamos definido los principios éticos, el siguiente paso es evaluar nuestros datos y acciones de IA para ver si se alinean con esos valores compartidos. Piense en sus acciones en dos categorías: recopilación de datos y diseño de algoritmos. 

Con la recopilación de datos, las acciones probablemente involucrarán **datos personales** o información de identificación personal (PII) de personas vivas identificables. Esto incluye [diversos elementos de datos no personales](https://ec.europa.eu/info/law/law-topic/data-protection/reform/what-personal-data_en) que identifican colectivamente a un individuo. Los desafíos éticos pueden estar relacionados con la privacidad de los datos , la propiedad de los datos y temas relacionados como el consentimiento informado y los derechos de propiedad intelectual de los usuarios.

Con el diseño de algoritmos, las acciones implicarán recopilar y seleccionar **conjuntos de datos**, uego usarlos para entrenar e implementar **modelos de datos** que predigan resultados o automaticen decisiones en contextos del mundo real. Los desafíos éticos pueden surgir del sesgo del conjunto de datos , problemas de calidad de los datos , injusticia y tergiversación en los algoritmos, incluidos algunos problemas que son de naturaleza sistémica.

En ambos casos, los desafíos éticos resaltan áreas donde nuestras acciones pueden entrar en conflicto con nuestros valores compartidos. Para detectar, mitigar, minimizar o eliminar estas preocupaciones, debemos hacer preguntas morales de "sí o no" relacionadas con nuestras acciones y luego tomar las acciones correctivas necesarias. Echemos un vistazo a algunos desafíos éticos y las cuestiones morales que plantean:


#### 2.1 Propiedad de los datos

La recopilación de datos a menudo implica datos personales que pueden identificar a los interesados. [La propiedad de los datos](https://permission.io/blog/data-ownership) se refiere al control y [_los derechos del usuario_](https://permission.io/blog/data-ownership) relacionados con la creación, el procesamiento y la difusión de datos.

Las preguntas morales que debemos plantearnos son: 
 * ¿A quién pertenecen los datos? (usuario u organización)
 * ¿Qué derechos tienen los interesados? (ej: acceso, borrado, portabilidad)
 * ¿Qué derechos tienen las organizaciones? (por ejemplo: rectificar reseñas de usuarios maliciosos)

#### 2.2 Consentimiento informado

[El consentimiento informado](https://legaldictionary.net/informed-consent/) define el acto por el cual los usuarios aceptan una acción (como la recopilación de datos) con una comprensión completa de los hechos relevantes, incluido el propósito, los riesgos potenciales y las alternativas.

Las preguntas para explorar aquí son:
 * ¿El usuario (titular de los datos) dio permiso para la captura y el uso de datos?
 * ¿El usuario entendió el propósito para el cual se capturaron esos datos?
 * ¿El usuario entendió los riesgos potenciales de su participación?

#### 2.3 Propiedad intelectual

[La propiedad intelectual](https://en.wikipedia.org/wiki/Intellectual_property) se refiere a creaciones intangibles resultantes de la iniciativa humana, que pueden tener valor económico para individuos o empresas.

Las preguntas para explorar aquí son:
 * ¿Los datos recopilados tenían valor económico para un usuario o empresa?
 * ¿El usuario tiene propiedad intelectual aquí?
 * ¿La **organización** tiene propiedad intelectual aquí?
 * Si estos derechos existen, ¿cómo los protegemos?

#### 2.4 Privacidad de datos

[La privacidad de los datos](https://www.northeastern.edu/graduate/blog/what-is-data-privacy/) o la privacidad de la información se refiere a la preservación de la privacidad del usuario y la protección de la identidad del usuario con respecto a la información de identificación personal.

Las preguntas para explorar aquí son:
 * ¿Están los datos (personales) de los usuarios protegidos contra ataques y filtraciones?
 * ¿Los datos de los usuarios son accesibles solo para usuarios y contextos autorizados?
 * ¿Se preserva el anonimato de los usuarios cuando se comparten o difunden datos?
 * ¿Se puede desidentificar a un usuario de conjuntos de datos anonimizados?


#### 2.5 Derecho al olvido
El [Derecho al Olvido](https://en.wikipedia.org/wiki/Right_to_be_forgotten) or [Derecho de Supresión](https://www.gdpreu.org/right-to-be-forgotten/)proporciona protección adicional de datos personales a los usuarios. Específicamente, otorga a los usuarios el derecho de solicitar la eliminación o eliminación de datos personales de búsquedas en Internet y otras ubicaciones, bajo circunstancias específicas , permitiéndoles un nuevo comienzo en línea sin que se les apliquen acciones pasadas.

Las preguntas para explorar aquí son:
 * ¿El sistema permite a los interesados ​​solicitar la supresión?
 * ¿La retirada del consentimiento del usuario debería provocar un borrado automático?
 * ¿Se recopilaron datos sin consentimiento o por medios ilegales?
 * ¿Cumplimos con las regulaciones gubernamentales sobre privacidad de datos?


#### 2.6 Sesgo del conjunto de datos

El sesgo de conjunto de datos o [recopilación](http://researcharticles.com/index.php/bias-in-data-collection-in-research/) consiste en seleccionar un subconjunto de datos no representativo para el desarrollo de algoritmos, creando una posible injusticia en los resultados para diversos grupos. Los tipos de sesgo incluyen sesgo de selección o muestreo, sesgo de voluntario y sesgo de instrumento.

Las preguntas para explorar aquí son:
 * ¿Contratamos a un conjunto representativo de interesados?
 * ¿Probamos nuestro conjunto de datos recopilados o seleccionados para detectar diversos sesgos?
 * ¿Podemos mitigar o eliminar cualquier sesgo descubierto?

#### 2.7 Calidad de los datos

[Data Quality](https://lakefs.io/data-quality-testing/) analiza la validez del conjunto de datos seleccionado utilizado para desarrollar nuestros algoritmos, verificando si las características y los registros cumplen con los requisitos del nivel de precisión y coherencia necesarios para nuestro propósito de IA.

Las preguntas para explorar aquí son:
 * ¿Captamos características válidas para nuestro caso de uso?
 * ¿Se capturaron datos de manera consistente en diversas fuentes de datos?
 * ¿Está completo el conjunto de datos para diversas condiciones o escenarios?
 * ¿Se captura la información con precisión para reflejar la realidad?

#### 2.8 Equidad del algoritmo

[La equidad del algoritmo ](https://towardsdatascience.com/what-is-algorithm-fairness-3182e161cf9f) verifica si el diseño del algoritmo discrimina sistemáticamente a subgrupos específicos de interesados, lo que genera [daños potenciales](https://docs.microsoft.com/en-us/azure/machine-learning/concept-fairness-ml) en la asignación (donde se niegan o retienen recursos de ese grupo) y la calidad del servicio (donde la IA no es tan precisa para algunos subgrupos como lo es). es para otros.

Las preguntas para explorar aquí son:
 * ¿Evaluamos la precisión del modelo para diversos subgrupos y condiciones?
 * ¿Examinamos el sistema en busca de daños potenciales (por ejemplo, estereotipos)?
 * ¿Podemos revisar los datos o volver a entrenar los modelos para mitigar los daños identificados?

Explore recursos como [las listas de verificación de equidad de IA](https://query.prod.cms.rt.microsoft.com/cms/api/am/binary/RE4t6dA) para obtener más información.

#### 2.9 Tergiversación

[La tergiversación de datos](https://www.sciencedirect.com/topics/computer-science/misrepresentation) consiste en preguntar si estamos comunicando conocimientos a partir de datos informados honestamente de manera engañosa para respaldar una narrativa deseada.

Las preguntas para explorar aquí son:
 * ¿Estamos reportando datos incompletos o inexactos?
 * ¿Estamos visualizando los datos de una manera que genera conclusiones engañosas?
 * ¿Estamos utilizando técnicas estadísticas selectivas para manipular los resultados?
 * ¿Existen explicaciones alternativas que puedan ofrecer una conclusión diferente?

#### 2.10 Libre Elección

La [ilusión de la libre elección](https://www.datasciencecentral.com/profiles/blogs/the-illusion-of-choice)  ocurre cuando las "arquitecturas de elección" del sistema utilizan algoritmos de toma de decisiones para empujar a las personas a tomar un resultado preferido mientras parecen darles opciones y control. Estos [patrones oscuros](https://www.darkpatterns.org/) pueden causar daños sociales y económicos a los usuarios. Debido a que las decisiones de los usuarios afectan los perfiles de comportamiento, estas acciones potencialmente impulsan decisiones futuras que pueden amplificar o extender el impacto de estos daños.

Las preguntas para explorar aquí son:
 * ¿Entendió el usuario las implicaciones de tomar esa decisión?
 * ¿El usuario conocía las opciones (alternativas) y los pros y los contras de cada una?
 * ¿Puede el usuario revertir una elección automatizada o influenciada más adelante?

### 3. Estudios de caso

To put these ethical challenges in real-world contexts, it helps to look at case studies that highlight the potential harms and consequences to individuals and society, when such ethics violations are overlooked. 

Here are a few examples:

| Ethics Challenge | Case Study  | 
|--- |--- |
| **Consentimiento informado** | 1972 - [Estudio de sífilis de Tuskegee](https://en.wikipedia.org/wiki/Tuskegee_Syphilis_Study) -  A los hombres afroamericanos que participaron en el estudio se les prometió atención médica gratuita, pero los investigadores los engañaron y no informaron a los sujetos sobre su diagnóstico ni sobre la disponibilidad del tratamiento. Muchos sujetos murieron y sus parejas o niños resultaron afectados; el estudio duró 40 años. | 
| **Privacidad de datos** |  2007 - El [premio de datos de Netflix](https://www.wired.com/2007/12/why-anonymous-data-sometimes-isnt/) proporcionó a los investigadores 10 millones de clasificaciones de películas anónimas de 50.000 clientes para ayudar a mejorar los algoritmos de recomendación. Sin embargo, los investigadores pudieron correlacionar datos anónimos con datos de identificación personal en conjuntos de datos externos (por ejemplo, comentarios de IMDb), "desanonimizando" efectivamente a algunos suscriptores de Netflix.|
| **Sesgo de colección**  | 2013 -  la ciudad de Boston [desarrolló Street Bump](https://www.boston.gov/transportation/street-bump), una aplicación que permitía a los ciudadanos informar sobre baches, brindando a la ciudad mejores datos sobre las carreteras para encontrar y solucionar problemas. Sin embargo, [las personas de los grupos de ingresos más bajos tenían menos acceso a automóviles y teléfonos](https://hbr.org/2013/04/the-hidden-biases-in-big-data), lo que hacía que sus problemas viales fueran invisibles en esta aplicación. Los desarrolladores trabajaron con académicos para abordar cuestiones de equidad en materia de acceso equitativo y brechas digitales. |
| **Equidad algorítmica**  | 2018 - The MIT [Gender Shades Study](http://gendershades.org/overview.html) evaluated the accuracy of gender classification AI products, exposing gaps in accuracy for women and persons of color. A [2019 Apple Card](https://www.wired.com/story/the-apple-card-didnt-see-genderand-thats-the-problem/) seemed to offer less credit to women than men. Both illustrated issues in algorithmic bias leading to socio-economic harms.|
| **Tergiversación de datos** | 2020 - The [Georgia Department of Public Health released COVID-19 charts](https://www.vox.com/covid-19-coronavirus-us-response-trump/2020/5/18/21262265/georgia-covid-19-cases-declining-reopening) that appeared to mislead citizens about trends in confirmed cases with non-chronological ordering on the x-axis. This illustrates misrepresentation through visualization tricks. |
| **Ilusión de libre elección** | 2020 - Learning app [ABCmouse paid $10M to settle an FTC complaint](https://www.washingtonpost.com/business/2020/09/04/abcmouse-10-million-ftc-settlement/) where parents were trapped into paying for subscriptions they couldn't cancel. This illustrates dark patterns in choice architectures, where users were nudged towards potentially harmful choices. |
| **Privacidad de datos y derechos del usuario** | 2021 - Facebook [Data Breach](https://www.npr.org/2021/04/09/986005820/after-data-breach-exposes-530-million-facebook-says-it-will-not-notify-users) exposed data from 530M users, resulting in a $5B settlement to the FTC. It however refused to notify users of the breach violating user rights around data transparency and access. |

Want to explore more case studies? Check out these resources:
* [Ethics Unwrapped](https://ethicsunwrapped.utexas.edu/case-studies) - ethics dilemmas across diverse industries. 
* [Data Science Ethics course](https://www.coursera.org/learn/data-science-ethics#syllabus) - landmark case studies explored.
* [Where things have gone wrong](https://deon.drivendata.org/examples/) - deon checklist with examples

> 🚨 Think about the case studies you've seen - have you experienced, or been affected by, a similar ethical challenge in your life? Can you think of at least one other case study that illustrates one of the ethical challenges we've discussed in this section?

## Applied Ethics

We've talked about ethics concepts, challenges ,and case studies in real-world contexts. But how do we get started _applying_ ethical principles and practices in our projects? And how do we _operationalize_ these practices for better governance? Let's explore some real-world solutions: 

### 1. Professional Codes

Professional Codes offer one option for organizations to "incentivize" members to support their ethical principles and mission statement. Codes are _moral guidelines_ for professional behavior, helping employees or members make decisions that align with their organization's principles. They are only as good as the voluntary compliance from members; however, many organizations offer additional rewards and penalties to motivate compliance from members.

Examples include:

 * [Oxford Munich](http://www.code-of-ethics.org/code-of-conduct/) Code of Ethics
 * [Data Science Association](http://datascienceassn.org/code-of-conduct.html) Code of Conduct (created 2013)
 * [ACM Code of Ethics and Professional Conduct](https://www.acm.org/code-of-ethics) (since 1993)

> 🚨 Do you belong to a professional engineering or data science organization? Explore their site to see if they define a professional code of ethics. What does this say about their ethical principles? How are they "incentivizing" members to follow the code?

### 2. Ethics Checklists

While professional codes define required _ethical behavior_ from practitioners, they [have known limitations](https://resources.oreilly.com/examples/0636920203964/blob/master/of_oaths_and_checklists.md) in enforcement, particularly in large-scale projects. Instead, many data Science experts [advocate for checklists](https://resources.oreilly.com/examples/0636920203964/blob/master/of_oaths_and_checklists.md), that can **connect principles to practices** in more deterministic and actionable ways. 

Checklists convert questions into "yes/no" tasks that can be operationalized, allowing them to be tracked as part of standard product release workflows. 

Examples include:
 * [Deon](https://deon.drivendata.org/) - a general-purpose data ethics checklist created from [industry recommendations](https://deon.drivendata.org/#checklist-citations) with a command-line tool for easy integration.
 * [Privacy Audit Checklist](https://cyber.harvard.edu/ecommerce/privacyaudit.html) - provides general guidance for information handling practices from legal and social exposure perspectives.
 * [AI Fairness Checklist](https://www.microsoft.com/en-us/research/project/ai-fairness-checklist/) - created by AI practitioners to support the adoption and integration of fairness checks into AI development cycles.
 * [22 questions for ethics in data and AI](https://medium.com/the-organization/22-questions-for-ethics-in-data-and-ai-efb68fd19429) - more open-ended framework, structured for initial exploration of ethical issues in design, implementation, and organizational, contexts.

### 3. Ethics Regulations

Ethics is about defining shared values and doing the right thing _voluntarily_. **Compliance** is about _following the law_ if and where defined. **Governance** broadly covers all the ways in which organizations operate to enforce ethical principles and comply with established laws.

Today, governance takes two forms within organizations. First, it's about defining **ethical AI** principles and establishing practices to operationalize adoption across all AI-related projects in the organization. Second, it's about complying with all government-mandated **data protection regulations** for regions it operates in.

Examples of data protection and privacy regulations:

 * `1974`, [US Privacy Act](https://www.justice.gov/opcl/privacy-act-1974) - regulates _federal govt._ collection, use ,and disclosure of personal information.
 * `1996`, [US Health Insurance Portability & Accountability Act (HIPAA)](https://www.cdc.gov/phlp/publications/topic/hipaa.html) - protects personal health data.
 * `1998`, [US Children's Online Privacy Protection Act (COPPA)](https://www.ftc.gov/enforcement/rules/rulemaking-regulatory-reform-proceedings/childrens-online-privacy-protection-rule) - protects data privacy of children under 13.
 * `2018`, [General Data Protection Regulation (GDPR)](https://gdpr-info.eu/) - provides user rights, data protection ,and privacy.
 * `2018`, [California Consumer Privacy Act (CCPA)](https://www.oag.ca.gov/privacy/ccpa) gives consumers more _rights_ over their (personal) data.
 * `2021`, China's [Personal Information Protection Law](https://www.reuters.com/world/china/china-passes-new-personal-data-privacy-law-take-effect-nov-1-2021-08-20/) just passed, creating one of the strongest online data privacy regulations worldwide.

> 🚨 The European Union defined GDPR (General Data Protection Regulation) remains one of the most influential data privacy regulations today. Did you know it also defines [8 user rights](https://www.freeprivacypolicy.com/blog/8-user-rights-gdpr) to protect citizens' digital privacy and personal data? Learn about what these are, and why they matter.


### 4. Ethics Culture

Note that there remains an intangible gap between _compliance_ (doing enough to meet "the letter of the law") and addressing [systemic issues](https://www.coursera.org/learn/data-science-ethics/home/week/4) (like ossification, information asymmetry, and distributional unfairness) that can speed up the weaponization of AI. 

The latter requires [collaborative approaches to defining ethics cultures](https://towardsdatascience.com/why-ai-ethics-requires-a-culture-driven-approach-26f451afa29f) that build emotional connections and consistent shared values _across organizations_ in the industry. This calls for more [formalized data ethics cultures](https://www.codeforamerica.org/news/formalizing-an-ethical-data-culture/) in organizations - allowing _anyone_ to [pull the Andon cord](https://en.wikipedia.org/wiki/Andon_(manufacturing)) (to raise ethics concerns early in the process) and making _ethical assessments_ (e.g., in hiring) a core criteria team formation in AI projects.

---
## [Post-lecture quiz](https://purple-hill-04aebfb03.1.azurestaticapps.net/quiz/3) 🎯
## Review & Self Study 

Courses and books help with understanding core ethics concepts and challenges, while case studies and tools help with applied ethics practices in real-world contexts. Here are a few resources to start with.

* [Machine Learning For Beginners](https://github.com/microsoft/ML-For-Beginners/blob/main/1-Introduction/3-fairness/README.md) - lesson on Fairness, from Microsoft.
* [Principles of Responsible AI](https://docs.microsoft.com/en-us/learn/modules/responsible-ai-principles/) - free learning path from Microsoft Learn.
* [Ethics and Data Science](https://resources.oreilly.com/examples/0636920203964) - O'Reilly EBook (M. Loukides, H. Mason et. al)
* [Data Science Ethics](https://www.coursera.org/learn/data-science-ethics#syllabus) - online course from the University of Michigan.
* [Ethics Unwrapped](https://ethicsunwrapped.utexas.edu/case-studies) - case studies from the University of Texas.

# Assignment 

[Write A Data Ethics Case Study](assignment.md)
