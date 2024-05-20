<script>
	import Footer from '../../components/Footer.svelte';
	import { goto } from '$app/navigation';

	function checkDetails() {
		goto('/playroom');
	}
</script>

<div>
	<div class="h-[85vh] w-[100vw] bg-white flex flex-col justify-center items-center">
		<div
			class="h-[70vh] w-[60%] flex justify-center items-center bg-white gap-3 border border-gray-100 rounded-3xl"
		>
			<section class="w-[40%] h-[100%] bg-blue-600">
				<img src="/tv.jpeg" alt="musicphoto" class="object-cover w-full h-full" />
			</section>

			<section class="h-[100%] w-[60%] flex flex-col justify-center items-center gap-3">
				<input
					type="text"
					placeholder="Enter PLei code"
					class="input input-bordered w-[75%] h-[70px] bg-gray-50 rounded-full px-10"
				/>
				<input
					type="text"
					placeholder="Enter password"
					class="input input-bordered w-[75%] h-[70px] bg-gray-50 rounded-full px-10"
				/>
				<button class="btn btn-neutral w-[75%] h-[70px] rounded-full" on:click={checkDetails}
					>Enter</button
				>
			</section>
		</div>
	</div>
</div>
