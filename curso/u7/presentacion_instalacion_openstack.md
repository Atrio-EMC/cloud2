---
layout: presentacion
title: Introducción a la implantación de Openstack
tema: white
---
<section>
  <h1>Introducción a la implantación de OpenStack</h1>
  <p>
    <small><a href="http://albertomolina.wordpress.com">Alberto Molina
	Coballes</a> / <a
			  href="http://twitter.com/alberto_molina">@alberto_molina</a> y <a
											    href="http://josedomingo.org">José Domingo Muñoz
	Rodríguez</a> / <a
			   href="http://twitter.com/Pledin_JD">@Pledin_JD</a> </small>
  </p>
  <p><small>
      <a href="http://creativecommons.org/licenses/by-sa/3.0/"><img src="../../img/cc_by_sa.png"
								    width="100px" border="0"/></a></small></p>
  <p><small>
      Theme
      by <a href="http://lab.hakim.se/reveal-js/#/">reveal.js</a>
    </small>
  </p>
</section>
<section>
  <h2>Por dónde empezar...</h2>
  <ul>
    <li>Si hemos decidio la implantación de un cloud privado IaaS con OpenStack tenemos que decidir cómo vamos a realizar la instalación y configuración del mismo.</li>
    <li>Tenemos la posibilidad de instalar un entorno de prueba (no para su explotación) en un equipo para tener una primera experiencia de cómo funciona OpenStack</li>
    <li>La administración y gestión de Openstack es un proceso "complejo".
  </ul>
</section>

<section>
  <h2>Instalación manual</h2>
  <ul>
    <li>Elegir una distribución Linux que incluya en sus repositorios los páquetes de OpenStack:</li>
      <ul>
        <li>Debian, Ubuntu, openSUSE, Red Hat, Centos, Fedora</li>
      </ul>
    <li>Realiza una instalación manual siguiendo la <a href="http://docs.openstack.org/">documentación oficial</a></li>
  </ul>
</section>

<section>
  <h2>Instalación automática</h2>
  <ul>
    <li>Existen recetas elaboradas con las herramientas de automatización de la configuración más populares:</li>
      <ul>
        <li><a href="http://docs.opscode.com/openstack.html">Chef</a> - <a href="https://github.com/stackforge/openstack-chef-repo">Repositorio GitHub</a></li>
        <li><a href="http://github.com/puppetlabs/puppetlabs-openstack">Puppet</a> - Ejemplo: <a href="https://www.rdoproject.org/Main_Page">RDO</a> </li>
        <li>Ansible: Hay muchas recetas desarrolladas. Por ejemplo la nuestra: <a href="https://github.com/iesgn/openstack-debian-ansible">https://github.com/iesgn/openstack-debian-ansible</a></li>
      </ul>
    <li></li>
  </ul>
</section>
