# Welcome to the Mono game modding guide! This will teach you how to mod games, incase if your a beginner.
**Step 1:**
Get an APK decompiler. APKToolkit works best.
**Step 2:**
Once you got ApkToolKit, Click the blue paper at the top right. Select an APK.
**Step 3:**
Click "Decompile", Once it finishes, the decompilation should be saved in a "1 - Decompiled" folder.
**Step 4:**
Install dnSpy. This is mandatory as its needed to ACTUALLY modify the games code.
**Step 5:**
In dnSpy, Click "File", then "Open" Navigate to the decompilation output.
**Step 6:**
In the decompilation output, go to "assets\bin\Data\Managed\" You should see an "Assembly-CSharp.dll" file. Open it in dnSpy.
**Step 7:**
In dnSpy's "Assembly Explorer", open the DLL, then click the pink "Assembly-CSharp".
**Step 8:**
Inside the pink "Assembly-CSharp", You should see an option like: "{ } -". Click it.
**Final Step:**
This will reveal the classes of the game, A.K.A, the brain of the game. Hope this helped you know how to mod.

# A Notice
1. This is only for games using the Mono scripting backend.
2. Using this guide for IL2CPP game modding wont work. It will take way more effort.
