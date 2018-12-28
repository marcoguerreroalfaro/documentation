Despliegues Continuos
=====================

Diagrama Flujo de Integración
-----------------------------

Soluciones .NET

.. figure:: ../_static/images/cdeployment1.png
  :align: center
  :figwidth: 500px
  :target: ../_static/images/cdeployment1.png
  
  
Soluciones PHP

.. figure:: ../_static/images/cdeployment2.png
  :align: center
  :figwidth: 500px
  :target: ../_static/images/cdeployment2.png
    
Soluciones .NET (Ansible)

.. figure:: ../_static/images/cdeployment3.png
  :align: center
  :figwidth: 500px
  :target: ../_static/images/cdeployment3.png    
  
  
  
Como Configurar CodeDeploy
--------------------------

Para desplegar utilizando CodeDeploy necesitamos que las instancias cuenten con los roles correctos.

Requerimientos para proyecto:

* Instancia EC2 basada AMI
* Bucket S3 (Proyectos .Net )
* Rol para CodeDeploy
* Rol para instancia 

Rol para CodeDeploy: 
Ref. `Rol CodeDeploy <http://docs.aws.amazon.com/codedeploy/latest/userguide/how-to-create-service-role.html#how-to-create-service-role-console>`__
