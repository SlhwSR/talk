# next即使通讯based on Next.js 13, React, Tailwind, Prisma, MongoDB, NextAuth, Pusher (2023)


Key Features:

使用push的实时消息传递
—消息通知和警报
-时尚UI的顺风设计
-tailwind Css和过渡效果
-对所有设备的完全响应
-使用NextAuth进行凭据认证
- Github认证集成
—通过cloudary CDN上传文件和图片
客户端表单验证和处理使用react-hook-form
-使用react-toast处理服务器错误
-消息读取收据
—在线/离线用户状态
-群聊和一对一消息
—邮件附件和文件共享
—用户配置文件自定义和设置
如何在路由处理程序中编写POST、GET和DELETE路由(app/api)
 mongod db集成serveless
—在实时环境中处理Server和Child组件之间的关系
-创建和管理聊天室和频道



### 环境

**Node version 16.x**

### Cloning the repository

```shell
git clone https://github.com/AntonioErdeljac/next13-messenger.git
```

### Install packages

```shell
npm i
```

### Setup .env file


```js
DATABASE_URL=
NEXTAUTH_SECRET=

NEXT_PUBLIC_PUSHER_APP_KEY=
PUSHER_APP_ID=
PUSHER_SECRET=

NEXT_PUBLIC_CLOUDINARY_CLOUD_NAME=

GITHUB_ID=
GITHUB_SECRET=

GOOGLE_CLIENT_ID=
GOOGLE_CLIENT_SECRET=
```

### Setup Prisma

```shell
npx prisma db push

```

### Start the app

```shell
npm run dev
```