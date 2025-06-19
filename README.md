Here I created a Python-based project that explores your music listening habits using a graph and Breadth-First Search (BFS). Find out which artist you listen to the most and get recommended artists based on your current music taste!

Features: find your most listened to or streamed artist, discover recommended artist based off listening history, visualize your music network as a graph, use Breadth First Search to range artist.

Project structure:
music_bfs/
├── music_graph.py       # Contains graph logic and BFS traversal
├── user_data.py         # Stores or simulates user listening history
├── main.py              # Entry point that runs the application
└── README.md            # This file

How it processes
* user listening history is stored as a graph
* edge represents similarities between artists based on genre, flow, and collaboration
