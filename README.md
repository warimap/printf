# Printf
  2 
  3 The printf project is a collaboration between Faith Warima Ng'endo  and David Macharia W    aweru, actual students of Software Engineering at Holberton School, were a function name    d "_printf" imitates the actual "printf" command located in the stdio.h library. It cont    ains some of the basic features and functions found in the manual 3 of "printf".
  4 
  5 _printf() is a function that performs formatted output conversion and print data. Its pr    ototype is the following:
  6 
  7         int _printf(const char *format, ...)
  8 
  9 Where **format** contains the string that is printed. As _printf() is variadic function,     it can receives n arguments that replace by n tags written inside the string.
 10 
 11 The format tags prototype is the following:
 12 
 13         %[flags][length]specifier
 14 
 15 If the program runs successfully, the **return value** is the amount of chars printed.
 16 
 17 | Specifier | Output |
 18 | ------------- | ------------- |
 19 | c  | Character  |
 20 | d or i | Signed decimal integer |
 21 | s  | String of characters  |
 22 | b  | Signed binary  |
 23 | o  | Signed octal  |
 24 | u  | Unsigned integer  |
 25 | x  | Unsigned hexadecimal  |
 26 | X  | Unsigned hexadecimal (uppercase)  |
 27 | p  | Pointer address  |
 28 | r  | Reverse string of characters |
 29 | R  | ROT13 translation of string |
 30 | S  | String with special chars replaced by their ASCII value  |
 31 | %  | Character  |
 32 
 33 | Flags | Description | Specifiers |
 34 | ------------- | ------------- | ------------- |
 35 | +  | Prints a plus sign (+) when the argument is a positive number. In other case, pri    nts a minus sign (-). | i, d |
 36 | (space) | Prints a blank space if the argument is a positive number | i, d |
 37 | #  | Prints 0, 0x and 0X for o, x and X specifiers, respectively. It doesn't print any    thing if the argument is zero | o, x, X |
 38 
 39 | Length | Description | Specifiers |
 40 | ------------- | ------------- | ------------- |
 41 | l | Prints a long int or unsigned long int | i, d, o, u, x and X |
 42 | h | Prints a short int or unsigned short int | i, d, o, u, x and X |
 43 
 44 ------------
 45 ## Technologies
 46 * Repository printf created in Github account of one group member.
 47 * Scripts written in Bash 4.3.11(1)
 48 * C files are compiled using `gcc 4.8.4`
 49 * C files are written according to the C90 standard
 50 * Tested on Ubuntu 14.04 LTS
 51 
 52 ## Project
All of the files are Task  projects done during the printf group studies.
 54 
 55 
 56 ## File Functions
 57 
 58 ### _printf.c
 59 Own Printf Function Tha Performs Formatted Output Conversion And Print Data.
 60 
 61 ------------
 62 
 63 ### main.h
 64 Header File Were All Prototypes Are Saved.
 65 
 66 ------------
 67 
 68 ### get_print_func.c
 69 Pointer To A Function That Selects The Correct Function To Perform The Operation.
 70 
 71 ------------
 72 
 73 ### print_buf.c
 74 Function That Prints The Buffer.
 75 
 76 ------------
 77 
 78 ### handl_buf.c
 79 Function That Concatenates The Buffer Characters.
 80 
 81 ------------
 82 
 83 ### print_chr.c
 84 Function That Writes The Character C To Stdout.
 85 ```c
 86 /* Indetifier : %c */
 87 ```
 88 
 89 ------------
 90 
 91 ### print_str.c
 92 Function That Writes The String To Stdout.
 93 ```c
 94 /* Indetifier : %s */
 95 ```
 96 
 97 ------------
 98 
 99 ### print_int.c
