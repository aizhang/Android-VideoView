Android-VideoView
=================
  VideoView is used to play video, a great replacement for android.widget.VideoView VideoView. We define a custom view, because we could not use {@link android.widget.VideoView VideoView} in ListView.
  VideoViews inside ScrollViews do not scroll properly. Even if you use the workaround to set the background color, the MediaController does not scroll along with the VideoView. Also, the scrolling video looks horrendous with the workaround, lots of flickering.
