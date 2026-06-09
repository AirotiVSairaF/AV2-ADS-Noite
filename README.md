# AV2-ADS-Noite

# Libft em Python

Este projeto traz a reimplementação manual de diversas funções clássicas da biblioteca padrão do C (`libc`) e outras utilidades adicionais, utilizando **Python**.

O objetivo principal é puramente didático: entender a lógica de baixo nível, a manipulação de strings e o gerenciamento de buffers "por baixo dos panos", sem depender de métodos nativos do Python (como `.split()`, `.strip()` ou `len()`).

## O que o código faz:
* **Funções da Libc:** Reimplementações de checagem de caracteres (`isalpha`, `isdigit`), manipulação de memória (`memset`, `memcpy`) e strings (`strlen`, `strncmp`).
* **Funções Adicionais:** Manipulação customizada de texto como `split`, `strjoin`, `strtrim` e `itoa`.
* **Saída de Dados:** Escrita direta no sistema operacional simulando File Descriptors (`os.write`).

## 🚀 Como testar:
Basta abrir o arquivo `.ipynb` diretamente no **Google Colab** pelo botão no topo do notebook ou rodar o script localmente com Python 3.
