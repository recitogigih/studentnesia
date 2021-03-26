<template> 
  <div class="column is-3" >
    <div class="card ">
      <!-- <div class="card-image">
        <figure class="image is-4by3">
          <img src="https://bulma.io/images/placeholders/1280x960.png" alt="Placeholder image">
        </figure>
      </div> -->
      <div class="card-content">
        <div class="media">
          <div class="media-content">
            <p class="title is-4">Batch 10</p>
          <p class="subtitle">11:09 PM - 1 Jan 2016</p>
          </div>
        </div>

        <div class="content">
          Lorem ipsum dolor sit amet, consectetur adipiscing elit.
          Phasellus nec iaculis mauris.
          <br><br>
           <button class="button is-success is-small is-rounded">Available</button>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
  export default {
    props: ["column"]
  };

