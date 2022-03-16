<script lang="ts" setup>
interface Props {
  label?: string
}

interface SelectProps extends Props {}

const props = withDefaults(defineProps<SelectProps>(), {
  label: 'Email',
})
</script>

<template>
  {{ props.label }}
</template>
