# 儿童绘本 AI 制作工具

这是一个使用 Midjourney AI 来制作儿童绘本的项目。本工具旨在帮助创作者快速生成高质量的儿童绘本插图，并提供完整的绘本制作工作流程指南。

## 项目目标

- 使用 Midjourney AI 生成符合儿童审美的绘本插图
- 建立统一的绘本风格指南
- 确保插图的连贯性和故事性
- 优化提示词以获得最佳效果

## 使用指南

### 1. 绘本风格设定

在开始制作之前，需要确定以下要素：
- 目标年龄段：6-9岁（小学低年级）
  - 认知特点：具备基础阅读能力，对科学知识感兴趣，想象力丰富
  - 审美偏好：既喜欢写实又接受夸张有趣的表现手法
  - 情节复杂度：可以接受多角色互动和稍复杂的故事情节
- 绘本风格：半写实风格，细节丰富但不过分复杂
- 色彩基调：明快活泼，可以使用较丰富的色彩搭配
- 主要角色设定：
  1. 小明（中国男孩）
     - 年龄：8岁
     - 特征：活泼好动，充满好奇心
     - 外观：短发，圆脸，白色短袖衬衫配米色短裤，红色领结
     - 性格：阳光开朗，喜欢探索新事物
  
  2. 小红（中国女孩）
     - 年龄：8岁
     - 特征：聪明细心，爱思考
     - 外观：扎着双马尾，戴眼镜，白色短袖衬衫配格子百褶裙，红色领结
     - 性格：认真负责，乐于助人
  
  3. 李老师（女教师）
     - 年龄：28岁
     - 特征：温柔耐心，富有教育智慧
     - 外观：干练的短发，优雅得体的着装
     - 性格：和蔼可亲，善于引导

### 2. Midjourney 提示词模板

#### 基础风格提示词
核心风格：
```
Chinese children's book illustration, semi-realistic style, soft lighting, gentle colors, clean lines, educational atmosphere, high quality, detailed, professional illustration, --style raw --v 6.1
```

#### 6.1 模型特性优化
1. 构图控制
   - 使用 `--zoom` 调整画面远近
   - 使用 `--pan` 微调画面位置
   - 使用 `--tile` 生成无缝贴图

2. 画面质量
   - 默认输出更高质量
   - 更好的人物面部表现
   - 更自然的光影效果

3. 新增参数使用
   - `--repeat` 生成多张相似图
   - `--chaos` 控制创意变化程度
   - `--weird` 增加独特创意效果

#### 优化后的提示词结构
```
[场景描述], [人物描述], [动作/情节], [环境细节], [风格修饰词], Chinese children's book style, --style raw --v 6.1 --zoom 1.5
```

#### 人物标准造型（6.1优化版）

1. 小明三视图组合：
```
Character reference sheet of 8-year-old Chinese boy, three views on white background: [front view: white short-sleeve shirt, beige shorts, round face, short black hair, cheerful expression] [side view: same outfit in profile, showing natural posture] [back view: same outfit from behind, backpack detail], height 130cm, semi-realistic children's book style, clean lines, professional character design layout, labeled views, --style raw --v 6.1 --ar 16:9 --zoom 1.2
```

2. 小红三视图组合：
```
Character reference sheet of 8-year-old Chinese girl, three views on white background: [front view: white short-sleeve shirt, plaid pleated skirt, round glasses, twin ponytails with red hair ties, gentle smile] [side view: same outfit in profile, showing neat posture] [back view: same outfit from behind, twin ponytails detail], height 128cm, semi-realistic children's book style, clean lines, professional character design layout, labeled views, --style raw --v 6.1 --ar 16:9 --zoom 1.2
```

3. 李老师三视图组合：
```
Character reference sheet of 28-year-old Chinese female teacher, three views on white background: [front view: professional light blue blouse and dark skirt, shoulder-length straight black hair, warm expression] [side view: same outfit in profile, showing elegant posture] [back view: same outfit from behind, hair detail], height 165cm, semi-realistic children's book style, clean lines, professional character design layout, labeled views, --style raw --v 6.1 --ar 16:9 --zoom 1.2
```

