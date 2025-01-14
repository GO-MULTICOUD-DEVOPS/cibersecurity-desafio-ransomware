# 🛡️ Projeto: Criação de um Ransomware com Python

## 📚 Descrição
Este repositório apresenta um projeto de **Criação de um Ransomware com Python** desenvolvido como parte do Bootcamp de Cibersegurança da [DIO](https://dio.me), em parceria com o **Santander Brasil**. 

O projeto tem como objetivo educacional demonstrar o funcionamento básico de um ransomware, desde a criptografia de arquivos até a sua descriptografia, utilizando a biblioteca `pyaes` para operações de criptografia AES (Advanced Encryption Standard). 

⚠️ **Nota Importante:** Este projeto foi desenvolvido exclusivamente para fins educacionais e demonstração. O uso de ransomware ou quaisquer técnicas maliciosas contra sistemas sem autorização explícita é ilegal e antiético.

---

## 🚀 Funcionalidades

1. **Criptografia de Arquivos**: 
   - O script `encrypter.py` lê o conteúdo de um arquivo, o criptografa e salva uma versão criptografada com extensão `.ransomwaretroll`.
   - O arquivo original é removido do sistema.

2. **Descriptografia de Arquivos**: 
   - O script `decrypter.py` reverte a criptografia aplicada ao arquivo, recriando o arquivo original.

---

## 💂️‍🔧 Estrutura do Projeto

```plaintext
├── encrypter.py        # Script para criptografar arquivos.
├── decrypter.py        # Script para descriptografar arquivos.
├── teste.txt           # Arquivo de exemplo para criptografia.
└── README.md           # Documentação do projeto.
```

---

## 🛠️ Tecnologias Utilizadas

- **Python 3.9+**
- **Biblioteca `pyaes`**: Utilizada para implementar a criptografia AES.

---

## 🧑‍💻 Como Executar

### Pré-requisitos
- Python instalado na máquina (recomenda-se versão 3.9 ou superior).
- Biblioteca `pyaes` instalada:
  ```bash
  pip install pyaes
  ```

### Passo a Passo

1. Clone este repositório:
   ```bash
   git clone https://github.com/GO-MULTICOUD-DEVOPS/cibersecurity-desafio-ransomware.git
   cd cibersecurity-desafio-ransomware
   ```

2. Certifique-se de que o arquivo `teste.txt` está na mesma pasta dos scripts.

3. **Criptografar o arquivo**:
   - Execute o script `encrypter.py`:
     ```bash
     python encrypter.py
     ```
   - Resultado: o arquivo `teste.txt` será removido e uma versão criptografada (`teste.txt.ransomwaretroll`) será criada.

4. **Descriptografar o arquivo**:
   - Execute o script `decrypter.py`:
     ```bash
     python decrypter.py
     ```
   - Resultado: o arquivo original (`teste.txt`) será restaurado.

---

## 🖍️ Conteúdo do Arquivo `teste.txt`

O arquivo de exemplo contém a seguinte mensagem:

```
FINALIZANDO BOOTCAMP DE CIBERSEGURANÇA NA DIO COM PARCERIA DO SANTANDER BRASIL, OBTENDO EXCELENTE DESEMPENHO E APRENDIZAGEM.
```

---

## 📌 Pontos de Atenção

- A chave de criptografia usada nos scripts (`testeransomwares`) deve ser mantida em segredo para garantir segurança em aplicações reais.
- Sempre execute scripts como estes em ambientes de teste controlados.

---

## 🤝 Agradecimentos

Este projeto é resultado de uma experiência de aprendizado transformadora proporcionada pelo **Bootcamp de Cibersegurança da DIO** em parceria com o **Santander Brasil**. Meu sincero agradecimento a:

- **Professor Cassiano Peres**: Por sua didática clara e inspiradora, que tornou este aprendizado ainda mais enriquecedor.
- **DIO**: Por oferecer uma oportunidade educacional tão rica e prática.
- **Santander Brasil**: Pela visão de futuro ao investir na capacitação tecnológica.

---

## 📧 Contato

Se você tiver dúvidas, sugestões ou quiser trocar ideias, fique à vontade para entrar em contato:

- **LinkedIn**: [Seu Nome](https://linkedin.com/in/seu-perfil)
- **E-mail**: seu-email@dominio.com

**Vamos construir juntos um mundo digital mais seguro!**
