 <template>
   <div class="calculator">
       <Display />
       <Button label="AC" triple @onCalButtonClick="clearMemory" />
       <Button label="/" operation @onCalButtonClick="setOperation" />
       <Button label="8" operation @onCalButtonClick="addDigit" />
       <Button label="7" @onCalButtonClick="addDigit" />
       <Button label="6" @onCalButtonClick="addDigit" />
       <Button label="0" double />
       <Button label="." />
       <Button label="=" operation />
   </div>
 </template>
 
 <script>
import Display from '../components/Display.vue'
import Button from '../components/Button.vue'

 export default {
     components: { Button, Display },
     methods: {
      clearMemory(){

      },
      setOperation(operation){

      },
      addDigit(n){

       }
     }
 }
 </script>
 
 <style>
 
 </style>