<script setup lang="ts">
const date = ref(new Date());
</script>

<template>
  <div class="min-h-screen min-w-scren bg-black">
    <div class="p-8 space-y-8">
      <div class="border border-white">
        <div class="flex justify-between">
          <button
            class="w-full h-full text-white hover:bg-white hover:text-black p-4 cursor-pointer"
          >
            <h1 class="text-2xl uppercase">о проекте</h1>
          </button>

          <button
            class="w-full h-full text-white hover:bg-white hover:text-black p-4 cursor-pointer"
          >
            <h1 class="text-2xl uppercase">Материалы</h1>
          </button>

          <button
            class="w-full h-full text-white hover:bg-white hover:text-black p-4 cursor-pointer"
          >
            <h1 class="text-2xl uppercase">Москва</h1>
          </button>

          <button
            class="w-full h-full text-white hover:bg-white hover:text-black p-4 cursor-pointer"
          >
            <h1 class="text-2xl uppercase">Креветка</h1>
          </button>
        </div>
      </div>
      <div class="text-center">
        <h1 class="uppercase text-8xl text-white">://DEAD.</h1>
      </div>

      <div class="grid grid-cols-4">
        <div>
          <img
            src="https://bf.sistema.ru/local/templates/bf-futuretense/images/2019/%D0%98%D0%BB%D0%BB%D1%8E%D1%81%D1%82%D1%80%D0%B0%D1%86%D0%B8%D1%8F%203.jpg"
          />
        </div>
      </div>

      <div class="flex justify-between">
        <div>
          <h1 class="text-white">Hello</h1>
          <h1 class="text-white">Hello</h1>
          <h1 class="text-white">Hello</h1>
          <h1 class="text-white">Hello</h1>
          <h1 class="text-white">Hello</h1>
        </div>
      </div>

      <div class="border border-white">
        <div class="text-white">
          <h1 class="text-xl uppercase">Материалы</h1>
        </div>
      </div>

      <div class="max-w-sm mx-auto">
        <div class="flex justify-between items-center gap-16">
          <div class="border border-white bg-gray-900 p-4 min-w-72">
            <h1 class="text-xl text-white uppercase underline">Материалы</h1>

            <p class="text-white">
              365 strokes representing the hours of darkness of each day. A
              recreation of the 2011 calendar by Accept & Proceed.
            </p>
          </div>

          <div>
            <h1 class="uppercase text-8xl text-white slashed-zero">09</h1>
          </div>
        </div>
      </div>
    </div>
  </div>
  <div class="min-w-screen min-h-screen bg-black">
    <div class="flex">
      <h1 class="uppercase text-white text-2xl overflow-y-hidden">
        ou can see at the bottom that I’m also calling the split the squares on
        the x and y, b see at the bottom that I’m also
      </h1>
    </div>
    <div class="flex">
      <div style="min-width: 40%" class="min-w-96 min-h-screen bg-gray-800">
        a
      </div>
      <div class="min-h-screen min-w-12 border border-white border-y-0">
        afsd
      </div>
      <div class="min-h-screen border border-white border-y-0">
        <div class="flex justify-between py-6 px-12">
          <p class="text-white">
            You can see at the bottom that I’m also calling the split the
            squares on the x and y, both in the middle. If these work, we’ll
            know we can do a lot more splitting. But for now, these will be
            great for testing.
          </p>

          <p class="text-white">
            You can see at the bottom that I’m also calling the split the
            squares on the x and y, both in the middle. If these work, we’ll
            know we can do a lot more splitting. But for now, these will be
            great for testing.
          </p>
        </div>

        <div class="flex justify-between py-6 px-12">
          <p class="text-white">
            You can see at the bottom that I’m also calling the split the
            squares on the x and y, both in the middle. If these work, we’ll
            know we can do a lot more splitting. But for now, these will be
            great for testing.
          </p>

          <p class="text-white">
            You can see at the bottom that I’m also calling the split the
            squares on the x and y, both in the middle. If these work, we’ll
            know we can do a lot more splitting. But for now, these will be
            great for testing.
          </p>
        </div>
      </div>
      <div class="min-h-screen min-w-12 border border-white border-y-0">
        afsd
      </div>
      <div class="min-h-screen min-w-12 border border-white border-y-0">
        afsd
      </div>
      <div class="min-h-screen min-w-12 border border-white border-y-0">
        afsd
      </div>
      <div class="min-h-screen min-w-12 border border-white border-y-0">
        afsd
      </div>
    </div>
  </div>

  <div class="min-w-screen min-h-screen bg-gray-900">
    <div class="grid grid-cols-4 px-8">
      <WindowText />
      <WindowText />
      <WindowText />
    </div>
  </div>

  {{ date }}
</template>
