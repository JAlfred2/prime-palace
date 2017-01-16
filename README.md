# prime-palace
Web app with several alogirthms that explore prime numbers.
Written in Javascript.

New version features new and improved algorithms.

Primality Test

The primality test will determine if a number is prime or not. It can work with very high numbers if they are divisible by 2, 3, or 5.

Prime Factorization

This breaks a number down into its prime factorization. It also serves as a primality test.

Primes Between

Determines how many primes there are between two given inputs. This might stop working well if the difference between inputs is greater than 10,000.

Chebyshev Function

The Chebyshev Function is the natural logarithm of the "primorial" of the input. The "primorial" of x is the product of all primes less than or equal to x. This particular algorithm can accept inputs up to around 50,000.

Mod Function

The mod function should be included in modern calculators in my opinion. I included one in this program so I'd have an easy way to check the remainder of a division.

Euler Totient Function

This function is defined as the number of values between 0 and x that share no divisors with x. It is denoted phi(x), the Greek letter phi.
So, for instance, if x is prime, phi(x) will always be x - 1, because a prime will never share divisors with a number less than it.
I noticed that for this particular algorithm, it would be easy to include a divisor function. So I included a divisor function. It counts the number of values that divide x evenly, including x.
There was also originally an omega function that counted the distinct prime factors, but it's not working properly, so I'm commenting it out for now.

Thanks for reading! Hopefully in the future, i will be taking on more ambitious tasks, like increasing the speed and size of permissible inputs. You can contact me for any other ideas.
