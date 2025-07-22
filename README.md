# MaaErrorCircleSound
---
本项目由[MaaFramework](https://github.com/MaaXYZ/MaaFramework)强力驱动!。

[原始README](./README_Old.md)

## 计划列表
### 功能类：
- [x] 游戏
  - [x] 启动游戏
  - [ ] 关闭游戏
- [ ] 收取邮件
- [x] 招募-外部招募
- [x] 补给站-支援货柜-每日礼包
- [x] 事务所
  - [x] 刷残片
  - [x] 卖材料
- [ ] 任务x
  - [x] 日常任务
  - [ ] 周常任务
  - [x] 市区巡逻
- [x] 作战
  - [x] 阈限禁区-会客间
        刷周本黑胶
  - [x] 特别行动-危机行动
        刷心锚
  - [ ] 画个大饼
- [ ] 画个大饼

### UI/体验类
- [ ] 启动游戏前切换分辨率
- [ ] 画个大饼

## pipeline编写:
1. [任务流水线协议](https://github.com/MaaXYZ/MaaFramework/blob/main/docs/zh_cn/3.1-%E4%BB%BB%E5%8A%A1%E6%B5%81%E6%B0%B4%E7%BA%BF%E5%8D%8F%E8%AE%AE.md)
2. [pipeline-非强制使用](./assets/resource/pipeline/ReadMe.md)


## 上传发版
1. 完成开发工作后，上传您的代码并发布版本。

    ```bash
    # 配置 git 信息（仅第一次需要，后续不用再配置）
    git config user.name "您的 GitHub 昵称"
    git config user.email "您的 GitHub 邮箱"
    
    # 提交修改
    git add .
    git commit -m "XX 新功能"
    git push origin HEAD -u
    ```

2. 发布您的版本

    需要**先**修改仓库设置 `Settings` - `Actions` - `General` - `Read and write permissions` - `Save`

    ```bash
    # CI 检测到 tag 会自动进行发版
    git tag v1.0.0
    git push origin v1.0.0
    ```

3. 更多操作，请参考[个性化配置](./docs/zh_cn/个性化配置.md)（可选）

## 生态共建

MAA 正计划建设为一类项目，而非舟的单一软件。

若您的项目依赖于 MaaFramework，我们欢迎您将它命名为 MaaXXX, MXA, MAX 等等。当然，这是许可而不是限制，您也可以自由选择其他与 MAA 无关的名字，完全取决于您自己的想法！

同时，我们也非常欢迎您提出 PR，在 [最佳实践列表](https://github.com/MaaXYZ/MaaFramework#%E6%9C%80%E4%BD%B3%E5%AE%9E%E8%B7%B5) 中添加上您的项目！

## 鸣谢

本项目由 **[MaaFramework](https://github.com/MaaXYZ/MaaFramework)** 强力驱动！

感谢以下开发者对本项目作出的贡献（下面链接改成你自己的项目地址）:

[![Contributors](https://contrib.rocks/image?repo=MaaXYZ/MaaFramework&max=1000)](https://github.com/MaaXYZ/MaaFramework/graphs/contributors)
