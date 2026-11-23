    <!--
      使用说明（GitHub 不渲染 HTML 注释）
      1. 头像直接引用 GitHub 头像，无需额外上传
      2. 把占位的 agent-runtime / search-platform / ops-console 换成你的真实仓库地址
      3. VISITORS badge 依赖 komarev.com，如不想依赖第三方可整行删除
    -->

    <div align="center">

    <img src="https://github.com/AikawaNarushika.png" width="100" alt="AikawaNarushika" />

    # AikawaNarushika

    `backend engineer` · `search` · `agent runtime` · `full-stack` ▌

    [![Email](https://img.shields.io/badge/2386905913@qq.com-c14438?style=flat-square&logo=gmail&logoColor=white)](mailto:2386905913@qq.com)
    [![GitHub](https://img.shields.io/badge/AikawaNarushika-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/AikawaNarushika)
    ![Visitors](https://komarev.com/ghpvc/?username=AikawaNarushika&style=flat-square&color=0d1117&label=VISITORS)

    </div>

    ---

    ## `$ whoami`

    ```bash
    $ whoami
    aikawa

    $ cat ~/.profile
    role        : Backend Engineer
    focus       : [ search-engine, agent-runtime, full-stack ]
    languages   : Java · TypeScript · SQL · Shell
    timezone    : UTC+8  (Asia/Shanghai)
    open_to     : backend architecture · search systems · agent engineering
    principle   : make it work, make it fast, make it run itself
    status      : ONLINE — turning internal Java services into agent-callable tools
    ```

    ---

    ## `$ stack --list`

    **core**
    ![Java](https://img.shields.io/badge/Java_17-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
    ![Spring Boot](https://img.shields.io/badge/Spring_Boot_3-6DB33F?style=flat-square&logo=springboot&logoColor=white)
    ![Spring Cloud](https://img.shields.io/badge/Spring_Cloud-6DB33F?style=flat-square&logo=spring&logoColor=white)
    ![Elasticsearch](https://img.shields.io/badge/Elasticsearch_8-005571?style=flat-square&logo=elasticsearch&logoColor=white)

    **data**
    ![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
    ![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
    ![Kafka](https://img.shields.io/badge/Kafka-231F20?style=flat-square&logo=apachekafka&logoColor=white)

    **delivery**
    ![Vue](https://img.shields.io/badge/Vue_3-4FC08D?style=flat-square&logo=vuedotjs&logoColor=white)
    ![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
    ![CI](https://img.shields.io/badge/CI/CD-0d1117?style=flat-square&logo=githubactions&logoColor=white)

    ```bash
    $ tree ~/stack -L 2
    stack
    ├── core      Java 17 · Spring Boot 3 · Spring Cloud
    ├── search    Elasticsearch 8 · aliases / analyzers / relevance tuning
    ├── data      MySQL · Redis · Kafka
    ├── frontend  Vue 3 · TypeScript · Vite
    └── ops       Docker · CI · tracing
    ```

    ---

    ## `$ ls ~/projects`

    ### [agent-runtime](https://github.com/AikawaNarushika/agent-runtime) — self-built agent orchestration + Function Call

    ```bash
    $ head -4 agent-runtime/README.md
    self-built orchestration, no framework magic:
      plan -> select tool -> function call -> observe -> retry
    ```

    - **Four decoupled layers**: `Planner` / `Tool Registry` / `Executor` / `Memory`, each replaceable
    - **Tools are annotations**: a Java service method is auto-exposed as an agent tool with a generated JSON Schema
    - **Execution guardrails**: tool whitelist, argument validation, timeout, circuit breaking, idempotent replay
    - **Observable by default**: one Trace ID flows through `Agent → Tool → Service`, every call replayable

    ### [search-platform](https://github.com/AikawaNarushika/search-platform) — Elasticsearch retrieval platform

    - Index aliases + dual-write switching → **zero-downtime** reindexing
    - Custom CJK analyzer for better Chinese recall
    - Search **p99: 300ms → 80ms**

    ### [ops-console](https://github.com/AikawaNarushika/ops-console) — full-stack delivery

    - Spring Boot services sustaining **5K RPS**
    - Vue 3 console with real-time metrics and service orchestration
    - Redis cache layer cutting DB load by **40%**

    ---

    ## `$ cat ~/.status | jq`

    ```json
    {
      "role"        : "backend engineer",
      "status"      : "online",
      "building"    : "agent-runtime",
      "shipping"    : ["search-platform", "ops-console"],
      "open_to"     : ["backend architecture", "search engineering", "agent engineering"],
      "timezone"    : "UTC+8",
      "reply_within": "24h"
    }
    ```

    ---

    ## `$ tail -f ~/focus.log`

    ```bash
    2026-11  agent observability   call traces · token cost · tool success rate
    2026-11  tool-ify retrieval    expose search as a standard agent tool
    2026-10  microservices         Spring Cloud splitting and governance
    2026-09  low-latency JVM       GC tuning and memory layout
    ```

    ---

    ## `$ cat PRINCIPLES.md`

    ```markdown
    1. Make it correct, then make it fast, then make it self-driving.
    2. Every layer of complexity must pay rent in measurable gains.
    3. Write docs for yourself three months later.
    ```

    ---

    <div align="center">
    <sub>// EOF — <a href="mailto:2386905913@qq.com">2386905913@qq.com</a> · <a href="https://github.com/AikawaNarushika">github.com/AikawaNarushika</a></sub>
    </div>
