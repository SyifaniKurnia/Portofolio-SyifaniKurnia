<template>
  <div>
    <section id="experience" class="experience">
      <h2><span>Experience</span></h2>

      <div class="row">
        <div class="content">
          <h3>Sutradara 2 Film Sekolah <br><i>“Kisah Sahabat -2020”</i></h3>
          <p>
            Saat itu, saya dan teman-teman tergabung dalam ekskul film dan ingin
            membuat film pendek untuk festival film antar sekolah. Saya terpilih
            sebagai sutradara 2 dalam project tersebut.
          </p>
        </div>
        <div class="content">
          <h3>Peserta FLS2N <br><i>“Seni lukis batik - 2015 <br>Seni kriya - 2016”</i></h3>
          <p>
            Saya belajar banyak tentang seni dan budaya Indonesia, mengembangkan
            kreativitas dan keterampilan teknis, dan mendapatkan kesempatan
            untuk berkompetisi dengan talenta muda dari berbagai daerah.
          </p>
        </div>
        <div class="content">
          <h3>Bekerja di Apotek</h3>
          <p>
            Saat Gapyear, saya merasa jenuh dengan aktivitas harian saya
            menjelang utbk untuk itu saya ingin mencoba hal baru dengan bekerja
            di sebuah apotek. Saya dapat belajar banyak tentang obat-obatan dan
            penggunaannya. Saya bekerja selama 1 tahun.
          </p>
        </div>
      </div>
    </section>
  </div>
</template>

<style scoped>
.experience h3 {
  color: var(--primary);
  font-family: var(--font);
  font-size: 1.4rem;
}

.experience h3::after {
  content: "";
  display: block;
  width: 50%;
  height: 2px;
  background-color: var(--primary);
  margin-top: 1rem;
  left: 25%;
}

.experience p {
  font-size: 1rem;
  line-height: 2rem;
}

.experience .row {
  display: flex;
  flex-wrap: wrap;
  margin-top: 5rem;
  justify-content: center;
}

.experience .row .content {
  flex: 1 1 auto;
  max-width: 33.33%;
  padding: 2rem;
  text-align: center;
}

@media (max-width: 768px) {
  .experience .row .content {
    flex: 1 1 auto;
    max-width: 100%;
  }
}

.experience .content h3::after {
    width: 100%;
    left: 0;
}
</style>
