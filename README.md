1:
a.print odd numbers:
function(arr){
                  for(var i = 0 ; i< array.length ; i++){
                        if(array[i]%2!=0){
                           console.log(arr[i])
                        } 
                   }
                }
                
b.convert to caps in string:
function (str) {
                    str = str.toLowerCase().split(' ');
                    for (var i = 0; i < str.length; i++) {
                      str[i] = str[i].charAt(0).toUpperCase() + str[i].slice(1); 
                    } 
                    return str.join(' ');
                  }
                  
c.sum of all numbers:
function(array){
                  var sum = 0;
                  for(var i = 0 ; i< array.length ; i++){
                     sum = sum + array[i];
                   }
                   return sum;
                }
                
d.return all prime numbers:
  function(numArray){
                  numArray = numArray.filter((number) => {
                    for (var i = 2; i <= Math.sqrt(number); i++) {
                      if (number % i === 0) return false;
                      }
                      return true;
                     });
                    console.log(numArray);
                    
e.return all palindromes:
 function isPalindrome(S)
    {
        let str = "" + S;
        let len = str.length;
        for (let i = 0; i < +(len / 2, 10); i++)
        {
            if (str[i] != str[len - 1 - i ])
                return false;
        }
        return true;
    }    
  
  f.remove duplicates:
  var arr=["a","b","c","a","b","c"];
  function removeDuplicates(arr){
  return [...new Set(arr)];
  }
  console.log(removeDuplicates(arr);
  
  g.rotate array k times:
   function(array , k){
                          k = k % a.length;
                            if(k < 0){
                              k += a.length;
                            }

                            reverse(a, 0, a.length - k - 1);
                            reverse(a, a.length - k, a.length - 1);
                            reverse(a, 0, a.length - 1);
                          }
                          
                          
2.ARROW FUNCTIONS:

a.Print odd numbers :

oddNumbers = (array) => {
                   for(var i = 0 ; i< array.length ; i++){
                        if(array[i]%2!=0){
                           console.log(array[i])
                        } 
                   }
                        }
                        
                        
b.Convert string to title case :                      
                        
              titleCase = (str) => {
                    str = str.toLowerCase().split(' ');
                    for (var i = 0; i < str.length; i++) {
                      str[i] = str[i].charAt(0).toUpperCase() + str[i].slice(1); 
                    } 
                    return str.join(' ');
                  } 
                  
c.Sum of all numbers :                
                  
              sum = (array)=>{
             var sum = 0;
                  for(var i = 0 ; i< array.length ; i++){
                     sum = sum + array[i];
                   }
                   return sum;
                   }  
                   
d.All prime numbers :                 
                   
primeNumber = (numArray) => {
                      numArray = numArray.filter((number) => {
                        for (var i = 2; i <= Math.sqrt(number); i++) {
                          if (number % i === 0) return false;
                        }
                        return true;
                      });
                      console.log(numArray);
                  }
