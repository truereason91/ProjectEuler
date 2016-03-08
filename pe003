/**
 * Project Euler Problem #003
 * By: Jason Moyer
 *
 * Problem: "Largest prime factor"
 *  The prime factors of 13195 are 5, 7, 13 and 29.
 *  What is the largest prime factor of the number 600851475143 ?
 */
public final class pe003 {
    public static void main (String[] args)
    {
        long num = 600851475143L;   // odd value is not divided by any even
        long primeFactor = 1L;

        for (long i = 3L; i <= num / i;)
        {
            if (num % i == 0) {
                primeFactor = i;
                num = num / i;
            }
            else {
                i += 2;
            }
        }

        if (primeFactor < num) {
            primeFactor = num;
        }

        System.out.println(primeFactor);
    }
}
