# 1)Counter()

Counter(string) =

1.count()- Built-in  Method (For Lists, Strings, and Tuples)

If you want to count  **all items at once** , import `Counter` from Python's standard `collections` library. It acts like a specialized dictionary where the elements are keys and their frequencies are values

# 2)Empty set initialise

a=set()

# 3)in-place and not-in-place sorting

in-place-doesn't create new object , it rearranges the original object

not-in-place-creates new object

# 4) defaultdict()

a **`defaultdict` is a subclass of the built-in `dict` class** that automatically assigns a default value to a key if it does not already exist, Unlike a standard dictionary, which raises a `KeyError` when you look up a non-existent key, a `defaultdict` calls a user-specified function (called a `default_factory`) to gracefully create and return a default value on the fly

# 5)Mutable and Immutable

mutable=list, set, dict

immutable=int,float,string,tuple

# 6) Counter().most_common()

returns a list of all elements in a `Counter` object and their frequencies, sorted from the most frequent to the least frequent

# 7)The Sieve of Eratosthenes Algorithm

1. **Initialize:** Create a list of boolean values indexed from \(2\) to \(n\), all initially marked as `True` (meaning they are assumed to be prime).
2. **Eliminate:** Start with the first prime number, \(2\). Go through the list and mark all multiples of \(2\) as `False` (e.g., \(4, 6, 8, \ldots\)).
3. **Repeat:** Move to the next number in the list that is marked `True`. Mark all of its multiples as `False`.
4. **Stop condition:** You only need to check multiples for primes up to \(\sqrt{n}\).
5. **Result:** All indices in your list that remain marked `True` after this process are the prime numbers less than or equal to \(n\).

# 8) GCD using Euclidean algorithm

The **Euclidean formula for finding the Greatest Common Divisor (GCD)** of two integers a and b is based on the principle that \(gcd(a, b) = gcd(b, a mod b)\) until the remainder becomes zero. Formally, it is expressed as the piecewise reduction function.


$$
\gcd(a, b) = \begin{cases} a, & \text{if } b = 0 \\ \gcd(b, a \bmod b), & \text{otherwise} \end{cases}
$$
