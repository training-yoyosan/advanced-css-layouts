<template>
  <q-page padding>
    <exercise-header
      label="02. CSS-only hamburger button"
      :expanded="expanded"
      :instructions="instructions"
      filename="02-hamburger"
    />

    <header>
      <div class="row">
        <a
          href="/02-hamburger#main-menu"
          class="menu-toggle"
          id="main-menu-toggle"
          aria-label="Open main menu"
        >
          <span class="sr-only">Open main menu</span>
          <span class="fa fa-bars" aria-hidden="true"></span>
        </a>
        <div class="logo">
          <h1>
            <i class="fas fa-paint-brush"></i> LayOut Times
          </h1>
          <h2>Your Web Design Destination</h2>
        </div>
      </div>

      <nav id="main-menu" class="main-menu" aria-label="main menu">
        <a href="/02-hamburger#main-menu-toggle" class="menu-close">
          <span class="sr-only">Close main menu</span>
          <span class="fa fa-close" aria-hidden="true"></span>
        </a>
        <ul>
          <li>
            <a href="/02-hamburger#">CSS Resources</a>
          </li>
          <li>
            <a href="/02-hamburger#">Design</a>
          </li>
          <li>
            <a href="/02-hamburger#">Videos</a>
          </li>
          <li>
            <a href="/02-hamburger#">Social Media</a>
          </li>
          <li>
            <a href="/02-hamburger#">Inspiration</a>
          </li>
          <li>
            <a href="/02-hamburger#">News</a>
          </li>
          <li>
            <a href="/02-hamburger#">Top Talent</a>
          </li>
        </ul>
      </nav>
      <!--
        Makes the whole screen clickable so the menu disappears
        if the users doesn't click on the Close button.
      -->
      <a href="/02-hamburger#main-menu-toggle" class="backdrop" hidden></a>
    </header>

    <main>
      <section id="first">
        <h1>Jen’s Awesome Resources</h1>
        <article>
          <h2>Learn with Jen Kramer online at Harvard Extension</h2>
          <p>Join some of the many informative courses Jen teaches through the Harvard Extension School. Courses count towards bachelors and masters degree programs, certificates, or take a class for your own enrichment.</p>
          <ul>
            <li>
              <a
                href="https://www.extension.harvard.edu/course-catalog/courses?instructors=Kramer,%20Jennifer"
                target="_blank"
              >
                Jen's course list
                <i class="fas fa-paint-brush"></i>
              </a>
            </li>
            <li>
              <a href="http://extension.harvard.edu" target="_blank">
                Harvard Extension website
                <i class="fas fa-paint-brush"></i>
              </a>
            </li>
          </ul>
        </article>
        <article>
          <img src="img/book.png" alt="Before You Code book cover." />
          <h2>Plan your product’s success</h2>
          <p>
            By taking the time to do upfront validation, planning and iterating before you build, you can avoid
            ideas that flop and create a product that exceeds expectations. Heather O'Neill and Jen Kramer's
            latest book,
            <cite>Before You Code</cite>, will guide you through the process.
          </p>
          <p>
            <a href="http://beforeyoucode.guide" target="_blank">
              Visit the
              <cite>Before You Code</cite> website
              <i class="fas fa-paint-brush"></i>
            </a>
          </p>
        </article>
        <article>
          <h2>More Responsive Design 2.0</h2>
          <p>
            Get a head start on the latest responsive web design (RWD) techniques with this great list of
            resources.
          </p>
          <p>
            <a href="https://codepen.io/jen4web/post/rwd20readinglist" target="_blank">
              Visit RWD 2.0 Reading List
              <i class="fas fa-paint-brush"></i>
            </a>
          </p>
        </article>
        <article>
          <img src="img/cssworkout.png" alt="CSS Workout" />
          <h2>Have you done your CSS workout for the day?</h2>
          <p>
            Nowhere is practice more important than with CSS layouts. For 15 years, we’ve listened to students
            complain about CSS layouts, how hard they are to understand, and how things “don’t work” in the
            expected way. Now you can train daily to master them.
          </p>
          <p>
            <a href="http://www.cssworkout.guide" target="_blank">
              Visit
              <cite>CSS Workouts</cite> to start your
              routine!
              <i class="fas fa-paint-brush"></i>
            </a>
          </p>
        </article>
      </section>
      <section id="main">
        <h1>Main News</h1>
        <article>
          <img src="img/courses.png" alt="Frontend Masters classroom." />
          <h2>Advance Your Skills with In-Depth, Modern Front-End Engineering Courses</h2>
          <p>The best courses on the web, taught by industry leading experts!</p>
          <p>
            <a href="http://www.frontendmasters.com" target="_blank">
              Join now to continue your learning journey.
              <i class="fas fa-paint-brush"></i>
            </a>
          </p>
        </article>
        <article>
          <img src="img/bootcamp.png" alt="Frontend Masters Bootcamp." class="floatright" />
          <h2>Coming 2019 the Frontend Masters Bootcamp</h2>
          <p>
            Featuring instruction from Jen Kramer and Brian Holt, this incredible and free resource is everything
            you need to get started on being a web developer. Available late 2019.
          </p>
          <p>
            <a href="https://frontendmasters.github.io/bootcamp/" target="_blank">
              Visit the Bootcamp website
              <i class="fas fa-paint-brush"></i>
            </a>
          </p>
        </article>
        <article>
          <h2>CSS-Tricks: why we love it!</h2>
          <p>
            Still one of the best resources on the web to bend CSS to your will, CSS-Tricks is jam packed with
            techniques, information and best practices.
          </p>
          <p>
            <a href="http://www.css-tricks.com" target="_blank">
              Check out CSS-Tricks
              <i class="fas fa-paint-brush"></i>
            </a>
          </p>
        </article>
        <article>
          <img src="img/codepen.png" alt="Codepen." class="floatleft" />
          <h2>Learn best by doing? Try Codepen!</h2>
          <p>Get immediate feedback on the code you type right in the browser!</p>
          <p>
            <a href="http://www.codepen.com" target="_blank">
              Try Codepen now
              <i class="fas fa-paint-brush"></i>
            </a>
          </p>
        </article>
      </section>
      <section id="devs">
        <h1>Developers to Follow:</h1>
        <ul>
          <li>
            <figure>
              <a href="http://www.twitter.com/jen4web" target="_blank">
                <img src="img/jen.png" alt="Jen Kramer" />
              </a>
              <figcaption>
                <p>
                  <strong>Jen Kramer</strong>
                  <br />Harvard University Extension School
                  <br />
                  <a href="http://www.twitter.com/jen4web" target="_blank">
                    <i class="fab fa-twitter-square"></i>
                  </a>
                </p>
              </figcaption>
            </figure>
          </li>
          <li>
            <figure>
              <a href="http://www.twitter.com/standardista" target="_blank">
                <img src="img/estelle.png" alt="Estelle Weyl" />
              </a>
              <figcaption>
                <p>
                  <strong>Estelle Weyl</strong>
                  <br />Standardista
                  <br />
                  <a href="http://www.twitter.com/standardista" target="_blank">
                    <i class="fab fa-twitter-square"></i>
                  </a>
                </p>
              </figcaption>
            </figure>
          </li>
          <li>
            <figure>
              <a href="http://www.twitter.com/holtbt" target="_blank">
                <img src="img/brian.png" alt="Brian Holt" />
              </a>
              <figcaption>
                <p>
                  <strong>Brian Holt</strong>
                  <br />Microsoft
                  <br />
                  <a href="http://www.twitter.com/holtbt" target="_blank">
                    <i class="fab fa-twitter-square"></i>
                  </a>
                </p>
              </figcaption>
            </figure>
          </li>
          <li>
            <figure>
              <a href="http://www.twitter.com/willsentance" target="_blank">
                <img src="img/will.png" alt="Will Sentance" />
              </a>
              <figcaption>
                <p>
                  <strong>Will Sentance</strong>
                  <br />Codesmith
                  <br />
                  <a href="http://www.twitter.com/willsentance" target="_blank">
                    <i class="fab fa-twitter-square"></i>
                  </a>
                </p>
              </figcaption>
            </figure>
          </li>
          <li>
            <figure>
              <a href="http://www.twitter.com/sarah_edo" target="_blank">
                <img src="img/sarah.png" alt="Jen Kramer" />
              </a>
              <figcaption>
                <p>
                  <strong>Sarah Drasner</strong>
                  <br />Microsoft
                  <br />
                  <a href="http://www.twitter.com/sarah_edo" target="_blank">
                    <i class="fab fa-twitter-square"></i>
                  </a>
                </p>
              </figcaption>
            </figure>
          </li>
        </ul>
      </section>
      <section id="resources">
        <h1>
          Design Resources
          <small>(credit: Sarah Drasner)</small>
        </h1>
        <ul>
          <li>
            <a href="https://dribbble.com/" target="_blank">Dribbble</a>
          </li>
          <li>
            <a href="https://www.sketchapp.com/" target="_blank">SketchApp</a>
          </li>
          <li>
            <a href="https://gridbyexample.com/" target="_blank">Grid By Example</a>
          </li>
          <li>
            <a href="http://cssgridgarden.com/" target="_blank">CSS Grid Garden</a>
          </li>
          <li>
            <a href="https://webanimationworkshops.com/" target="_blank">Web Animation Workshops</a>
          </li>
          <li>
            <a href="https://color.adobe.com" target="_blank">color.adobe.com</a>
          </li>
          <li>
            <a href="https://uigradients.com/" target="_blank">uigradients.com</a>
          </li>
          <li>
            <a href="https://unsplash.com/" target="_blank">Unsplash</a>
          </li>
          <li>
            <a href="https://fontjoy.com/" target="_blank">FontJoy</a>
          </li>
          <li>
            <a href="https://www.shutterstock.com/" target="_blank">Shutterstock</a>
          </li>
        </ul>
      </section>
    </main>
  </q-page>
