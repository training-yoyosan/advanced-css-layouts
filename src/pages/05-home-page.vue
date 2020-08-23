<template>
  <q-page padding>
    <link rel="stylesheet" href="css/nav.css" />

    <exercise-header
      label="05. Complex layouts"
      :expanded="expanded"
      :instructions="instructions"
      filename="05-home-page"
    />

    <header>
      <div class="row">
        <a
          href="/05-home-page#main-menu"
          id="main-menu-toggle"
          class="menu-toggle"
          aria-label="Open main menu"
        >
          <span class="sr-only">Open main menu</span>
          <span class="fa fa-bars" aria-hidden="true"></span>
        </a>
        <div class="logo">
          <h1><i class="fas fa-paint-brush"></i> LayOut Times</h1>
          <h2>Your Web Design Destination</h2>
        </div>
      </div>
      <nav id="main-menu" class="main-menu" aria-label="Main menu">
        <a
          href="/05-home-page#main-menu-toggle"
          id="main-menu-close"
          class="menu-close"
          aria-label="Close main menu"
        >
          <span class="sr-only">Close main menu</span>
          <span class="fa fa-close" aria-hidden="true"></span>
        </a>
        <ul>
          <li>
            <a href="/05-home-page#">CSS Resources</a>
          </li>
          <li>
            <a href="/05-home-page#">Design</a>
          </li>
          <li>
            <a href="/05-home-page#">Videos</a>
          </li>
          <li>
            <a href="/05-home-page#">Social Media</a>
          </li>
          <li>
            <a href="/05-home-page#">Inspiration</a>
          </li>
          <li>
            <a href="/05-home-page#">News</a>
          </li>
          <li>
            <a href="/05-home-page#">Top Talent</a>
          </li>
        </ul>
      </nav>
      <a
        href="/05-home-page#main-menu-toggle"
        class="backdrop"
        tabindex="-1"
        hidden
      ></a>
    </header>

    <main class="home">
      <section id="first">
        <h1>Jen’s Awesome Resources</h1>
        <article>
          <h2>Learn with Jen Kramer online at Harvard Extension</h2>
          <p>
            Join some of the many informative courses Jen teaches through the
            Harvard Extension School. Courses count towards bachelors and
            masters degree programs, certificates, or take a class for your own
            enrichment.
          </p>
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
            By taking the time to do upfront validation, planning and iterating
            before you build, you can avoid ideas that flop and create a product
            that exceeds expectations. Heather O'Neill and Jen Kramer's latest
            book,
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
            Get a head start on the latest responsive web design (RWD)
            techniques with this great list of resources.
          </p>
          <p>
            <a
              href="https://codepen.io/jen4web/post/rwd20readinglist"
              target="_blank"
            >
              Visit RWD 2.0 Reading List
              <i class="fas fa-paint-brush"></i>
            </a>
          </p>
        </article>
        <article>
          <img src="img/cssworkout.png" alt="CSS Workout" />
          <h2>Have you done your CSS workout for the day?</h2>
          <p>
            Nowhere is practice more important than with CSS layouts. For 15
            years, we’ve listened to students complain about CSS layouts, how
            hard they are to understand, and how things “don’t work” in the
            expected way. Now you can train daily to master them.
          </p>
          <p>
            <a href="http://www.cssworkout.guide" target="_blank">
              Visit
              <cite>CSS Workouts</cite> to start your routine!
              <i class="fas fa-paint-brush"></i>
            </a>
          </p>
        </article>
      </section>
      <section id="main">
        <h1>Main News</h1>
        <article>
          <img src="img/courses.png" alt="Frontend Masters classroom." />
          <h2>
            Advance Your Skills with In-Depth, Modern Front-End Engineering
            Courses
          </h2>
          <p>
            The best courses on the web, taught by industry leading experts!
          </p>
          <p>
            <a href="http://www.frontendmasters.com" target="_blank">
              Join now to continue your learning journey.
              <i class="fas fa-paint-brush"></i>
            </a>
          </p>
        </article>
        <article>
          <img
            src="img/bootcamp.png"
            alt="Frontend Masters Bootcamp."
            class="floatright"
          />
          <h2>Coming 2019 the Frontend Masters Bootcamp</h2>
          <p>
            Featuring instruction from Jen Kramer and Brian Holt, this
            incredible and free resource is everything you need to get started
            on being a web developer. Available late 2019.
          </p>
          <p>
            <a
              href="https://frontendmasters.github.io/bootcamp/"
              target="_blank"
            >
              Visit the Bootcamp website
              <i class="fas fa-paint-brush"></i>
            </a>
          </p>
        </article>
        <article>
          <h2>CSS-Tricks: why we love it!</h2>
          <p>
            Still one of the best resources on the web to bend CSS to your will,
            CSS-Tricks is jam packed with techniques, information and best
            practices.
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
          <p>
            Get immediate feedback on the code you type right in the browser!
          </p>
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
            <a href="https://gridbyexample.com/" target="_blank"
              >Grid By Example</a
            >
          </li>
          <li>
            <a href="http://cssgridgarden.com/" target="_blank"
              >CSS Grid Garden</a
            >
          </li>
          <li>
            <a href="https://webanimationworkshops.com/" target="_blank"
              >Web Animation Workshops</a
            >
          </li>
          <li>
            <a href="https://color.adobe.com" target="_blank"
              >color.adobe.com</a
            >
          </li>
          <li>
            <a href="https://uigradients.com/" target="_blank"
              >uigradients.com</a
            >
          </li>
          <li>
            <a href="https://unsplash.com/" target="_blank">Unsplash</a>
          </li>
          <li>
            <a href="https://fontjoy.com/" target="_blank">FontJoy</a>
          </li>
          <li>
            <a href="https://www.shutterstock.com/" target="_blank"
              >Shutterstock</a
            >
          </li>
        </ul>
      </section>
    </main>
  </q-page>
