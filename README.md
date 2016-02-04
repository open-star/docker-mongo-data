# docker-mongo-data
MongoDB Data Only Container

## DockerfileからのDockerイメージの作成方法
自分のマシンでDockerfileからのDockerイメージの作成する方法について説明します。 
Dockerfileの存在するディレクトリに移動して下さい。 i
次に、docker build コマンドを実行して下さい。

### MongoDB のデータ専用コンテナイメージの作成
	$ docker build -t my-mongo-data .
