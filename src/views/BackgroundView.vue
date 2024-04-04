<template>
  <div>
    <section id="background" class="background">
      <h2><span>Background</span></h2>
      <div class="row">
        <div class="content">
          <p>
            Full name : Syifani Kurnia Mora <br />
            Nick name : Syifa<br/>
            Place, Date of Birth : Pangkalan Kerinci, 27 June 2003 <br />
            Gender : Female <br/>
            Age : 20 years old <br/>
            Religions : Moslem <br/>
          </p>
        </div>
        <div class="content">
          <p>
            Address : Air Dingin III street <br />
            Hobby : Drawing and painting <br />
            Email Address : syifanikurnia332@gmail.com <br />
            Favorite Food : Mie ayam bakso <br />
            Favorite Drink : Hazelnut Chocolate ice <br />
            Favorite Color : Blue and Pink
          </p>
        </div>
      </div>
    </section>
  </div>
</template>

<style scoped>
.background {
  display: flex;
  flex-direction: column;
  align-items: center;
}

.background .row {
  display: flex;
}

.background .row .content {
  flex: 1 0 37rem;
  padding: 0 3rem;
}

.background .row .content h2 {
  font-size: 2rem;
  margin-bottom: 1rem;
  color: var(--primary);
  font-family: var(--font);
  font-style: italic;
  text-align: center;
}
.background .content p {
  color: #000;
  margin-bottom: 0.8rem;
  font-weight: 500;
  font-size: 1.4rem;
  line-height: 2rem;
}
</style>
