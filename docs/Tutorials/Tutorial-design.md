# Tutorial Design

The purpose of a hack week is to expose participants to a broad range of data science tools and methods. With this in mind, we suggest the following guidelines when developing a tutorial:

* Tutorials should be designed to address broad challenges in the data science community being served by the event. Speaking with community groups, reading blogs and attending workshops are good ways to connect with the most urgent data science challenges in a particular community. For example, the ICESat-2 hack week tutorial content was largely informed by members of the satellite's science team who were directly involved in releasing the data to the research community. 
* Based on the needs of the community, and in consultation with other event planners, build an outline of desired learning outcomes.  
* Consider how you would like to balance teaching on core concepts versus the technical aspects of operating a specific tool or library. Be mindful of spending too much time on a tool you might have just discovered that represents the latest and greatest, but might not be something the community decides to adopt in the long term. 
* Include content that provides an initial picture of what might be possible when applying a particular data science tool. Save detailed explanations on a narrow topic for a later breakout session.
* Start with simple explanations that attend to people who are seeing this content for the first time, AND keep advanced participants engaged by inviting them to assist others, or to explore more advanced concepts through individual study.
* Make your tutorials interactive through live coding challenges, working through a Juypter Notebook together, or interactive discussions. Leave some space when you are not talking for people to work through examples and ask questions. 
* take a bit of time to review tutorials offered at our previous hackweeks. [Here](https://www.youtube.com/watch?v=VMJ1ZO48cwU) is an example of a particularly well-crafted tutorial by Catherine Kuhn at the 2018 Geo Hack Week.

## Tutorial Timeline

It is a good idea to prepare your tutorials well in advance of the event so that they can be reviewed by other tutorial developers and members of the community. In some cases early preparation is required so that shared computing resources can be tested and configured to contain the libraries and datasets necessary to run the tutorials. Early tutorial preparation also cretes an opportunity for exploring the overall flow of tutorial ideas and concepts across the event. 

## Technical Considerations

Teaching software and data science tools to a large group of people is challenging when each person arrives with a different computer and operating system configuration. To avoid these challenges we often deploy shared computing resources, such as an instance of JupyterHub on a commercial cloud platform. We then have participants log in to this system using GitHub credentials. This centralized computing architecture can be directly linked to virtual drives that store any of the sample datasets used in the tutorials. Each tutorial can also be tested in advance on this system to ensure all the correct libraries and tools are installed.

## Tutorial Formats

We have experimented with several different ways to construct and serve tutorial content online. These include:

* using templates developed by the [Software Carpentry](https://software-carpentry.org/) organization, such as the [Geo Hack Week vector tutorial](https://github.com/geohackweek/vector). This apprach enables the building of a curriculum over time that is openly available as a reference to the community. Another advantage to this format is that others can request to add content or make corrections via GitHub pull requests. A disadvantage to this approach is that participants cannot interact directly with coding examples, as is possible with a Jupyter Notebook. It also takes more time for tutorial leads to copy and paste code into the markdown format of these tutorial templates.   
* preparing Jupyter Notebooks that combine explanatory text and graphics together with code. These notebooks can be copied directly to each participant's working directly and they can instantly begin following along with the instructor during the tutorial. Some tutorial leads include all of their code in the notebook and have participants run the code in tandem with the teacher. Others keep the code blocks empty and ask participants to write the code in real time, or give them time to compose their own code blocks in response to instructional prompts.
* presenting a slideshow containing text and images to teach specific concepts. This is a more traditional style of lecturing that might be appropriate for providing big picture overviews about the scientific underpinnings of specific data science applications.
* teaching with hand-written drawings, text or equations at a whiteboard. Sometimes it helps just to step away from the screen and explain some core concepts with a traditional (pre-PowerPoint era) lecture.

## Interactive content

The hack week model strives to provide participants with an interactive and immersive experience. Building interactive tutorials is a good way to achieve this goal. We have experimented with the [Software Carpentry](https://software-carpentry.org/) approach to teaching software which involves inviting participants to solve a coding challenge or work through an example during the tutorial. We provide each particiant with two different colored post-it notes that they can use to indicate if they do or do not need help with a particular example. This approach requires having multiple assistants in the room who are familiar with the tutorial and can be available to help answer questions. Without these assistants it can become too overwhelming for one tutorial lead to both navigate the overall pace of the teaching and answer detailed questions from individual participants. 

## Tutorial Scheduling and flow

Once the overall learning outcomes of each individual tutorial are articulated, the planning committee should spend some time considering the best way to sequence the tutorials. Ideally core concepts, for example the use of GitHub and other collaborative software tools, should be introduced early in the event. If possible, look for ways that one tutorial can build on the previous one. In some cases it may be desirable to have a common sample dataset that is worked with across multiple tutorials as a way to provide a coherent theme. 

The scheduling of tutorials will also impact the overall pacing of the event. Consider the energy of the participants at different stages, and their capacity to absorb new knowedge. For example, having too many dense and more complex tutorials on a given day might not leave people with enough energy to take part in projects or hacking later in the day.  