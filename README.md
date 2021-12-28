# Easy problems are not so easy

Hello Connections, 👋👋

I want share my experience after which I don't leave any problem just because it is has easy difficulty tag or its solution is very intuitive. Mostly easy problems tempting to leave as they vert intuitive or direct.

All of the problems links are in the comment.

Once I read a easy problem on leetcode given below. 
Problem #53 **𝐌𝐚𝐱𝐢𝐦𝐮𝐦 𝐒𝐮𝐛𝐚𝐫𝐫𝐚𝐲**.
 "𝘎𝘪𝘷𝘦𝘯 𝘢𝘯 𝘪𝘯𝘵𝘦𝘨𝘦𝘳 𝘢𝘳𝘳𝘢𝘺 𝘯𝘶𝘮𝘴, 𝘧𝘪𝘯𝘥 𝘵𝘩𝘦 𝘤𝘰𝘯𝘵𝘪𝘨𝘶𝘰𝘶𝘴 𝘴𝘶𝘣𝘢𝘳𝘳𝘢𝘺 (𝘤𝘰𝘯𝘵𝘢𝘪𝘯𝘪𝘯𝘨 𝘢𝘵 𝘭𝘦𝘢𝘴𝘵 𝘰𝘯𝘦 𝘯𝘶𝘮𝘣𝘦𝘳) 𝘸𝘩𝘪𝘤𝘩 𝘩𝘢𝘴 𝘵𝘩𝘦 𝘭𝘢𝘳𝘨𝘦𝘴𝘵 𝘴𝘶𝘮 𝘢𝘯𝘥 𝘳𝘦𝘵𝘶𝘳𝘯 𝘪𝘵𝘴 𝘴𝘶𝘮.
𝘈 𝘴𝘶𝘣𝘢𝘳𝘳𝘢𝘺 𝘪𝘴 𝘢 𝘤𝘰𝘯𝘵𝘪𝘨𝘶𝘰𝘶𝘴 𝘱𝘢𝘳𝘵 𝘰𝘧 𝘢𝘯 𝘢𝘳𝘳𝘢𝘺."

I though problem is just direct implementation of Kadane's algorithm🤷‍♂️. I decided not to solve it because I have implemented kadane's algorithm already sometimes.

After months later, when I was learning segment tree. So after learning it's implementation and reading some problems (and some solutions too) related to segment tree. I decided to solve segment tree problems on my own.
First problem I encountered with was: 
𝐆𝐒𝐒1 - 𝐂𝐚𝐧 𝐲𝐨𝐮 𝐚𝐧𝐬𝐰𝐞𝐫 𝐭𝐡𝐞𝐬𝐞 𝐪𝐮𝐞𝐫𝐢𝐞𝐬 𝐈.

"𝘠𝘰𝘶 𝘢𝘳𝘦 𝘨𝘪𝘷𝘦𝘯 𝘢 𝘴𝘦𝘲𝘶𝘦𝘯𝘤𝘦 𝘈[1], 𝘈[2], ..., 𝘈[𝘕] . ( |𝘈[𝘪]| ≤ 15007 , 1 ≤ 𝘕 ≤ 50000 ). 𝘈 𝘲𝘶𝘦𝘳𝘺 𝘪𝘴 𝘥𝘦𝘧𝘪𝘯𝘦𝘥 𝘢𝘴 𝘧𝘰𝘭𝘭𝘰𝘸𝘴:
𝘘𝘶𝘦𝘳𝘺(𝘹,𝘺) = 𝘔𝘢𝘹 { 𝘢[𝘪]+𝘢[𝘪+1]+...+𝘢[𝘫] ; 𝘹 ≤ 𝘪 ≤ 𝘫 ≤ 𝘺 }.
𝘎𝘪𝘷𝘦𝘯 𝘔 𝘲𝘶𝘦𝘳𝘪𝘦𝘴, 𝘺𝘰𝘶𝘳 𝘱𝘳𝘰𝘨𝘳𝘢𝘮 𝘮𝘶𝘴𝘵 𝘰𝘶𝘵𝘱𝘶𝘵 𝘵𝘩𝘦 𝘳𝘦𝘴𝘶𝘭𝘵𝘴 𝘰𝘧 𝘵𝘩𝘦𝘴𝘦 𝘲𝘶𝘦𝘳𝘪𝘦𝘴."

When I read the problem. I don't have any clue how to even start with the problem🥺😳, although I know we have to use segment tree to solve this problem. After spending a lot of time I was not going anywhere near to the solution. The best solution I was able to come up was brute force solution(using kadane's algorithm) of O(MN) which will definately was going end up to TLE. After getting all tired🥵🥵, I decided to watch the solution.
So I searched the the solution on Google, found some videos and blogs. Even solutions were even hard to understand. After spending a lot of time and banging my head against the wall😤😤, I got fully exhausted and went to sleep😴😴.
Next day I dry run one of the solution and finally understood the logic behind all of the solutions😌😌. I was very happy😁😁.

After so many day I again somehow found that same easy problem of LeetCode 𝐌𝐚𝐱𝐢𝐦𝐮𝐦 𝐒𝐮𝐛𝐚𝐫𝐫𝐚𝐲(kadane's algorithm). I re-read the problem because now I know one more solution to solve the problem from that segment tree one problem. To check if it this solution can pass the all of the test cases I checked the constraints and saw below the problem there was written "Follow up: If you have figured out the O(n) solution, try coding another solution using the divide and conquer approach, which is more subtle."
I saw discussion section of LeetCode to check if another solution they are talking about is same new solution that I have learnt recently?? And astonishingly Yess!! it was same solution that I learnt in that hard way😒😒. That hard problem has exactly same solution as this easy LeetCode problem only extra is segment tree to memorize this solution's sub-solution.

After reading this solution my mind was completely blank, the only thought was "why the hell I didn't read the whole problem that day"🥺🥺.

Learnings:
1) Don't take any problem for granted regardless of there tags.
2) If possible, try to learn different approaches for one problem.
3) Read complete problem even other solutions have higher time complexity.
