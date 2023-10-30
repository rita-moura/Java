## Para instalar a OpenJDK 17 no Ubuntu e derivados.

- Comece atualizando os pacotes com o seguinte comando:

```shell
sudo apt update
```

- Depois faça a instalação do OpenJDK 17 com o comando a seguir:

```shell
sudo apt install openjdk-17-jdk
```

- Em caso tenha outras versões do java instaladas defina a OpenJDK 17 como padrão com o seguinte comando:

```shell
sudo update-java-alternatives --set java-1.17.0-openjdk-amd64
```

- Use o comando a baixo para verificar se tem outras versões instaladas:

```shell
sudo update-java-alternatives --list
```

- O proximo comando é para verificar a versão atual:

```shell
java -version
```