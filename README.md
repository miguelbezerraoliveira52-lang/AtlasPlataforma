# 🚀 Atlas: Ilhas dos Conjuntos

> Salte, explore e use a matemática para restaurar os portais da Atlas.

![Godot](https://img.shields.io/badge/Godot-4.4.1-478CBF?logo=godotengine&logoColor=white)
![GDScript](https://img.shields.io/badge/Linguagem-GDScript-355570)
![Categoria](https://img.shields.io/badge/Categoria-Plataforma%202D-8A2BE2)
![Educacional](https://img.shields.io/badge/Foco-Matemática-2EA44F)

## 📖 Sobre o projeto

**Atlas: Ilhas dos Conjuntos** é um jogo educacional de plataforma 2D desenvolvido em Godot.

O jogador controla a exploradora **Lia**, percorre ilhas, supera obstáculos e coleta cristais e cápsulas. Os conceitos matemáticos são aplicados durante a exploração e fornecem a energia necessária para ativar os portais.

## 🎯 Objetivo

Ensinar teoria dos conjuntos por meio de decisões e ações no cenário.

O jogador precisa observar os elementos disponíveis e identificar quais pertencem à coleção solicitada, aplicando os conceitos de:

- Definição de conjuntos e pertinência.
- União.
- Interseção.
- Complemento.
- Subconjuntos.

## 🌌 Enredo

Uma tempestade fragmentou a estação **Atlas** em cinco ilhas flutuantes.

Para recuperar a energia da estação e abrir o caminho de volta para casa, Lia precisa explorar cada ilha e restaurar seus portais.

Cada missão representa um conceito matemático. Os cristais coletados e as cápsulas recuperadas ajudam a reconstruir a Atlas.

## 🎮 Como jogar

1. Escolha uma ilha no mapa.
2. Leia a missão e observe os conjuntos apresentados.
3. Explore o cenário usando movimento, pulo duplo e impulso.
4. Aproxime-se de um cristal ou cápsula e pressione **E**.
5. Recolha os itens que satisfazem a operação da missão.
6. Complete a coleção para ativar o portal.
7. Entre no portal localizado no extremo direito da ilha.

> Itens inválidos permanecem no cenário e apresentam uma explicação. **Erros matemáticos não retiram vida.**

## 🗺️ Missões

| Ilha | Conceito | Objetivo |
|---|---|---|
| O jardim dos elementos | Definição e pertinência | Recolher os elementos pertencentes a A |
| As duas margens | União — A ∪ B | Reunir elementos pertencentes a A ou B |
| O eco entre mundos | Interseção — A ∩ B | Recolher elementos comuns aos dois conjuntos |
| O outro lado da aurora | Complemento — U ∖ A | Recuperar elementos de U que não pertencem a A |
| Cargas para o portal | Subconjuntos — C ⊆ A | Recolher cápsulas inteiramente contidas em A |

As cinco missões representam **20 coletas matemáticas distintas**, além das interações de movimento e exploração.

As ilhas compartilham a estrutura de plataformas, com variações de missão, paleta, objetos e perigos.

## 💎 Matemática no cenário

### Cristais

Cada cristal possui um número e uma marca de pertencimento.

| Marca | Significado |
|---|---|
| A | Pertence a A |
| B | Pertence a B |
| AB | Pertence a A e B |
| U | Pertence ao universo; os cristais assim marcados estão fora de A e B |
| Fora de U | Não pertence ao universo considerado |

Na missão de união, existem dois cristais com o mesmo valor para demonstrar que **repetir um elemento não aumenta um conjunto**.

Na missão de complemento, há um elemento fora do universo, reforçando que **não pertencer a A não é suficiente: o elemento também precisa pertencer a U**.

### Cápsulas

Na última ilha, cada cápsula representa um conjunto completo.

O jogador deve verificar se **todos os elementos da cápsula pertencem a A**.

A missão demonstra que:

- O conjunto vazio é subconjunto de qualquer conjunto.
- Todo conjunto é subconjunto de si mesmo.
- Um único elemento fora de A torna a cápsula inválida.

> Recolher uma cápsula ∅ é uma ação válida e diferente de não recolher nenhuma cápsula.

## ✨ Funcionalidades

- ✅ Cinco missões temáticas.
- ✅ Movimentação lateral e pulo duplo.
- ✅ Impulso horizontal.
- ✅ Plataformas elevadas e plataforma móvel.
- ✅ Abismos, espinhos e drones.
- ✅ Moedas como recompensa de exploração.
- ✅ Coleta de cristais e cápsulas.
- ✅ Validação matemática durante a coleta.
- ✅ Checkpoint.
- ✅ Sistema de energia do traje.
- ✅ Portais ativados pela conclusão da coleção.
- ✅ Tutorial, dicas e feedback visual e sonoro.
- ✅ Sistema de estrelas e salvamento local.
- ✅ Cenário e personagem desenhados por código.

## 🕹️ Controles

| Ação | Comando |
|---|---|
| Mover para a esquerda | `A` ou `←` |
| Mover para a direita | `D` ou `→` |
| Pular | `Espaço`, `W` ou `↑` |
| Executar pulo duplo | Pressionar a tecla de pulo novamente no ar |
| Usar impulso | `Shift` |
| Recolher item próximo | `E` |
| Consultar dica | `H` |
| Pausar ou continuar | `Esc` |
| Reiniciar a ilha | `R` |
| Ativar ou desativar o áudio | `M` |

### Dicas de movimento

- Soltar a tecla de pulo cedo reduz sua altura.
- Use o segundo pulo para alcançar plataformas mais altas.
- O impulso possui recarga de **0,75 segundo**.
- O impulso destrói drones durante sua execução.
- Espinhos continuam perigosos durante o impulso.

## ❤️ Traje e checkpoints

Lia possui um traje com **três cargas de energia**.

- Sofrer dano ou cair leva a personagem ao último checkpoint.
- A bandeira central ativa o checkpoint ao avançar pelo cenário.
- Cristais, cápsulas e moedas recolhidos são preservados após dano.
- Quando as três cargas acabam, o traje recarrega.
- Não existe tela de game over nem limite de tempo.

A primeira ilha não possui drones ou espinhos, permitindo aprender os controles antes dos desafios seguintes.

## ⭐ Sistema de estrelas

Cada ilha permite conquistar até três estrelas:

| Conquista | Recompensa |
|---|---|
| Concluir a ilha | ⭐ |
| Recolher pelo menos seis moedas | Uma estrela adicional |
| Sofrer no máximo dois impactos ou quedas | Uma estrela adicional |

As melhores estrelas ficam salvas, incentivando o jogador a revisitar as ilhas.

## 🛠️ Tecnologias

| Tecnologia | Aplicação |
|---|---|
| Godot 4.4.1 Standard | Motor do jogo |
| GDScript | Mecânicas e regras matemáticas |
| CharacterBody2D | Movimentação e colisões da personagem |
| StaticBody2D | Plataformas fixas |
| AnimatableBody2D | Plataforma móvel |
| Camera2D | Acompanhamento da personagem |
| WAV | Efeitos sonoros |

## 📂 Organização do projeto

| Arquivo ou pasta | Responsabilidade |
|---|---|
| `project.godot` | Configurações do projeto |
| `main.tscn` | Cena principal |
| `scripts/main.gd` | Menus, tutorial, painel, pausa, resultados e salvamento |
| `scripts/player.gd` | Movimento, saltos, impulso e desenho da personagem |
| `scripts/world.gd` | Cenário, colisões, itens, perigos, checkpoint e portal |
| `scripts/levels.gd` | Dados das missões e regras matemáticas |
| `assets/` | Efeitos sonoros |
| `tests/game_test.gd` | Testes de lógica e integração |
| `tests/traversal.gd` | Teste de percurso com a física do jogo |
| `previews/` | Capturas das telas |
| `export_presets.cfg` | Configurações de exportação |

A interface e os elementos do cenário são criados por código durante a execução.

## ▶️ Como executar

### Pelo Godot

1. Instale o **Godot 4.4.1 Standard**.
2. Extraia a pasta do projeto.
3. Abra o Godot e clique em **Importar**.
4. Selecione `AtlasPlataforma/project.godot`.
5. Aguarde a importação dos recursos.
6. Pressione **F5**.

> O projeto utiliza Godot 4 e não é compatível com Godot 3.

### Pelo executável Windows

1. Extraia o pacote Windows.
2. Execute `AtlasConjuntos.exe`.

Não é necessário instalar o Godot para jogar pelo executável.

### Pelo navegador

A versão Web deve ser servida por HTTP ou HTTPS.

Para um teste local com Python instalado, execute na pasta da exportação:

```bash
python -m http.server 8000
```

Acesse:

```text
http://localhost:8000
```

Mantenha todos os arquivos exportados na mesma pasta.

> A versão é destinada a computadores com teclado e não possui controles de toque.

## 💾 Salvamento

O jogo registra:

- As melhores estrelas de cada ilha.
- A preferência de áudio.

Os dados ficam armazenados em:

```text
user://atlas_platform.cfg
```

A coleção e as moedas da tentativa atual não são preservadas ao fechar o jogo, reiniciar a ilha ou retornar ao mapa.

Reiniciar uma ilha e apagar as estrelas salvas exigem confirmação.

## 🧪 Testes e validação

- **150 verificações de integração sem falhas.**
- Testes das regras matemáticas dos cinco temas.
- Verificação de coletas válidas, inválidas e repetidas.
- Testes de movimento, pulo duplo, impulso e coleta por proximidade.
- Verificação de colisões, dano, checkpoints e portais.
- Testes de pausa e salvamento.
- Percurso físico por **dez pontos**, incluindo as plataformas superiores e o portal.
- Revisão visual das principais telas.
- Exportação para Windows e Web.

Para executar os testes a partir da pasta do projeto:

```bash
godot --headless --path . --script res://tests/game_test.gd
godot --headless --path . --script res://tests/traversal.gd
```

> Os testes de integração escrevem estrelas no perfil local. Após executá-los, use a opção de apagar estrelas no mapa, se necessário.

Os testes foram realizados no Godot em Linux. O executável Windows e a exportação Web não foram executados em seus ambientes finais durante essa validação.

## 🎓 Contexto acadêmico

O projeto integra matemática e exploração: o jogador observa conjuntos, escolhe itens e recebe explicações enquanto avança pelo cenário.

Pode ser utilizado em apresentações acadêmicas e atividades de aprendizagem para alunos do ensino médio.

A apresentação em slides, a publicação de uma forma de acesso ao jogo e os testes de usabilidade com participantes reais devem ser realizados pela equipe.
