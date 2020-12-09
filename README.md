# one_time_pad_attack

Knowledge required to do this attack: 
C1⊕C2 = (P1⊕K)⊕(P2⊕K) = (P1⊕P2)⊕(K⊕K) = P1⊕P2 ,  

By having the knowledge of this (plaintext  1 layered with plaintext  2 ), this can sufficiently reveal readable plaintext information from the output. Then we may gusse what may exist in orginal message, we may drag this again into the C1⊕C2. 
By doing so, we may get another piece of information from another message as part of plaint text could be revealed after xor with original message. By continuing to do so, we keep extracting information from both message until we get an fair guess for the whole message. 

Some people refer this workflow as crib drag

