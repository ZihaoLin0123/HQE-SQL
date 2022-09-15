# HQE-SQL

This is a repo for HQE-SQL: History Question Relation Enhanced Text2SQL, which is our final project of CS 590.03 Advanced NLP course in 2022 Spring.

## Abstract

Text2SQL problem aims to efficiently translate natural language questions asked by users to SQL queries, which are executable by database software, and return searched results to users. Previous approaches put more attention on schema link- ing between tables and question but overlook the relation information between historical and current questions, and thus perform unsatisfying on harder datasets which contain more context-dependent questions. In this work, we propose His- tory Question Relation Enhanced Text2SQL (HQE-SQL) model to explicitly cap- ture the question relation information. In particular, we first propose a new task to predict question relations and then involve the predicted question relations into self-attention mechanism. We conduct experiments on a new Chinese Text2SQL dataset Chase (Guo et al., 2021) and achieve better results compared to one strong baseline.

## Model
<img width="1002" alt="image" src="https://user-images.githubusercontent.com/71021979/190299885-176aeab8-051d-4c1f-9737-ac35f24d7de8.png">
