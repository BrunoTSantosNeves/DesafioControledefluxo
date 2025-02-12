# Contador de Números em Java

## 📌 Descrição do Projeto
Este projeto consiste em um **contador de números** desenvolvido em **Java**. O programa solicita dois números inteiros do usuário e imprime uma contagem baseada nesses valores. Caso o segundo número seja menor que o primeiro, uma exceção personalizada é lançada para indicar o erro ao usuário.

O projeto segue boas práticas de programação, incluindo o uso de **exceções personalizadas** para controle de erros.

---

## 🚀 Funcionalidades
- Solicita dois números inteiros ao usuário.
- Valida se o segundo número é maior que o primeiro.
- Imprime uma contagem de 1 até a diferença entre os dois valores.
- Caso o segundo número seja menor que o primeiro, exibe uma mensagem de erro.

---

## 🛠️ Tecnologias Utilizadas
- **Java 17+**
- **Scanner** para entrada de dados do usuário
- **Tratamento de Exceções** para lidar com erros de entrada

---

## 📂 Estrutura do Projeto

```
ContadorNumeros
├── src
│   ├── 
│   │  ├── java
│   │  │   ├── Contador.java  # Classe principal com a lógica de contagem
│   │  │   ├── ParametrosInvalidosException.java  # Exceção personalizada
├── README.md  # Documentação do projeto
```

---

## 🔒 Tratamento de Erros
O programa inclui uma **exceção personalizada** chamada `ParametrosInvalidosException`, que é lançada quando o primeiro número é maior que o segundo. Isso evita execuções inválidas e melhora a usabilidade do sistema.

**Exemplo de erro:**
```
Digite o primeiro parâmetro
10
Digite o segundo parâmetro
5
O segundo parâmetro deve ser maior que o primeiro
```

---

## 📈 Exemplo de Execução

### Entrada:
```
Digite o primeiro parâmetro
2
Digite o segundo parâmetro
6
```

### Saída:
```
Imprimindo o número 1
Imprimindo o número 2
Imprimindo o número 3
Imprimindo o número 4
```

---

## 🔄 Como Executar
1. **Compilar o programa:**
```bash
javac Contador.java
```

2. **Executar o programa:**
```bash
java Contador
```

---

## 🚀 Possíveis Melhorias
- Implementar interface gráfica (GUI) para entrada de dados.
- Permitir a contagem em ordem decrescente caso o primeiro parâmetro seja maior.
- Adicionar suporte para entrada de números negativos.

---

## 📚 Licença
Este projeto está sob a licença **MIT**. Você pode utilizá-lo e modificá-lo conforme necessário.

---

Caso precise de ajustes ou adicione novas funcionalidades, sinta-se à vontade para modificar a documentação! ✨

