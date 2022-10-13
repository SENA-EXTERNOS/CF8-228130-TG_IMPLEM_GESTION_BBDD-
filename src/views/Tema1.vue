<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 1
      h1 Introducción a los sistemas operativos de red

    .row.justify-content-center.align-items-center.mb-5
      .col-md-7
        p.mb-4 Son aquellos sistemas que están unidos a dos o más equipos utilizando un medio de comunicación, con el objetivo de compartir recursos de 
         em hardware 
         | y 
         em software; 
         | entre los sistemas operativos de red más comunes están: 
         em LAN Manager, Novell Netware, Linux, UNIX, LanTastic, Windows Server, 
         | etc.
          
        p.mb-4 Una red de equipos no pude funcionar sin un sistema operativo de red, al igual que un equipo sin un sistema operativo, a estos sistemas de red también se les conoce como NOS; otra definición es que es un software que rige y administra recursos en una red y lleva el control de seguridad de los mismos.
          
        p Un NOS maneja los servicios óptimos para que el usuario esté libre de error al conectarse a una red, este provee una interfaz de usuario que permite reducir la complejidad y dificultades al usar la red.
      .col-md-5
        figure
          img(src='@/assets/curso/temas/tema1/img1-1.png', alt="Microchip")

      p.mb-5 La principal función de un sistema operativo de red es brindar una forma de transmisión de archivos de un equipo a otro, la internet brinda un mecanismo para hacer transferencias a través del FTP (#[em File Transfer Protocol]).

      .row.justify-content-center.mb-5
        .col-lg-9
          .cajon.color-acento-contenido.p-4
            p.mb-0 El primer sistema operativo de red estaba enfocado a equipos con un procesador Motorola 6800, luego aparecieron los procesadores Intel como 
              em Novell Netware; 
              | el éxito de este #[em software] de red es que a pesar de que era arcaico, estaba dispuesto a relacionarse con otras tecnologías, también brindaba apoyo al protocolo de #[em AppleTalk]. (Cura, 2020).
      
      .row.justify-content-center.mb-5
        .col-lg-9

          .bloque-texto-g.color-secundario.p-3.p-sm-4.p-md-5
            .bloque-texto-g__img(
            :style="{'background-image': `url(${require('@/assets/curso/temas/tema1/img1-2.png')})`}"
            )
            .bloque-texto-g__texto.p-4
              p.mb-0 Para el año 2000, apareció la versión de #[em Microsoft Windows] 200 profesional, el que se adoptaría por su estabilidad y por primera vez presentó también el #[em ActiveDirectory], la versión actual de #[em Microsoft] para estaciones de trabajo, el #[em Windows Server] 2022, lanzado en agosto del 2021, el cual aplica protección multicapa contra amenazas con un servidor de núcleo seguro y ejecuta cargas de trabajo como SQL server utilizando 48Tb de memoria, también usa #[em Windows] admin center para mejorar la gestión de máquinas virtuales y conexión a #[em Azure].

      p.mb-4 Se presentan las características técnicas en la familia 
        em Windows.

      p.mb-0 A continuación, se muestran las características técnicas en la familia de 
        em Windows:

    ImagenInfografica.color-primario
      template(v-slot:imagen)
        figure
          img(src='@/assets/curso/temas/tema1/img1-3.png', alt='Características técnicas de la familia Windows.')
          
      .tarjeta.color-secundario.p-3(x="12%" y="16%" numero="+")
        p • Es de 16 Bit
        p • Fue diseñado y desarrollado para gestionar recursos en la 
          em networking 
          | basadas en 
          em Windows 
          | y 
          em peer to peer.
        p • No fue diseñado para soportar muchos usuarios.

      .tarjeta.color-secundario.p-3(x="88%" y="16%" numero="+")
        p • Es un sistema operativo que provee máxima confiabilidad, rendimiento y seguridad.
        p • Tiene mayores requerimientos de 
          em hardware 
          | frente a 
          em Windows 
          | 95.
        p • Su interfaz gráfica es amigable similar a la de 
          em Windows 
          | 95.

      .tarjeta.color-secundario.p-3(x="12%" y="62%" numero="+")
        p Desarrollado en el lenguaje C, está disponible en varias versiones, entre ellas, una adaptada por IBM para el uso en estaciones de trabajo, 
          em UNIX 
          | permite múltiples tareas y múltiples usuarios, su sistema de archivo admite la organización fácil a los archivos y permite la protección de los mismos, para el año 71 Ritchie y Kernigham desarrollan el lenguaje C en un PDP-11, luego en 1973, Ritchie y Thompson desarrollan un sistema multiusuario, 
          em UNIX 
          | había nacido. (Lezcano, 2018)

      .tarjeta.color-secundario.p-3(x="88%" y="61%" numero="+")
        p Dentro de las características principales de este sistema destaca la capacidad multitarea, que hace posible la ejecución de varios programas a la vez; también el sistema multiusuario en el que varios usuarios pueden acceder a las aplicaciones y recursos al mismo tiempo, Linux es flexible para poder conectarse a cualquier ordenador ya que internet creó dentro en entornos 
          em Unix 
          | y es por eso que Linux tiene mayores capacidades para navegar.
      
    .row.justify-content-center.mb-5
      .col-lg-8  
        .cajon.color-acento-contenido.p-4.mb-5
          p.mb-0 Puede decirse que tanto 
            em Unix, 
            | como 
            em Linux 
            | son sistemas operativos idénticos (Cura, 2020).

    Separador

    #t_1_1.titulo-segundo.color-acento-contenido
      h2 1.1 Licenciamientos

    .row.justify-content-center.mb-5
      .col-lg-10
        .bloque-texto-a.color-secundario.p-4.p-md-5.mb-5.fcac25
          .row.m-0.align-items-center.justify-content-between
            .col-lg-8.bloque-texto-a__texto.p-4.borde-lineas
                p.mb-0 
                  b
                    span.text.cac Las licencias 
                    | son básicamente, convenios o contratos en donde el usuario acepta las condiciones y términos de la empresa desarrolladora para hacer uso del 
                    em software, 
                    | los términos serán más o menos restrictivos, si es libre o propietario. Por tanto, las licencias son permisos para poder usar algún tipo de 
                    em software 
                    | y pueden tener limitación de tiempo y variar según la ubicación geográfica donde se utiliza.
            .col-lg-4.mb-4.mb-lg-0(data-aos="fade-left")
              figure.mb-5
                img(src='@/assets/curso/temas/tema1/img1-4.png', alt="Licencias")

    p.mb-5 Las licencias se pueden definir en varios tipos como:

    TabsA.color-primario.mb-5
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
              | que derivan proyectos anteriores como es el caso de 
              em Unix.

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
            p Están protegidas por la legislación internacional de <em>Copyright</em>, estas restringen las modificaciones o copias sin la autorización del autor. Sin embargo, estas licencias definen las condiciones en las que se puede hacer uso, copia, modificación y distribución del <em>software</em>.

      .tarjeta.color-adicional-1.p-4(titulo="GPL <em>General Public License</em>").borde
        .row.m-0.justify-content-center.align-items-center
          .col-xl-2.mb-5
            h4 
              span.text-white GPL
            figure
              img(src='@/assets/curso/temas/tema1/img1-8.svg', alt='Licencia GPL')
          .col-xl-6
            p Limita la distribución del <em>software</em> e impide que pueda ser integrado. Además, se basa en la legislación internacional de <em>Copyright</em>.

    .row.justify-content-center.mb-5
      .col-lg-10

        .bloque-texto-g.fcac25.p-3.p-sm-4.p-md-5
          .bloque-texto-g__img(
            :style="{'background-image': `url(${require('@/assets/curso/temas/tema1/img1-9.svg')})`}"
          )
          .bloque-texto-g__texto.p-4.mb-5.borde-lineas
            p.mb-3 Un tema muy interesante es el referente a los licenciamientos de los servidores, desde 
              em Windows Server 
              | 2016, cambia la forma en como se licencian los sistemas operativos en temas de servidores.
              br
              br
            p El modelo de licenciamiento anterior era un servidor o CPU, que necesitaba de una licencia de 
              em Windows Server, 
              | a un nuevo modelo donde por cada núcleo de la CPU tenga una licencia 
              em Core 
              | de 
              em Windows Server, 
              | esto se debe a que las CPU actuales cuentan por varios núcleos o 
              em Cores, 
              | lo que se convierte en una CPU, existen varias CPU en forma de núcleos.

    .row.justify-content-center.mb-5
      .col-lg-10
        .cajon.color-acento-contenido.p-4.mb-5
          p.mb-0 En resumen, existen muchos tipos de licencias específicas y se clasifican según el tipo, el uso, el tiempo y el público a quien va dirigido.

    Separador

    #t_1_2.titulo-segundo.color-acento-contenido
      h2 1.2 Conceptos básicos de redes y <em>networking</em>

    .row.justify-content-center.align-items-center
      .col-md-7
        p.mb-4 Una red de computadoras que se interconectan entre sí, se define como una red, utilizando dispositivos físicos que envían y reciben datos con el fin de compartir recursos, información y ofrecer múltiples servicios. El alcance de una red dependerá de su tamaño geográfico, ya que puede variar desde pocos equipos en una empresa hasta miles de estos conectados a largas distancias, es por esto que las redes se catalogan según su extensión de la siguiente forma:

        .fcac25.p-4.mb-5
          p.mb-0 <b>Red de área local:</b> esta red suele interconectar equipos y dispositivos cerca, por ejemplo, en una empresa o un hogar. Existen otras redes como la (WAN) que es una red de área extensa y conecta varios equipos que se encuentran a largas distancias, un ejemplo de esta sería dos LAN interconectadas a largas distancias. El internet es un tipo de red WAN (Tanenbaum et al, 2012).
        
      .col-md-5
        figure.mb-5
          img(src='@/assets/curso/temas/tema1/img1-10.png', alt="Mundo conectado")

    .row.justify-content-center.align-items-center.mb-5
      .col-md-5
        figure
        img(src='@/assets/curso/temas/tema1/img1-11.png', alt="Conexiones de red")

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

    h3
      i.fas.fa-square.cac.me-3
      | Topologías básicas de redes

    p Existen 5 topologías básicas, estas son:

    TabsC.color-acento-contenido.mb-5
      .py-3.py-md-4(titulo="Topología bus")
        .row.justify-content-center.align-items-center
          .col-md-5
           figure
            img(src='@/assets/curso/temas/tema1/img1-13.svg', alt="Conexiones tipo bus")
          .col-md-5.mb-4.mb-md-0
            p Se evidencia cuando los dispositivos están conectados a un cable, un ejemplo de esto sería dos equipos conectados entre sí por un mismo cable, esta topología tiene una desventaja grande y es que si en algún momento el cable principal falla, la red también dejaría de funcionar.

      .py-3.py-md-4(titulo="Topología estrella")
        .row.justify-content-center.align-items-center
          .col-md-5
           figure
            img(src='@/assets/curso/temas/tema1/img1-14.svg', alt="Conexiones tipo estrella")
          .col-md-5.mb-4.mb-md-0
            p Es en donde los dispositivos están conectados a segmentos de cables que llegan hasta el concentrador, esta topología se encuentra en empresas y hogares normalmente, una ventaja de la topología estrella es que si uno de los dispositivos de la red falla, los demás dispositivos podrán funcionar normalmente.

      .py-3.py-md-4(titulo="Topología malla")
        .row.justify-content-center.align-items-center
          .col-md-5
           figure
            img(src='@/assets/curso/temas/tema1/img1-15.svg', alt="Conexiones tipo malla")
          .col-md-5.mb-4.mb-md-0
            p Aquí los dispositivos de la red están conectados entre sí mediante un cable, esta topología brinda mayor estabilidad en la conexión y transferencia de datos, una de sus ventajas es que permite hacer respaldo de la información, ya que proporciona múltiples rutas, esta requiere más cable lo que hace su costo de instalación más elevado.

      .py-3.py-md-4(titulo="Topología anillo")
        .row.justify-content-center.align-items-center
          .col-md-5
           figure
            img(src='@/assets/curso/temas/tema1/img1-15.svg', alt="Conexiones tipo anillo")
          .col-md-5.mb-4.mb-md-0
            p Aquí los dispositivos están conectados a un cable en forma circular alrededor de un concentrador central (Kurose, 2017).

      .py-3.py-md-4(titulo="Topología híbrida")
        .row.justify-content-center.align-items-center
          .col-md-5
           figure
            img(src='@/assets/curso/temas/tema1/img1-17.svg', alt="Conexiones híbridas")
          .col-md-5.mb-4.mb-md-0
            p En ella se pueden utilizar una o más topologías fusionadas para brindar una mejor seguridad y estabilidad en la organización; es importante decir que, en esta topología, si un solo equipo falla no afectará al resto de la red, generalmente se pueden hacer combinaciones entre la estrella-bus y estrella-anillo (Sánchez et al, 2020).

    h3
      i.fas.fa-square.cac.me-3
      | Modelo OSI

    .row.justify-content-center.align-items-center
      .col-md-7
        p.mb-4 Un puente de red, es un dispositivo de interconexión de redes, este opera en la capa 2 del modelo OSI, divide una red en segmentos. Por su parte, el #[em switch] es un dispositivo electrónico de interconexión de redes que también opera en la capa de enlace de datos, este interconecta dos o más segmentos de red. Ahora bien, un 
          em router 
          | es un dispositivo electrónico que encamina e interconecta las redes de los equipos que operan en la capa 3.
      
        .fcac25.p-4.mb-5
          p <b>¿Qué es TCP/IP?</b>
          p.mb-0 Se relaciona a un protocolo para el funcionamiento de la red de internet, este funciona a nivel de transporte del modelo de referencia OSI, proporciona fiabilidad en los datos, el protocolo IP, se encuentra en el nivel de red OSI, que encamina los datos hacia otros equipos. #[br] Estos protocolos se pueden descomponer en niveles de TCP/IP, usando siempre como referencia el modelo OSI, este se descompone en cinco niveles, cuatro niveles de 
            em software 
            | y un nivel de 
            em hardware 
            | (Kurose et at, 2017).
    
      .col-md-5
        figure
        img(src='@/assets/curso/temas/tema1/img1-18.png', alt="Autopista de datos")

    p ¿Qué es un protocolo? Puede ser relativamente simple o complejo, es un conjunto de reglas que permiten la conexión y comunicación de dos o más entidades de un sistema.

    .row.justify-content-center.align-items-center.mb-5
      .col-md-1.col-sm-10
        figure
          img(src='@/assets/curso/temas/tema1/img1-19.svg', alt="Monitor con la palabra OSI")
      .col-md-11
        p.mb-0 El modelo OSI, básicamente es un estándar para interconectar sistemas sin importar si los sistemas son diferentes, este modelo está conformado por 7 capas, cada una de estas tienen sus propias funciones y así el conjunto alcanza su objetivo (Sánchez et al, 2020). A continuación, se detallan algunos de los protocolos en las respectivas capas de este modelo:
    
    
    .col-md-8.mx-auto.mb-5
      ImagenInfografica.color-acento-contenido.mb-5
        template(v-slot:imagen)
          figure
            img(src='@/assets/curso/temas/tema1/img1-20.svg', alt="Capas del modelo OSI")

        .tarjeta.color-acento-contenido.p-3(x="30%" y="7%" numero="+")
          .h5.mb-2 Capa de aplicación
          p.mb-0 • #[em HyperText Transfer Protocol] (HTTP)
          p.mb-0 • #[em File Transfer Protocol] (FTP)
          p.mb-0 • #[em Simple Mail Transfer Protocol] (SMTP)
          p.mb-0 • #[em Secure Shell] (SSH)
          p.mb-0 • #[em Simple Network Management Protocol] (SNMP)
          p • #[em Domain Name System] (dignissim)
          p Estos protocolos se utilizan más en cuando se ven videos o se envían mensajes en #[em software] de mensajería o correos electrónicos.

        .tarjeta.color-acento-contenido.p-3(x="26%" y="21%" numero="+")
          h5 Capa de presentación
          p.mb-0 • #[em Apple Filing Protocol] (AFP)
          p • #[em Network File System] (NFS)
          p Traduce el formato en el que se quiere ver, un ejemplo sería cuando se descarga un archivo, la extensión de este será manejada por esta capa.

        .tarjeta.color-acento-contenido.p-3(x="22%" y="36%" numero="+")
          h5 Capa de sesión
          p.mb-0 • #[em Network Basic Input/Output System (NetBIOS)]
          p.mb-0 • #[em Internet Storage Name Service (ISNS)]
          p.mb-0 • #[em File Transfer Protocol (FTP)]
          p • #[em Session Annoucement Protocol (SAP)]
          p Lleva a cabo la comunicación, autoriza y gestiona el enlace entre los dispositivos.

        .tarjeta.color-acento-contenido.p-3(x="17%" y="50%" numero="+")
          h5 Capa de transporte de datos
          p.mb-0 • #[em User Datagram Protocol (UDP)]
          p • #[em Transmission Control Protocol (TCP)]
          p Hace la segmentación de lo que se va a compartir, fragmenta en varias partes, según la capacidad de la red.

        .tarjeta.color-acento-contenido.p-3(x="13%" y="65%" numero="+")
          h5 Capa de red
          p.mb-0 • #[em Interior Gateway Protocol (IGP)]
          p.mb-0 • #[em Internet Protocol (IP)]
          p.mb-0 • #[em Routing Information Protocol (RIP)]
          p • #[em Internetwork Packet Exchange / Sequence Packet Exchange (IPX / SPX)]
          p Calcula la mejor ruta para enviar los paquetes, se encarga de direccionar los datos transmitidos para que salgan y lleguen al destino.

        .tarjeta.color-acento-contenido.p-3(x="8%" y="80%" numero="+")
          h5 Capa de enlace de datos
          p.mb-0 • #[em Ethernet]
          p.mb-0 • #[em Fiber Distributed Data Interface (FDDI)]
          p.mb-0 • #[em Address Resolution Protocol (ARP)]
          p • #[em Point to Point Protocol (PPP)]
          p Obtiene la información y la traduce en binario para así enviarla a la capa física.

        .tarjeta.color-acento-contenido.p-3(x="4%" y="94%" numero="+")
          h5 Capa física
          p.mb-0 • #[em Digital Subscriber Line (DLS)]
          p.mb-0 • #[em Integrated Services Digital Network (ISDN)]
          p.mb-0 • #[em Bluetooth]
          p • #[em Universal Serial Bus (USB)]
          p Hace el envío en binario a los medios de la red. Se encarga de la conexión física de una red.

    h3
      i.fas.fa-square.cac.me-3
      | Protocolos de RED

    p.mb-4 Dentro de los protocolos de red más usados están:

    TabsC.color-acento-contenido.mb-5
      .py-3.py-md-4(titulo="DNS")
        .row.justify-content-center.align-items-center
          .col-md-5
           figure
            img(src='@/assets/curso/temas/tema1/img1-21.svg', alt="DNS")
          .col-md-5.mb-4.mb-md-0
            p Se encarga de transformar las direcciones IP a nombres.

      .py-3.py-md-4(titulo="DHCP")
        .row.justify-content-center.align-items-center
          .col-md-5
           figure
            img(src='@/assets/curso/temas/tema1/img1-22.svg', alt="DHCP")
          .col-md-5.mb-4.mb-md-0
            p Protocolo de configuración dinámica de 
              em host, 
              | permite que los dispositivos tengan una configuración de red de una manera automática, es más fácil de administrar.

      .py-3.py-md-4(titulo="HTTP")
        .row.justify-content-center.align-items-center
          .col-md-5
           figure
            img(src='@/assets/curso/temas/tema1/img1-23.svg', alt="HTTP")
          .col-md-5.mb-4.mb-md-0
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
