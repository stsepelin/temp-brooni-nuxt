<script setup lang="ts">
import Employees from '~/components/_partials/employees';
import Calendar from '~/components/_partials/calendar';
import Services from '~/components/_partials/services';

const employees = [
  {
    id: 1,
    full_name: 'Aleksandr Štšepelin',
    photo:
      'https://images.unsplash.com/photo-1618641986557-1ecd230959aa?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=facearea&facepad=2&w=256&h=256&q=80',
    available_times: {
      '2023-08-05': ['11:00'],
    },
  },
  {
    id: 1,
    full_name: 'Jekaterina Štšepelina',
    photo:
      'https://images.unsplash.com/photo-1494790108377-be9c29b29330?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=facearea&facepad=2&w=256&h=256&q=80',
    available_times: {},
  },
];
</script>

<template>
  <div class="h-screen bg-gray-50">
    <div
      class="mx-auto max-w-2xl px-4 pb-24 pt-16 sm:px-6 lg:max-w-7xl lg:px-8"
    >
      <h2 class="sr-only">Checkout</h2>

      <form class="grid gap-y-10 lg:grid-cols-2 lg:gap-x-12 xl:gap-x-16">
        <div>
          <Employees :employees="employees" />

          <Calendar />
        </div>

        <Services />
      </form>
    </div>
  </div>
</template>
