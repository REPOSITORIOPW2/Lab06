<div align="center">
<table>
    <theader>
        <tr>
            <td><img src="https://github.com/rescobedoq/pw2/blob/main/epis.png?raw=true" alt="EPIS" style="width:50%; height:auto"/></td>
            <th>
                <span style="font-weight:bold;">UNIVERSIDAD NACIONAL DE SAN AGUSTIN</span><br />
                <span style="font-weight:bold;">FACULTAD DE INGENIERÍA DE PRODUCCIÓN Y SERVICIOS</span><br />
                <span style="font-weight:bold;">ESCUELA PROFESIONAL DE INGENIERÍA DE SISTEMAS</span>
            </th>
            <td><img src="https://github.com/rescobedoq/pw2/blob/main/abet.png?raw=true" alt="ABET" style="width:50%; height:auto"/></td>
        </tr>
    </theader>
    <tbody>
        <tr><td colspan="3"><span style="font-weight:bold;">Formato</span>: Guía de Práctica de Laboratorio / Talleres / Centros de Simulación</td></tr>
        <tr><td><span style="font-weight:bold;">Aprobación</span>:  2022/03/01</td><td><span style="font-weight:bold;">Código</span>: GUIA-PRLD-001</td><td><span style="font-weight:bold;">Página</span>: 1</td></tr>
    </tbody>
</table>
</div>

<div align="center">
<span style="font-weight:bold;">INFORME DE LABORATORIO</span><br />
<span>(formato estudiante)</span>
</div>


<table>
<theader>
<tr><th colspan="6">INFORMACIÓN BÁSICA</th></tr>
</theader>
<tbody>
<tr><td>ASIGNATURA:</td><td colspan="5">Programación Web 2</td></tr>
<tr><td>TÍTULO DE LA PRÁCTICA:</td><td colspan="5">Docker</td></tr>
<tr>
<td>NÚMERO DE PRÁCTICA:</td><td>06</td><td>AÑO LECTIVO:</td><td>2022 A</td><td>NRO. SEMESTRE:</td><td>III</td>
</tr>
<tr>
<td>FECHA DE PRESENTACION:</td><td>19-Jun-2022</td><td>HORA DE PRESENTACION:</td><td colspan="3">21:00</td>
</tr>
<tr><td colspan="3">Integrantes:
<ul>
<li>Kevin Pedro Yare Chulunquia</li>
<li>Joel Erick Gutierrez Puma</li>
<li>Joaquín Gonzalo Paredes Mescco</li>
</ul>
</td>
<td>NOTA:</td><td colspan="2"></td>
</tr>
<tr><td colspan="6">DOCENTES:
<ul>
<li>Richart Smith Escobedo Quispe (rescobedoq@unsa.edu.pe)</li>
</ul>
</td>
</<tr>
</tdbody>
</table>


# Solución y resultados

## I.		SOLUCIÓN DE EJERCICIOS/PROBLEMAS

Especifique paso a paso e incluya el código fuente referenciado en README.md.

1.  Realice los cambios necesarios para que la imagen que ud creo a partir de un contenedor personalizado se pueda acceder al servidor web desde el equipo anfitríon.
    ```sh
    docker run -p 8088:80 mydocker22
    ```
2.  Crear dos contenedores que puedan comunicarse: ping ?.?.?.?

3.  Investigar acerca de la ejecución de programas con interfaz gráfica dentro de contenedores Docker.

4.  Desplegar los siguientes ejercicios en contenedores docker:
    -   JavaScript: Escribir un página que reciba el URL de la sesión de google meet de hoy y devuelva el código de la sesión sin guiones separadores.
    -   NodeJS: Aplicación web que navegue sobre archivos Markdown.
    -   Python: Dibujar un tablero de Ajedrez.
    -   Django: Blog sencillo. 

#
    
## II.	SOLUCIÓN DE CUESTIONARIO

- ¿Qué son los "cgroups" del kernel de Linux? y ¿Qué diferencia más interesante encontró entre las versiones 1 y 2?
- ¿Qué son los "namespaces" del kernel de Linux? y ¿Cuáles son los tipos de "namespaces"?
- ¿Qué diferencia puede resaltar entre LXC y libcontainer?
- Investigue acerca del malware Doki y explique brevemente.
- ¿Hasta que punto la empresa RedHat se ha comprometido con el proyecto Docker?

#

## III.	CONCLUSIONES

- En conclusión, 
- 

## REFERENCIAS Y BIBLIOGRÁFIA RECOMENDADAS
-   Sitio oficial del Proyecto Docker: https://www.docker.com/
-   Proyecto Moby: https://github.com/moby/moby
-   Diapositivas "Contenedores de Linux y la nube del futuro" por Rami Rosen: http://www.haifux.org/lectures/320/netLec8_final.pdf
-   Docker para un proyecto Joomla-MySQL: https://dondocker.com/orquestando-contenedores-docker-para-tener-un-joomla-y-un-mysql-en-diferentes-hosts/
-   Tutorial de Docker en Youtube: https://www.youtube.com/watch?v=VeiUjkiqo9E#t=60
-   Cómo instalar y usar Docker en Ubuntu 20.04: https://www.digitalocean.com/community/tutorials/how-to-install-and-use-docker-on-ubuntu-20-04-es
