<script>
    import { name } from '../stores/name';

    function onClick() {
        $name = 2;
    }
</script>

<button on:click={onClick}>Some useless html</button>
