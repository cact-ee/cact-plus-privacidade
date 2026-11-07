---
lang: pt-BR
---

# CACT+ — Política de privacidade

Vale a partir da versão 0.2.0 da extensão.

O CACT+ é uma extensão do Google Chrome publicada pela Cact Estratégia Empresarial. Ela baixa notas fiscais de
serviço eletrônicas (NFS-e) do Padrão Nacional e grava os arquivos no computador de quem a usa.

## O que a extensão acessa

- **O Ambiente de Dados Nacional da NFS-e** (`adn.nfse.gov.br`), da Receita Federal, para baixar as notas e os eventos
  do CNPJ que o usuário digita. É o único servidor com que a extensão se comunica.
- **O certificado digital instalado no navegador**, apenas por meio do próprio Chrome, que o apresenta ao ADN quando o
  usuário confirma. A extensão não lê o certificado, a chave privada nem a senha.
- **A pasta que o usuário escolhe**, para gravar os XML, os DANFSe e o livro fiscal, e para ler de volta as notas do
  mês ao montar o livro.

## O que fica guardado, e onde

No próprio navegador, no armazenamento da extensão:

- cada CNPJ já baixado, com o nome do contribuinte tirado da nota, o último NSU e a data da última sincronização;
- as preferências da tela;
- a referência à pasta escolhida.

Os arquivos baixados ficam na pasta escolhida, no computador do usuário. Desinstalar a extensão apaga o que está no
armazenamento dela; os arquivos da pasta continuam.

## O que não acontece

- Nenhum dado é enviado ao desenvolvedor ou a terceiros: não há servidor próprio, cadastro, analytics nem telemetria.
- O nome da empresa sai do XML da nota; não há consulta de CNPJ a nenhum serviço.
- Nenhum dado é vendido, compartilhado ou usado para outra finalidade.

## Contato

Dúvidas sobre a extensão ou sobre esta política: [ti@cact.com.br](mailto:ti@cact.com.br).
