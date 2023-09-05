<script>
    import { onMount } from 'svelte';
	import AOS from 'aos';
    import Project from '$lib/project.svelte';
    import Skill from '$lib/skill.svelte';

    onMount(() => {
		AOS.init()
        var typed = new Typed('#element', {
            strings: ['<i>Software Developer</i>'],
            typeSpeed: 50,
            showCursor: false,
        });
	})
</script>


<svelte:head>
    <script src="https://unpkg.com/typed.js@2.0.16/dist/typed.umd.js"></script>
	<link rel="stylesheet" href="https://unpkg.com/aos@next/dist/aos.css" />
</svelte:head>

<div class="scrollbar-hide">
    <section id="about" class="relative bg-gray-50 bg-[url(https://github.com/Hublove/hublove.github.io/blob/master/css/images/background.jpg?raw=true)] bg-cover bg-center bg-no-repeat sm:aspect-auto aspect-square">
        <div
          class="mx-auto max-w-screen-xl px-4 py-32 lg:flex lg:h-screen lg:items-center"
        >
          <div class="mx-auto max-w-xl text-center">
            <h1 class="text-4xl text-gray-900 font-extrabold sm:text-6xl">
              Sebastian Stanik
              
            </h1>
            <strong id="element" class="text-2xl mt-2 font-extrabold sm:text-4xl text-orange-600 sm:block">
                Software Developer
            </strong>
            <p class="hidden mt-4 sm:text-xl/relaxed">
              Lorem ipsum dolor sit amet consectetur, adipisicing elit. Nesciunt illo
              tenetur fuga ducimus numquam ea!
            </p>
      
            <div class="mt-8 flex flex-wrap justify-center gap-4">
              <a
                class="block w-full rounded bg-orange-600 px-12 py-3 text-sm font-medium text-white shadow hover:bg-orange-700 focus:outline-none focus:ring active:bg-orange-500 sm:w-auto"
                href="#projects"
              >
                Get Started
              </a>
      
              <a
                class="hidden block w-full rounded px-12 py-3 text-sm font-medium text-red-600 shadow hover:text-red-700 focus:outline-none focus:ring active:text-red-500 sm:w-auto"
                href="/about"
              >
                Learn More
              </a>
            </div>
          </div>
        </div>
      </section>
    
    <!--
      Heads up! 👋
    
      This component comes with some `rtl` classes. Please remove them if they are not needed in your project.
    -->
    
    <section class="w-full bg-gray-900 px-2 " id="projects">
        <div class=" px-4 py-8 sm:px-6 sm:py-12 lg:px-8 lg:py-16">
          <div
            class="grid grid-cols-1 gap-y-8 lg:grid-cols-2 place-items-center lg:items-center  "
          >
            <div
              class="mx-auto max-w-lg  lg:mx-0 ltr:lg:text-left rtl:lg:text-right "
            >
              <h2 class="text-3xl text-white font-bold sm:text-5xl">Skills</h2>

              <p class="sm:mt-16  mt-6 mb-3 font-semibold leading-relaxed tracking-wide text-gray-300 text-lg sm:text-xl">Hello there 👋 </p>
              <p class="leading-relaxed tracking-wide text-gray-300 text-md sm:text-lg">
                I'm Sebastian,  a front-end developer and junior dev with a passion for 
                creating visually engaging and user-friendly web experiences. My toolkit includes 
                expertise in JavaScript and Python, with a focus on modern frameworks like Svelte 
                to craft efficient and responsive web applications. Beyond coding, I find joy in 
                the art of photography, where I channel my creativity and capture the 
                beauty of the world one frame at a time. With a passion for both technology and 
                the visual arts, I enjoy combining the two to build unique digital experiences. 
                





              </p>
      
              <a
                href="#"
                class="hidden mt-8 inline-block rounded bg-indigo-600 px-12 py-3 text-sm font-medium text-white transition hover:bg-indigo-700 focus:outline-none focus:ring focus:ring-yellow-400"
              >
                Get Started Today
              </a>
            </div>
      
            <div class="sm:flex sm:flex-row sm:flex-wrap justify-stretch sm:gap-8 gap-1  grid grid-cols-2">
              <Skill lang="Javascript" svg="https://img.icons8.com/?size=512&id=39854&format=png"/>
              <Skill lang="Python" svg="https://img.icons8.com/?size=512&id=12592&format=png"/>
              <Skill lang="Java" svg="https://img.icons8.com/?size=512&id=38294&format=png"/>
              <Skill lang="C" svg="https://img.icons8.com/?size=512&id=66724&format=png"/>
              <Skill lang="SQL" svg="https://img.icons8.com/?size=512&id=3764&format=png"/>
              <Skill lang="React" svg="https://img.icons8.com/?size=512&id=35989&format=png"/>
              <Skill lang="Node.js" svg="https://img.icons8.com/?size=512&id=DAoKOqsuGfIG&format=png"/>
              <Skill lang="Svelte" svg="https://img.icons8.com/?size=512&id=7ST6T6xV3OPb&format=png"/>
              <Skill lang="Tailwind" svg="https://img.icons8.com/?size=512&id=UpSCHTwpywad&format=png"/>
              <Skill lang="Git" svg="https://img.icons8.com/?size=512&id=38389&format=png"/>
              <Skill lang="Docker" svg="https://img.icons8.com/?size=512&id=sIsJJux4DVLR&format=png"/>
              <Skill lang="VS Code" svg="https://img.icons8.com/?size=512&id=121602&format=png"/>          
            </div>
          </div>
          
          
        </div>
    
      </section>
    <!-- PROJECTS -->
      <section class="bg-gray-900 text-white px-2">
        <div class="flex justify-center ">
            <div class="w-5/6 border border-gray-700 my-4"></div>
        </div>
        <div
          class="mx-auto max-w-screen-xl px-4 py-8 sm:py-12 sm:px-6 lg:py-16 lg:px-8"
        >
          <div class="mx-auto max-w-lg text-center">
            <h2 class="text-3xl font-bold sm:text-5xl pb-8">Projects</h2>
      
            <p class="hidden mt-4 text-gray-300">
              Lorem ipsum, dolor sit amet consectetur adipisicing elit. Consequuntur
              aliquam doloribus nesciunt eos fugiat. Vitae aperiam fugit consequuntur
              saepe laborum.
            </p>
          </div>
      
          <div class="mt-8 grid grid-cols-1 gap-8 md:grid-cols-2 lg:grid-cols-2">
            <Project Title="Sebs.vision" Desc="Developed a responsive and visually appealing photography portfolio website to showcase a photographer's work and skills." Langs="Svelte Tailwind DaisyUI" />
            <Project Title="@PokeCardDaily" Desc="Developed a Python script which utilizes the Twitter API to enable automatic daily tweets of Pokémon trading cards." Langs="Python" />
            <Project Title="Stellar Jeopardy" Desc="Utilized backend technologies such as Node.js, Express, and Socket.IO to create robust APIs for seamless communication between the frontend and backend." Langs="React MongoDB NodeJS" />
            <Project Title="Sudoku" Desc="Developed puzzle solving and generating algorithms for a Sudoku clone using Java and JavaFX." Langs="Java JavaFX" />
          </div>
        </div>
      </section>
    
    <!-- FOOTER -->
    <footer id="contact" class="bg-white">
        <div class="mx-auto max-w-screen-xl px-4 pb-8 pt-16 sm:px-6 lg:px-8 lg:pt-24">
          <div class="text-center">
            <h2 class="text-3xl font-extrabold text-gray-900 sm:text-5xl">
              Get In Contact
            </h2>
      
            <p class="hidden mx-auto mt-4 max-w-sm text-gray-500">
              Lorem ipsum dolor, sit amet consectetur adipisicing elit. Cum maiores
              ipsum eos temporibus ea nihil.
            </p>
      
            <a
              href="https://flowcv.com/resume/8jobdiperk"
              class="mt-8 inline-block rounded-full border-2 border-orange-600 px-12 py-3 text-lg font-bold text-orange-600 hover:bg-orange-600 hover:text-white focus:outline-none focus:ring active:bg-indigo-500"
            >
              Resume
            </a>
          </div>
      
          <div
            class="mt-16 border-t border-gray-100 pt-8 sm:flex sm:items-center sm:justify-between lg:mt-24"
          >
            <ul class="flex flex-wrap justify-center gap-4 text-xs lg:justify-end">
              <li>
                <p href="#" class="text-gray-500 transition hover:opacity-75">
                    💖 With love from Toronto, Canada 💖
                </p>
              </li>
            </ul>
      
            <ul class="mt-8 flex justify-center gap-6 sm:mt-0 lg:justify-end">
              <li>
                <a
                  href="https://www.linkedin.com/in/sebastianstanik/"
                  rel="noreferrer"
                  target="_blank"
                  class="text-gray-700 transition hover:opacity-75"
                >
                  <span class="sr-only">Linkedin</span>
      
                  <svg class="h-6 w-6" xmlns="http://www.w3.org/2000/svg" x="0px" y="0px" viewBox="0 0 50 50">
                    <path d="M41,4H9C6.24,4,4,6.24,4,9v32c0,2.76,2.24,5,5,5h32c2.76,0,5-2.24,5-5V9C46,6.24,43.76,4,41,4z M17,20v19h-6V20H17z M11,14.47c0-1.4,1.2-2.47,3-2.47s2.93,1.07,3,2.47c0,1.4-1.12,2.53-3,2.53C12.2,17,11,15.87,11,14.47z M39,39h-6c0,0,0-9.26,0-10 c0-2-1-4-3.5-4.04h-0.08C27,24.96,26,27.02,26,29c0,0.91,0,10,0,10h-6V20h6v2.56c0,0,1.93-2.56,5.81-2.56 c3.97,0,7.19,2.73,7.19,8.26V39z"></path>
                  </svg>
                </a>
              </li>
      
              
      
              
      
              <li>
                <a
                  href="https://github.com/Hublove"
                  rel="noreferrer"
                  target="_blank"
                  class="text-gray-700 transition hover:opacity-75"
                >
                  <span class="sr-only">GitHub</span>
      
                  <svg
                    class="h-6 w-6"
                    fill="currentColor"
                    viewBox="0 0 24 24"
                    aria-hidden="true"
                  >
                    <path
                      fill-rule="evenodd"
                      d="M12 2C6.477 2 2 6.484 2 12.017c0 4.425 2.865 8.18 6.839 9.504.5.092.682-.217.682-.483 0-.237-.008-.868-.013-1.703-2.782.605-3.369-1.343-3.369-1.343-.454-1.158-1.11-1.466-1.11-1.466-.908-.62.069-.608.069-.608 1.003.07 1.531 1.032 1.531 1.032.892 1.53 2.341 1.088 2.91.832.092-.647.35-1.088.636-1.338-2.22-.253-4.555-1.113-4.555-4.951 0-1.093.39-1.988 1.029-2.688-.103-.253-.446-1.272.098-2.65 0 0 .84-.27 2.75 1.026A9.564 9.564 0 0112 6.844c.85.004 1.705.115 2.504.337 1.909-1.296 2.747-1.027 2.747-1.027.546 1.379.202 2.398.1 2.651.64.7 1.028 1.595 1.028 2.688 0 3.848-2.339 4.695-4.566 4.943.359.309.678.92.678 1.855 0 1.338-.012 2.419-.012 2.747 0 .268.18.58.688.482A10.019 10.019 0 0022 12.017C22 6.484 17.522 2 12 2z"
                      clip-rule="evenodd"
                    />
                  </svg>
                </a>
              </li>
      
              
            </ul>
          </div>
        </div>
      </footer>
      
</div>
