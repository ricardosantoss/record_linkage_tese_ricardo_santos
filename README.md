# Extração de informações clínicas e vinculação de registros

Notebooks Jupyter/Google Colab destinados ao processamento de documentos clínicos obstétricos, extração de atributos de ultrassonografias e vinculação de registros.

## Estrutura

- `notebooks/extracao/`: extração de informações de ultrassonografias (normal, morfológica e Doppler), adendos e relatórios de alta.
- `notebooks/record_linkage/`: integração e vinculação de adendos, relatórios, ultrassonografias e registros de nascidos vivos (RNV).

## Execução

Os notebooks foram desenvolvidos originalmente em Google Colab e referenciam caminhos locais do Google Drive. Antes de executá-los, ajuste os caminhos de entrada e saída ao seu ambiente e instale as dependências usadas nas células. A ordem de execução e os esquemas dos dados dependem dos arquivos originais, não incluídos neste repositório.

## Privacidade e reprodutibilidade

- Os notebooks foram preparados **sem saídas de execução**, que poderiam conter informações clínicas sensíveis.
- Não envie prontuários, planilhas com identificadores pessoais, bases de pacientes, credenciais ou arquivos intermediários para repositórios públicos.
- **Atenção:** os códigos originais não foram anonimizados ou auditados integralmente; revise caminhos, exemplos e eventuais identificadores literais antes de publicação.
- A remoção de saídas não altera a lógica do código, mas este pacote não constitui validação de execução.

## Origem

Organização dos oito notebooks fornecidos no arquivo ZIP original. Os códigos foram preservados, exceto pela limpeza de saídas e contadores de execução.

## Revisão de privacidade
Consulte [REVISAO_PRIVACIDADE.md](REVISAO_PRIVACIDADE.md). Os caminhos originais do Drive foram substituídos por marcadores locais; os notebooks não foram testados com bases reais. **Não publique saídas de execução nem bases clínicas.**
