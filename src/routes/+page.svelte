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
  <span>&copy; Lesley, Akiko, Rukiya, Zainab & Eef</span>
</main>

<style>
  main {
    padding: 2rem;
    background-color: var(--blueberry);
    color: var(--turquoise);
  }

  h1, p {
    margin: 0;
    padding: 0;
  }
  
  h1 {
    margin-bottom: 1rem;
  }

  img {
    width: 6.6rem;
  }

  section {
    margin: 1rem 0 3rem 0;
  }

  div {
    display: grid;
    grid-template-columns: repeat(3, calc((100% / 3) - 2px));
    gap: 1px 0;
    margin-bottom: 4em;
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
  
  span {
    margin: 2em 0;
    display: flex;
    align-items: flex-end;
  }
</style>