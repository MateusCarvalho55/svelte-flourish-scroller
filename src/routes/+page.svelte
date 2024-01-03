<script>
	import FlourishScroller from '../components/FlourishScroller.svelte';
	import NewsArticle from './NewsArticle.svelte';
	let steps = [
		'Serão os ministérios ocupados de forma igual entre homens e mulheres?',
		'Os homens continuam a dominar os ministérios na União Europeia, chegam a ser mais do dobro das mulheres.',
		'O destaque vem, principalmente, da Hungria que apenas inclui nos seus quadros governamentais uma única mulher.',
		'As finanças e a economia apresentam uma maior dominância masculina, enquanto que a cultura e a educação são as áreas com mais destaque feminino.',	
	];
</script>

<FlourishScroller flourish_id="2134537" {steps} />

<NewsArticle />
