![CLEVER DATA GIT REPO](https://raw.githubusercontent.com/LiCongMingDeShujuku/git-resources/master/0-clever-data-github.png "李聪明的数据库")

# SQL Server SSMS 字体和颜色什么是什么
#### SQL Server SSMS Fonts And Colors

## Contents

- [中文](#中文)
- [English](#English)
- [SQL Logic](#Logic)
- [Build Info](#Build-Info)
- [Author](#Author)
- [License](#License) 


## 中文 & English

Here’s a quick and dirty guide to see where to modify certain fonts, and colors.
这是一个快速黑科技帮助你查看修改某些字体和颜色的位置。
If you want to skip directly to the download… The Download is also available as .doc All you need to do is drop the .doc extension, and load up the .vssettings file. 
如果你想直接跳到下载，你需要做的就是删除.doc扩展名，然后加载.vssettings文件。
https://mikesdatawork.wordpress.com/2017/07/07/dark-ssms-theme-ssms-2017/
Here’s everything I modified on my 2016 Management Studio.
这是我在2016 Management Studio上修改的所有内容。
Plain Text
Selected Text
Line Number
Brace Matching
BreakPoint (Enabled)
BreakPoint – Selected
Collapsible Region
Comment
Find Scope Highlight
Keyword
SQL Operator
SQL Stored Procedure
SQL String
SQL System Function
SQL System Table
Sring
Text
Track Changes Before Save
Track Changes After Save
Outlining Margin Square
Outlining Margin Vertical Rule
纯文本
选定的文字
电话号码
支撑匹配
BreakPoint（已启用）
BreakPoint  - 选中
可折叠区域
评论
查找范围突出显示
关键词
SQL运算符
SQL存储过程
SQL字符串
SQL系统功能
SQL系统表
SRING
文本
保存前跟踪更改
保存后跟踪更改
概述边缘广场
概述保证金垂直规则


Starting with ‘Plain Text’. As you can see here; you can modify the basic text colors, and more importantly the background.
以“纯文本”开始说。正如你在这里看到的那样，你可以修改基本的文字颜色，更重要的是背景。


![#](images/ssms-fonts-and-colors-01.png?raw=true "#")
 
Plan Text is found here:
纯文本可在此处找到：

![#](images/ssms-fonts-and-colors-02.png?raw=true "#")
 
Once you do this you’ll notice the highlighting of the current line becomes almost too bright, and can be quite annoying, and maybe even throw of your rhythm. So; to remove that you’ll need to go to the general options and uncheck ‘Highlight Current Line’.
一旦你这样做，你会注意到当前线条的突出显示变得几乎太明亮，这非常烦人。所以，要删除你需要转到常规选项并取消选中“Highlight Current Line”。
![#](images/ssms-fonts-and-colors-03.png?raw=true "#")
 
Here’s how to turn off the Current Highlighting. To go Tools, Options, and then click on ‘General’. Uncheck ‘Highlight Current Line’.
以下是关闭当前突出显示的方法。要转到“工具”，“选项”，然后单击“常规”。取消选中“突出显示当前行”。
![#](images/ssms-fonts-and-colors-04.png?raw=true "#")
 
If you want to change the general highlighting color whenever you select a bunch of syntax you can use the ‘Selected Text’.
如果要在选择一组语法时更改常规突出显示颜色，可以使用“选定文本”。
![#](images/ssms-fonts-and-colors-05.png?raw=true "#")
 
Selected Text found here:
选定的文字在这里：
![#](images/ssms-fonts-and-colors-06.png?raw=true "#")
 
Here’s where the ‘Line Number’ is located.
这是“行号”所在的位置。
![#](images/ssms-fonts-and-colors-07.png?raw=true "#")
 
Line Number can be found here:
行号可以在这里找到：
![#](images/ssms-fonts-and-colors-08.png?raw=true "#")
 
The ‘Brace Matching’ is when the bracket you’re using gets closed, and you see the first one also highlighted. In this example I am using the Parenthesis around the number 16.
“Brace Matching”是指你正在使用的支架关闭时，你会看到第一个支架也突出显示。在这个例子中，我使用数字16。
![#](images/ssms-fonts-and-colors-09.png?raw=true "#")
 
Brace Matching can be found here:
Brace Matching可以在这里找到：
![#](images/ssms-fonts-and-colors-10.png?raw=true "#")
 
All the breakpoint colors and fonts can be found here and are all located together so I’ll just show you what I modified, and you can experiment with the rest. Here you have the breakpoint color modified along with it’s border.
所有的断点颜色和字体都可以在这里找到并且都在一起。所以我只会告诉你我修改了什么，你可以试试其他的。在这里，你可以修改断点颜色及其边框。
![#](images/ssms-fonts-and-colors-11.png?raw=true "#")
 
In this case the ‘Breakpoint (Enabled)’ was modified, and the border color you’ll see below. Whenever you click on the text within the breakpoint it will shows the border color.
在这种情况下，修改了“断点（启用）”，并在下面看到边框颜色。每当你单击断点内的文本时，它将显示边框颜色。
![#](images/ssms-fonts-and-colors-12.png?raw=true "#")
 
Here’s where you modify the border color of the breakpoint once it’s selected. It’s called ‘Breakpoint – Selected’.
在这里，你可以在选择断点后修改断点的边框颜色。它被称为'断点 - 选择'。
![#](images/ssms-fonts-and-colors-13.png?raw=true "#")
 
Here’s the ‘Collapsible Region’. Normally this is super bright and really messes with your eyes while you work through your logic cause every time the cursor passes over the collapsible region it flashes at you. Here; I’m modifying it to be nearly the same color as a usual highlight or (Selected Text) as you see above.
这是'可折叠区域'。通常情况下，这是超级明亮的，当你完成逻辑作业时，你会眼花缭乱，因为每当光标经过可折叠区域时它会闪烁。我正在修改它，使其与正常的显示亮度和颜色几乎相同，或者如上所示（选定文本）。
![#](images/ssms-fonts-and-colors-14.png?raw=true "#")
 
Here’s where you can find the Collapsible Region’:
在这里你可以找到可折叠区域：
![#](images/ssms-fonts-and-colors-15.png?raw=true "#")
 
Here’s where you can modify the ‘Comment’ color. Here; as you can see I’m using the green you’ll usually find in Monokai.

你可以在此处修改“评论”颜色。正如你所看到的，我正在使用通常在Monokai能找到的绿色。
![#](images/ssms-fonts-and-colors-16.png?raw=true "#")
 
The Comment color can be found here:
评论颜色可以在这里找到：
![#](images/ssms-fonts-and-colors-17.png?raw=true "#")
 
Here’s where you can find the bullet icon in the left margin for whenever you do a ‘find’ on your syntax. This is the ‘Find Scope Highlight’
在这里，你可以在左边距中找到子弹图标，以便在对语法进行“查找”时使用。这是“Find Scope Highlight”
![#](images/ssms-fonts-and-colors-18.png?raw=true "#")
 
Here’s where you can find the ‘Find Scope Highlight’.
在这里你可以找到“查找范围突出显示”。
![#](images/ssms-fonts-and-colors-19.png?raw=true "#")
 
Here’s where you can modify the ever so popular ‘Keyword’.
在这里，你可以修改很流行的“关键字”。
![#](images/ssms-fonts-and-colors-20.png?raw=true "#")
 
Keyword can be found here:
关键字可以在这里找到：
![#](images/ssms-fonts-and-colors-21.png?raw=true "#")
 
To modify the ‘SQL Operator’ color you can (and probably should) use a bright color which is basically dedicated only to the operators. I know some of you already wondering what the operators are. There are all kinds. Most basic would be the Logical, Compound, and Numeric operators.
要修改“SQL运算符”颜色，你可以使用基本上仅专用于运算符的亮色。我知道有些人已经想知道运算符是什么。有各种各样的。最基本的是逻辑，复合和数字运算符。
Things like this = &, %, (), <> ALL, AND, ANY, BETWEEN, NOT, OR, SOME, EXISTS etc… More on operators can be found here if you’re curious:
比如说：= &, %, (), <> ALL, AND, ANY, BETWEEN, NOT, OR, SOME, EXISTS 等等…更多的运算符可以参考：
https://msdn.microsoft.com/en-us/library/ms174986.aspx
![#](images/ssms-fonts-and-colors-22.png?raw=true "#")
 
SQL Operators can be found here:
SQL运算符可以在这里找到：
![#](images/ssms-fonts-and-colors-23.png?raw=true "#")
 
‘SQL Stored Procedures’ are using a color from the Monokai theme. Incidentally; I’m using this for both the stored procedures, and the SQL Strings.

“SQL存储过程”使用的是Monokai主题中的颜色。我正在将它用于存储过程和SQL字符串。
![#](images/ssms-fonts-and-colors-24.png?raw=true "#")
 
Here’s where you can find the ‘SQL Stored Procedure’:
在这里你可以找到“SQL存储过程”：
![#](images/ssms-fonts-and-colors-25.png?raw=true "#")
 
To change the colors of the strings simply find the ‘SQL String’. You’ll see in my examples that the strings use a Monokai color, as do the Stored Procedures.
要更改字符串的颜色，只需找到“SQL字符串”。你将在我的示例中看到字符串使用Monokai颜色，存储过程也是如此。

![#](images/ssms-fonts-and-colors-26.png?raw=true "#")
 
The SQL String can be found here:
SQL String可以在这里找到：

![#](images/ssms-fonts-and-colors-27.png?raw=true "#")

 
I colored the ‘SQL System Function’ to be purple based on the Monokai theme.
我根据Monokai主题将“SQL系统功能”设置成紫色。

![#](images/ssms-fonts-and-colors-28.png?raw=true "#")

 
The SQL System Function color can be found here:
SQL系统函数颜色可以在这里找到：
![#](images/ssms-fonts-and-colors-29.png?raw=true "#")
 
My ‘SQL System Table’ colors are bright green. I might end up changing this at a later point, but you can easily find them in your logic this way. Extremely helpful in Joins.
我的“SQL系统表”颜色为亮绿色。我可能会在稍后更改此内容，但你可以通过这种方式轻松地在逻辑中找到它们。在加入的时候非常有用。
![#](images/ssms-fonts-and-colors-30.png?raw=true "#")
 
You can find the SQL System Table color here:
你可以在此处找到SQL系统表颜色：
![#](images/ssms-fonts-and-colors-31.png?raw=true "#")
 
I added this next one in for kicks. Although we already addressed the ‘SQL String’ colors above; we can still make the general ‘String’ color consistent by making it the same.
虽然我们已经解决了上面的“SQL String”颜色，我们仍然可以相同的方法来使一般的“String”颜色保持一致。
![#](images/ssms-fonts-and-colors-32.png?raw=true "#")
 
As with ‘Text’; I went ahead, and made it the same as the Plain Text above.
与“文字”一样，我继续操作，并使其与上面的纯文本相同。
![#](images/ssms-fonts-and-colors-33.png?raw=true "#")
 
Whenever you modify a line, delete a line, add a line you’ll see on the left of the editor a vertical line which is keeping track of changes. That line in the SSMS is called the ‘Track Changes before save’ item. Formerly this was bright green. It goes away once it’s saved, but for a dark theme the bright green was too much so I made it a lite shade of red.
无论何时修改一条线，删除一条线，在编辑器左侧添加一条直线，该线跟踪变化。 SSMS中的该行称为“保存前跟踪更改”项。以前这是亮绿色。一旦它被保存就会消失，但对于一个黑暗的主题，明亮的绿色太多，所以我把它变成了浅红色。
![#](images/ssms-fonts-and-colors-34.png?raw=true "#")
 
Here’s where you can find the Track Changes before save item:
你可以在此处找到保存项目之前的跟踪更改：
![#](images/ssms-fonts-and-colors-35.png?raw=true "#")
 
Additionally; you can always change the color to something else; to show syntax was modified. However; as with my theme I made it the same color as the background so it disappears once the changes are saved.

另外，你可以随时改变颜色，突出显示被修改的语法。然而，我设置它与我的背景颜色相同，所以一旦保存更改它就会消失。
![#](images/ssms-fonts-and-colors-36.png?raw=true "#")
 
Here’s where you can change the ‘Outlining Margin Square’. This modifies the collapsible reference on the left side of all statements. This is usually pretty bright so I reduced the color to be 2 shades of grey.
在这里你可以改变'概述边缘广场'。这会修改所有语句左侧的可折叠引用。这通常很亮，所以我将颜色减少为2灰度。
![#](images/ssms-fonts-and-colors-37.png?raw=true "#")
 
Here’s where you can find the Outlining Margin Square color:
在这里你可以找到概述边缘方形颜色：
![#](images/ssms-fonts-and-colors-38.png?raw=true "#")
 
You can also modify the vertical rule beneath it. It’s called the ‘Outlining Margin Vertical Rule’.
你还可以修改其下方的垂直规则。它被称为“概述保证金垂直规则”。
![#](images/ssms-fonts-and-colors-39.png?raw=true "#")
 
Here’s where you can find the Outlining Margin Vertical Rule:
在这里你可以找到概述保证金垂直规则：
![#](images/ssms-fonts-and-colors-40.png?raw=true "#")
 

[![WorksEveryTime](https://forthebadge.com/images/badges/60-percent-of-the-time-works-every-time.svg)](https://shitday.de/)

## Build-Info

| Build Quality | Build History |
|--|--|
|<table><tr><td>[![Build-Status](https://ci.appveyor.com/api/projects/status/pjxh5g91jpbh7t84?svg?style=flat-square)](#)</td></tr><tr><td>[![Coverage](https://coveralls.io/repos/github/tygerbytes/ResourceFitness/badge.svg?style=flat-square)](#)</td></tr><tr><td>[![Nuget](https://img.shields.io/nuget/v/TW.Resfit.Core.svg?style=flat-square)](#)</td></tr></table>|<table><tr><td>[![Build history](https://buildstats.info/appveyor/chart/tygerbytes/resourcefitness)](#)</td></tr></table>|

## Author

- **李聪明的数据库 Lee's Clever Data**
- **Mike的数据库宝典 Mikes Database Collection**
- **李聪明的数据库** "Lee Songming"

[![Gist](https://img.shields.io/badge/Gist-李聪明的数据库-<COLOR>.svg)](https://gist.github.com/congmingshuju)
[![Twitter](https://img.shields.io/badge/Twitter-mike的数据库宝典-<COLOR>.svg)](https://twitter.com/mikesdatawork?lang=en)
[![Wordpress](https://img.shields.io/badge/Wordpress-mike的数据库宝典-<COLOR>.svg)](https://mikesdatawork.wordpress.com/)

---
## License
[![LicenseCCSA](https://img.shields.io/badge/License-CreativeCommonsSA-<COLOR>.svg)](https://creativecommons.org/share-your-work/licensing-types-examples/)

![Lee Songming](https://raw.githubusercontent.com/LiCongMingDeShujuku/git-resources/master/1-clever-data-github.png "李聪明的数据库")
