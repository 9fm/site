<template>
	<div class="bg-black snap text-white font-extrabold h-dvh text-7xl sm:text-9xl flex items-center justify-center">
		<div>

			krokiety.
			<p class="text-sm sm:text-2xl mt-2 sm:mt-0"><a href="https://discord.com/user/688804133674811473">

					<Icon name="ic:outline-discord" size="2rem" class="mx-1" />discord
				</a>
				<a href="https://t.me/krokieciki">

					<Icon name="ic:round-telegram" size="2rem" class="mx-1" />telegram

				</a>
				<a href="https://github.com/9fm">

					<Icon name="mdi:github" size="2rem" class="mx-1" />github
				</a>
			</p>
		</div>


		<span class="absolute bottom-20  text-3xl">
			Projects
			<Icon size="4rem" name="material-symbols:arrow-downward-rounded"></Icon>
		</span>
	</div>
	<div class="bg-white text-black h-dvh p-12 ">
		<div class="snap bg-black rounded-lg projects text-white md:w-2/5 xl:w-2/6 w-full mx-auto">
			<h1 class="text-2xl text-center  ">My "projects"</h1>
			<div class="h-1   m-1 bg-gray-400" />
			<div class="p-1 ">

				<project name="This website" icon="mdi:nuxt" description="this website. i made it with nuxt+tailwindcss" />
				<project name="More coming soon..." description="there are projects that i hopefully will release later." icon="ph:dots-three-outline-fill" />
				<project name="More coming soon..." description="filler" icon="ph:dots-three-outline-fill" />
				<project name="More coming soon..." description="filler" icon="ph:dots-three-outline-fill" />

			</div>
		</div>
	</div>
</template>

<style>
body {
	font-family: 'Poppins';
}

.snap {
	scroll-snap-align: start;
}

.projects {
	box-shadow: 10px 5px gray;

}

html {
	scroll-snap-type: y mandatory;
}
</style>