sequenceDiagram

    browser->>server: POST https://studies.cs.helsinki.fi/exampleapp/new_note_spa activate server server-->>browser: [{ "content": "any gigguk fans", "date": "2023-1-1" }, .... ] deactivate server

Note right of browser: The server returns the new note as JSON data file containing both the content of the note and the timestamp.
