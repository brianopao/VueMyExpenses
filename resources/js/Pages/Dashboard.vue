<script setup>
import AuthenticatedLayout from '@/Layouts/AuthenticatedLayout.vue';
import { Head,Link } from '@inertiajs/vue3';
</script>

<template>
    <Head title="Dashboard" />

    <AuthenticatedLayout>
        <template #header>
            <h2 class="text-xl font-semibold leading-tight text-gray-800">
                Dashboard
            </h2>
        </template>
        
        <div class="py-8">
            <div class="mx-auto max-w-7xl sm:px-4 lg:px-6">
                <div class="overflow-hidden bg-white shadow-sm sm:rounded-lg">
                    <div class="p-4 text-gray-900">
                        <h4>Welcome to VueMyExpense</h4>
                    </div>
                </div>                
            </div>
        </div>
        <div class="grid grid-cols-1 gap-4 sm:grid-cols-2 md:gap-6 max-w-7xl mx-auto">
            <div class="sm:px-4 lg:px-6">
                <div class="overflow-hidden bg-white shadow-sm sm:rounded-lg">
                    <div class="p-4 text-gray-900">
                        <h4>Total Income:</h4>
                    </div>
                </div>                
            </div>
            <div class="sm:px-4 lg:px-6">
                <div class="overflow-hidden bg-white shadow-sm sm:rounded-lg">
                    <div class="p-4 text-gray-900">
                        <h4>Total Expenses:</h4>
                    </div>
                </div>                
            </div>
        </div>
    </AuthenticatedLayout>
</template>
