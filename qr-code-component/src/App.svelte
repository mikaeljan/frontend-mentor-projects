<script>
  import qrImage from "./assets/qr-code.png";
</script>

  <div class="qr-code-container round">
    <img class=round alt="qr code" src={qrImage} width="288">
    <h3>Improve your front-end skills by building projects</h3>
    <p class="description">Scan the QR code to visit Frontend Mentor and take your coding skills to the next level</p>
  </div>

<style>
  .qr-code-container {
    display: flex;
    flex-direction: column;
    align-items: center;
    text-align: center;
    width: 20rem;
    padding: 1rem 1rem 2.5rem;
    background: var(--clr-white);
    margin: auto; 
    font-size: var(--fs-paragraph);
  }

  .qr-code-container h3 {
    font-size: 1.375rem;
    color: var(--clr-dark-navy);
    margin-top: 1.5rem;
  }

  .qr-code-container .description {
    max-width: 16rem;
    color: var(--clr-grey);
    margin-top: 1rem;
    letter-spacing: 0.012rem;
  }

  .round {
    border-radius: var(--br-round);
  }
</style>
