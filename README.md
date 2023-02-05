<html>
<head></head>
<style>
    .blink {
        animation: blinker 1.5s linear infinite;
        color:aquamarine;
        font-family: sans-serif;
    }
    @keyframes blinker {
        50% {
            opacity: 0;
        }
    }
    #mtable {
        font-family: Arial, Helvetica, sans-serif;
        border-collapse: collapse;
        width: 30%;
      }

      #mtable td, #mtable th {
        border: 1px solid #ddd;
        padding: 8px;
        }
      #mtable tr:nth-child(even){background-color: #dcfffa;}

      #mtable tr:nth-child(odd){background-color: #F5DEB3;}
    
</style>

  <body bgcolor="black">
    
    
    <h1 class="blink"><marquee bgcolor="">monthly chick plan</marquee></h1>
    <center>
        <input type="button" value="month1" onclick="month1()" />
        
    
    &nbsp;<input type="button" value="month2" onclick="month2()" />
    &nbsp;<input type="button" value="month3" onclick="month3()" />
    &nbsp;<input type="button" value="month4" onclick="month4()" />
    &nbsp;<input type="button" value="month5&6" onclick="month56()" /> 
    
        <div id="result"></div>

       <script>

            function month1() {
            var table;
            table='<table id="mtable" align="center">';

            var num=30;
            
            
               for(i=10;i<=100;){
                  table+='<tr><td>'+num+'g*'+i+'H='+num*i+'</td></tr>';
                  i+=10;
               }
               for(i=100;i<=1001;){
                table+='<tr><td>'+num+'g*'+i+'H='+num*i+'</td></tr>';
                i+=50;
             }

            table+='</table>';
           document.getElementById("result").innerHTML = table;
            }
            function month2() {
                var table;
                table='<table id="mtable" align="center">';
    
                var num=50;
                
                
                   for(i=10;i<=100;){
                      table+='<tr><td>'+num+'g*'+i+'H='+num*i+'</td></tr>';
                      i+=10;
                   }
                   for(i=100;i<=1001;){
                    table+='<tr><td>'+num+'g*'+i+'H='+num*i+'</td></tr>';
                    i+=50;
                 }
    
                table+='</table>';
               document.getElementById("result").innerHTML = table;
                }
                function month3() {
                    var table;
                    table='<table id="mtable" align="center">';
        
                    var num=70;
                    
                    
                       for(i=10;i<=100;){
                          table+='<tr><td>'+num+'g*'+i+'H='+num*i+'</td></tr>';
                          i+=10;
                       }
                       for(i=100;i<=1001;){
                        table+='<tr><td>'+num+'g*'+i+'H='+num*i+'</td></tr>';
                        i+=50;
                     }
        
                    table+='</table>';
                   document.getElementById("result").innerHTML = table;
                    }
                    function month4() {
                        var table;
                        table='<table id="mtable" align="center">';
            
                        var num=90;
                        
                        
                           for(i=10;i<=100;){
                              table+='<tr><td>'+num+'g*'+i+'H='+num*i+'</td></tr>';
                              i+=10;
                           }
                           for(i=100;i<=1001;){
                            table+='<tr><td>'+num+'g*'+i+'H='+num*i+'</td></tr>';
                            i+=50;
                         }
            
                        table+='</table>';
                       document.getElementById("result").innerHTML = table;
                        }
                        function month56() {
                            var table;
                            table='<table id="mtable" align="center">';
                
                            var num=110;
                            
                            
                               for(i=10;i<=100;){
                                  table+='<tr><td>'+num+'g*'+i+'H='+num*i+'</td></tr>';
                                  i+=10;
                               }
                               for(i=100;i<=1001;){
                                table+='<tr><td>'+num+'g*'+i+'H='+num*i+'</td></tr>';
                                i+=50;
                             }
                
                            table+='</table>';
                           document.getElementById("result").innerHTML = table;
                            }
        </script>
    </body>
</html>
