<template>
  <header>
    <div class="profile">
      <img src="../assets/profilePhoto.png" alt="photo1">
      <h1>Rodney Cotton</h1>
      <p>Helsinki, Finland</p>
    </div>
  </header>
  <section class="posts">
    <div class="metrics">
      <p class="metrics-number">100</p>
      <p class="metrics-name">Posts</p>
    </div>
    <div class="metrics">
      <p class="metrics-number">100</p>
      <p class="metrics-name">Posts</p>
    </div>
    <div class="metrics">
      <p class="metrics-number">100</p>
      <p class="metrics-name">Posts</p>
    </div>
  </section>
</template>

<script>
export default {
  name: 'Header',
}
</script>

<style>
  header {
    display: flex;
    flex-direction: column;
    align-items: center;
    margin: 48px 0 24px 0;
  }

  header .profile {
    max-width: 186px;
    width: 100%;
    height: 226px;
  }

  header .profile img {
    max-width: 156px;
    width: 100%;

    max-height: 156px;
    height: 100%;

    border-radius: 16px;
  }

  header .profile h1 {
    color: var(--gray-800);
    font-style: normal;
    font-weight: 600;
    font-size: 24px;
    white-space: nowrap;
    width: 100%;

    margin-top: 16px;
  }

  header .profile p {
    font-style: normal;
    font-weight: 600;
    font-size: 14px;

    color: var(--gray-700);
    margin-top: 8px;
  }

  .posts {
    display: flex;
    flex-direction: row;
    justify-content: space-between;
    margin: 0 auto;
    width: 348px;
  }

  .posts .metrics {
    max-width: 100px;
    width: 100%;
    height: 64px;

    background: var(--gray-400);
    border-radius: 12px;

    display: flex;
    flex-direction: column;
    justify-content: center;
  }
  .posts .metrics .metrics-number {
    font-weight: 600;
    font-size: 18px;
    line-height: 22px;
    text-align: center;
    color: var(--gray-800);
  }
  .posts .metrics .metrics-name {
    font-weight: 600;
    font-size: 14px;
    line-height: 17px;
    text-align: center;
    color: var(--gray-600);
  }

  @media (max-width: 700px) {

    header {
      margin: 48px 0 68px 0;
    }

    header .profile {
      max-width: 101.76px;
      height: 101.76px;
    }

    header .profile h1 {
      font-weight: 600;
      font-size: 14px;
      margin-top: 11.24px;
    }

    header .profile p {
      font-weight: 600;
      font-size: 10px;
      margin-top: 4px;
    }
  }
</style>