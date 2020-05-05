<script>
  import {
    Carousel,
    CarouselControl,
    CarouselIndicators,
    CarouselItem
  } from 'sveltestrap';

    let img1 = '/img/web.jpg'
    let img2 = '/img/web3.jpg'
    let img3 = '/img/web2.jpg'

  const items =[
      img1 ,
      img2 ,
      img3 
  ];
  let activeIndex = 0;
</script>

<Carousel {items} bind:activeIndex>
  <CarouselIndicators bind:activeIndex {items} />

  <div class="carousel-inner">
    {#each items as item, index}
      <CarouselItem bind:activeIndex itemIndex={index}>
        <img src={item} class="d-block w-100" alt={`${item} ${index + 1}`} />
      </CarouselItem>
    {/each}
  </div>

  <CarouselControl direction="prev" bind:activeIndex {items} />
  <CarouselControl direction="next" bind:activeIndex {items} />
</Carousel>

<style>
.d-block{
  height: 600px;
}
</style>