
# install manual
  https://github.com/kubernetes/minikube

# Windows

## Hyper-v

以下のコマンドを管理者モードで実行  
`switch-name`はHyper-Vで作成した外部接続ネットワーク名にしてください

```
minikube start --vm-driver=hyperv --hyperv-virtual-switch=<switch-name>
```

※メモリーエラーになった場合は、最大メモリーに到達している可能性があるので、  
　Hyper-Vの動的メモリーをオフにしてください

https://qiita.com/terukizm/items/bf8e4744fcb8ba494fc8

## kubectlの導入

```
choco install kubernetes-cli
```