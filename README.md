# Content
This directory contains the specifications for a React Suspense simulation of functionality, 
expressed as a Kingly state machine.  

# API
<Suspense let:intents={{done, failed}} task timeout >
  <Spinner slot="fallback" ...props />
  <Main on:load="{... => done(...}" />
</Suspense>

# Machine component
The Svelte `<Machine>` component is based on [Kingly](https://github.com/brucou/kingly) (though it would also work with any other 
machine library which adheres to the same interface as Kingly). The corresponding file is `Suspense.svelte`. 

# Install
`import <your-name> from 'svelte-machine'`

# Demo
[Svelte suspense demo](https://github.com/brucou/svelte-suspense-app)
