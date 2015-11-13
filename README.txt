调用系统的代码即可实现二维码扫描功能，并且性能比ZBar强多了。


- (void)scanButtonEvent:(UIButton *)sender {
    
    lhScanQCodeViewController * sqVC = [[lhScanQCodeViewController alloc]init];
    UINavigationController * nVC = [[UINavigationController alloc]initWithRootViewController:sqVC];
    [self presentViewController:nVC animated:YES completion:^{
        
    }];
}


