# Easy problems are not so easy

Hello Connections, ๐๐

I want share my experience after which I don't leave any problem just because it is has easy difficulty tag or its solution is very intuitive. Mostly easy problems tempting to leave as they vert intuitive or direct.

All of the problems links are in the comment.

Once I read a easy problem on leetcode given below. 
Problem #53 **๐๐๐ฑ๐ข๐ฆ๐ฎ๐ฆ ๐๐ฎ๐๐๐ซ๐ซ๐๐ฒ**.
 "๐๐ช๐ท๐ฆ๐ฏ ๐ข๐ฏ ๐ช๐ฏ๐ต๐ฆ๐จ๐ฆ๐ณ ๐ข๐ณ๐ณ๐ข๐บ ๐ฏ๐ถ๐ฎ๐ด, ๐ง๐ช๐ฏ๐ฅ ๐ต๐ฉ๐ฆ ๐ค๐ฐ๐ฏ๐ต๐ช๐จ๐ถ๐ฐ๐ถ๐ด ๐ด๐ถ๐ฃ๐ข๐ณ๐ณ๐ข๐บ (๐ค๐ฐ๐ฏ๐ต๐ข๐ช๐ฏ๐ช๐ฏ๐จ ๐ข๐ต ๐ญ๐ฆ๐ข๐ด๐ต ๐ฐ๐ฏ๐ฆ ๐ฏ๐ถ๐ฎ๐ฃ๐ฆ๐ณ) ๐ธ๐ฉ๐ช๐ค๐ฉ ๐ฉ๐ข๐ด ๐ต๐ฉ๐ฆ ๐ญ๐ข๐ณ๐จ๐ฆ๐ด๐ต ๐ด๐ถ๐ฎ ๐ข๐ฏ๐ฅ ๐ณ๐ฆ๐ต๐ถ๐ณ๐ฏ ๐ช๐ต๐ด ๐ด๐ถ๐ฎ.
๐ ๐ด๐ถ๐ฃ๐ข๐ณ๐ณ๐ข๐บ ๐ช๐ด ๐ข ๐ค๐ฐ๐ฏ๐ต๐ช๐จ๐ถ๐ฐ๐ถ๐ด ๐ฑ๐ข๐ณ๐ต ๐ฐ๐ง ๐ข๐ฏ ๐ข๐ณ๐ณ๐ข๐บ."

I though problem is just direct implementation of Kadane's algorithm๐คทโโ๏ธ. I decided not to solve it because I have implemented kadane's algorithm already sometimes.

After months later, when I was learning segment tree. So after learning it's implementation and reading some problems (and some solutions too) related to segment tree. I decided to solve segment tree problems on my own.
First problem I encountered with was: 
๐๐๐1 - ๐๐๐ง ๐ฒ๐จ๐ฎ ๐๐ง๐ฌ๐ฐ๐๐ซ ๐ญ๐ก๐๐ฌ๐ ๐ช๐ฎ๐๐ซ๐ข๐๐ฌ ๐.

"๐ ๐ฐ๐ถ ๐ข๐ณ๐ฆ ๐จ๐ช๐ท๐ฆ๐ฏ ๐ข ๐ด๐ฆ๐ฒ๐ถ๐ฆ๐ฏ๐ค๐ฆ ๐[1], ๐[2], ..., ๐[๐] . ( |๐[๐ช]| โค 15007 , 1 โค ๐ โค 50000 ). ๐ ๐ฒ๐ถ๐ฆ๐ณ๐บ ๐ช๐ด ๐ฅ๐ฆ๐ง๐ช๐ฏ๐ฆ๐ฅ ๐ข๐ด ๐ง๐ฐ๐ญ๐ญ๐ฐ๐ธ๐ด:
๐๐ถ๐ฆ๐ณ๐บ(๐น,๐บ) = ๐๐ข๐น { ๐ข[๐ช]+๐ข[๐ช+1]+...+๐ข[๐ซ] ; ๐น โค ๐ช โค ๐ซ โค ๐บ }.
๐๐ช๐ท๐ฆ๐ฏ ๐ ๐ฒ๐ถ๐ฆ๐ณ๐ช๐ฆ๐ด, ๐บ๐ฐ๐ถ๐ณ ๐ฑ๐ณ๐ฐ๐จ๐ณ๐ข๐ฎ ๐ฎ๐ถ๐ด๐ต ๐ฐ๐ถ๐ต๐ฑ๐ถ๐ต ๐ต๐ฉ๐ฆ ๐ณ๐ฆ๐ด๐ถ๐ญ๐ต๐ด ๐ฐ๐ง ๐ต๐ฉ๐ฆ๐ด๐ฆ ๐ฒ๐ถ๐ฆ๐ณ๐ช๐ฆ๐ด."

When I read the problem. I don't have any clue how to even start with the problem๐ฅบ๐ณ, although I know we have to use segment tree to solve this problem. After spending a lot of time I was not going anywhere near to the solution. The best solution I was able to come up was brute force solution(using kadane's algorithm) of O(MN) which will definately was going end up to TLE. After getting all tired๐ฅต๐ฅต, I decided to watch the solution.
So I searched the the solution on Google, found some videos and blogs. Even solutions were even hard to understand. After spending a lot of time and banging my head against the wall๐ค๐ค, I got fully exhausted and went to sleep๐ด๐ด.
Next day I dry run one of the solution and finally understood the logic behind all of the solutions๐๐. I was very happy๐๐.

After so many day I again somehow found that same easy problem of LeetCode ๐๐๐ฑ๐ข๐ฆ๐ฎ๐ฆ ๐๐ฎ๐๐๐ซ๐ซ๐๐ฒ(kadane's algorithm). I re-read the problem because now I know one more solution to solve the problem from that segment tree one problem. To check if it this solution can pass the all of the test cases I checked the constraints and saw below the problem there was written "Follow up: If you have figured out the O(n) solution, try coding another solution using the divide and conquer approach, which is more subtle."
I saw discussion section of LeetCode to check if another solution they are talking about is same new solution that I have learnt recently?? And astonishingly Yess!! it was same solution that I learnt in that hard way๐๐. That hard problem has exactly same solution as this easy LeetCode problem only extra is segment tree to memorize this solution's sub-solution.

After reading this solution my mind was completely blank, the only thought was "why the hell I didn't read the whole problem that day"๐ฅบ๐ฅบ.

Learnings:
1) Don't take any problem for granted regardless of there tags.
2) If possible, try to learn different approaches for one problem.
3) Read complete problem even other solutions have higher time complexity.
