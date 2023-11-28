<script>
	import SearchBar from './SearchBar.svelte';
</script>

<header
	class="md:flex hidden px-4 items-center h=[64px] py-2 bg-white z-10 justify-between sticky top-0 left-0"
>
	<a href="/">
		<img src="/icons/ytLogo.svg" class="md:hidden mr-5" alt="" />
	</a>
	<div class="md:flex hidden gap-4 items-center">
		<img
			class="p-3 rounded-full hover:bg-gray-200 cursor-pointer"
			src="/icons/burgerIcon.svg"
			alt=""
		/>
		<a href="/">
			<img src="/icons/ytLogo.svg" alt="" />
		</a>
	</div>
	<SearchBar />
	<div class="md:flex hidden gap-3 items-center">
		<img
			src="/icons/createIcon.svg"
			class="p-3 rounded-full hover:bg-gray-200 cursor-pointer"
			alt=""
		/>
		<img
			src="/icons/notificationIcon.svg"
			class="p-3 rounded-full hover:bg-gray-200 cursor-pointer"
			alt=""
		/>
		<img src="/avatar.png" class="rounded-full bg-gray-200 h-8 w-8 cursor-pointer" alt="" />
	</div>
</header>
