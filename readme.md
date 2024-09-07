## How to use


1. Clone the repository
```bash
git clone <repository-url>
cd <repository-url>
```

2. Install Go Packages
```bash
go mod tidy
```

3. Run the application
```bash
go run main.go
```

4. Build the application
```bash
go build -o <output-name> && ./<output-name>
```

5. use --debug flag to enable debug mode
```bash
go run main.go --debug
```

env file
```bash
cp .env.example .env

JWT_SECRET=
POLKA_KEY=
```