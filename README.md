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
     - 外观：短发，圆脸，经常穿运动风格的校服
     - 性格：阳光开朗，喜欢探索新事物
  
  2. 小红（中国女孩）
     - 年龄：8岁
     - 特征：聪明细心，爱思考
     - 外观：扎着双马尾，戴眼镜，穿整洁的校服
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
Chinese children's book illustration, semi-realistic style, soft lighting, gentle colors, clean lines, educational atmosphere, high quality, detailed, professional illustration, --ar 7:10 --v 5.2 --style raw
```

风格修饰词组合：
- 整体氛围：`warm and inviting, cheerful atmosphere, educational setting`
- 艺术风格：`semi-realistic watercolor, clean digital art, soft textures`
- 光影效果：`soft natural lighting, gentle shadows, warm glow`
- 色彩基调：`vibrant but harmonious colors, pastel palette, school-themed colors`
- 画面质感：`smooth gradients, subtle textures, clean edges`

#### 场景通用提示词结构
```
[基础场景描述], [人物描述], [动作/情节], [环境细节], [风格修饰词], [核心风格提示词], --ar 7:10 --v 5.2 --style raw
```

#### 人物统一风格

##### 小明三视图标准造型：

1. 正面视图：
```
Front view of 8-year-old Chinese boy, modern navy blue school uniform, round face, short black hair, height 130cm, energetic standing pose, cheerful expression, white background, character reference sheet, semi-realistic children's book style, clean lines, consistent character design, --ar 1:1 --v 5.2 --style raw
```

2. 侧面视图：
```
Side profile view of 8-year-old Chinese boy, modern navy blue school uniform, round face profile, short black hair, height 130cm, standing pose from side angle, white background, character reference sheet, semi-realistic children's book style, clean lines, consistent character design, --ar 1:1 --v 5.2 --style raw
```

3. 背面视图：
```
Back view of 8-year-old Chinese boy, modern navy blue school uniform, short black hair, height 130cm, standing pose from behind, backpack detail, white background, character reference sheet, semi-realistic children's book style, clean lines, consistent character design, --ar 1:1 --v 5.2 --style raw
```

##### 小红三视图标准造型：

1. 正面视图：
```
Front view of 8-year-old Chinese girl, modern red school uniform, round glasses, twin ponytails with red hair ties, height 128cm, neat standing pose, gentle smile, white background, character reference sheet, semi-realistic children's book style, clean lines, consistent character design, --ar 1:1 --v 5.2 --style raw
```

2. 侧面视图：
```
Side profile view of 8-year-old Chinese girl, modern red school uniform, round glasses side view, twin ponytails with red hair ties, height 128cm, standing pose from side angle, white background, character reference sheet, semi-realistic children's book style, clean lines, consistent character design, --ar 1:1 --v 5.2 --style raw
```

3. 背面视图：
```
Back view of 8-year-old Chinese girl, modern red school uniform, twin ponytails with red hair ties, height 128cm, standing pose from behind, backpack detail, white background, character reference sheet, semi-realistic children's book style, clean lines, consistent character design, --ar 1:1 --v 5.2 --style raw
```

##### 李老师三视图标准造型：

1. 正面视图：
```
Front view of 28-year-old Chinese female teacher, professional light blue blouse and dark skirt, shoulder-length straight black hair, height 165cm, professional standing pose, warm welcoming expression, white background, character reference sheet, semi-realistic children's book style, clean lines, consistent character design, --ar 1:1 --v 5.2 --style raw
```

2. 侧面视图：
```
Side profile view of 28-year-old Chinese female teacher, professional light blue blouse and dark skirt, shoulder-length straight black hair, height 165cm, standing pose from side angle, white background, character reference sheet, semi-realistic children's book style, clean lines, consistent character design, --ar 1:1 --v 5.2 --style raw
```

3. 背面视图：
```
Back view of 28-year-old Chinese female teacher, professional light blue blouse and dark skirt, shoulder-length straight black hair, height 165cm, standing pose from behind, white background, character reference sheet, semi-realistic children's book style, clean lines, consistent character design, --ar 1:1 --v 5.2 --style raw
```

#### 人物参考要点

1. 服装细节：
   - 小明：深蓝色校服，运动风格，配白色运动鞋
   - 小红：红色校服，整洁大方，配黑色皮鞋
   - 李老师：浅蓝色衬衫，深色半身裙，配黑色中跟鞋

2. 发型特征：
   - 小明：短直发，自然蓬松，略微偏分
   - 小红：双马尾，红色发圈，整齐服帖
   - 李老师：肩长直发，干练利落，自然垂落

3. 体态特征：
   - 小明：活泼好动，经常微微前倾
   - 小红：端正有礼，保持良好坐姿
   - 李老师：优雅大方，举止得体

4. 表情参考：
   - 小明：阳光笑容，眼神好奇
   - 小红：温和微笑，眼神专注
   - 李老师：亲切微笑，眼神温和

#### 生成建议
1. 先使用三视图提示词生成人物参考图
2. 保存满意的 seed 值
3. 在场景中使用相同的 seed 值确保人物特征一致性
4. 可以使用 `--seed [数字]` 参数复用成功的人物特征

#### 场景风格统一
1. 室内场景基础提示词：
```
Indoor school setting, clean modern interior, warm lighting, educational decorations, organized space, semi-realistic children's book style, --ar 7:10
```

2. 室外场景基础提示词：
```
Outdoor school environment, natural lighting, clear sky, school building background, safe playground setting, semi-realistic children's book style, --ar 7:10
```

#### 统一细节要素
- 光线：`soft natural lighting, gentle shadows`
- 色调：`warm and vibrant, school-themed colors`
- 构图：`dynamic composition, clear focal point`
- 细节：`educational details, age-appropriate elements`
- 氛围：`positive learning environment, friendly atmosphere`

#### 质量控制参数
- 添加 `--v 5.2` 获得更稳定的风格
- 使用 `--style raw` 保持画面清晰度
- 添加 `--q 2` 提高生成质量
- 使用 `--seed [数字]` 保持风格一致性

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

// ... rest of existing code ... #   C h e n g Y u  
 