# One-Thousand-Problem-
Target to solve one thousand Problem. 

>>Problem - 01 
**Sum all array element (JavaScript)
// Sum all numbers in an array 

const numbers= [11,22,33,44,55,66,77,88,99]
var sum = 0
for(var i = 0; i<numbers.length; i++){
    sum = sum+numbers[i]
}
console.log('The sum is:', sum)

// Sum all array element by function 
var asum=0
function sumNumber(number){
    for( var i = 0; i<number.length;i++){
        asum = asum + number[i]
    }
    return asum
}

obj = sumNumber([10,20,30])
console.log('Sum by function:',obj)
