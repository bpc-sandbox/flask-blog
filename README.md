### Falsk sample code

For self-reference only ([source - realpython.com](http://realpython.com))

### Note to self

| File | Syntax | Note |
| --- | --- | --- |
| blog.py | `g`.db... | `g` object as a 'request blackboard'. This blackboard gets wiped clean after the request is finished([ref](https://stackoverflow.com/questions/15083967/when-should-flask-g-be-used)). In thise example it work as best practice to dealing with database connections within request. |
| blog.py | return (response, status, headers) | best practice: assign status code when build RESTful API |

