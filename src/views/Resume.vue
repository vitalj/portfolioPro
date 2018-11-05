<template>
  <div class="about">
    <h1>En savoir plus à propros de moi :</h1>
      <p id="my-txt">J'ai fait ma formation de développeur logiciel à l'Access Code School et suis titulaire du diplôme de développeur logiciel (titre de niveau III). Je cherche un emploi de développeur junior à Lyon, alors si vous êtes intéressé n'hésitez pas à me contacter !
</p>
      
    <div class="cv"></div>
    <div><div>
    <img src="../assets/CV.jpg" id="img" alt="CV de Jérémy VITAL" />
  </div>

    <!-- <a target="_blank" href="https://vitalj.github.io/pdf/CV-Jeremy-Vital.pdf">   <i class="fas fa-download"></i> -->
        <a target="_blank" href="https://vitalj.github.io/pdf/CV-Jeremy-Vital.pdf">  <i class="fas fa-folder-open"></i>
</a>
  </div>
</div>

</template>
<style scoped>

#my-txt {
    padding-bottom: 2vh;
   font-family: 'PT Sans', sans-serif;
    Font-Size: 1.2rem;
      line-height: 1.5;

  }



.fas {
  font-size: 1.8rem; 
   color: white;
  background-color: rgba(0, 0, 0, 0);
   border: 1px solid rgba(247, 212, 212, 0);
   padding-top: 2vh;
}

.far:hover {
  color: black;
}


img .card {
  background-color: rgba(180, 179, 179, 0);
  border-radius: 0.25rem;
  box-shadow: 0 20px 40px -14px rgba(0, 0, 0, 0.25);
  display: flex;
  flex-direction: column;
  overflow: hidden;
  border: 1px solid rgb(36, 36, 36);
}

  .about {
    padding-top: 5vh;
    width: 90vh;
    margin-left: auto;    
    margin-right: auto;

  }

#img {
  height: 81vh;
}
</style>