</template>

<script>
export default {
  name: 'Hamburger',

  components: {
    'exercise-header': require('components/ExerciseHeader').default
  },

  data() {
    return {
      expanded: false,
      instructions: `
:::
With a little warm up under our belts, let's move on to making a CSS-only hamburger button.

RESOURCES:
- Responsive, Pure CSS Off-Canvas Hamburger Menu: Building a progressively enhanced mobile menu that works without JavaScript
https://medium.com/@heyoka/responsive-pure-css-off-canvas-hamburger-menu-aebc8d11d793

- Tasty CSS-animated hamburgers
https://jonsuh.com/hamburgers/
(Consider swapping in one of these instead of the FontAwesome hamburger above)
:::
`
    }
  },
}
</script>

<style lang="css">
/* CSS hamburger button code, h/t
https://medium.com/@heyoka/responsive-pure-css-off-canvas-hamburger-menu-aebc8d11d793
Below is a starting navigation bar formatted for mobile and desktop. MQ is set to break where nav wraps once we've set up some typography... which we have not done yet. Trust the process :-)
*/

h1 {
  font-size: 2rem;
}
h2 {
  font-size: 1.5rem;
  line-height: normal;
}

header .row {
  display: flex;
  flex-flow: row nowrap;
}

.sr-only {
  position: absolute;
  width: 1px;
  height: 1px;
  padding: 0;
  margin: -1px;
  overflow: hidden;
  clip: rect(0, 0, 0, 0);
  border: 0;
}

