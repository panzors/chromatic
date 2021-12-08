<script>
  const data = [];
  export let title = "Chart as follows";
</script>

<div class="chart panel">
  <h2>{title}</h2>
  <div class="d3chart" />
</div>

<style>
  .chart.panel {
    margin:10px;
  }

  .d3chart{
    width:400px;
    height:400px;
    background-color: aqua;
  }
</style>
