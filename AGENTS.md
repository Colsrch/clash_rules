# 仓库规则

- 本仓库只维护 Clash 配置与规则文件，不新增或维护自动化测试，也不创建 `tests/` 目录。
- 修改 `stash` 或 `rules/*.list` 后，只检查文件格式：所有文件必须能被 YAML 解析，并通过 `git diff --check`。
- 不需要为代理组、规则路由、provider 映射或文件名编写行为测试。
