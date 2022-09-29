<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 1
      h1 Introducción a los sistemas operativos de red

    .row.justify-content-center.align-items-center
      .col-md-7
        p.mb-4 Son aquellos sistemas que están unidos a dos o más equipos utilizando un medio de comunicación, con el objetivo de compartir recursos de hardware y software; entre los sistemas operativos de red más comunes están: #[ em LAN Manager, Novell Netware, Linux, UNIX, LanTastic, Windows Server,] etc.
          
        p.mb-4 Una red de equipos no pude funcionar sin un sistema operativo de red, al igual que un equipo sin un sistema operativo, a estos sistemas de red también se les conoce como NOS; otra definición es que es un software que rige y administra recursos en una red y lleva el control de seguridad de los mismos.
          
        p Un NOS maneja los servicios óptimos para que el usuario esté libre de error al conectarse a una red, este provee una interfaz de usuario que permite reducir la complejidad y dificultades al usar la red.
      .col-md-5
        figure
          img(src='@/assets/curso/temas/tema1/img1-1.png', alt="")

      p.mb-5 La principal función de un sistema operativo de red es brindar una forma de transmisión de archivos de un equipo a otro, la internet brinda un mecanismo para hacer transferencias a través del FTP (#[em File Transfer Protocol]).

      .row.justify-content-center.mb-5
        .col-lg-9
          .cajon.color-acento-contenido.p-4
            p El primer sistema operativo de red estaba enfocado a equipos con un procesador motorola 6800, luego aparecieron los procesadores intel como Novell Netware; el éxito de este #[em software] de red es que a pesar de que era arcaico, estaba dispuesto a relacionarse con otras tecnologías, también brindaba apoyo al protocolo de #[em AppleTalk]. (Cura, 2020).
      
      .row.justify-content-center.mb-5
        .col-lg-9

          .bloque-texto-g.color-secundario.p-3.p-sm-4.p-md-5
            .bloque-texto-g__img(
            :style="{'background-image': `url(${require('@/assets/curso/temas/tema1/img1-2.png')})`}"
            )
            .bloque-texto-g__texto.p-4
              p.mb-0 Para el año 2000, apareció la versión de #[em Microsoft Windows] 200 profesional el que se adoptaría por su estabilidad y por primera vez presentó también el #[em ActiveDirectory], la versión actual de #[em Microsoft] para estaciones de trabajo, el #[em Windows Server] 2022, lanzado en agosto del 2021, el cual aplica protección multicapa contra amenazas con un servidor de núcleo seguro y ejecuta cargas de trabajo como SQL server utilizando 48Tb de memoria, también usa #[em Windows] admin center para mejorar la gestión de máquinas virtuales y conexión a #[em Azure].

      p.mb-4 Se presentan las características técnicas en la familia Windows.

      p A continuación, se muestran las características técnicas en la familia de Windows:

    ImagenInfografica.color-primario
      template(v-slot:imagen)
        figure
          img(src='@/assets/curso/temas/tema1/img1-3.png', alt='')
          
      .tarjeta.color-secundario.p-3(x="10%" y="13%" numero="+")
        .h5.mb-2 Windows 3.11
        p •Es de 16 Bit #[br]
        p •Fue diseñado y desarrollado para gestionar recursos en la networking basadas en Windows y peer to peer.#[br]
        p •No fue diseñado para soportar muchos usuarios.

      .tarjeta.color-secundario.p-3(x="90%" y="13%" numero="+")
        .h5.mb-2 Windows NT
        p •Es un sistema operativo que provee máxima confiabilidad, rendimiento y seguridad.#[br]
        p •Tiene mayores requerimientos de hardware frente a Windows 95.#[br]
        p •Su interfaz gráfica es amigable similar a la de Windows 95.

      .tarjeta.color-secundario.p-3(x="10%" y="60%" numero="+")
        .h5.mb-2 UNIX
        p Desarrollado en el lenguaje C, está disponible en varias versiones, entre ellas, una adaptada por IBM para el uso en estaciones de trabajo, UNIX permite múltiples tareas y múltiples usuarios, su sistema de archivo admite la organización fácil a los archivos y permite la protección de los mismos, para el año 71 Ritchie y kernigham desarrollan el lenguaje C en un PDP-11, luego en 1973, Ritchie y Thompson desarrollan un sistema multiusuario, UNIX había nacido. (Lezcano, 2018)

      .tarjeta.color-secundario.p-3(x="90%" y="60%" numero="+")
        .h5.mb-2 LINUX
        p Dentro de las características principales de este sistema destaca la capacidad multitarea, que hace posible la ejecución de varios programas a la vez; también el sistema multiusuario en el que varios usuarios pueden acceder a las aplicaciones y recursos al mismo tiempo, Linux es flexible para poder conectarse a cualquier ordenador ya que internet creó dentro en entornos Unix y es por eso que Linux tiene mayores capacidades para navegar.
      
    .row.justify-content-center.mb-5
      .col-lg-8  
        .cajon.color-acento-contenido.p-4.mb-5
          p Puede decirse que tanto Unix, como Linux son sistemas operativos idénticos (Cura, 2020).

    Separador

    #t_1_1.titulo-segundo.color-acento-contenido
      h2 1.1 Licenciamientos

    .row.justify-content-center.mb-5
      .col-lg-10(data-aos="flip-left")

        figure.mb-5
          img(src='@/assets/curso/temas/tema1/img1-4.svg', alt="")

    TabsA.color-primario
      .tarjeta.color-adicional-1.p-4(titulo="Código abierto")
        h4 Código abierto
        .row
          .col-xl-6.mb-5
            figure
              img(src='@/assets/curso/temas/tema1/img1-5.svg', alt='')
          .col-xl-6
            p Permiten que quien lo adquiera pueda modificar el código fuente y pueda distribuir libremente sin pagar derechos de autor, hoy en día existen muchos de estos softwares que derivan proyectos anteriores como es el caso de Unix.

      .tarjeta.color-adicional-1.p-4(titulo="<em>Software</em> libre")
        h4 <em>Software</em> libre
        .row
          .col-xl-6.mb-5
            figure
              img(src='@/assets/curso/temas/tema1/img1-6.svg', alt='')
          .col-xl-6
            p Su código estará siempre disponible para usarlo, copiarlo y distribuirlo; es por esto que su código fuente está siempre a la mano, entendiendo que, el hecho de que un <em>software</em> sea libre no significa que este sea gratuito, se deje usar o copiar.

      .tarjeta.color-adicional-1.p-4(titulo="<em>Copyleft</em>")
        h4 <em>Copyleft</em>
        .row
          .col-xl-6.mb-5
            figure
              img(src='@/assets/curso/temas/tema1/img1-7.svg', alt='')
          .col-xl-6
            p Están protegidas por la legislación internacional de <em>Copyright</em>, estas restringen las modificaciones o copias sin la autorización del autor. Sin embargo, estas licencias definen las condiciones en las que se puede hacer uso, copia, modificación y distribución del <em>software</em>.

      .tarjeta.color-adicional-1.p-4(titulo="GPL <em>General Public License</em>")
        h4 GPL <em>General Public License</em>
        .row
          .col-xl-6.mb-5
            figure
              img(src='@/assets/curso/temas/tema1/img1-8.svg', alt='')
          .col-xl-6
            p Limita la distribución del <em>software</em> e impide que pueda ser integrado. Además, se basa en la legislación internación de <em>Copyright</em>.

    .row.justify-content-center.mb-5
      .col-lg-10

        figure.mb-5
          img(src='@/assets/curso/temas/tema1/img1-9.svg', alt="")

    .row.justify-content-center.mb-5
      .col-lg-8  
        .cajon.color-acento-contenido.p-4.mb-5
          p En resumen, existen muchos tipos de licencias específicas y se clasifican según el tipo, el uso, el tiempo y el público a quien va dirigido.

    Separador

    .titulo-segundo.color-acento-contenido
      h2 1.2 Conceptos básicos de redes y <em>networking</em>

    .row.justify-content-center.align-items-center
      .col-md-7
        p.mb-4 Una red de computadoras que se interconectan entre sí, se define como una red, utilizando dispositivos físicos que envían y reciben datos con el fin de compartir recursos, información y ofrecer múltiples servicios. El alcance de una red dependerá de su tamaño geográfico, ya que puede variar desde pocos equipos en una empresa hasta miles de estos conectados a largas distancias, es por esto que las redes se catalogan según su extensión de la siguiente forma:

        p.mb-5 <b>Red de área local:</b> esta red suele interconectar equipos y dispositivos cerca, por ejemplo, en una empresa o un hogar. Existen otras redes como la (WAN) que es una red de área extensa y conecta varios equipos que se encuentran a largas distancias, un ejemplo de esta sería dos LAN interconectadas a largas distancias. El internet es un tipo de red WAN (Tanenbaum et al, 2012).
        
      .col-md-5
        figure.mb-5
          img(src='@/assets/curso/temas/tema1/img1-10.png', alt="")

    .row.justify-content-center.align-items-center
      .col-md-5
        figure
        img(src='@/assets/curso/temas/tema1/img1-11.png', alt="")

      .col-md-7
        p.mb-4 Otro concepto que debe tenerse en cuenta es la Intranet, que es básicamente, una red interna con un alcance dentro de una organización o entidad, este tipo de red nos garantiza un mejor control de la seguridad, estabilidad y <em>performance</em> en la gestión de la información.

        p.mb-4 Entre los medios de conexión que permiten intercambiar datos se encuentra el cable de red, existe el cable de par trenzado que es el medio de transmisión más utilizado, el cual, está formado por dos hebras aisladas de hilo de cobre o aleación trenzado entre sí. Estos cables pueden transportar datos y señales a distancias de 100 metros y son llamados cables UTP, también es el cable en una LAN algo parecido se encuentra con los cables STP, que utilizan una funda de cobre trenzado, que es más protector de interferencias. El cableado par trenzado generalmente utiliza conectores RJ-45 (<em>Registered Jack</em>) para la conexión a un dispositivo.

        p.mb-5 Un cable muy común es el Coaxial que está formado en su interior por cobre, rodeado por un aislamiento y una capa de metal trenzado y es una buena opción cuando se transmiten señales a larga distancia. Este cable necesita tener terminaciones en cada extremo y su cobertura es aproximada a los 185 metros.

    .bloque-texto-g.color-secundario.p-3.p-sm-4.p-md-5.mb-5
      .bloque-texto-g__img(
        :style="{'background-image': `url(${require('@/assets/curso/temas/tema1/img1-12.png')})`}"
      )
      .bloque-texto-g__texto.p-4
        p.mb-0 Actualmente la mejor opción para transportar señales de datos es la fibra óptica, ya que lo hace mediante pulsos modulados de luz, como el cable no transporta impulsos eléctricos, la señal no se ve afectada por interferencias y lo hace más seguro, debido a que la pérdida de datos es nula. Sin embargo, un inconveniente de la fibra óptica, es que se puede llegar a romper fácilmente si la manipulación no se hace de forma adecuada, luego es más difícil de manipular y cortar, ya que requiere un equipo especial. #[br]
        p Ahora bien, existen las topologías en las redes, las cuales definen cómo se interconectan dispositivos para intercambiar datos lógica y físicamente, es decir cómo está diseñada la red.

    h3.titulo-tercero Topologías básicas de redes

    p Existen 5 topologías básicas, estas son:

    TabsC.color-acento-contenido.mb-5
      .py-3.py-md-4(titulo="Topología bus")
        .row.justify-content-center.align-items-center
          .col-md-5
           figure
            img(src='@/assets/curso/temas/tema1/img1-13.svg', alt="")
          .col-md-5.mb-4.mb-md-0
            h4 Topología bus
            p Se evidencia cuando los dispositivos están conectados a un cable, un ejemplo de esto sería dos equipos conectados entre sí por un mismo cable, esta topología tiene una desventaja grande y es que si en algún momento el cable principal falla, la red también dejaría de funcionar.

      .py-3.py-md-4(titulo="Topología estrella")
        .row.justify-content-center.align-items-center
          .col-md-5
           figure
            img(src='@/assets/curso/temas/tema1/img1-14.svg', alt="")
          .col-md-5.mb-4.mb-md-0
            h4 Topología estrella
            p Es en donde los dispositivos están conectados a segmentos de cables que llegan hasta el concentrador, esta topología se encuentra en empresas y hogares normalmente, una ventaja de la topología estrella es que si uno de los dispositivos de la red falla, los demás dispositivos podrán funcionar normalmente.

      .py-3.py-md-4(titulo="Topología malla")
        .row.justify-content-center.align-items-center
          .col-md-5
           figure
            img(src='@/assets/curso/temas/tema1/img1-15.svg', alt="")
          .col-md-5.mb-4.mb-md-0
            h4 Topología malla
            p Aquí los dispositivos de la red están conectados entre sí mediante un cable, esta topología brinda mayor estabilidad en la conexión y transferencia de datos, una de sus ventajas es que permite hacer respaldo de la información, ya que proporciona múltiples rutas, esta requiere más cable lo que hace su costo de instalación más elevado.

      .py-3.py-md-4(titulo="Topología anillo")
        .row.justify-content-center.align-items-center
          .col-md-5
           figure
            img(src='@/assets/curso/temas/tema1/img1-15.svg', alt="")
          .col-md-5.mb-4.mb-md-0
            h4 Topología anillo
            p Aquí los dispositivos están conectados a un cable en forma circular alrededor de un concentrador central (Kurose, 2017).

      .py-3.py-md-4(titulo="Topología híbrida")
        .row.justify-content-center.align-items-center
          .col-md-5
           figure
            img(src='@/assets/curso/temas/tema1/img1-17.svg', alt="")
          .col-md-5.mb-4.mb-md-0
            h4 Topología híbrida
            p En ella se pueden utilizar una o más topologías fusionadas para brindar una mejor seguridad y estabilidad en la organización; es importante decir que, en esta topología, si un solo equipo falla no afectará al resto de la red, generalmente se pueden hacer combinaciones entre la estrella-bus y estrella-anillo (Sánchez et al, 2020).

    h3.titulo-tercero Modelo OSI

    .row.justify-content-center.align-items-center
      .col-md-7
        p.mb-4 Un puente de red, es un dispositivo de interconexión de redes, este opera en la capa 2 del modelo OSI, divide una red en segmentos. Por su parte, el #[em switch] es un dispositivo electrónico de interconexión de redes que también opera en la capa de enlace de datos, este interconecta dos o más segmentos de red. Ahora bien, un router es un dispositivo electrónico que encamina e interconecta las redes de los equipos que operan en la capa 3.
      
        .cajon.color-acento-contenido.p-4.mb-4
          p <b>¿Qué es TCP/IP?</b>
          p.mb-5 Se relaciona a un protocolo para el funcionamiento de la red de internet, este funciona a nivel de transporte del modelo de referencia OSI, proporciona fiabilidad en los datos, el protocolo IP, se encuentra en el nivel de red OSI, que encamina los datos hacia otros equipos. #[br] Estos protocolos se pueden descomponer en niveles de TCP/IP, usando siempre como referencia el modelo OSI, este se descompone en cinco niveles, cuatro niveles de software y un nivel de hardware (Kurose et at, 2017).
    
      .col-md-5
        figure
        img(src='@/assets/curso/temas/tema1/img1-18.png', alt="")

    p ¿Qué es un protocolo? Puede ser relativamente simple o complejo, es un conjunto de reglas que permiten la conexión y comunicación de dos o más entidades de un sistema.

    .row.justify-content-center.align-items-center
      .col-md-1
        figure
          img(src='@/assets/curso/temas/tema1/img1-19.svg', alt="")
      .col-md-11
        p.mb-5 El modelo OSI, básicamente es un estándar para interconectar sistemas sin importar si los sistemas son diferentes, este modelo está conformado por 7 capas, cada una de estas tienen sus propias funciones y así el conjunto alcanza su objetivo (Sánchez et al, 2020). A continuación, se detallan algunos de los protocolos en las respectivas capas de este modelo:

    ImagenInfograficaB.color-acento-contenido.mb-5
      template(v-slot:imagen)
        figure
          img(src='@/assets/curso/temas/tema1/img1-20.svg', alt="")

      div(x="30%" y="6%" tooltip="Capa de aplicación" numero="+")
        h5 Capa de aplicación
        p • #[em HyperText Transfer Protocol] (HTTP) #[br]
        p • #[em File Transfer Protocol] (FTP) #[br]
        p • #[em Simple Mail Transfer Protocol] (SMTP) #[br]
        p • #[em Secure Shell] (SSH) #[br]
        p • #[em Simple Network Management Protocol] (SNMP) #[br]
        p • #[em Domain Name System] (dignissim) #[br]#[br]
        p Estos protocolos se utilizan más en cuando se ven videos o se envían mensajes en #[em software] de mensajería o correos electrónicos.

      div(x="26%" y="20%" tooltip="Capa de presentación" numero="+")
        h5 Capa de presentación
        p • #[em Apple Filing Protocol] (AFP) #[br]
        p • #[em Network File System] (NFS) #[br]#[br]
        p Traduce el formato en el que se quiere ver, un ejemplo sería cuando se descarga un archivo, la extensión de este será manejada por esta capa.

      div(x="22%" y="35%" tooltip="Capa de sesión" numero="+")
        h5 Capa de sesión
        p • #[em Network Basic Input/Output System (NetBIOS)] #[br]
        p • #[em Internet Storage Name Service (ISNS)] #[br]
        p • #[em File Transfer Protocol (FTP)] #[br]
        p • #[em Session Annoucement Protocol (SAP)] #[br]#[br]
        p Lleva a cabo la comunicación, autoriza y gestiona el enlace entre los dispositivos.

      div(x="17%" y="49%" tooltip="Capa de transporte de datos" numero="+")
        h5 Capa de transporte de datos
        p • #[em User Datagram Protocol (UDP)] #[br]
        p • #[em Transmission Control Protocol (TCP)] #[br]#[br]
        p Hace la segmentación de lo que se va a compartir, fragmenta en varias partes, según la capacidad de la red.

      div(x="13%" y="64%" tooltip="Capa de red" numero="+")
        h5 Capa de red
        p • #[em Interior Gateway Protocol (IGP)] #[br]
        p • #[em Internet Protocol (IP)] #[br]
        p • #[em Routing Information Protocol (RIP)] #[br]
        p • #[em Internetwork Packet Exchange / Sequence Packet Exchange (IPX / SPX)] #[br]#[br]
        p Calcula la mejor ruta para enviar los paquetes, se encarga de direccionar los datos transmitidos para que salgan y lleguen al destino.

      div(x="9%" y="78%" tooltip="Capa de enlace de datos" numero="+")
        h5 Capa de enlace de datos
        p • #[em Ethernet] #[br]
        p • #[em Fiber Distributed Data Interface (FDDI)] #[br]
        p • #[em Address Resolution Protocol (ARP)] #[br]
        p • #[em Point to Point Protocol (PPP)] #[br]#[br]
        p Obtiene la información y la traduce en binario para así enviarla a la capa física.

      div(x="4%" y="93%" tooltip="Capa física" numero="+")
        h5 Capa física
        p • #[em Digital Subscriber Line (DLS)] #[br]
        p • #[em Integrated Services Digital Network (ISDN)] #[br]
        p • #[em Bluetooth] #[br]
        p • #[em Universal Serial Bus (USB)] #[br]#[br]
        p Hace el envío en binario a los medios de la red. Se encarga de la conexión física de una red.

    h3.titulo-tercero Protocolos de RED

    p.mb-4 Dentro de los protocolos de red más usados están:

    TabsC.color-acento-contenido.mb-5
      .py-3.py-md-4(titulo="DNS")
        .row.justify-content-center.align-items-center
          .col-md-5
           figure
            img(src='@/assets/curso/temas/tema1/img1-21.svg', alt="")
          .col-md-5.mb-4.mb-md-0
            h4 DNS
            p Se encarga de transformar las direcciones IP a nombres.

      .py-3.py-md-4(titulo="DHCP")
        .row.justify-content-center.align-items-center
          .col-md-5
           figure
            img(src='@/assets/curso/temas/tema1/img1-22.svg', alt="")
          .col-md-5.mb-4.mb-md-0
            h4 DHCP
            p Protocolo de configuración dinámica de host, permite que los dispositivos tengan una configuración de red de una manera automática, es más fácil de administrar.

      .py-3.py-md-4(titulo="HTTP")
        .row.justify-content-center.align-items-center
          .col-md-5
           figure
            img(src='@/assets/curso/temas/tema1/img1-23.svg', alt="")
          .col-md-5.mb-4.mb-md-0
            h4 HTTP
            p Es de los más importantes, ya que hace la transferencia de documentos de tipo “Hipertexto”. (Kurose et al, 2017).

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
