<div class="w-[100vw] h-[15vh] flex flex-col bg-white border-gray-200 justify-center items-center">
	<div class="w-[30%] h-[50%] flex justify-center items-center p-10">
		<img src="/logo.jpeg" alt="logo" class="h-[8vh] w-[4vw] rounded-full hidden" />
		<a href="/home" class="text-3xl font-semibold">PleiRoom</a>
	</div>

	<div class="w-[30%] h-[50%] flex justify-center items-center p-10 gap-3">
		<button class="btn btn-neutral rounded-full h-30px px-5">Log In</button>
		<div class="dropdown dropdown-end">
			<div tabindex="0" role="button" class="btn m-1 btn-outline px-5 rounded-full">Me</div>
			<ul class="dropdown-content z-[1] menu p-2 shadow bg-base-100 rounded-box w-52">
				<li><a>My Profile</a></li>
				<li><a href="/createroom">Create Room</a></li>
			</ul>
		</div>
		<button class="btn btn-outline rounded-full h-30px px-5">Home</button>
		<button class="btn btn-outline rounded-full h-30px px-5">Inbox</button>
	</div>
</div>
