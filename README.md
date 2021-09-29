# Mini-tutorial de configuração

## Clonagem do repositório

- Dentro do diretório que quiserem clonar o repositório, execute o seguinte comando:

``` git
git clone https://github.com/ph-cardoso/ctd_front_end_1_checkpoint_3.git
```

Obs:

- Certifique-se de estar dentro da pasta correta que deseja clonar;

Com o repositório clonado na sua máquina, você já pode rodar os comandos `push` e `pull` para atualizar o repositório remoto. Não dê `push` diretamente na brach **main**

## Criação de uma nova branch

- Para facilitar a gestão do projeto, cada desenvolvedor deve trabalhar em uma branch própria e realizar commits e pushs nessa branch

- Para criar uma nova branch, execute o seguinte comando dentro do repositório:

``` git
git checkout -b NOME_BRANCH
```

Obs:

- Em "NOME_BRANCH" substitua pelo nome que você quer dar para a branch;

- Após a execução do comando você já vai estar trabalhando na branch recém criada. Para se certificar sobre qual branch está selecionada no momento, utilize o comando:

``` git
git branch
```

- Esse comando lista todas as branchs criadas no repositório. A selecionada vai estar **destacada**. Caso esteja utilizando o Vscode, também é possível visualizar a branch selecionada no canto esquerdo da barra inferior.

## Alternar entre branchs

- Para alternar entre branchs e selecionar uma diferente, utilize o comando:

``` git
git checkout NOME_BRANCH
```

- Substitua "NOME_BRANCH" pelo nome da branch que deseja selecionar.

## Observações

- Novamente, **não dê push na branch `main`**.

- Faça commits constantes a cada avanço, pois, se der algum problema lá na frente fica tranquilo voltar ao ponto que estava funcionando adequadamente.
