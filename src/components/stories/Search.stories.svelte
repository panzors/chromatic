<script>
  import { Meta, Template, Story } from "@storybook/addon-svelte-csf";
  import Search from "../Search.svelte";
</script>

<Meta 
  title= "Herderder/Search"
  argTypes={
    {
      placeHolder: {control:"text"}
    }
  }
/>
  
<Template let:args>
  <Search {...args} />
</Template>

<Story name="Default" args= {{placeHolder:"I love peanuts"}}/>