# Radare2 Guide

<h3>I: Mở radare2 để đọc assembly code</h3>
<p>1: Mở radare2: r2 file</p>
<img height=300 width=500 src="https://cloud.githubusercontent.com/assets/28984391/26500947/27ecd560-4262-11e7-8e38-5349cf565f4a.png" />
<p>2: Phân tích assembly code (quan trọng) : aaa </p>
<img height=300 width=500 src="https://cloud.githubusercontent.com/assets/28984391/26517169/2bc9f4b4-42bd-11e7-8aa8-8d11c7834f08.png" />
<p>3: Nhảy con trỏ đến vị trí hàm: s [tên hàm/địa chỉ]</p>
<img height=300 width=500 src="https://cloud.githubusercontent.com/assets/28984391/26517189/a74e259c-42bd-11e7-932a-8e49c71d4dcf.png" />
<p>4: In hàm tại địa chỉ con trỏ hiện tại: pdf </p>
<img height=300 width=500 src="https://cloud.githubusercontent.com/assets/28984391/26517203/f157e4ac-42bd-11e7-8687-026ff9eeb073.png" />
<p>5: In hàm tại địa chỉ khác địa chỉ con trỏ (con trỏ không thay đổi) : pdf @ [tên hàm/địa chỉ]</p>
<img height=300 width=500 src="https://cloud.githubusercontent.com/assets/28984391/26517221/63c0a72c-42be-11e7-97b8-2c4b0cd395f7.png" />
<p>6: Thay đổi tên biến tại hàm đang được trỏ đến : afvn [tên cũ] [tên mới] </p>
<img height=300 width=500 src="https://cloud.githubusercontent.com/assets/28984391/26517242/cd0c55dc-42be-11e7-94b1-dff83d97f835.png" />
<p>7: In địa chỉ dưới dạng hexa (hex dump) : px @ [địa chỉ] </p>
<img height=300 width=500 src="https://cloud.githubusercontent.com/assets/28984391/26517300/c95da052-42bf-11e7-9b73-6e8287374d20.png" />
<br><br>
<h3>II: Mở radare2 để debug</h3>
<p>1: Mở radare2 để debug: r2 -d file params</p>
<img height=300 width=500 src="https://cloud.githubusercontent.com/assets/28984391/26517313/468d6198-42c0-11e7-8d5d-6c510f951cf8.png" />
<p>2: Phân tích aaa</p>
<p>3: Mở Visual Mode để debug </p>
<img height=300 width=500 src="https://cloud.githubusercontent.com/assets/28984391/26517322/8f97bb36-42c0-11e7-8983-ef3ed17ce481.png" />
<p>4: Mở chế độ lệnh : : (giống vim) </p>
<img height=300 width=500 src="https://cloud.githubusercontent.com/assets/28984391/26517344/e830f6cc-42c0-11e7-8aee-5f239ef09713.png" />
<p>5: Đặt breakpoint: db [địa chỉ] (nếu muốn xóa bp đặt dấu trừ trước địa chỉ)</p>
<img height=300 width=500 src="https://cloud.githubusercontent.com/assets/28984391/26517353/161cf068-42c1-11e7-9980-55863ea8b34a.png" />
<p>6: Chạy chương trình cho đến khi gặp bp: dc </p>
<img height=300 width=500 src="https://cloud.githubusercontent.com/assets/28984391/26517368/5cf865a8-42c1-11e7-8f50-f8211c3556ea.png" />
<p>7: Nhấn Enter để trở về visual mode </p>
<img height=300 width=500 src="https://cloud.githubusercontent.com/assets/28984391/26517384/973b881c-42c1-11e7-9569-2fc73bf86ed2.png" />
<p>8: Chạy 1 lệnh: s (bỏ qua hàm: S)</p>
<img height=300 width=500 src="https://cloud.githubusercontent.com/assets/28984391/26517399/c22f6908-42c1-11e7-8c3a-65a503d5fdad.png" />
<p>9: Đặt giá trị cho thanh ghi: dr [tên thanh ghi]=[giá trị] </p>
<img height=300 width=500 src="https://cloud.githubusercontent.com/assets/28984391/26517434/97ab0042-42c2-11e7-8ffc-64413bcd51eb.png" />
<p>End!</p>
