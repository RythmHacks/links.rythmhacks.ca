<script>
export default {
  data() {},
  methods: {
    onClick(link) {
      window.open(link, "_blank");
    },
    }
}
</script>

<template>
  <div className="card">
    <div id="one">
      <img src="./assets/logosmall.png" className="ml-auto mr-auto w-[40%] rounded-full cursor-pointer hover:scale-105 duration-300" @click="onClick('https://www.rythmhacks.ca/')"/>
      <h1 className="font-bold text-center mt-8">RythmHacks</h1>
      <p className="text-[1.25rem] text-center mt-6">Here are some important links and resources for RythmHacks!</p>
    </div>
    <div id="two">
      <button @click="onClick('https://www.rythmhacks.ca/')">
        Check out our cool website!
        <i class="bi bi-arrow-up-right-square"></i>
      </button>
      <button @click="onClick('https://medium.com/@rythmhacks')">
        Read some blog posts!
        <i class="bi bi-chat-left-text"></i>
      </button>
      <button @click="onClick('https://www.instagram.com/rythm.hacks/')" className="hover:border-[#D62976] hover:text-[#F6D373]">
        Instagram
        <i class="bi bi-instagram"></i>
      </button>
      <button @click="onClick('https://www.linkedin.com/company/rythmhacks/')" className="hover:border-[#0C63BC] hover:text-[#0C63BC]">
        LinkedIn
        <i class="bi bi-linkedin"></i>
      </button>
      <button @click="onClick('https://twitter.com/rythmhacks/')" className="hover:border-[#1C9CEA] hover:text-[#1C9CEA]">
        Twitter
        <i class="bi bi-twitter"></i>
      </button>
      <button @click="onClick('https://github.com/RythmHacks')">
        GitHub
        <i class="bi bi-github"></i>
      </button>
      <button @click="onClick('mailto:rythmhacks@gmail.com')">
        Got a question? Email us!
        <i class="bi bi-envelope"></i>
      </button>
      <p className="text-center opacity-60">
        Made with <a href='https://vuejs.org/' class="text-[#43D292]">Vue</a>, <a href='https://tailwindcss.com/' class="text-[#39BCF8]">Tailwind</a>, and 🐒🧠
        <!-- <br/>--- -->
        <br/>© RythmHacks 2022-23
      </p>
    </div>
  </div>
</template>