

<template>
<div class="article-container">
    <h1>Check out our latest article</h1>
    <div class="article-cards">
        <div class="laboratory">
<img src="../assets/images/Mask Group2.png"/>
<div class="laboratory-text">
    <h2>Disease detection, check up in the laboratory.</h2>
<p>In this case, the role of the health laboratory is very important to do
    a disease detection...</p>
    <a href="" class="link">Read More <span>&rarr;</span></a>
</div>

        </div>
        <div class="medicine">
<img src="../assets/images/Mask Group3.png"/>
<div class="medicine-text">
    <h2>Herbal Medicines that are safe for consumption.</h2>
<p>Herbal medicine is very widely used at this time because of its very good for your health...</p>
<a href="" class="link">Read More <span>&rarr;</span></a>
</div>

        </div>
        <div class="skin">
<img src="../assets/images/Mask Group4.png" />
<div class="skin-text">
    <h2>Natural care for healthy facial skin</h2>
<p>A healthy lifestyle should start from now and also for your skin health.
    There are some...</p>

    <a href="" class="link">Read More <span>&rarr;</span></a>
</div>
        </div>
    </div>
    <div class="link-btn">
        <a href="" >View all</a>
    </div>
    
</div>
    
</template>

<style scoped>
.article-container{
    display: grid;
    place-content: center;
    margin-top: 2rem;
}
h1{
    font-size: 36px;
    font-weight: bold;
    color: black;
    text-align: center;
   
}
h2{
    margin: 0 0 10px;
    color: black;
    line-height: 32px;
    font-size: 21px;
    font-weight: bold;
}
p{
    margin: 0 0 20px;
    color: #7D7987;
    font-size: 16px;
    line-height: 28px;
}
.article-cards{
    display: flex;
    align-items: center;
    gap: 36px;
}
.laboratory,
.medicine,
.skin{
    max-width: 300px;
    height: 512px;
    background-color: white;
    overflow: hidden;
    border-radius: 15px;
    text-align: left;
    box-shadow:  0 4px 6px rgba(0, 0, 0, 0.1);
   
}

img{
    width: 100%;
    height: auto;
}
.medicine-text,
.laboratory-text,
.skin-text{
    padding: 20px;

}
.link{
    text-decoration: none;
    color: #458FF6;
    display: flex;
    align-items: center;
    font-weight: bold;
    gap: 1rem;
}
.link-btn a{
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
  margin-bottom: 2rem;
  
}
.link-btn{
    margin-top: 5rem;
    display: flex;
    justify-content: center;
}

@media(max-width: 768px){
    .article-cards{
        flex-direction: column;
    }
}
</style>