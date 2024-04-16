<script>
  import CardProfile from "./components/CardProfile.svelte";
  import CardSection from "./components/CardSection.svelte";

  function updateTheme() {
    const theme = localStorage.theme || (window.matchMedia('(prefers-color-scheme: dark)').matches ? 'dark' : 'light');
    document.documentElement.classList.remove('dark', 'light');
    document.documentElement.classList.add(theme);
  }

  updateTheme();
</script>

<body class="bg-background">
  <div class="flex flex-row place-content-center">
    <CardProfile/>
    <CardSection/>
  </div>
</body>

<style>
  @import url('https://fonts.googleapis.com/css2?family=Tilt+Neon&display=swap');
  
  :global(body) {
    font-family: "Tilt Neon", sans-serif;
    transition: all 0.3s;
  }
</style>