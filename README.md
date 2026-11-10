# 黄鸡大笑桌宠

macOS 桌面宠物：黄鸡大笑（和黄鸡小笑）陪你学习、工作、睡觉、玩耍、看电影、打游戏。

这个仓库只放**安装包和自动更新文件**，不包含源代码。

## 下载安装

到 [Releases](https://github.com/xuan-88-505/huangji-pet/releases/latest) 下载最新版本：

- Apple 芯片（M1 / M2 / M3 / M4）：`HuangjiPet-版本号-Apple-Silicon.zip`
- Intel 芯片：`HuangjiPet-版本号-Intel.zip`

解压后把 `HuangjiPet.app` 拖进「应用程序」，在终端执行一次：

```
xattr -cr /Applications/HuangjiPet.app
```

然后正常打开即可。

## 自动更新

1.1.5 及以上版本会每 6 小时检查一次这里的 `latest.json`。有新版本时，桌宠会在后台下载几百 KB 的内容包（`updates/content-版本号.asar`），下好后冒气泡提醒，重启一下就能用。

- 每个更新都带 Ed25519 签名，桌宠只接受签名验证通过的更新
- 新版本万一启动失败，会自动退回上一个能用的版本
- 国内访问 GitHub 慢的话，会自动改走 jsDelivr 镜像

---

粉丝自制，仅供个人娱乐使用。黄鸡大笑、黄鸡小笑形象版权归《剑网3》/ 西山居所有，请勿商用。
