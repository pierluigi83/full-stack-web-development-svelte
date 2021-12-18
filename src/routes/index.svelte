<script>
    import TodoItem from "$lib/todo-itemk.svelte"

    const title = "Todo"
</script>

<svelt:head><title>{title}</title></svelt:head>
<h1>{title}</h1>
<form method="" action="">
    <input type="text" name="text" placeholder="+ add a tap bla  bla">
</form>
<TodoItem/>
<TodoItem/>
<TodoItem/>