100 Function That Prints An Integer.
101 ```c
102 /* Indetifier : %i or %d */
103 ```
104 
105 ------------
106 
107 ### print_bnr.c
108 Function That Prints Decimal In Binary.
109 ```c
/* Indetifier : %b */
111 ```
112 
113 ------------
114 
115 ### print_oct.c
116 Function That Prints Decimal In Octal.
117 ```c
118 /* Indetifier : %o */
119 ```
120 
121 ------------
122 
123 ### print_hex.c
124 Function That Prints Decimal In Hexadecimal.
125 ```c
126 /* Indetifier : %x */
127 ```
128 
129 ------------
130 
131 ### print_upx.c
132 Function That Prints Decimal In Uppercase Hexadecimal.
133 ```c
134 /* Indetifier : %X */
135 ```
136 
137 ------------
138 
139 ### print_usr.c
140 Function That Prints A String And Values Of Non-Printed Chars.
141 ```c
142 /* Indetifier : %S */
143 ```
144 
145 ------------
146 
147 ### print_unt.c
148 Function That Prints An Unsigned Integer.
149 ```c
150 /* Indetifier : %u */
151 ```
152 
153 ------------
154 
155 ### print_rev.c
156 Function That Writes The String To Stdout In Reverse.
157 ```c
158 /* Indetifier : %r */
159 ```
160 
161 ------------
162 
163 ### print_rot.c
Function That Writes The String To Stdout In Rot13.
165 ```c
166 /* Indetifier : %R */
167 ```
168 
169 ------------
170 
171 ### print_add.c
172 Function That Prints The Address Of An Input Variable.
173 ```c
174 /* Indetifier : %p */
175 ```
176 
177 ------------
178 
179 ### print_long_oct.c
180 Function That Prints Long Decimal Number In Octal.
181 ```c
182 /* Indetifier : %lo */
183 ```
184 
185 ------------
186 
187 ### print_long_hex.c
188 Function That Prints Long Decimal Number In Hexadecimal.
189 ```c
190 /* Indetifier : %lx */
191 ```
192 
193 ------------
194 
195 ### print_long_int.c
196 Function That Prints  A Long Integer.
197 ```c
198 /* Indetifier : %li */
199 ```
200 
201 ------------
202 
203 ### print_long_upx.c
204 Function That Prints A Long Decimal In Uppercase Hexadecimal.
205 ```c
206 /* Indetifier : %lX */
207 ```
208 
209 ------------
210 
211 ### print_long_unt.c
212 Function That Prints A Long Unsigned Integer.
213 ```c
214 /* Indetifier : %lu */
215 ```
216 
217 ------------

