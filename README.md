# QrCode
1.主动激活接口     参数（序列号，客户ID）      返回值int                0[失败]        1[使用次数达到上限]   2[成功]
2.被动激活检测     参数（客户ID）                 返回值int               0[以激活]      1[未激活]
3.客户反馈           参数（客户ID,二进制数组）  返回值boolean        true[成功]    falsep[未激活]  
4.客户反馈获取     参数（客户ID）                 返回值                   二进制数组  
5.获取客户ID       参数  无                           返回值                   string          **返回所有激活的客户ID      
6.批量生成二维码
