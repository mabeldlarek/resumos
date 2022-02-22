# Métodos Java
## Definição
* São disponibilizados por uma classe.
* Executados quando solicitados.
* Definem e realizam um comportamento.

---

## Criação
Possuem os seguintes elementos:

`visibilidade (obrigatório) - tipo - modificador (obrigatório) - retorno (obrigatório) - nome (obrigatório)  - parâmetros - exceções - corpo`

Que podem ser compreendidos pelas suas iniciais como:

`v`: public, protected ou private (adequada ao contexto)
`t`: concreto ou abstrato
`m`: static ou final
`r`: tipo de retorno ou void
`n`: nome do método (curtos e descritivos)
`p`: parametros que pode receber (breves)
`e`: exceções que pode lançar
`c`: código que possui ou vazio

---

## Particularidades
**Assinatura**
Forma exclusiva de identificação.
    `ASS = nome + parâmetros`

**Construtor e destrutor**: 
Respectivamente criação e destruição do objeto.

**Mensagem**:
Ato de solicitar a execução do método.

**Passagem de parâmetros**:

* Por valor (cópia)
* Por referência (endereço)

---

## Sobrecarga
Ocorre quando métodos com o mesmo nome são usado em contextos diferentes, sendo diferenciados pelos seus parâmetros.

---

## Retornos
* Funciona como uma instrução de interrupção. Simbologia: `return`

* Ocorrem a partir de instruções internas completas, declaração explicita e no lançamento de uma exceção.
* O tipo de retorno é definido na criação do método.
* Um método sem retorno pode ou não ter um return.