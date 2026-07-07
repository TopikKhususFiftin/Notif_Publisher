# Project Structure

Dokumentasi automatically generated dari struktur proyek.

## Root
- `main.go`
- `README.md`
- `.gitignore`
- `config/config.go`

## config
- `config.go`

## internal
- `entity/entity.go`
- `entity/response.go`
- `handler/handler.go`
- `repository/rabbitmq_repo.go`
- `usecase/message_usecase.go`

## pkg
- `rabbitmq/connection.go`

---

## Penjelasan singkat
- `main.go`: entrypoint aplikasi.
- `config/config.go`: konfigurasi aplikasi.
- `internal/entity`: model data entitas dan response.
- `internal/handler`: HTTP/handler logic.
- `internal/repository`: akses data / repo untuk RabbitMQ.
- `internal/usecase`: business logic usecase.
- `pkg/rabbitmq`: koneksi RabbitMQ.
