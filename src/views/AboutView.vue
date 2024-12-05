<script>
export default {
  data() {
    return {
      activeTab: 1,
      tech: [
        {
          id: 1,
          name: "HTML",
          imageUrl: "https://cdn-icons-png.flaticon.com/512/1051/1051277.png",
          status: "Advanced",
        },
        {
          id: 2,
          name: "CSS",
          imageUrl: "https://cdn-icons-png.flaticon.com/512/732/732190.png",
          status: "Advanced",
        },
        {
          id: 4,
          name: "Javascript",
          imageUrl:
            "https://cdn.icon-icons.com/icons2/2415/PNG/512/javascript_original_logo_icon_146455.png",
          status: "Intermediate",
        },
        {
          id: 5,
          name: "C#",
          imageUrl:
            "https://img.icons8.com/?size=100&id=55205&format=png&color=6A0D8E",
          status: "Intermediate",
        },
        {
          id: 6,
          name: ".NET",
          imageUrl:
            "data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAOEAAADhCAMAAAAJbSJIAAAAh1BMVEVRK9T///9EEtLMxfBKHtOai+M/ANFCDdLk4PfSy/LZ0/RPKNRYM9bx7/tHGdLJwvCgkeWyp+mVhOLt6vpMI9Pf2vZ+aN2qnOiOfOCrn+iHc9/n4/jBt+7b1fWKd+B1XdtkRti6r+z5+P1yWNtePdeTguJ6YtxnS9htUtr29P23q+upneeDbt7xWqHzAAADn0lEQVR4nO3a7VraMBiA4bSUFKgUxagoooKfOM//+KaMvgk0NFxOXM2e+yeWJc+sTWlQCgAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAA4H+SpSJrOMxUB5Xuq2XaaOONQaV/5L8OvOx31vrj3WOYq+qwE+egct5p0n9PNJN+4zGO18Mkpv3EOip2HZYdV8fMcvtqPk0a6ff/hMvmQxy9fNfoX1c40OHCgVvYCxde7F149g2Fyc2uP8VoChfpjvM0msLkesco8RQm9yb2wlP/xebzhe26ln648K5KocLhyKOzWg87W6/a39nW0SffsB6ueBfFUGFf73lPk2cy0HjrPQe6p6kXznznaahwsO8ZVhzJQN2mu8SvUy9MJp6RoyiU2S6y+nkaReFYhvYsilEU3tjztb4oRlHYtWMPaxebKAovtF2cL9Otw6IovCz1UEZ/2LrYRFJobmX0s63zNIrC95um/FqGf9y8w4ilsEgXMv7mohhLocpuZPzRxnkaTaHSA5nAk7soxlNY7FgU4ylUpaQkJ86iGP70VOd9WvDvC5W2z0Dv7MUmVLg4rRle+RJbUGieZQrOoviZpxi+T2FtKFTpq8zBPuaPqlDl9ubNVOdpXIXmSSbRqc7TuAqVts/DztdXi8gKCyOzWK57IitU2aNM4/XPoviZwscWFyo9k3ncrc7TUGFv3N12/Ox78NqWQmcevdXFJnxPk9V4t7HaUuhuqHQ/Xo/ovrTi3LypIspC8yIz6esoC1U+l6mcZ1EWKr2sfvK+KGbdCAuzN5nLPI+yUOmOTOa5HMdYWBQymamexFio7C8u6T5FWaj0mUznJc7C4kGmM4qzUKX174q0vrAwZuOOuLlQ6dMfVljkxfnbg/skM1Bo7n9WoTla9UxvbUyg0N2Oair0fXryfoA6bKGRC8dEakKFRWm3oxoKe5OxR3d7o/XQhc5jQnmcHSpU2dU+hTuc1x57H7Qwm9ihR9WeRLBQ6c3vFLW5sHT+pGRjKVxYqB9TmNrHoMli/0JVdt1Jt7mwPLFDy3c59yhU2g1pc2FxZ4c+rv71fQqN88ZWFzq7SlPZN9unUKXOb3/W5kKl5+tZ2qU4HS2HK8tfDQPq6XBt2XF2htPBcthk8eQpXFQ/HB/iri1/uZ6djd60sxCn1aZ043i57F1vfB8s9WxuBza6C/nhYW68TZnnqf/r+AAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAA/Ei/AfHYTPUXy/PDAAAAAElFTkSuQmCC",
          status: "Intermediate",
        },
        {
          id: 7,
          name: "ReactVite",
          imageUrl: "https://vetores.org/d/vite-js-logo.svg",
          status: "Advanced",
        },
        {
          id: 9,
          name: "NodeJS",
          imageUrl:
            "https://cdn.iconscout.com/icon/free/png-256/free-node-js-1174925.png",
          status: "Beginner",
        },
        {
          id: 10,
          name: "Tailwind",
          imageUrl:
            "https://upload.wikimedia.org/wikipedia/commons/d/d5/Tailwind_CSS_Logo.svg",
          status: "Intermediate",
        },
        {
          id: 11,
          name: "Bootstrap",
          imageUrl:
            "https://getbootstrap.com/docs/5.2/assets/brand/bootstrap-logo-shadow.png",
          status: "Intermediate",
        },
        {
          id: 12,
          name: "ReactJS",
          imageUrl:
            "https://cdn4.iconfinder.com/data/icons/logos-3/600/React.js_logo-512.png",
          status: "Beginner",
        },
      ],
      tools: [
        {
          id: 1,
          name: "Git",
          imageUrl:
            "https://git-scm.com/images/logos/downloads/Git-Icon-1788C.png",
          status: "Version Control",
        },
        {
          id: 2,
          name: "GitHub",
          imageUrl: "https://cdn-icons-png.flaticon.com/512/25/25231.png",
          status: "Git Hosting",
        },
        {
          id: 3,
          name: "NPM",
          imageUrl:
            "https://cdn.iconscout.com/icon/free/png-256/free-npm-3-1175132.png",
          status: "Package Manager",
        },
        {
          id: 4,
          name: "Vercel",
          imageUrl:
            "https://img.icons8.com/?size=100&id=66763&format=png&color=000000",
          status: "Web Sites Hosting",
        },
        {
          id: 5,
          name: "SQL Server",
          imageUrl:
            "https://img.icons8.com/?size=100&id=laYYF3dV0Iew&format=png&color=000000",
          status: "Data Base",
        },
        {
          id: 6,
          name: "Figma",
          imageUrl:
            "https://img.icons8.com/?size=100&id=zfHRZ6i1Wg0U&format=png&color=000000",
          status: "Designer",
        },
      ],
    };
  },
};
</script>
<template>
  <div
    class="bg-[#1e1e1f] px-5 py-5 md:px-12 md:py-10 text-left border border-[#383838] rounded-3xl text-purple-50 mx-3 mb-5"
  >
    <article data-page="about">
      <header>
        <div
          class="text-2xl font-bold text-white mb-5 fadein-bot title-section flex items-center"
        >
          About Me &nbsp;
          <div
            class="h-[1px] w-32 bg-purple-200 md:w-96 aos-init aos-animate"
            data-aos="zoom-in-left"
            data-aos-duration="600"
          ></div>
        </div>
      </header>

      <section
        class="text-sm md:text-lg text-justify flex flex-col gap-4 md:flex-row md:gap-8 md:justify-left md:items-center"
      >
        <div class="flex justify-center">
          <img
            class="w-9/12 rounded-full mb-3 fadein-up"
            src="../assets/avatar.jpg"
            alt="Foto"
          />
        </div>
        <div class="md:w-7/12">
          <p class="mb-3 md:mb-7 fadein-left fadeins-1">
            &nbsp; &nbsp; &nbsp; Hi everyone! My name is Cauã Diório. I'm a web
            developer who completed a two-year technical course at SENAI. During
            my training, I mastered HTML, CSS, Tailwind, React, React Vite, C#,
            JavaScript, .NET, MAUI, Git, GitHub, npm, Node.js, Bootstrap, and
            Material-UI.
          </p>
          <p class="mb-3 fadein-left fadeins-2">
            &nbsp; &nbsp; &nbsp; My job is to build websites that are both
            functional and user-friendly while maintaining an attractive design.
            I believe coding is not just about solving problems—it's a creative
            process that blends logic with artistry. I strive to deliver
            products that capture attention and provide a seamless user
            experience.
          </p>
          <p class="mb-3 fadein-left fadeins-2">
            &nbsp; &nbsp; &nbsp; If you're interested in collaborating or hiring
            me, feel free to reach out!
          </p>
        </div>
      </section>
    </article>
  </div>

  <div class="px-5 py-5 md:px-12 md:py-10 text-left text-purple-50 mx-3">
    <article data-page="about">
      <header>
        <div
          class="text-2xl font-bold text-white mb-5 fadein-bot title-section flex items-center"
        >
          <div
            class="h-[1px] w-10 bg-purple-200 md:w-20 aos-init aos-animate"
            data-aos="zoom-in-left"
            data-aos-duration="600"
          ></div>
          &nbsp; Skills
        </div>
      </header>
      <section>
        <div>
          <ul
            class="flex flex-wrap text-sm font-medium text-center text-gray-500 dark:text-gray-400 mb-5"
          >
            <li class="mr-2">
              <button
                class="inline-block px-4 py-3 rounded-lg hover:text-white"
                :class="{
                  'text-purple-200 bg-purple-200 bg-opacity-10':
                    activeTab === 1,
                }"
                @click="activeTab = 1"
              >
                Tech Stack
              </button>
            </li>
            <li class="mr-2">
              <button
                class="inline-block px-4 py-3 rounded-lg hover:text-white"
                :class="{
                  'text-purple-200 bg-purple-200 bg-opacity-10':
                    activeTab === 2,
                }"
                @click="activeTab = 2"
              >
                Tools
              </button>
            </li>
          </ul>
        </div>
        <div v-show="activeTab === 1">
          <div
            class="grid grid-cols-2 gap-4 pb-32 md:grid-cols-3 md:gap-8 xl:grid-cols-4 xl:gap-10 2xl:gap-12"
          >
            <div v-for="item in tech" :key="item.id">
              <div
                class="item-tech flex cursor-pointer items-center gap-2 rounded border border-purple-200 px-2 py-2 hover:bg-purple-200 hover:bg-opacity-10 md:gap-3 lg:px-3"
              >
                <div
                  class="flex h-12 w-12 items-center justify-center p-0 lg:h-16 lg:w-16 lg:p-2 zoom-in"
                >
                  <img
                    alt="HTML"
                    loading="lazy"
                    width="32"
                    height="32"
                    decoding="async"
                    data-nimg="1"
                    class="img-tech drop-shadow-xl transition-all duration-300 h-[65%] w-[65%] lg:h-[85%] lg:w-[85%]"
                    :src="item.imageUrl"
                    style="color: transparent"
                  />
                </div>
                <div class="flex items-center text-sm md:text-base lg:text-lg">
                  <div
                    class="tech font-medium text-secondary transition-all duration-300 translate-y-0"
                  >
                    {{ item.name }}
                  </div>
                  <div
                    class="status-tech opacity-0 absolute mt-5 text-[10px] text-purple-200 transition-all duration-300 md:text-xs lg:text-sm"
                  >
                    {{ item.status }}
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
        <div v-show="activeTab === 2">
          <div
            class="grid grid-cols-2 gap-4 pb-32 md:grid-cols-3 md:gap-8 xl:grid-cols-4 xl:gap-10 2xl:gap-12"
          >
            <div v-for="item in tools" :key="item.id">
              <div
                class="item-tech flex cursor-pointer items-center gap-2 rounded border border-purple-200 px-2 py-2 hover:bg-purple-200 hover:bg-opacity-10 md:gap-3 lg:px-3"
              >
                <div
                  class="flex h-12 w-12 items-center justify-center p-0 lg:h-16 lg:w-16 lg:p-2 zoom-in"
                >
                  <img
                    alt="HTML"
                    loading="lazy"
                    width="32"
                    height="32"
                    decoding="async"
                    data-nimg="1"
                    class="img-tech drop-shadow-xl transition-all duration-300 h-[65%] w-[65%] lg:h-[85%] lg:w-[85%]"
                    :src="item.imageUrl"
                    style="color: transparent"
                  />
                </div>
                <div class="flex items-center text-sm md:text-base lg:text-lg">
                  <div
                    class="tech font-medium text-secondary transition-all duration-300 translate-y-0"
                  >
                    {{ item.name }}
                  </div>
                  <div
                    class="status-tech opacity-0 absolute mt-5 text-[10px] text-purple-200 transition-all duration-300 md:text-xs lg:text-sm"
                  >
                    {{ item.status }}
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </section>
    </article>
  </div>
</template>

<style>
.fadein-left {
  opacity: 0;
  animation: fadeInLeft 0.5s ease-out forwards;
}

@keyframes fadeInLeft {
  0% {
    opacity: 0;
    transform: translateX(100%);
  }

  100% {
    opacity: 1;
    transform: translateX(0);
  }
}

.fadeins-1 {
  animation-delay: 500ms;
}

.fadeins-2 {
  animation-delay: 800ms;
}

.img-tech,
.tech {
  transition: transform 0.3s ease;
}

.item-tech:hover .img-tech {
  transform: scale(1.3);
}

.item-tech:hover .tech {
  transform: translateY(-12px);
}

.item-tech:hover .status-tech {
  opacity: 1;
}
</style>
