<script lang="ts">
 let date: string = new Date().toLocaleDateString(
    'en-us',
    {
      year: 'numeric',
      month: 'long',
      day: 'numeric'
    }
  );
</script>

<main>
  <img src="/aadl-logo.png" style="width: 17vw;"/>
  <h1><strong>AADL PRODUCTIONS</strong></h1>
  <p>Produced on {date} <br/> by the Ann Arbor District Library</p>
  <img src="/by-nc-sa.png" style="width: 17vw;"/>
</main>

<style>

</style>
