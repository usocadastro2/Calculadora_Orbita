# Órbita 

Órbita é uma calculadora feita para quem só quer resolver contas sem drama. Nada de botões escondidos ou menus infinitos — aqui é digitar, calcular e seguir viagem.

O que ela faz (sem frescura)
Soma, subtrai, multiplica e divide sem reclamar

Aguenta uns cálculos mais parrudos também

Guarda o histórico, porque ninguém merece refazer conta perdida

Interface simples, limpa e sem enfeite desnecessário

Por que usar?
Porque às vezes você só precisa de uma calculadora que funcione. Orbita é isso: prática, direta e sempre pronta para salvar seu dia

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
