<script>
    import "../app.css";
</script>
<!--   
  <nav class="flex justify justify-between p-4 px-8 items-center bg-white m-10 rounded-[2rem]">
    <div>
      <img src="https://cdn.discordapp.com/attachments/1063591220028383252/1099083245691355136/xx.png" alt="" class="w-12">
    </div>
    <div class="flex gap-4 font-semibold ">
      <a href="/" class="hover:text-[#7751ff] ease-in-out duration-300">Home</a>
      <a href="/about" class="hover:text-[#7751ff] ease-in-out duration-300">About</a>
      <a href="/contact" class="hover:text-[#7751ff] ease-in-out duration-300">Contact</a>
    </div>

  </nav> -->
<main>
  <slot />
</main>

<style lang="postcss">
  :global(html)
  {
    background-color: #4d1cff;
  }
</style>