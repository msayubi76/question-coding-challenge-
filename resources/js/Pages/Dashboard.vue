<script setup>
import AuthenticatedLayout from '@/Layouts/AuthenticatedLayout.vue';
import { Head } from '@inertiajs/vue3';
import questions from '../questions'
</script>

<template>
    <Head title="Dashboard" />

    <AuthenticatedLayout>
        <template #header>
            <h2 class="font-semibold text-xl text-gray-800 leading-tight">Dashboard</h2>
        </template>

        <div class="py-12">
            <div class="max-w-7xl mx-auto sm:px-6 lg:px-8">
                <div class="bg-white overflow-hidden shadow-sm sm:rounded-lg">
                    <div class="questions">
                        <div class="question">
                            <div class="inline-flex">
                                <div class="m-1">
                                    <b>1) </b>
                                </div>
                                <div class=" m-1">
                                    What%20was%20the%20last%20colony%20the
                                </div>
                            </div>
                            <div class="col-md-6">
                                <input type="radio" class="form-control m-2 " id="question1" name="answer[]">
                                <label for="question1">question1</label>
                            </div>
                            <div class="col-md-6">
                                <input type="radio" class="form-control m-2 " id="question2" name="answer[]">
                                <label for="question2">question2</label>
                            </div>
                            <div class="col-md-6">
                                <input type="radio" class="form-control m-2 " id="question3" name="answer[]">
                                <label for="question3">question3</label>
                            </div>
                            <div class="col-md-6">
                                <input type="radio" class="form-control m-2 " id="question4" name="answer[]">
                                <label for="question4">question4</label>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>


    </AuthenticatedLayout>
</template>
