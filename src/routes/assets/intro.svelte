<script>
    import "tailwindcss/tailwind.css";
    function mail() {
        open("mailto:Amritanshu@duck.com")
    }
</script>
<div class="hero min-h-screen bg-base-200">
    <div class="hero-content text-center">
      <div class="max-w-md">
        <h1 class="text-5xl font-bold">Hi there!</h1>
        <p class="py-6">I am AK.<br/> I am a Web Developer.<br/> I work with html,css and javascript.</p>
        <button class="btn btn-primary" on:click={mail}>Contact Me 📞</button>
      </div>
    </div>
  </div>