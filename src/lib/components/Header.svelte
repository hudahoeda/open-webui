<script>
  import { WEBUI_NAME } from '$lib/stores';
  import { ExternalLink } from 'lucide-svelte';
</script>

<header class="bg-background border-b">
  <div class="container mx-auto px-4 py-3">
    <nav class="flex items-center justify-between">
      <div class="flex items-center space-x-2">
        <a href="/" class="text-xl font-semibold text-foreground">
          {$WEBUI_NAME}
        </a>
      </div>
      
      <div class="flex items-center space-x-6">
        <a 
          href="https://github.com/open-webui/open-webui" 
          target="_blank" 
          rel="noopener noreferrer"
          class="flex items-center gap-1 text-sm text-muted-foreground hover:text-foreground transition-colors"
        >
          GitHub <ExternalLink class="h-4 w-4" />
        </a>
        <a 
          href="https://discord.gg/open-webui" 
          target="_blank" 
          rel="noopener noreferrer"
          class="flex items-center gap-1 text-sm text-muted-foreground hover:text-foreground transition-colors"
        >
          Discord <ExternalLink class="h-4 w-4" />
        </a>
        <a 
          href="https://docs.openwebui.com" 
          target="_blank" 
          rel="noopener noreferrer"
          class="flex items-center gap-1 text-sm text-muted-foreground hover:text-foreground transition-colors"
        >
          Documentation <ExternalLink class="h-4 w-4" />
        </a>
      </div>
    </nav>
  </div>
</header> 