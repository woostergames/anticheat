# anticheat
all you have to do is load this in unity 
then click on the left of the screen "GameObject" once you do that at the right click the title that says "GameObject" click edit script and change the following lines  public string modDataFolderName = "moddata"; // EDIT HERE: change folder name if needed

    [Tooltip("File name to detect cheats inside moddata folder")]
    public string cheatFileName = "com.anti.cheat";  // EDIT HERE: change to your mod file name

    [Tooltip("Name of scene to load after validation")]
    public string sceneToLoad = "MainScene"; // EDIT HERE: change to your target scene name 

    
