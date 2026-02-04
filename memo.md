VSCodeは複数行選択して、
「CTRL」+「/」
（Macは「Command」+「/」）
すると一括でコメントアウトできる

複数行選択して「Tab」で
一括でTabできる

wire型  
wire 信号幅 信号線名;    のように記述  
信号線を定義する  
```v
wire [31:0] 信号線名;
```

r_aをw_xに代入
```v
assign w_x = r_a;
```

r_aのNOTをw_xに代入
```v
assign w_x = ~r_a;
```

OR