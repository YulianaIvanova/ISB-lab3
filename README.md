# ISB-lab3
Hybrid cryptosystem

HOW TO USE:

   python main.py -gen GENERATION -symkey D:\University\ISB\isb-lab3\symmetric_key -pubkey D:\University\ISB\isb-lab3\public_key -seckey D:\University\ISB\isb-lab3\secret_key

   python main.py -enc ENCRYPTION -initial D:\University\ISB\isb-lab3\initial_file -seckey D:\University\ISB\isb-lab3\secret_key -symkey D:\University\ISB\isb-lab3\symmetric_key -encrypted D:\University\ISB\isb-lab3\encrypted_file

   python main.py -dec DECRYPTION -encrypted D:\University\ISB\isb-lab3\encrypted_file -seckey D:\University\ISB\isb-lab3\secret_key -symkey D:\University\ISB\isb-lab3\symmetric_key -dencrypted D:\University\ISB\isb-lab3\decrypted_file

WHERE:

  -gen GENERATION (generating encryption keys)
  
  -enc ENCRYPTION (text encryption)
  
  -dec DECRYPTION (text decryption)
