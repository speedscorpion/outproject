lbs圈养
=====

定义
=====
这是个基于位置关系的社交平台，通过圈养与被圈养构建社交关系

目标
-----
1.连接人

为了达到连接人的目的，我们需要推进信息交换
同时为了让用户放心地来这个平台交换信息，我们要做到信息保护

2.趣味性

为了创造趣味性，我们需要制定有趣的规则
什么样的规则算有趣呢，符合用户对有趣的认知，就是有趣


基本流程
-----
1.每个用户身兼两职，是一个监护人，同时也是一只宠物
2.将自己放在宠物市场待领养
3.从宠物市场领养别人
4.圈养一段时间
5.释放手中的宠物
6.再次捕获宠物或从市场领养宠物

重复4，5，6三步

信息的交换在第4步完成，宠物可以与监护人对话。同时，圈养与被圈养的关系产生

规则
------
要始终记住，规则的最终目标是创造信息交换的渠道，推进社交关系的建立

获得圈养权方式：
从市场上领养宠物
随机捕获被释放的宠物

在市场上领养时，需要双方的相互认可
监护人可以挑选宠物，这一点毋庸置疑。同时这里我们需要给宠物一个筛选监护人的权利，比如，可以让宠物设置问题，回答满意才允许领养
长时间没有人领养，或不愿意被领养的，我们释放，让宠物可以被随机捕获

为了保证能够被再次捕获，被释放的宠物要在总体上保证先释放，先被捕获，并避开以前的监护人
作为宠物，我们在被释放后，可以回到市场
随机捕获能更快地构建圈养关系，所以，想回到市场需要一定条件

为了保证所有玩家都有宠物可养，我们限定同时只能养一只宠物
为了保证建立更多的圈养关系，我们限定圈养一段时间后，必须释放
圈养关系可以再次建立，需要双方的同意，并满足一定条件

能查看到所有养过自己的监护人的信息，能查看到所有自己养过的宠物的信息，除非对方不想让自己看。这里体现信息保护

市场与释放都基于位置，没有错我们是基于地理位置的

在前面多次提到需要一定条件，这个条件要在圈养关系中获取，在圈养关系结束时对监护人进行评价，这个评价将构成积分。而一定的条件就可以定位扣除这些积分

平台
=====
在没有能够满足刚需，能让用户眼前一亮的情况下，首先考虑的就是微信平台。我们采用web app来实现

功能划分
=====
数据支持，包括位置信息，角色信息，圈养关系信息
逻辑支持，包括展卖，领养，释放，捕获，评价
聊天支持，这里涉及到在线消息与离线消息，两种的消息的实现截然不同
展示支持，展现给用户的页面，包括市场，领养过的宠物，所有的监护人，对话页面，用户的详细信息页面


有趣这一点要能在圈养的过程中体现，圈养过程的本质是对话。如何打造有趣的对话形式，这里需要着力设计。
