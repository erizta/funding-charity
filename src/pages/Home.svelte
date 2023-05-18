<script>
  import CharityList from "../components/CharityList.svelte";

  let title = "Charity";

	let charities=['1','2','3']

</script>


<div>
	<h1>{title}</h1>
  <CharityList charities={charities} />
  <CharityList  />
</div>

<style>
  h1 {
    font-size: 3em;
    color: #e2071c;
  }
</style>

