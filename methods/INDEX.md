# 808zdlb 方法论文库索引

> 方法论跨模式共享。按场景匹配 → 匹配不到用通用兜底。

## 匹配机制

```
任务来 → 提取特征（模式/用途/主题）
        ↓
     扫描INDEX → 按【适用场景】匹配
        ├─ 命中 → 加载该方法论
        └─ 未命中 → 加载 _universal/ 对应通用方法论
```

## 方法论定义格式

每条方法论：
```
### 方法论名称
- **适用**：审/写/答 + 什么条件下触发（用途/场景/关键词）
- **优先级**：核心（必加载）/ 常用（条件触发）/ 辅助
- **核心规则**：3-7条
```

## 方法论文库

### 共享方法论（跨模式适用）

| 文件 | 适用 | 优先级 |
|------|------|--------|
| [first-principles.md](first-principles.md) | 审/写/答通用 | 核心 |
| [review/pyramid.md](review/pyramid.md) | 审材料+写材料（结论先行） | 核心 |

### 审材料专用

| 文件 | 适用场景 | 触发关键词 | 优先级 |
|------|---------|-----------|--------|
| [review/ppt-review-zhanshi.md](review/ppt-review-zhanshi.md) | 审PPT演讲材料 | PPT/幻灯片/演示 | 常用 |
| [review/ppt-review-style.md](review/ppt-review-style.md) | 审PPT视觉风格 | PPT/幻灯片 | 常用 |
| [review/industry-material-rules.md](review/industry-material-rules.md) | 审行业材料通用规范 | 行业/市场/终端/手机 | 常用 |
| [review/5w2h.md](review/5w2h.md) | 审材料逻辑完整性 | What/Why/When/Where/Who/How | 常用 |
| [review/pdca.md](review/pdca.md) | 审材料闭环 | PDCA/闭环/执行 | 常用 |

### 写材料专用

| 文件 | 适用场景 | 触发关键词 | 优先级 |
|------|---------|-----------|--------|
| [write/pyramid-write.md](write/pyramid-write.md) | 写材料结构（金字塔写作法） | 写/编制/撰写 | 常用 |
| [write/scqa.md](write/scqa.md) | 写宣传/演讲稿（SCQA故事线） | 宣传/演讲/动员 | 常用 |

### 答问题专用

| 文件 | 适用场景 | 触发关键词 | 优先级 |
|------|---------|-----------|--------|
| [answer/first-answer.md](answer/first-answer.md) | 答问题结构（结论先行） | 所有问答 | 常用 |

### 行业数据分析方法论

| 文件 | 适用场景 | 触发关键词 | 优先级 |
|------|---------|-----------|--------|
| [analyze/market-data-read.md](analyze/market-data-read.md) | 涉及销量/份额/同比/5G渗透率等市场数据 | 含"销量""份额""同比""市场数据" | 常用 |
| [analyze/brand-positioning.md](analyze/brand-positioning.md) | 涉及品牌策略/竞品分析/份额解读 | 含"品牌""竞品""份额""价位段" | 常用 |
| [analyze/channel-insight.md](analyze/channel-insight.md) | 涉及渠道策略/线上线下对比 | 含"渠道""线上""线下""电商""零售" | 常用 |

### 通用兜底（匹配不到时自动加载）

| 文件 | 适用 |
|------|------|
| [_universal/review-default.md](_universal/review-default.md) | 审材料通用 |
| [_universal/write-default.md](_universal/write-default.md) | 写材料通用 |
| [_universal/answer-default.md](_universal/answer-default.md) | 答问题通用 |

---

**总计：16条方法论**
- 共享2 + 审阅6 + 写作2 + 问答1 + 分析3 + 兜底3 = 16
