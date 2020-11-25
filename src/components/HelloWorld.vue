<template>
  <div>
    <!-- Navigation bar -->
    <nav id="navbar" class="nav">
      <ul class="nav-list">
        <li>
          <a href="#welcome-section">About</a>
        </li>
        <li>
          <a href="#projects">Work</a>
        </li>
        <li>
          <a href="#contact">Contact</a>
        </li>
      </ul>
    </nav>

    <!-- Section 1 -->
    <section id="welcome-section" class="welcome-section">
      <h1><code>Hello World, I'm Taya</code></h1>
      <p>I'm a web developer.</p>
    </section>

    <!-- Section 2 -->
    <section id="projects">
      <div class="projects-section">
        <h2>Here are some of my projects</h2>
        <a
          href="https://codepen.io/tayamikachimatiro/pen/zYqJzej"
          target="_blank"
        >
          <img
            src="https://raw.githubusercontent.com/freeCodeCamp/cdn/master/build/testable-projects-fcc/images/tribute.jpg"
            alt="Page Image"
          />
          <p class="project-tile">
            Tribute Page
          </p>
        </a>
      </div>
    </section>

    <!-- Section 3 -->
    <section id="contact" class="contact-section">
      <div class="contact-section-header">
        <h2>Let's make things work...</h2>
        <p>What's your cup of tea?</p>
      </div>
      <div>
        <a
          ><i class="fab fa-facebook-square">Facebook</i>
          <br />
        </a>
        <a><i class="fab fa-github"></i>Github</a>
        <br />
        <a><i class="fab fa-twitter"></i>Twitter</a>
        <br />
        <a><i class="fas fa-shipping-fast">Send an e-mail</i> </a>
        <br />
        <a><i class="fas fa-phone-square-alt"></i>Call me</a>
      </div>
    </section>

    <!-- Footer -->
    <footer>
      <p>
        This is a dummy page for exersice perposes only.
      </p>
      <p>
        &copy; Taya, 2020
      </p>
    </footer>
  </div>
</template>

<script>
export default {
  name: "HelloWorld",
  props: {
    msg: String,
  },
};
</script>
