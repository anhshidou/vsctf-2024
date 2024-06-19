![image](https://github.com/anhshidou/vsctf-2024/assets/120787381/d080eeb5-fc3e-4049-b84f-105d6a5e27e7)

Ở bài này, thì ta đúng nghĩ phải dịch ngược. Sau khi cùng (xem) anh Trí ngồi làm. Mình đã nhận ra được cách hợp lý nhất để làm bài này là phải hiểu awascii:))

![image](https://github.com/anhshidou/vsctf-2024/assets/120787381/e6b1f29a-f5c7-41a1-93a0-e93f05044878)

và awatisms

![image](https://github.com/anhshidou/vsctf-2024/assets/120787381/0d3eabd3-8241-4adf-8e00-687bb4b33041)

Hiểu đơn giản thì sau khi hỏi chatgpt, mình biết rằng stack của awa là bubble abyss. Và nhờ GPT viết code hộ. Ouput mình có được là

``` awa awa awawawa                            red
awa awawawawa                              pop
awa awawawa awa | awa awa awawa awa        sbm 2
awa awawawa awa | awa awa awawawa          sbm 3
awa awawawa awa | awa awawa awa awa        sbm 4
awa awawawa awa | awa awa awa awawa        sbm 1
awa awawawa awa | awa awawawa awa          sbm 6
awa awawawa awa | awa awawa awawa          sbm 5
awa awawawa awa | awa awa awawawa          sbm 3
awa awawawa awa | awawa awawa awa          sbm 10
awa awawawa awa | wa awawa awa awa         sbm 20
awa awawawa awa | wa awawawa awa           sbm 22
awa awawawa awa | wawa awa awawa           sbm 25
awa awawawa awa | awa awa awawawa          sbm 3
awa awawawa awa | awa awa awa awa awa      sbm 0
awa awawawa awa | awa awa awa awa awa      sbm 0
awa awawawa awa | awa awa awawa awa        sbm 2
awa awawawa awa | awa awa awawawa          sbm 3
awa awawawa awa | awa awawa awa awa        sbm 4
awa awawawa awa | awa awa awa awawa        sbm 1
awa awawawa awa | awa awawawa awa          sbm 6
awa awawawa awa | awa awawa awawa          sbm 5
awa awawawa awa | awa awa awawawa          sbm 3
awa awawawa awa | awawa awawa awa          sbm 10
awa awawawa awa | wa awawa awa awa         sbm 20
awa awawawa awa | wa awawawa awa           sbm 22
awa awawawa awa | wawa awa awawa           sbm 25
awa awawawa awa | awa awa awawawa          sbm 3
awa awawawa awa | awa awa awa awa awa      sbm 0
awa awawawa awa | awa awa awa awa awa      sbm 0
awa awawawa awa | awa awa awa awa awa      sbm 0
awa awawawa awa | wa awa awa awa awa       sbm 16
awa awawawa awa | wawa awawa awa           sbm 26
awa awawawa awa | wawawawawa               sbm 31
awa awa awa awawa                          prn
awa awa awa awawa                          prn
awa awa awa awawa                          prn
awa awa awa awawa                          prn
awa awa awa awawa                          prn
awa awa awa awawa                          prn
awa awa awa awawa                          prn
awa awa awa awawa                          prn
awa awa awa awawa                          prn
awa awa awa awawa                          prn
awa awa awa awawa                          prn
awa awa awa awawa                          prn
awa awa awa awawa                          prn
awa awa awa awawa                          prn
awa awa awa awawa                          prn
awa awa awa awawa                          prn
awa awa awa awawa                          prn
awa awa awa awawa                          prn
awa awa awa awawa                          prn
awa awa awa awawa                          prn
awa awa awa awawa                          prn
awa awa awa awawa                          prn
awa awa awa awawa                          prn
awa awa awa awawa                          prn
awa awa awa awawa                          prn
awa awa awa awawa                          prn
awa awa awa awawa                          prn
awa awa awa awawa                          prn
awa awa awa awawa                          prn
awa awa awa awawa                          prn
awa awa awa awawa                          prn
awa awa awa awawa                          prn
```

Vậy là mình đã có được đáp án sẽ có 31 kí tự. Tiếp tục thì ta sẽ tự dịch awatisms qua awascii rồi lên gpt stack hộ. Stack xong thì ta sẽ có đáp án là:

``` J3lly_0oooosHii11i_awawawawaawa! ```

Vậy flag là:

Flag: **vsctf{J3lly_0oooosHii11i_awawawawaawa!}**
