<script>
  export let placeHolder = "Roses...";
</script>

<form class="search-form" onsubmit="preventDefault();">
  <label for="search" class="label">Search</label>
  <input id="search" placeholder={placeHolder} />
</form>

<style>
  .search-form {
    display: flex;
  }
  .search-form > .label {
    margin-left: 10px;
    margin-right: 10px;
    font-weight: bold;
  }
  .search {
    width: 300px;
  }
</style>
