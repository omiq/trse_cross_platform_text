* This is a work in progress. Expect things to break

Cross-platform Text Mode Unit for TRSE users.

Currently offers input and output for 

BBC

Apple II

PET

C64

Vic 20

```
// Function prototypes

  	procedure cls();
	procedure cursor_home();
	procedure move_to(_text_x: byte, _text_y: byte);
	procedure wait_vsync();
	procedure text_colour(_chosen_text_colour: byte);
	procedure print_string(in_str: pointer, CRLF: byte = True);
	function get_key():byte;
	procedure wait_key();
	procedure clear_buffer();
	procedure beep();
	procedure DefineScreen();
        procedure put_char_at(_atx,_aty,_atchar:byte);
        procedure put_ch(CH:byte);
        function get_char_at(_col,_row:byte):byte;
	function str_compare(str1,str2:pointer):byte;
	procedure put_dec_at(_natx,_naty,_nat:byte);
	procedure print_dec(_in_n:byte, _add_cr:byte);
	function str_to_dec(_in_str:pointer):byte;
	function get_dec():integer;
```
