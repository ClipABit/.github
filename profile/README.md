# Welcome to the ClipABit GitHub!

### What is ClipABit?
ClipABit is a semantic search engine that enables video editors to search through their footage using natural language, saving them the time it takes to manually search through their files. Think of it as an ```AI-powered Ctrl+F``` tool for videos. You can search based on the context of the clip, location, entities and people. You can use it directly in an editor like Davinci Resolve or in the cloud through our web client.

### How does it work?
We take all the raw footage someone uploads, index it and save its context in a vector database that can be queried to find the most relevant clips instantly. All the indexing is done via a SLURM job that runs on WatCloud, which then stores the embeddings and raw footage in AWS. Upon querying, another job embeds your input and compares it against the vectors stored in the database, finds the most relevant ones and returns the videos associated with those embeddings.

## Journey

## The Team
This project couldn't have been possible without the leadership of our amazing technical project managers and the dedication of our core members

#### Technical Project Managers
- Eshaan Mehta: [Email](mailto:e3mehta@uwaterloo.ca) [LinkedIn](https://www.linkedin.com/in/eshaan-mehta-136a6924b/)
- Safiya Makada: [Email](mailto:smakada@uwaterloo.ca) [LinkedIn](https://www.linkedin.com/in/safiya-makada/)

#### Core Members
- [Guruprasanna Rajukannan Suresh](https://www.linkedin.com/in/guruprasanna-rajukannan-suresh/)
- [Kabir Jain](https://www.linkedin.com/in/kabirjain25/)
- [Sujash Nayak](https://www.linkedin.com/in/sujash-nayak/)
- [Ethan McManus](https://www.linkedin.com/in/ethan-mcmanus-302512302/)
- [Justin Wu](https://www.linkedin.com/in/justin-wu-171481162/)
- [Yifan Zhang]()
- [Warren Xu](https://www.linkedin.com/in/warren-xu/)
- [Adithya Thayyil](https://www.linkedin.com/in/adithayyil/)
