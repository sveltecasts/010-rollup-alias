<script>
  import Comp from "@components/Comp";
  import Comp2 from "@components/Comp2";
  import ErrorPage from "@routes/_error.svelte";
</script>

hello Component:
<Comp />
<br />
Component 2
<br />
<Comp2 />
<br />
ErrorPage:
<ErrorPage status="No real error" error={{ message: 'haha' }} />
