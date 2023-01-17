
<div align="center">
    <h1>Curso de Introducción a la Nube con Azure</h1>
    <img src="https://static.platzi.com/media/achievements/badge-introduccion-nube-azure-05c6de71-609b-4b00-971c-56a8d88915d2.png" width="">
    <img src="https://i.imgur.com/wL2G5A8.png" width="">
</div>

# Aprender sobre la nube
* https://learn.microsoft.com/en-us/certifications/
* https://quique-olazaran.notion.site/quique-olazaran/Microsoft-Fundamentos-AZ-900-aafa18a3543944999292642d57c67f44

## Beneficios y consideraciones del uso de servicios en la nube
### Alta Disponibilidad
💡 La `disponibilidad` se refiere al hecho de cuanto tiempo se encuentra un servicio disponible, para acceder al mismo.

> ¿Por qué perderíamos disponibilidad?
> 
- **Problema en la red** **(Múltiples conexiones entre varios recursos).**
- **Bug de una aplicación** **(Regularmente el responsable es el creador del software).**
- **Falla del sistema** **(Ocurre cuando una VM corriendo un S.O. particular se torna como "NO DISPONIBLE").**
- **Corte de energía.**


💡 `Alta disponibilidad:` Contar con la mayor cantidad de tiempo de disponibilidad de nuestros recursos.

✅ Lo ideal es contar con la mayor cantidad de tiempo de disponibilidad en nuestros recursos.

Los proveedores en la nube, brindan un **Acuerdo de Nivel de Servicio (SLA)** que garantiza cierto nivel de disponibilidad de los recursos con un porcentaje (%). 

Este acuerdo es muy cercano al 100%. 💯

Únicamente aplica para los recursos controlados por el proveedor. 🌐

### Escalabilidad
💡 `Escalabilidad` se refiere al hecho de incrementar o decrementar los recursos o servicios basados en la demanda o carga de trabajo en determinado tiempo.

---


💡 `Escalamiento Vertical` Es el proceso de agregar más recursos para incrementar el poder de un servidor existente **(Memoria, CPU, SSD, etc.).**

