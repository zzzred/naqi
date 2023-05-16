<script>
  let overflow = 'hidden'
  let rootRef
</script>

<section class="root" bind:this={rootRef} style={`overflow: ${overflow}`}>
  <div style="background-image: url('/60.png');" on:click={() => {
    overflow = 'auto'
    // rootRef.scrollTop = window.innerHeight
    rootRef.scrollTo({top: window.innerHeight, left: 0, behavior: 'smooth'})
  }}/>
  <img src="/1.png" alt="xx" />
  <img src="/2.png" alt="xx" />
  <img src="/3.png" alt="xx" />
  <img src="/4.png" alt="xx" />
  <img src="/5.png" alt="xx" />
  <img src="/6.png" alt="xx" />
  <img src="/7.png" alt="xx" />
  <img src="/8.png" alt="xx" />
  <img src="/9.png" alt="xx" />
  <img src="/10.png" alt="xx" />
  <img src="/11.png" alt="xx" />
  <img src="/12.png" alt="xx" />
  <img src="/13.png" alt="xx" />
  <img src="/14.png" alt="xx" />
  <img src="/15.png" alt="xx" />
  <img src="/16.png" alt="xx" />
  <img src="/17.png" alt="xx" />
  <img src="/18.png" alt="xx" />
  <img src="/19.png" alt="xx" />
  <img src="/20.png" alt="xx" />
  <img src="/21.png" alt="xx" />
  <img src="/22.png" alt="xx" />
  <img src="/23.png" alt="xx" />
  <img src="/24.png" alt="xx" />
  <img src="/25.png" alt="xx" />
  <img src="/26.png" alt="xx" />
  <img src="/27.png" alt="xx" />
  <img src="/28.png" alt="xx" />
  <img src="/29.png" alt="xx" />
  <img src="/30.png" alt="xx" />
  <img src="/31.png" alt="xx" />
  <img src="/32.png" alt="xx" />
  <img src="/33.png" alt="xx" />
  <img src="/34.png" alt="xx" />
  <img src="/35.png" alt="xx" />
  <img src="/36.png" alt="xx" />
  <img src="/37.png" alt="xx" />
  <img src="/38.png" alt="xx" />
  <img src="/39.png" alt="xx" />
  <img src="/40.png" alt="xx" />
  <img src="/41.png" alt="xx" />
  <img src="/42.png" alt="xx" />
  <img src="/43.png" alt="xx" />
  <img src="/44.png" alt="xx" />
  <img src="/45.png" alt="xx" />
  <img src="/46.png" alt="xx" />
  <img src="/47.png" alt="xx" />
  <img src="/48.png" alt="xx" />
  <img src="/49.png" alt="xx" />
  <img src="/50.png" alt="xx" />
  <img src="/51.png" alt="xx" />
  <img src="/52.png" alt="xx" />
  <img src="/53.png" alt="xx" />
  <img src="/54.png" alt="xx" />
  <img src="/55.png" alt="xx" />
  <img src="/56.png" alt="xx" />
</section>

<style lang="scss">
  .root {
    width: 100%;
    height: 100%;
    overflow: hidden;
  }

  .root > div:nth-child(1) {
    width: 100%;
    height: 100%;
    background-position: center;
    background-size: cover;
    background-repeat: no-repeat;
    cursor: pointer;
  }

  img {
    width: 100%;
    cursor: pointer;
    display: block;
  }
</style>
