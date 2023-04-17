<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 1
      h1 Introducción a los sistemas operativos de red

    .row.justify-content-center.align-items-center.mb-5
      .col-md-7(data-aos="fade-right")
        p.mb-4 Los sistemas operativos de red, son aquellos que están unidos a dos o más equipos, utilizando un medio de comunicación, con el objetivo de compartir recursos de #[em hardware] y #[em software]; entre los sistemas operativos de red más comunes tenemos a: LAN Manager, Novell Netware, Linux, UNIX, LANtastic, Windows Server, entre otros.
          br
          br
          |Una red de equipos no puede funcionar sin un sistema operativo de red, al igual que un equipo, sin un sistema operativo; a estos sistemas de red, también se les conoce como NOS; otra definición se refiere a que es un #[em software] que rige y administra recursos en una red y lleva el control de la seguridad de los mismos.
          br
          br
          |Un NOS maneja los servicios óptimos para que el usuario esté libre de error al conectarse a una red; este provee una interfaz de usuario que permite reducir la complejidad y dificultades al usar la red.
      .col-md-5.mb-sm-4(data-aos="fade-left")
        figure
          img(src='@/assets/curso/temas/tema1/img1-1.png', alt="Microchip")

      p.mb-5(data-aos="fade-right") La principal función de un sistema operativo de red es brindar una forma de transmisión de archivos de un equipo a otro, la Internet brinda un mecanismo para hacer transferencias a través del FTP (#[em File Transfer Protocol]).

      .row.justify-content-center.mb-5
        .col-lg-10(data-aos="flip-up")
          .cajon.color-acento-contenido.p-4
            p.mb-0 El primer sistema operativo de red estaba enfocado hacia equipos con un procesador motorola 6800; luego, aparecieron los procesadores intel como Novell Netware; el éxito de este #[em software] de red es que, a pesar que era arcaico, estaba dispuesto a relacionarse con otras tecnologías y también brindaba apoyo al protocolo de AppleTalk. (Cura, 2020)
      
      .row.justify-content-center.mb-5
        .col-lg-10(data-aos="zoom-in")
          .bloque-texto-g.color-secundario.p-3.p-sm-4.p-md-4
            .bloque-texto-g__img(
            :style="{'background-image': `url(${require('@/assets/curso/temas/tema1/img1-2.png')})`}"
            )
            .bloque-texto-g__texto.p-4
              p.mb-0 Para el año 2000, apareció la versión de Microsoft Windows Profesional, el que se adoptaría por su estabilidad y porque, por primera vez, se presentó también el Active Directory, la versión actual de Microsoft para estaciones de trabajo; el Windows Server 2022, lanzado en agosto del 2021, el cual aplica protección multicapa contra amenazas, con un servidor de núcleo seguro y ejecuta cargas de trabajo como SQL server, utilizando 48Tb de memoria, también usa Windows Admin Center, para mejorar la gestión de máquinas virtuales y conexión con Azure.


      p.mb-0(data-aos="fade-left") A continuación, se muestran las características técnicas en la familia de Windows:

    .row.justify-content-center.align-items-center.mb-5
      .col-lg-10.col-sm-9
        ImagenInfografica.color-primario(data-aos="zoom-in")
          template(v-slot:imagen)
            figure
              img(src='@/assets/curso/temas/tema1/img1-3.png', alt='Características técnicas de la familia Windows.')
              
          .tarjeta.color-secundario.p-3(x="12%" y="16%" numero="+")
            h4 Windows 3.11
            p •  Es de 16 Bit.
              br
              | • Fue diseñado y desarrollado para gestionar recursos en la #[em networking] basadas en Windows y Peer to peer.
              br
              | • No fue diseñado para soportar muchos usuarios.

          .tarjeta.color-secundario.p-3(x="88%" y="16%" numero="+")
            h4 Windows NT
            p •  Es un sistema operativo que provee máxima confiabilidad, rendimiento y seguridad.
              br
              |• Tiene mayores requerimientos de #[em hardware] frente a Windows 95.
              br
              | • Su interfaz gráfica es amigable, similar a la de Windows 95.

          .tarjeta.color-secundario.p-3(x="12%" y="62%" numero="+")
            h4 UNIX
            p Desarrollado en el lenguaje C, está disponible en varias versiones; entre ellas, una adaptada por IBM para el uso en estaciones de trabajo, UNIX permite múltiples tareas y múltiples usuarios, su sistema de archivo admite la organización fácil a los archivos y permite la protección de los mismos; para el año 1971, Ritchie y Kernigham desarrollan el lenguaje C en un PDP-11; luego, en 1973, Ritchie y Thompson desarrollan un sistema multiusuario, UNIX había nacido. (Lezcano, 2018)

          .tarjeta.color-secundario.p-3(x="88%" y="61%" numero="+")
            h4 LINUX
            p Dentro de las características principales de este sistema destaca la capacidad multitarea, que hace posible la ejecución de varios programas a la vez; también el sistema multiusuario en el que varios usuarios pueden acceder a las aplicaciones y recursos al mismo tiempo, Linux es flexible para poder conectarse a cualquier ordenador ya que internet creó dentro en entornos UNIX y es por eso que Linux tiene mayores capacidades para navegar.
      
    .row.justify-content-center.mb-5
      .col-lg-10(data-aos="flip-up")
        .cajon.color-acento-contenido.p-4
          p.mb-0 Puede decirse que tanto UNIX, como Linux son sistemas operativos idénticos. (Cura, 2020)

    Separador

    #t_1_1.titulo-segundo.color-acento-contenido(data-aos="fade-right")
      h2 1.1 Licenciamientos

    .row.justify-content-center.mb-5
      .col-lg-10
        .bloque-texto-a.color-secundario.p-4.p-md-3.fcac25
          .row.m-0.align-items-center.justify-content-between
            .col-lg-8(data-aos="zoom-in")
              .contenedor-dashed.p-3
                .bloque-texto-a__texto.p-4
                  p.mb-0  #[b Las licencias] 
                      | son básicamente, convenios o contratos en donde el usuario acepta las condiciones y términos de la empresa desarrolladora para hacer uso del 
                      em software, 
                      | los términos serán más o menos restrictivos, si es libre o propietario. Por tanto, las licencias son permisos para poder usar algún tipo de 
                      em software 
                      | y pueden tener limitación de tiempo y variar según la ubicación geográfica donde se utiliza.
                
            .col-lg-4.mb-lg-0.order-sm-first.order-lg-last.mb-sm-4(data-aos="fade-left")
              figure
                img(src='@/assets/curso/temas/tema1/img1-4.png', alt="Licencias")

    p.mb-5(data-aos="fade-right") Las licencias se pueden definir en varios tipos como:

    TabsA.color-primario.mb-5(data-aos="zoom-in")
      .tarjeta.tarjeta--border.color-adicional-1.p-4(titulo="Código abierto").borde
        .row.m-0.justify-content-center.align-items-center
          .col-xl-2.mb-5
            h4 
              span.text-white CA
            figure
              img(src='@/assets/curso/temas/tema1/img1-5.svg', alt='Caja abierta')
          .col-xl-8
            p Permiten que quien lo adquiera pueda modificar el código fuente y pueda distribuir libremente sin pagar derechos de autor, hoy en día existen muchos de estos 
              em software 
              | que derivan proyectos anteriores como es el caso de  UNIX.

      .tarjeta.color-adicional-1.p-4(titulo="<em>Software</em> libre").borde
        .row.m-0.justify-content-center.align-items-center
          .col-xl-2.mb-5
            h4 
              span.text-white SL
            figure
              img(src='@/assets/curso/temas/tema1/img1-6.svg', alt='Pantalla con la palabra API')
          .col-xl-6
            p Su código estará siempre disponible para usarlo, copiarlo y distribuirlo; es por esto que su código fuente está siempre a la mano, entendiendo que, el hecho de que un <em>software</em> sea libre no significa que este sea gratuito, se deje usar o copiar.

      .tarjeta.color-adicional-1.p-4(titulo="<em>Copyleft</em>").borde
        .row.m-0.justify-content-center.align-items-center
          .col-xl-2.mb-5
            h4
              span.text-white CL
            figure
              img(src='@/assets/curso/temas/tema1/img1-7.svg', alt='Certificado')
          .col-xl-6
            p Están protegidas por la legislación internacional de  Copyright; estas restringen las modificaciones o copias sin la autorización del autor. Sin embargo, estas licencias definen las condiciones en las que se puede hacer uso, copia, modificación y distribución del #[em software.]

      .tarjeta.color-adicional-1.p-4(titulo="GPL <em>General Public License</em>").borde
        .row.m-0.justify-content-center.align-items-center
          .col-xl-2.mb-5
            h4 
              span.text-white GPL
            figure
              img(src='@/assets/curso/temas/tema1/img1-8.svg', alt='Licencia GPL')
          .col-xl-6
            p Limita la distribución del #[em software] e impide que pueda ser integrado. Además, se basa en la legislación internacional de Copyright.

    .row.justify-content-center.align-items-center.mb-5
      .col-lg-10
        .bloque-texto-a.bloque-texto-t1.p-4.p-md-4(data-aos="zoom-in")
          .row.m-0.align-items-center.justify-content-between
            .col-lg-4.mb-4.mb-lg-0
              figure
                img(src='@/assets/curso/temas/tema1/img1-9.svg', alt='Persona revisando licencias')
            .col-lg-8
              .contenedor-dashed.p-4
                .bloque-texto-a__texto.p-4
                  p Un tema muy interesante es el referente a los licenciamientos de los servidores; desde Windows Server 2016, cambia la forma como se licencian los sistemas operativos en temas de servidores.

                  p.mt-3 El modelo de licenciamiento anterior era un servidor o CPU, que necesitaba de una licencia de Windows Server, a un nuevo modelo donde, por cada núcleo de la CPU se tiene una licencia Core de Windows Server; esto se debe a que las CPU actuales cuentan con varios núcleos o Cores, lo que se convierte en una CPU y también se puede encontrar CPU en forma de núcleos.

    .row.justify-content-center.mb-5
      .col-lg-10(data-aos="flip-up")
        .cajon.color-acento-contenido.p-4
          p.mb-0 En resumen, existen muchos tipos de licencias específicas y se clasifican según el tipo, el uso, el tiempo y el público a quien va dirigido.

    Separador

    #t_1_2.titulo-segundo.color-acento-contenido(data-aos="fade-right")
      h2 1.2 Conceptos básicos de redes y  networking

    .row.justify-content-center.align-items-center
      .col-md-7(data-aos="fade-right")
        p.mb-4 Una red de computadoras que se interconecta entre sí, se define como una red, utilizando dispositivos físicos que envían y reciben datos con el fin de compartir recursos, información y ofrecer múltiples servicios. El alcance de una red dependerá de su tamaño geográfico, porque puede variar desde pocos equipos en una empresa, hasta miles de estos, conectados a largas distancias; es por esto que las redes, según su extensión, se catalogan de la siguiente forma:
        .fcac25.p-4.mb-5(data-aos="flip-up")
          p.mb-0 #[b Red de área local:] esta red suele interconectar equipos y dispositivos cerca, como, por ejemplo, en una empresa o un hogar. Existen otras redes como la (WAN) que es una red de área extensa y conecta varios equipos que se encuentran a larga distancia; un ejemplo de esta sería dos LAN interconectadas a larga distancia. El Internet es un tipo de red WAN.
      .col-md-5.order-sm-first.order-lg-last.mb-sm-4(data-aos="fade-left")
        figure
          img(src='@/assets/curso/temas/tema1/img1-10.png', alt="Mundo conectado")

    .row.justify-content-center.align-items-center.mb-5
      .col-md-5.mb-sm-4(data-aos="fade-right")
        figure
        img(src='@/assets/curso/temas/tema1/img1-11.png', alt="Conexiones de red")
      .col-md-7(data-aos="fade-left")
        p.mb-4 Otro concepto que debe tenerse en cuenta es la Intranet, que es básicamente, una red interna con un alcance dentro de una organización o entidad, este tipo de red nos garantiza un mejor control de la seguridad, estabilidad y <em>performance</em> en la gestión de la información.

        p.mb-4 Entre los medios de conexión que permiten intercambiar datos se encuentra el cable de red, existe el cable de par trenzado que es el medio de transmisión más utilizado, el cual, está formado por dos hebras aisladas de hilo de cobre o aleación trenzado entre sí. Estos cables pueden transportar datos y señales a distancias de 100 metros y son llamados cables UTP, también es el cable en una LAN algo parecido se encuentra con los cables STP, que utilizan una funda de cobre trenzado, que es más protector de interferencias. El cableado par trenzado generalmente utiliza conectores RJ-45 (<em>Registered Jack</em>) para la conexión a un dispositivo.

        p.mb-0 Un cable muy común es el Coaxial que está formado en su interior por cobre, rodeado por un aislamiento y una capa de metal trenzado y es una buena opción cuando se transmiten señales a larga distancia. Este cable necesita tener terminaciones en cada extremo y su cobertura es aproximada a los 185 metros.

    .row.justify-content-center.align-items-center.mb-5
      .col-lg-10
        .bloque-texto-g.color-secundario.p-3.p-sm-4.p-md-4(data-aos="zoom-in")
          .bloque-texto-g__img(
            :style="{'background-image': `url(${require('@/assets/curso/temas/tema1/img1-12.png')})`}"
          )
          .bloque-texto-g__texto.p-4
            p.mb-0 Actualmente la mejor opción para transportar señales de datos es la fibra óptica, ya que lo hace mediante pulsos modulados de luz, como el cable no transporta impulsos eléctricos, la señal no se ve afectada por interferencias y lo hace más seguro, debido a que la pérdida de datos es nula. Sin embargo, un inconveniente de la fibra óptica, es que se puede llegar a romper fácilmente si la manipulación no se hace de forma adecuada, luego es más difícil de manipular y cortar, ya que requiere un equipo especial. #[br]
            p.mb-0 Ahora bien, existen las topologías en las redes, las cuales definen cómo se interconectan dispositivos para intercambiar datos lógica y físicamente, es decir cómo está diseñada la red.


    p.mb-5(data-aos="fade-right") Existen 5 topologías básicas, estas son:

    TabsC.color-acento-contenido.mb-5(data-aos="zoom-in")
      .py-3.py-md-4(titulo="Topología bus")
        .row.justify-content-center.align-items-center
          .col-md-5.mb-sm-4
            figure
              img(src='@/assets/curso/temas/tema1/img1-13.svg', alt="Conexiones tipo bus")
          .col-md-5.mb-4.mb-md-0
            p Se evidencia cuando los dispositivos están conectados a un cable; un ejemplo de esto serían dos equipos conectados entre sí, por un mismo cable; esta topología tiene una desventaja grande y es que si, en algún momento, el cable principal falla, la red también dejaría de funcionar.

      .py-3.py-md-4(titulo="Topología estrella")
        .row.justify-content-center.align-items-center
          .col-md-5.mb-sm-4
            figure
              img(src='@/assets/curso/temas/tema1/img1-14.svg', alt="Conexiones tipo estrella")
          .col-md-5.mb-4.mb-md-0
            p Es en donde los dispositivos están conectados a segmentos de cables que llegan hasta el concentrador, esta topología se encuentra en empresas y hogares normalmente, una ventaja de la topología estrella es que si uno de los dispositivos de la red falla, los demás dispositivos podrán funcionar normalmente, 

      .py-3.py-md-4(titulo="Topología malla")
        .row.justify-content-center.align-items-center
          .col-md-5.mb-sm-4
           figure
            img(src='@/assets/curso/temas/tema1/img1-15.svg', alt="Conexiones tipo malla")
          .col-md-5.mb-4.mb-md-0
            p Aquí los dispositivos de la red están conectados entre sí mediante un cable, esta topología brinda mayor estabilidad en la conexión y transferencia de datos, una de sus ventajas es que permite hacer respaldo de la información, ya que proporciona múltiples rutas, esta requiere más cable lo que hace su costo de instalación más elevado.

      .py-3.py-md-4(titulo="Topología anillo")
        .row.justify-content-center.align-items-center
          .col-md-5.mb-sm-4
           figure
            img(src='@/assets/curso/temas/tema1/img1-16.svg', alt="Conexiones tipo anillo")
          .col-md-5.mb-4.mb-md-0
            p Aquí los dispositivos están conectados a un cable en forma circular, alrededor de un concentrador central.

      .py-3.py-md-4(titulo="Topología híbrida")
        .row.justify-content-center.align-items-center
          .col-md-5.mb-sm-4
           figure
            img(src='@/assets/curso/temas/tema1/img1-17.svg', alt="Conexiones híbridas")
          .col-md-5.mb-4.mb-md-0
            p En ella se pueden utilizar una o más topologías fusionadas para brindar una mejor seguridad y estabilidad en la organización; es importante decir que, en esta topología, si un solo equipo falla, no afectará al resto de la red; generalmente se pueden hacer combinaciones entre la estrella-bus y estrella-anillo.

    h3.mb-4(data-aos="fade-right")
      i.fas.fa-square.cac.me-3
      | Modelo OSI

    .row.justify-content-center.align-items-center
      .col-md-7
        p.mb-4(data-aos="fade-right") Un puente de red, es un dispositivo de interconexión de redes; este opera en la capa 2 del modelo OSI y divide una red en segmentos. Por su parte, el #[em switch] es un dispositivo electrónico de interconexión de redes, que también opera en la capa de enlace de datos y este interconecta dos o más segmentos de red. Ahora bien, un #[em router] es un dispositivo electrónico que encamina e interconecta las redes de los equipos que operan en la capa 3.
      
        .fcac25.p-4.mb-5(data-aos="flip-up")
          p <b>¿Qué es TCP/IP?</b>
          p.mb-0 Se relaciona con un protocolo para el funcionamiento de la red de Internet; este funciona a nivel de transporte del modelo de referencia OSI y proporciona fiabilidad en los datos; el protocolo IP, se encuentra en el nivel de red OSI, que encamina los datos hacia otros equipos.
            br
            br
            |Estos protocolos se pueden descomponer en niveles de TCP/IP, usando siempre como referencia, el modelo OSI, el cual se descompone en cinco niveles, cuatro niveles de #[em software] y un nivel de #[em hardware.]
    
      .col-md-5.mb-sm-4(data-aos="fade-left")
        figure
          img(src='@/assets/curso/temas/tema1/img1-18.png', alt="Autopista de datos")

    p.mb-5(data-aos="fade-right") ¿Qué es un protocolo? Puede ser relativamente simple o complejo, y se refiere a un conjunto de reglas que permiten la conexión y comunicación entre dos o más entidades de un sistema.

    .row.justify-content-center.align-items-center.mb-5
      .col-md-1.col-sm-2(data-aos="fade-right")
        figure
          img(src='@/assets/curso/temas/tema1/img1-19.svg', alt="Monitor con la palabra OSI")
      .col-md-11.col-sm-10(data-aos="fade-left")
        p.mb-0 El modelo OSI, básicamente es un estándar para interconectar sistemas sin importar si estos son diferentes; este modelo está conformado por 7 capas, cada una de ellas tiene sus propias funciones y de esta manera, el conjunto alcanza su objetivo. A continuación, se detallan algunos de los protocolos en las respectivas capas de este modelo:
        
    .col-md-8.mx-auto.col-sm-9.mb-5(data-aos="zoom-in")
      ImagenInfografica.color-acento-contenido.mb-5
        template(v-slot:imagen)
          figure
            img(src='@/assets/curso/temas/tema1/img1-20.svg', alt="Capas del modelo OSI")

        .tarjeta.color-acento-contenido.p-3(x="30%" y="7%" numero="+")
          .h5.mb-2 Capa de aplicación
          p  •  HyperText Transfer Protocol #[span.fst-normal (HTTP)]
            br
            | •  File Transfer Protocol #[span.fst-normal (FTP)]
            br
            | •  Simple Mail Transfer Protocol #[span.fst-normal (SMTP)]
            br
            | •  Secure Shell #[span.fst-normal (SSH)]
            br
            | •  Simple Network Management Protocol #[span.fst-normal (SNMP)]
            br
            | •  Domain Name System #[span.fst-normal (DNS)]
            br
            span.fst-normal Estos protocolos se utilizan más cuando se ven videos o se envían mensajes en software de mensajería o correos electrónicos. 

        .tarjeta.color-acento-contenido.p-3(x="26%" y="21%" numero="+")
          h5 Capa de presentación
          p.mb-0 •  Apple Filing Protocol #[span.fst-normal (AFP)]
          p •  Network File System #[span.fst-normal (NFS)]
          p Traduce el formato en el que se quiere ver, un ejemplo sería cuando se descarga un archivo, la extensión de este será manejada por esta capa.

        .tarjeta.color-acento-contenido.p-3(x="22%" y="36%" numero="+")
          h5 Capa de sesión
          p •  Network Basic Input/Output System #[span.fst-normal (NetBIOS)]
            br
            |•  Internet Storage Name Service #[span.fst-normal (ISNS)]
            br
            |•  File Transfer Protocol #[span.fst-normal (FTP)]
            br
            |•  Session Annoucement Protocol #[span.fst-normal (SAP)]
            br
            span.fst-normal Lleva a cabo la comunicación, autoriza y gestiona el enlace entre los dispositivos.

        .tarjeta.color-acento-contenido.p-3(x="17%" y="50%" numero="+")
          h5 Capa de transporte de datos
          p •  User Datagram Protocol #[span.fst-normal (UDP)]
            br
            |•  Transmission Control Protocol #[span.fst-normal (TCP)]
            br
            span.fst-normal Hace la segmentación de lo que se va a compartir, fragmenta en varias partes, según la capacidad de la red.

        .tarjeta.color-acento-contenido.p-3(x="13%" y="65%" numero="+")
          h5 Capa de red
          p •  Interior Gateway Protocol #[span.fst-normal (IGP)]
            br
            |•  Internet Protocol #[span.fst-normal (IP)]
            br
            |•  Routing Information Protocol #[span.fst-normal (RIP)]
            br
            |•  Internetwork Packet Exchange / Sequence Packet Exchange #[span.fst-normal (IPX / SPX)]
            br
            span.fst-normal Calcula la mejor ruta para enviar los paquetes, se encarga de direccionar los datos transmitidos para que salgan y lleguen al destino.

        .tarjeta.color-acento-contenido.p-3(x="8%" y="80%" numero="+")
          h5 Capa de enlace de datos
          p •  Ethernet
            br
            |•  Fiber Distributed Data Interface #[span.fst-normal (FDDI)]
            br
            |•  Address Resolution Protocol #[span.fst-normal (ARP)]
            br
            |•  Point to Point Protocol #[span.fst-normal (PPP)]
            br
            span.fst-normal Obtiene la información y la traduce en binario, para enviarla a la capa física.

        .tarjeta.color-acento-contenido.p-3(x="4%" y="94%" numero="+")
          h5 Capa física
          p •  Digital Subscriber Line #[span.fst-normal (DLS)]
            br
            |•  Integrated Services Digital Network #[span.fst-normal (ISDN)]
            br
            |•  Bluetooth
            br
            |•  Universal Serial Bus #[span.fst-normal (USB)]
            br
            span.fst-normal Hace el envío en binario a los medios de la red. Se encarga de la conexión física de una red.

    h3.mb-4(data-aos="fade-right")
      i.fas.fa-square.cac.me-3
      | Protocolos de RED

    p.mb-5(data-aos="fade-right") Dentro de los protocolos de red más usados están:

    TabsC.color-acento-contenido.mb-5(data-aos="zoom-in")
      .py-3.py-md-4(titulo="DNS")
        .row.justify-content-center.align-items-center
          .col-md-5.mb-sm-4
           figure
            img(src='@/assets/curso/temas/tema1/img1-21.svg', alt="DNS")
          .col-md-5.mb-4.mb-md-0
            p Se encarga de transformar las direcciones IP a nombres.
      .py-3.py-md-4(titulo="DHCP")
        .row.justify-content-center.align-items-center
          .col-md-5.mb-sm-4
           figure
            img(src='@/assets/curso/temas/tema1/img1-22.svg', alt="DHCP")
          .col-md-5.mb-4.mb-md-0
            p Protocolo de configuración dinámica de 
              em host, 
              | permite que los dispositivos tengan una configuración de red de una manera automática, es más fácil de administrar.
      .py-3.py-md-4(titulo="HTTP")
        .row.justify-content-center.align-items-center
          .col-md-5.mb-sm-4
           figure
            img(src='@/assets/curso/temas/tema1/img1-23.svg', alt="HTTP")
          .col-md-5.mb-4.mb-md-0
            p Es de los protocolos más importantes, porque hace la transferencia de documentos de tipo “hipertexto”.

</template>

<script>
export default {
  name: 'Tema1',
  components: {},
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
