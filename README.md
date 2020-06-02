# LOGFILE

Essa biblioteca irá ajudar a gerar arquivos de log quando aplicação estiver em produção.

# Exemplo
```go
import("github.com/DuxxSolucoes/go-log-file")

func main() {
  // Production
  logfile.LogFileDay("Error loading", true)
  // Development
  logfile.LogFileDay("Error loading", false)
}
```
