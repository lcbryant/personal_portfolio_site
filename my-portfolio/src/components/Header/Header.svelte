<script>
    import Avatar from "../Avatar/Avatar.svelte";
    import NavLinkList from "../NavLinkList/NavLinkList.svelte";
</script>

<style>
    @import "../app.postcss";
</style>

<div>
    <header>
        <div class="flex flex-row">
            <Avatar />
            <div class="">
                <h1>Placeholder</h1>
            </div>
        </div>
    </header>
    <main>
        <div>
            <p>CS@Princeton | Marine Veteran | Explorer Intern @ Microsoft</p>
        </div>
    </main>
    <footer>
        <NavLinkList />
    </footer>
</div>