```javascript
// 세자리수 나누기 두자리수 문제 생성 (50문제)
function generateThreeByTwoDigitDivision() {
    const problems = [];
    for (let i = 0; i < 50; i++) {
        const dividend = Math.floor(Math.random() * 900) + 100; // 100-999
        const divisor = Math.floor(Math.random() * 90) + 10;    // 10-99
        problems.push(`${dividend} ÷ ${divisor}`);
    }
    return problems;
}

// 네자리수 나누기 두자리수 문제 생성 (30문제)
function generateFourByTwoDigitDivision() {
    const problems = [];
    for (let i = 0; i < 30; i++) {
        const dividend = Math.floor(Math.random() * 9000) + 1000; // 1000-9999
        const divisor = Math.floor(Math.random() * 90) + 10;      // 10-99
        problems.push(`${dividend} ÷ ${divisor}`);
    }
    return problems;
}

// 다섯자리수 나누기 세자리수 문제 생성 (20문제)
function generateFiveByThreeDigitDivision() {
    const problems = [];
    for (let i = 0; i < 20; i++) {
        const dividend = Math.floor(Math.random() * 90000) + 10000; // 10000-99999
        const divisor = Math.floor(Math.random() * 900) + 100;      // 100-999
        problems.push(`${dividend} ÷ ${divisor}`);
    }
    return problems;
}

console.log("===== 세자리수 ÷ 두자리수 (50문제) =====");
console.log(generateThreeByTwoDigitDivision().join('\n'));
console.log("\n===== 네자리수 ÷ 두자리수 (30문제) =====");
console.log(generateFourByTwoDigitDivision().join('\n'));
console.log("\n===== 다섯자리수 ÷ 세자리수 (20문제) =====");
console.log(generateFiveByThreeDigitDivision().join('\n'));

```
<br>
<br>
<br>
<br>
<br>
<br>
<br>


# 나눗셈 계산 100문항 (임규연 선생님)

## 각 문제의 몫과 나머지를 구하시오.

### 1부: 세자리수 ÷ 두자리수 (1-50번)

1. 713 ÷ 48
2. 544 ÷ 95
3. 305 ÷ 53
4. 268 ÷ 10
5. 344 ÷ 44
6. 511 ÷ 67
7. 161 ÷ 57
8. 908 ÷ 15
9. 297 ÷ 51
10. 749 ÷ 93
11. 678 ÷ 34
12. 611 ÷ 54
13. 592 ÷ 56
14. 908 ÷ 80
15. 447 ÷ 29
16. 388 ÷ 21
17. 174 ÷ 76
18. 525 ÷ 32
19. 425 ÷ 90
20. 840 ÷ 50
21. 188 ÷ 38
22. 932 ÷ 81
23. 834 ÷ 24
24. 802 ÷ 49
25. 698 ÷ 10
26. 670 ÷ 98
27. 299 ÷ 58
28. 176 ÷ 70
29. 753 ÷ 86
30. 789 ÷ 66
31. 265 ÷ 44
32. 705 ÷ 53
33. 123 ÷ 71
34. 841 ÷ 43
35. 956 ÷ 55
36. 402 ÷ 81
37. 224 ÷ 77
38. 184 ÷ 48
39. 794 ÷ 59
40. 910 ÷ 18
41. 227 ÷ 64
42. 340 ÷ 15
43. 766 ÷ 32
44. 752 ÷ 81
45. 300 ÷ 84
46. 343 ÷ 23
47. 877 ÷ 51
48. 703 ÷ 61
49. 705 ÷ 44
50. 417 ÷ 18

### 2부: 네자리수 ÷ 두자리수 (51-80번)

51. 9639 ÷ 75
52. 5844 ÷ 24
53. 7072 ÷ 28
54. 7372 ÷ 98
55. 8652 ÷ 34
56. 4626 ÷ 20
57. 6849 ÷ 53
58. 1412 ÷ 68
59. 1864 ÷ 35
60. 6631 ÷ 32
61. 8658 ÷ 45
62. 5021 ÷ 87
63. 6390 ÷ 80
64. 6407 ÷ 14
65. 5614 ÷ 63
66. 1968 ÷ 57
67. 4299 ÷ 75
68. 4513 ÷ 59
69. 2514 ÷ 24
70. 9003 ÷ 20
71. 1688 ÷ 21
72. 7491 ÷ 42
73. 4671 ÷ 62
74. 4378 ÷ 70
75. 8779 ÷ 94
76. 3613 ÷ 13
77. 9174 ÷ 94
78. 8344 ÷ 90
79. 6341 ÷ 29
80. 9570 ÷ 25

### 3부: 다섯자리수 ÷ 세자리수 (81-100번)

81. 28385 ÷ 100
82. 47997 ÷ 120
83. 94457 ÷ 130
84. 47467 ÷ 500
85. 48763 ÷ 600
86. 38568 ÷ 200
87. 83927 ÷ 700
88. 26263 ÷ 300
89. 51624 ÷ 200
90. 37415 ÷ 100
91. 69953 ÷ 250
92. 17355 ÷ 150
93. 47442 ÷ 100
94. 85939 ÷ 790
95. 39546 ÷ 150
96. 10593 ÷ 500
97. 93299 ÷ 900
98. 94031 ÷ 300
99. 30074 ÷ 600
100. 40740 ÷ 500