#### 角色设计参考要点

1. 三视图布局：
   - 正面视图居中
   - 侧面视图位于左侧
   - 背面视图位于右侧
   - 添加视角标签
   - 包含尺寸参考线

2. 统一要素：
   - 白色背景
   - 清晰的轮廓线
   - 一致的比例尺
   - 标准的站姿
   - 完整的服装细节

3. 注意事项：
   - 保持服装细节在三个视角的一致性
   - 确保人物比例准确
   - 添加必要的标注
   - 突出关键特征

#### 场景示例（6.1优化版）

1. 教室场景：
```
Modern Chinese elementary school classroom, Xiao Ming in white shirt and beige shorts, Xiao Hong in white shirt and plaid skirt, both wearing red bow ties, sitting at desks while Teacher Li explains at whiteboard, organized desk rows, educational posters on walls, warm natural lighting, cheerful learning atmosphere, Chinese children's book style, --style raw --v 6.1 --zoom 1.5 --chaos 20
```

2. 实验室场景：
```
School science laboratory, Teacher Li demonstrating experiment, Xiao Ming and Xiao Hong wearing safety goggles observing with curiosity, clean lab equipment, safety posters, warm lighting, educational atmosphere, Chinese children's book style, --style raw --v 6.1 --zoom 1.5 --chaos 20
```

#### 服装细节参考

1. 小明夏季校服：
- 上衣：白色短袖衬衫，胸前口袋，红色领结
- 下装：米色短裤，长度及膝
- 鞋子：白色运动鞋配白色短袜
- 配饰：红色领结，胸牌

2. 小红夏季校服：
- 上衣：白色短袖衬衫，蝴蝶结领结
- 下装：红蓝格子百褶裙，长度及膝
- 鞋子：黑色皮鞋配白色短袜
- 配饰：红色领结，胸牌，红色发圈

#### 6.1版本特殊效果提示词

1. 光影增强：
```
[基础场景], cinematic lighting, volumetric light, soft shadows, --style raw --v 6.1
```

2. 细节增强：
```
[基础场景], intricate details, sharp focus, high definition, --style raw --v 6.1 --zoom 1.2
```

3. 氛围增强：
```
[基础场景], atmospheric, mood lighting, ambient occlusion, --style raw --v 6.1
```

#### 质量控制参数（6.1版本）
- 使用 `--v 6.1` 获得最新模型效果
- 使用 `--style raw` 保持画面清晰度
- 使用 `--zoom` 调整构图
- 使用 `--chaos` 控制变化程度（建议值：20-30）
- 使用 `--repeat` 批量生成相似图像

### 示例组合

1. 教室场景完整提示词：
```
Modern Chinese elementary school classroom, Xiao Ming and Xiao Hong sitting at desks while Teacher Li explains at whiteboard, organized desk rows, educational posters on walls, warm natural lighting, cheerful learning atmosphere, Chinese children's book illustration, semi-realistic style, soft lighting, gentle colors, clean lines, educational atmosphere, high quality, detailed, professional illustration, --ar 7:10 --v 5.2 --style raw --q 2
```

2. 实验室场景完整提示词：
```
School science laboratory, Teacher Li demonstrating experiment, Xiao Ming and Xiao Hong wearing safety goggles observing with curiosity, clean lab equipment, safety posters, warm lighting, educational atmosphere, Chinese children's book illustration, semi-realistic style, soft lighting, gentle colors, clean lines, high quality, detailed, professional illustration, --ar 7:10 --v 5.2 --style raw --q 2
```

### 3. 主要场景设定与提示词

1. 教室场景
   - 环境特征：
     - 明亮现代的中国小学教室
     - 整齐的课桌椅
     - 多媒体教学设备
     - 展示学生作品的墙面
   
   提示词示例：
   ```
   Modern Chinese elementary school classroom, bright natural lighting, colorful educational posters on walls, neat rows of desks, Teacher Li teaching at whiteboard, Xiao Ming and Xiao Hong sitting attentively, semi-realistic style, children's book illustration, warm atmosphere, --ar 2:1
   ```

