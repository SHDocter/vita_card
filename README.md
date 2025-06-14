# 千蚀vita套麻袋模拟器

在麻袋里放关东煮诱惑千蚀vita上钩

## 功能

- 套麻袋一次
- 套麻袋十次

## 使用方法

### 如果要体验模拟套麻袋，请访问托管页面：<br>

[Vercel](https://card.vitavita.world/)<br>

### 如果对此项目本身感兴趣

此项目是采用 `typescript` + `less` + `html` 进行前端开发的小型静态页面，使用 `webpack` 构建打包

如果想修改ts代码(位于 `src/ts` 文件夹内)以后运行，需要安装 `Node.js` 的环境

clone项目

```bash
git clone https://github.com/SHDocter/vita_card.git
```

随后在项目根目录执行

```bash
npm i
```

- 修改完成以后编译

由于使用了 `webpack`，故直接在项目目录控制台输入

```bash
npm run build
```

随后打开`dist/index.html`或进行静态托管即可看到效果

### 项目源码结构

```plaintext
src
|- css
   |- style.less        less样式表
   |- style.css         编译后的css样式表
|- img                  图片
   ...
|- page
   |-  index.ejs        页面模板
|- ts                   ts源码文件
   |- ConstVar.ts       常量
   |- Counter.ts        计数器类
   |- HeadHunter.ts     寻访类
   |- JsonDefines.d.ts  接口定义
   |- main.ts           入口
   |- Random.ts         随机类
   |- SJManager.ts      货币管理器类
   |- ViewControl.ts    UI视图控制类
```