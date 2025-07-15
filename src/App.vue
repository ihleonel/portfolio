<script setup>
import LinkedinIcon from './Components/Icons/LinkedinIcon.vue'
import GithubIcon from './Components/Icons/GithubIcon.vue'
import TwitterIcon from './Components/Icons/TwitterIcon.vue';
import Timeline from './Components/Timeline.vue';
import Skills from './Components/Skills.vue';
import EmailIcon from './Components/Icons/EmailIcon.vue';
import GithubContributions from './Components/GithubContributions.vue';
</script>
<template>
  <main>
    <section class="presentation">
      <div class="presentation-left">
        <h1 class="fw-bold display-4">Leonel Ibarra</h1>
        <h3 class="fw-bold highlight">Full Stack Developer</h3>
        <p class="description">
          Inicié mi carrera profesional como desarrollador hace más de
          6 años. Participé en multiples proyectos del sector público
          y privado, colaborando con distintos equipos de profesionales.
        </p>
        <div class="social-media">
          <LinkedinIcon />
          <GithubIcon />
          <TwitterIcon />
          <EmailIcon />
        </div>
      </div>
      <div class="presentation-right">
        <img
          src="https://picsum.photos/200"
          class="rounded-circle image"
          alt="Imagen Leonel"
        >
      </div>
    </section>
    <section class="experience">
      <h3 class="fw-bold">Experiencia</h3>
      <Timeline />
    </section>
    <section class="habilities">
      <h3 class="fw-bold">Tecnologías</h3>
      <p>
        Tecnologías con las que trabajé en estos años como desarrollador y con las que
        me siento cómodo y seguro de mis conocimientos. Aplicadas tanto en proyectos greenfields y brownfields.
      </p>
      <Skills />
    </section>
    <section class="contributions">
      <h3 class="fw-bold">Contribuciones</h3>
      <GithubContributions />
    </section>
    <section class="contact">
      <h3 class="fw-bold">Contacto</h3>
      <p>
        Para más información pueden visitar mis redes sociales o copiar mi correo electrónico haciendo
        clic en el icono de abajo.
      </p>
      <div class="social-media">
        <LinkedinIcon />
        <GithubIcon />
        <TwitterIcon />
        <EmailIcon />
      </div>
    </section>
  </main>
</template>

