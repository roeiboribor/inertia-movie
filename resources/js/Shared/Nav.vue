<template>
    <nav>
        <ul>
            <li><Link href="/">Home</Link></li>
            <li><Link href="/users">Users</Link></li>
            <li><Link href="/settings">Settings</Link></li>
            <li>
                <Link href="/logout" method="post" as="button">Logout</Link>
            </li>
        </ul>
    </nav>
    <!-- https://www.youtube.com/watch?v=aNZvFb402-U&list=PL3VM-unCzF8jeu0m8pSz6-Q9TwV74AbvW&index=6 -->
</template>

<script>
import { Link } from "@inertiajs/vue3";

export default {
    components: { Link },
};
</script>
