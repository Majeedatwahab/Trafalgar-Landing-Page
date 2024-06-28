<template>

<section class="hero">
    <div class="container">
        <div class="hero-content">
            <h1>Virtual Healthcare <span>for you</span></h1>
      <p>
        Trafalgar provides progressive, and affordable 
healthcare, accessible on mobile and online 
for everyone
      </p>
      <a href="">Consult Today</a>
        </div>
<img src="../assets/images/illustration.png" class="hero-img"  />
   
    </div>
  </section>
</template>

<style scoped>
.hero{
    padding: 2rem 1rem;
}
.container{
  display: flex;
  align-items: center;
  justify-content: space-between;
  max-width: 1200px;
  margin: 0 auto;
  padding: 0 1rem;
}
.hero-content{
  max-width: 500px;
}
h1{
  font-size: 48px;
  font-weight: bold;
  color: #1F1534;
}
p{
  font-size: 21px;
  color: #7D7987;
}
.hero-content a{
  background-color: #458FF6;
  color: #fff;
  padding: 10px 20px;
  border-radius: 50px;
  font-size: 18px;
  font-weight: bold;
  outline: none;
  border: 0;
  cursor: pointer;
  text-decoration: none;
}
.hero-img{
 width: 500px;
}
@media(max-width: 768px){
    .container{
        flex-direction: column;
    }
    .hero-img{
        width: 250px;
        margin-top: 2rem;
    }
}
</style>