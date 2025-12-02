# dados-atletas
# Projeto: Notas dos Atletas

- Receber informações de diversos atletas;
- Calcular a categoria de acordo com a idade;
- Calcular IMC;
- Calcular a média válida das notas (ignorando a maior e a menor);
- Exibir todas as informações ao usuário.

---

## Funcionalidades

A classe `Atleta` possui os atributos:

- `nome`
- `idade`
- `peso`
- `altura`
- `notas` (array com 5 notas)

E os métodos:

- `calculaCategoria()`
- `calculaIMC()`
- `calculaMediaValida()`
- `obtemNomeAtleta()`
- `obtemIdadeAtleta()`
- `obtemPesoAtleta()`
- `obtemNotasAtleta()`
- `obtemCategoria()`
- `obtemIMC()`
- `obtemMediaValida()`

---

##  Regras utilizadas

### Categoria por idade
| Idade | Categoria |
|------|-----------|
| 9–11 | Infantil |
| 12–13 | Juvenil |
| 14–15 | Intermediário |
| 16–30 | Adulto |
| Outros | Sem categoria |

### Cálculo IMC

### Média válida
Usa apenas **as 3 notas do meio**, descartando:

- a **maior** nota
- a **menor** nota




