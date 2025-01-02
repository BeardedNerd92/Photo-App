<template>
  <section class="h-dvh flex justify-center items-center m-auto">
    <div>
      <h1 class="text-center">Register Account</h1>
      <form action="" class="mt-4">
        <label class="block">
          <span
            class="after:content-['*'] after:ml-0.5 after:text-red-500 block text-sm font-medium text-slate-700"
          >
            Email
          </span>
          <input
            type="email"
            name="email"
            class="mt-1 px-3 py-2 bg-white border shadow-sm border-slate-300 placeholder-slate-400 focus:outline-none focus:border-sky-500 focus:ring-sky-500 block w-full rounded-md sm:text-sm focus:ring-1"
            placeholder="you@example.com"
          />
        </label>

        <label class="block">
          <span
            class="after:content-['*'] after:ml-0.5 after:text-red-500 block text-sm font-medium text-slate-700"
          >
            Username
          </span>
          <input
            type="text"
            name="username"
            class="mt-1 px-3 py-2 bg-white border shadow-sm border-slate-300 placeholder-slate-400 focus:outline-none focus:border-sky-500 focus:ring-sky-500 block w-full rounded-md sm:text-sm focus:ring-1"
            placeholder="nzackgrooms92"
          />
        </label>

        <label class="block">
          <span
            class="after:content-['*'] after:ml-0.5 after:text-red-500 block text-sm font-medium text-slate-700"
          >
            Password
          </span>
          <input
            type="password"
            name="password"
            class="mt-1 px-3 py-2 bg-white border shadow-sm border-slate-300 placeholder-slate-400 focus:outline-none focus:border-sky-500 focus:ring-sky-500 block w-full rounded-md sm:text-sm focus:ring-1"
            placeholder="1234"
          />
        </label>
      </form>
    </div>
  </section>
</template>

<script>
console.log('Hello World')
</script>
