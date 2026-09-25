# persona-manager

管理用户画像 `persona.md` 的一键操作：清空（备份后重置为空白六维模板）或导入（从来源文件导入，备份旧的 + 校验六维）。

## 这是什么

DSH（DeepSeek Harness）skill —— 一个薄触发壳，实际文件操作由 `scripts/` 下的 Python 标准库脚本执行。

## 安装

    git clone https://github.com/hpsks416/persona-manager.git "$env:USERPROFILE\.dsh\skills\persona-manager"
    # 或 Gitee（国内直连）
    git clone https://gitee.com/hpsks416/persona-manager.git "$env:USERPROFILE\.dsh\skills\persona-manager"

## 使用

- 说「清空画像 / 重置画像」→ 备份当前画像并重置为空白六维模板
- 说「导入画像 <文件路径>」→ 从来源导入（备份旧的 + 校验六维结构）

画像积累本身由铁律二的「收尾提取」机制负责，本 skill 只做清空/导入。

## 目录结构

    persona-manager/
    ├── SKILL.md
    └── scripts/
        ├── persona_clear.py
        └── persona_import.py

## License

MIT License. See [LICENSE](LICENSE).
