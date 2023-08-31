# Guidelines para novas implementações

## 🔱 Como ajudar

* Acesse as issues e verifique as demandas da comunidade  
* Participe dos fóruns de discussão e contribua com as análises e boas práticas para implementação  
* Crie uma WIKI com exemplos de utilização  
* Crie uma WIKI com casos de uso e casos de sucesso  

**6)** 

**Parabéns!** Você está pronto para realização do Pull Request!

## 🚀 Criação de novos Testes Unitários e Casos de Uso

Nós encorajamos ampliar a cobertura de testes. Casos específicos ou casos raros devem ser implementados, como: 
 - documentos com dígito verificador 0   
 - documentos cujo resto da soma = 10 ou resto = 11  
 - número de documentos com caracteres especiais 
 - documentos com tamanho variável, etc
 
 Para implementar novos testes basta inserir uma função na unit _testes.rs_ adicionando a macro `#[test]`
 Implemente tantas funções quanto necessário para cada caso de uso encontrado.

## 💡 Criação de novas funcionalidades

Novas funcionalidades que estejam muito além da capacidade de validar ou realizar parse seguro devem ser discutidas no 
[💬 Fórum de discussão](https://github.com/ricardodarocha/validador-br/discussions)

## 💛 Solicitar uma nova feature

Crie uma [➕ nova issue](https://github.com/ricardodarocha/validador-br/issues/new) com a solicitação. A comunidade irá avaliar a possibilidade de implementar. Importante dar o máximo de informações, 
adicionar links com a documentação técnica, exemplos e pelo menos uma dúzia de números de documento válidos para 
ser adicionado ao Teste

## ✅ Revisão de Código e Refatoração

Toda revisão de código ou refactoring é bem vinda, contando que os testes unitários não sofram alteração antes e após a refatoração
