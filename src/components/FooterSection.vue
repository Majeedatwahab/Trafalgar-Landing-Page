<template>
    <footer class="footer">
      <div class="footer-container">
        <div class="footer-section">
         <div class="logo"> 
          <h1>T</h1>
         <p>Trafalgar</p>
         </div>
          <p>Trafalgar provides progressive, and affordable healthcare, accessible on mobile and online for everyone</p>
          <p>©Trafalgar PTY LTD 2020. All rights reserved</p>
        </div>
        <div class="footer-section">
          <h3>Company</h3>
          <ul>
            <li><a href="#">About</a></li>
            <li><a href="#">Testimonials</a></li>
            <li><a href="#">Find a doctor</a></li>
            <li><a href="#">Apps</a></li>
          </ul>
        </div>
        <div class="footer-section">
          <h3>Region</h3>
          <ul>
            <li><a href="#">Indonesia</a></li>
            <li><a href="#">Singapore</a></li>
            <li><a href="#">Hongkong</a></li>
            <li><a href="#">Canada</a></li>
          </ul>
        </div>
        <div class="footer-section">
          <h3>Help</h3>
          <ul>
            <li><a href="#">Help center</a></li>
            <li><a href="#">Contact support</a></li>
            <li><a href="#">Instructions</a></li>
            <li><a href="#">How it works</a></li>
          </ul>
        </div>
      </div>
    </footer>
  </template>
  
  
  
  <style scoped>
  .footer {
    background-color: #5B9BF3;
    color: #ffffff;
    padding: 2rem 1rem;
  }
  
  .footer-container {
    display: flex;
    flex-direction: column;
    align-items: center;
    text-align: center;
  }
  
  .footer-section {
    margin-bottom: 1.5rem;
  }
  .logo{
    display: flex;
    align-items: center;
    gap: 1.2rem;
  }
  .logo p{
    font-size: 24px;
    font-weight: bold;
  }
  h1{
    color: #5B9BF3;
    background-color: white;
    border-radius: 50%;
    width: 40px;
    text-align: center;
  }

  .footer-section h3 {
    margin-bottom: 1rem;
    font-size: 20px;
  }
  
  .footer-section ul {
    list-style: none;
    padding: 0;
  }
  
  .footer-section ul li {
    margin-bottom: 0.5rem;
  }
  
  .footer-section ul li a {
    color: #ffffff;
    text-decoration: none;
    font-size: 18px;
  }
  
  .footer-section ul li a:hover {
    text-decoration: underline;
  }
  
  @media(min-width: 768px) {
    .footer-container {
      flex-direction: row;
      justify-content: space-around;
      text-align: left;
    }
  
    .footer-section {
      margin-bottom: 0;
      max-width: 200px;
    }
  }
  </style>
  