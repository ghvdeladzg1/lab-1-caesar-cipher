

1. Caesar Cipher
   
Decrypted text: “Hvs Eiwqy Pfckb Tcl Xiadg Cjsf Hvs Zonm Rcu.”
Result: “The quick brown fox will jump over the lazy dog.”

Discussion: 
The Caesar cipher is not secure because it is very easy to break. There are only 25 possible shifts, so someone can try all of them very quickly (brute-force). Also, it does not hide letter patterns, so frequency analysis can reveal the message. Some old systems or legacy devices might still use similar simple encryption for basic data protection or obfuscation, but it is not safe for modern security needs.


2. XOR Encryption/Decryption
   
I first decrypted the Caesar cipher mznxpz by trying all shifts and found it gave the word rescue. This word is an anagram, and when rearranged it became the passphrase secure. I used this passphrase to XOR-decrypt the base64 message. After decoding and XOR decryption, the final text was: “This is the XOR challenge!” This shows how Caesar is weak and XOR needs a secret key to work.
