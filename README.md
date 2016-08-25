# ExpandHeader

pod 'SPIExpandHeader'

列表视图或scrollview的头部图片 拉伸放大效果！

@interface ViewC ()
{
        CExpandHeader *_header;
}
- (void)viewDidLoad
{
    [super viewDidLoad];
    
    _header = [CExpandHeader expandWithScrollView:self.myTableView expandView:self.cycleScrollView];

    
}
