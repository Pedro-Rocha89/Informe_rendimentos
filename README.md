# Gerador de Informe de Rendimentos no Excel


## 🧾 Descrição do Projeto  
O projeto consiste na criação de uma planilha de controle de dados para facilitar a organização de informações necessárias para a declaração de imposto de renda. A ferramenta será desenvolvida no Excel, utilizando validações de dados, navegação facilitada e funções interativas. 


## 📑 Etapas

- `Criação da aba TITULAR`:  
Nesta etapa foi criada a planilha onde o usuário insere os **dados declarante titular** (nome, CPF, etc.).

![image](https://github.com/user-attachments/assets/b0a85762-357c-4708-a0df-3894fc2d36ac)


- `Construção da aba INFORMES`:  
Esta é a aba principal do documento. Nela são listados os informes de rendimentos de cada instituição financeira. Para cada informe, são preenchidos:

  - Nome da fonte pagadora
  - Valor do rendimento
  - Anexo do documento

![image](https://github.com/user-attachments/assets/8f9986e7-faa3-4360-85fd-c8b733b273a4)


- `Criação da aba NOTAS`:  
A aba **NOTAS** especificar e periodizar as entradas de valores. Ela pode ser usada para esclarecer:
  - Data do recebimento
  - Categoria do recebimento (contracheque, recibo, etc.)
  - Valor do recebimento

![image](https://github.com/user-attachments/assets/2cac0d0c-05f9-45ed-ba56-f28db9a7dbe4)


## 🖩 Fórmulas/Funções Utilizadas

- `Validação de Dados`:  
Foi aplicada para restringir as opções em campos específicos, garantindo que os usuários selecionem apenas valores válidos em listas pré-definidas. Isso evita erros de digitação e padroniza as respostas — especialmente útil em campos como bancos e campos com resposta 'SIM' e 'NÃO'.

- `Link (Hiperlink interno)`:  
Algumas células foram configuradas com links que direcionam o usuário rapidamente para outras partes da planilha, facilitando a navegação entre as abas ou seções do documento.

- `Preenchimento com Gradiente`:  
Utilizado para aplicar efeitos visuais nos títulos e seções principais da planilha, ajudando na organização visual e deixando o documento mais apresentável e profissional.

- `Formatação Personalizada de Células`:  
Foram aplicados formatos específicos para:
  - **CPF** (`000\.000\.000\-00`)  
  - **Celular** (`(00) 00000\-0000`)  
  - **Telefone Fixo** (`(00) 0000\-0000`)
  - **CEP** (formatação especial já incorporada nativamente) 
  Isso garante que os dados inseridos sigam o padrão oficial brasileiro, sem necessidade de ajustes manuais.

- `Proteção de Planilha`:  
A planilha foi protegida para impedir alterações indesejadas nas fórmulas e células críticas. Apenas as áreas de entrada foram deixadas desbloqueadas para edição, garantindo a integridade do documento.

- `Gráfico 3D`:  
Na aba **INFORMES**, foi adicionado um **gráfico de pizza 3D** que representa visualmente os valores dos rendimentos por fonte pagadora. Esse recurso auxilia na análise rápida e comparativa entre os valores recebidos ao longo do ano.

![image](https://github.com/user-attachments/assets/07974a9e-dff4-48c0-9546-3700a7865b07)


## 🧰 Ferramentas e Aplicativos Utilizados

- ``Excel``  
- ``ChatGPT`` 

## 👨‍💻 Desenvolvedores

[<img loading="lazy" src="https://avatars.githubusercontent.com/u/201495780?s=96&v=4" width=115><br><sub>Pedro Rocha</sub>](https://github.com/Pedro-Rocha89)

[<img loading="lazy" src="https://avatars.githubusercontent.com/u/37452836?v=4" width=115><br><sub>Felipe Aguiar</sub>](https://github.com/felipeAguiarCode)

