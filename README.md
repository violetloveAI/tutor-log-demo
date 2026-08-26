# Tutor Log Demo

一个为家教老师设计的课程、学生成长、课表和收入记录演示应用。

**在线演示：** https://violetloveAI.github.io/tutor-log-demo/

> 这是公开演示版。内置姓名、电话和地址均为虚构示例，请勿填写真实个人信息。

![Tutor Log 视觉预览](assets/preview.png)

## 可以体验

- 月视图与周课表，课程可按学生专属颜色辨认
- 学生资料、家教地点简称、详细地址与通勤时间
- 课程内容、掌握情况、作业和下次计划记录
- 本机四位密码保护的老师私密档案
- 课程收入与收款进度统计

所有演示数据只保存在访问者当前浏览器的 `localStorage`，不会上传到服务器。

## 本地运行

```bash
npm install
npm run dev
```

生产构建：

```bash
npm run build
npm run preview
```

## 技术栈

React、TypeScript、Vite、GSAP 与 Lucide Icons。该演示版是纯静态前端，不需要后端服务。

## 说明

本仓库仅用于公开展示，未授予复制、修改或再分发许可。
