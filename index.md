---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
title: Home
nav_order: 1
description: "Human Centered Design Dokumentation"
---
# Human Centered Design

Das ist die Dokumentation des Modul Human Centered Design von den studierenden Pascale Anderegg, Nicole Watrinet, Marc Hatt und Matthias Koch. Es zeigt die Erarbeitung eines Produkts unter der Beachtung des Human Centered Design Prozess.

Herzlichen Dank and die Dozierenden, Armin Egli und Fabian Scheiwiller. 

<button class="btn js-toggle-dark-mode">night mode</button>

<script>
const toggleDarkMode = document.querySelector('.js-toggle-dark-mode')
const cssFile = document.querySelector('[rel="stylesheet"]')
const originalCssRef = cssFile.getAttribute('href')
const darkModeCssRef = originalCssRef.replace('just-the-docs.css', 'dark-mode-preview.css')

addEvent(toggleDarkMode, 'click', function(){
  if (cssFile.getAttribute('href') === originalCssRef) {
    cssFile.setAttribute('href', darkModeCssRef)
  } else {
    cssFile.setAttribute('href', originalCssRef)
  }
})
</script>
