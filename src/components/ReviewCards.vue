<template>
    <section class="reviews">
      <div class="container">
        <div>
          <h2>What our customers are saying</h2>
        </div>
  
        <div class="card">
          <img src="../assets/images/Mask Group.png" class="customer-image" alt="Edward Newgate"/>
          <div class="card-info">
            <h2 class="card-name">Edward Newgate</h2>
            <p class="card-description">Founder's Circle</p>
          </div>
          <p class="our">
            “Our dedicated patient engagement app and 
            web portal allow you to access information instantaneously (no tedious form, long calls, 
            or administrative hassle) and securely”
          </p>
        </div>
      </div>
      <div class="pagination">
        <img src="../assets/images/arrow nav.png" class="arrow-nav" alt="Navigation arrow"/>
      </div>
    </section>
  </template>
  
  <style scoped>
  .reviews {
    width: 100%;
    max-width: 800px;
    margin: 0 auto;
    padding: 20px;
  }
  
  .container {
    background-color: #458FF6;
    border-radius: 15px;
    box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
    padding: 20px;
  }
  
  .container > div {
    text-align: center;
    margin-bottom: 20px;
  }
  
  h2 {
    font-size: 25px;
    color: white;
  }
  
  .card {
    border-radius: 8px;
    padding: 20px;
    display: flex;
    align-items: center;
    margin-bottom: 20px;
  }
  
  .customer-image {
    width: 100px;
    height: 100px;
    border-radius: 50%;
    margin-right: 20px;
  }
  
  .card-info {
    flex-grow: 1;
  }
  
  .card-name {
    font-size: 15px;
    color: white;
    margin: 0;
    
  }
  
  .card-description {
    font-size: 12px;
    color: white;
    margin: 5px 0 0;
  }
  
  .our {
    font-size: 15px;
    color: white;
    margin: 20px 0 0;
    padding-left: 120px;
  }
  
  .pagination {
    text-align: center;
    margin-top: 20px;
  }
  
  .arrow-nav {
  
    height: auto;
    cursor: pointer;
  }
  
  .arrow-nav:hover {
    transform: scale(1.1);
  }

/* Responsive Styling */
@media (max-width: 768px) {
  .reviews {
    padding: 10px;
  }

  .container {
    padding: 10px;
  }

  .card {
    flex-direction: column;
    text-align: center;
  }

  .customer-image {
    margin: 0 auto 10px;
  }

  .our {
    padding-left: 0;
  }
}

@media (max-width: 480px) {
  .card-info {
    text-align: center;
  }
}
  </style>
  