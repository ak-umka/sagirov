<template>
  <nav class="lg:px-6 py-10 dark:bg-gray-800">
    <div
      class="flex flex-wrap justify-between items-center mx-auto max-w-screen-xl"
    >
      <img
            src="../assets/icons/logo.png"
            class="mr-3"
          />
      <!-- <img src="../assets/icons/logoStyle.png"/> -->
      <!-- <span
        class="self-center text-xl font-semibold whitespace-nowrap dark:text-white"
        >SpaceX</span
      > -->

      <div
        class="hidden justify-between items-center w-full lg:flex lg:w-auto lg:order-1"
        id="mobile-menu-2"
      >
        <ul
          class="flex flex-col mt-4 font-medium lg:flex-row lg:space-x-8 lg:mt-0"
        >
          <li>
            <router-link
              to="/"
              class="block py-2 pr-4 pl-3 text-white rounded bg-primary-700 lg:bg-transparent lg:text-primary-700 lg:p-0 dark:text-white hover:text-[#817f81]"
              aria-current="page"
              >Главная</router-link
            >
          </li>
          <li>
            <a
              href="#"
              class="block py-2 pr-4 pl-3 text-white border-b border-gray-100 hover:text-[#817f81] lg:hover:bg-transparent lg:border-0 lg:hover:text-primary-700 lg:p-0 dark:text-gray-400 lg:dark:hover:text-white dark:hover:bg-gray-700 dark:hover:text-white lg:dark:hover:bg-transparent dark:border-gray-700"
              >Технология</a
            >
          </li>
          <li>
            <a
              href="#"
              class="block py-2 pr-4 pl-3 text-white border-b border-gray-100 hover:text-[#817f81] lg:hover:bg-transparent lg:border-0 lg:hover:text-primary-700 lg:p-0 dark:text-gray-400 lg:dark:hover:text-white dark:hover:bg-gray-700 dark:hover:text-white lg:dark:hover:bg-transparent dark:border-gray-700"
              >График Полетов</a
            >
          </li>
          <li>
            <a
              href="#"
              class="block py-2 pr-4 pl-3 text-white border-b border-gray-100 hover:text-[#817f81] lg:hover:bg-transparent lg:border-0 lg:hover:text-primary-700 lg:p-0 dark:text-gray-400 lg:dark:hover:text-white dark:hover:bg-gray-700 dark:hover:text-white lg:dark:hover:bg-transparent dark:border-gray-700"
              >Гарантии</a
            >
          </li>
          <li>
            <a
              href="/about"
              class="block py-2 pr-4 pl-3 text-white border-b border-gray-100 hover:text-[#817f81] lg:hover:bg-transparent lg:border-0 lg:hover:text-primary-700 lg:p-0 dark:text-gray-400 lg:dark:hover:text-white dark:hover:bg-gray-700 dark:hover:text-white lg:dark:hover:bg-transparent dark:border-gray-700"
              >О Компании</a
            >
          </li>
          <li>
            <router-link
              to="/about"
              class="block py-2 pr-4 pl-3 text-white border-b border-gray-100 hover:text-[#817f81] lg:hover:bg-transparent lg:border-0 lg:hover:text-primary-700 lg:p-0 dark:text-gray-400 lg:dark:hover:text-white dark:hover:bg-gray-700 dark:hover:text-white lg:dark:hover:bg-transparent dark:border-gray-700"
              >Контакты</router-link
            >
          </li>
        </ul>
      </div>
    </div>
  </nav>
</template>

<script>
</script>

<style lang="scss" scoped></style>
