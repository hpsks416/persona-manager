# persona-manager

管理 `~/.dsh/persona.md` 的一键清空 / 导入。实际文件操作由 `scripts/` 下的脚本执行，本 skill 只负责触发 + 确认。

## 环境依赖

- 操作系统：Windows
- 运行时：Python 3（标准库）
- 第三方软件：无（仅依赖系统自带的 PowerShell / 标准库）

## 目录结构

    persona-manager/
    ├── SKILL.md    技能入口与工作流
    ├── scripts\persona_clear.py
    ├── scripts\persona_import.py

## 安装

    # GitHub
    git clone https://github.com/hpsks416/persona-manager.git "$env:USERPROFILE\.dsh\skills\persona-manager"
    # 或 Gitee（国内直连）
    git clone https://gitee.com/hpsks416/persona-manager.git "$env:USERPROFILE\.dsh\skills\persona-manager"

克隆后 DSH 自动重新发现，无需构建。

## License

MIT License. See [LICENSE](LICENSE).
