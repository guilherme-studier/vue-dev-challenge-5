<template>
  <div class="images">
    <div class="row-1">
      <div class="col-1">
        <img src="../assets/photo1.png" alt="">
      </div>
      <div class="col-2">
        <img src="../assets/photo2.png" alt="">
      </div>
    </div>
    <div class="row-2">
      <div class="col-1">
        <div class="row-3">
          <img class="img-1" src="../assets/photo3.png" alt="">
        </div>
        <div class="row-3">
          <img class="img-2" src="../assets/photo5.png" alt="">
          <img class="img-3" src="../assets/photo6.png" alt="">
        </div>
      </div>
      <div class="col-2">
        <img class="img-1" src="../assets/photo_4.png" alt="">
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Images',
}
</script>

<style scoped>

  .images {
    max-width: 962px;
    display: flex;
    flex-direction: column;
    margin-top: 64px;
    margin-bottom: 134px;
    max-height: 961px;
    height: 100%;
    justify-content: space-between;
  }

  .images .row-1 {
    width: 100%;
    display: flex;
    flex-direction: row;
    justify-content: space-between;
    max-height: 299px;
    margin-bottom: 32px;
  }

  .images .row-1 .col-1 {
    width: 299px;
    margin-right: 16px;
  }

  .images .row-1 .col-1 img {
    width: 100%;
    border-radius: 12px;
  }

  .images .row-1 .col-2 {
    width: 629px;
    margin-left: 16px;
  }

  .images .row-1 .col-2 img {
    width: 100%;
    border-radius: 12px;
  }

  /*  */

  .images .row-2 {
    width: 100%;
    max-height: 630px;
    display: flex;
    flex-direction: row;
    justify-content: space-between;
  }

  .images .row-2 .col-1 {
    width: 70%;
    max-width: 627px;
    max-height: 630px;
    display: flex;
    flex-direction: column;
    justify-content: space-between;
    margin-right: 16px;
  }

  .images .row-2 .col-1 .row-3 {
    width: 100%;
    max-width: 627px;
    display: flex;
    justify-content: space-between;
  }

  .images .row-2 .col-1 .img-1 {
    width: 100%;
    max-height: 299px;
    border-radius: 12px;
    max-width: 627px;
    margin-bottom: 32px;
  }

  .images .row-2 .col-1 .img-2 {
    width: 48%;
    max-height: 299px;
    max-width: 299px;
    border-radius: 12px;
  }

  .images .row-2 .col-1 .img-3 {
    width: 48%;
    max-height: 299px;
    max-width: 299px;
    border-radius: 12px;
  }

  .images .row-2 .col-2 {
    width: 32%;
    max-width: 297px;
    max-height: 630px;
    margin-left: 16px;
  }

  .images .row-2 .col-2 .img-1 {
    width: 100%;
    height: 100%;
    border-radius: 12px;
  }

  @media (max-width: 700px) {

    .images {
      max-height: 380.58px;
      margin-top: 39px;
      margin-bottom: 44px;
    }

    .images .row-1 {
      margin-bottom: 11.72px;
    }

    .images .row-1 .col-1 {
      margin-right: 8px;
    }

    .images .row-1 .col-2 {
      margin-left: 8px;
    }

    .images .row-2 .col-1 {
      margin-right: 8px;
    }

    .images .row-2 .col-2 {
      margin-left: 8px;
    }

    .images .row-2 .col-1 .img-1 {
      margin-bottom: 11.72px;
    }
  }

</style>