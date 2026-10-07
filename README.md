# Órbita • MapaTrader

Calculadora PWA sem dependências: responsiva, teclado, histórico local, copiar resultado e uso offline após o primeiro acesso.

## Executar

Na pasta appCalculadora, execute:

```powershell
python -m http.server 8080
```

Abra http://localhost:8080. Para disponibilizar no celular, publique todos os arquivos em uma hospedagem HTTPS. Um endereço HTTP na rede local não habilita instalação/offline; localhost vale apenas no próprio dispositivo.

## Instalar

Chrome/Edge: use “Instalar app” quando disponível ou a opção de instalação do navegador. iPhone/iPad no Safari: Compartilhar → Adicionar à Tela de Início. O modo offline fica pronto após o carregamento inicial e a ativação do service worker. Abrir index.html diretamente não habilita PWA.

## Operações

+ − × ÷, decimais, inversão de sinal, porcentagem e parênteses pelo teclado. Enter calcula, Backspace apaga, Escape limpa. Porcentagem divide o valor por 100: 200 × 10% = 20; 200 + 10% = 200,1. Resultados usam até 12 algarismos significativos; não é uma ferramenta de precisão financeira. Histórico armazena até 12 operações no dispositivo.

Para atualizar recursos offline, altere a versão de CACHE em sw.js.
