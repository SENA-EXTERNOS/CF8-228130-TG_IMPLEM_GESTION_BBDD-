<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 2
      h1 Instalación

    .row
      .col-md-12
        p En el siguiente video se puede observar el proceso de instalación de Windows server 2016, es importante prestar mucha atención a todos los procedimientos y explicaciones que se detallan en allí:

    figure.mb-5
    .video
      iframe(width="560" height="315" src="https://www.youtube.com/embed/2L91WMqw96A" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen)

    figure.mb-5
    .video.mb-5
      iframe(width="560" height="315" src="https://www.youtube.com/embed/2L91WMqw96A" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen)

    .row.justify-content-center.mb-5
      .col-lg-12

        figure.mb-5
          img(src='@/assets/curso/temas/tema2/img2-1.svg', alt="")

    .row.justify-content-center.align-items-center
      .col-md-7
        p #[b Deben aceptarse los términos de licencia y luego se visualiza una ventana que muestra dos opciones:]

        ol.lista-ol--cuadro
          li 
            .lista-ol--cuadro__vineta
              span.cp 1
            | Actualización, opción que no se puede seleccionar porque actualizaría a una versión ya existente. 
          li 
            .lista-ol--cuadro__vineta
              span.cp 2
            | La siguiente opción personalizada es la que se debe hacer para realizar nuevas instalaciones del sistema operativo, cuando se hace clic en personalizada, empezará el proceso de preparación del disco duro.

      .col.md-5
        figure.mb-5
          img(src='@/assets/curso/temas/tema2/img2-2.png', alt="")

    .row.justify-content-center.align-items-center.mb-5
      .col-md-6
        figure
          img(src='@/assets/curso/temas/tema2/img2-3.png', alt="")

      .col-md-6
        p A partir de la anterior imagen y se analizan los componentes para la preparación del disco duro:

        ol.lista-ol--cuadro
          li 
            .lista-ol--cuadro__vineta
              span.cp 1
            | Disco o discos duros para la instalación: en esta opción se seleccionan los discos que se tengan instalados en la máquina para su instalación.
          li 
            .lista-ol--cuadro__vineta
              span.cp 2
            | Actualizar: se utiliza para actualizar el contenido de la ventana, en caso de haber un cambio reciente.
          li 
            .lista-ol--cuadro__vineta
              span.cp 3
            | Cargar controlador: se utiliza cuando al hacer la instalación se detecta que el disco duro no es estándar y se requiere algún drive en específico para poder hacer la detección del disco duro.
          li
            .lista-ol--cuadro__vineta
              span.cp 4
            | Opciones de unidad: al seleccionar esta opción se visualizan las herramientas para realizar la instalación, como lo son el particionamiento y el formato.

    .row.justify-content-center.align-items-center
      .col-md-6
        figure
          img(src='@/assets/curso/temas/tema2/img2-4.png', alt="")

      .col-md-6
        p En la anterior imagen se puede ver, que la opción

        ol.lista-ol--cuadro
          li 
            .lista-ol--cuadro__vineta
              span.cp 1
            | Hace referencia a eliminar particiones primarias o extendidas en el disco duro, la opción
          li 
            .lista-ol--cuadro__vineta
              span.cp 2
            | Formatea las particiones al disco duro, la opción
          li 
            .lista-ol--cuadro__vineta
              span.cp 3
            | Crea particiones primarias o extendidas, la opción
          li
            .lista-ol--cuadro__vineta
              span.cp 4
            | Se utiliza para hacer redimensiones de particiones; esto es muy útil, ya que permite administrar la partición, sin perder información en esta.

    Separador

    #t_2_1.titulo-segundo.color-acento-contenido
      h2 2.1 Tipos de instalaciones de sistemas operativos

    p Dentro de los tipos de instalaciones se pueden encontrar los siguientes:

    .tarjeta--container.row.mb-5
      .col-md.tarjeta.color-secundario.p-5
        .row.justify-content-center.mb-4
          .col-6
            figure
              img(src='@/assets/curso/temas/tema2/img2-5.svg', alt='')
        
        h2.text-center Atendida
        p El usuario realiza el procedimiento paso a paso utilizando el software para la instalación del sistema operativo.

      .col-md.tarjeta.color-primario.p-5
        .row.justify-content-center.mb-4
          .col-6
            figure
              img(src='@/assets/curso/temas/tema2/img2-6.svg', alt='')
        
        h2.text-center Desatendida
        p En este tipo de instalación, se realiza la configuración anterior y luego el sistema operativo se instala automáticamente, sin necesidad de realizar algún paso a paso por parte del usuario.

    Separador

    #t_2_2.titulo-segundo.color-acento-contenido
      h2 2.2 Plan de instalación: dependencias, configuración y problemas de instalación

    p En este proceso se abarcan diferentes procedimientos como:

    h3
      i.fas.fa-square.cac.me-3
      | Creación de usuarios

    .row.justify-content-center.align-items-center
      .col-md-6
        p En la instalación se podrá establecer un usuario administrador o superusuario, se pueden dar diferentes alternativas en la seguridad de los equipos informáticos, para administrar el equipo siempre se propone un superusuario que tendrá todos los privilegios y derechos para instalar, modificar y eliminar información en la cuenta de usuario. También podrá crear nuevos usuarios con limitaciones o sin limitaciones.

        .cajon.color-secundario.p-4.mb-5
          p En el caso de Linux, el usuario “superusuario” se llama “root”, para el sistema operativo Windows se llama “administrador” según el idioma en que sea instalado el sistema operativo.

      .col-md-6
        .titulo-sexto.color-acento-contenido.mb-3
          h5 Figura 1. 
          br
          em Usuarios
        figure
          img(src='@/assets/curso/temas/tema2/img2-7.png', alt='')

    .row.justify-content-center.align-items-center.mb-5
      .col-md-1.col-sm-10
        figure
          img(src='@/assets/curso/temas/tema2/img2-8.svg', alt="")
      .col-md-11
        p.mb-0 Para crear un usuario en Windows server se debe iniciar sesión en el servidor como administrador, para abrir la configuración de Windows, se arrastra el mouse hasta la barra de búsqueda y se escribe la palabra Configuración, luego se debe hacer clic en Cuentas, después, se va a otros usuarios, haciendo  clic en Agregar otra persona a este equipo y desde la barra de navegación se hace clic en Usuarios.
        br
        p.mb-0 Se debe hacer clic en Acción y luego Usuario nuevo desde la barra de menú:

    .row.justify-content-center.mb-5
      .col-lg-6
        .titulo-sexto.color-acento-contenido.mb-3
          h5 Figura 2. 
          br
          em Nuevo usuario
        figure
          img(src='@/assets/curso/temas/tema2/img2-9.png', alt="")

    .row.justify-content-center.mb-5
      .col-lg-10
        .cajon.color-secundario.p-4.mb-4
          p Desde ahí, debe introducirse el nombre del usuario, nombres completos, descripción del usuario y la contraseña de la cuenta.

    h3
      i.fas.fa-square.cac.me-3
      | Configuración del servidor NTP Windows server 2016

    p Es de gran importancia tener la sincronización del tiempo, tanto para los equipos cliente, como para el servidor, ya que algún error en los tiempos puede afectar las tareas administrativas.

    .row.justify-content-center.align-items-center
      .col-md-4
        figure
          img(src='@/assets/curso/temas/tema2/img2-10.svg', alt="")
      .col-md-8
        p Estos procesos en 
          em Windows server 
          | 2016 son gestionados por un servicio llamado NTP, ¿Qué es el NTP? (
          em Network Time Protocol
          |) es de los más antiguos, su principal función es la sincronización de la hora de todos los dispositivos utilizando una misma red.
        p NTP se encarga de que todos los dispositivos conectados a un dominio tengan la misma hora que el controlador de dominio y de esta forma se tenga un control y gestión en las actividades de manera exacta. Este protocolo utiliza el puerto 123 UDP.
        p Este protocolo permite:
        ul.lista-ul.mb-5
          li 
            i.lista-ul__vineta
            | Autenticación de los usuarios en la red
          li 
            i.lista-ul__vineta
            | Compartir información en la red
          li 
            i.lista-ul__vineta
            | Gestión de correos electrónicos
          li 
            i.lista-ul__vineta
            | Actualizaciones y sincronización de los equipos

    h3
      i.fas.fa-square.cac.me-3
      | Configuración desde el 
      em PowerShell
    p Para la configuración desde el PowerShell, se realizan los siguientes pasos:

    .tarjeta.tarjeta--gris.p-4.mb-5
      LineaTiempoC.color-primario(text-small)
        .row(titulo="Paso 1")
          .col-md-6.mb-4.mb-md-0
            p Abrir PowerShell con permisos administrador y se ejecuta el comando w32tm /dumpreg /subkey:parameters de esta forma se pueden ver los servidores NTP que haya en la máquina, por defecto aparecerá time.windows.com.

          .col-md-6
            figure
              img(src='@/assets/curso/temas/tema2/img2-11.png', alt="")

        .row(titulo="Paso 2")
          .col-md-6.mb-4.mb-md-0
            p Luego para ejecutar el servidor NTP se ejecuta w32tm /config /syncfromflags:manual /manualpeerlist:»serverntp1 serverntp2″ /update con el siguiente comando se pueden poner los nombres y direcciones IP de los servidores NTP.

          .col-md-6
            figure
              img(src='@/assets/curso/temas/tema2/img2-12.png', alt="")

        .row(titulo="Paso 3")
          .col-md-6.mb-4.mb-md-0
            p Reiniciar el servicio W32time con los siguientes comandos Stop-Service w32time y luego iniciar con el comando Start-Service w32time.

          .col-md-6
            figure
              img(src='@/assets/curso/temas/tema2/img2-13.png', alt="")

        .row(titulo="Paso 4")
          .col-md-6.mb-4.mb-md-0
            p Para confirmar que el servidor NTP está funcionando, se pone el comando w32tm /dumpreg /subkey:parameters y así se puede visualizar la configuración que tiene el servidor.

          .col-md-6
            figure
              img(src='@/assets/curso/temas/tema2/img2-14.png', alt="")

    h3
      i.fas.fa-square.cac.me-3
      | Errores de instalación

    .row.justify-content-center.align-items-center
      .col-md-4
        figure
          img(src='@/assets/curso/temas/tema2/img2-15.svg', alt="")
      .col-md-8
        .cajon.color-acento-contenido.p-4.mb-5
          p Existen muchos errores a la hora de instalar un sistema operativo, entre los más comunes están los famosos bugs, que son errores de programación dentro de un software, lo que causa un exceso en el uso de los recursos, bloqueos de pantallas que no permiten abrir aplicaciones o servicios, esto se resuelve haciendo una reparación o reinstalación del sistema operativo.

        p Otro error que se presenta es con el 
          em hardware, 
          | evidenciado cuando hay errores de conexiones del equipo y algún dispositivo externo, es posible que los drivers no estén instalados correctamente o no sean del fabricante correcto. Existen también, los problemas de compatibilidad, estos se manifiestan cuando el equipo no es compatible con el dispositivo instalado, puede ser porque el dispositivo tiene un 
          em software 
          | que no es reconocido con el sistema operativo.

    p Por otra parte, se encuentran los conocidos errores en el registro, esta es una parte del sistema que permite personalizar el equipo, sino se hace uso correcto de esto generaría errores en el sistema operativo. Finalmente, existen los virus, estos están programados para generar conflictos en el 
      em software, 
      | desconfiguraciones en las aplicaciones, reinicios constantes y aleatorios. La mejor forma de proteger los equipos de ellos, será la instalación de un antivirus.           

</template>

<script>
import Separador from '../../node_modules/ecored-base-pkg/src/components/Separador.vue'
export default {
  name: 'Tema2',
  components: { Separador },
  data: () => ({
    // variables de vue
  }),
  mounted() {
    this.$nextTick(() => {
      this.$aosRefresh()
    })
  },
  updated() {
    this.$aosRefresh()
  },
}
</script>

<style lang="sass"></style>
