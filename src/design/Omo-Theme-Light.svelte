<script>
  import OmoDesignBase from "./Omo-Design-Base.svelte";
  import OmoDesignUtilities from "./Omo-Design-Utilities.svelte";
</script>

<style global>
  @tailwind components;
  .text-ci {
    color: #ee9590;
  }
  .text-ci-2 {
    color: #8170b6;
  }
  .text-action {
    color: #58c087;
  }

  .bg-ci {
    background-color: #ee9590;
  }

  .bg-ci-2 {
    background-color: #8170b6;
  }

  .bg-action {
    background-color: #58c087;
  }

  .bg-info {
    background-color: #f8d571;
  }

  .primary {
    @apply bg-gray-100 text-gray-800;
  }

  .app {
    @apply bg-gray-200 h-screen w-full;
  }

  .button {
    @apply bg-blue-800 text-white px-4 py-2 rounded-lg  uppercase font-semibold text-sm tracking-wider;
  }

  .button:hover {
    @apply bg-blue-700;
  }

  .button:active {
    @apply bg-green-400;
  }
  .omo-border {
    @apply border-solid border border-gray-300 rounded-lg;
  }

  .omo-shadow {
    @apply shadow-sm;
  }

  @tailwind utilities;
</style>

<OmoDesignBase />
<OmoDesignUtilities />
