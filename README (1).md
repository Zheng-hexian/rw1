
# xxx的自我介绍

<img src="C:\Users\17520\Desktop\65305dbe9635e9e7cd3c04e24054964b.jpg" width="200" alt="个人头像">

## 大家好，我是**xxx**，我的身份是*xxx*。以下是我的自我介绍：

---

## 基础档案

### 外貌特征
- 特征1
- 特征2

### 我的好朋友
1. 好朋友1
2. 好朋友2
3. ~~好朋友3~~

### 重要坐标

#### 住址
[点击查看我的住址](https://www.google.com/maps)

#### 日常作息表

| 时间段 | 活动内容 |
|--------|--------|
| 08:00-09:00 | 起床、洗漱、早餐 |
| 09:00-12:00 | 学习/工作 |
| 12:00-14:00 | 午餐、午休 |
| 14:00-18:00 | 学习/工作 |
| 18:00-20:00 | 晚餐、休息 |
| 20:00-22:00 | 自主学习/项目实践 |
| 22:00-23:00 | 阅读、准备入睡 |

#### 人生信条
> 保持热爱，奔赴山海。在不断学习中遇见更好的自己。

---

## 我的专业是人工智能

## 我最喜欢的一段代码

```python
# dev_skills_env.py

import os
import sys

def setup_environment():
    """配置开发环境"""
    print("正在初始化人工智能开发环境...")
    
    # 检查Python版本
    python_version = sys.version_info
    print(f"Python版本: {python_version.major}.{python_version.minor}.{python_version.micro}")
    
    # 设置环境变量
    os.environ['AI_PROJECT_ROOT'] = os.getcwd()
    print(f"项目根目录: {os.getenv('AI_PROJECT_ROOT')}")
    
    # 创建必要的目录
    directories = ['data', 'models', 'notebooks', 'outputs']
    for dir_name in directories:
        if not os.path.exists(dir_name):
            os.makedirs(dir_name)
            print(f"已创建目录: {dir_name}")
    
    print("环境配置完成！")
    return True

def main():
    """主函数"""
    print("=" * 50)
    print("人工智能开发环境配置工具")
    print("=" * 50)
    
    if setup_environment():
        print("\n✅ 环境配置成功！")
    else:
        print("\n❌ 环境配置失败！")

if __name__ == "__main__":
    main()
