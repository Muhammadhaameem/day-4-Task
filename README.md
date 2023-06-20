# day-4-Task
1)a) odd numbers
Annonymous function

   var odd=function(arr)
   {
    for(i=0;i<arr.length;i++)
    {
        if(arr[i]%2!==0)
        {
            console.log(arr[i])
        }
    }
}
    odd([90,34,66,77,89,43])

    IIFE function


       (
    
        function(arr)
{
    for(i=0;i<arr.length;i++)
    {
        if(arr[i]%2!==0)
        {
            console.log(arr[i])
        }
    }
    }
   )([54,89,9,50,66,78])
})

b) title caps

Annonymous Function

var caps=function(str)
    {
        str=str.toLowerCase().split(" ")
        for(var i=0;i<str.length;i++)
        {
        str[i]=   str[i][0].toUpperCase() + str[i].slice(1)
        }
        return str.join(' ')
        } 
        
   console.log(caps("java script and python is the leading programming language"))


   IIFE Function

   (
       function(str)
        {
           str=str.toLowerCase().split(" ")
            for(var i=0;i<str.length;i++)
            {
                str[i]=str[i][0].toUpperCase()+str[i].slice(1)
             }
             
           console.log(str.join(" "))
        }
        
)("java script and python is the leading programming language")

c) sum of all elements
Annonymous function

var add=function(arr)
{
    var sum=0
    for(i=0;i<arr.length;i++)
    {
         sum+=arr[i]
    }
    console.log(sum)
}
add([34,7,9,0,35,889])

IIFE Function

(
    function(arr){
        var sum=0
        for( var i=0;i<arr.length;i++)
        {
            sum+=arr[i]
        }
        console.log(sum)
    }
)([45,88,90,8,42,4])

d) return prime numbers

Annonymous Function


    
