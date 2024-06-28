
<template>
<section class="section-container">
    <div class="container">
        <h1>Our Services</h1>
        <p class="info">
            We provide to you the best choices for you. Adjust it to your health needs and make sure your undergo treatment with our highly qualified doctors you can consult with us which type of service is suitable for your health
        </p>

    <div class="service-cards">
      
        <div class="service-card">
            <img src="../assets/images/Frame.png" />
            <h2>Search Doctor</h2>
            <p>Choose your doctor from thousands of specialist, general, and trusted hospitals.</p>
        </div>
        <div class="service-card">
            <img src="../assets/images/Frame2.png" />
        <h2>Online Pharmacy</h2>
        <p>Buy  your medicines with our mobile application with a simple delivery system.</p>
        </div>
        
        <div class="service-card">
            <img src="../assets/images/Frame3.png"/>
            <h2>Consultation</h2>
            <p>Free consultation with our trusted doctors and get the best recomendations.</p>
        </div>
      
       
        <div class="service-card">
            <img src="../assets/images/Frame4.png"/>
            <h2>Details Info</h2>
            <p>Free consultation with our trusted doctors and get the best recomendations.</p>
        </div>
        <div class="service-card">
            <img src="../assets/images/Frame5.png"/>
            <h2>Emergency Care</h2>
            <p>24/7 emergency care with our highly qualified doctors.</p>
        </div>
        <div class="service-card">
            <img src="../assets/images/Frame6.png"/>
            <h2>Tracking Info</h2>
            <p>Track and save your medical history and health data.</p>
        </div>

    
    </div>
   </div>
</section>
</template>

<style scoped>
.section-container{
   
    padding: 2rem 1rem;
}


.info{
    font-size: 18px;
    color: #7D7987;
    line-height: 30px;
    text-align: center;
}
.container{
    max-width: 1200px;
    margin: 0 auto;
    padding: 0 1rem;
}

.service-cards{
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    margin-top: 37px;
    margin-left: 34px;
   
}

.service-card {
  background: #fff;
  padding: 1.5rem;
  border-radius: 8px;
  box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
  max-width: 240px;
  height: 254px;
  margin: 2rem;
}
.service-card p{
    font-size: 14px;
    color: #7D7987;
}
.service-card h2{
    font-size: 24px;
    font-weight: bold;
}
.service-card img {
  width: 50px;
  margin-bottom: 1rem;
}
h1{
    color: black;
    font-size: 38px;
    font-weight: bold;
    text-align: center;
    
}


a{
  background-color: #fff;
  color: #458FF6;
  padding: 10px 20px;
  border-radius: 50px;
  font-size: 18px;
  font-weight: bold;
  outline: none;
  border: 1px solid #458FF6;
  cursor: pointer;
  text-decoration: none;
  text-align: center;

}

@media(max-width: 1024px){
    .service-cards{
        grid-template-columns: repeat(1, 1fr);
        gap: 1.5rem;
        justify-content: space-between;
 
    }
}
</style>