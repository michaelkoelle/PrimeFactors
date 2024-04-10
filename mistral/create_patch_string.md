{"patch_string": ["diff --git a/prime_factors/primes.py b/prime_factors/primes.py\n", "index 3f0e62a..5b91e48 100644\n", "--- a/prime_factors/primes.py\n", "+++ b/prime_factors/primes.py\n", " @@ -1,7 +1,7 @@\n", " def generate(n: int):\n", " + import math\n", " \tresult = [1]\n", " \twhile n % 2 == 0:\n", " \tm.append(2)\n", " \tn //= 2\n", " \tif n % 2 != 0:\n", " \tm.extend(prime_factors(int(math.sqrt(n))+1))\n", " \tn = n // (m[-1] ** 2)\n", " \tm.append(n)\n", " return m\n"]}