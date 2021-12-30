(function(arr){
    let sum=0;
    for(let i in arr){
        sum+=arr[i];
        //sum.push(arr[i])
    }
     console.log(sum);
})([1,2,3,4,5]);