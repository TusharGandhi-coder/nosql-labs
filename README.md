# NoSQL Database Design Labs – COER University

Solutions for Lab Sheets 2, 3, 4, 5. Copy-paste ready for `mongosh`, `redis-cli`, `cqlsh`, `hbase shell`, Riak HTTP API (`curl`), Cypher + Python.

## Files
- `LAB2.md` – Lab Sheet 2: RDBMS vs MongoDB, MongoDB CRUD, Orders embedded, Redis, Cassandra, HBase, Neo4j, deployment, sharding, replica-set, P2P, sharding+replication, MapReduce, distribution models (Q1–Q15)
- `LAB3.md` – Lab Sheet 3: 15 MongoDB apps – activity tracking, event logging, blogging, product catalog, e-commerce, analytics, CMS, cart, reviews, inventory, wallet transactions, notifications, course platform, order tracking, news DB
- `LAB4.md` – Lab Sheet 4: HBase Q1–Q10 (`Student`, `Employee`, events, CMS, blogs, column-family model, `WebsiteCounter`, TTL sessions, row-key design, regions) + Cassandra Q11–Q15 (CollegeDB, employees, event logging, ONE/QUORUM/ALL, full event app)
- `LAB5.md` – Lab Sheet 5: Riak KV Q1–Q10 (`students`, `user_sessions`, profiles, carts, data types, quorum R/W, scaling, transaction-like, query-by-data, sets) + Neo4j Q11–Q15 (Student/Course/Dept, social network, e-commerce, transactions, Python app)

## How to run
```bash
# MongoDB
mongosh
# Redis
redis-cli
# Cassandra
cqlsh
# HBase
hbase shell
# Riak
curl http://localhost:8098/ping
# Neo4j Browser
# http://localhost:7474
pip install neo4j requests
```

## Push to GitHub
```bash
cd "C:\Users\gandh\OneDrive\Documents\Default Project"
git init
git add LAB2.md LAB3.md LAB4.md LAB5.md README.md
git commit -m "Add NoSQL Lab Sheets 2-5 solutions"
git branch -M main
git remote add origin https://github.com/<your-username>/<your-repo>.git
git push -u origin main
```
Replace `<your-username>/<your-repo>` with your repo. If repo already exists locally, skip `git init` and just `git add/commit/push`.
