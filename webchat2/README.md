How to run:
- serve `index.html` on `http://127.0.0.1:8080/` by running `npx http-server .` from this folder

- in a new terminal: run rasa server with `python3 -m rasa run --cors "*"` from the project root folder
- in a new terminal: run rasa actions server with `python3 -m rasa run actions` from the project root folder

- in a new terminal: run rasa server with `rasa run --cors "*"` from the project root folder
- in a new terminal: run rasa actions server with `rasa run actions` from the project root folder


# Via REST 

- POST `http://localhost:5005/webhooks/rest/webhook`
```json
{
  "sender": "test_user",
  "message": "Hi there!"
}
```