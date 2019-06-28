# Content
This directory contains the specifications for a React Suspense simulation of functionality, 
expressed as a Kingly state machine.  

# API
<Suspense let:dispatch={dispatch} settings=... {commandHandlers}? {effectHandlers}?>
  <Spinner slot="fallback" ...props />
  <Main on:load="{... => dispatch ...}" />
</Suspense>

# Machine component
The Svelte `<Machine>` component is based on [Kingly](https://github.com/brucou/kingly) (though it would also work with any other 
machine library which adheres to the same interface as Kingly). The corresponding file is `Machine.svelte`. 

# Install
`import <your-name> from 'svelte-machine'`
