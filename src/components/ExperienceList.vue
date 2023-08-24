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
    <template #dates>
      2021 2023
    </template>
    <template #location>Fresno, CA</template>
    <template #organization>AlphaWorks/Bitwise</template>
    <template #jobtitle>Apprentice Lead (Manager)</template>

    <p>Trained 36 apprentices across 3 apprenticeships in React/React-Native.</p>
    <ul>
      <li>React &amp; Native w/ TypeScript collaborative project hands on training</li>
      <li>Provided remote instruction focusing on collaborative team building</li>
      <li>Trained: HTML/CSS/JS, Agile Methodology, gitHub, debugging</li>
    </ul>
  </WelcomeItem>

  <WelcomeItem>
    <template #dates>
      2021 2023
    </template>
    <template #location>Fresno, CA</template>
    <template #organization>Tooling</template>
    <template #jobtitle>Tooling</template>

    This project is served and bundled with
    <a href="https://vitejs.dev/guide/features.html" target="_blank" rel="noopener">Vite</a>. The
    recommended IDE setup is
    <a href="https://code.visualstudio.com/" target="_blank" rel="noopener">VSCode</a> +
    <a href="https://github.com/johnsoncodehk/volar" target="_blank" rel="noopener">Volar</a>. If
    you need to test your components and web pages, check out
    <a href="https://www.cypress.io/" target="_blank" rel="noopener">Cypress</a> and
    <a href="https://on.cypress.io/component" target="_blank">Cypress Component Testing</a>.

    <br />

    More instructions are available in <code>README.md</code>.
  </WelcomeItem>

  <WelcomeItem>
    <template #dates>
      2021 2023
    </template>
    <template #location>Fresno, CA</template>
    <template #organization>Ecosystem</template>
    <template #jobtitle>Tooling</template>

    Get official tools and libraries for your project:
    <a href="https://pinia.vuejs.org/" target="_blank" rel="noopener">Pinia</a>,
    <a href="https://router.vuejs.org/" target="_blank" rel="noopener">Vue Router</a>,
    <a href="https://test-utils.vuejs.org/" target="_blank" rel="noopener">Vue Test Utils</a>, and
    <a href="https://github.com/vuejs/devtools" target="_blank" rel="noopener">Vue Dev Tools</a>. If
    you need more resources, we suggest paying
    <a href="https://github.com/vuejs/awesome-vue" target="_blank" rel="noopener">Awesome Vue</a>
    a visit.
  </WelcomeItem>

  <WelcomeItem>
    <template #dates>
      2021 2023
    </template>
    <template #location>Fresno, CA</template>
    <template #organization>Community</template>
    <template #jobtitle>Tooling</template>

    Got stuck? Ask your question on
    <a href="https://chat.vuejs.org" target="_blank" rel="noopener">Vue Land</a>, our official
    Discord server, or
    <a href="https://stackoverflow.com/questions/tagged/vue.js" target="_blank" rel="noopener"
      >StackOverflow</a
    >. You should also subscribe to
    <a href="https://news.vuejs.org" target="_blank" rel="noopener">our mailing list</a> and follow
    the official
    <a href="https://twitter.com/vuejs" target="_blank" rel="noopener">@vuejs</a>
    twitter account for latest news in the Vue world.
  </WelcomeItem>

  <WelcomeItem>
    <template #dates>
      2021 2023
    </template>
    <template #location>Fresno, CA</template>
    <template #organization>Support Vue</template>
    <template #jobtitle>Tooling</template>

    As an independent project, Vue relies on community backing for its sustainability. You can help
    us by
    <a href="https://vuejs.org/sponsor/" target="_blank" rel="noopener">becoming a sponsor</a>.
  </WelcomeItem>
</template>
