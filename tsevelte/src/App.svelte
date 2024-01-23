<script>
  import Image from './components/Image.svelte'
  let name = 'Mikes'
  let imgUrl = 'https://fastly.picsum.photos/id/0/5000/3333.jpg?hmac=_j6ghY5fCfSD6tvtcV74zXivkJSPIfR9B8w34XeQmvU'
</script>

<div>
  hello <span class="highlight">world {name}</span>
  <Image imgUrl={imgUrl}/>
</div>


<style>
  .highlight {
      color: red;
  }
</style>