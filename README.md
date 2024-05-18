## book-recommend

> [!TIP]
>
> 基于深度学习的优质文学类图书推荐系统文档

## 一、功能

- [x] markdown 拓展支持
- [x] 引入 giscus 实现评论功能
- [x] PicGO + OSS 实现图片上传
- [x] 通过 github workflow 自行搭建部署
- [ ] 提供 Docker Image 容器化部署
- [ ] 通过 electron 打包分发

## 二、安装

### 2.1 环境安装

> [!CAUTION]
>
> - 运行环境：本项目使用最新的 [node](https://nodejs.org/en/download) 版本 `20.13.0` (vite press 官方要求 node
    版本需要 18+) 其它版本请自行测试
> - 包管理工具：使用 `yarn` 进行管理 如果未安装使用 ` npm install --global yarn`

![image-20240516130103516](https://2024-cbq-1311841992.cos.ap-beijing.myqcloud.com/picgo/image-20240516130103516.png)

1. `git clone https://github.com/cbq-2024/book-recommend.git  --depth=1 && cd book-recommend`

2. `yarn install`

3. `yarn run docs:dev`

![image-20240518000403670](https://2024-cbq-1311841992.cos.ap-beijing.myqcloud.com/picgo/202405180004883.png)

![image-20240518000409563](https://2024-cbq-1311841992.cos.ap-beijing.myqcloud.com/picgo/202405180004843.png)

### 2.2 开发工具

| 工具       | 版本       | 描述              |
|----------|----------|-----------------|
| WebStorm | 2024.1.2 | 前端开发工具          |
| Node     | 20.13.0  | JavaScript 运行环境 |
| yarn     | 1.22.22  | 包管理工具           |

