<script setup lang="ts">
import { ref } from 'vue'

defineProps<{ msg: string }>()

const count = ref(0)
</script>

<template>
    <h1>{{ msg }}</h1>

    <van-cell-group>
        <van-cell title="单元格" value="内容" />
        <van-cell title="单元格" value="内容" label="描述信息" />
    </van-cell-group>

    <van-icon name="chat-o" size="40" />

    <van-image width="100" height="100" lazy-load src="https://fastly.jsdelivr.net/npm/@vant/assets/cat.jpeg" />

    <div class="rem-test">rem测试</div>

    <p>
        Recommended IDE setup:
        <a href="https://code.visualstudio.com/" target="_blank">VSCode</a>
        +
        <a href="https://github.com/johnsoncodehk/volar" target="_blank">Volar</a>
    </p>

    <p>See <code>README.md</code> for more information.</p>

    <p>
        <a href="https://vitejs.dev/guide/features.html" target="_blank"> Vite Docs </a>
        |
        <a href="https://v3.vuejs.org/" target="_blank">Vue 3 Docs</a>
    </p>

    <button type="button" @click="count++">count is: {{ count }}</button>
    <p>
        Edit
        <code>components/HelloWorld.vue</code> to test hot module replacement.
    </p>

    <p>
        Edit
        <code>components/HelloWorld.vue</code> to test hot module replacement.
    </p>

    <p>
        Edit
        <code>components/HelloWorld.vue</code> to test hot module replacement.
    </p>

    <p>
        Edit
        <code>components/HelloWorld.vue</code> to test hot module replacement.
    </p>

    <p>
        Edit
        <code>components/HelloWorld.vue</code> to test hot module replacement.
    </p>

    <p>
        Edit
        <code>components/HelloWorld.vue</code> to test hot module replacement.
    </p>

    <van-image width="100" lazy-load height="100" src="https://fastly.jsdelivr.net/npm/@vant/assets/cat.jpeg" />
</template>

<style scoped>
a {
    color: #42b983;
}

label {
    margin: 0 0.5em;
    font-weight: bold;
}

code {
    background-color: #eee;
    padding: 2px 4px;
    border-radius: 4px;
    color: #304455;
}

.rem-test {
    height: 100px;
}
</style>
