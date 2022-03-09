 <template>
   <div class="calculator">
       <Display />
       <Button />
   </div>
 </template>
 
 <script>
import Display from '../components/Display.vue'
import Button from '../components/Button.vue'

 export default {
     components: { Button, Display }
 }
 </script>
 
 <style>
 
 </style>