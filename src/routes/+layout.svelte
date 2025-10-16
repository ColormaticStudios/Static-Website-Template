<script lang="ts">
  import "style/main.scss";
  import "style/tailwind.css";

  interface Props {
    children?: import("svelte").Snippet;
  }
  let { children }: Props = $props();
</script>

{@render children?.()}
