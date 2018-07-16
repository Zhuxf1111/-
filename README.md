# -
记录一些日常中看到的知识点


1.录制音频使用AudioRecord 播放音频使用AudioTrack
link:http://blog.csdn.net/lantingshuxu/article/details/53520316

2.onActivityResult 立马回掉的解决方法
去除跳转activity newInstance等模式

3.去除scrollerview 边界拉动的效果
<style name="NoEdgeEffectScrollViewStyle">
  <item name="android:overScrollMode">never</item>
  <item name="android:fadingEdge">none</item>
</style>
