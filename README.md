# Gomoku

A strategy board game implemented for Artificial Intelligence course:</br>

**Task**: 
  - Implement Gomoku with a GUI
  - Provide 3 levels of difficulty with 3 different AI strategies (algorithms, heurisitics)
  - On player turn provide move suggestions

**Programming Language**: Python with tkinter package from Tk GUI toolkit</br></br>
**AI concepts**:
  - Computer moves randomly for level 1
  - For level 2 and 3: 2 heuristics that assign a score to the board state depending on open and potential future winning positions of both players
  - Min-Max algorithm to simulate, up to a certain depth of exploration, all possible future plays of the game, given a current state, in order to choose the best possible move for the current player, depending on the value of the heuristic. 
