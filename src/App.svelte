<script>
  import Button from './Button.svelte';
</script>

<div class="p-[96px] bg-gray-100">
  
  <div class="space-y-4">
    <Button 
      buttonLabel="Button 1" 
      backgroundColor="#6B4EFF" 
      hoverColor="#E7E7FF" 
      textColor="#ffffff" 
      hoverTextColor="#6B4EFF" 
    /> 
    
    <Button 
      buttonLabel="Button 2" 
      backgroundColor="#5538EE" 
      hoverColor="#C6C4FF" 
      textColor="#ffffff" 
      hoverTextColor="#5538EE" 
    /> 
    
    <Button 
      buttonLabel="Button 3" 
      backgroundColor="#E3E5E5" 
      hoverColor="#E3E5E5" 
      textColor="#979C9E" 
      hoverTextColor="#979C9E" 
    /> 
  </div>
</div>

<style>
  h1 {
    font-family: 'Inter', sans-serif;
    color: #333; 
  }
</style>

<svelte:head>
  <link rel="stylesheet" href="https://unpkg.com/tailwindcss@2.2.19/dist/tailwind.min.css" />
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500&display=swap" rel="stylesheet" />
</svelte:head>