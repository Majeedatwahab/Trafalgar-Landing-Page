
<template>
    <section class="download-apps">
        <div class="container">
        <div class="download-content">
        <h1>Download our mobile apps</h1>
        <p>
            Our dedicated patient engagement app and 
web portal allow you to access information instantaneously (no tedeous form, long calls, 
or administrative hassle) and securely
        </p>
        <div class="link">
    <button>Download <img src="../assets/images/Vector2.png" /></button>
</div>
    </div>
    
        <img src="../assets/images/trafalgar-illustration sec03 1.png" class="download-image"/>

    </div>
    </section>
    

</template>

<style scoped>
.download-apps{
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
.download-content{
    max-width: 500px;
}
.download-image{
    max-width: 500px;
}
h1{
    font-size: 36px;
    font-weight: bold;
    line-height: 48px;
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
        padding: 2rem;
    }
    
}

</style>