# Chapter 2

Curl commands:
    
    curl http://0.0.0.0:8000

    curl http://0.0.0.0:8000/todo
    
    curl http://0.0.0.0:8000/todo -H "Content-Type: application/json" -d '{
        "id": 1,
        "item": "First todo is to finish this book!"
    }'

    curl http://0.0.0.0:8000/todo -H "Content-Type: application/json" -d '{}'