219 ### print_short_oct.c
220 Function That Prints Short Decimal Number In Octal.
221 ```c
222 /* Indetifier : %ho */
223 ```
224 
225 ------------
226 
227 ### print_short_hex.c
228 Function That Prints Short Decimal Number In Hexadecimal.
229 ```c
230 /* Indetifier : %hx */
231 ```
232 
233 ------------
234 
235 ### print_short_int.c
236 Function That Prints  A Short Integer.
237 ```c
238 /* Indetifier : %hi */
239 ```
240 
241 ------------
242 
243 ### print_short_upx.c
244 Function That Prints A Short Decimal In Uppercase Hexadecimal.
245 ```c
246 # Printf
247   2
248   3 The printf project is a collaboration between Faith Warima Ng'endo  and David Machar    ia W    aweru, actual students of Software Engineering at Holberton School, were a funct    ion name    d "_printf" imitates the actual "printf" command located in the stdio.h libr    ary. It cont    ains some of the basic features and functions found in the manual 3 of "    printf".
249 # Printf
250   2
251   3 The printf project is a collaboration between Faith Warima Ng'endo  and David Machar    ia W    aweru, actual students of Software Engineering at Holberton School, were a funct    ion name    d "_printf" imitates the actual "printf" command located in the stdio.h libr    ary. It cont    ains some of the basic features and functions found in the manual 3 of "    printf".
252   4
253   5 _printf() is a function that performs formatted output conversion and print data. It    s pr    ototype is the following:
254   6
255   7         int _printf(const char *format, ...)
256   8
257   9 Where **format** contains the string that is printed. As _printf() is variadic funct    ion,     it can receives n arguments that replace by n tags written inside the string.
258  10
259  11 The format tags prototype is the following:
12
261  13         %[flags][length]specifier
262  14
263  15 If the program runs successfully, the **return value** is the amount of chars printe    d.
264  16
265  17 | Specifier | Output |
266  18 | ------------- | ------------- |
267  19 | c  | Character  |
268  20 | d or i | Signed decimal integer |
269  21 | s  | String of characters  |
270  22 | b  | Signed binary  |
271  23 | o  | Signed octal  |
272  24 | u  | Unsigned integer  |
273  25 | x  | Unsigned hexadecimal  |
274  26 | X  | Unsigned hexadecimal (uppercase)  |
275  27 | p  | Pointer address  |
276  28 | r  | Reverse string of characters |
277  29 | R  | ROT13 translation of string |
278  30 | S  | String with special chars replaced by their ASCII value  |
279  31 | %  | Character  |
280  32
281  33 | Flags | Description | Specifiers |
282  34 | ------------- | ------------- | ------------- |
283  35 | +  | Prints a plus sign (+) when the argument is a positive number. In other case,     pri    nts a minus sign (-). | i, d |
284  36 | (space) | Prints a blank space if the argument is a positive number | i, d |
285  37 | #  | Prints 0, 0x and 0X for o, x and X specifiers, respectively. It doesn't print     any    thing if the argument is zero | o, x, X |
286  38
287  39 | Length | Description | Specifiers |
288  40 | ------------- | ------------- | ------------- |
289  41 | l | Prints a long int or unsigned long int | i, d, o, u, x and X |
290  42 | h | Prints a short int or unsigned short int | i, d, o, u, x and X |
291  43
292  44 ------------
293  45 ## Technologies
294  46 * Repository printf created in Github account of one group member.
295  47 * Scripts written in Bash 4.3.11(1)
296  48 * C files are compiled using `gcc 4.8.4`
297  49 * C files are written according to the C90 standard
298  50 * Tested on Ubuntu 14.04 LTS
299  51
300   4
301   5 _printf() is a function that performs formatted output conversion and print data. It    s pr    ototype is the following:
302   6
303   7         int _printf(const char *format, ...)
304   8
  9 Where **format** contains the string that is printed. As _printf() is variadic funct    ion,     it can receives n arguments that replace by n tags written inside the string.
306  10
307  11 The format tags prototype is the following:
308  12
309  13         %[flags][length]specifier
310  14
311  15 If the program runs successfully, the **return value** is the amount of chars printe    d.
312  16
313  17 | Specifier | Output |
314  18 | ------------- | ------------- |
315  19 | c  | Character  |
316  20 | d or i | Signed decimal integer |
317  21 | s  | String of characters  |
318  22 | b  | Signed binary  |
319  23 | o  | Signed octal  |
320  24 | u  | Unsigned integer  |
321  25 | x  | Unsigned hexadecimal  |
322  26 | X  | Unsigned hexadecimal (uppercase)  |
323  27 | p  | Pointer address  |
324  28 | r  | Reverse string of characters |
325  29 | R  | ROT13 translation of string |
326  30 | S  | String with special chars replaced by their ASCII value  |
327  31 | %  | Character  |
328  32
329  33 | Flags | Description | Specifiers |
330  34 | ------------- | ------------- | ------------- |
331  35 | +  | Prints a plus sign (+) when the argument is a positive number. In other case,     pri    nts a minus sign (-). | i, d |
332  36 | (space) | Prints a blank space if the argument is a positive number | i, d |
333  37 | #  | Prints 0, 0x and 0X for o, x and X specifiers, respectively. It doesn't print     any    thing if the argument is zero | o, x, X |
334  38
335  39 | Length | Description | Specifiers |
336  40 | ------------- | ------------- | ------------- |
337  41 | l | Prints a long int or unsigned long int | i, d, o, u, x and X |
338  42 | h | Prints a short int or unsigned short int | i, d, o, u, x and X |
339  43
340  44 ------------
341  45 ## Technologies
342  46 * Repository printf created in Github account of one group member.
343  47 * Scripts written in Bash 4.3.11(1)
344  48 * C files are compiled using `gcc 4.8.4`
345  49 * C files are written according to the C90 standard
346  50 * Tested on Ubuntu 14.04 LTS
347  51
348 /* Indetifier : %hX */                 
```
350 
351 ------------
352 
353 ### print_short_unt.c
354 Function That Prints A Short Unsigned Integer.
355 ```c
356 /* Indetifier : %hu */
357 ```
358 
359 ------------
360 
361 ### print_num_hex.c
362 Function That Print A Number In Hexadecimal Begining With 0 And x.
363 ```c
364 /* Indetifier : %#x */
365 ```
366 
367 ------------
368 
369 ### print_num_oct.c
370 Function That Prints A Number In Octal Begining With 0 And o.
371 ```c
372 /* Indetifier : %#o */
373 ```
374 
375 ------------
376 
377 ### print_num_upx.c
378 Function That Prints A Number In Uppercase Hexadecimal.
379 ```c
380 /* Indetifier : %#X */
381 ```
382 
383 ------------
384 
385 ### print_plus_int.c
386 Function That Prints An Integer With Plus Symbol.
387 ```c
388 /* Indetifier : %+i */
389 ```
390 
391 ------------
392 
393 ### print_space_int.c
394 Function That Prints An Integer Begining With 0 And u.
395 ```c
396 /* Indetifier : % i */
397 ```
398 
399 ------------
400 
401 ### ev_print_func.c
402 Function That Returns The Amount Of Indetifiers.
403 
404 ------------
405 
406 
407 # ANSWERS

409 The following link contains answers given for each task and  are explained in depth.
410 <a href="https://docs.google.com/document/d/1CrvES5I22vKO7x09gkIzfNIQE9TT7MdatllkqM2Y7PI    /edit?usp=sharing">DOCUMENT CONTAINING EXPLAINED ANSWERS</a>
411 
412 
413 
414 
415 
416 - We on my way to be the best software engineer that I  can possibly  be!!
417 
418 ## Author 
419 + Faith Warima Ng'endo. Nickname- Pharium Warima
420 + David Macharia Waweru.
421 
422 ---
423 
424 ## WARNING!!
425 - This repo is done as a school group  assignment. Beware of copying my responses. I rec    ommend you  to read resources and come up with your own solutions instead. Feel free to     reach out for help!
426 - This repo may contain some errors. If you notice any, please add a pull request.
