SLASHMARK Basic task-1:
     Text Encryptor/Decryptor

     
 Open the HTML File in a Browser
 Use the Encryptor/Decryptor
1.Enter Text to Encrypt:
   .In the inputText textarea, enter the text you want to encrypt.
   .In the secretKey input field, enter the secret key for encryption.
   
2.Encrypt Text:
   .Click the "Encrypt" button.
   .The encrypted text will appear in the outputText textarea.

3.Decrypt Text:
   .To decrypt the text, ensure the encrypted text is in the outputText textarea and the correct secret key is in the secretKey input field.
   .Click the "Decrypt" button.
   .The decrypted text will appear in the outputText textarea.
*Additional Notes:
   .Encryption Security: Ensure the secret key is kept secure. The strength of the encryption depends significantly on the key's security.
   .IV Handling: The initialization vector (IV) is generated randomly and included in the encrypted output for proper decryption. This ensures the same plaintext will encrypt to different ciphertexts each time.
