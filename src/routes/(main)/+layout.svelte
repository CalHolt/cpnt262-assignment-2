<script>
  import { AppRail, AppRailAnchor, Avatar, AppShell, AppBar } from '@skeletonlabs/skeleton';

</script>
<AppShell>
  <AppBar>
    
    <svelte:fragment slot="lead"><svg xmlns="http://www.w3.org/2000/svg" height="2em" viewBox="0 0 512 512"><!--! Font Awesome Free 6.4.2 by @fontawesome - https://fontawesome.com License - https://fontawesome.com/license (Commercial License) Copyright 2023 Fonticons, Inc. --><style>svg{fill:#fefefe}</style><path d="M256 80C149.9 80 62.4 159.4 49.6 262c9.4-3.8 19.6-6 30.4-6c26.5 0 48 21.5 48 48V432c0 26.5-21.5 48-48 48c-44.2 0-80-35.8-80-80V384 336 288C0 146.6 114.6 32 256 32s256 114.6 256 256v48 48 16c0 44.2-35.8 80-80 80c-26.5 0-48-21.5-48-48V304c0-26.5 21.5-48 48-48c10.8 0 21 2.1 30.4 6C449.6 159.4 362.1 80 256 80z"/></svg></svelte:fragment>
    <h1 class="h1">Music Platform</h1>
    <svelte:fragment slot="trail"><a href="/signup" class="btn variant-filled-primary">Signup</a> <a href="/" class="btn variant-filled-primary">Login</a></svelte:fragment>
  </AppBar>
<svelte:fragment slot="sidebarLeft" >
<AppRail>
  <svelte:fragment slot="lead">
    <AppRailAnchor href="/" title="Account"><Avatar class='mx-2'
      border="border-4 border-surface-300-600-token hover:!border-primary-500"
    /></AppRailAnchor>
  </svelte:fragment>
  <!-- --- -->
  <AppRailAnchor href="/music" target="_blank" title="Account">
    <svelte:fragment slot="lead"></svelte:fragment>
    <span>Music</span>
  </AppRailAnchor>
  <AppRailAnchor href="/" target="_blank" title="Account">
    <svelte:fragment slot="lead"></svelte:fragment>
    <span>Podcasts</span>
  </AppRailAnchor>
  <AppRailAnchor href="/" target="_blank" title="Account">
    <svelte:fragment slot="lead"></svelte:fragment>
    <span>Live</span>
  </AppRailAnchor>
  <!-- --- -->
  <svelte:fragment slot="trail">
    <AppRailAnchor href="/" target="_blank"><div class="mx-7"><svg xmlns="http://www.w3.org/2000/svg" height="2em" viewBox="0 0 512 512"><!--! Font Awesome Free 6.4.2 by @fontawesome - https://fontawesome.com License - https://fontawesome.com/license (Commercial License) Copyright 2023 Fonticons, Inc. --><style>svg{fill:#fefefe}</style><path d="M495.9 166.6c3.2 8.7 .5 18.4-6.4 24.6l-43.3 39.4c1.1 8.3 1.7 16.8 1.7 25.4s-.6 17.1-1.7 25.4l43.3 39.4c6.9 6.2 9.6 15.9 6.4 24.6c-4.4 11.9-9.7 23.3-15.8 34.3l-4.7 8.1c-6.6 11-14 21.4-22.1 31.2c-5.9 7.2-15.7 9.6-24.5 6.8l-55.7-17.7c-13.4 10.3-28.2 18.9-44 25.4l-12.5 57.1c-2 9.1-9 16.3-18.2 17.8c-13.8 2.3-28 3.5-42.5 3.5s-28.7-1.2-42.5-3.5c-9.2-1.5-16.2-8.7-18.2-17.8l-12.5-57.1c-15.8-6.5-30.6-15.1-44-25.4L83.1 425.9c-8.8 2.8-18.6 .3-24.5-6.8c-8.1-9.8-15.5-20.2-22.1-31.2l-4.7-8.1c-6.1-11-11.4-22.4-15.8-34.3c-3.2-8.7-.5-18.4 6.4-24.6l43.3-39.4C64.6 273.1 64 264.6 64 256s.6-17.1 1.7-25.4L22.4 191.2c-6.9-6.2-9.6-15.9-6.4-24.6c4.4-11.9 9.7-23.3 15.8-34.3l4.7-8.1c6.6-11 14-21.4 22.1-31.2c5.9-7.2 15.7-9.6 24.5-6.8l55.7 17.7c13.4-10.3 28.2-18.9 44-25.4l12.5-57.1c2-9.1 9-16.3 18.2-17.8C227.3 1.2 241.5 0 256 0s28.7 1.2 42.5 3.5c9.2 1.5 16.2 8.7 18.2 17.8l12.5 57.1c15.8 6.5 30.6 15.1 44 25.4l55.7-17.7c8.8-2.8 18.6-.3 24.5 6.8c8.1 9.8 15.5 20.2 22.1 31.2l4.7 8.1c6.1 11 11.4 22.4 15.8 34.3zM256 336a80 80 0 1 0 0-160 80 80 0 1 0 0 160z"/></svg></div></AppRailAnchor>
  </svelte:fragment>
</AppRail>
</svelte:fragment>
<slot />
<svelte:fragment slot="pageFooter">
		<h6 class="h5 mx-2">Want to listen to your favourite songs and podcasts ad free ?</h6>
		<p class="text-md mx-2">Sign up today and get ad free listening </p>
</svelte:fragment>
</AppShell>