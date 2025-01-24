# Desafio Ransoware - Encryption Project 🛡️

Este projeto demonstra como usar Python para criptografar e descriptografar arquivos de forma educativa. Ele utiliza a biblioteca `cryptography` para ilustrar conceitos básicos de segurança de dados e criptografia simétrica.

## 📁 Estrutura do Projeto
- **`encrypter.py`**: Criptografa um arquivo usando uma chave gerada aleatoriamente e sobrescreve o arquivo original.
- **`decrypter.py`**: Descriptografa o arquivo criptografado utilizando a chave previamente salva.
- **`test.txt`**: Arquivo de exemplo usado para testar a funcionalidade de criptografia/descriptografia.

## ⚙️ Como Usar

### 1. Pré-requisitos
- **Sistema operacional:** Kali Linux em uma máquina virtual (VirtualBox).
- **Python:** Python 3.6 ou superior.
- **Bibliotecas:** Instale a biblioteca necessária:
  ```bash
  pip install cryptography
  ```

### 2. Passo a Passo

1. **Prepare o ambiente:**
   - Certifique-se de que o Kali Linux está configurado em uma VM usando o VirtualBox.
   - Abra o terminal dentro da VM Kali Linux.

2. **Prepare o arquivo a ser criptografado:**
   - Crie um arquivo chamado `test.txt` na mesma pasta com qualquer conteúdo de sua escolha.
     Exemplo de conteúdo:
     ```
     Este é um arquivo de teste para criptografia e descriptografia.
     ```

3. **Execute o encrypter:**
   ```bash
   python encrypter.py
   ```
   - Criptografa o arquivo `test.txt`.

4. **Verifique o arquivo criptografado:**
   - O conteúdo de `test.txt` estará ilegível após a criptografia.

5. **Execute o decrypter:**
   ```bash
   python decrypter.py
   ```
   - Descriptografa o arquivo `test.txt`, restaurando o conteúdo original.

## ⚠️ Avisos
- Este projeto é apenas para fins educativos. Use-o com responsabilidade.
