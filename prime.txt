let prime = function (arr) {
    return arr.filter((n) => {
      for (let i = 2; i < n; i++) {
        if (n % i === 0) return false;
      }
      return n > 1;
    });
  };
  console.log(prime([1,2,3,4,5,6,7,8,9]));