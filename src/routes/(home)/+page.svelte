<script lang="ts">
	import Clock from './Clock.svelte';
	import DiscordInfo from './DiscordInfo.svelte';
	import SocialLink from './SocialLink.svelte';
	import SpotifyInfo from './SpotifyInfo.svelte';

	import GitHub from '$lib/components/icons/GitHub.svelte';
	import Envelope from '$lib/components/icons/Envelope.svelte';
	import Spotify from '$lib/components/icons/Spotify.svelte';
	import Twitter from '$lib/components/icons/Twitter.svelte';
	import Meta from '$lib/components/Meta.svelte';
</script>

<Meta title="IconicMurph" description="My portfolio and personal website." />

<main class="wrapper fade">
	<h1 class="header">Iconic Murph</h1>

	<p class="mt-4 text-gray-400">
		Hey! I'm <b>IconicMurph</b>, a discord user and gamer from
		<b>USA</b>.
	</p>

	<div class="mt-4 flex gap-6">
		<SocialLink href="https://github.com/iconicmurph" name="GitHub">
			<GitHub />
		</SocialLink>


		<SocialLink href="https://twitter.com/iconicmurph" name="Twitter">
			<Twitter />
		</SocialLink>

		<SocialLink
			href="https://open.spotify.com/user/31zsf2ykflhkushtctn5cnojww4u"
			name="Spotify"
		>
			<Spotify />
		</SocialLink>

		<SocialLink href="mailto:IconicMurph@gmail.com" name="Email">
			<Envelope />
		</SocialLink>
	</div>

	<Clock />

	<DiscordInfo />
	<SpotifyInfo />
</main>
