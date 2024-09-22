<<<<<<< HEAD
# admin-dashboard-java
A Spring Boot-based Admin Dashboard with user, role, and permission management.
=======
# Admin Dashboard 后台管理系统

## 功能
- 用户管理：添加、删除、更新用户
- 角色管理：为用户分配角色，设置权限
- 权限管理：为角色分配权限
- 安全：基于 Spring Security 的权限控制

## 如何运行

1. 克隆项目。
2. 创建 MySQL 数据库 `admin_dashboard`，并在 `application.properties` 文件中配置数据库连接。
3. 运行 `AdminDashboardApplication.java`，启动服务。
4. 使用 Postman 或其他工具通过 RESTful API 进行测试。

## API 列表

- `GET /api/users`：获取所有用户
- `POST /api/users`：创建新用户
- `DELETE /api/users/{id}`：删除用户
- `GET /api/roles`：获取所有角色
- `POST /api/roles`：创建新角色
- `DELETE /api/roles/{id}`：删除角色
>>>>>>> 45ffdb1 (Initial commit)
