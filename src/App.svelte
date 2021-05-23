<script>
	import UserInfo from './UserInfo.svelte'
	import Box from './Box.svelte'
	import Form from './Form.svelte'
	import Counter from './Counter.svelte'
	let stringToRender=""
</script>

<UserInfo name={'Kaska'} surname={'Kmiotek'} />
<Box>
	<h1 slot="header">Title of the page</h1>
	<span slot="body">Description of the app</span>
	<span slot="footer">footer text</span>
</Box>
<textarea bind:value={stringToRender}/>

<div>{@html stringToRender}</div>

<Form/>
<Counter/>