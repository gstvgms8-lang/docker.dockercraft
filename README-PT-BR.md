# docker.dockercraft — guia de referência em português

Guia próprio deste fork. Revisão documental: **21/09/2026**.

[Documentação original preservada](./README.md) · [Catálogo de referências](https://github.com/gstvgms8-lang/referencias-projetos)

## 1. Origem do projeto

- Projeto original: [docker-archive-public/docker.dockercraft](https://github.com/docker-archive-public/docker.dockercraft).
- Nossa cópia: [gstvgms8-lang/docker.dockercraft](https://github.com/gstvgms8-lang/docker.dockercraft).
- Contexto: referência identificada nas imagens reunidas no catálogo.
- Autoria e licenças continuam pertencendo aos respectivos titulares. Conferir a licença aplicável antes de incorporar código ou assets.

## 2. Breve descrição em português

Experimento que representa e administra contêineres Docker dentro de um mundo de Minecraft.

## 3. Por que salvamos

Guardar uma ideia de interface visual para sistemas externos e estudar comunicação por eventos.

## 4. Partes que podem ser úteis para nós

- [README.md](./README.md): Explicação do fluxo Minecraft → plugin → Docker.
- [Docker](./Docker): Plugin associado à interface no jogo.
- [daemon.go](./daemon.go): Parte do daemon de integração.
- [docs](./docs): Imagens e referências visuais do experimento.

## 5. Tecnologias utilizadas

Go no daemon, Lua no plugin, Docker e Docker Compose. O servidor de Minecraft utilizado é Cuberite, implementado em C++.

## 6. Ideias de adaptação para Flutter, Python e APIs

As propostas abaixo são ideias para experimentos futuros; precisam de implementação e validação.

- Flutter: desenhar um painel visual de serviços inspirado na representação de estados.
- Python: simular eventos de contêineres e publicar somente informações de leitura.
- APIs: estudar uma camada intermediária com permissões, sem expor o socket Docker ao cliente.

**Primeiro experimento sugerido:** Reproduzir a visualização com eventos simulados antes de conectar qualquer infraestrutura.

## 7. Nível prioritário

**Baixa — sugestão inicial.** Referência histórica e de interação; o original está arquivado e exige modernização para uso real.

Critério comum da coleção: **alta** para aplicação próxima em Flutter/Python/APIs; **média** para um objetivo específico ou estudo mais profundo; **baixa** para exploração ou utilidade indireta. Reavaliar quando houver requisitos do próximo projeto. Prioridade não representa qualidade do original nem garantia de ganho de desempenho.

## 8. Nossas observações à medida que estudamos

**Situação atual:** documentação e estrutura consultadas; execução e integração ainda não realizadas.

O README original informa ausência de autenticação e privilégios elevados para jogadores. A primeira adaptação deve usar dados simulados; não tratamos este código como base pronta para produção.

| Data | O que estudamos | Evidência ou resultado | Decisão / próximo passo |
| --- | --- | --- | --- |
| 21/09/2026 | Triagem documental | Identificados os caminhos e tecnologias acima; sem testes de execução | Avaliar o primeiro experimento sugerido |
| A preencher | Parte ou funcionalidade estudada | Medida, teste, erro reproduzível ou link de commit | Adotar, adaptar, descartar ou investigar |

Ao registrar um experimento, informar ambiente, versão/commit e uma comparação antes/depois quando houver alegação de desempenho. Este fork é público: registrar apenas observações técnicas que possam ser compartilhadas.

---

Este guia complementa o material original. As ideias de adaptação e a prioridade são avaliações nossas, não compromissos dos mantenedores.

