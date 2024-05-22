<template>
  <footer class="flex flex-col mt-10  max-w-[800px] mx-auto w-full ">
    <div>
      <h1 class="text-[2rem] font-normal">Get in touch</h1>
      <a href="mailto:mohamad@elhadidy.co"
        class="font-semibold  text-[3.5rem] cursor-pointer hover:underline">mohamad@elhadidy.co</a>
    </div>
    <ul class="flex flex-row  items-center">
      <li><a target="_blank" href="https://www.linkedin.com/in/muhamadelhadidy/"> <img src="../assets/images/link.png"
            width="40" /></a></li>
      <li><a target="_blank" href="https://github.com/MohamadElhadidy">
          <img src="../assets/images/git.png" width="30" />
        </a>
      </li>
    </ul>
    <p class="mt-40 mb-10 font-semibold text-sm text-slate-500">©Mohamad Elhadidy {{ new Date().getFullYear() }}</p>
  </footer>
</template>