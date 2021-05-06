<script>
  import {
    Telegram,
    WhatsApp,
    Facebook,
    Twitter,
  } from "svelte-share-buttons-component"

  const url = "https://pedrocastillo.netlify.app/"
  const title = "Compromiso de Pedro Castillo con el pueblo peruano"
  const desc =
    "Hemos tenido en el pasado a políticos que llegaron al poder con la promesa de cambios, y que al final terminaron traicionando la confianza de los peruanos. Me comprometo a que no daré descanso a mi brazo ni reposo a mi alma hasta haber honrado mis promesas de transformación social."
</script>

<img
  class="cover"
  src="images/pedrocastillo.png"
  alt="Foto de Pedro Castillo"
/>

<main>
  <h1>Compromiso con el pueblo peruano</h1>
  <p>
    <a target="_blank" href="https://twitter.com/PedroCastilloTe">
      Pedro Castillo Terrones</a
    > <span class="date">5 de Mayo del 2021</span>
  </p>
  <ol>
    <li>
      <p>
        <b>Me comprometo</b> a trabajar sin descanso para derrotar la pandemia, sin
        perder tiempo y sin repetir los errores cometidos. Voy a garantizar la vacunación
        para todos sin discriminación y sin privilegios. No habrá colores políticos
        ni ideologías en nuestro objetivo de conseguir las vacunas. Tocaremos todas
        las puertas, la vacuna es fundamental. La salud de mi pueblo estará por encima
        de todo.
      </p>
    </li>
    <li>
      <p>
        La pandemia ha evidenciado la importancia de la ciencia y la teconología
        en el bienestar de la población. Por tanto, <b>me comprometo</b> a que la
        política de salud en mi Gobierno será en base a la evidencia científica.
        Asímismo, se brindará todo el apoyo al trabajo de los científicos e investigadores
        peruanos, a partir del nuevo Ministerio de Ciencia y Tecnología. Sin ciencia
        no hay futuro ni desarrollo.
      </p>
    </li>
    <li>
      <p>
        Durante nuestra campaña hemos ofrecido cambios fundamentales en el país,
        como la convocatoria a una Asamablea Constituyente. <b>Me comprometo</b>
        que todo ello se hará dentro del marco jurídico vigente. Nunca más golpes
        de Estado, nunca más compra de medios de comunicación. Nunca más corrupción
      </p>
    </li>
    <li>
      <p>
        Hemos tenido en el pasado a Gobiernos que entraron por la vía
        democrática y luego buscaron perpetuarse en el poder. <b
          >Me comprometo</b
        > a dejar el cargo de presidente de la República el 28 de julio de 2026.
        Nunca más interpretaciones auténticas. Cuando termine mi mandato regresaré
        a mi escuela a seguir trabajando por mi pueblo.
      </p>
    </li>
    <li>
      <p>
        Doy la garantía de que no obstaculizaremos el trabajo de la justicia.
        Soy demócrata, por ellp <b>me comprometo</b> a fortalecer el sistema anticorrupcion
        del país, respetar su independencia y no interferir en los procesos en curso
        y en los que se pueden venir. La lucha contra la corrupción en un mandato
        del pueblo y en mi gobierno será un imperativo moral
      </p>
    </li>
    <li>
      <p>
        No puede existir democracia sin libertad de expresión, el respeto a las
        minorías y el respeto a los derechos humanos. En ese sentido, <b
          >me comprometo</b
        > a defender los derechos humanos de todos los peruanos y peruanas. Ademas,
        respetaré los tratados internacionales que el Perú ha suscrito en dicha materia
      </p>
    </li>
    <li>
      <p>
        Los pueblos indígenas han sido los eternos postergados de nuestra
        República. No puede haber democracia si no se respeta sus derechos. <b
          >Me comprometo</b
        > a atender las decisiones de los pueblos originarios respecto a su territorio
        y a su forma de vida. El necesario crecimiento económico debe ir de la mano
        de la mejora de sus condiciones de básicas
      </p>
    </li>
    <li>
      <p>
        <b>Me comprometo</b> a luchar contra la delicuencia en todas sus formas,
        la que nos roba en la calle y la que usa cuello blanco. Condenamos al terrorismo
        y al narcotráfico y lo combatiremos intensamente. Fortaleceremos a la Policía
        Nacional, sumaremos a esta lucha contra la inseguridad a las rondas campesinas
        y las Fuerzas Armadas tendrán el rol que la democracia manda.
      </p>
    </li>
    <li>
      <p>
        Hemos tenido en el pasado a políticos que llegaron al poder con la
        promesa de cambios, y que al final terminaron traicionando la confianza
        de los peruanos. <b>Me comprometo</b> a que no daré descanso a mi brazo ni
        reposo a mi alma hasta haber honrado mis promesas de transformación social.
        Mi Gobierno buscará una solución decidida y sostenible en el tiempo para
        la pobreza y el desempleo. Lucharemos para que nuestros niños y jóvenes puedan
        vivir en una sociedad con menos desigualdades. Lo haremos de manera técnica
        y viable, respetando la propiedad
      </p>
    </li>
    <li>
      <p>
        Para que ese país que sueño para mis hijos y alumnos se haga realidad
        será necesario fortalecer la democracia, garantizar las libertates y
        consolidar a las instituciones. El Tribunal Constitucional, la
        Defensoría del Pueblo y los organismos reguladores del Estado serán
        fortalecidos para que cumplan con su verdadero objetivo: servir al
        pueblo. Nuestro objetivo es el bien común. Es momento de darle a la
        gente los derechos que le han sido ajenas. Ese es <b>mi compromiso</b>
      </p>
    </li>
  </ol>
  <p>Palabra de maestro.</p>

  <div class="signature">
    <p><b>🇵🇪 Pedro Castillo Terrones</b></p>
    <span>Candidato a Presidencia Constitucional de la República</span>
  </div>
  <div class="share">
    <span><b>Compartir ❤️</b></span>
    <Telegram class="share-button" text={title} {url} />
    <Twitter
      class="share-button"
      text={title}
      {url}
      hashtags="pedrocastillo,perulibre,juntosporelperu"
      via="username"
      related="other,users"
    />
    <WhatsApp class="share-button" text="{title} {url}" />
    <Facebook class="share-button" {url} />
  </div>
</main>

<style>
  .cover {
    max-width: 100%;
    height: auto;
    margin: 0 auto;
    display: block;
  }

  .date {
    color: rgb(135, 135, 135);
  }

  main {
    max-width: 325px;
    margin: 0 auto;
    padding-bottom: 60px;
  }

  @media (min-width: 640px) {
    .cover {
      max-width: 720px;
    }
    main {
      padding: 1em;
      max-width: 600px;
    }
  }

  .share span {
    margin-right: 12px;
    background-image: linear-gradient(
      to left,
      rgb(238, 165, 238),
      rgb(170, 110, 212),
      rgb(102, 102, 238),
      rgb(70, 211, 70),
      rgb(191, 237, 118),
      rgb(255, 199, 95),
      rgb(255, 118, 118)
    );
    -webkit-background-clip: text;
    color: transparent;
  }

  .share {
    padding-top: 12px;
    display: flex;
    justify-content: flex-end;
    align-items: center;
  }

  .signature p {
    margin-bottom: 0;
  }

  .signature span {
    color: rgb(135, 135, 135);
  }
</style>
