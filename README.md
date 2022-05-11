# Assignment-1-may-11
class Solution: def countPrimes(self, n: int) -> int: primes = [True for i in range(n)] i = 2 while(ii < n): if(primes[i] == True): for p in range(ii, n, i): primes[p] = False i += 1

    counter = 0
    for i in range(2, len(primes)):
        if primes[i]:
            counter += 1
    return counter
