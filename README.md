# INOVAMED · Certificados

Repositório público de proveniência criptográfica dos certificados emitidos pelos cursos AIMED.

## Arquitetura

- **`index.json`** — registro mestre de todas as edições
- **`editions/`** — JSON imutável de cada turma

## Princípio operacional

Arquivos neste repositório são **append-only**. Após a publicação de uma edição:

- Nomes podem ser corrigidos apenas em caso de erro de digitação documentado
- Hashes **nunca** são alterados — são contrato perpétuo com o aluno
- Edições passadas **nunca** são removidas

## Validação pública

Cada certificado emitido recebe um hash de 10 caracteres hexadecimais. Para validar, acesse:

**https://inovamed.pro/?page_id=2662**

## Responsável técnico

**Dr. Mbula Luzingu Barros** · CRM-SC 8512  
Coordenador AIMED · Fundador INOVAMED
