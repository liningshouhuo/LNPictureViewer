# LNPictureViewer
#带有圆形加载进度图片浏览器
##
#
    使用方法：
    
    NSArray *imageArray = @[@"http://ww3.sinaimg.cn/large/006ka0Iygw1f6bqm7zukpj30g60kzdi2.jpg",
                            @"http://ww1.sinaimg.cn/large/61b69811gw1f6bqb1bfd2j20b4095dfy.jpg",
                            @"http://ww1.sinaimg.cn/large/54477ddfgw1f6bqkbanqoj20ku0rsn4d.jpg"];
                            
    LNPictureView *pickView = [[LNPictureView alloc] init];
    
    pickView.viewAlpha = 1;
    
    pickView.imageArray = imageArray;
    
    [pickView showLNPictureViewAndIndex:1];//显示第几张图片
    
    
    更新优化代码，并添加放大、缩小手势
    使用方法示例
        NSArray *imageArray = @[@"http://ww3.sinaimg.cn/large/006ka0Iygw1f6bqm7zukpj30g60kzdi2.jpg",
                            @"http://ww1.sinaimg.cn/large/61b69811gw1f6bqb1bfd2j20b4095dfy.jpg",
                            @"http://ww1.sinaimg.cn/large/54477ddfgw1f6bqkbanqoj20ku0rsn4d.jpg"];
    LNPictureView *pictureView = [[LNPictureView alloc] init];
    pictureView.isScalePinchGesture = YES;//添加放大、缩小手势，默认不添加该手势
    pictureView.viewAlpha = 1;//背景透明度
    pictureView.imageArray = imageArray;
    [pictureView showLNPictureViewAndIndex:1];//显示第几张图片
    
    
    
    
    
