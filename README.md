My first readme

```mermaid
flowchart TD;
A[execmd is called]-->B[is argv true?];
B--No-->C[Do nothing.];
B--Yes-->D[Call find_location.];
D-->E[is real_command NULL?];
E--Yes-->[a];
