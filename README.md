# 📌 Projeto: Calculator de IMC para Academia “Vida Saudável”
Você foi contratado pela academia “Vida Saudável” para desenvolver um programa simples que calcule o IMC dos alunos e mantenha um pequeno registro de seus resultados ao longo do tempo.

## ✏️ O que o programa deve fazer
Permitir que o aluno insira:
- Nome  
- Altura (em metros)  
- Peso (em quilos)  

Calcular o IMC usando a fórmula:
IMC = peso / (altura × altura)

markdown
Copiar código

Exibir:
- O valor do IMC calculado  
- Uma mensagem com a classificação (ex: “Abaixo do peso”, “Peso normal”, “Sobrepeso”, “Obesidade”)  

Permitir que o aluno adicione registros novos (peso / altura em datas diferentes) para acompanhar mudanças.

Mostrar um histórico simples com cada registro, listando:
- Data  
- Peso  
- Altura  
- IMC  
- Classificação  

## 📦 Entregáveis
1. Código-fonte do programa  
2. Instruções de uso  
3. Exemplos de execução: teste com 2 ou 3 registros  
4. (Opcional) Interface simples, como menu de texto  

## 🛠 Instruções de uso sugeridas
1. Clone ou baixe este repositório  
2. Acesse a pasta do projeto  
3. Execute o programa (por exemplo, `python imc.py`)  
4. Insira o nome, altura e peso quando solicitado  
5. O programa calculará e exibirá o IMC + classificação  
6. Se quiser, adicione outro registro com data nova  
7. Exiba o histórico para ver a evolução  

## 📊 Exemplo de execução
Bem-vindo ao Programa de IMC!
Digite seu nome: Rafael
Digite sua altura (em metros): 1.80
Digite seu peso (em kg): 75

Rafael, seu IMC é 23.15
Classificação: Peso normal

Deseja inserir novo registro? (s/n): s
Digite sua altura (em metros): 1.80
Digite seu peso (em kg): 78

Histórico de registros:
Data | Altura | Peso | IMC | Classificação
2025-10-14 | 1.80 | 75 | 23.15 | Peso normal
2025-10-20 | 1.80 | 78 | 24.07 | Peso normal

shell
Copiar código

## 📁 Estrutura de arquivos sugerida
/
├── README.md
├── imc.py (ou Imc.java, Main.cs etc.)
├── historico.txt (ou arquivo para salvar registros)
└── requirements.txt (caso haja dependências externas)

markdown
Copiar código

## ✅ Possíveis melhorias futuras
- Exportar histórico para CSV ou PDF  
- Criar interface gráfica simples (Tkinter, JavaFX etc.)  
- Adicionar gráficos para mostrar evolução do IMC  
- Enviar alertas ou notificações quando o aluno atingir metas  
- Validação mais robusta de entradas (altura = 0 ou peso negativo)  
- Permitir múltiplos usuários com login
