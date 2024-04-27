<script setup lang="ts">
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
    <template #heading>work experience</template>

    <a href="https://vuejs.org/" target="_blank" rel="noopener"></a>Pernah bekerja di suatu perusahaan pertamina Hulu Rokan pada tahun 2007-2013
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <ToolingIcon />
    </template>
    <template #heading>Skill</template>

    Marketing, Fast-moving Consumer Goods, Corporate sales account management, Experience in retail and manu facturing sales.
    <a href="https://vitejs.dev/guide/features.html" target="_blank" rel="noopener"></a>
    <a href="https://code.visualstudio.com/" target="_blank" rel="noopener"></a>
    <a href="https://github.com/johnsoncodehk/volar" target="_blank" rel="noopener"></a>
    <a href="https://www.cypress.io/" target="_blank" rel="noopener"></a> 
    <a href="https://on.cypress.io/component" target="_blank" rel="noopener"
      ></a
    >

    <br />

     <code></code>
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <EcosystemIcon />
    </template>
    <template #heading>Education Background</template>

    BA sales and Commerce:Undergrad Teaching Assistant for intro for intro to Econamics
    <a href="https://pinia.vuejs.org/" target="_blank" rel="noopener"></a>
    <a href="https://router.vuejs.org/" target="_blank" rel="noopener"></a>
    <a href="https://test-utils.vuejs.org/" target="_blank" rel="noopener"></a>
    <a href="https://github.com/vuejs/devtools" target="_blank" rel="noopener"></a>
    <a href="https://github.com/vuejs/awesome-vue" target="_blank" rel="noopener"></a>
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <CommunityIcon />
    </template>
    <template #heading>Reference</template>

    Atri Putra:CFO, Thinklytics (62-879-523-321)
    <a href="https://chat.vuejs.org" target="_blank" rel="noopener"></a>
    <a href="https://stackoverflow.com/questions/tagged/vue.js" target="_blank" rel="noopener"
      ></a
    >
    <a href="https://news.vuejs.org" target="_blank" rel="noopener"></a> 
    <a href="https://twitter.com/vuejs" target="_blank" rel="noopener"></a>
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <SupportIcon />
    </template>
    <template #heading>Contact</template>

    * Shintabeela@gmail.com  * +628-189-321  *3310 W Braker Ln Austin
    <a href="https://vuejs.org/sponsor/" target="_blank" rel="noopener"></a>
  </WelcomeItem>
</template>
