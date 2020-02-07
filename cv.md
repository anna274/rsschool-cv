## Anna Rusakovich
### Contacts:
* *email*: anna_rusakovich.01@mail.ru
* *phone*: +375(44)750-17-36
### Summary
My goal is to try my hand at Web development, to learn bacics and to use it in creating real projects and in solving different issues. I want to practice skills in working with GIT version control and some web development tools and frameworks. An improving soft skills is also important for me. It includes communication, stress resistance and an ability to find information fast.
It's essential for me that my job is done well, so I'm ready to spent as much time as needed for it. My forte is time manegement. I know how to prioritize tasks and how to complete them before deadlines.
### Skills:
* *programming languages*: C++, JavaScript basics, Java basics, ; 
* *frameworks:* Laravel;
* *tools:* Visual Studio, Visual Studio Code, Intellij IDEA;
* *version control:* GitHub.
### Code examples:
```php
  public function index()
    {
        $posts = Post::all();
        
        return view('posts.index')->withPosts($posts);
    }
```

```php
 public function show($id)
    {   
        $post = Post::find($id);
        $posts = Post::where('category_id', $post->category_id)->get();      
        $print = (isset($_GET['print']))?'print':'default';
        
        return view('posts.show', compact('print', 'post', 'posts'));
    }
```
### Experience:
* a simple blog site (PHP, Laravel);
* tasks from Coursera courses "Algorithms. Path 1" in Java;
* a course project in C++.
### Education:
* Belarusian State University of informatics and radioelectronics (2 course);
* Coursera "Algorithms. Path 1" online courses;
* HTMLAcademy online courses.
### English:
* an intermidiate level B1;
* learning technical English at university (1 year);
* International House courses (7 mounths);
* Skyteach Festival volunteering.
