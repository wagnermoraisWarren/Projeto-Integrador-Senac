<template>
    <div class="">
      <header>
        <div class="logo">
          <img src="@/assets/logo.png" alt="" />
        </div>
        <nav>
          <ul>
            <li>Sobre</li>
            <li>Objetivos</li>
            <li>Inscrever-se</li>
            <li>Contato</li>
          </ul>
        </nav>
      </header>
    </div>
  </template>
  
    <script>
  export default {
    name: "Header",
  };
  </script>
  
    <style scoped>
  header {
    display: flex;
    align-items: center;
    justify-content: space-around;
    background: var(--primary-dark-low);
    padding: 2rem;
    background: hsl(210, 17%, 9%);
    border-bottom: 1px solid dodgerblue;
  }
  
  .senac {
    font-family: var(--font-montserrat);
    font-size: 2rem;
    font-weight: 700;
    color: rgba(0, 0, 0, 0.7);
    letter-spacing: 1px;
  }
  
  .fit {
    font-family: var(--font-poppins);
    font-size: 2.1rem;
    font-weight: 700;
    color: #f7ad0c;
    letter-spacing: 2px;
  }
  
  ul {
    display: flex;
    gap: 2rem;
  }
  
  li {
    font-family: var(--font-montserrat);
    padding: 0.8rem;
    font-size: 1.1rem;
    font-weight: 700;
    color: #fff;
    border-radius: 5px;
    cursor: pointer;
    transition: 200ms;
  }
  
  li:hover {
    background: #c9d6d4;
    color: rgba(0, 0, 0, 0.7);
  }
  
  img {
    width: 13rem;
  }
  </style>