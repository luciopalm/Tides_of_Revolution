# Tides Of Revolution — Build Repository

Este repositório é destinado à distribuição de builds jogáveis de **Tides Of Revolution**.

> Este repositório não contém o código-fonte completo do jogo.  
> Ele serve para disponibilizar versões compiladas, instruções de instalação, notas de versão e arquivos auxiliares para testes.

---

## Sobre o jogo

**Tides Of Revolution** é um RPG 2D top-down com foco em exploração, progressão de personagem, navegação, combate naval, quests, NPCs, coleta de recursos, gerenciamento de inventário e sistemas de mundo persistente.

O jogo ainda está em desenvolvimento. Builds disponibilizadas aqui podem conter bugs, sistemas incompletos ou ajustes temporários de balanceamento.

---

## Plataformas

Builds disponíveis neste repositório podem variar por versão.

Plataformas planejadas ou usadas para teste:

- macOS
- Windows
- Linux, futuramente, se houver build publicada

Verifique sempre a pasta ou release correspondente à sua plataforma.

---

## Como baixar

Na página do repositório, procure a versão mais recente em:

```txt
Releases
```

ou baixe diretamente o arquivo disponibilizado na pasta de builds.

Arquivos comuns:

```txt
TidesOfRevolution_macOS.zip
TidesOfRevolution_Windows.zip
TidesOfRevolution_Linux.zip
```

---

## Instalação no macOS

1. Baixe o arquivo `.zip` da build para macOS.
2. Extraia o arquivo.
3. Você verá um aplicativo parecido com:

```txt
Tides Of Revolution.app
```

4. Arraste o aplicativo para:

```txt
Applications / Aplicativos
```

5. Abra o jogo.

### Aviso de segurança do macOS

Se o macOS bloquear o jogo com uma mensagem de desenvolvedor não verificado, use um dos métodos abaixo:

#### Opção 1

1. Clique com o botão direito no app.
2. Selecione **Open / Abrir**.
3. Confirme a abertura.

#### Opção 2

1. Abra **System Settings / Ajustes do Sistema**.
2. Vá em **Privacy & Security / Privacidade e Segurança**.
3. Procure o aviso sobre o app bloqueado.
4. Clique em **Open Anyway / Abrir Mesmo Assim**.

Esse aviso pode aparecer em builds de teste que ainda não foram assinadas e notarizadas para distribuição pública.

---

## Instalação no Windows

1. Baixe o arquivo `.zip` da build para Windows.
2. Extraia a pasta.
3. Abra o executável:

```txt
Tides Of Revolution.exe
```

Se o Windows SmartScreen mostrar um aviso, confirme apenas se você baixou a build diretamente deste repositório oficial.

---

## Como jogar

Controles principais podem mudar durante o desenvolvimento, mas a base atual é:

| Ação | Tecla / Input |
|---|---|
| Movimento | WASD ou setas |
| Interagir / avançar diálogo | E |
| Ataque terrestre | Clique esquerdo |
| Abrir quest log | L |
| Entrar no interior do barco | B ou botão da HUD, quando disponível |
| Salvar / carregar | Menu de Save/Load do jogo |

Alguns controles podem variar conforme o contexto, por exemplo, navegação, combate naval, pesca, diálogo, inventário ou menus.

---

## Save files

O jogo usa sistema de múltiplas instâncias/campanhas e slots de save.

Em builds de teste, o jogo pode criar automaticamente um primeiro save no **Slot 1** após a criação do personagem, dependendo da configuração da build publicada.

### Local aproximado dos saves

No macOS, os dados normalmente ficam em uma pasta parecida com:

```txt
~/Library/Application Support/<CompanyName>/<GameName>/
```

No Windows, os dados normalmente ficam em uma pasta parecida com:

```txt
C:\Users\<User>\AppData\LocalLow\<CompanyName>\<GameName>\
```

O caminho exato pode variar conforme o nome configurado no projeto Unity.

---

## Debug dumps e logs

Algumas builds podem incluir ferramentas de auditoria/debug.

Em builds com auditor ativo:

| Tecla | Ação |
|---|---|
| F8 | Inicia/finaliza gravação de auditoria |
| F9 | Exporta dump/debug para pasta local |

No Windows, dumps de debug podem aparecer em caminho semelhante a:

```txt
C:\Users\<User>\AppData\LocalLow\FungoGamesStudio\Tides Of Revolution\DebugDumps
```

Se você encontrou um bug visual, de UI, save/load ou progressão, envie o dump junto com uma descrição do problema.

---

## Como reportar bugs

Ao reportar um bug, inclua:

1. Versão da build.
2. Sistema operacional.
3. O que você estava fazendo antes do bug.
4. Passos para reproduzir.
5. Print ou vídeo, se possível.
6. Arquivo de log ou dump, se existir.
7. Se o bug envolve save/load, informe:
   - nome da campanha/instância;
   - slot usado;
   - se era novo jogo ou save carregado.

Modelo sugerido:

```txt
Versão da build:
Sistema operacional:
Descrição do problema:
Passos para reproduzir:
Resultado esperado:
Resultado obtido:
Ocorre sempre ou às vezes?
Arquivos anexos:
```

---

## Problemas conhecidos



```txt
- Algumas animações podem estar temporárias.
- Algumas UIs ainda estão em ajuste.
- Balanceamento de combate, fome, energia e recursos ainda pode mudar.
- Algumas quests podem depender de ordem específica de interação.
```

---

## Notas de versão

Bug fix geral

### Build 0.0.0.2

```txt
Data:11-06-2026
Plataforma: Win,MacOs
Mudanças:
Correções:
Problemas conhecidos:
```

---

## Recomendações para testers

- Comece um novo jogo quando a build indicar quebra de compatibilidade com saves antigos.
- Não renomeie arquivos internos da build.
- No macOS, mantenha o `.app` dentro de `Applications`.
- Ao reportar bugs, informe se o problema aconteceu após carregar um save ou em uma sessão nova.
- Guarde saves importantes antes de testar builds experimentais.

---

## Estado do projeto

**Tides Of Revolution** está em desenvolvimento ativo.

Sistemas já presentes ou em desenvolvimento incluem:

- Save/load multi-instância.
- Criação de personagem.
- Inventário.
- Party.
- Quests.
- Diálogos.
- NPCs com agenda.
- Relacionamento com NPCs.
- Coleta de recursos.
- Containers persistentes.
- Sistema de tempo.
- Clima.
- Energia, fome e sono.
- Barco e navegação.
- Interior do barco.
- Combate naval.
- Boarding.
- Combate em turnos.
- Pesca.
- Dungeons temporárias.
- Sistema de loja.
- Localização.

---

## Créditos

Desenvolvido por **Fungo Games Studio**.

Projeto em desenvolvimento por **Lúcio Palmieri**.

---

## Licença e distribuição

Esta build é fornecida apenas para teste, avaliação ou distribuição controlada, conforme indicado pelo desenvolvedor.

Não redistribua builds privadas sem autorização.
Não publique saves, dumps ou logs que contenham dados pessoais de outros jogadores.
