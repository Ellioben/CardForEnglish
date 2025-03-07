# 英语学习产品 - 图片单词标记工具

## 产品概述
本产品是一款帮助用户通过图片学习英语单词的工具。用户可以通过拍照或上传图片，系统会自动识别图片中的常见物体并标记对应的英语单词。同时，系统会生成一段描述图片的英语句子，帮助用户学习相关词汇和表达。

## 主要功能
1. 图片上传/拍照
2. 自动识别图片中的物体
3. 标记英语单词
4. 生成图片描述
5. 单词发音功能

## 交互流程

### 1. 首页
- 显示产品logo和名称
- 两个主要按钮：
  - 📷 拍照
  - 📂 上传图片

### 2. 图片处理页面
#### 2.1 图片展示区
- 显示用户拍摄/上传的图片
- 图片加载时显示进度条

#### 2.2 单词标记过程
- 系统自动识别图片中的物体
- 在图片上显示识别到的物体，并标记对应的英语单词
  - 标记样式：单词 + 箭头指向物体
  - 点击标记可播放单词发音

#### 2.3 图片描述区
- 在图片下方显示系统生成的英语描述
  - 示例： "This is a picture of a cat sitting on a chair next to a table."
- 每个名词单词高亮显示
- 点击高亮单词可播放发音

### 3. 学习模式
- 点击"学习"按钮进入学习模式
- 显示所有标记单词的列表，包括：
  - 单词
  - 音标
  - 中文释义
  - 发音按钮
- 提供"添加到生词本"功能

### 4. 历史记录
- 显示用户之前处理过的图片
- 点击图片可查看之前的标记和描述
- 提供删除功能

## 技术实现
1. 图片识别：使用计算机视觉技术识别图片中的物体
2. 单词标记：根据识别结果匹配对应的英语单词
3. 句子生成：使用自然语言处理技术生成描述性句子
4. 发音功能：集成TTS（Text-to-Speech）技术

## 未来功能规划
1. 支持视频输入
2. 添加单词测验功能
3. 社交分享功能
4. 个性化学习推荐