double num = 100.0 / 3.0;
	//控制cout显示精度
	//1.强制以小数的方式显示
	cout << fixed;
	//2.控制小数点后位数
	cout << setprecision(2);//<iomanip>
	//3.设置宽度setw(5),只在显示下个值有效
	
	cout << setw(15)  << num * 1000000 << endl;
