**NAME**  
T W I L - Stands for "This Week I Learned"  
  
**SYNOPSIS**  
TWIL [Students Club]  
  
**DESCRIPTION**  
TWIL Club is dedicated to enable students to share what they have learned, the subjects might be any tech related discipline (e.g., Algorithms and AI, Networking and Security, Graphics, Mathematics, ..).  
  
**FORMAT**  
The TWIL session are going to be organized on weekly basis.  
There will be multiple formats of speeches:  

* **Lecture** *(30 min --extendable)*: direct talk about specific subject.
* **Quickie** *(10-15 min)*: brief talk where the focus is on providing keywords for later search.
* **Tools-in-Action** *(30 min)*: a presentation of a tool that includes demos and best practices.

**PROPSALS SUBMISSIONS**  
if you want to give a talk in one of T W I L's sessions, please make a pull request to this repository adding a file in this format:  

    name:  
    title:  
    description:  
    format: [Lecture | Quickie | Tools-in-Action]

**MODERATORS**  
[M'bark Erras](https://github.com/MbarkErras), [Youssef Lagtab](https://github.com/vanderwolk).

<ul>
	{% for post in site.posts %}
    	<li>
	    	<a href="{{ post.url }}">{{ post.title }}</a>
		</li>
	{% endfor %}
</ul>