![Untitled](https://quique-olazaran.notion.site/image/https%3A%2F%2Fs3-us-west-2.amazonaws.com%2Fsecure.notion-static.com%2Fbbaf870d-f143-4d1c-9e75-38e87cd89f44%2FUntitled.png?id=27818387-bd9c-4a8f-b66a-62a8fee3540b&table=block&spaceId=976dd965-5699-47c3-8b7a-0e4e80bae9fa&width=480&userId=&cache=v2)

💡 `Escalamiento Horizontal` Crear una copia exacta del servidor para que ya no sea solo uno, sino sean dos los que reciben solicitudes **(de tráfico de red)** o trabajen en ciertos procesos.

Estos dos servidores tendrían las mismas capacidades técnicas pero trabajarían en conjunto como una sola unidad, a este proceso se le llama escalamiento horizontal.

![Untitled](https://quique-olazaran.notion.site/image/https%3A%2F%2Fs3-us-west-2.amazonaws.com%2Fsecure.notion-static.com%2F6408b4f5-1f73-4a02-8b07-435df28e86e6%2FUntitled.png?id=450d4dcb-cf67-4ff2-8972-a980acbef0aa&table=block&spaceId=976dd965-5699-47c3-8b7a-0e4e80bae9fa&width=1200&userId=&cache=v2)

![Untitled](https://quique-olazaran.notion.site/image/https%3A%2F%2Fs3-us-west-2.amazonaws.com%2Fsecure.notion-static.com%2F016f772b-6568-4a42-8a84-4c7d336196fe%2FUntitled.png?id=7bbb530a-3e57-4ce4-8ca1-0a6085fe8b45&table=block&spaceId=976dd965-5699-47c3-8b7a-0e4e80bae9fa&width=1320&userId=&cache=v2)

![](https://static.platzi.com/media/user_upload/1-27218f9e-d785-4b42-895e-7730e97184ec.jpg)
![](https://static.platzi.com/media/user_upload/2-0f51246a-638c-4e3f-a91d-7b1bddd2304a.jpg)


## Introducción al Cómputo en la nube
### **Conociendo Azure**

- Qué es
- Azure Portal
- Marketplace
- Servicios

### **Servicios:**

- Cómputo
- Web
- Almacenamiento
- BBDD
- Red
- IA
- DevOps
- Entornos
- Serverless
- IoT
- Seguridad

### **Componentes de Azure**

- Suscripciones
- Grupos de administración
- Recursos
- Grupos de recursos
- Regiones

### **Seguridad y privacidad**

- Protección de la información.
- Red segura.
- Servicios de identidad.
- Gobernanza de la nube.
- Estándares de privacidad.

### **Acuerdo de nivel de servicio**

- Acuerdos.
- Ciclo de vida del servicio.
- Administración de costos de servicio.

### Certificaciones Microsoft

**Developer:** Diseñan, construyen, prueban y mantienen soluciones para la nube:

- Azure Developer
- Developer Associate
- Dynamics 365
- Power Platform Developer
- IoT Developer

**Solutions Architect:** Expertos en cómputo, redes, almacenamiento y seguridad:

- Azure Solutions
- Power Platform
- Finance and Operations Apps

**DevOps Engineer:** Combinan personas, procesos y tecnologías para entregar productos de valor y servicios de forma continua:

- Azure DevOps Engineer Expert

**Security Engineer:** Implementan controles de seguridad y protección de amenazas para accesos, datos, aplicaciones y redes: 

- Azure Security Engineer
- Security Operations
- Indentity and Access

**Administrator:** Implementan, monitorean y mantienen soluciones.

- Azure Administrator
- Windows Virtual Desktop
- Teams Administrator
- Security Administrator

**Data Engineer:** Diseñan e implementan la administración, monitoreo, seguridad y privacidad de datos 

- Azure Data Engineer Associate

**Data Scientist:** Aplican técnicas de machine learning para entrenar, evaluar y desplegar modelos que resuelven problemas de negocio:

- Azure Data Scientist Associate

**AI Engineer:** Usan servicios cognitivos, machine learning y knowledge mining para diseñar e implementar soluciones:

- Azure AI Engineer Associate.


## 2- ¿Qué es la nube? Ventajas y características
### ¿Qué es la nube?

La nube son instalaciones en las cuales cada una tiene de forma independiente energia electrica, refrigeración y seguridad, son llamados Centro de Datos. Dentro de ellos se encuentran cientos de equipos conectados a Internet para consumir los servicios ofrecidos en la Nube.

Los Centros de Datos se encuentran distribuidos a lo largo del mundo. Azure es el servicio Cloud que tiene mas DataCenters desplegados a nivel mundial.

<aside>
💡 Azure (Microsoft) busca que sus DataCenters sean 100% sustentables utilizando Energias Limpias

</aside>

### ¿Para qué o Por qué?

- Cómputo
- Servidores
- Almacenamiento y bases de datos
- Redes
- Inteligencia Artificial
- Software y mas

> "Todo lo que puedes hacer en una computadora se puede hacer en la nube pero más: **barato, ágil y seguro**"
> 

### Modelo basado en consumo

Pago por servicios usados:

- Reduce costos operativos
- Optimiza la infraestructura
- Escala según las necesidades

### CapEx vs OpEx

- **Gastos de capital (CapEx):** Inversión en infraestructura física, deducible a largo plazo
- **Gastos operativos (OpEx):** Inversión en servicios o productos facturados al momento

### Ventajas

**Confiabilidad y Alta Disponibilidad**

- Experiencia de usuario sin tiempo de inactividad perceptible, aunque haya errores

**Escalable**

- Vertical: aumentando RAM | CPU a una VM
- Horizontal: aumentado instancias de recursos

**Elasticidad**

- Las aplicaciones siempre tendrán los recursos necesarios

**Agilidad**

- Instanciar recursos en la nube es muy rápido de implementar y configurar

**Distribución geográfica**

- DataCenter en todo el mundo ofreciendo el mejor rendimiento a cada región

**Recuperación ante desastres**

- Los datos se protegen con copias de seguridad, replicación de datos y distribución geográfica

# ¿Qué es la nube? Ventajas y características

Son instalaciones en la cual cada una tiene de forma independiente energía, refrigeración, y seguridad. 

Azure se toma muy en serio la seguridad, tanto así que la dirección de los Data Center no es pública. Los empleados de Microsoft no pueden acceder sin permisos, de hecho quienes ingresan cuentan con los permisos y cumplen los requisitos para llegar a ellos.

Dentro de cada Data Center encontraran **servidores** y **computadoras**, cientos de estos equipos y todos **conectados** los cuales podemos **acceder a través de internet**.

Los Data Center de Azure se encuentran distribuidos por todo el mundo.

![](https://bush-socks-586.notion.site/image/https%3A%2F%2Fs3-us-west-2.amazonaws.com%2Fsecure.notion-static.com%2F39d0ac84-31ed-4eb0-ae7a-958cc5d15edd%2FUntitled.png?id=d1ecd144-f62e-4ee6-b9bf-ef3ec3b8474a&table=block&spaceId=a735bb1c-a61b-4978-a1e7-3c13c96a025e&width=1380&userId=&cache=v2)

**Azure es el servicio en la nube que mas Data Center** **ofrece a lo largo del mundo** y cada día habrá más y más. Cada ubicación de los Data Center es estratégica.

Los Data Center (ahora en adelante **DC**) consumen mucha energía y Microsoft busca que estos sean 100% sustentables utilizando energías limpias, como sumergirlas en el mar que también ayuda a que haya más DC en regiones costeras.

**¿PARA QUÉ O QUÉ?**

La nube principalmente nos brinda servicios de cómputo, servidores, máquinas virtuales, almacenamiento, redes, bases de datos, IA, etc.

"*Todo lo que puedes realizar en una computadora se puede hacer en la nube pero más: **barato, ágil y seguro***". Esto es porque el modelo de servicios de la nube es el **modelo de consumo,** lo cual quiere decir que no tienes que invertir en infraestructura y esto reduce costos corporativos porque Azure ya cumple con esto. Azure te ofrecerá escalamiento cuando un recurso lo necesite y no te tendrás que preocupar por el espacio o capacidad de sistema. 

**Modelo basado en consumo**

Pago por servicios usados:

- Reduce costos operativos.
- Optimiza la infraestructura.
- Escala según necesidades.

Hay dos conceptos que van ligados con este modelo.

- **Gastos de capital (CapEx):** Es la inversión en infraestructura física, que es deducible a largo plazo.
- **Gastos operativos (OpEx):** Es la inversión en servicios que se pagan mensualmente o se facturan al momento. Los servicios no se encuentran físicamente en la empresa ya hay que un proveedor que los ofrece

**Confiabilidad y alta disponibilidad**

Es la experiencia de usuario sin tiempo de inactividad perceptible, aunque haya errores. Los DC se van a encargan de que nuestros servicios cuente con la mayor disponibilidad, replicando los servicios en diferentes DC.

**Escalabilidad**

- **Vertical:** Que escala un solo equipo, aumentando su capacidad como RAM, CPU entre otros en una VM.
- **Horizontal:**  Aumenta la instancia de los recursos

**Elasticidad**

La nube siempre tendrá los recursos necesarios. No hay problema si una aplicación es muy demandante en cuanto a recursos porque los DC siempre van a estar trabajando.

**Agilidad**

Instanciar recursos en la nube es muy rápido de implementar y configurar

**Distribución geográfica**

La distribución geográfica asegura que este disponible para todo el mundo. 

**Recuperación ante desastres**

Los datos se protegen con copias de seguridad, replicación de datos y distribución geográfica. En algunas ocasiones de forma opcional hay una oferta para la recuperación ante desastres porque los DC no están exentos ante una catástrofe.

![](https://static.platzi.com/media/user_upload/Que%20es%20la%20nube-8119376a-30ba-4cc3-bf3d-a4d7145892ec.jpg)

# Modelos de servicio: IaaS, PaaS, SaaS y serverless
 ## On-Premise (Local)
### Todo corre por tu cuente:

* Equipos
* Adecuación
* Mantenimiento
* Configuración
* Actualización
* IaaS

### Ventajas

Parecedo a on-premise ofreciendo mayor flexibilidad y control sobre el hardware:

* Sin CapEx
* Ágil
* Administración compartida
* Desventajas

Complicado al inicio según el grado de detalle que se requiere en aspectos de conocimiento y tiempo

# PaaS
## Ventajas

Entorno administrado por el proveedor: VMs, red, infraestructura.

* Solo te preocupas por el desarrollo.
* Configuración más ágil que IaaS.
* Enfocado al despliegue de aplicaciones.

## Desventajas

* Puede ser más caro que IaaS.
* Compatibilidad con algunos elementos.
* Dependencias con el proveedor.
* Riesgos de seguridad.
* Limitantes de idioma, interfaz o recursos.

# SaaS
## Ventajas

El proveedor administra el 100% del entorno y los usuarios solo utilizan la aplicación que se ejecuta en la nube:

* Office Online.
* Outlook.
* CRM.
* ERP.

## Desventajas

* Se necesita conexión a internet.
* Poco control.
* Baja personalización.
* Desempeño limitado.

# Serveless
Sí usa servidores.
El proveedor aprovisiona, escala y administra la infraestructura.
Ejecuta funciones o fracciones de código.
Es dirigida por eventos.

## Ventajas

* Altamente escalable.
* Enfocada a la lógica de negocio.
* Ahorro de tiempo.
* Desarrollo ágil.
* Pago por uso.

## Desventajas

* No están diseñada para procesos extensos.
* Detalles de desempeño.
* Retos de testing y debugging.

![](https://static.platzi.com/media/user_upload/modelos%20de%20servicios-632cf4ff-e4e1-4159-8172-b37fc95fbe88.jpg)



