

![consulta1](consulta1.png  "consulta1")

![consulta2](consulta2.png  "consulta2")

![consulta5](consulta5.png  "consulta5")

![consulta6](consulta6.png  "consulta6")

![consulta7](consulta7.png  "consulta7")

![consulta8](consulta8.png  "consulta8")

![consulta9](consulta9.png  "consulta9")

![consulta10](consulta10.png  "consulta10")



![consulta11](consulta11.png  "consulta11")

SELECT Empleado.nombre_empleado, Empleado.apellidos_empleado FROM Empleado 
JOIN Departamento ON Empleado.id_departamento = Departamento.id_departamento WHERE 
Departamento.presupuesto_departamento > 100000000;