<script lang="ts">
	import type { Song } from '$lib/spotify';

	export let song: Song;
</script>

<a href={song.external_urls.spotify} target="_blank">
	<div class="rounded-lg relative">
		<img class="rounded-lg z-0" src={song.album.images[0].url} alt="" />
		<div class="m-4 z-10 top-0 right-0 absolute py-0 px-2 text-black bg-gray-300 opacity-80 rounded-full text-sm w-min">
			Song
		</div>
		<div
			class="w-full h-1/2 p-4 z-10 bottom-0 absolute rounded-lg bg-gradient-to-t to-transparent from-black flex-col flex justify-end"
		>
			<a
				href={`/songs/${song.id}`}
				class="hover:underline text-white text-lg">{song.name}</a
			>
			<a href={`/artists/${song.artists[0].id}`} class="hover:underline text-white">
				{song.artists[0].name}
			</a>
		</div>
	</div>
</a>
