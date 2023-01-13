
<div align="center">
    <h1>Curso de Introducción a la Nube con Azure</h1>
    <img src="https://static.platzi.com/media/achievements/badge-introduccion-nube-azure-05c6de71-609b-4b00-971c-56a8d88915d2.png" width="">
    <img src="https://i.imgur.com/wL2G5A8.png" width="">
</div>

![](https://static.platzi.com/media/user_upload/1-27218f9e-d785-4b42-895e-7730e97184ec.jpg)

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


