```javascript
{
    "indent_size": 4,      //缩进大小，默认4
    "indent_char": " ",    //缩进字符，默认" "
    "eol": "\n",           //end of line，行结尾字符"\n"
    "indent_level": 0,     //初始缩进级别
    "indent_with_tabs": false, //使用tab缩进，将会覆盖“indent_size”和“indent_char”设置，默认false
    "preserve_newlines": true,       //保留空行，默认“true”
    "max_preserve_newlines": 10,     //一次最多保留多少行的空行，默认10
    "jslint_happy": false,           //开启jslint-stricter的严格模式（强制开启“space_after_anon_function”选项）,默认false
    "space_after_anon_function": false, //在匿名函数前自动加一个空格，比如`function (){}`，默认false
    "brace_style": "collapse",          //括号风格，"collapse-preserve-inline", "collapse", "expand", "end-expand", or "none" ,默认“collapse”
    "keep_array_indentation": false,    //保持数组缩进，默认false
    "keep_function_indentation": false, //保持函数缩进，默认false
    "space_before_conditional": true,   //在条件语句之前保留一个空格，默认true
    "break_chained_methods": false,     //中断多行间的链式方法调用，默认true
    "eval_code": false,
    "unescape_strings": false,      //解码用xNN编码的可打印字符，默认false
    "wrap_line_length": 0,          //Wrap lines at next opportunity after N characters. (Set zero to ignore wrapping),默认0,下次在n个字符后换行
    "wrap_attributes": "auto",        //将html属性标签放在新行“auto”,“force”,默认auto
    "wrap_attributes_indent_size": 4, //html属性标签新行缩进字符数，默认为"indent_size"4
    "end_with_newline": false         //在文件结尾保证有换行，默认false
}
```
