<script setup>
   defineProps({
     class: {
       type: String,
       default: 'h-5 w-5',
     },
   });
   </script>

   <template>
     <svg :class="$props.class" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke="currentColor">
       <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M10 19l-7-7m0 0l7-7m-7 7h18" />
     </svg>
   </template>
