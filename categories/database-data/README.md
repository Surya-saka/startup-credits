# Database & Data Infrastructure

Database-as-a-service and data pipeline credits for startups.

---

## Document Databases

### MongoDB for Startups
- **Credits:** Up to $5,000
- **Duration:** 12 months

#### Two Tracks Available

| Track | Credits | Focus |
|-------|---------|-------|
| General | $5,000 | MongoDB Atlas |
| AI Startups | $5,000 | AI + co-sell program |

- **Eligibility:**
  - Series A or earlier
  - Building a product (not consulting)
  - First-time participants
  - Active website and LinkedIn
- **Benefits:**
  - MongoDB Atlas credits
  - Unlimited MongoDB University access
  - 1:1 technical consultations
  - Professional service credits
  - Co-marketing opportunities
  - Multi-cloud deployment
- **AI Track Bonus:** MongoDB Ventures investment consideration
- **Link:** [mongodb.com/solutions/startups](https://www.mongodb.com/solutions/startups)

---

## Serverless Postgres

### Neon
| Program | Credits | Target |
|---------|---------|--------|
| Standard | $100 | Developers |
| YC Startup Deal | $100,000 | Y Combinator companies |

- **Link:** [neon.tech](https://neon.tech/)
- **YC Link:** [neon.tech/yc](https://neon.tech/yc)

---

## Distributed SQL

### CockroachDB Cloud Free Trial
- **Credits:** $400
- **Target:** New organizations
- **Features:** Distributed SQL, multi-region
- **Link:** [cockroachlabs.com/pricing/](https://www.cockroachlabs.com/pricing/)

---

## NoSQL & Vector

### DataStax Astra DB
- **Credits:** $300/year
- **Target:** Developers building with Cassandra
- **Link:** [astra.datastax.com](https://astra.datastax.com/)

### Neo4j
| Program | Value | Target |
|---------|-------|--------|
| AuraDB Free | Free tier | All users |
| Startup Program | Custom | Enterprise startups |

- **Link:** [neo4j.com/cloud/aura-free/](https://neo4j.com/cloud/aura-free/)

---

## Time-Series & Caching

### InfluxDB Free Trial
- **Credits:** $250
- **Target:** Time-series workloads
- **Link:** [influxdata.com](https://www.influxdata.com/)

### Redis Startup Program
- **Credits:** $10,000
- **Target:** Early-stage startups
- **Features:** Redis Cloud, caching, pub/sub
- **Link:** [redis.com/startups/](https://redis.com/startups/)

---

## Managed Data Services

### Aiven Cluster Startup Program
- **Credits:** $100,000
- **Target:** Startups via partner programs
- **Services:** Managed Kafka, PostgreSQL, MySQL, Redis, etc.
- **Link:** [aiven.io/startup-program](https://aiven.io/startup-program)

---

## Data Pipelines

### Fivetran YC Startup Program
- **Credits:** $50,000
- **Duration:** 12 months

#### Two Options
| Program | Use Case |
|---------|----------|
| Standard Fivetran | Internal analytics |
| Powered by Fivetran | Product integration |

- **Eligibility:**
  - Y Combinator companies
  - <$5M raised
  - Not previous Fivetran customers
- **Benefits:**
  - 700+ pre-built connectors
  - Technical support
  - Automated pipeline maintenance
- **Links:**
  - Standard: [go.fivetran.com/startup-program-standard-yc](https://go.fivetran.com/startup-program-standard-yc)
  - Powered: [go.fivetran.com/startup-program-pbf-yc](https://go.fivetran.com/startup-program-pbf-yc)

---

## Comparison

| Database | Type | Max Credits | Best For |
|----------|------|-------------|----------|
| MongoDB | Document | $5,000 | Flexible schemas |
| Neon | Serverless Postgres | $100,000 | YC startups |
| CockroachDB | Distributed SQL | $400 | Multi-region |
| DataStax | Cassandra | $300 | High throughput |
| Neo4j | Graph | Free tier | Relationships |
| InfluxDB | Time-series | $250 | Metrics/IoT |
| Redis | Cache/KV | $10,000 | Caching |
| Aiven | Managed | $100,000 | Multi-service |
| Fivetran | Pipeline | $50,000 | Data integration |

---

## Stack Recommendations

### Early-Stage SaaS
- **Primary:** Neon (Postgres)
- **Cache:** Redis
- **Analytics:** Fivetran → warehouse

### AI/ML Application
- **Primary:** MongoDB
- **Vector:** Pinecone (see AI/ML section)
- **Pipeline:** Fivetran

### High-Scale Application
- **Primary:** CockroachDB
- **Cache:** Redis
- **Streaming:** Aiven (Kafka)
