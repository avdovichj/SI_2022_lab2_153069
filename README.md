# SI_2022_lab2_153069

Jasmina Avdovikj 153069

2. ![Control Flow Graph](https://github.com/avdovichj/SI_2022_lab2_153069/blob/master/153069_SILab2.png)
3. Ciklomatska kompleksnost na grafot e 7, a do nea dojdov preku formulata koja glasi, M = E - N + 2P. Tuka E pretstavuva broj na rebra, N pretstavuva broj na jazli, a P pretstavuva broj na povrzani komponenti, pa taka M = 29 - 24 + 2*1 = 7
4. Every statement:
- Test 1: 1, 3, 4, 5, 7, 8, 23 (false = 1, 5, 8)
- Test 2: 1, 2 (throws exception if 1 is true and stops execution of the function)
- Test 3: 1, 3, 4, 6 (throws exception if 6 is true and stops execution of the function)
- Test 4: 1, 3, 4, 5, 7, 8, 9, 21, 22, 23 (false = 1, 5, 9)
- Test 5: 1, 3, 4, 5, 7, 8, 9, 10, 11, 16, 18, 20, 23 (false = 1, 5, 11, 16, 18)
- Test 6: 1, 3, 4, 5, 7, 8, 9, 10, 11, 12, 13, 16, 18, 20, 23 (false = 1, 5, 16, 18)
- Test 7: 1, 3, 4, 5, 7, 8, 9, 10, 11, 12, 13, 16, 17, 18, 19, 20, 23 (false = 1, 5, 14)
    
5.Every branch:
- Test 1: A, B, D (B is true and throws exception stopping the execution)
- Test 2: A, B, C, E, F, G (F is true and throws exception stopping the execution)
- Test 3: A, B, C, E, F, H, I, J, X (J is false and the function returns numMines)
- Test 4: A, B, C, E, F, H, I, J, K, W, V, J (K is false)
- Test 5: A, B, C, E, F, H, I, J, K, L, M, Q, S, U, V, J (M, Q, S are false)
- Test 6: A, B, C, E, F, H, I, J, K, L, M, N, P, Q, S, U, V, J (N, Q, S are false)
- Test 7: A, B, C, E, F, H, I, J, K, L, M, N, O, Q, R, S, U, V, J (S is false)
- Test 8: A, B, C, E, F, H, I, J, K, L, M, N, O, Q, R, S, T, U, V, J (all are true)
