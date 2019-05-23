# clean-vuecli3-package
[![npm](https://img.shields.io/npm/v/clean-vuecli3-package.svg)](https://www.npmjs.com/package/clean-vuecli3-package)
[![Build Status](https://travis-ci.org/edtoken/clean-vuecli3-package.svg?branch=master)](https://travis-ci.org/edtoken/clean-vuecli3-package)  


```
Very simple components package with vue-cli3  
help to configure the vue-cli components packages on npm
```



```
// App.vue

<template>
    <div id="app">
        <component-a>
            Child component A
        </component-a>
        <hr/>
        <component-b>
            Child component B
        </component-b>
    </div>
</template>

<script>
    import {ComponentA, ComponentB} from 'clean-vuecli3-package';

    export default {
        name: 'app',
        components: {
            ComponentA,
            ComponentB,
        },
    };
</script>

<style>
    #app {
        font-family: 'Avenir', Helvetica, Arial, sans-serif;
        -webkit-font-smoothing: antialiased;
        -moz-osx-font-smoothing: grayscale;
        text-align: center;
        color: #2c3e50;
        margin-top: 60px;
    }
</style>
 ```
