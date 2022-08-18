Criei uma API de teste do funcionamento das lojas de pequeno porte, utilizando Laravel e Blade (como Tamplate Enginne)
Exemplos de alguns End-points a seguir :

Buscar todas a lojas no banco :
- # 127.0.0.1:8000/api/stores
Resultado :
"current_page": 1,
    "data": [
        {
            "id": 1,
            "name": "tempore repellendus rerum",
            "description": "Cupiditate deleniti adipisci ut nostrum nam autem.",
            "created_at": "2022-08-09T01:45:58.000000Z",
            "updated_at": "2022-08-09T01:45:58.000000Z"
        },
        {
            "id": 2,
            "name": "corporis ad omnis",
            "description": "Fugit excepturi nam voluptas repellat saepe.",
            "created_at": "2022-08-09T01:46:25.000000Z",
            "updated_at": "2022-08-09T01:46:25.000000Z"
        },
        {
            "id": 3,
            "name": "deserunt fugit incidunt",
            "description": "Et sed et omnis temporibus.",
            "created_at": "2022-08-09T01:47:06.000000Z",
            "updated_at": "2022-08-09T01:47:06.000000Z"
        },
        {
            "id": 4,
            "name": "quis architecto ut",
            "description": "Ullam accusamus quo eaque sint repellendus voluptas ut excepturi.",
            "created_at": "2022-08-09T01:52:07.000000Z",
            "updated_at": "2022-08-09T01:52:07.000000Z"
        },
        {
            "id": 5,
            "name": "est quaerat quas",
            "description": "Est illo vitae doloribus sit.",
            "created_at": "2022-08-09T01:52:07.000000Z",
            "updated_at": "2022-08-09T01:52:07.000000Z"
        },
        {
            "id": 6,
            "name": "ipsam quia odit",
            "description": "Expedita autem rerum dolor voluptatem molestiae.",
            "created_at": "2022-08-09T01:52:07.000000Z",
            "updated_at": "2022-08-09T01:52:07.000000Z"
        },
        {
            "id": 7,
            "name": "pariatur animi est",
            "description": "Ab illo dolorum hic doloremque.",
            "created_at": "2022-08-09T01:52:07.000000Z",
            "updated_at": "2022-08-09T01:52:07.000000Z"
        },
        {
            "id": 8,
            "name": "quasi autem ut",
            "description": "Doloremque natus adipisci et et maxime.",
            "created_at": "2022-08-09T01:52:07.000000Z",
            "updated_at": "2022-08-09T01:52:07.000000Z"
        },
        {
            "id": 9,
            "name": "voluptatem aliquam deserunt",
            "description": "Recusandae voluptatem delectus quam vitae facilis similique et.",
            "created_at": "2022-08-09T01:52:07.000000Z",
            "updated_at": "2022-08-09T01:52:07.000000Z"
        },
        {
            "id": 10,
            "name": "ut laboriosam minus",
            "description": "Qui neque et hic quia.",
            "created_at": "2022-08-09T01:52:07.000000Z",
            "updated_at": "2022-08-09T01:52:07.000000Z"
        }
    ],
    "first_page_url": "http://127.0.0.1:8000/api/stores?page=1",
    "from": 1,
    "last_page": 2,
    "last_page_url": "http://127.0.0.1:8000/api/stores?page=2",
    "links": [
        {
            "url": null,
            "label": "&laquo; Previous",
            "active": false
        },
        {
            "url": "http://127.0.0.1:8000/api/stores?page=1",
            "label": "1",
            "active": true
        },
        {
            "url": "http://127.0.0.1:8000/api/stores?page=2",
            "label": "2",
            "active": false
        },
        {
            "url": "http://127.0.0.1:8000/api/stores?page=2",
            "label": "Next &raquo;",
            "active": false
        }
    ],
    "next_page_url": "http://127.0.0.1:8000/api/stores?page=2",
    "path": "http://127.0.0.1:8000/api/stores",
    "per_page": 10,
    "prev_page_url": null,
    "to": 10,
    "total": 14
}
