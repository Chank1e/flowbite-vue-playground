<template>
  <div class="flex gap-10">
    <Button :color="'green'">Example</Button>
    <Button :color="'red'">Example</Button>
    <Button :color="'purple'">Example</Button>
    <dropdown text="Нажми на меня" placement="top">
      <list-group>
        <list-group-item>Example</list-group-item>
      </list-group>
    </dropdown>
  </div>
</template>
<script setup lang="ts">
import { Button, Dropdown, ListGroup, ListGroupItem } from 'flowbite-vue'
</script>
