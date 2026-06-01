# 小羊成卷 / Lambfolio 1.0.0 (15)

GitHub DMG 发布包。

## 下载文件

- `xiaoyangchengjuan-1.0.0-15.dmg`

## 更新内容

- 优化长篇生成内存管理，冻结后释放节点临时上下文与流式事件。
- 流式正文仅保留界面尾部窗口，避免长输出造成内存持续增长。
- 加强模型 JSON 输出校验，异常包装文本会触发重试。
- 正文写作优先生成 4000 字以上丰富内容，同时保留 3000 字软提示以兼容更多模型。

## SHA256

```text
8f0e1712f2ad83c284157576ce90c106d6cb35ce47e60060c53ebbc1d5028c46  xiaoyangchengjuan-1.0.0-15.dmg
```

## 使用平台

- macOS 14.0 或更高版本
- Apple Silicon / arm64
- Intel Mac 暂未单独提供构建包

## 许可限制

本软件仅限个人非商业使用，禁止商用、转载、镜像、二次分发、转售或转授权。

## macOS 安全提示

当前 GitHub DMG 包未使用 Developer ID 公证。首次打开如被 macOS 拦截，请在"系统设置 > 隐私与安全性"中允许打开。
