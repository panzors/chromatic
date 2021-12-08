<script>
  import { Meta, Template, Story } from "@storybook/addon-svelte-csf";
  import Performance from "../Performance.svelte";
</script>

<Meta
  title="Herderder/Performance"
  argTypes={{
    placeHolder: { control: "text" },
  }}
/>

<Template let:args>
  <Performance {...args} />
</Template>

<Story name="Default" args={{ title: "hello world" }} />
<Story
  name="CustomText"
  args={{
    title: "fatty cheese is fantastic",
  }}
/>
