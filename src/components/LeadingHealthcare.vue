
<template>
<section class="providers">
    <div class="container">
        <img src="../assets/images/trafalgar-illustration sec02 1.png" class="providers-image">
    <div class="providers-content">
        <h1>Leading Healthcare Providers </h1>
        <p>
            Trafalgar provides progressive, and affordable healthcare, accessible on mobile and online for everyone. To us, it’s not just work. We take pride 
in the solutions we deliver
        </p>
       <button>Learn More</button>
    </div>
    </div>
</section>
</template>

<style scoped>
.providers{
   padding: 2rem 1rem;
}
.leading-image img{
    width: 100%;

}
.container{
    display: flex;
    align-items: center;
    justify-content: space-between;
    max-width: 1200px;
    margin: 0 auto;
    padding: 0 1rem;
}
.providers-content{
    max-width: 500px;
}
.providers-image{
    max-width: 500px;
}
h1{
    font-size: 36px;
    font-weight: bold;
    line-height:56px;

}
p{
    font-size: 18px;
    line-height: 30px;
    color: #7D7987;
}
button{
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
    .container{
        flex-direction: column;
    }
}
</style>