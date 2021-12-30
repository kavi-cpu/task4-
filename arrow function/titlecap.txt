var sumb=(arr)=>{
    let sum=0;
    for(let i in arr){
        sum+=arr[i];
    }
    console.log(sum);
}
console.log(sumb([1,2,3,4,5]))