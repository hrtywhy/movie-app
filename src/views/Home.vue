<template>
  <div class="home">
    <div class="feature-card">
      <router-link to="/movie/tt3896198">
      <img src="https://m.media-amazon.com/images/M/MV5BNjM0NTc0NzItM2FlYS00YzEwLWE0YmUtNTA2ZWIzODc2OTgxXkEyXkFqcGdeQXVyNTgwNzIyNzg@._V1_SX300.jpg" alt="Naruto Poster" class="featured-img"/>
      <div class="detail">
        <h3>Guardians of the Galaxy Vol. 2</h3>
        <p>The Guardians struggle to keep together as a team while dealing with their personal family issues, notably Star-Lord's encounter with his father the ambitious celestial being Ego</p>
      </div>
      </router-link>
    </div>
  </div>
</template>

<script>

export default {
 
}
</script>

<style lang="scss">
  .home{
    .featured-card{
      position: relative;

      .featured-img{
        display: block;
        width: 100px;
        height: 300px;
        object-fit: cover;

        position: relative;
        z-index: 0;
      }

      .detail {
        position: absolute;
        left: 0;
        right: 0;
        bottom: 0;
        background-color: rgba(0, 0, 0, 0);
        padding: 16px;
        z-index: 1;

        h3{
          color: white;
          margin-bottom: 16px;
        }

        p{
          color: white;
        }
      }
    }
  }
</style>