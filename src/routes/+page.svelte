<script>
  import '../global.css';
</script>

<main>
  <section>
    <h1>Our team of experts</h1>
    <p>We are enthousiastic students who are studying Front-End Development and Design at the Amsterdam University of Applied Sciences.</p>
  </section>
  <div>
    <a href="/Lesley"><img src="/lesley.jpg" alt="Lesley"></a>
    <p>F</p>
    <a href="/Akiko"><img src="/akiko.jpg" alt="Akiko"></a>
    <p>D</p>
    <a href="/Rukiya"><img src="/rukiya.jpg" alt="Rukiya"></a>
    <p>N</p>
    <a href="/Zainab"><img src="/zainab.jpg" alt="Zainab"></a>
    <p>D</p>
    <a href="/Eva"><img src="/eva.jpg" alt="Eef"></a>
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

  a {
    display: inline-block;
  }

  img {
    width: 6.6rem;
    height: auto;
  }

  section {
    margin: 1rem 0 3rem 0;
  }

  div {
    display: grid;
    grid-template-columns: repeat(3, 1fr);
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