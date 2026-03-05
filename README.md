# Ankit-sinha
function sumofdigits(num){
    int sum=0;
    while(num>0){
        let digit = num%10;
        sum = sum + digit;
        num = Math.floor(num/10);
    }
    return sum;
}
console.log(sumofdigits(1234))
