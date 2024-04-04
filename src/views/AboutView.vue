<template>
  <div>
    <section id="about" class="about">
      <h2><span>About Me</span></h2>
      <div class="row">
        <div class="about-img">
          <img
            src="../assets/img/photo.png"
            width="300px"
            height="520px"
            alt=""
          />
        </div>
        <div class="content">
          <p>
            Saya memiliki semangat yang tinggi dalam lukisan, ilustrasi, desain
            cetak dan obat-obatan. Tujuan saya adalah untuk berkontribusi di
            dunia media digital dan teknologi. Saya ingin sekali bekerja sama
            dengan orang-orang dan perusahaan yang mau memberi kesempatan untuk
            menampilkan gaya saya yang minimalis.
          </p>
        </div>
      </div>
    </section>
  </div>
</template>

<style scoped>
.about .row {
  display: flex;
  padding: 0 10rem;
}
.about .row .about-img {
  flex: 1 1 45rem;
}

.about .row .content {
  flex: 1 1 30rem;
  padding: 0 1rem;
}

.about .row .content h3 {
  font-size: 3rem;
  margin-bottom: 1rem;
  color: var(--primary);
  font-family: var(--font);
  font-style: italic;
}

.about .content p {
  color: #000;
  margin-bottom: 0.8rem;
  font-weight: 500;
  font-size: 1.4rem;
  line-height: 2rem;
  padding: 4rem 0;
}
</style>
