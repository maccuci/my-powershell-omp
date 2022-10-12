# Windows PowerShell

Utilize esse arquivo .omp.json para customizar o seu PowerShell do windows, para ficar mais agradável aos olhos e melhorar o entendimento do que ocorre na sua tela.

## Instalação
Após baixar ou clonar o repositório, vá até o seu arquivo .ps1 e insira a seguinte linha

```
$omp_config = Join-Path $PSScriptRoot ".\name.omp.json"
oh-my-posh --init --shell pwsh --config $omp_config | Invoke-Expression
```
