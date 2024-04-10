<script>
  import CardProfile from "./components/CardProfile.svelte";
  import CardSection from "./components/CardSection.svelte";

  function updateTheme() {
    if (localStorage.theme === 'dark' || (!('theme' in localStorage) && window.matchMedia('(prefers-color-scheme: dark)').matches)) {
      document.documentElement.classList.add('dark');
    } else {
      document.documentElement.classList.remove('dark');
    }
  }
  updateTheme();
</script>

<div class="flex flex-row">
  <CardProfile/>
  <CardSection/>
</div>