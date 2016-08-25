# ExpandHeader

pod 'SPIExpandHeader'

使用方便，一句代码实现！

列表视图或scrollview的头部图片 拉伸放大效果！

导入头文件#import <SPIExpandHeader/CExpandHeader.h>

@interface ViewC () { CExpandHeader *_header; }

(void)viewDidLoad { [super viewDidLoad];

_header = [CExpandHeader expandWithScrollView:self.myTableView expandView:self.cycleScrollView];

}
