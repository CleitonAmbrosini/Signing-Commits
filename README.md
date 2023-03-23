# Signing commits
Assinar commits é uma prática importante em projetos de desenvolvimento de software para garantir a autenticidade e integridade das alterações feitas no código-fonte.

Com a assinatura de commits, é possível garantir que as alterações feitas no código são autênticas e que ninguém as alterou maliciosamente após a sua criação.

A assinatura dos commits pode ser feita usando GPG, SSH, ou S/MIME.

Para mais informações de como configurar cada uma delas basta acessar a documentação do GitHub sobre o assunto [clicando aqui](https://docs.github.com/pt/authentication/managing-commit-signature-verification/signing-commits).

O objetivo deste repositório é exemplificar um commit assinado.

## Como saber se o commit foi assinado?
Para saber se um commit foi assinado, basta clonar o projeto ir até o diretório do mesmo e digitar o seguinte comando.
```bash
git log --show-signature
```
Esse comando mostrará uma lista de todos os commits do repositório, juntamente com informações sobre se eles foram ou não assinados.

Outra maneira de verificar se o commit foi assinado é indo até a página de commits do repositório e verificar se o commit em questão possui a tag "Verifed"
<div align="center">
  <img src="./Signing commits.png">
  <hr>
</div>