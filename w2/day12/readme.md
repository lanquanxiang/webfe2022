# jQuery动画
1. 显示和隐藏
	1. show(动画持续时间，动画结束之后执行的函数)
	2. hide()
	3. toggle()
2. 淡入和淡出
	1. fadeIn() 透明度从0到默认值
	2. fadeOut() 透明度从默认值到0
	3. fadeTo() 透明度淡入淡出到指定值（更新默认值）
3. 划入和划出
	1. 划入 slideDown()
	2. 划出 slideUp()
	3. 切换 slideToggle()
4. 自定义动画和动画清除
	1. 自定义动画$(selector).animate(params[,speed[,callback]]).animate().animate();
	2. 清除动画 stop()
# jQuery与Ajax
1. $.get()
2. $.post()
3. $.ajax()