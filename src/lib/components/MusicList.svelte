<script>
  export let name;
  export let action;
</script>

<nav class="list-nav">
	<!-- (optionally you can provide a label here) -->
	<ul>
		<li class="border-b-2 border-surface-600">
			<a href="/elements/lists">
				<span class="badge bg-secondary-500">{action}</span>
				<span class="flex-auto">{name}</span>
			</a>
		</li>
		<!-- ... -->
	</ul>
</nav>
