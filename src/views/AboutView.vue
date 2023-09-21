<style scoped>
table, th, td {
  border: 1px solid green;
}
</style>

<template>
  <div class="about">
    <h2>My Education, Experience and Skills:</h2>
    <table style ="width:800px">
      <tr>
        <td>Education</td>
        <td>Experience</td>
        <td>Skills</td>
      </tr>
      <tr>
        <td>Bachelor of IT</td>
        <td>2 Years at Google</td>
        <td>Vue Framework</td>
      </tr>
      <tr>
        <td>Masters in Web Development</td>
        <td>3 Years at Valve</td>
        <td>Html, Css, and JavaScript</td>
      </tr>
    </table>
  </div>
</template>

<style>
@media (min-width: 1024px) {
  .about {
    min-height: 100vh;
    display: flex;
    align-items: center;
  }
}
</style>
