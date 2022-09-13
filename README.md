<p><a href="https://docs.koderover.com" target="_blank" rel="noopener noreferrer"><img height="50" src="https://docs.koderover.com/zadig/img/zadig.png" alt="Zadig logo"></a></p>


欢迎来到 [Zadig](https://github.com/koderover/zadig) 自定义任务仓库。

Zadig 于 v1.13.0 版本中推出了自定义工作流并支持自定义任务，满足复杂场景下任务顺序自由编排能力，诸如审核、多任务组装；提供更强的开放性和系统扩展性，可广泛链接合作伙伴和企业内部系统。

## 目录说明

```
zadig-jobs
├── good-first-jobs     # 待实现任务的场景描述
├── hello-world         # 已实现的自定义任务 demo，打印 hello world
└── update-nacos-config # 已实现的自定义任务 demo，实现 Nacos 配置变更
```

## 如何贡献

社区小伙伴可以从 [good-first-jobs](https://github.com/koderover/zadig-jobs/tree/main/good-first-jobs) 中选取场景实现，也可以实现自己的场景，参照以下目录格式提交代码：

```
zadig-jobs
└── update-nacos-config              # 自定义任务目录
    ├── README.md                    # 自定义任务说明
    └── v0.0.1                       # 自定义任务版本目录
        ├── Dockerfile               # 镜像编译文件
        ├── Makefile                 # 工程编译文件
        ├── main.go                  # 自定义任务源码实现
        └── update-nacos-config.yaml # 自定义任务配置文件
```

## 联系我们

在贡献时遇到任何问题，都可以添加官方公众号联系我们获取帮助</br>。
![KodeRover 官方公众号](./wechat-platform.jpg)
