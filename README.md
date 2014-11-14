Android Swipe-to-Dismiss Sample Code forked by brownsoo
====================================
I create a new fork class - SwipeDismissListViewTouchListener with adding some functions below.  
밀어서(Swipe) 리스트뷰의 아이템을 사라지게 만들기 위해 [SwipeDismissListViewTouchListener](https://github.com/romannurik/android-swipetodismiss)를 복제하고 새로운 클래스를 만들고수정했습니다.  
아래 함수들이 추가된 사항입니다.  

* setSwipeDistanceRatio(float) : 밀기 가능한 거리를 지정한다.
* setSwipeMode(int) : 밀기 방향을 오른쪽, 왼쪽, 양쪽으로 지정한다.
* setEnableTouchListen(boolean) : 터치 이벤트 동작을 활성 또는 비활성 시킨다.
* setDoDismiss(boolean) : 밀기를 통해 사라지게 할 것인지 결정한다.
* setDismissDecisionDistanceRatio(float) : 얼마나 이동했을 때 사라지게 할지 그 거리를 지정한다.
* DismissCallbacks#onTryToDismiss(android.view.View, int) : isDoDismiss() 값이 false 일 때, 밀어서 사라지지 않는 대신에 이 콜백이 실행된다.
* dismiss(android.view.View, int) : 뷰를 사라지게 한다.
  
new class :  
    com.hansune.touch.SwipeDismissListViewTouchListener  
  
With these function codes, I made a some different example.  
Thanks to original author. 감사해요~!  
Brownsoo.  
  
sample [video](http://youtu.be/ONRMNjrDR_U)
  
  
See the original [Git](https://github.com/romannurik/android-swipetodismiss) soruce.  
See the original [Google+ post](https://plus.google.com/+RomanNurik/posts/Fgo1p5uWZLu) for discussion.  
