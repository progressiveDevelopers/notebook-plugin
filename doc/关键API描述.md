| 关键字               | 描述                                                         | 接口                 | plugins.xml加载元素     |
| -------------------- | ------------------------------------------------------------ | -------------------- | ----------------------- |
| action               | 在Tools工具菜单添加一个子菜单                                |                      |                         |
| NotificationGroup    | 通知（参数:action的Id）                                      |                      |                         |
| ApplicationComponent | 在idea启动的时候初始化，整个idea中只有一个实例               | ApplicationComponent | <application-componens> |
| ProjectComponent     | idea会为每一个Project实例创建对应级别的Component             | ProjectComponent     | <project-componens>     |
| ModuleComponent      | Idea会为每一个已经加载的Project中的每一个模块（Module）创建Module级别的Component | ModuleComponent      | <module-componens>      |
| DialogWrapper        | 创建对话框                                                   |                      |                         |

