<script>
    let value = $state({ options:[] });
    let other = $state('');

    $effect(() => {
        console.log("Running Effect")
        value = { options:[] };
        other = [...value.options];
    })
</script>

<div>Hello</div>