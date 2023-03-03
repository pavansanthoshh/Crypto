Consider a modified Vigenere cipher where the set of characters are the hexadecimal digits (instead of letters from the English alphabet).
(1) If Pi is the ith digit of the plaintext, Ci is the ith digit of the ciphertext, and Ki
is the ith digit of the key, please write equations for the encryption and decryption operations. (5 points)
E(Pi, Ki) = Ci=
D(Ci, Ki) = Pi =
[hint: The ordinary encryption and decryption operations in Vigenere cipher are
E(Pi, Ki) = Ci = Pi+Ki mod 26,
D(Ci, Ki) = Pi = Ci-Ki mod 26,

(2) For P = 5D8 and K= 8E1, what is C?

Solution:
1) The encrypted and decrypted equations of the modified Vigenere cipher can be expressed as follows-
E(Pi, Ki) = Ci = (Pi + Ki)mod16D(Ci, Ki) = Pi = (Ci - Ki)mod16
There are 16 possible hexadecimal digits, therefore the modulus is 16 instead of 26 (0-9 and A-F).
2) Let P = 5D8 and K = 8E1.
The encryption equation must be applied to each pair of plaintext and key digits in order to find the ciphertext C.
K can be repeated cyclically to match P since it has four digits while P has three.
P = 5D8K = 8E18E18E1
In this case, we can compute each ciphertext digit Ci by calculating the following-
C1 = (5+8)mod16 = DC2 = (D+E)mod16 = BC3= (8+1)mod16 = 9 So,
ciphertext C is OxDB9.
Explanation
C1 = (5+8) mod 16 = DC2 = (D+ E) mod 16 = B C3 = (8 + 1) mod 16 = 9 So,
ciphertext C is OxDB9
