# Daniel Suh

Software engineer at Persist AI Formulations in Sacramento, California. I own our lab
information management system end to end and build the infrastructure beneath a multi-agent
LLM platform for pharmaceutical formulation. Mostly PostgreSQL and FastAPI, with React and
TypeScript on top.

Most of what I do day to day is closed source, so this account is the other half: hardware,
home infrastructure, and things I wanted to exist.

## Projects

**[digicalender](https://github.com/dsuh02/digicalender)**
A touch-wall hub that runs my house. Configurable widgets on a fine-grained grid, with
calendars, to-dos, weather, and direct control of the Rokus, Govee plugs, and Samsung TVs on
the network. Python standard library plus Postgres, with no pip and no build step, which meant
writing a hand-rolled HTTP router, an SSE broadcaster, and a minimal RFC 6455 WebSocket client.
A wall display that will not boot because a package failed to compile is worse than a router I
wrote myself.

**[raspberry-pi-reverse-camera-screen](https://github.com/dsuh02/raspberry-pi-reverse-camera-screen)**
An always-on dash and reverse camera for a Lexus CT200h. A Pi 4B drives a 4.3 inch DSI touch
display through DRM/KMS with no desktop session, and an overlay service watches the capture
dongle so the camera appears the moment the feed goes live. Powered off an ACC fuse tap, so it
has to boot like an appliance every time the key turns.

**[lims-pi-scanners](https://github.com/dsuh02/lims-pi-scanners)**
Raspberry Pi barcode scanners that post container moves straight into a lab inventory system.
Two-step scan, USB HID, deployed with udev rules.

**[dsuh02.github.io](https://github.com/dsuh02/dsuh02.github.io)**
My site. Hand-written HTML, CSS, and JavaScript. No framework, no bundler, no build step,
deployed by git push.

## Stack

| | |
|---|---|
| **Languages** | Python, TypeScript, JavaScript, Java, C, C++, SQL, Bash |
| **Backend** | FastAPI, Flask, SQLAlchemy, Pydantic, asyncio, httpx, WebSockets, SSE |
| **Data** | PostgreSQL, pgvector, SQLite, MySQL, Alembic, schema migrations |
| **Frontend** | React, Vite, TypeScript, Zustand, Tailwind |
| **LLM systems** | multi-agent orchestration, tool calling, RAG, embedding pipelines, provider routing |
| **Infrastructure** | Docker, Azure, Linux, CI/CD, pytest, Playwright, Vitest |
| **Hardware** | OPC UA (asyncua), serial protocols, Raspberry Pi, embedded C |

## Elsewhere

[dsuh02.github.io](https://dsuh02.github.io) &middot;
[LinkedIn](https://www.linkedin.com/in/danielsuh8205/) &middot;
dsuh3508@gmail.com
