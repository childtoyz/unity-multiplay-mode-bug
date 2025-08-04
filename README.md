# Unity Multiplay Mode Bug Reproduction Project

## Unity Version  
- 6000.35f1

## Fish-Networking Version  
- 4.6.12R Pro

## Bug Description  
- **Issue:** Prefab not found after modifying a prefab in main.  
- **Expected Behavior:** Modified prefab should update correctly and be found during gameplay.  
- **Actual Behavior:** When not using generated prefab list, the modified prefab is not found, causing persistent errors.

## How to Test  
1. Open the project and open the GameScreen scene.  
2. Activate player 2 with multiplay mode and start the game.  
3. Everything should work smoothly.  
4. Make a change to the RigidbodyPrediction2D prefab inside `Assets/MyBugReport/Resources/`.  
5. Restart the game.  
6. You will see the Prefab Id XYZ not found error in multiplay mode.

## Notes  
- FishNet files are excluded from this package.  
- This project contains only the minimal setup needed to reproduce the issue.  
- Unity and FishNet versions are listed above.

---

Thank you!

@Kojak (in discord community) 
