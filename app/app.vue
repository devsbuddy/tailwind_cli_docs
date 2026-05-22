<template>
  <NuxtRouteAnnouncer />
  <div
    class="min-h-screen bg-linear-to-b from-slate-950 via-slate-900 to-slate-950 text-slate-100"
  >
    <main
      class="mx-auto flex min-h-screen w-full max-w-4xl items-center px-6 py-16"
    >
      <section
        class="w-full rounded-2xl border border-white/10 bg-white/5 p-8 shadow-2xl shadow-cyan-900/20 backdrop-blur"
      >
        <p
          class="mb-3 inline-flex items-center rounded-full border border-cyan-300/30 bg-cyan-300/10 px-3 py-1 text-xs font-semibold uppercase tracking-wider text-cyan-200"
        >
          Tailwind CLI for Flutter
        </p>

        <h1 class="text-3xl font-bold leading-tight md:text-4xl">
          Build Flutter styles with familiar Tailwind utility classes.
        </h1>

        <p class="mt-4 max-w-2xl text-sm leading-6 text-slate-300 md:text-base">
          A tiny, developer-friendly CLI that helps you write utility-first
          styles for Flutter projects. Simple setup, fast output, and easy to
          use.
        </p>

        <div class="mt-8 flex flex-wrap items-center gap-3">
          <a
            href="https://pub.dev/packages/tailwind_cli"
            rel="noreferrer"
            target="_blank"
            class="inline-flex items-center rounded-lg bg-cyan-400 px-4 py-2 text-sm font-semibold text-slate-950 shadow-lg shadow-cyan-900/30 transition duration-200 hover:-translate-y-0.5 hover:bg-cyan-300"
          >
            View on pub.dev
          </a>
          <a
            href="https://github.com/devsbuddy/tailwind_cli"
            rel="noreferrer"
            target="_blank"
            class="inline-flex items-center rounded-lg border border-slate-500/70 bg-slate-900/50 px-4 py-2 text-sm font-semibold text-slate-200 transition duration-200 hover:-translate-y-0.5 hover:border-slate-300 hover:text-white"
          >
            GitHub
          </a>
          <a
            href="/docs/"
            class="inline-flex items-center rounded-lg border border-cyan-300/40 bg-cyan-400/10 px-4 py-2 text-sm font-semibold text-cyan-200 transition duration-200 hover:-translate-y-0.5 hover:border-cyan-200 hover:bg-cyan-300/20 hover:text-cyan-100"
          >
            Documentation
          </a>
        </div>

        <div class="mt-8 grid gap-3 sm:grid-cols-3">
          <div class="rounded-lg border border-white/10 bg-black/20 p-4">
            <p class="text-sm font-semibold text-white">Small &amp; Fast</p>
            <p class="mt-1 text-xs text-slate-300">
              Focused CLI experience with clean commands.
            </p>
          </div>
          <div class="rounded-lg border border-white/10 bg-black/20 p-4">
            <p class="text-sm font-semibold text-white">Utility-First</p>
            <p class="mt-1 text-xs text-slate-300">
              Compose styles quickly using Tailwind-like class names.
            </p>
          </div>
          <div class="rounded-lg border border-white/10 bg-black/20 p-4">
            <p class="text-sm font-semibold text-white">Flutter Ready</p>
            <p class="mt-1 text-xs text-slate-300">
              Designed for modern Flutter workflows from day one.
            </p>
          </div>
        </div>
      </section>
    </main>
  </div>
</template>
