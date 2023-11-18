<script>
  import { focusTrap } from '@skeletonlabs/skeleton';
  let isFocused = true;
</script>

<h1 class="h1 max-w-lg m-auto text-center p-6">Sign up to start listening ad free!</h1>
<div class="flex justify-center ">
<div class="w-6/12">

  <form class="w-full card p-4 text-token space-y-4" use:focusTrap={isFocused}>
    <label class="label">
      <span>Name</span>
      <input class="input" type="text" placeholder="Enter name..." />
    </label>
    <label class="label">
      <span>Email</span>
      <input class="input" type="email" placeholder="Enter email address..." />
    </label>
    <div class="text-right">
      <button class="btn variant-filled-primary">Next</button>
    </div>
  </form>
</div>
</div>
<hr class="m-6">
<div class="flex justify-center ">
<div class="w-6/12">
  <div class="logo-cloud grid-cols-1 lg:!grid-cols-3 gap-1">
    <a class="logo-item" href="/">
      <span>Signup with Google</span>
    </a>
    <a class="logo-item" href="/">
      <span>Signup with Facebook</span>
    </a>
    <a class="logo-item" href="/">
      <span>Signup with Apple</span>
    </a>
    <!-- ... -->
  </div>

</div>
</div>
<hr class="m-6">
<p class="text-lg max-w-lg m-auto text-center p-6">Have an account? <a class="underline" href="/">Login</a></p>