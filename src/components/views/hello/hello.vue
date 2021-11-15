<!--
* Hello
* @author tangxiaomi <81195314@qq.com>
* @date 2021-11-15 11:36:23
* @since 0.1.0
-->

<template>
    <div>
        <h1>Hello</h1>
    </div>
</template>

<script lang="ts">
import { Component, Prop, Vue } from 'vue-property-decorator'

@Component
export default class Hello extends Vue {
    created() {}
}
</script>

<style src="./hello.styl" lang="stylus" scoped></style>
