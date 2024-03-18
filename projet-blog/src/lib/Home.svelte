<script>
  
  import Actuality from "../composants/Actuality.svelte";

</script>



<div aria-hidden="true" class="bandeau">
    <img src="./src/assets/banniere.jpg" alt="bannière header">    
</div>

<style lang="scss">
  .bandeau{
    display: flex;
    justify-content: center;
  }
    img {
    //height: 300px;
    width: 40vw;
    margin-top: 50px;
  } 
</style>

<Actuality/>
