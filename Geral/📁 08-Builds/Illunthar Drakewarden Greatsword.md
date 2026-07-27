---
tags: [build, drakewarden, ranger, dragonborn, illunthar]
aliases: [Build Illunthar - Drakewarden, Urban Bounty Hunter Drakewarden]
---

# 🐉 Build: Illunthar — Drakewarden (Urban Bounty Hunter)

> [!info] Ficha Base
> **Raça:** [[Dragonborn]] (Ascendência Metálica — Branco/Prata)
> **Classe:** [[Ranger]] 4 ([[Drakewarden]])
> **Companheiro:** [[Tico]]
> **Personagem de Campanha:** [[Illunthar]]

## 📊 Atributos

| STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|
| 20 (+5) | 15 (+2) | 17 (+3) | 10 (+0) | 14 (+2) | 11 (+0) |

**HP:** 40 (4d10) | **AC:** 17 (Scale Mail) | **Speed:** 9m | **Prof:** +2 | **Iniciativa:** +2

## ⚔️ Combos

### Combo 1 — Ataque Padrão Completo (GWM + Hunter's Mark + Favored Foe + Infused Strikes)

Setup: [[Hunter's Mark]] já conjurada no alvo (ação bônus, concentração) e **[[Tico]]** invocado e a até 9m.

**1 ataque de Greatsword com GWM:**
- Acerto: +2 (7 base - 5 do GWM)
- Dano: **2d6 (Greatsword) + 5 (STR) + 10 (GWM) + 1d6 (Hunter's Mark, todo acerto) + 1d4 (Favored Foe, só no 1º acerto do turno) + 1d6 (Infused Strikes do Tico, reação)**

**Total: 4d6 + 1d4 + 15**
*(exemplo de rolagem média: 4d6≈14 + 1d4≈2,5 + 15 = ~31,5 de dano em um único golpe)*

> [!tip] Se score um crítico nesse ataque
> GWM libera um **ataque bônus extra** com a Greatsword. Além disso, os dados "presos" ao acerto dobram:
> - Greatsword: 2d6 → **4d6**
> - Hunter's Mark: 1d6 → **2d6**
> - Favored Foe: 1d4 → **2d4**
> - Infused Strikes: permanece **1d6** (reação de outra criatura, não dobra)
>
> **Dano do golpe crítico: 4d6 + 2d6 + 1d6 (=7d6) + 2d4 + 15**

### Combo 2 — Turno Completo com Ataque Bônus do GWM

Se o Combo 1 critar (ou reduzir o alvo a 0 HP), você ganha um **ataque bônus extra** com a Greatsword no mesmo turno:
- Esse segundo golpe: **2d6 (Greatsword) + 5 (STR) + 10 (GWM) + 1d6 (Hunter's Mark, aplica de novo)**
- Favored Foe **não** se repete (só vale no 1º acerto do turno) e Infused Strikes já foi consumido (reação limitada a 1x por rodada)

**Segundo ataque: 3d6 + 15**

**Turno inteiro (1º ataque crítico + ataque bônus normal):**
7d6 + 2d4 + 15 (crítico) + 3d6 + 15 (bônus) = **10d6 + 2d4 + 30**

### Combo 3 — Sopro Dracônico (área, sem gastar recursos de ataque)

Substitui **um** ataque da ação de Atacar (não precisa gastar magia nem espaço):
- Cone de 4,5m, CD 13 Destreza
- Falha: **1d10** de dano de frio
- Sucesso: metade (arredondado para baixo) → **⌊1d10/2⌋**
- 2 usos por descanso longo

> [!tip] Bom contra grupos
> Diferente do Greatsword, o Sopro acerta todos os inimigos no cone de uma vez — vale mais a pena contra 2+ alvos do que contra um só.

### Combo 4 — Absorb Elements (defensivo → ofensivo)

Reação ao sofrer dano ácido/frio/fogo/raio/trovão:
- Resistência ao tipo de dano até o início do próximo turno (efetivamente **reduz pela metade** o dano recebido)
- No próximo ataque corpo a corpo que acertar: **+1d6** do mesmo tipo elemental absorvido

Combinado com o Combo 1 no turno seguinte:
**4d6 + 1d4 + 1d6 (Absorb Elements) + 15 = 5d6 + 1d4 + 15**

> [!tip] Ordem de Prioridade em Combate
> 1. Invocar [[Tico]] (se não estiver ativo) — ação.
> 2. Atacar com Greatsword usando GWM.
> 3. Marcar Favored Foe no primeiro acerto.
> 4. Deixar Tico posicionado a até 9m de qualquer aliado que ataque, para maximizar reações de Infused Strikes.

### Combo Secundário: Sopro + Absorb Elements
Se for atacado por dano ácido/frio/fogo/raio/trovão antes do seu turno, use **[[Absorb Elements]]** como reação para resistir e adicionar +1d6 do mesmo tipo no seu próximo ataque corpo a corpo — ótimo antes de entrar em uma sala com criaturas elementais.

## 🎒 Utilitários

- **[[Goodberry]]** — sustento e cura leve fora de combate (10 HP totais + comida por 1 dia cada).
- **[[Thaumaturgy]]** — intimidação, sinalização e pequenos truques ambientais (encaixa bem com a filosofia "chego anunciado" do personagem).
- **Speak with Animals** (Primal Awareness, grátis 1x/descanso longo) — investigação e rastreamento.
- **[[Hunter's Mark]]** — rastreamento com vantagem em Percepção/Sobrevivência, além do dano extra.

## 🛡️ Resistências e Defesas

| Fonte | Efeito |
|---|---|
| Ascendência Dracônica (Metálica — Frio) | Resistência a dano de **frio** |
| Scale Mail + Fighting Style Defense | AC 17 (16 base + 1) |
| [[Absorb Elements]] | Resistência situacional a ácido/frio/fogo/raio/trovão (1 rodada, via reação) |

## 🎯 Cálculos de Dano

### Ataque — Greatsword (sem GWM)
+7 para acertar → **2d6 + 5** (média 12) de dano cortante.

### Ataque — Greatsword (com GWM)
+2 para acertar → **2d6 + 15** (média 22) de dano cortante.
*Trade-off: -5 no acerto por +10 de dano garantido no hit — vale a pena contra AC baixa/média, ou quando já há vantagem no ataque.*

### Ataque — Sopro de Gelo (Breath Weapon)
Cone de 4,5m, CD 13 Destreza. **1d10** de dano de frio (falha) / **metade** (sucesso). 2 usos por descanso longo, sem gastar ação de ataque completa (substitui um ataque).

### Ataque — Tico (Mordida)
+5 para acertar → **1d6+2** perfurante + dano elemental do momento.

### Defesa
AC 17. Com [[Absorb Elements]] ativo: resistência ao tipo de dano que o desencadeou até o início do próximo turno.

## 📈 Notas de Progressão

- **[[Great Weapon Mastery]]** e **[[Favored Foe]]** já adquiridos como talentos/features.
- Próximo objetivo natural: subir para nível 5 (Extra Attack do Ranger) para dobrar a frequência de aplicação do combo GWM + Favored Foe.
- Considerar **Martial Versatility** apenas se houver necessidade de trocar Defense por outro estilo (ex: Great Weapon Fighting, para suavizar a variância do dado de dano do Greatsword).