![week-4-git_log](https://github.com/user-attachments/assets/74242d5b-fc34-44e1-a6df-c41ca066775e)
![week-4-code_4](https://github.com/user-attachments/assets/beb5452e-f2b7-48ba-a7ac-65ab3f67e164)
![week-4-code_3](https://github.com/user-attachments/assets/a78f5a01-3733-4988-8ad5-fb0cc3571838)
![week-4-code_2](https://github.com/user-attachments/assets/3ae60837-accc-4ec2-b603-b5128118e05a)
![week-4-code_1](https://github.com/user-attachments/assets/6997554f-6dbd-481b-a4be-5a2618b0ca20)
![week-4-challenge-result](https://github.com/user-attachments/assets/aa779904-be06-4a51-80f6-73bd33658a92)
** Summarizing the process and the Git commands i used.

1. cd ..
2. ls
3. ssh
4. sudo apt-get update
5. sudo apt-get upgrade
6. git status
7. mkdir week-4-challenge
8. cd week-4-challenge/
9. git init
10. git status
11. git branch
12. touch info.txt
13. vim info.txt
14. git add info.txt
15. git commit -m "Initial commit: Add info.txt with introductory content"
16. git remote -v
17. git remote add origin https://github.com/PurveshDevOps/90DaysOfDevOps.git
18. git push origin master
19. git remote -v
20. git remote set-url origin https://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@github.com/PurveshDevOps/90DaysOfDevOps.git
21. git pull origin master
22. git push origin master
23. git pull origin master --rebase
24. git push origin master
25. git log
26. git checkout -b feature-update
27. vim info.txt
28. git add info.txt
29. git commit -m "feature-update: Enhance info.txt with additional details"
30. git push origin feature-update
31. git checkout master
32. git pull origin master
33. cd week-4-challenge/
34. git clone git@github.com:PurveshDevOps/90DaysOfDevOps.git
35. git branch
36. git checkout feature-update
37. git clone git@github.com:PurveshDevOps/90DaysOfDevOps.git
38. git checkout -b experimental
39. git branch
40. vim info.txt
41. git checkout master
42. git status
43. git add info.txt
44. git commit -m "added info.txt"
45. git push origin master
46. git status
47. git checkout feature-update
48. git merge experimental
49. git branch
50. git checkout feature-update
51. touch solution.md
52. git pull origin feature-update
53. git push origin feature-update
54. git status
55. git add solution.md
56. git commit -m "added solution.md to feature-update"
57. git push origin feature-update
58. git push -u origin main
59. git branch
60. git status
61. git add 90DaysOfDevOps
62. git commit -m "Added 90DaysOfDevOps"
63. git status
64. git add solution.md
65. git commit -m "added solution file"
66. git push origin master
67. git config pull.rebase true
68. git pull origin master
69. git status
70. git restore solution.md
71. git add solution.md
72. git status
73. git commit -m "added solution file"
74. git push origin master
75. ls
76. git rm -rf solution.md
77. ls
78. clear
79. touch SOLUTION.md
80. ls
81. vim SOLUTION.md
82. git status
83. git add SOLUTION.md
84. git commit -m "added SOLUTION.md to changes"
85. git push origin master
86. git status
87. git branch
88. git rebase --continue
89. git branch
90. git status
91. git log --oneline
92. clear
93. git push origin master
