## flutter_sliverappbar

> Flutter_sliverAppBar, 为导航栏添加TabBar,并设置pinned以控制导航栏是否随ScrollView滚动?是否停留到界面顶部?
```flutter
SliverPersistentHeader(
  delegate: _SliverAppBarDelegate(
    TabBar(
      controller: new TabController(length: 2, vsync: this),
      labelColor: Colors.lightBlue,
      indicatorColor: Colors.lightGreen,
      unselectedLabelColor: Colors.grey,
      tabs: <Widget>[
        new Tab(icon: new Icon(Icons.info), text: 'Info',),
        new Tab(icon: new Icon(Icons.cake), text: 'cake',)
      ],
    ),
  ),
  pinned: true,
),
```
