<template>
  <doc-section id="carousel" name="Carousel">
    <div class="bs-example">
      <carousel>
        <slider>
          <img src="https://placehold.it/1200x500?text=one">
          <div class="carousel-caption">
           <h3>Slide #1</h3>
           <p>sunt in culpa qui officia deserunt mollit a.</p>
         </div>
        </slider>
        <slider>
          <img src="https://placehold.it/1200x500?text=two">
          <div class="carousel-caption">
           <h3>Slide #2</h3>
           <p>sunt in culpa qui officia deserunt mollit a.</p>
         </div>
        </slider>
        <slider>
          <img src="https://placehold.it/1200x500?text=three">
          <div class="carousel-caption">
           <h3>Slide #3</h3>
           <p>sunt in culpa qui officia deserunt mollit a.</p>
         </div>
        </slider>
      </carousel>
    </div>
    <doc-code language="markup">
      <carousel>
        <slider>
          <img src="https://placehold.it/1200x400?text=one">
          <div class="carousel-caption">
            ...
          </div>
        </slider>
        <slider>
          <img src="https://placehold.it/1200x400?text=two">
        </slider>
        <slider>
          <img src="https://placehold.it/1200x400?text=three">
        </slider>
      </carousel>
    </doc-code>
    <doc-table>
      <div>
        <p>indicators</p>
        <p><code>Boolean</code></p>
        <p><code>true</code></p>
        <p>Whether to show the indicators.</p>
      </div>
      <div>
        <p>controls</p>
        <p><code>Boolean</code></p>
        <p><code>true</code></p>
        <p>Whether to show the direction controls.</p>
      </div>
      <div>
        <p>interval</p>
        <p><code>Number</code></p>
        <p><code>5000</code></p>
        <p>The amount of time to delay between automatically cycling an item. If set to 0 or a negative number,
          carousel will not automatically cycle.
        </p>
      </div>
    </doc-table>
  </div>
</template>

<script>
import docSection from './docSection.vue'
import docTable from './docTable.vue'
import docCode from './docCode.vue'
import carousel from 'src/Carousel.vue'
import slider from 'src/Slider.vue'

export default {
  components: {
    docSection,
    docTable,
    docCode,
    carousel,
    slider
  }
}
</script>
