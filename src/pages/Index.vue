<template>
  <Layout>
    <div class="hero container-inner mx-auto flex flex-col sm:flex-row justify-between items-center py-16">
      <div class="text-4xl font-bold w-full sm:w-3/5 text-center sm:text-left">
        <div class="leading-tight">Marioneta´s Blog</div>
        <div class="text-gray-700 leading-tight">Sharing all about the technology we enjoy</div>
      </div>
      <div class="mt-8 sm:mt-0 w-9/12 ml-10">
        <g-image src="../../static/computer.png" alt="hero" class="mx-auto sm:mx-0" />
      </div>
    </div> <!-- end hero -->

    <div class="container-inner mx-auto">
      <p class="text-lg sm:text-xl">This gridsome theme was forked from my <a href="https://andremadarang.com">personal website</a>. I added more features and decided to release it as an open source project. Check it out on <a href="https://github.com/drehimself/gridsome-portfolio-starter">GitHub</a> or check out the <a href="https://www.youtube.com/watch?v=uHo6o1TNQeE">screencast I did</a>. Feel free to use it for your own site or projects! Lorem, ipsum dolor sit amet consectetur adipisicing elit. Minima, repellat. Dolores iure, quas perspiciatis rerum quaerat atque eum repellat autem.</p>
    </div>

    
    <div class="overflow-x-hidden border-gray-200 border-b">
      <div class="get-to-know-me container-inner mx-auto text-xl pb-16 relative">
        <h2 class="font-bold mb-6" id="about">Get to know me:</h2>

        <div class="absolute left-0" style="top: 50px; transform: translateX(-100%)">
          <svg width="170px" height="170px"><use xlink:href="#dots-triangle" /></svg>
        </div>

        <div class="flex flex-col sm:flex-row justify-between items-center mb-16">
          <div><g-image src="../../static/avatar.jpg" alt="avatar" class="w-32 h-32 rounded-full mb-8 lg:mb-0" /></div>
          <div class="flex-1 text-lg sm:text-xl ml-6">Lorem ipsum dolor sit amet consectetur, adipisicing elit. Eum quae architecto minus molestias iusto ducimus fuga quo quia libero dignissimos, fugiat modi assumenda debitis laboriosam.</div>
        </div>

        <div class="responsive-container" style="display:none">
          <iframe class="responsive-iframe w-full h-full top-0 left-0 border-0" src="https://www.youtube.com/embed/uHo6o1TNQeE" style="border:0;" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
        </div>
      </div> <!-- end get-to-know me -->
    </div>

  </Layout>
</template>

<script>
export default {
  metaInfo: {
    title: 'Start'
  }
}
</script>

