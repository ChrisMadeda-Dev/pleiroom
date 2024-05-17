<script>
	import { goto } from '$app/navigation';

	function checkDetails() {
		goto('/playroom');
	}
</script>

<div class="h-[80vh] w-[100vw] bg-white flex flex-col justify-center items-center">
	<div
		class="h-[60vh] w-[60%] flex justify-center items-center rounded-lg border-gray-100 bg-white gap-3"
	>
		<section class="w-[40%] h-[100%] bg-blue-600">
			<img src="/tv.jpeg" alt="musicphoto" class="object-cover w-full h-full" />
		</section>

		<section class="h-[100%] w-[60%] flex flex-col justify-center items-center gap-3">
			<input
				type="text"
				placeholder="Enter PLei code"
				class="input input-bordered w-[75%] h-[50px] bg-gray-50"
			/>
			<input
				type="text"
				placeholder="Enter password"
				class="input input-bordered w-[75%] h-[50px] bg-gray-50"
			/>
			<button class="btn btn-neutral w-[75%]" on:click={checkDetails}>Enter</button>
		</section>
	</div>
</div>
