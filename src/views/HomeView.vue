<template>
  <div class="home">
    <nav class="sections-nav-container">
      <ul id="sections-nav" class="nav sections-nav sections-nav-animated">
        <li class="sections-nav-item">
          <a
            href="#section-01"
            class="nav-link sections-nav-link goto-section active"
          >
            <span class="sections-nav-counter">01</span>
            Top
          </a>
        </li>
        <li class="sections-nav-item">
          <a href="#section-02" class="nav-link sections-nav-link goto-section">
            <span class="sections-nav-counter">02</span>
            About me
          </a>
        </li>
        <li class="sections-nav-item">
          <a href="#section-08" class="nav-link sections-nav-link goto-section">
            <span class="sections-nav-counter">03</span>
            Projects
          </a>
        </li>
        <li class="sections-nav-item">
          <a href="#section-10" class="nav-link sections-nav-link goto-section">
            <span class="sections-nav-counter">04</span>
            Contact
          </a>
        </li>
        <li class="sections-nav-item">
          <div class="sections-nav-info">
            <a href="mailto:andyyglecias@gmail.com">andyyglecias@gmail.com</a
            ><br />
            <a href="tel:+420652887351">224-245-4999</a>
          </div>
        </li>
      </ul>
    </nav>
    <main class="content">
      <div class="container-fluid-limited">
        <div class="row">
          <div class="col col-xl-9">
            <section
              id="section-01"
              class="section section-sub-header animation interaction-in"
            >
              <div class="section-body">
                <div class="jumbotron jumbotron-fluid pt-6 pt-lg-8 pb-0 mb-0">
                  <img
                    src="assets/img/profile.jpg"
                    class="jumbotron-img animation-translate animation-item-1"
                    alt="Avatar"
                  />
                  <h1
                    class="display-1 display-animated display-animated-in animation-translate animation-item-2"
                  >
                    Andy<br />Yglecias
                  </h1>
                  <p class="lead animation-translate animation-item-3">
                    Full-Stack WEB DEVELOPER
                  </p>
                </div>
              </div>
              <div class="section-footer animation-translate animation-item-4">
                <a class="section-next goto-section" href="#section-02">
                  <span class="section-next-counter">01/04</span>
                  <span class="section-next-label">Next chapter</span>
                  <span class="section-next-icon"></span>
                </a>
              </div>
            </section>
            <section id="section-02" class="section animation">
              <div class="section-body">
                <div class="row">
                  <div class="col col-xl-10">
                    <h2
                      class="section-title animation-translate-overline animation-item-1"
                    >
                      About me
                    </h2>
                    <article
                      class="article animation-translate animation-item-2"
                    >
                      <p>
                        Hello!<br />
                        I'm a Full-Stack Web developer graduate with a stellar
                        customer service and sales background. Eagerly seeking a
                        Web Developer role at a company where I can utilize and
                        further develop learned front end and back end
                        technologies, namely; Ruby on Rails, JavaScript, HTML,
                        CSS, SQL and Vue.js to create sophisticated and
                        intuitive user experiences.
                      </p>
                    </article>
                  </div>
                </div>
              </div>
              <div class="section-footer animation-translate animation-item-3">
                <a class="section-next goto-section" href="#section-03">
                  <span class="section-next-counter">02/04</span>
                  <span class="section-next-label">Next chapter</span>
                  <span class="section-next-icon"></span>
                </a>
              </div>
            </section>
            <section id="section-08" class="section animation">
              <div class="section-body">
                <h2
                  class="section-title animation-translate-overline animation-item-1"
                >
                  Projects
                </h2>
                <div class="row animation-translate animation-item-2">
                  <div class="col-12 col-md-4">
                    <a href="https://nbalatestnews.com/#/">
                      <img
                        class="card-img-top"
                        src="https://besthqwallpapers.com/Uploads/24-2-2022/190457/thumb2-nba-3d-logo-4k-gray-brickwall-national-basketball-association-creative.jpg"
                        alt="Project 1"
                      />
                    </a>
                    <div class="card-body">
                      <br />
                      <h3 class="card-title">Project 1</h3>
                      <h4 class="card-subtitle">NBA Latest News (Vue.js)</h4>
                      <a href="https://github.com/andyyglecias/nba-app.git"
                        ><p class="card-tags">View Code</p></a
                      >
                    </div>
                  </div>
                  <div class="col-12 col-md-4">
                    <a href="https://andyyglecias.github.io/graffiti-data/">
                      <img
                        class="card-img-top"
                        src="https://image.shutterstock.com/image-photo/colorful-designs-graffiti-alley-baltimore-600w-215820700.jpg
