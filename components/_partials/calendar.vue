<script setup lang="ts"></script>

<template>
  <div class="mt-10 border-t border-gray-200 pt-10">
    <h2 class="text-lg font-medium text-gray-900">Date & Time</h2>
    <div class="mt-4">
      <div class="flex items-center justify-end">
        <h2 class="text-sm font-semibold text-gray-900">January 2022</h2>
        <button
          type="button"
          class="
            -my-1.5
            ml-2
            flex flex-none
            items-center
            justify-center
            p-1.5
            text-gray-400
            hover:text-gray-500
          "
        >
          <span class="sr-only">Previous month</span>
          <svg
            class="h-5 w-5"
            viewBox="0 0 20 20"
            fill="currentColor"
            aria-hidden="true"
          >
            <path
              fill-rule="evenodd"
              d="M12.79 5.23a.75.75 0 01-.02 1.06L8.832 10l3.938 3.71a.75.75 0 11-1.04 1.08l-4.5-4.25a.75.75 0 010-1.08l4.5-4.25a.75.75 0 011.06.02z"
              clip-rule="evenodd"
            />
          </svg>
        </button>
        <button
          type="button"
          class="
            -my-1.5
            flex flex-none
            items-center
            justify-center
            p-1.5
            text-gray-400
            hover:text-gray-500
          "
        >
          <span class="sr-only">Next month</span>
          <svg
            class="h-5 w-5"
            viewBox="0 0 20 20"
            fill="currentColor"
            aria-hidden="true"
          >
            <path
              fill-rule="evenodd"
              d="M7.21 14.77a.75.75 0 01.02-1.06L11.168 10 7.23 6.29a.75.75 0 111.04-1.08l4.5 4.25a.75.75 0 010 1.08l-4.5 4.25a.75.75 0 01-1.06-.02z"
              clip-rule="evenodd"
            />
          </svg>
        </button>
      </div>
      <div
        class="
          mt-10
          grid grid-cols-7
          text-center text-xs
          leading-6
          text-gray-500
        "
      >
        <div>M</div>
        <div>T</div>
        <div>W</div>
        <div>T</div>
        <div>F</div>
        <div>S</div>
        <div>S</div>
      </div>
      <div class="mt-2 grid grid-cols-7 text-sm">
        <div class="py-2">
          <button
            type="button"
            class="
              mx-auto
              flex
              h-8
              w-8
              items-center
              justify-center
              rounded-full
              text-gray-400
              hover:bg-gray-200
            "
          >
            <time datetime="2021-12-27">27</time>
          </button>
        </div>
        <div class="py-2">
          <button
            type="button"
            class="
              mx-auto
              flex
              h-8
              w-8
              items-center
              justify-center
              rounded-full
              text-gray-400
              hover:bg-gray-200
            "
          >
            <time datetime="2021-12-28">28</time>
          </button>
        </div>
        <div class="py-2">
          <button
            type="button"
            class="
              mx-auto
              flex
              h-8
              w-8
              items-center
              justify-center
              rounded-full
              text-gray-400
              hover:bg-gray-200
            "
          >
            <time datetime="2021-12-29">29</time>
          </button>
        </div>
        <div class="py-2">
          <button
            type="button"
            class="
              mx-auto
              flex
              h-8
              w-8
              items-center
              justify-center
              rounded-full
              text-gray-400
              hover:bg-gray-200
            "
          >
            <time datetime="2021-12-30">30</time>
          </button>
        </div>
        <div class="py-2">
          <button
            type="button"
            class="
              mx-auto
              flex
              h-8
              w-8
              items-center
              justify-center
              rounded-full
              text-gray-400
              hover:bg-gray-200
            "
          >
            <time datetime="2021-12-31">31</time>
          </button>
        </div>
        <div class="py-2">
          <button
            type="button"
            class="
              mx-auto
              flex
              h-8
              w-8
              items-center
              justify-center
              rounded-full
              text-gray-900
              hover:bg-gray-200
            "
          >
            <time datetime="2022-01-01">1</time>
          </button>
        </div>
        <div class="py-2">
          <button
            type="button"
            class="
              mx-auto
              flex
              h-8
              w-8
              items-center
              justify-center
              rounded-full
              text-gray-900
              hover:bg-gray-200
            "
          >
            <time datetime="2022-01-02">2</time>
          </button>
        </div>
        <div class="border-t border-gray-200 py-2">
          <button
            type="button"
            class="
              mx-auto
              flex
              h-8
              w-8
              items-center
              justify-center
              rounded-full
              text-gray-900
              hover:bg-gray-200
            "
          >
            <time datetime="2022-01-03">3</time>
          </button>
        </div>
        <div class="border-t border-gray-200 py-2">
          <button
            type="button"
            class="
              mx-auto
              flex
              h-8
              w-8
              items-center
              justify-center
              rounded-full
              text-gray-900
              hover:bg-gray-200
            "
          >
            <time datetime="2022-01-04">4</time>
          </button>
        </div>
        <div class="border-t border-gray-200 py-2">
          <button
            type="button"
            class="
              mx-auto
              flex
              h-8
              w-8
              items-center
              justify-center
              rounded-full
              text-gray-900
              hover:bg-gray-200
            "
          >
            <time datetime="2022-01-05">5</time>
          </button>
        </div>
        <div class="border-t border-gray-200 py-2">
          <button
            type="button"
            class="
              mx-auto
              flex
              h-8
              w-8
              items-center
              justify-center
              rounded-full
              text-gray-900
              hover:bg-gray-200
            "
          >
            <time datetime="2022-01-06">6</time>
          </button>
        </div>
        <div class="border-t border-gray-200 py-2">
          <button
            type="button"
            class="
              mx-auto
              flex
              h-8
              w-8
              items-center
              justify-center
              rounded-full
              text-gray-900
              hover:bg-gray-200
            "
          >
            <time datetime="2022-01-07">7</time>
          </button>
        </div>
        <div class="border-t border-gray-200 py-2">
          <button
            type="button"
            class="
              mx-auto
              flex
              h-8
              w-8
              items-center
              justify-center
              rounded-full
              text-gray-900
              hover:bg-gray-200
            "
          >
            <time datetime="2022-01-08">8</time>
          </button>
        </div>
        <div class="border-t border-gray-200 py-2">
          <button
            type="button"
            class="
              mx-auto
              flex
              h-8
              w-8
              items-center
              justify-center
              rounded-full
              text-gray-900
              hover:bg-gray-200
            "
          >
            <time datetime="2022-01-09">9</time>
          </button>
        </div>
        <div class="border-t border-gray-200 py-2">
          <button
            type="button"
            class="
              mx-auto
              flex
              h-8
              w-8
              items-center
              justify-center
              rounded-full
              text-gray-900
              hover:bg-gray-200
            "
          >
            <time datetime="2022-01-10">10</time>
          </button>
        </div>
        <div class="border-t border-gray-200 py-2">
          <button
            type="button"
            class="
              mx-auto
              flex
              h-8
              w-8
              items-center
              justify-center
              rounded-full
              text-gray-900
              hover:bg-gray-200
            "
          >
            <time datetime="2022-01-11">11</time>
          </button>
        </div>
        <div class="border-t border-gray-200 py-2">
          <button
            type="button"
            class="
              mx-auto
              flex
              h-8
              w-8
              items-center
              justify-center
              rounded-full
              font-semibold
              text-indigo-600
              hover:bg-gray-200
            "
          >
            <time datetime="2022-01-12">12</time>
          </button>
        </div>
        <div class="border-t border-gray-200 py-2">
          <button
            type="button"
            class="
              mx-auto
              flex
              h-8
              w-8
              items-center
              justify-center
              rounded-full
              text-gray-900
              hover:bg-gray-200
            "
          >
            <time datetime="2022-01-13">13</time>
          </button>
        </div>
        <div class="border-t border-gray-200 py-2">
          <button
            type="button"
            class="
              mx-auto
              flex
              h-8
              w-8
              items-center
              justify-center
              rounded-full
              text-gray-900
              hover:bg-gray-200
            "
          >
            <time datetime="2022-01-14">14</time>
          </button>
        </div>
        <div class="border-t border-gray-200 py-2">
          <button
            type="button"
            class="
              mx-auto
              flex
              h-8
              w-8
              items-center
              justify-center
              rounded-full
              text-gray-900
              hover:bg-gray-200
            "
          >
            <time datetime="2022-01-15">15</time>
          </button>
        </div>
        <div class="border-t border-gray-200 py-2">
          <button
            type="button"
            class="
              mx-auto
              flex
              h-8
              w-8
              items-center
              justify-center
              rounded-full
              text-gray-900
              hover:bg-gray-200
            "
          >
            <time datetime="2022-01-16">16</time>
          </button>
        </div>
        <div class="border-t border-gray-200 py-2">
          <button
            type="button"
            class="
              mx-auto
              flex
              h-8
              w-8
              items-center
              justify-center
              rounded-full
              text-gray-900
              hover:bg-gray-200
            "
          >
            <time datetime="2022-01-17">17</time>
          </button>
        </div>
        <div class="border-t border-gray-200 py-2">
          <button
            type="button"
            class="
              mx-auto
              flex
              h-8
              w-8
              items-center
              justify-center
              rounded-full
              text-gray-900
              hover:bg-gray-200
            "
          >
            <time datetime="2022-01-18">18</time>
          </button>
        </div>
        <div class="border-t border-gray-200 py-2">
          <button
            type="button"
            class="
              mx-auto
              flex
              h-8
              w-8
              items-center
              justify-center
              rounded-full
              text-gray-900
              hover:bg-gray-200
            "
          >
            <time datetime="2022-01-19">19</time>
          </button>
        </div>
        <div class="border-t border-gray-200 py-2">
          <button
            type="button"
            class="
              mx-auto
              flex
              h-8
              w-8
              items-center
              justify-center
              rounded-full
              text-gray-900
              hover:bg-gray-200
            "
          >
            <time datetime="2022-01-20">20</time>
          </button>
        </div>
        <div class="border-t border-gray-200 py-2">
          <button
            type="button"
            class="
              mx-auto
              flex
              h-8
              w-8
              items-center
              justify-center
              rounded-full
              bg-gray-900
              font-semibold
              text-white
            "
          >
            <time datetime="2022-01-21">21</time>
          </button>
        </div>
        <div class="border-t border-gray-200 py-2">
          <button
            type="button"
            class="
              mx-auto
              flex
              h-8
              w-8
              items-center
              justify-center
              rounded-full
              text-gray-900
              hover:bg-gray-200
            "
          >
            <time datetime="2022-01-22">22</time>
          </button>
        </div>
        <div class="border-t border-gray-200 py-2">
          <button
            type="button"
            class="
              mx-auto
              flex
              h-8
              w-8
              items-center
              justify-center
              rounded-full
              text-gray-900
              hover:bg-gray-200
            "
          >
            <time datetime="2022-01-23">23</time>
          </button>
        </div>
        <div class="border-t border-gray-200 py-2">
          <button
            type="button"
            class="
              mx-auto
              flex
              h-8
              w-8
              items-center
              justify-center
              rounded-full
              text-gray-900
              hover:bg-gray-200
            "
          >
            <time datetime="2022-01-24">24</time>
          </button>
        </div>
        <div class="border-t border-gray-200 py-2">
          <button
            type="button"
            class="
              mx-auto
              flex
              h-8
              w-8
              items-center
              justify-center
              rounded-full
              text-gray-900
              hover:bg-gray-200
            "
          >
            <time datetime="2022-01-25">25</time>
          </button>
        </div>
        <div class="border-t border-gray-200 py-2">
          <button
            type="button"
            class="
              mx-auto
              flex
              h-8
              w-8
              items-center
              justify-center
              rounded-full
              text-gray-900
              hover:bg-gray-200
            "
          >
            <time datetime="2022-01-26">26</time>
          </button>
        </div>
        <div class="border-t border-gray-200 py-2">
          <button
            type="button"
            class="
              mx-auto
              flex
              h-8
              w-8
              items-center
              justify-center
              rounded-full
              text-gray-900
              hover:bg-gray-200
            "
          >
            <time datetime="2022-01-27">27</time>
          </button>
        </div>
        <div class="border-t border-gray-200 py-2">
          <button
            type="button"
            class="
              mx-auto
              flex
              h-8
              w-8
              items-center
              justify-center
              rounded-full
              text-gray-900
              hover:bg-gray-200
            "
          >
            <time datetime="2022-01-28">28</time>
          </button>
        </div>
        <div class="border-t border-gray-200 py-2">
          <button
            type="button"
            class="
              mx-auto
              flex
              h-8
              w-8
              items-center
              justify-center
              rounded-full
              text-gray-900
              hover:bg-gray-200
            "
          >
            <time datetime="2022-01-29">29</time>
          </button>
        </div>
        <div class="border-t border-gray-200 py-2">
          <button
            type="button"
            class="
              mx-auto
              flex
              h-8
              w-8
              items-center
              justify-center
              rounded-full
              text-gray-900
              hover:bg-gray-200
            "
          >
            <time datetime="2022-01-30">30</time>
          </button>
        </div>
        <div class="border-t border-gray-200 py-2">
          <button
            type="button"
            class="
              mx-auto
              flex
              h-8
              w-8
              items-center
              justify-center
              rounded-full
              text-gray-900
              hover:bg-gray-200
            "
          >
            <time datetime="2022-01-31">31</time>
          </button>
        </div>
        <div class="border-t border-gray-200 py-2">
          <button
            type="button"
            class="
              mx-auto
              flex
              h-8
              w-8
              items-center
              justify-center
              rounded-full
              text-gray-400
              hover:bg-gray-200
            "
          >
            <time datetime="2022-02-01">1</time>
          </button>
        </div>
        <div class="border-t border-gray-200 py-2">
          <button
            type="button"
            class="
              mx-auto
              flex
              h-8
              w-8
              items-center
              justify-center
              rounded-full
              text-gray-400
              hover:bg-gray-200
            "
          >
            <time datetime="2022-02-02">2</time>
          </button>
        </div>
        <div class="border-t border-gray-200 py-2">
          <button
            type="button"
            class="
              mx-auto
              flex
              h-8
              w-8
              items-center
              justify-center
              rounded-full
              text-gray-400
              hover:bg-gray-200
            "
          >
            <time datetime="2022-02-03">3</time>
          </button>
        </div>
        <div class="border-t border-gray-200 py-2">
          <button
            type="button"
            class="
              mx-auto
              flex
              h-8
              w-8
              items-center
              justify-center
              rounded-full
              text-gray-400
              hover:bg-gray-200
            "
          >
            <time datetime="2022-02-04">4</time>
          </button>
        </div>
        <div class="border-t border-gray-200 py-2">
          <button
            type="button"
            class="
              mx-auto
              flex
              h-8
              w-8
              items-center
              justify-center
              rounded-full
              text-gray-400
              hover:bg-gray-200
            "
          >
            <time datetime="2022-02-05">5</time>
          </button>
        </div>
        <div class="border-t border-gray-200 py-2">
          <button
            type="button"
            class="
              mx-auto
              flex
              h-8
              w-8
              items-center
              justify-center
              rounded-full
              text-gray-400
              hover:bg-gray-200
            "
          >
            <time datetime="2022-02-06">6</time>
          </button>
        </div>
      </div>
    </div>
  </div>
</template>
