# MHWA(苍雾世界脚本)（建设中）

苍雾世界 小助手。图像技术 + 模拟控制，解放双手！  
由 [MaaFramework](https://github.com/MaaXYZ/MaaFramework) 强力驱动！

## 功能介绍

准备做的的功能：

1. 启动游戏
2. 每日免费礼包
3. 作战
4. 演习
5. 指挥室领取
6. 奖励领取
7. 商店资源购买
8. 好友点赞
9. 关闭游戏

## 使用说明

下载地址：<https://github.com/yeluo2022/MHWA/releases>

1. MuMu模拟器需要关闭模拟器设置中的“后台挂机时保活运行”
2. 模拟器不能有中文路径
3. 模拟器窗口大小要16:9，最好建议是使用720p分辨率

## How to build

**如果你要编译源码才看这节，否则直接 [下载](https://github.com/yeluo2022/MHWA/releases) 即可**

0. 完整克隆本项目及子项目

    ```bash
    git clone --recursive https://github.com/yeluo2022/MHWA
    ```

1. 下载 MaaFramework 的 [Release 包](https://github.com/MaaXYZ/MaaFramework/releases)，解压到 `deps` 文件夹中
2. 安装

    ```python
    python ./install.py
    ```

生成的二进制及相关资源文件在 `install` 目录下

## 开发相关

- [MaaFramework 快速开始](https://github.com/MaaXYZ/MaaFramework/blob/main/docs/zh_cn/1.1-%E5%BF%AB%E9%80%9F%E5%BC%80%E5%A7%8B.md)

 完成开发后，上传您的代码并发布版本。

    ```bash
    # 配置 git 信息（仅第一次需要，后续不用再配置）
    git config user.name "您的 GitHub 昵称"
    git config user.email "您的 GitHub 邮箱"
    
    # 提交修改
    git add .
    git commit -m "XX 新功能"
    git push origin HEAD -u
    ```

 发布您的版本

    需要**先**修改仓库设置 `Settings` - `Actions` - `General` - `Read and write permissions` - `Save`

    ```bash
    # CI 检测到 tag 会自动进行发版
    git tag v1.0.0
    git push origin v1.0.0
    ```

## Join us

- MaaFramework 开发交流 QQ 群: 595990173

## 鸣谢

本项目由 **[MaaFramework](https://github.com/MaaXYZ/MaaFramework)** 强力驱动！
