<template>
  <div>
    <section class="project" id="project">
      <h2><span>Project Gallery</span></h2>
      <p>Here are some of the projects I worked on.</p>
      <div class="row">
        <div class="project-card">
          <div class="project-image">
            <img src="../assets/img/projects/1.jpeg" />
          </div>
        </div>
        <div class="project-card">
          <div class="project-image">
            <img src="../assets/img/projects/2.jpeg" />
          </div>
        </div>
        <div class="project-card">
          <div class="project-image">
            <img src="../assets/img/projects/3.jpeg" />
          </div>
        </div>
        <div class="project-card">
          <div class="project-image">
            <img src="../assets/img/projects/4.jpeg" />
          </div>
        </div>
        <div class="project-card">
          <div class="project-image">
            <img src="../assets/img/projects/5.jpeg" />
          </div>
        </div>
        <div class="project-card">
          <div class="project-image">
            <img src="../assets/img/projects/6.jpeg" />
          </div>
        </div>
        <div class="project-card">
          <div class="project-image">
            <img src="../assets/img/projects/7.jpg" />
          </div>
        </div>
        <div class="project-card">
          <div class="project-image">
            <img src="../assets/img/projects/8.jpeg" />
          </div>
        </div>
        <div class="project-card">
          <div class="project-image">
            <img src="../assets/img/projects/9.jpg" width="600px"/>
          </div>
        </div>
        <div class="project-card">
          <div class="project-image">
            <img src="../assets/img/projects/10.jpeg" width="600px"/>
          </div>
        </div>
        <div class="project-card">
          <div class="project-image">
            <img src="../assets/img/projects/11.jpeg" />
          </div>
        </div>
      </div>
    </section>
  </div>
</template>

<style scoped>
.project .row {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(30rem, 1fr));
  gap: 1.5rem;
  margin-top: 4rem;
}

.project .project-card {
  text-align: center;
  padding: 2rem;
}

.project .project-image img {
  height: 25rem;
}

</style>
