<template> 
  <div class="column is-4">
    <div class="card">
      <div class="card-image">
        <figure class="image is-4by3">
          <img :src="`/${photo}`" alt="Placeholder image" style="object-fit:cover;">
        </figure>
      </div>
      <div class="card-content">
        <div class="media">
          <div class="media-content">
            <p class="title is-4">{{nama}}</p>
          </div>
        </div>
        <div class="content">
          Lorem ipsum dolor sit amet, consectetur adipiscing elit.
          Phasellus nec iaculis mauris.
          <br>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
  export default {
    props: ["photo","nama"]
  };

</script>