.menu-toggle {
  color: #333;
  margin-right: 1rem;
  font-size: 2rem;
}
.menu-toggle:hover,
/* when element is tabbed */
.menu-toggle:focus {
  color: #c85028;
}

.main-menu {
  position: fixed;
  display: none;
  left: -200px;
  top: 50px;
  height: 100%;
  overflow-x: visible;
  overflow-y: auto;
  transition: left 0.3s ease;
  z-index: 999;
}
.main-menu ul {
  list-style: none;
  margin: 0;
  padding-top: 2.6rem;
  /* Sets the height of the menu at max
     on a mobile phone. */
  min-height: 100%;
  width: 200px;
  background-color: #1a1a1a;
  display: flex;
  flex-flow: column nowrap;
}
.main-menu a {
  /* makes the link area bigger and easily clickable */
  display: block;
  padding: 0.75em;
  color: white;
  text-decoration: none;
  border-bottom: 1px solid #383838;
}
.main-menu li:first-child a {
  border-top: 1px solid #383838;
}
.main-menu a:hover,
.main-menu a:focus {
  background-color: #333;
  text-decoration: none;
}
.main-menu .menu-close {
  position: absolute;
  right: 0;
  top: 0;
}
/* emulates a click event in CSS */
.main-menu:target {
  display: block;
  left: 0;
  outline: none;
}
.main-menu:target .menu-close {
  z-index: 1001;
}
.main-menu:target ul {
  position: relative;
  z-index: 1000;
  padding-inline-start: 0;
}
.main-menu:target + .backdrop {
  position: fixed;
  display: block;
  left: 0;
  top: 0;
  width: 100%;
  height: 100%;
  z-index: 998;
  background-color: rgba(0, 0, 0, 0.85);
  cursor: default;
}

main {
  border-top: 2px solid #dddddd;
  margin-top: 0.5rem;
}
nav ul {
  list-style: none;
  margin: 0;
}

nav a {
  display: block;
  padding: 0.75rem;
  text-decoration: none;
}

@media (min-width: 800px) {
  /* header and nav borders rearranged for desktop */
  header,
  main {
    border: none;
    margin: 0;
  }
  nav {
    border-top: 4px solid #9ea9c1;
    border-bottom: 1px solid #dddddd;
    padding: 0.3rem 0;
  }
  .menu-toggle,
  .main-menu .menu-close {
    display: none;
  }
  .main-menu {
    position: static;
    display: block;
  }
  .main-menu ul {
    padding: 0;
    height: auto;
    width: auto;
    background: none;
    display: block;
    overflow: hidden;
    text-align: center;
  }
  .main-menu li {
    display: inline-block;
  }
  .main-menu li:first-child a {
    border: none;
  }
  .main-menu a {
    color: #c85028;
    border: none;
    display: inline;
  }
  .main-menu a:hover,
  .main-menu a:focus {
    background: none;
    color: #7e64be;
    text-decoration: none;
  }

  nav ul {
    text-align: center;
  }
  /* display the li's horizontally */
  nav li {
    display: inline-block;
  }
  /* add cute divider after each li, but not the last one */
  nav li:not(:last-child)::after {
    content: " || ";
  }
  /* above style the same as
      nav li::after {
          content: " || ";
      }
      nav li:last-child::after {
        content: "";
    }
*/
  /* desktop assumes a pointer display */
  nav a {
    color: #c85028;
    border-bottom: none;
    display: inline;
  }
}
</style>
