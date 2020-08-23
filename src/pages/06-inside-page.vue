<template>
  <q-page padding>
    <link rel="stylesheet" href="css/nav.css" />
    <link rel="stylesheet" href="css/inside.css" />

    <exercise-header
      label="06. Inside page"
      :expanded="expanded"
      :instructions="instructions"
      filename="06-inside-page"
    />

    <header>
      <div class="row">
        <a
          href="/06-inside-page#main-menu"
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
          href="/06-inside-page#main-menu-toggle"
          id="main-menu-close"
          class="menu-close"
          aria-label="Close main menu"
        >
          <span class="sr-only">Close main menu</span>
          <span class="fa fa-close" aria-hidden="true"></span>
        </a>
        <ul>
          <li><a href="/06-inside-page#">CSS Resources</a></li>
          <li><a href="/06-inside-page#">Design</a></li>
          <li><a href="/06-inside-page#">Videos</a></li>
          <li><a href="/06-inside-page#">Social Media</a></li>
          <li><a href="/06-inside-page#">Inspiration</a></li>
          <li><a href="/06-inside-page#">News</a></li>
          <li><a href="/06-inside-page#">Top Talent</a></li>
        </ul>
      </nav>
      <a
        href="/06-inside-page#main-menu-toggle"
        class="backdrop"
        tabindex="-1"
        hidden
      ></a>
    </header>

    <main>
      <article>
        <h1>
          <cite>Before You Code</cite>: Product success is part of the plan
        </h1>
        <img
          src="img/book.png"
          alt="Before You Code book cover."
          class="floatright"
        />
        <p>
          Your idea is going to be BIG. You just know it. But before you hire
          your favorite developer to go build it, take a step back. Creating a
          brand-new product is a risk; many of them fail within their first
          year. Is there a proven way to set yourself up for success?
        </p>
        <p>
          Yes! All it takes is some preparation. By taking the time to do
          upfront validation, planning and iterating before you build, you can
          avoid ideas that flop and create a product that exceeds expectations.
        </p>
        <h2>Execute each lesson using the accompanying workbook</h2>
        <p>
          Upon purchase you'll receive a confirmation email with instructions on
          how to download your workbook, as well as a notice when your physical
          copy has shipped.
        </p>
        <p>
          The workbook, an editable PDF file, is essential. It is full of
          activities and guidance for implementing at every step.
        </p>
        <h2>About the Authors</h2>
        <h3>Heather O'Neill</h3>
        <p>
          <img
            src="img/heather.png"
            alt="Heather O'Neill."
            class="circle"
          />Heather O'Neill is a product strategist and tech consultant with
          over a decade of experience creating meaningful products for the
          people who use them. At Pixels for Humans, Heather helps tech
          start-ups solve their toughest challenges and grow into mature,
          community-focused businesses, that center people over profits.
        </p>
        <p>
          A problem solver at heart, Heather also works with design teams to
          define problems, hypothesize solutions, and track success in their
          work. Heather is the recipient of the 2018 Women in Tech, Tech 10
          award in Rhode Island and has taught classes and workshops at Harvard
          Extension School, O’Reilly, UXPA International, and more.
        </p>
        <p>
          Heather is also the author of several video courses including Measured
          UX, her signature course for UX designers. The course trains designers
          on how to collect, refine, and analyze quantitative data as part of a
          UX design process. Students finish the course able to solve problems
          more effectively and track the impact of their design iterations.
        </p>
        <p>
          Heather earned a dual BA in mathematics and music at Northeastern
          University in Boston, graduating cum laude in 2006.
        </p>
        <h3>Jen Kramer</h3>
        <p>
          <img src="img/jen.png" alt="Jen Kramer." class="circle" />For nearly
          twenty years, Jen Kramer has been educating clients, colleagues,
          friends and graduate students about the meaning of a "quality
          website." Since 2000, she has built websites that are supportive of
          business and marketing goals in a freelance capacity and as part of an
          agency.
        </p>
        <p>
          Jen is a Lecturer at Harvard University Extension School in the
          Master's of Liberal Arts in Digital Media Design, teaching at least
          five courses per year, advising students, and assisting in curriculum
          design. She is a 2018 Shattuck Award winner, presented for excellence
          in teaching.
        </p>
        <p>
          Jen is also a prolific video author, creating over 35 training courses
          for Lynda.com (a division of LinkedIn Learning), O'Reilly Media,
          Aquent Gymnasium, osTraining, and Frontend Masters.
        </p>
        <p>
          She is also available for individual private tutoring, customized
          classroom training, and occasional freelance web design work.
        </p>
        <p>
          Jen earned a BS in biology at University of North Carolina at Chapel
          Hill and an MS in Internet Strategy Management at the Marlboro College
          Graduate School.
        </p>
      </article>
      <aside>
        <h3>What people are saying</h3>
        <i class="fas fa-book-open"></i>
        <blockquote>
          <p>
            Reading <cite>Before You Code</cite> has changed the way I work with
            clients entirely! I've seen an instant shift in the way they view
            the work I'm doing.
          </p>
          <p>
            If you are a freelancer, start-up or a larger company and you need a
            better understanding of how to build a great digital product and the
            value of planning first, then you need this book!!!
          </p>
          <cite
            >Ehi Aimiuwu<br />
            Founder and CEO at Geek Empowered<br />
            Host, Code Burnout and GeekEmpowered On Air
          </cite>
        </blockquote>
        <p>
          <a
            href="https://www.beforeyoucode.guide"
            target="_blank"
            class="button"
            >Purchase now</a
          >
        </p>
      </aside>
    </main>
  </q-page>
</template>

<script>
export default {
  name: "InsidePage",

  components: {
    "exercise-header": require("components/ExerciseHeader").default
  },

  data() {
    return {
      expanded: true,
      instructions: `
:::
I've given you book.html, an inside page layout for the website. It has its own stylesheet, inside.css. This stylesheet is purely "pretty" stuff -- there's nothing in it pertaining to layout.

Go back to layout.css and see if you can edit this stylesheet to apply to the book.html page.

Screenshots for the book page are included so you know how the page should look.

HINTS:

- Where are the flex containers/parents and the flex items/children?

- What layouts do you want at each dimension? How do they change?
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
