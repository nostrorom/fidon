<script>
	import Pic from '$lib/Pic.svelte';
	let pics = [
		{
			name: 'Plages 1',
			src: 'https://i.ibb.co/S0H0C1J/SONY-DSC.jpg',
			technique: 'huile sur toile',
			dimensions: '70 x 50 cm'
		},
		{
			name: 'Plages 2',
			src: 'https://i.ibb.co/BK1gHZd/SONY-DSC.jpg',
			technique: 'huile sur toile',
			dimensions: '70 x 50 cm'
		},
		{
			name: 'Plages 3',
			src: 'https://i.ibb.co/FDjDJJ6/SONY-DSC.jpg',
			technique: 'huile sur toile',
			dimensions: '70 x 50 cm'
		},
		{
			name: 'Plages 4',
			src: 'https://i.ibb.co/m8X8FDf/SONY-DSC.jpg',
			technique: 'huile sur toile',
			dimensions: '70 x 50 cm'
		},
		{
			name: 'Plages 5',
			src: 'https://i.ibb.co/5cVnhsK/SONY-DSC.jpg',
			technique: 'huile sur toile',
			dimensions: '70 x 50 cm'
		},
		{
			name: 'Plages 6',
			src: 'https://i.ibb.co/g4QGsky/SONY-DSC.jpg',
			technique: 'huile sur toile',
			dimensions: '70 x 50 cm'
		},
		{
			name: 'Plages 7',
			src: 'https://i.ibb.co/XkDLDfW/SONY-DSC.jpg',
			technique: 'huile sur toile',
			dimensions: '81 x 65 cm'
		},
		{
			name: 'Plages 8',
			src: 'https://i.ibb.co/YRNm1T2/SONY-DSC.jpg',
			technique: 'huile sur toile',
			dimensions: '81 x 65 cm'
		},
		{
			name: 'Plages 9',
			src: 'https://i.ibb.co/D7m59n9/SONY-DSC.jpg',
			technique: 'huile sur toile',
			dimensions: '81 x 65 cm'
		}
	];
</script>

<svelte:head>
	<title>Plages</title>
</svelte:head>

<div class="">
	{#each pics as pic}
		<Pic {pic} />
	{/each}
</div>
