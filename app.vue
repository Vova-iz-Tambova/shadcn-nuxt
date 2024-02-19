<script setup lang="ts">
import { Mail, Loader2 } from "lucide-vue-next";
import { Button } from "@/components/ui/button";
</script>

<template>
  <Button>Primary</Button>
  <Button variant="secondary">Secondary</Button>
  <Button variant="destructive"> Destructive </Button>
  <Button variant="outline"> Outline </Button>
  <Button variant="ghost"> Ghost </Button>
  <Button variant="link"> Link </Button>
  <Button> <Mail class="w-4 h-4 mr-2" /> Login with Email </Button>
  <Button disabled>
    <Loader2 class="w-4 h-4 mr-2 animate-spin" />
    Please wait
  </Button>
</template>