"
                        alt="Project 2"
                      />
                    </a>
                    <div class="card-body">
                      <h3 class="card-title">Project 2</h3>
                      <h4 class="card-subtitle">
                        Chicago graffiti data (VanJS)
                      </h4>
                      <a
                        href="https://github.com/andyyglecias/graffiti-data.git"
                        ><p class="card-tags">View Code</p></a
                      >
                    </div>
                  </div>
                  <div class="col-12 col-md-4">
                    <img
                      class="card-img-top"
                      src="https://image.shutterstock.com/image-photo/colorful-designs-graffiti-alley-baltimore-600w-215820700.jpg
"
                      alt="Project 3"
                    />
                    <div class="card-body">
                      <h3 class="card-title">Project 3</h3>
                      <h4 class="card-subtitle">
                        Chicago graffiti data (Ruby on Rails)
                      </h4>
                      <a
                        href="https://github.com/andyyglecias/graffit-rmv-bnd.git"
                        ><p class="card-tags">View Code</p></a
                      >
                    </div>
                  </div>
                </div>
              </div>
              <div class="section-footer animation-translate animation-item-3">
                <a class="section-next goto-section" href="#section-09">
                  <span class="section-next-counter">03/04</span>
                  <span class="section-next-label">Next chapter</span>
                  <span class="section-next-icon"></span>
                </a>
              </div>
            </section>
            <section id="section-10" class="section animation">
              <div class="section-body">
                <h2
                  class="section-title animation-translate-overline animation-item-1"
                >
                  Contact
                </h2>
                <div class="row mb-10 animation-translate animation-item-2">
                  <div class="col-12 col-md-4">
                    <div class="contact">
                      <strong class="contact-label">Stay in touch</strong>
                      <a href="mailto:andyyglecias@gmail.com"
                        >andyyglecias@gmail.com</a
                      ><br />
                      <a href="tel:+420652887351">224-245-4999</a>
                    </div>
                  </div>
                  <div class="col-12 col-md-4">
                    <div class="contact">
                      <strong class="contact-label">Social</strong>
                      <a href="www.linkedin.com/in/andy-yglecias">LinekdIn</a
                      ><br />
                    </div>
                  </div>
                  <div class="col-12 col-md-4">
                    <div class="contact">
                      <strong class="contact-label">Address</strong>
                      Dallas<br />
                      TX, 75052<br />
                    </div>
                  </div>
                </div>
                <div class="row">
                  <div class="col-12 col-xl-9">
                    <h3
                      class="section-subtitle animation-translate animation-item-3"
                    >
                      Leave a message
                    </h3>
                    <form
                      class="needs-validation animation-translate animation-item-4"
                      novalidate
                    >
                      <div class="row">
                        <div class="col-12 col-md-6">
                          <div class="form-group">
                            <label for="contact-form-name">Name</label>
                            <input
                              type="text"
                              class="form-control"
                              name="name"
                              id="contact-form-name"
                              placeholder="Your name"
                              required
                            />
                            <div class="invalid-feedback">
                              Please enter your name.
                            </div>
                          </div>
                        </div>
                        <div class="col-12 col-md-6">
                          <div class="form-group">
                            <label for="contact-form-name">E-mail</label>
                            <input
                              type="email"
                              class="form-control"
                              name="email"
                              id="contact-form-email"
                              placeholder="@"
                              required
                            />
                            <div class="invalid-feedback">
                              Please enter a valid e-mail address.
                            </div>
                          </div>
                        </div>
                      </div>
                      <div class="form-group">
                        <label for="contact-form-message">Message</label>
                        <textarea
                          class="form-control"
                          name="message"
                          id="contact-form-message"
                          placeholder="Your message"
                          rows="5"
                          required
                        ></textarea>
                        <div class="invalid-feedback">
                          Please type some message.
                        </div>
                      </div>
                      <button type="submit" class="btn btn-primary">
                        Send
                      </button>
                    </form>
                  </div>
                </div>
              </div>
              <div class="section-footer animation-translate animation-item-5">
                <span class="section-next goto-section">
                  <span class="section-next-counter">04/04</span>
                </span>
              </div>
            </section>
          </div>
        </div>
      </div>
    </main>
  </div>
</template>

<style></style>

<script>
export default {
  data: function () {
    return {
      message: "Welcome to Vue.js!",
    };
  },
  created: function () {},
  methods: {},
  computed: {},
};
</script>
