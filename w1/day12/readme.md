# jQuery动画
1. 显示和隐藏
	1. show("持续时间","动画结束之后的执行函数")
	2. hide()
	3. toggle()
2. 淡入淡出
	1. fadeIn() 透明度从0到默认值
	2. fadeOut() 透明度从默认值到0
	3. fadeTo(0.5) 透明度淡入淡出到指定值（更新默认值）
3. 划入划出
	1. slideDown()
	2. slideUp()
	3. slideToggle()
4. 自定义动画
	$(selector).animate(CSS-JSON[,speed[,callback]]);
# jQuery与Ajax
1. $.get()
2. $.post()
3. $.ajax()