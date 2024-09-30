<script>
	import { Card } from '$lib/components/ui/card';
	import { Button } from '$lib/components/ui/button';
	import CardHeader from '$lib/components/ui/card/card-header.svelte';
	import CardContent from '$lib/components/ui/card/card-content.svelte';
</script>

<Card>
	<CardHeader>Login to the site!</CardHeader>
	<CardContent>
		<Button href="/auth/login/github">Sign in with Github</Button>
	</CardContent>
</Card>
