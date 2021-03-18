# 해당 용도 
수업을 들으며 기억해야겠다 혹은 , 따로 기록하고 싶은 내용들을 저장하는 공간 
복습차원이라 생각하면 될것같습니다. 


# 하노이 탑 쌓기 

Input : n개의 원반이 봉 a에 크기 순으로 쌓여있다.

output : n개의 원반이 봉 b에 크기 순으로 쌓여있다.

procedure : 
               hanoi_Tower(n,a,b,c) { 
                 if (n > 0 ) { 
  	                   hanoi Tower( n-1 , a, c, b) ; 
                                봉 a의 마지막 원반을 봉 b로 옮김 
                                hanoi_Tower(n-1 , c, b ,a );
                   } 
              } 
