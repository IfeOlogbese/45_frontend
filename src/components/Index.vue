<template>
    <div>
        <!-- <reg-form></reg-form> -->
        <world-today></world-today>
    </div>
</template>

<script>
import RegistrationForm from '@/components/RegistrationForm.vue'
import WorldToday from '@/components/WorldToday.vue'

export default {
    name: 'Index',
    components: {
        'reg-form': RegistrationForm,
        'world-today': WorldToday
    }
}
</script>
