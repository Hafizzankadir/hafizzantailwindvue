<template>
  <div class="hello">
   <img class="w-32 h-32 md:w-48 md:h-auto md:rounded-none rounded-full mx-auto" src="../assets/img/kim.jpeg" alt="" width="384" height="512">
  <div class="pt-6 md:p-8 text-center md:text-left space-y-4">
    <blockquote>
      <p class="text-lg font-semibold">
        “I like to program, read book, do a lot of sport such as running and weightlifting and also eat a lot of pizza”
      </p>
    </blockquote>
    <figcaption class="font-medium">
      <div class="text-cyan-600">
        Muhammad Nur Hafizzan Bin Kadir
      </div>
      <div class="text-gray-500">
        19FTT1159
      </div>
    </figcaption>
  </div>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>