2. 操场场景
   - 环境特征：
     - 宽敞的塑胶跑道
     - 绿色的运动场
     - 体育器材区
     - 休息长椅区
   
   提示词示例：
   ```
   Sunny Chinese school playground, red running track, green sports field, children playing sports, Xiao Ming playing basketball, Xiao Hong and Teacher Li cheering, semi-realistic style, dynamic scene, vibrant colors, --ar 2:1
   ```

3. 图书室场景
   - 环境特征：
     - 整齐的书架
     - 舒适的阅读区
     - 自然采光
     - 学习交流区
   
   提示词示例：
   ```
   Cozy school library, wooden bookshelves, reading corner with cushions, warm lighting, Xiao Hong reading a book, Xiao Ming browsing shelves, Teacher Li recommending books, semi-realistic style, peaceful atmosphere, --ar 2:1
   ```

4. 花园场景
   - 环境特征：
     - 色彩缤纷的花圃
     - 小型菜园
     - 观察学习区
     - 户外课桌
   
   提示词示例：
   ```
   School garden with blooming flowers, vegetable patches, learning area with benches, Teacher Li showing plants to Xiao Ming and Xiao Hong, butterfly flying, semi-realistic style, natural sunlight, vibrant colors, --ar 2:1
   ```

5. 实验室场景
   - 环境特征：
     - 科学实验台
     - 安全设备
     - 展示柜
     - 互动学习区
   
   提示词示例：
   ```
   Elementary school science lab, safety equipment, microscopes, interactive displays, Teacher Li demonstrating experiment, Xiao Ming and Xiao Hong wearing safety goggles, semi-realistic style, educational atmosphere, --ar 2:1
   ```

### 4. 场景互动指南

1. 教室互动
   - 课堂教学场景
   - 小组讨论
   - 展示作品
   - 回答问题

2. 操场活动
   - 体育课活动
   - 课间游戏
   - 团队运动
   - 休息交流

3. 图书室活动
   - 安静阅读
   - 图书推荐
   - 小组学习
   - 故事分享

4. 花园活动
   - 自然观察
   - 植物培育
   - 户外课程
   - 环保活动

5. 实验室活动
   - 科学实验
   - 安全教育
   - 观察记录
   - 探究讨论

### 5. 场景转换建议

- 保持时间的连续性（上午、中午、下午）
- 确保天气的一致性
- 维持角色服装的统一
- 注意场景间的自然过渡

## 绘本制作目录结构

### 1. 角色设定（/characters）
- 基础设定
  - 小明三视图组合.png
  - 小红三视图组合.png
  - 李老师三视图组合.png
- 表情设定
  - 小明表情组合.png
  - 小红表情组合.png
  - 李老师表情组合.png
- 动作设定
  - 小明动作组合.png
  - 小红动作组合.png
  - 李老师动作组合.png
- 参考文档
  - 角色设定说明.md
  - 尺寸参考表.md
  - 服装细节说明.md

### 2. 场景设定（/scenes）
- 教室场景
  - 教室-空场景.png
  - 教室-上课.png
  - 教室-小组活动.png
- 操场场景
  - 操场-空场景.png
  - 操场-体育课.png
  - 操场-课间活动.png
- 图书室场景
  - 图书室-空场景.png
  - 图书室-阅读.png
  - 图书室-讨论.png
- 花园场景
  - 花园-空场景.png
  - 花园-观察.png
  - 花园-实践.png
- 实验室场景
  - 实验室-空场景.png
  - 实验室-实验.png
  - 实验室-讨论.png

### 3. 分镜脚本（/storyboard）
- 第1章：初识科学
  - 场景1：教室引入
  - 场景2：实验室探索
  - 场景3：课后讨论
- 第2章：自然探索
  - 场景1：花园观察
  - 场景2：记录发现
  - 场景3：分享成果
- 第3章：运动乐趣
  - 场景1：操场活动
  - 场景2：团队合作
  - 场景3：总结收获
- 第4章：知识殿堂
  - 场景1：图书室探索
  - 场景2：阅读分享
  - 场景3：知识应用

