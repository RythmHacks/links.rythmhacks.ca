<script>
export default {
  data() {},
  methods: {
    onClick() {
      window.open("https://www.rythmhacks.ca/", "_blank");
    },
    }
}
</script>

<template>
  <div className="card">
    <div id="one">
      <img src="./assets/logosmall.png" className="ml-auto mr-auto w-[40%] rounded-full cursor-pointer hover:scale-105 duration-300" @click="onClick"/>
      <h1 className="font-bold text-center mt-8">RythmHacks</h1>
      <p className="text-[1.25rem] text-center mt-6">Here are some important links and resources for RythmHacks!</p>
    </div>
    <div id="two">
      <button href="https://forms.gle/4Az622QCitExXvXx6" target="_blank" rel="noreferrer">
        Apply to be an organizer!
        <i class="bi bi-people"></i>
      </button>
      <button href="https://www.rythmhacks.ca/" target="_blank" rel="noreferrer">
        Check out our cool website!
        <i class="bi bi-arrow-up-right-square"></i>
      </button>
      <button href="https://www.instagram.com/rythm.hacks/" target="_blank" rel="noreferrer">
        Instagram
        <i class="bi bi-instagram"></i>
      </button>
      <button href="https://www.linkedin.com/company/rythmhacks/" target="_blank" rel="noreferrer">
        LinkedIn
        <i class="bi bi-linkedin"></i>
      </button>
      <button href="https://twitter.com/rythmhacks" target="_blank" rel="noreferrer">
        Twitter
        <i class="bi bi-twitter"></i>
      </button>
      <button href="https://github.com/RythmHacks" target="_blank" rel="noreferrer">
        GitHub
        <i class="bi bi-github"></i>
      </button>
      <p className="text-center opacity-60">
        Made with <a href='https://vuejs.org/' class="text-[#43D292]">Vue</a>, <a href='https://tailwindcss.com/' class="text-[#39BCF8]">Tailwind</a>, and 🐒🧠
        <!-- <br/>--- -->
        <br/>RythmHacks 2022-23
      </p>
    </div>
  </div>
</template>