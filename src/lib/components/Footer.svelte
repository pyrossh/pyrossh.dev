<script>
	import Copyright from './Copyright.svelte';
	import SocialLinks from './SocialLinks.svelte';
</script>

<footer class="flex flex-row justify-center text-xl leading-6 bg-black">
	<div class="flex flex-row flex-1 py-4 px-3 max-w-5xl">
		<div class="flex-1">
			<SocialLinks />
		</div>
		<div class="flex items-center justify-center mx-2">
			<Copyright />
		</div>
	</div>
</footer>
