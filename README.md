# 🌳 FocaAí
> Protótipo de Baixa Fidelidade — Disciplina de IHC & UX

**FocaAí** é um aplicativo de produtividade focado em bem-estar digital, projetado com base nos princípios de **Calm Technology (Tecnologia Calma)** para ajudar usuários a manterem o foco sem gerar ansiedade ou culpa.

---

## 📋 Informações do Projeto

| Campo | Detalhes |
|---|---|
| **Instituição** | Centro Universitário UNA |
| **Disciplina** | Interação Humano-Computador (IHC) & UX |
| **Professor** | Daniel Henrique Matos de Paiva |
| **Entrega** | Lista de Exercícios XXI — Atividade Prática de Prototipagem de Baixa Fidelidade |

### 👥 Equipe

- Jonathan
- João Pedro
- João Zanardo
- Yago
- Lucas Nascimento

---

## 🧠 Abordagem de UX: Calm Technology

O design do FocaAí foi inteiramente planejado para **informar o usuário sem competir por sua atenção** ou gerar gatilhos de ansiedade — comuns em apps de produtividade hipercompetitivos.

| Princípio | Aplicação no FocaAí |
|---|---|
| **Atenção Periférica** | Elementos como o crescimento da árvore e o timer utilizam linhas finas e formas limpas para ficarem em segundo plano enquanto o usuário trabalha |
| **Foco no Positivo** | Em vez de monitorar "tempo de tela gasto" (gerador de culpa), o sistema foca no **"Tempo Ganho para a Vida Real"** |
| **Minimalismo** | Telas limpas, sem excesso de botões, cores berrantes ou notificações intrusivas |

---

## 📱 Telas do Protótipo

### 1. Dashboard Principal (Home)

A tela central do aplicativo, com hierarquia visual clara.

- **Elemento principal:** Timer circular com o tempo restante em destaque máximo
- **Elementos secundários:** Ícone minimalista da árvore digital (indicador de progresso) e botão de ação `[Iniciar Foco]`
- **Navegação:** Menu inferior (rodapé) com acesso rápido a Configurações, Grupos e Relatórios

---

### 2. Configuração de Bloqueio & Ambiente

Dividida em duas seções distintas para facilitar a leitura.

- **Seção superior — Sons do Ambiente:** Seletores de áudio (🌧️ Chuva, ☕ Café, 🌲 Floresta)
- **Seção inferior — Bloqueio de Apps:** Lista de redes sociais com Toggle Switches ON/OFF
- **Navegação:** Seta de retorno fixada no topo esquerdo para voltar ao Dashboard

---

### 3. Desafio em Grupo (Salas de Foco)

Foco no status coletivo, sem punição individual.

- **Elemento principal:** Pontuação total do grupo em destaque no topo
- **Elementos secundários:** Listagem vertical com avatares minimalistas dos participantes e barras de progresso indicando quem está em foco no momento
- **Navegação:** Acesso direto via menu de navegação inferior

---

### 4. Relatório de Conquistas ("Tempo Ganho")

Reforço positivo ao fim de cada ciclo.

- **Elemento principal:** Texto centralizado com as horas salvas na semana
- **Elementos secundários:** Frase motivacional ("Você ganhou X horas para a vida real!") e gráfico de barras vertical com árvores plantadas nos últimos dias
- **Navegação:** Acesso direto via menu de navegação inferior

---

### 5. Tela de Tentativa de Saída (Micro-interação)

Acionada automaticamente se o usuário tentar encerrar o foco antes do timer zerar.

- **Elemento principal:** Pop-up com mensagem empática: _"Sua árvore precisa de você. Tem certeza?"_
- **Botão primário (destaque visual):** `[Continuar Focado]`
- **Botão secundário (sutil):** Link em texto simples `Desistir e Sair`
- **Navegação:** Disparada automaticamente ao tentar quebrar o fluxo de foco

---

## 🔄 Fluxo de Navegação

```
[Configuração de Bloqueio & Sons]
         │
         ▼
[Dashboard Principal] ──── [Iniciar Foco]
         │                        │
         │               Tentativa de saída?
         │                        │
         │                ┌───────┴────────┐
         │                ▼                ▼
         │       [Continuar Focado]  [Desistir e Sair]
         │
         ▼ (timer concluído)
[Relatório de Conquistas 🌳]
```

O ciclo completo:

1. O usuário acessa a tela de **Configuração** para ajustar som ambiente e apps bloqueados
2. Retorna ao **Dashboard** e clica em `[Iniciar Foco]`
3. Caso tente sair durante o ciclo, a tela de **Tentativa de Saída** é disparada
4. Ao concluir o tempo, é direcionado ao **Relatório de Conquistas** para ver sua recompensa (árvore plantada + tempo ganho)

---

## 🗂️ Protótipo Interativo

> O wireframe interativo com as setas de fluxo foi desenvolvido no **Miro** e entregue diretamente na plataforma do Centro Universitário UNA.

---

## 📄 Licença

Este projeto é de uso acadêmico, desenvolvido exclusivamente para fins educacionais na disciplina de IHC & UX.
