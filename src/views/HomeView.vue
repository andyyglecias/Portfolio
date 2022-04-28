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
                    <a class="card" href="#modal-project-1" data-toggle="modal">
                      <img
                        class="card-img-top"
                        src="https://via.placeholder.com/360x240"
                        alt="Project 1"
                      />
                      <div class="card-body">
                        <h3 class="card-title">Project 1</h3>
                        <h4 class="card-subtitle">Design e-shop</h4>
                        <p class="card-tags">Frontend — Backend</p>
                      </div>
                    </a>
                  </div>
                  <div class="col-12 col-md-4">
                    <a class="card" href="#modal-project-2" data-toggle="modal">
                      <img
                        class="card-img-top"
                        src="https://via.placeholder.com/360x240"
                        alt="Project 2"
                      />
                      <div class="card-body">
                        <h3 class="card-title">Project 2</h3>
                        <h4 class="card-subtitle">
                          Social Network for Musicians
                        </h4>
                        <p class="card-tags">Design — Frontend — Backend</p>
                      </div>
                    </a>
                  </div>
                  <div class="col-12 col-md-4">
                    <a class="card" href="#modal-project-3" data-toggle="modal">
                      <img
                        class="card-img-top"
                        src="https://via.placeholder.com/360x240"
                        alt="Project 3"
                      />
                      <div class="card-body">
                        <h3 class="card-title">Project 3</h3>
                        <h4 class="card-subtitle">Jewelry e-shop</h4>
                        <p class="card-tags">Frontend — Backend</p>
                      </div>
                    </a>
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
                      <a href="mailto:john@wilson.com">john@wilson.com</a><br />
                      <a href="tel:+420652887351">+420 652 887 351</a>
                    </div>
                  </div>
                  <div class="col-12 col-md-4">
                    <div class="contact">
                      <strong class="contact-label">Social</strong>
                      <a href="https://www.facebook.com">Facebook</a><br />
                      <a href="https://www.linked.com">LinekdIn</a><br />
                      <a href="https://www.twitter.com">Twitter</a>
                    </div>
                  </div>
                  <div class="col-12 col-md-4">
                    <div class="contact">
                      <strong class="contact-label">Address</strong>
                      1234 Houston Street<br />
                      New York<br />
                      NY 123456<br />
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
