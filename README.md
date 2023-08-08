My first readme

```mermaid
flowchart TB;
  A[Tokenize is called]-->B[c_read set to getline];
  B-->C[Is c_read -1?];
  C--Yes-->D[Free input];
  D-->E[Exit];
  C--No-->F[Make memory for input_copy];
  F-->G[Was memory Allocated?];
  G--No-->H[perror];
  G--Yes-->I[Make Tokens from input];
  I-->J[While Token is true];
  J-->K[Added to token count];
  K-->L[Make memory for Tokens];
  L-->M[Iterate through argv];
  M-->N[Copy Tokens to argv[i]];
  N-->O[Free input,copy. Return argv];
```
