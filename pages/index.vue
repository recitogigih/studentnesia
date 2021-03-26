<template>
  <div>
    <section class="hero is-fullheight-with-navbar">
      <div class="hero-body">
        <div class="container">
          <nav class="level">
            <div class="level-item has-50-width">
              <div>
                <p class="title is-1 has-text-dark"> Selamat datang di <b class="has-text-info"> Studentnesia</b> </p>
                <br>
                <p>Program persiapan dan mentoring studi S1, S2 dan S3 ke dalam dan luar negeri melalui Studentnesia Mentorship dan persiapan test bahasa asing seperti IELTS/TOEFL/TOEIC melalui Studentnesia Testa bersama 100+ mentor Beasiswa berpengalaman kami.</p>
              </div>
            </div>
            <div class="level-item has-text-centered has-50-width">
              <img src="/bannerimg.svg" alt="">
            </div>
          </nav>
          <nav class="level">
            <div class="level-item has-text-centered">
              <div>
                <p class="title has-text-dark">456</p>
                <p class="heading has-text-info"><b>Mentor</b></p>
              </div>
            </div>
            <div class="level-item has-text-centered">
              <div>
                <p class="title has-text-dark">123</p>
                <p class="heading has-text-info"><b>Student</b></p>
              </div>
            </div>
            <div class="level-item has-text-centered">
              <div>
                <p class="title has-text-dark">456</p>
                <p class="heading has-text-info"><b>Batch</b></p>
              </div>
            </div>
            <div class="level-item has-text-centered">
              <div>
                <p class="title has-text-dark">1,789</p>
                <p class="heading has-text-info"><b>Alumnus</b></p>
              </div>
            </div>
          </nav>
        </div>
        <!-- <hr> -->
      </div>
    </section>

    <section class="hero is-medium is-info is-bold">
      <div class="hero-body">
        <div class="container">
          <div class="columns is-vcentered">
            <div class="column is-3">
              <img src="/logo/logo-studentnesia-mentorship-white.png" alt="">
            </div>
            <div class="column is-9" style="border-left:3px solid white">
              <h1 class="title is-3 ">
                Raih Mimpimu Untuk Studi di Universitas Ternama di Dunia
              </h1>
              <h2 class="subtitle">
               Studentnesia Mentorship memiliki lebih dari 100 mentor berpengalaman yang telah menyelesaikan studi S2 dan S3 mereka di kampus-kampus ternama dunia. Studentnesia Mentorship memiliki kurikulum yang disusun oleh tim profesional yang akan membantumu menembus kampus impianmu. Program Studentnesia Mentorship meliputi konsultasi jurusan dan minat, live coaching bersama alumni kampus tujuan hingga review essay lamaran beasiswa. 
              </h2>
            </div>
          </div>

        </div>
      </div>
    </section>
    <section class="hero is-default ">
      <div class="hero-body">
        <div class="container">
          <p class="title is-2 has-text-dark has-text-centered"> Our Mentor </p> <br>
          <div class="columns is-mobile">
            <div class="column is-three-fifths is-offset-one-fifth">
              <div class="columns">
                <Mentor v-for="mentor in mentors" :key="mentor.id" :photo="mentor.photo" :nama="mentor.nama" />
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>


    <section class="hero is-default">
      <div class="hero-body">
        <div class="container">
          <p class="title is-2 has-text-dark has-text-centered">Scholarship <br>Mentoring Program </p> <br>
          <div class="columns">
            <Card />
            <Card />
            <Card />
            <Card />
          </div>
        </div>
      </div>
    </section>

    <section class="hero is-medium is-default">
      <div class="hero-body">
        <div class="container">
          <p class="title is-2 has-text-dark has-text-centered mb-6">Another studentnesia services<br>
            <div class="columns">
              <div class="column is-3">
                <div class="card">
                  <div class="card-content">
                    <p class="title is-4">
                      Toefl Preparation
                    </p><br>
                    <button class="button is-info is-small is-rounded">Detail</button>
                  </div>
                </div>
              </div>
              <div class="column is-3">
                <div class="card">
                  <div class="card-content">
                    <p class="title is-4">
                      Toeic Preparation
                    </p><br>
                    <button class="button is-info is-small is-rounded">Detail</button>
                  </div>
                </div>
              </div>
               <div class="column is-3">
                <div class="card">
                  <div class="card-content">
                    <p class="title is-4">
                      Proof Reading
                    </p><br>
                    <button class="button is-info is-small is-rounded">Detail</button>
                  </div>
                </div>
              </div>
               <div class="column is-3">
                <div class="card">
                  <div class="card-content">
                    <p class="title is-4">
                      Document Preparation
                    </p><br>
                    <button class="button is-info is-small is-rounded">Detail</button>
                  </div>
                </div>
              </div>
            </div>
        </div>
      </div>
    </section>

    <section class="hero is-medium is-default">
      <div class="hero-body">
        <div class="container">
          <p class="title is-2 has-text-dark has-text-centered mb-6">What do they say<br>
            <div class="columns">
              <div class="column is-half is-offset-one-quarter">
                <div class="card">
                  <div class="card-content">
                    <center>
                      <img src="/mentor/mentor1.jpg" style="width:90px;height:90px;object-fit:cover;border-radius:35px;"
                        alt="">
                    </center>
                    <p class="subtitle has-text-centered mb-6">
                      Jeff Atwood <br>
                      <small>Batch 23 alumnus</small>
                    </p>
                    <p class="title has-text-centered">
                      “There are two hard things in computer science: cache invalidation, naming things, and off-by-one
                      errors.”
                    </p><br>
                  </div>
                </div>
              </div>
            </div>
        </div>
      </div>
    </section>
  </div>
</template>

<script>
  import Card from '../components/cardProgram.vue'
  import Mentor from '../components/cardMentor.vue'

  export default {
    components: {
      Card,
      Mentor
    },
    data() {
      return {
        mentors: [{
            id: 1,
            nama: "Adeline Wayne",
            photo: "mentor/mentor1.jpg",

          },
          {
            id: 2,
            nama: "Elena May",
            photo: "mentor/mentor2.jpg",

          },
          {
            id: 3,
            nama: "Merry Washington",
            photo: "mentor/mentor3.jpg",

          },
        ]
      }
    },

  }

</script>


<style>
  .has-50-width {
    width: 50%;
  }

  .has-text-dark {
    color: #9f9f9f !important;
  }

  .card {
    background-color: white;
    border-radius: 0.25rem;
    box-shadow: 0 0.5em 1em -0.125em rgb(10 10 10 / 10%), 0 0px 0 1px rgb(10 10 10 / 2%);
    color: #4a4a4a;
    max-width: 100%;
    overflow: hidden;
    position: relative;
    border-radius: 12px;
  }

</style>
