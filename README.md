# Select2

## Chargement de select 2 et Jquery

    <script src="https://code.jquery.com/jquery-3.5.1.min.js"></script>
    <link href="https://cdnjs.cloudflare.com/ajax/libs/select2/4.1.0-beta.1/css/select2.min.css" rel="stylesheet">
    <script src="https://cdnjs.cloudflare.com/ajax/libs/select2/4.1.0-beta.1/js/select2.min.js"></script>
    
    
## Implemetation 

       // JS    
       <script>
        $(document).ready(function(){
            var sportlist = [
                  "crickey","vollleyball","Rubby", "Tennis","Baseball"
            ];
            
            $(".sports").select2({
                placeholder: "Selecte Sport",
                data: sportlist
            });
            
         })
      </script>
      
      // Html
      
      <!-- Simple selected -->
      <select class="sports" name="sport">
        
      </select>
      
      <!-- Multiple selected -->
      <select class="sports" name="sports[]" multiple="multiple">
        
      </select>
      
      
   
