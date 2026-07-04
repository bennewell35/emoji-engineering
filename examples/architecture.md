# Architecture

Tiny diagrams for APIs, services, queues, workers, databases, and system boundaries.

## Tiny Architecture Map

```text
📱 → 🌐 → 🧠 → 🗄️
          ↓
         ⚙️
          ↓
         📊
```

Use for client, API, model, database, worker, and output.

## Queue Worker

```text
🌐
⬇️
📬
⬇️
⚙️
⬇️
🗄️
```

Use for request, queue, worker, and persistence.

## Cache Layer

```text
👤 → 🌐 → 🟦 → 🗄️
          cache
```

Use for explaining a cache between API and database.

## Event Pipeline

```text
📱
⬇️
📨
⬇️
⚙️
⬇️
📊
```

Use for event capture, processing, and analytics.

## Boundary Map

```text
👤 | 📱 | 🌐 | 🗄️
user client api data
```

Use for making ownership or trust boundaries visible.