</template>

<script>
export default {
  name: "HomePage",

  components: {
    "exercise-header": require("components/ExerciseHeader").default
  },

  data() {
    return {
      expanded: false,
      instructions: `
:::
BOOM goes Bootstrap!!!

Check the chapter 5 folder for comps for how the site should look at extra large, large, medium, and small dimensions.

Use Flexbox, calc(), and custom properties to complete this task.

A good place to start is the chapter 4 answer. Remember that we had this logic:

\`\`\`css
.row {
	margin: 0;
	display: flex;
	flex-flow: row wrap;
	justify-content: space-between;
	--columns: 4;
}
[class*="col-"] {
  --width: 4;
  --initialbasis: calc(var(--width, 0) / var(--columns, 4) * 100%);
  --gap: calc((var(--columns) - var(--width)) * 1%);
  flex-basis: calc(var(--initialbasis) - var(--gap));
}
\`\`\`

In your case, do the following:

- What is "row" and "col-" in this HTML? Make sure the selectors reflect what you're doing. Remember flex containers/parents and flex items/children -- the relationship is critical!

- The designer said this is a 16-column layout, so let's work with that. What do we need to change?

- What if we want a different size gap?

- What changes in the media queries?


BONUS: Now that you've applied this to the major page layout, could you use this same logic to the developers column and its changes in layout?


RESOURCES:

There are so many resources for calc, custom properties, Flexbox, and these methodologies, I've listed them on their own page:
https://codepen.io/jen4web/post/rwd20readinglist
:::
`
    };
  }
};
</script>

<style lang="css">
/* grid system -- mobile first! */
main.home {
  display: flex;
  flex-flow: row wrap;
  justify-content: space-between;
  --columns: 16;
}
#devs ul {
  display: flex;
  flex-flow: row wrap;
  justify-content: space-between;
  --columns: 2;
}

section,
#devs ul li {
  --width: 16;
  --initialBasis: calc(var(--width, 0) / var(--columns, 16) * 100%);
  --gap-constant: 0.3rem;
  --gap: calc((var(--columns, 16) - var(--width, 0)) * var(--gap-constant));
  flex-basis: calc(var(--initialBasis) - var(--gap));
}
#devs ul li {
  --width: 1;
  --gap-constant: 2rem;
}

@media (min-width: 740px) {
  .floatleft {
    float: left;
    margin: 0 1rem 1rem 0;
  }
  .floatright {
    float: right;
    margin: 0 0 1rem 1rem;
  }
  main.home {
    --columns: 11;
  }
  #first {
    --width: 5;
  }
  #main {
    --width: 6;
  }
  #resources,
  #devs {
    --width: 11;
  }
  #devs ul {
    --columns: 5;
  }
}
@media (min-width: 950px) {
  main.home {
    --columns: 14;
  }
  #first {
    order: 0;
  }
  #main {
    order: 1;
  }
  #resources {
    --width: 3;
    order: 2;
  }
  #devs {
    --width: 14;
    order: 3;
  }
}
@media (min-width: 1200px) {
  main.home {
    --columns: 16;
  }
  #devs {
    --width: 2;
    order: 2;
  }

  #resources {
    --width: 3;
    order: 3;
  }

  #devs ul {
    --columns: 1;
  }
}
</style>
