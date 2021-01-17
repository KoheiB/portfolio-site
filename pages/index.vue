<template lang="pug">
  div
    header
    main
      div#about.section
        h1 About
      div#works.section
        h1 Works
      div#skill.section
        h1 Skill
      div#contact.section
        h1 Contact
    footer
</template>

<script>
export default {}
</script>

<style>
h1 {
  font-size: 3.56rem;
}
.section {
  width: 100%;
  min-height: 100vh;
}
#about {
  background-color: pink;
}
#works {
  background-color: brown;
}
#skill {
  background-color: purple;
}
#contact {
  background-color: gray;
}

/* Sample `apply` at-rules with Tailwind CSS
.container {
@apply min-h-screen flex justify-center items-center text-center mx-auto;
}
*/
</style>
