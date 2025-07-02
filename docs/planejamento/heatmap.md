# Heatmap de Disponibilidade

## Introdução

Este documento descreve a ferramenta utilizada para gerar o heatmap de disponibilidade dos integrantes do Grupo08 na disciplina de Requisitos de Software. O objetivo do heatmap é visualizar a sobreposição de horários livres dos membros para facilitar o agendamento de reuniões e atividades em grupo.

## Ferramenta utilizada

|                       Imagem                        |                Ferramenta                | Finalidade                                                                                                          |
| :-------------------------------------------------: | :--------------------------------------: | ------------------------------------------------------------------------------------------------------------------- |
| <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/3/34/Microsoft_Office_Excel_%282019%E2%80%93present%29.svg/1200px-Microsoft_Office_Excel_%282019%E2%80%93present%29.svg.png" alt="Excel" style="height:100px;width=75px"> | <a id="a" href="#aa">Microsoft Excel</a> | Utilizado para coletar, compilar e visualizar os dados de disponibilidade dos membros do grupo em forma de heatmap. |

<div align="center">
<p>Figura 1: Heatmap gerado com base nas disponibilidades semanais dos integrantes do grupo.</p>

<img src="" alt="Grade Horária Grupo08" width="750px">

</div>

<font size="3"><p style="text-align: center">Elaborado pelo autor: ([João Marcos Moraes](https://github.com/JJOAOMARCOSS), 2025).</p></font>

## Como foi feito o Heatmap

1. **Coleta de dados:** Cada membro do grupo preencheu sua disponibilidade horária durante a semana, indicando se estava **"ocupado"** ou **"livre"** para cada bloco de uma hora.

2. **Montagem da tabela:** As respostas foram organizadas em uma tabela no Excel, separando os dias da semana e os horários. A cada horário marcado como "livre", era atribuída uma pontuação de 1; para "ocupado", 0. A soma dessas pontuações permitiu identificar os horários com maior sobreposição de disponibilidade entre os membros.

3. **Aplicação da escala de cor:** Foi aplicada uma formatação condicional do tipo **Escala de Cor (Color Scale)** no Excel, variando do vermelho (menos disponibilidade) até o verde (mais disponibilidade), facilitando a visualização das melhores faixas de horário.

4. **Exportação:** A tabela foi exportada como imagem para ser utilizada em documentos e apresentações do projeto.

## Bibliografia

> <a id="aa" href="#a">[1]</a> MICROSOFT. Microsoft Excel. Disponível em: [https://www.microsoft.com/pt-br/microsoft-365/excel](https://www.microsoft.com/pt-br/microsoft-365/excel). Acesso em: 11 de Abril de 2025.

## Histórico de Versão

| Versão |             Descrição             |           Autor(es)           |    Data    |    Revisor(es)     | Data de Revisão |
| :----: | :-------------------------------: | :---------------------------: | :--------: | :----------------: | :-------------: |
| 1.0  | Criação do heatmap e documentação | [João Marcos Moraes](https://github.com/JJOAOMARCOSS) | 11/04/2025 | [Luiza da Silva](https://github.com/Luizaxx) |   12/04/2025    |
| 1.1    |  Padronizando histórico de versões               |  [Lucas Mendonça ](https://github.com/lucasarruda9)  | 13/04/2025 | [Artur Mendonça](https://github.com/ArtyMend07)   | 13/04/2025      |
| 2.0    |  Arrumando a img que quebrou  |  [João Marcos Moraes](https://github.com/JJOAOMARCOSS) | 01/07/2025 | [Luiza da Silva](https://github.com/Luizaxx) |   01/07/2025    |