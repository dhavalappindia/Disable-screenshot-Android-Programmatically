<B>Add Following line to your Activity or fragment to restrict screen shot capturing Also screen cast or screen mirroring </B>


getWindow().setFlags(WindowManager.LayoutParams.FLAG_SECURE,WindowManager.LayoutParams.FLAG_SECURE);


