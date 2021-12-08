<script>
  import Search from "./Search.svelte";
</script>

<div class="header">
  <img alt="Logo Pull left" src="simplesvg" class="icon" />
  <div class="search">
    <Search />
  </div>
</div>

<style>
  .icon {
    width: 40px;
    height: 40px;
  }

  .header {
    display: flex;
    flex-direction: row;
  }
  .header > .search {
  }
</style>
