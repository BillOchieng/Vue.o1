<script setup>
import WelcomeItem from './WelcomeItem.vue'
import DocumentationIcon from './icons/IconDocumentation.vue'
import ToolingIcon from './icons/IconTooling.vue'
import EcosystemIcon from './icons/IconEcosystem.vue'
import CommunityIcon from './icons/IconCommunity.vue'
import SupportIcon from './icons/IconSupport.vue'
</script>

<template>
  <WelcomeItem>
    <template #icon>
      <DocumentationIcon />
    </template>
    <h1>courses</h1>
    <template #heading>COMPUTER SCIENCE</template>
    Professors Jumadinova (Chair), Bonham-Carter, Kapfhammer, Luman

    Computer Science focuses on computational theory and the rich interplay between computer hardware and software.
    Students use scientific and design-centric approaches to solve computational problems and to create and evaluate
    realistic computer and computer-based systems.

    The study of computer science leads to and requires the ability to analyze ideas, to think logically, and to
    communicate ideas clearly and concisely. In this way, study of computer science contributes to the foundation of an
    excellent liberal arts education.


    <a href="https://www.cs.allegheny.edu/teaching/bulletin/#cmpsc" target="_blank" rel="noopener">Computer Science
      Learning Outcomes</a>
    Demonstrate and be able to communicate the knowledge of data types, algorithms, and mathematical principles behind
    discrete objects.
    Use scientific and theoretical methods to design, implement, evaluate, deploy, improve, maintain, and document
    software and hardware systems.
    Apply and articulate key concepts from a specialization area where the interconnection between software and hardware
    is important and evident.
    Able to communicate technical details of the produced software and hardware artifacts both in writing and orally.

  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <ToolingIcon />
    </template>
    <template #heading>INFORMATICS</template>


    <a href="https://www.cs.allegheny.edu/teaching/bulletin/#infm" target="_blank" rel="noopener">These are the
      courses</a>. The
    MAJOR/MINOR
    <a href="https://code.visualstudio.com/" target="_blank" rel="noopener">VSCode</a> +
    <a href="https://github.com/johnsoncodehk/volar" target="_blank" rel="noopener">Volar</a>. If
    you need to test your components and web pages, check out
    <a href="https://www.cypress.io/" target="_blank" rel="noopener">Cypress</a> and
    <a href="https://on.cypress.io/component" target="_blank">Cypress Component Testing</a>.

    <br />

    More instructions are available in <code>README.md</code>.
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <EcosystemIcon />
    </template>
    <template #heading>DATA SCIENCE</template>

    Professors Jumadinova (Chair), Bonham-Carter, Graber, Green, Kapfhammer, Luman

    <p>Data Science <a href="https://www.cs.allegheny.edu/teaching/bulletin/#ds" target="_blank"
        rel="noopener">courses</a>, focuses on the study of
      integrated principles and methods to analyze complex big data for decision
      making, prediction, modeling, and data management. Students examine social and human contexts and ethical
      implications
      of how data are collected, analyzed, and utilized in diverse areas.</p>

    <h2>Data Science Learning Outcomes</h2>
    <P>Effectively collects, organizes, analyzes and interprets both structured and unstructured datasets from diverse
      sources.
      Can effectively and ethically use statistical data analysis techniques, modern machine learning algorithms, and
      state-of-the-art software tools and programming environments to design, build, evaluate, and deploy new predictive
      models.
      Demonstrates and articulates the value of subject matter expertise in domains that apply data science techniques.
      Can clearly and persuasively communicate the results of data analysis including critical examination and reflection
      on the ethical implications of such analysis
      .</P>

    <a href="https://router.vuejs.org/" target="_blank" rel="noopener">Vue Router</a>,
    <a href="https://test-utils.vuejs.org/" target="_blank" rel="noopener">Vue Test Utils</a>, and
    <a href="https://github.com/vuejs/devtools" target="_blank" rel="noopener">Vue Dev Tools</a>. If
    you need more resources, we suggest paying
    <a href="https://github.com/vuejs/awesome-vue" target="_blank" rel="noopener">Awesome Vue</a>
    a visit.
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <CommunityIcon />
    </template>
    <template #heading>SOFTWARE ENGINEERING</template>

    Software Engineering Learning Outcomes
    <a href="https://www.cs.allegheny.edu/teaching/bulletin/#se" target="_blank" rel="noopener">courses</a>, While working
    in a team, can effectively design, implement, evaluate, improve, and document a solution to a problem delivered as a
    maintainable software system.
    Demonstrates competency in the theories, models, and practices of project domains that require the engineering of
    software.
    Can effectively manage and predict the cost, scope, and deadline of a software engineering project.
    Uses effective oral and written communication methods to explain both the technical and product-use details of a
    software artifact.
    <a href="https://stackoverflow.com/questions/tagged/vue.js" target="_blank" rel="noopener">StackOverflow</a>. You
    should also subscribe to
    <a href="https://news.vuejs.org" target="_blank" rel="noopener">our mailing list</a> and follow
    the official
    <a href="https://twitter.com/vuejs" target="_blank" rel="noopener">@vuejs</a>
    twitter account for latest news in the Vue world.
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <SupportIcon />
    </template>
  <template #heading>DEPARTMENT PROGRAMS</template>

  These are the courses that are important for a qualified Gheny graduate
  <a href="https://www.cs.allegheny.edu/teaching/bulletin/#courses" target="_blank" rel="noopener">relevant todo</a>.
</WelcomeItem></template>
