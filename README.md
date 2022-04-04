# password-generator

This script is for a passphrase generator.

Hackers can use a brute force attack to crack any 8 character password containing uppercase and lowercase letters, numbers, and symbols in less than 6 hours. Generally a password under 12 characters is vulnerable to be cracked by hackers. 

This script generates a passphrase using Electronic Frontier Foundation's (EFF) guidelines and EFF's long word list for generating strong passphrases. 

It asks how many words the user wants the password to comprise of.

The generator randomly generates a 5 number code for each word. The 5 number code generated corresponds to a word in EFF's long wordlist. The script stores the words as phrase_chosen.

Then the script asks the user how many symbols they want in the password. If the user does not want any symbols, they may enter 0. The script stores the symbols chosen as symbol_chosen.

The script then asks if the user wants numbers in the password. If the user does not want any numbers, they may enter 0. The stores the randomly chosen numbers as numbers_chosen.

The script finally combines the stored values: phrase_chosen, symbol_chosen, and numbers_chosen. Each symbol and number are added randomly between the words. 

The script prints out the randomly generated password.

The script then calculates and displays the entropy of the passphrase, which is used to determine the strength of the password. 



For more information regarding diceware, passphrases, and strength of passwords; please see the following websites:

What is a passphrase: https://theworld.com/~reinhold/diceware.html 

Dice generated passphrase: https://www.eff.org/dice 

Diceware faq: https://theworld.com/%7Ereinhold/dicewarefaq.html#login   

Passphrases vs passwords: https://generatepasswords.org/passphrases-vs-passwords/  











