<script>
  import "virtual:windi.css"

  // if you want to enable windi devtools
  import { browser } from "$app/env";
  if (browser) import("virtual:windi-devtools")
  // ...
</script>

<main class="h-screen bg-red-900">
	<slot />
</main>