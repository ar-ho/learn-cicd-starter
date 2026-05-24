![code coverage badge](https://github.com/ar-ho/learn-cicd-starter/actions/workflows/ci.yml/badge.svg)

# learn-cicd-starter (Notely)

- This repo contains the starter code for the "Notely" application for the "Learn CICD" course on [Boot.dev](https://boot.dev).

- It's a showcase project that show's a working CICD pipeline and deploys a small project!

## Local Development

1. Make sure you're on Go version 1.22+.

2. Create a `.env` file in the root of the project with the following contents:

```bash
PORT="8080"
```

3. Run the server:

```bash
go build -o notely && ./notely
```

*This starts the server in non-database mode.* It will serve a simple webpage at `http://localhost:8080`.

You do *not* need to set up a database or any interactivity on the webpage yet. Instructions for that will come later in the course!

Arne's version of Boot.dev's Notely app.

### Misc

- Image
![Alt text](/home/a/Downloads/apu_hacker.jpeg)

- Quote
> this is a quote

- Table
| Feature | Status      |
|---------|-------------|
| Login   | Done        |
| API     | In Progress |


