[![Hits](https://hits.seeyoufarm.com/api/count/incr/badge.svg?url=https%3A%2F%2Fgithub.com%2Fakilans%2Fgolang-mini-projects%2Ftree%2Fmain%2F04-bookstore-api&count_bg=%2379C83D&title_bg=%23555555&icon=&icon_color=%23E7E7E7&title=hits&edge_flat=false)](https://hits.seeyoufarm.com)

# Bookstore REST API

This is REST based API to list, add, update and delete books using local JSON

### Build and run

```bash
go build
./bookstore

```

### URL and request

- Get all the books - http://localhost:8080
- Get book by id - http://localhost:8080/book?id=1
- Delete book by id - http://localhost:8080/delete?id=5
- Add books - http://localhost:8080/add
- Update book - http://localhost:8080/update

```
