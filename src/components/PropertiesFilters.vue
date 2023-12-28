<template>
     <section id="type_room">
      <div class="container">
        <div class="btn_container">
          <button class="btn active">
            <span>Tout</span>
          </button>

          <button class="btn active">
            <span> Haut-Standing</span>
          </button>
          <button class="btn">
            <span>logement</span>
          </button>
          <button class="btn">
            <span>logement sociaux</span>
          </button>
          <button class="btn">
            <span>Centres commerciaux</span>
          </button>
        </div>
      </div>
    </section>

</template>

<script></script>

<style>

#type_room .btn_container {
  margin-top: 50px;
  /* margin-left: 30px; */
  display: flex;
  justify-content: start;
  gap: 20px;
  overflow-x: scroll;
}

#type_room .btn_container .btn {
  background-color: rgb(255, 255, 255);
  padding: 15px 30px;
  color: var(--btn_blue);
  border: none;
  font-size: 12px;
  word-break: keep-all;
  /* flex-basis: auto;
  flex-shrink: 0;
  flex-grow: 0; */

  flex: auto 0 0;
}

#type_room .btn.active {
  background-color: var(--btn_blue);
  color: white;
}

@media (max-width: 426px) {
}

@media (max-width: 768px) {
  /* tablet */
}

@media (max-width: 992px) {
}

/* #footer_one .col_four .btn {
  
    background-color: var(--btn_blue);
   
} */

</style>