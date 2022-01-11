Cipher/Decipher ⚡
=============
A short python script made to decrypt Caesar cipher encryptions without knowing the amount of rotation or to create your own encryptions.

## 📜 History:
In cryptography a Caesar cipher is one of the simplest and most widely known encryption techniques. In it, each letter in the plaintext is replaced by a letter some fixed number of positions down the alphabet. For example, with a left shift of 3, D would be replaced by A, E would become B, and so on. The method is named after Julius Caesar, who used it in his private correspondence, making the cipher over 2000 years old.

<img src="https://media.geeksforgeeks.org/wp-content/uploads/ceaserCipher.png" width="600">
  
 ## 🤖 How decipher works:
You might be wondering how I'm able to decode any message with high precision. For this, I use a helper function letter_prob which returns the monogram probablity of each alphabetic character in a word. For example 'e' is the most common alphabetic character in the English language, followed by 't' then 'a'. Each possible shifted string is assigned a sum of these probabilities, and the string with the greatest sum is likely the original message. The lunguistic data is adapted from Gothenburg University.

## 📒 How to use my script:
###### To encipher: 
encipher(message, amount of shift)
###### To decipher:
decipher(message)
