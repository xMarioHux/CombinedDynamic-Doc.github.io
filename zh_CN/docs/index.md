# 接口文档
[<返回](../index.md)

这里收录了本Addon提供的接口，您可以在您的Addon中使用这些接口来为您的游戏内容添加与复合动力联动的功能。

## 内置tag

| 名称 | 描述 |
| --- | :---: |
| [`combined_dynamic:is_wrench`](./inner_tags/is_wrench.md) | 将物品定义为扳手 |

## tag组件

| 名称 | 描述 |
| --- | :---: |
| [`combined_dynamic:pressable`](./tag_components/pressable.md) | 将物品定义为可锻压物品 |
| [`combined_dynamic:fuel`](./tag_components/fuel.md) | 将物品定义为机器燃料 |

## 脚本事件

| 名称 | 描述 |
| --- | :---: |
| `combined_dynamic:recipe_register` | 注册机器配方 |

## 内置类

| 名称 | 描述 |
| --- | :---: |
| `ItemIngredient` | 物品配方原料 |
| `TagIngredient` | 标签配方原料 |
| `ItemResult` | 物品配方结果 |
