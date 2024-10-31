## Overhead (50 WU)
nVersion (16)

Input count (1*4) 


Output count (3*4) 


nLockTime (16) 

Segwit marker & segwit flag (2) 

##  Input (166WU)

Outpoint (36*4) 

scriptSig length (1*4)

scriptSig (0) 

nSequence (4*4) 

Witness item count (1) 

Witness items 

OP_TRUE (1)

## Output (40WU,for minimal size)
nValue (8*4) 

scriptPubKey length (1*4) 
scriptPubKeys 
OP_TRUE(1*4)

if we have 9995 outputs, the size is 40*9993 = 399720 WU
total size is 50+166+399720 = 399936 WU
and now we could have one more op_return 40wu +
so total max ouputs is 9996

further material 
