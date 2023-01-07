# ## Desenvolvimento com Java 17 - IDE - NetBeans

### Objetivo

#### 🌱 O objetivo geral foi desenvolver e cumprir os requisitos estabelecidos.

#### 📫 REQUISITOS:

#### ⚡ 
####  LISTA DE REQUISITOS A SEREM SEGUIDOS:

I) No diagrama há sinais que indicam se os membros das classes são:
“ - ” privados ou “+” públicos;

II) Perceba que só há associações da classe TstConta com apenas 2 outras classes: PessoaJuridica e
NumException. Sendo assim, na classe TstConta, só haverá estes 2 tipos de objetos;

III) Métodos Construtores: excepcionalmente nesta prova não serão desenvolvidos os métodos
construtores. Desta forma, a instanciação de cada atributo será feita (obrigatoriamente) na mesma
linha de sua declaração e da seguinte maneira:

- Os de tipos numerais com zeros;
- Os de tipos literais com espaço em branco;
- E, quando forem objetos, instancie com o seu respectivo tipo;

VI) O diagrama de classes descreve as classes que deverá construir para resolução da prova;

V) Não utilizará interface gráfica nesta prova.

VI) As classes Endereco, PessoaFisica e PessoaJuridica NÃO poderão ser herdadas.

VII) A classe NumException, trata-se de uma classe de exceção do tipo verificada. Esta classe contém (apenas) o
método chamado impMsg() que, ao ser chamado, imprimirá a mensagem: “ERRO: Não pode haver Número
Negativo para conta!”. O método impMsg() será utilizado na classe TstConta.

VIII) Interface Verifica: contém um método chamado validar(), que não tem retorno e não recebe parâmetros. Quando
implementado deverá verificar o Número da Conta e imprimir na tela se este é par ou é ímpar;

#### ⚡ A classe ClienteBanco é abstrata e contém:

- Um método abstrato chamado “verifDoc” o qual verificará:

- Em PessoaFisica: se o valor informado para o atributo CPF está entre 10 e 20. Caso o valor esteja fora
desta escala, informará na tela a mensagem “CPF inválido”, se não, informará na tela a mensagem
“CPF válido”;

- Em PessoaJuridica: se a quantidade de letras do nome do “responsavel” é maior que 30, caso seja
deverá informar na tela a mensagem “Nome inválido para Responsável”, se não, informará na tela a
mensagem “Nome válido para Responsável”;

- O seu método setNumeroConta: se valor informado for positivo, atribuirá este valor ao atributo
numeroConta, se não, deverá disparar uma exceção do tipo NumException;

- Contém um atributo chamado ender, que define os dados cadastrais dos clientes do banco, seja esta pessoa
física ou jurídica;

- A classe PessoaJuridica contém um atributo denominado responsavel, este indica uma pessoa física da empresa
incumbida de gerenciar a conta.

#### Diagrama a ser implementado:

![image](https://user-images.githubusercontent.com/103886679/211152762-02a604e2-efe2-4756-82b4-4f3fc02fa0b5.png)


- ![NetBeans IDE](https://img.shields.io/badge/NetBeansIDE-1B6AC6.svg?style=for-the-badge&logo=apache-netbeans-ide&logoColor=white)

- ![Git](https://img.shields.io/badge/git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white)

- ![Java](https://img.shields.io/badge/java-%23ED8B00.svg?style=for-the-badge&logo=java&logoColor=white)
