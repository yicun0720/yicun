---
permalink: /
title: "About Me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am Yicun Yang, a Ph.D. student at the Institute of Parallel and Distributed Systems ([IPADS](https://ipads.se.sjtu.edu.cn/)), Shanghai Jiao Tong University. 
Currently, my advisor is Prof. [Zhaoguo Wang](https://ipads.se.sjtu.edu.cn/pub/members/zhaoguo_wang) and my research interest lies in SQL query processing and optimization in database systems, with the application of formal verification, AI, etc.

<!-- I'm always full of energy for life. I love sports (especially ballgames like 🏀 and 🏸️), musics, aerial photography and traveling.
Welcome everyone from all corners of the world to make friends with me. -->

Projects
======

SQLSolver
------
SQLSolver is an automated SQL equivalence solver based on SMT solver and Linear Integer Arithmetic Theory. Compared to existing SQL equivalence solvers, it supports more SQL features, guaranteeing a stronger verification capability. In our evaluation, SQLSolver can verify the equivalence of all 232 query pairs from the Calcite test suite, while only 121 of them can be proved by prior provers. 
In this project, I contributed to the implementation of SQL query to logical formula translation, and the evaluation on Calcite test suite.

[pdf](https://dl.acm.org/doi/10.1145/3626768) | 
[source code](https://github.com/SJTU-IPADS/SQLSolver) | 
[online demo](https://sqlsolver.systems/sqlsolver/home)

WeTune
------
WeTune is a tool for automatically discovering SQL query rewrite rules and verifying their correctness. Inspired by compiler superoptimization, it enumerates all valid logical query plans and discovers equivalent plans that could potentially lead to more efficient SQL rewrites. 
It also proposes a new SMT-based solver to solve the equivalence of a query pair under different constraints.
WeTune successfully optimizes 247 queries from 20 open-sourced application on Github that existing databases cannot optimize, resulting in substantial performance improvements.
In this project, I contributed to the design and implementation of rule enumeration and SQL query rewriting, along with the evaluation on the performance of rewritten SQL queries.

[pdf](https://dl.acm.org/doi/10.1145/3514221.3526125) | 
[extended version](https://ipads.se.sjtu.edu.cn/_media/publications/wtune_extend.pdf) |
[source code](https://github.com/WeTune/WeTune-code)

WeRewriter
------
WeRewriter is an online query rewriting system demo based on the rules automatically discovered by WeTune. WeRewriter can generate equivalent but potentially more efficient SQL queries given the input query and present the used query rewrite rules when rewriting.

[online demo](https://ipads.se.sjtu.edu.cn/werewriter-demo/home)


Education
======
- 2023.04 - now, transfer to Ph.D., School of Software Engineering, Shanghai Jiao Tong University, Advisor: Zhaoguo Wang
- 2021.09 - 2023.03, M.S., School of Software Engineering, Shanghai Jiao Tong University, Advisor: Zhaoguo Wang
- 2017.09 - 2021.06, B.S., School of Software Engineering, Nanjing University

Contact
======
Email: [yangyicun027@gmail.com](mailto:yangyicun027@gmail.com) or [yangyicun@sjtu.edu.cn](mailto:yangyicun@sjtu.edu.cn)