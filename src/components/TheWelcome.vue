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
    <template #heading>Amplo conhecimento</template>

    A vasta gama de conhecimentos na área de tecnologia permite que softwares únicos sejam produzidos por mim.
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <ToolingIcon />
    </template>
    <template #heading>Ferramental</template>

    Esta página foi construída por mim utilizando a última versão do Vue. Possuo experiência com diversas ferramentas de desenvolvimento, dentre elas
    <a href="https://vitejs.dev/guide/features.html" target="_blank" rel="noopener">Vite</a>,
    <a href="https://code.visualstudio.com/" target="_blank" rel="noopener">VSCode</a> +
    <a href="https://github.com/johnsoncodehk/volar" target="_blank" rel="noopener">Volar</a>. 
    Se você precisa que seus sistemas possuam testes que garantam seu funcionamento, também tenho experiência com
    <a href="https://www.cypress.io/" target="_blank" rel="noopener">Cypress</a> e
    <a href="https://on.cypress.io/component" target="_blank">Cypress Component Testing</a> para a criação de testes automatizados.

    <br />

    Meu endereço no Github é <a href="https://github.com/n2oliver">https://github.com/n2oliver</a>.
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <EcosystemIcon />
    </template>
    <template #heading>Ambientes</template>
    Possuo conhecimento em ambientes de software portáteis com 
    <a href="https://www.docker.com/" target="_blank" rel="noopener">Docker</a> 
    para operação das aplicações em diversos ambientes.
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <SupportIcon />
    </template>
    <template #heading>Redes sociais</template>

    Deseja entrar em contato? Me siga nas redes sociais
    <ul>
      <li>Instagram: <a href="https://www.instagram.com/olivercastilho/" target="_blank" rel="noopener">olivercastilho</a></li>
      <li>Facebook: <a href="https://www.facebook.com/oliver.silvacastilho" target="_blank" rel="noopener">oliver.silvacastilho</a></li>
      <li>Twitter: <a href="https://twitter.com/castilho_oliver" target="_blank" rel="noopener">castilho_oliver</a></li>
      <li>Github: <a href="https://github.com/n2oliver" target="_blank" rel="noopener">n2oliver</a></li>
      <li>E-mail: <a href="mailto:olivercastilho@protonmail.com" target="_blank" rel="noopener">olivercastilho@protonmail.com</a></li>
    </ul>
  </WelcomeItem>
</template>

<script lang="ts">
VANTA.NET({
  el: "body",
  mouseControls: false,
  touchControls: true,
  gyroControls: true,
  minHeight: 200.00,
  minWidth: 200.00,
  scale: 1.00,
  scaleMobile: 1.00,
  color: 0xd7ebe1,
  backgroundColor: 0xf5f5f5,
  showDots: false
})
</script>