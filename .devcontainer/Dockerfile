# Goの公式イメージを使用
FROM golang:1.21-buster

# コンテナ内での作業ディレクトリを設定
WORKDIR /workspace

# goplsやdlv (Delve) などGo開発用ツールをインストール
RUN go install golang.org/x/tools/gopls@latest && \
    go install github.com/go-delve/delve/cmd/dlv@latest
