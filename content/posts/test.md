---
title : 2025-我的第一篇博客
date : 2025-01-18T12:01:38+08:00
categories : ["日记"]
tags : ["日记"]
---

# 2025-我的第一篇博客

## 1. 计划

### 🌅 早晨

#### 计划 

- [ ] test

#### 复盘 

- 看看效果
---

### ☀️ 下午

#### 计划 

- [ ] test

#### 复盘 

---

### 🌇 晚上

#### 计划

#### 复盘 

---

## 2. 笔记索引

```dataview
LIST FROM ""
WHERE file.cday = date("2024-12-04")
```

---

## 3. 资源与链接

---

## 4. 未完成的任务

```dataview
TASK FROM "dairy"
WHERE !completed
  AND file.cday >= (this.file.cday - dur(7 days))
  AND file.cday <= this.file.cday
SORT file.cday DESC
```

---

## 5. 反思