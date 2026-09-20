## Elbruz Mâfe Canbolat

Computer engineering student at Bandırma Onyedi Eylül University. I mostly build
Flutter apps and the backends they talk to, and I run everything I write on a
Debian box at home rather than a managed platform — which has taught me more
about the boring parts of software than any course has.

The thread through most of my projects is that I don't like tools that give you
an answer without showing their work. So the invoice reader points every field
back to a box on the page, the rota planner records why each shift was assigned,
and the RAG tool tells you which stage of the pipeline actually broke.

### What I'm working on

- **[sitewalk](https://github.com/ElbruzMafe/sitewalk)** — self-hosted inspection
  platform for recurring safety rounds. An answer is durable the moment it is
  typed, and the phone can prove what reached the server. Flutter + Fastify +
  Postgres.
- **[vouched](https://github.com/ElbruzMafe/vouched)** — invoice reader where every
  extracted field is grounded to a region of the page; anything it can't ground it
  drops rather than guesses, and it scores its own accuracy on your documents.
- **[fair-rota](https://github.com/ElbruzMafe/fair-rota)** — shift scheduler in Go
  that fills a weekly rota under hard constraints, spreads the unpopular shifts
  evenly, and explains every assignment.

Also around: [schema-drift](https://github.com/ElbruzMafe/schema-drift), which
watches live JSON APIs and reports breaking shape changes before they reach
production, and [rag-triage](https://github.com/ElbruzMafe/rag-triage), which tells
you whether a bad RAG answer is a corpus, retrieval or generation problem.

### Tech stack

Dart/Flutter · TypeScript (Node, Fastify, Next.js) · Python · Go
Postgres · SQLite · Docker · Debian/Linux self-hosting

### Contact

- GitHub: [@ElbruzMafe](https://github.com/ElbruzMafe)
- Email: furrkan432.fc@gmail.com
- LinkedIn: [elbruz-mâfe-canbolat](https://www.linkedin.com/in/elbruz-m%C3%A2fe-canbolat-77665b335)
- Site: [mafe.live](https://mafe.live)
