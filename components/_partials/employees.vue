<script setup lang="ts">
import { ref } from 'vue';
import {
  Listbox,
  ListboxButton,
  ListboxOptions,
  ListboxOption,
} from '@headlessui/vue';
import { CheckIcon, ChevronUpDownIcon } from '@heroicons/vue/20/solid';

const props = defineProps<{ employees: Employee[] }>();

const selectedEmployee = ref(props.employees[0]);
</script>

<template>
  <div>
    <h2 class="text-lg font-medium text-gray-900">Employee</h2>

    <div class="mt-4">
      <div>
        <Listbox v-model="selectedEmployee">
          <div class="relative mt-1">
            <ListboxButton
              class="
                relative
                w-full
                flex
                items-center
                space-x-4
                rounded-xl
                px-4
                py-2
                hover:bg-gray-100
                focus:outline-none
                focus-visible:border-indigo-500
                focus-visible:ring-2
                focus-visible:ring-white
                focus-visible:ring-opacity-75
                focus-visible:ring-offset-2
                focus-visible:ring-offset-orange-300
                sm:text-sm
              "
            >
              <div class="flex items-center space-x-4">
                <img
                  :src="selectedEmployee.photo"
                  alt=""
                  class="h-10 w-10 flex-none rounded-full"
                />
                <div class="flex-auto">
                  <p class="text-gray-900">
                    {{ selectedEmployee.full_name }}
                  </p>
                  <p class="mt-0.5">
                    <time datetime="2022-01-21T13:00">1:00 PM</time> -
                    <time datetime="2022-01-21T14:30">2:30 PM</time>
                  </p>
                </div>
              </div>
              <span
                class="
                  pointer-events-none
                  absolute
                  inset-y-0
                  right-0
                  flex
                  items-center
                  pr-2
                "
              >
                <ChevronUpDownIcon
                  class="h-5 w-5 text-gray-400"
                  aria-hidden="true"
                />
              </span>
            </ListboxButton>

            <transition
              leave-active-class="transition duration-100 ease-in"
              leave-from-class="opacity-100"
              leave-to-class="opacity-0"
            >
              <ListboxOptions
                class="
                  absolute
                  mt-1
                  max-h-60
                  w-full
                  overflow-auto
                  rounded-md
                  bg-white
                  py-1
                  text-base
                  shadow-lg
                  ring-1 ring-black ring-opacity-5
                  focus:outline-none
                  sm:text-sm
                "
              >
                <ListboxOption
                  v-slot="{ active, selected }"
                  v-for="employee in props.employees"
                  :key="employee.id"
                  :value="employee"
                  as="template"
                >
                  <li
                    :class="[
                      active ? 'bg-amber-100 text-amber-900' : 'text-gray-900',
                      'relative cursor-default select-none py-2 pr-10 pl-4',
                    ]"
                  >
                    <span class="flex items-center">
                      <img
                        :src="employee.photo"
                        alt=""
                        class="h-6 w-6 flex-none rounded-full"
                      />
                      <span
                        :class="[
                          selected ? 'font-medium' : 'font-normal',
                          'ml-2 block truncate',
                        ]"
                        >{{ employee.full_name }}</span
                      >
                    </span>
                    <span
                      v-if="selected"
                      class="
                        absolute
                        inset-y-0
                        right-0
                        flex
                        items-center
                        pr-3
                        text-amber-600
                      "
                    >
                      <CheckIcon class="h-5 w-5" aria-hidden="true" />
                    </span>
                  </li>
                </ListboxOption>
              </ListboxOptions>
            </transition>
          </div>
        </Listbox>
      </div>
    </div>
  </div>
</template>
