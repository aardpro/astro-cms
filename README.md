# astro-cms
> A SEO-friendly, Astro-based responsive blog/CMS system with optimized content management.    
> 一个基于 Astro 开发的 SEO 友好、响应式博客/内容管理系统。    

## 首次部署
***注意拉取docker需要魔法上网***
```bash
git clone https://github.com/aardpro/astro-cms.git
cd astro-cms
docker compose up -d
```
### 然后通过 http://127.0.0.1:8103访问
### 管理员账号：admin
### 管理员初始密码：admin

### 更新镜像
```bash
cd astro-cms
docker compose pull && docker compose down && docker compose up -d
```

## 预览
***首页***
![](./assets/home-1.webp)
***首页***
![](./assets/home-2.webp)
***登录入口***
![](./assets/home-3.webp)
***系统配置***
![](./assets/admin-1.webp)
***管理文章***
![](./assets/admin-5.webp)
***编辑文章***
![](./assets/admin-2.webp)
***编辑菜单***
![](./assets/admin-3.webp)
***裁剪图片***
![](./assets/admin-4.webp)