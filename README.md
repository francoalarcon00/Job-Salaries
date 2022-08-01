
<p>El primer objetivo de este jupyter notebook es visualizar puestos de trabajo en el ámbito de datos y el nivel de experiencia. Para ello, se crearon histogramas, gráfico de barras y boxplots (para todos ellos tanto numéricos como categóricos). Se ha logrado un ambiente más organizado al agrupar datos y obtener información relevante para el análisis.

El segundo objetivo es enfatizar los fundamentos estadísticos para analizar, agrupar y determinar que datos se necesitan y que representan estos como tal.</p>

<h1>Dataset</h1>

<li>work_year - Año de trabajo.</li>
<br>
<li>experience_level - Nivel de experiencia</li>
    EN =  Junior <br>
    MI = Midlevel <br>
    SE = Senior <br>
    EX = Director <br>

<br>

<li>employment_type - Tipo de empleo</li>

PT = Part-time<br>
FT = Full-time<br>
CT = Contrato<br>
FL = Freelance<br>

<br>

<li>job_title - Titulo profesional.</li>
<br>
<li>salary - El monto total del salario bruto pagado.</li>
<br>
<li>salary_currency - La moneda del salario pagado.</li>
<br>
<li>salary_in_usd - El salario en USD (tasa de cambio dividida por la tasa promedio de USD para el año respectivo a través de fxdata.foorilla.com).</li>
<br>
<li>employee_residence - El país de residencia principal del empleado</li>
<br>
<li>remote_ratio - La cantidad total de trabajo realizado de forma remota</li>
0 = No remoto (menos que el  20%)<br>
50 = Parcialmente remoto<br>
100 = Remoto (mas que el 80%)<br>
<br>
<li>company_location - El país de la oficina principal del empleador o de la sucursal contratante.</li>

<li>company_size - El número promedio de personas que trabajaban para la empresa</li>
S = menos que 50 empleados (small)<br>
M = 50 to 250 empleados (medium)<br>
L = mas que 250 empleados (large)<br>
