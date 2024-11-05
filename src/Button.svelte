<script>
  export let buttonLabel = "Button"; 
  export let backgroundColor = ''; 
  export let hoverColor = ''; 
  export let textColor = '#ffffff'; 
  export let hoverTextColor = '#ffffff'; 

  let isHovered = false;
</script>

<button
  class="w-[327px] h-[327px] rounded-full transition duration-300 ease-in-out"
  style={`background-color: ${isHovered ? hoverColor : backgroundColor}; color: ${isHovered ? hoverTextColor : textColor}; `}
  on:mouseenter={() => isHovered = true}
  on:mouseleave={() => isHovered = false}
>
  {buttonLabel}
</button>

<style>
  button {
    font-family: 'Inter', sans-serif;
    font-size: 16px;
    font-weight: 500;
    line-height: 1; 
    text-align: center;
    border: none; 
    cursor: pointer; 
    display: inline-flex; 
    justify-content: center; 
    align-items: center; 
		width: 327px;
		height: 48px;
  }
</style>