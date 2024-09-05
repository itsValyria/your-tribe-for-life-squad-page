<script>
  import '../global.css';
</script>

<main>
  <section>
    <h1>Our team of experts</h1>
    <p>We are enthousiastic students who are studying Front-End Development and Design at the Amsterdam University of Applied Sciences.</p>
  </section>
  <div>
    <img src="/lesley.jpg" alt="Lesley">
    <p>F</p>
    <img src="/akiko.jpg" alt="Akiko">
    <p>D</p>
    <img src="/rukiya.jpg" alt="Rukiya">
    <p>N</p>
    <img src="/zainab.jpg" alt="Zainab">
    <p>D</p>
    <img src="/eva.jpg" alt="Eef">
  </div>
</main>

<style>
  main {
    padding: 2rem;
    background-color: var(--blueberry);
    color: var(--turquoise);
  }

  img {
    width: 6.6rem;
  }

  div {
    display: grid;
    grid-template-columns: repeat(3, calc((100% / 3) - 2px));
    gap: 1px 0;
  }

  div p {
    display: flex;
    justify-content: center;
    align-items: center;
    font-weight: bold;
    font-size: 1.2rem;
  }

  div img {
    margin: 0 auto;
  }
</style>