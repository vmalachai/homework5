<script setup>
import { faker } from '@faker-js/faker'
const fullname = faker.person.fullName()

</script>

<template>
{{ fullName }} <br />
</template>