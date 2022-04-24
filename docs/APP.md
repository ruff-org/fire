# App
At the core of the HTML monolith is a visible, interactive, reactive app component.

## What is it?
The app component is basically a wrapper which denotes the active/interactive pane in a web application.
This pane is usually pre-rendered by the backend (see: [Ice](https://github.com/ruff-org/ice)), and delivered to the client upon request.
Note: While backend routing delivers each content pane, a front-end routing library can also be utilized to control states on the client-side. When both routing strategies are used together, they create what's known as an isomorphic application.

> By isomorphic we mean that any given line of code (with notable exceptions) can execute both on the client and server.

**- Charlie Robbins 18 Oct 2011**