### 4. 文字内容（/text）
- story.md（故事文本）
- dialogs.md（对话内容）
- descriptions.md（场景描述）

### 5. 素材资源（/assets）
- 背景元素
  - 教室装饰
  - 实验器材
  - 自然元素
  - 教学用具
- 道具设定
  - 书本教材
  - 实验工具
  - 运动器材
  - 学习用品
- 环境效果
  - 光影设置
  - 天气效果
  - 氛围渲染

### 6. 排版设计（/layout）
- 封面设计
- 内页版式
- 章节页设计
- 文字版式

### 7. 输出文件（/output）
- 预览版本
  - 低分辨率PDF
  - 样张图片
- 印刷文件
  - 高分辨率PDF
  - 分层源文件
- 电子版本
  - 阅读版PDF
  - 交互式电子书

### 8. 项目文档（/docs）
- 制作说明
- 风格指南
- 修改记录
- 版本控制

### 9. 工作流程

1. 前期准备
   - 确定主题和内容大纲
   - 完成角色设定
   - 制作场景概念图

2. 内容制作
   - 生成角色立绘
   - 创建场景背景
   - 编写故事文本
   - 制作分镜脚本

3. 排版设计
   - 确定版式
   - 编排文字
   - 调整构图
   - 添加细节

4. 最终输出
   - 校对内容
   - 调整效果
   - 输出文件
   - 存档备份

### 10. 质量检查清单

- [ ] 角色一致性检查
- [ ] 场景连贯性确认
- [ ] 故事流畅度评估
- [ ] 文字排版核对
- [ ] 色彩效果确认
- [ ] 印刷适应性测试
- [ ] 最终效果审核

#### 表情组合提示词

1. 小明表情组合：
```
Expression sheet for Xiao Ming, Chinese boy character: [happy: cheerful wide smile, bright eyes] [curious: raised eyebrows, attentive gaze] [thinking: slight frown, hand on chin] [excited: beaming smile, sparkling eyes] [focused: concentrated look, determined expression], consistent semi-realistic children's book style, clean layout with labels, white background, --style raw --v 6.1 --ar 16:9
```

2. 小红表情组合：
```
Expression sheet for Xiao Hong, Chinese girl character: [gentle smile: kind eyes behind glasses] [studious: focused gaze, slight head tilt] [helpful: warm encouraging smile] [thoughtful: contemplative look, slight smile] [attentive: alert expression, bright eyes], consistent semi-realistic children's book style, clean layout with labels, white background, --style raw --v 6.1 --ar 16:9
```

3. 李老师表情组合：
```
Expression sheet for Teacher Li, Chinese female teacher: [welcoming: warm professional smile] [teaching: engaging expression, encouraging look] [caring: gentle concerned expression] [proud: appreciative smile] [guiding: patient explanatory expression], consistent semi-realistic children's book style, clean layout with labels, white background, --style raw --v 6.1 --ar 16:9
```

#### 动作组合提示词

1. 小明动作组合：
```
Action sheet for Xiao Ming, Chinese boy character: [running: energetic motion] [raising hand: eager to answer] [experimenting: careful handling of equipment] [playing sports: dynamic athletic pose] [reading: casual relaxed posture], consistent semi-realistic children's book style, clean layout with labels, white background, --style raw --v 6.1 --ar 16:9
```

2. 小红动作组合：
```
Action sheet for Xiao Hong, Chinese girl character: [writing notes: focused posture] [helping others: supportive stance] [conducting experiment: precise movements] [reading: proper studying posture] [presenting: confident speaking pose], consistent semi-realistic children's book style, clean layout with labels, white background, --style raw --v 6.1 --ar 16:9
```

3. 李老师动作组合：
```
Action sheet for Teacher Li, Chinese female teacher: [teaching at board: professional stance] [demonstrating experiment: careful guidance] [helping students: supportive posture] [explaining: engaging gesture] [observing: attentive monitoring pose], consistent semi-realistic children's book style, clean layout with labels, white background, --style raw --v 6.1 --ar 16:9
```

// ... rest of existing code ... #   C h e n g Y u 
 
 