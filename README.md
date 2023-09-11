# kHOA1245
Bai tap ve in so va tinh toan dt

#include <iostream>

/* run this program using the console pauser or add your own getch, system("pause") or input loop */

int main(int argc, char** argv) {
	printf("\n================= nhap tu ban phim =================\n");
	int chieudai, chieurong, chuVi, DienTich;
	printf("\nNhap gia tri cua chieudai = ");
	scanf("%d", &chieudai);
	printf("\nchieudai = %d", chieudai);
		printf("\nNhap gia tri cua chieurong = ");
	scanf("%d", &chieurong);
	printf("\nchieurong = %d",chieurong);
 chuVi = chieurong + chieudai + chieurong + chieudai;
 printf("\nChu Vi cua hinh chu nhat =");
	printf("\n%d", chuVi );
	DienTich = chieurong*chieudai;
	 printf("\nDien Tich cua hinh chu nhat =");
	printf("\n%d", DienTich);
	
	
	int BanKinhHinhTron, ChuViHinhTron, DienTichHinhTron;
	printf("\nBan kinh hinh tron =");
	scanf("%d", &BanKinhHinhTron);
	printf("\nBan Kinh hinh tron = %d", BanKinhHinhTron);
	ChuViHinhTron = BanKinhHinhTron*2*3.14;
	printf("\nChu vi cua hinh tron la");
	printf("\n%d", ChuViHinhTron);
		DienTichHinhTron = BanKinhHinhTron*BanKinhHinhTron*3.14;
	printf("\nDien Tich cua hinh tron la");
	printf("\n%d", DienTichHinhTron);
	
int i;
int n;
  long S;
  S = 0;
  i = 1;
  printf("\nNhap vào so N: ");
  scanf("%d", &n);
 
  for(int i = 1; i <=n; i++)
    {
        S = S + i;
    }
  printf("\nTu 1 den N la  1 + 2 + ... + %d là %ld: ", n, S);
 
  printf("\n----------------------------------------\n");
	
	
		return 0;
}
