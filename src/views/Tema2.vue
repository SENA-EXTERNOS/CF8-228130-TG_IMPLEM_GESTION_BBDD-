<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 2
      h1 Instalación

    .row
      .col-md-12.mb-5(data-aos="fade-left")
        p.mb-0 En el siguiente video se puede observar el proceso de instalación de Windows server 2016; es importante prestar mucha atención a todos los procedimientos y explicaciones que se detallan:

    figure.mb-5(data-aos="zoom-in")
      .video
        iframe(width="560" height="315" src="https://www.youtube.com/embed/7g2Eo4L9wgc" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen)
      
    .bloque-texto-a.color-secundario.p-4.p-md-5.mb-5.fcac25
      .row.m-0.align-items-center.justify-content-between
        .col-lg-8.bloque-texto-a__texto.p-4.borde-lineas(data-aos="zoom-in")
            p.mb-0 Existen dos formas para hacer la instalación del sistema operativo; la primera de ellas, se realiza utilizando una máquina virtual, y la segunda, haciendo la instalación desde cero en la máquina. Para poder instalar Windows Server hay que tener ya “booteada” la memoria USB, que estará lista para hacer la instalación. Luego, se procede a iniciar la máquina, ingresando al BIOS presionando la tecla F2, o alguna tecla diferente, dependiendo del modelo y la marca del equipo. Una vez ingresado al BIOS, se configura en el BOOT, el inicio primario por USB, para que al iniciar la máquina se reconozca como dispositivo primario la memoria USB para su arranque; luego, se reinicia la máquina con la USB conectada y se espera hasta que comience la instalación.
        .col-lg-4.mb-4.mb-lg-0.order-sm-first.order-lg-last.mb-sm-4(data-aos="fade-left")
          figure
            img(src='@/assets/curso/temas/tema2/img2-1.svg', alt="Windows Server")

    .row.justify-content-center.align-items-center
      .col-md-7.rectanguloid.p-4(data-aos="fade-right")
        p 
          b Deben aceptarse los términos de licencia y luego se visualiza una ventana que muestra dos opciones:
        ol.lista-ol--cuadro
          li 
            .lista-ol--cuadro__vineta
              span.cst 1
            | Actualización, opción que no se puede seleccionar porque actualizaría a una versión ya existente. 
          li 
            .lista-ol--cuadro__vineta
              span.cst 2
            | La siguiente opción personalizada es la que se debe hacer para realizar nuevas instalaciones del sistema operativo, cuando se hace clic en personalizada, empezará el proceso de preparación del disco duro.
      .col.md-5.mb-sm-5(data-aos="fade-left")
        figure
          img(src='@/assets/curso/temas/tema2/img2-2.png', alt="Tipo de instalación")

    .row.justify-content-center.align-items-center.mb-5
      .col-md-6(data-aos="fade-right")
        figure
          img(src='@/assets/curso/temas/tema2/img2-3.png', alt="¿Dónde instalar Windows?")
      .col-md-6.rectanguloid.p-4(data-aos="fade-left")
        p 
          b A partir de la anterior imagen y se analizan los componentes para la preparación del disco duro:
        ol.lista-ol--cuadro
          li 
            .lista-ol--cuadro__vineta
              span.cst 1
            | Disco o discos duros para la instalación: en esta opción, se seleccionan los discos que se tengan instalados en la máquina, para su instalación.

          li 
            .lista-ol--cuadro__vineta
              span.cst 2
            | Actualizar: se utiliza para actualizar el contenido de la ventana, en caso de haber un cambio reciente.
          li 
            .lista-ol--cuadro__vineta
              span.cst 3
            p.mb-0 Cargar controlador: se utiliza cuando al hacer la instalación, se detecta que el disco duro no es estándar y se requiere algún drive en específico, para poder hacer la detección del disco duro.
          li
            .lista-ol--cuadro__vineta
              span.cst 4
            | Opciones de unidad: al seleccionar esta opción se visualizan las herramientas para realizar la instalación, como lo son el particionamiento y el formato.

    .row.justify-content-center.align-items-center.mb-5
      .col-md-6(data-aos="fade-right")
        figure
          img(src='@/assets/curso/temas/tema2/img2-4.png', alt="Paso 3 de instalación")
      .col-md-6.rectanguloid.p-4(data-aos="fade-left")
        p 
          b En la anterior imagen se puede ver, que la opción
        ol.lista-ol--cuadro
          li 
            .lista-ol--cuadro__vineta
              span.cst 1
            | Hace referencia a eliminar particiones primarias o extendidas en el disco duro, la opción. 

          li 
            .lista-ol--cuadro__vineta
              span.cst 2
            | Formatea las particiones al disco duro, la opción. 

          li 
            .lista-ol--cuadro__vineta
              span.cst 3
            | Crea particiones primarias o extendidas, la opción.

          li
            .lista-ol--cuadro__vineta
              span.cst 4
            | Sutiliza para hacer redimensiones de particiones; esto es muy útil, ya que permite aministrar la partición, sin perder información en esta.


    p.mb-5 Dentro de los tipos de instalaciones se pueden encontrar los siguientes:

    .tarjeta--container.row.mb-5(data-aos="zoom-in")
      .col-md.tarjeta.color-secundario.p-5
        .row.justify-content-center.mb-4
          .col-6
            figure
              img(src='@/assets/curso/temas/tema2/img2-5.svg', alt='Instalación atendida')
        
        h2.text-center Atendida
        p El usuario realiza el procedimiento paso a paso utilizando el 
          em software 
          | para la instalación del sistema operativo.

      .col-md.tarjeta.color-primario.p-5
        .row.justify-content-center.mb-4
          .col-6
            figure
              img(src='@/assets/curso/temas/tema2/img2-6.svg', alt='Instalación desatendida')
        
        h2.text-center Desatendida
        p En este tipo de instalación, se realiza la configuración anterior y luego el sistema operativo se instala automáticamente, sin necesidad de realizar algún paso a paso por parte del usuario.

    Separador

    ul.lista-ul--color
      li
        i.fas.fa-square
        h3.mb-0 Plan de instalación: dependencias, configuración y problemas de instalación

    p.mb-5(data-aos="fade-right") En este proceso se abarcan diferentes procedimientos como:

    p.mb-4(data-aos="fade-right")
      i.fas.fa-check.cac.me-3
      | #[b Creación de usuarios]

    .row.justify-content-center.align-items-center.mb-5
      .col-md-6(data-aos="fade-right")
        .rcacid.p-4.mb-3
          p.mb-0 En la instalación se podrá establecer un usuario administrador o superusuario, se pueden dar diferentes alternativas en la seguridad de los equipos informáticos; para administrar el equipo, siempre se propone un superusuario quien tendrá todos los privilegios y derechos para instalar, modificar y eliminar información en la cuenta de usuario. También podrá crear nuevos usuarios con, o sin limitaciones.
        .cajon.color-secundario.cs.p-4.cs25.mb-4
          p.mb-0 En el caso de Linux, el usuario “superusuario” se llama “root”; para el sistema operativo Windows, se llama “administrador” según el idioma en que sea instalado el sistema operativo.
      .col-md-6(data-aos="fade-left")
        figure.borde-lineas
          img(src='@/assets/curso/temas/tema1/c1.png', alt='Usuarios')


    .row.justify-content-center.align-items-center.mb-5
      .col-md-1.col-sm-2(data-aos="fade-right")
        figure
          img(src='@/assets/curso/temas/tema2/img2-8.svg', alt="Monitor")
      .col-md-11.col-sm-10(data-aos="fade-left")
        p.mb-0 Para crear un usuario en Windows Server, se debe iniciar sesión en el servidor como administrador; para abrir la configuración de Windows, se arrastra el mouse hasta la barra de búsqueda y se escribe la palabra Configuración; luego se debe hacer clic en Cuentas, y luego se va a otros usuarios, haciendo clic en Agregar otra persona a este equipo y, desde la barra de navegación, se hace clic en Usuarios.

    .row.justify-content-center.mb-5
      .col-lg-6
        figure(data-aos="zoom-in")
          img(src='@/assets/curso/temas/tema2/img2-7.png', alt='Usuarios')
    p.mb-5(data-aos='fade-right') Se debe hacer clic en #[b Acción] y luego #[b Usuario] nuevo desde la barra de menú:
    .row.justify-content-center.mb-5
      .col-lg-6
        figure(data-aos="zoom-in")
          img(src='@/assets/curso/temas/tema2/img2-9.png', alt="Nuevo usuario")

    .row.justify-content-center.mb-5
      .col-lg-10(data-aos="flip-up")
        .cajon.color-secundario.p-4.cs25.mb-4
          p.mb-0 Desde ahí, debe introducirse el nombre del usuario, nombres completos, descripción del usuario y la contraseña de la cuenta.

    p.mb-4.fw-bold(data-aos="fade-right")
      i.fas.fa-check.me-3(style="color: #ffb30b")
      span Configuración del servidor NTP Windows Server 2016

    p.mb-5(data-aos="fade-left") Es de gran importancia tener la sincronización del tiempo, tanto para los equipos cliente, como para el servidor, porque algún error en los tiempos, puede afectar las tareas administrativas.

    .row.justify-content-center.align-items-center.mb-5
      .col-md-4.mb-sm-4(data-aos="fade-right")
        figure
          img(src='@/assets/curso/temas/tema2/img2-10.svg', alt="Imagen decorativa")
      .col-md-8(data-aos="fade-down")
        p Estos procesos en Windows Server 2016, son gestionados por un servicio llamado NTP. ¿Qué es el NTP? Network Time Protocol es de los más antiguos y su principal función es la sincronización de la hora de todos los dispositivos, utilizando una misma red.
          
        p.mb-0.rcacid.p-4 NTP se encarga que todos los dispositivos conectados a un dominio, tengan la misma hora que el controlador de dominio y de esta forma se tenga un control y gestión en las actividades, de una manera exacta. Este protocolo utiliza el puerto 123 UDP.
        p Este protocolo permite:
        ul.lista-ul
          li 
            i.lista-ul__vineta.cab
            | Autenticación de los usuarios en la red.
          li 
            i.lista-ul__vineta.cab
            | Compartir información en la red.
          li 
            i.lista-ul__vineta.cab
            | Gestión de correos electrónicos.
          li 
            i.lista-ul__vineta.cab
            | Actualizaciones y sincronización de los equipos.

    p.mb-4.fw-bold(data-aos="fade-right")
      i.fas.fa-check.cac.me-3(style="color: #ffb30b")
      span Configuración desde el PowerShell
    p.mb-5(data-aos="fade-right") Para la configuración desde el PowerShell, se realizan los siguientes pasos:

    .tarjeta.tarjeta--gris.p-4.mb-5
      LineaTiempoC.color-primario(text-small)
        .row(titulo="Paso 1")
          .col-md-6.mb-4.mb-md-0
            p Abrir PowerShell con permiso de administrador y se ejecuta el comando #[b w32tm /dumpreg /subkey:parameters;] de esta forma, se pueden ver los servidores NTP que se encuentren en la máquina y, por defecto, aparecerá #[b time.windows.com.]
          .col-md-6
            figure
              img(src='@/assets/curso/temas/tema2/img2-11.png', alt="Configuración con PowerShell, paso 1")

        .row(titulo="Paso 2")
          .col-md-6.mb-4.mb-md-0
            p Luego para ejecutar el servidor NTP se ejecuta "w32tm /config /syncfromflags:manual /manualpeerlist:»serverntp1 serverntp2″ /update" con el siguiente comando se pueden poner los nombres y direcciones IP de los servidores NTP.
          .col-md-6
            figure
              img(src='@/assets/curso/temas/tema2/img2-12.png', alt="Configuración con PowerShell, paso 2")

        .row(titulo="Paso 3")
          .col-md-6.mb-4.mb-md-0
            p Reiniciar el servicio "W32time" con los siguientes comandos "Stop-Service w32time" y luego iniciar con el comando "Start-Service w32time".
          .col-md-6
            figure
              img(src='@/assets/curso/temas/tema2/img2-13.png', alt="Configuración con PowerShell, paso 3")

        .row(titulo="Paso 4")
          .col-md-6.mb-4.mb-md-0
            p Para confirmar que el servidor NTP está funcionando, se pone el comando "w32tm /dumpreg /subkey:parameters" y así se puede visualizar la configuración que tiene el servidor.
          .col-md-6
            figure
              img(src='@/assets/curso/temas/tema2/img2-14.png', alt="Configuración con PowerShell, paso 4")

    p.mb-4(data-aos="fade-right")
      i.fas.fa-check.cac.me-3
      | Errores de instalación

    .row.justify-content-center.align-items-center
      .col-md-4.mb-sm-4(data-aos="fade-right")
        figure
          img(src='@/assets/curso/temas/tema2/img2-15.svg', alt="Señal de error")
      .col-md-8
        .cajon.color-acento-contenido.p-4.mb-5(data-aos="flip-up")
          p.mb-0 Se pueden dar bastantes errores a la hora de instalar un sistema operativo; entre los más comunes están los famosos bugs, que son errores de programación dentro de un #[em software], lo que causa un exceso en el uso de los recursos, bloqueos de pantallas, que no permiten abrir aplicaciones o servicios; esto se resuelve haciendo una reparación o reinstalación del sistema operativo.

        p(data-aos="fade-left") Otro error que se presenta es con el #[em hardware], evidenciado cuando hay errores de conexiones del equipo y algún dispositivo externo; es posible que los drivers no estén instalados apropiadamente o no sean del fabricante correcto. Existen también, los problemas de compatibilidad, los cuales se manifiestan cuando el equipo no es compatible con el dispositivo instalado y puede ser porque el dispositivo tiene un #[em software] que no es reconocido por el sistema operativo.

    p.mb-5.rcacid.p-4(data-aos="fade-down") Por otra parte, se encuentran errores en el registro; esta es una parte del sistema que permite personalizar al equipo y si no se realiza un uso correcto, se generan errores en el sistema operativo. Finalmente, existen los virus, los cuales están programados para generar conflictos en el #[em software], desconfiguraciones en las aplicaciones, reinicios constantes y aleatorios. La mejor forma de proteger los equipos de ellos, es la instalación de un antivirus.
    .row.justify-content-center.mb-5
      .col-lg-8
        .cajon.color-acento-botones.p-4.mb-4
          p.mb-0 Recuerde explorar los demás recursos que se encuentran disponibles en este componente formativo; para ello, diríjase al menú principal, donde encontrará la síntesis, una actividad didáctica para reforzar los conceptos estudiados, material complementario, entre otros.

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
