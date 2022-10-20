<script>
	import rei from '$lib/images/rei.jpg';
	import instagramIcon from '$lib/images/instagram-icon.svg';
	import tikTokIcon from '$lib/images/tiktok-icon.svg';
	import youTubeIcon from '$lib/images/youtube-icon.svg';
	import letterIcon from '$lib/images/mail-icon.svg';

	let boxClass = 'flex items-center mt-8 border-[#FFD1D1] border-4 p-2 rounded bg-[#FFE3E1]';
</script>

<div class="bg-[#FFF5E4]">
	<div class="container mx-auto px-4 py-8 h-screen max-w-xl">
		<img src={rei} alt="Rei" class="rounded-full h-32 w-32 mx-auto border-[#FFD1D1] border-8" />

		<div class="flex flex-col items-center font-light">
			<h1 class="text-6xl mt-8 font-bold mb-4 text-[#FF9494]">Lil' Rei</h1>
			<h2>Her Royal Potatoness 👑</h2>
			<h2>Shiba Inufluencer based in Berlin</h2>
		</div>

		<div>
			<a
				href="https://www.instagram.com/lilshiba_rei/"
				target="_blank"
				rel="noopener noreferrer"
				class={boxClass}
			>
				<img src={instagramIcon} alt="Instagram" class="h-10 w-10" />
				<span class="font-bold text-3xl mx-auto">Instagram</span>
			</a>

			<a
				href="https://www.tiktok.com/@lilshiba_rei"
				target="_blank"
				rel="noopener noreferrer"
				class={boxClass}
			>
				<img src={tikTokIcon} alt="TikTok" class="h-10 w-10" />
				<span class="font-bold text-3xl mx-auto">TikTok</span>
			</a>

			<a
				href="https://www.youtube.com/channel/UCghbLlBfsS8uXeig2oRiwcw"
				target="_blank"
				rel="noopener noreferrer"
				class={boxClass}
			>
				<img src={youTubeIcon} alt="YouTube" class="h-10 w-10" />
				<span class="font-bold text-3xl mx-auto">YouTube</span>
			</a>

			<a
				href="mailto:bark@shiba-rei.com"
				target="_blank"
				rel="noopener noreferrer"
				class={boxClass}
			>
				<img src={letterIcon} alt="Email" class="h-10 w-10" />
				<span class="font-bold text-3xl mx-auto">Email</span>
			</a>
		</div>
	</div>
</div>
