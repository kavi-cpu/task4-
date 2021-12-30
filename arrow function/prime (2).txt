let primes = (arr) => {
    return arr.filter((e) => {
      for (let i = 2; i < e; i++) {
        if (e % i === 0) {
          return false;
        }
      }
      return e > 1;
    });
  };
  console.log(primes([1, 2, 5, 16, 25, 99, 101]));