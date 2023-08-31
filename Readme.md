# 森空岛 ~~（斯卡蒂）~~ 社区 API
## 鹰角网络旗下官方玩家社区 API
---
### 叠甲
- 本项目遵守 CC-BY-NC 4.0 协议，禁止一切商业使用，如需转载请注明作者 ID
- 请勿滥用，本项目仅用于学习和测试！禁止通过本项目向社区滥用发布请求
- 因使用本项目造成的一切后果，本项目作者不承担任何责任
- 本项目所涉及的公司名称、商标、产品等均为其各自所有者的资产，仅供识别。项目内使用的游戏图片、动画、音频、文本原文，仅用于更好地表现游戏资料，其版权属于 Arknights/上海鹰角网络科技有限公司。
### API 清单
本清单接口列表自动化构建于森空岛 APP，清单内容由 ChatGPT 提供，并未经过测试，仅供参考

*更新时间：2023/08/31*
| 接口解释 | 请求地址 | 方法 | 是否完成 | 备注 |
|---------|---------|------|--------|--------|
| 获取用户附加信息 | `/api/v1/user/info/additional` | `GET` | X |
| 用户删除预检查 | `/api/v1/user/delete/precheck` | `GET` | X |
| 获取当前用户信息 | `/api/v1/user/me` | `GET` | X |
| 获取用户信息 | `/api/v1/user/info` | `GET` | X |
| 获取用户基本信息 | `/api/v1/user/info/basic` | `GET` | X |
| 编辑用户信息 | `/api/v1/user/edit` | `POST` | X |
| 调整评论标记操作 | `/api/v1/moderator/comment/mark/adjust` | `POST` | X |
| 调整评论操作操作 | `/api/v1/moderator/comment/operation/adjust` | `POST` | X |
| 调整物品标记操作 | `/api/v1/moderator/item/mark/adjust` | `POST` | X |
| 调整物品操作操作 | `/api/v1/moderator/item/operation/adjust` | `POST` | X |
| 调整物品类别操作 | `/api/v1/moderator/item/cate/adjust` | `POST` | X |
| 对用户进行制裁 | `/api/v1/moderator/user/sanction` | `POST` | X |
| 获取版主日志列表 | `/api/v1/moderator/log/list` | `GET` | X |
| 撤销版主日志操作 | `/api/v1/moderator/log/revoke` | `POST` | X |
| 搜索物品 | `/api/v1/search/item` | `POST` | X |
| 搜索用户 | `/api/v1/search/user` | `POST` | X |
| 搜索建议 | `/api/v1/search/suggestion` | `POST` | X |
| 获取热门搜索 | `/api/v1/search/hot` | `POST` | X |
| 搜索标签 | `/api/v1/search/tag` | `POST` | X |
| 获取热门标签列表 | `/api/v1/tags/list-hot` | `POST` | X |
| 获取玩家绑定信息 | `/api/v1/game/player/binding` | `GET` | X |
| 获取玩家信息 | `/api/v1/game/player/info` | `GET` | X |
| 显示玩家配置 | `/api/v1/game/player/show-config` | `POST` | X |
| 显示玩家资产 | `/api/v1/game/player/asset-show` | `POST` | X |
| 获取提醒列表 | `/api/v1/reminder/list` | `GET` | X |
| 获取通知列表 | `/api/v1/notification/list` | `GET` | X |
| 获取系统消息列表 | `/api/v1/system-message/list` | `GET` | X |
| 触发动作 | `/api/v1/action/trigger` | `POST` | X |
| 取消动作 | `/api/v1/action/cancel` | `POST` | X |
| 多重取消动作 | `/api/v1/action/multi-cancel` | `POST` | X |
| 获取关系列表 | `/api/v1/relation/list` | `GET` | X |
| 更改关系 | `/api/v1/relation/change` | `POST` | X |
| 用户举报 | `/api/v1/report/user` | `POST` | X |
| 物品举报 | `/api/v1/report/item` | `POST` | X |
| 评论举报 | `/api/v1/report/comment` | `POST` | X |
| 获取用户头像列表 | `api/v1/user/avatar/list` | 未知 | X |
| 主页信息 | `api/v1/home/index` | 未知 | X |
| 版主角色信息 | `api/v1/moderator/role` | 未知 | X |
| 游戏信息 | `api/v1/game` | 未知 | X |
| 我的角色 | `myCharacters?token=` | 未知 | X |
| 我的角色 | `myCharacters?token=` | 未知 | X |
| 游戏 ~~出勤信息~~ 签到 | `api/v1/game/attendance` | `GET` | X | 获取签到收益列表、历史签到记录
| 游戏 ~~出勤信息~~ 签到 | `api/v1/game/attendance` | `POST` | X | 进行签到 |
| 游戏信息 | `api/v1/game` | 未知 | X |
| 主页信息 | `api/v1/home/index` | 未知 | X |
| 默认角色切换 | `api/v1/game/player/default-switch` | 未知 | X |
| 我的角色 | `myCharacters?token=` | 未知 | X |