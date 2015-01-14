# Gerador e validador de CPFs

Veja o [demo](http://tiagoporto.github.io/gerador-validador-cpf/).

Esta ferramenta foi desenvolvida para auxiliar desenvolvedores em testes de software, e não tem qualquer vínculo com a Receita Federal do Brasil.

A ferramenta utiliza o seguinte [algoritmo](http://www.geradorcpf.com/algoritmo_do_cpf.htm) para verificação e geração do CPF.

Um CPF declarado como válido por essa ferramenta não significa que ele exista no Cadastro Nacional de Pessoas Físicas nem que seja um número ativo ou com situação cadastral regular. Para conferir tais dados, consulte o site oficial da [Secretaria da Receita Federal do Brasil](http://www.receita.fazenda.gov.br/aplicacoes/atcta/cpf/consultapublica.asp).

O número CPF guarda o estado de onde foi emitido, esse número corresponde ao último algarismo anterior aos dois dígitos verificadores.

Um exemplo de CPF nº 000.000.008-00, o número 8 corresponde ao estado de São Paulo.

Veja abaixo os códigos correspondentes aos estados brasileiros:

```text
1 - Distrito Federal, Goiás, Mato Grosso do Sul e Tocantins;

2 - Pará, Amazonas, Acre, Amapá, Rondônia e Roraima;

3 - Ceará, Maranhão e Piauí;

4 - Pernambuco, Rio Grande do Norte, Paraíba e Alagoas;

5 - Bahia e Sergipe;

6 - Minas Gerais;

7 - Rio de Janeiro e Espírito Santo;

8 - São Paulo;

9 - Paraná e Santa Catarina;

0 - Rio Grande do Sul.
```

## Funcionalidades

* Gerar CPFs válidos

* Validar CPFs

## Uso

Faça o download de uma das versões:

* [Não Compactada](https://raw.githubusercontent.com/tiagoporto/gerador-validador-cpf/gh-pages/PROJECT/public/js/CPF-1.0.0.js)

* [Compactada](https://raw.githubusercontent.com/tiagoporto/gerador-validador-cpf/gh-pages/PROJECT/public/js/CPF-1.0.0.min.js)


## License

Project Name is released under the terms of the [MIT license](http://opensource.org/licenses/MIT).
