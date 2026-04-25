# Welcome to the ClipABit GitHub!

### What is ClipABit?
ClipABit is a plugin that enables video editors to quickly search for specific moments in their footage using natural language. It's an AI-powered Ctrl+F tool powered with the full context of your clips. Simply describe what you’re looking for and ClipABit will not only find the right video, but also the exact timestamp. It integrates directly as a plugin into DaVinci Resolve, enabling instantaneous searching without interrupting the editing flow.  **Check out our website and download [here](https://clipabit.web.app), or test it out from our online demo [here](https://clipabit.web.app/demo)!**

### How does it work?
We take all the user uploaded footage, index it and save its context in a vector database that can be queried to find the most relevant clips instantly. During indexing, we chunk and normalize videos, extract frames and create embeddings from the visual and audio semantics. This is done using various pre-trained models. At the same time, we also extract any faces from frames, cluster identical ones together and tag them. Upon querying, the user input is compared against the vectors stored in the database, where the most relevant ones are retrieved, ranked, and the respective video clips are returned. 

### What can you find here?
Here you’ll find repositories for the various projects and initiatives our team is working on. This includes implementations of the core ClipABit product, experimental research into new model architectures, and testing frameworks for evaluating performance. **Feel free to browse around and explore what we’ve been building!**

### The Team
This project couldn't have been possible without the leadership of our amazing technical project managers and the dedication of our core members!

#### Technical Project Managers
- Eshaan Mehta: [Email](mailto:e3mehta@uwaterloo.ca) [LinkedIn](https://www.linkedin.com/in/eshaan-mehta-136a6924b/)
- Safiya Makada: [Email](mailto:smakada@uwaterloo.ca) [LinkedIn](https://www.linkedin.com/in/safiya-makada/)

#### Core Members
- [Sujash Nayak](https://www.linkedin.com/in/sujash-nayak/)
- [Ethan McManus](https://www.linkedin.com/in/ethan-mcmanus-302512302/)
- [Justin Wu](https://www.linkedin.com/in/justin-wu-171481162/)
- [Yifan Zhang](https://www.linkedin.com/in/yifan-zhang-a120652b3/)
- [Warren Xu](https://www.linkedin.com/in/warren-xu/)
- [Adithya Thayyil](https://www.linkedin.com/in/adithayyil/)
