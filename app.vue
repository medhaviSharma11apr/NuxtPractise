

<script setup lang="ts">
const counter = userCounter();
</script>

<template>
  <div id="main_counter">
    Counter: {{ counter }}
    <button @click="counter++">
      +
    </button>
    <button @click="counter--">
      -
    </button>
    <div>
      <Counter></Counter>
      <Counter></Counter>
      <Counter></Counter>
    </div>
  </div>

</template>

<!-- <template>
  <NuxtLayout>
    <header>
      <ul>
        <li>
          <NuxtLink to='/'>Home</NuxtLink>
          <NuxtLink to='/events'>Events</NuxtLink>
        </li>
      </ul>
    </header>
    <Header></Header>
    <NuxtPage/>
  </NuxtLayout>
 <div>
  <h1 class="text-5xl font-bold underline">
    Hello world!
  </h1>
  </div> -->
<!-- </template> --> 
