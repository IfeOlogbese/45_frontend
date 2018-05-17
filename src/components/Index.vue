<template>
    <div>
        <reg-form></reg-form>
    </div>
</template>

<script>
import RegistrationForm from '@/components/RegistrationForm.vue'

export default {
    name: 'Index',
    components: {
        'reg-form': RegistrationForm
    }
}
</script>
