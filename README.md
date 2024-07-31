# acccode13
sql
'''ENAME             SAL     SAL*12                                                
---------- ---------- ----------                                                
ALLEN            1600      19200                                                
WARD             1250      15000                                                
JONES            2975      35700                                                
MARTIN           1250      15000                                                
BLAKE            2850      34200                                                
CLARK            2450      29400                                                
SCOTT            3000      36000                                                
KING             5000      60000                                                
TURNER           1500      18000                                                
ADAMS            1100      13200                                                
FORD             3000      36000 '''
select ename,sal, sal*12
    from emp
   where sal*12>12000;

