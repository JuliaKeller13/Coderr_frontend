<p align="center">
    <img src="assets/logo/logo_coderr.svg" alt="Coderr logo" width="220">
</p>

<h1 align="center">Coderr Frontend</h1>

Coderr is a service marketplace where customers can find IT services offered by business users.

- [Coderr backend](https://github.com/JuliaKeller13/coderr_backend)
- [Original Developer Akademie project](https://github.com/Developer-Akademie-Backendkurs/project.Coderr)

## About

Coderr is a service marketplace. Customers can browse offers, place orders and review business users.

The frontend was originally provided by Developer Akademie. I forked and adapted it to work with my own Django REST Framework backend.

## Tech Stack

- HTML5
- CSS3
- Vanilla JavaScript

## Run Locally

### Clone

```bash
git clone https://github.com/JuliaKeller13/Coderr_frontend.git
cd Coderr_frontend
```

### Backend

Follow the setup instructions in the [backend README](https://github.com/JuliaKeller13/coderr_backend#readme), then run the backend at:

`http://127.0.0.1:8000/`

### Frontend

Open the root `index.html` with the VS Code Live Server extension. The frontend is then available at:

`http://127.0.0.1:5500/`

### API Connection

The frontend connects to the backend through:

```javascript
const API_BASE_URL = 'http://127.0.0.1:8000/api/';
```

## Backend

I implemented the backend using Python, Django and Django REST Framework.

[View the Coderr backend repository](https://github.com/JuliaKeller13/coderr_backend)

## Project Context

Coderr is a Developer Akademie Backend curriculum project. The original frontend was provided by Developer Akademie, and this repository is my adapted frontend fork.

My main implementation work is in the [backend repository](https://github.com/JuliaKeller13/coderr_backend).

## License

The original frontend and assets are subject to the [Developer Akademie Learning License (Non-commercial)](LICENSE.md).

## Footer

Julia Keller · [GitHub](https://github.com/JuliaKeller13) · [Backend](https://github.com/JuliaKeller13/coderr_backend)

This project is based on work by [Developer Akademie](https://github.com/Developer-Akademie-Backendkurs/project.Coderr).
