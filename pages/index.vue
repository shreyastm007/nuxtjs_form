<template>
<div>
  <div id="carouselExampleIndicators" class="carousel slide" data-bs-ride="carousel">
  <div class="carousel-indicators">
    <button type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide-to="0" class="active" aria-current="true" aria-label="Slide 1"></button>
    <button type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide-to="1" aria-label="Slide 2"></button>
    <button type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide-to="2" aria-label="Slide 3"></button>
  </div>
  <div class="carousel-inner">
    <div class="carousel-item active">
      <img src="https://th.bing.com/th/id/OIP.-fbmVyXHN8j_IEA3InZdpwHaEL?w=296&h=180&c=7&r=0&o=5&dpr=1.25&pid=1.7" class="d-block w-100" alt="one">
    </div>
    <div class="carousel-item">
      <img src="https://th.bing.com/th/id/OIP.VJM-h4l0zKlUHkRh1WeRowHaCn?w=339&h=123&c=7&r=0&o=5&dpr=1.25&pid=1.7" class="d-block w-100" alt="two">
    </div>
    <div class="carousel-item">
      <img src="https://th.bing.com/th/id/OIP.1451C6NTrJqy-5sIJX_EUQHaDt?w=331&h=174&c=7&r=0&o=5&dpr=1.25&pid=1.7" class="d-block w-100" alt="three">
    </div>
  </div>
  <button class="carousel-control-prev" type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide="prev">
    <span class="carousel-control-prev-icon" aria-hidden="true"></span>
    <span class="visually-hidden">Previous</span>
  </button>
  <button class="carousel-control-next" type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide="next">
    <span class="carousel-control-next-icon" aria-hidden="true"></span>
    <span class="visually-hidden">Next</span>
  </button>
</div>
 
</div>
</template>

<script>
export default {

}
</script>

<style>
.image{
  width: 60%;
}
</style>