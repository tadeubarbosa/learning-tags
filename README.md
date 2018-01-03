# estudando tags do git

## exibindo tags

**git tag:** exibe todas as tags.

**git ls-remote --tags `origin`:** exibindo tags remotas.

##  criando tags locais e remotas

**git tag -am "criando tag v1.0 lorem ipsum" v1.0:** criando tag v1.0.

**git push `origin` v1.0:** enviando/criando tag v1.0 em `origin.

## abrindo tag

**git checkout v1.0:** faz checkout para a tag.

## enviando tag para remoto

**git push --tags:** envia todas as tags.

**git push `origin` v1.0:** envia uma tag para o remoto `origin´.

## deletando tags

**git tag :v1.0:** deleta uma tag local.

**git push `origin`  :v1.0:** deleta uma tag remota.

