# 12fz-sso — 统一用户认证（Go）

统一用户认证系统，管理所有用户注册、登录、权限。

## 技术栈
- Go 1.24+
- Gin（HTTP框架）
- JWT（Access 15min + Refresh 30天）
- PostgreSQL（unified_users 等表）

## Phase 1 任务
1. Go项目骨架搭建（路由/中间件/配置）
2. 统一用户系统（unified_users + unified_oauth_bindings）
3. 用户角色权限中心（角色/权限/菜单）
4. 认证网关（邮箱密码 + JWT + OAuth框架）
5. 企业子账号系统（suzao/kefu 命名体系）

详见 https://github.com/ai12fz/12fz-docs
