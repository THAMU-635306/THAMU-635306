- 👋 Hi, I’m @THAMU-635306
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...

<!---
THAMU-635306/THAMU-635306 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
SELECT EMPNO
, ENAME
, JOB
, MGR
, TO_CHAR(HIREDATE,'yyyy-mm-dd') AS HIREDATE 
,months_between(sysdate,HIREDATE) AS TOTAL_EXPERIENCE
, SAL
, COMM
, DEPTNO
FROM EMPP
