<template>
  <router-link to="/lists">
    <div class="inline-flex hover:bg-ashy hover:transition rounded-full p-3">
      <svg viewBox="0 0 24 24" class="h-6 w-6">
        <g>
          <path
            d="M19.75 22H4.25C3.01 22 2 20.99 2 19.75V4.25C2 3.01 3.01 2 4.25 2h15.5C20.99 2 22 3.01 22 4.25v15.5c0 1.24-1.01 2.25-2.25 2.25zM4.25 3.5c-.414 0-.75.337-.75.75v15.5c0 .413.336.75.75.75h15.5c.414 0 .75-.337.75-.75V4.25c0-.413-.336-.75-.75-.75H4.25z"
          ></path>
          <path
            d="M17 8.64H7c-.414 0-.75-.337-.75-.75s.336-.75.75-.75h10c.414 0 .75.335.75.75s-.336.75-.75.75zm0 4.11H7c-.414 0-.75-.336-.75-.75s.336-.75.75-.75h10c.414 0 .75.336.75.75s-.336.75-.75.75zm-5 4.11H7c-.414 0-.75-.335-.75-.75s.336-.75.75-.75h5c.414 0 .75.337.75.75s-.336.75-.75.75z"
          ></path>
        </g>
      </svg>
      <svg viewBox="0 0 24 24" class="h-6 w-6 absolute opacity-0">
        <g>
          <path
            d="M19.75 2H4.25C3.013 2 2 3.013 2 4.25v15.5C2 20.987 3.013 22 4.25 22h15.5c1.237 0 2.25-1.013 2.25-2.25V4.25C22 3.013 20.987 2 19.75 2zM11 16.75H7c-.414 0-.75-.336-.75-.75s.336-.75.75-.75h4c.414 0 .75.336.75.75s-.336.75-.75.75zm6-4H7c-.414 0-.75-.336-.75-.75s.336-.75.75-.75h10c.414 0 .75.336.75.75s-.336.75-.75.75zm0-4H7c-.414 0-.75-.336-.75-.75s.336-.75.75-.75h10c.414 0 .75.336.75.75s-.336.75-.75.75z"
          ></path>
        </g>
      </svg>
      <span class="ml-5 xl:block hidden">Lists</span>
    </div>
  </router-link>
</template>

<style scoped>
.router-link-exact-active div {
  font-weight: bold;
}

.router-link-exact-active div svg:first-child {
  opacity: 0;
}

.router-link-exact-active div svg:nth-child(2) {
  opacity: 1;
}
</style>
