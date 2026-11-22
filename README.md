<p align="center">
  <img src="./assets/usman-virk-banner.png" width="100%" alt="Usman Virk, Senior Software Engineer in Germany with 7+ years of experience">
</p>

I build software end to end: backend services, web and mobile clients, data models, and the deployment and monitoring around them. I have 7+ years of experience, and this profile keeps growing as I add projects across more of that work.

Each project says what it covers and where it stops. Together they carry more than 1,600 automated tests, and the ones that need a database or a queue run against the real service.

I work in **Python, Go and TypeScript** (React and Node.js). Projects are grouped by language below.

_These projects were built with AI assistance._

**Jump to:** [Python](#python) · [Go](#go) · [React and front end](#react-and-front-end) · [Node.js and TypeScript back end](#nodejs-and-typescript-back-end)

## Python

FastAPI, Django, Django REST Framework, Celery, SQLAlchemy, PostgreSQL, Redis. [Show only these projects](https://github.com/VirkUsman?tab=repositories&language=python)

- [payout-runs](https://github.com/VirkUsman/payout-runs): seller payouts that pay once, even when a worker is killed mid transfer
- [seat-holds](https://github.com/VirkUsman/seat-holds): a seat that cannot be sold twice, a group that gets all its seats or none, and a seat map that updates live
- [webhook-relay](https://github.com/VirkUsman/webhook-relay): webhooks that keep retrying through restarts, signed, replay-protected and with a dead-letter list
- [rate-limits](https://github.com/VirkUsman/rate-limits): five rate limiters measured under 50 concurrent clients, including the one that admits double at a boundary
- [release-watch](https://github.com/VirkUsman/release-watch): a release that takes live traffic only as far as its measurements allow, and goes back by itself when they say no
- [answer-sources](https://github.com/VirkUsman/answer-sources): answers from a document set that name the passages they used, with retrieval measured on a labelled set

## Go

PostgreSQL with pgx, Redis, RabbitMQ, Protobuf, Kubernetes. [Show only these projects](https://github.com/VirkUsman?tab=repositories&language=go)

- [outbox](https://github.com/VirkUsman/outbox): a database write and its published message that cannot disagree
- [push-fanout](https://github.com/VirkUsman/push-fanout): one price drop to 40,000 devices, one notification per person
- [cache-stampede](https://github.com/VirkUsman/cache-stampede): 2,000 origin calls collapsed into 1 when a popular key expires
- [query-plans](https://github.com/VirkUsman/query-plans): four queries fixed, including a textbook N+1 fix that ran 600 times slower
- [mobile-bff](https://github.com/VirkUsman/mobile-bff): payloads cut from 270 KB to 3.4 KB, with the budget enforced by a test
- [offline-basket](https://github.com/VirkUsman/offline-basket): a cart that survives a dead signal: 200 offline actions, settled once
- [api-versioning](https://github.com/VirkUsman/api-versioning): four live versions of one endpoint, pinned by golden files
- [contract-checks](https://github.com/VirkUsman/contract-checks): fails a pull request that would break an app already on a phone
- [graded-catalogue](https://github.com/VirkUsman/graded-catalogue): a marketplace where every unit is one of a kind
- [k8s-rollout](https://github.com/VirkUsman/k8s-rollout): why rolling deploys return 502s, and the drain order that stops it

## React and front end

React, Next.js, Redux, Vue, Vite, Tailwind CSS, React Native. [Show only these projects](https://github.com/VirkUsman?tab=repositories&q=react)

- [clinic-slots](https://github.com/VirkUsman/clinic-slots): A clinic booking app where 50 patients pressing Book at once still get one appointment per slot
- [table-state](https://github.com/VirkUsman/table-state): A data table for 50,000 rows where a slow old response can never overwrite newer data
- [form-schema](https://github.com/VirkUsman/form-schema): a multi-step form built from a schema, with validation races, saved drafts and screen reader announcements
- [live-board](https://github.com/VirkUsman/live-board): A shared task board that replays exactly what you missed after a dropped connection, across two servers
- [shift-swaps](https://github.com/VirkUsman/shift-swaps): a team rota where two approvals at the same moment cannot put one person on two shifts
- [outage-notes](https://github.com/VirkUsman/outage-notes): a public status page that stays up when the service it reports on is down, and never shows green because it could not check
- [price-watch](https://github.com/VirkUsman/price-watch): one feature across a service, a mobile app and a web page, with a generated contract
- [ts-api-client](https://github.com/VirkUsman/ts-api-client): the API client a mobile app uses, with single-flight refresh and full jitter

## Node.js and TypeScript back end

Express, MongoDB, GraphQL, PostgreSQL, Redis, BullMQ. [Show only these projects](https://github.com/VirkUsman?tab=repositories&q=nodejs)

- [fleet-logs](https://github.com/VirkUsman/fleet-logs): a maintenance records API for many fleet companies, where no company can read another's data
- [order-graph](https://github.com/VirkUsman/order-graph): an API where hostile queries are refused and the N+1 problem is proven gone by counting statements
- [app-session](https://github.com/VirkUsman/app-session): refresh token rotation where a stolen token ends the whole family
- [thumb-queue](https://github.com/VirkUsman/thumb-queue): an image job queue with one output per image however often it is sent, and a clean drain on shutdown

## Contact

[LinkedIn](https://www.linkedin.com/in/usman-virk)
