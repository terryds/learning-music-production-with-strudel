# Making Beats in Strudel

In this course, we’re going to use Ableton Live guide and some other resources ( Youtube video & [Drumbit.app](http://Drumbit.app) ) to practice making beats, and writing it in Strudel.

First, please make sure you’ve at least completed the Official Strudel’s Getting Started Workshop https://strudel.cc/workshop/getting-started/ so you have a basic knowledge of mini-notation format and understand about setting the tempo (cycles per minute) in Strudel docs.

Now, let’s try to make beats using Strudel.

Let’s start with getting familiar with drums first.

Now, let’s open Ableton’s learning music and try to make the same beat with Strudel

![image.png](Making%20Beats%20in%20Strudel/image.png)

[Make beats | Learning Music](https://learningmusic.ableton.com/make-beats/make-beats.html)

Open the link and hear the beats, and try to do it in Strudel

Try making the beats on Strudel by yourself.

Open the solution below after either you’ve managed to do it yourself or having trouble.

- Show Strudel Code
    
    Take note that we can use `$variable` to stack as well besides the javascript syntax `const` or `let` like we did previously
    
    Here is the solution using `const` and stack() syntax
    
    [https://strudel.cc/#c2V0Y3BtKDk4LzQpCgovLyBEZWZpbmUgZWFjaCBpbnN0cnVtZW50IHBhdHRlcm4KY29uc3Qga2ljayA9IHMoIltiZCB%2BIH4gfl1bfiB%2BIH4gYmRdW34gfiBiZCB%2BXVt%2BIH4gfiBiZF0iKQpjb25zdCBjbG9zZWRIYXQgPSBzKCJbaGggaGggfiB%2BXVsgaGggfiBoaCB%2BXVtoaCB%2BIGhoIH5dW2hoIH4gaGggfl0iKQpjb25zdCBvcGVuSGF0ID0gcygiW34gfiBvaCB%2BXVt%2BIH4gfiB%2BXVt%2BIH4gfiB%2BXVt%2BIH4gfiB%2BXSIpCmNvbnN0IGNsYXAgPSBzKCJbfiB%2BIH4gfl1bY3AgfiB%2BIH5dW34gfiB%2BIH5dW2NwIH4gfiB%2BXSIpCgovLyBTdGFjayB0aGVtIHRvZ2V0aGVyCnN0YWNrKG9wZW5IYXQsIGNsb3NlZEhhdCwgY2xhcCwga2ljaykuYmFuaygiUm9sYW5kVFI5MDkiKQo%3D](https://strudel.cc/#c2V0Y3BtKDk4LzQpCgovLyBEZWZpbmUgZWFjaCBpbnN0cnVtZW50IHBhdHRlcm4KY29uc3Qga2ljayA9IHMoIltiZCB%2BIH4gfl1bfiB%2BIH4gYmRdW34gfiBiZCB%2BXVt%2BIH4gfiBiZF0iKQpjb25zdCBjbG9zZWRIYXQgPSBzKCJbaGggaGggfiB%2BXVsgaGggfiBoaCB%2BXVtoaCB%2BIGhoIH5dW2hoIH4gaGggfl0iKQpjb25zdCBvcGVuSGF0ID0gcygiW34gfiBvaCB%2BXVt%2BIH4gfiB%2BXVt%2BIH4gfiB%2BXVt%2BIH4gfiB%2BXSIpCmNvbnN0IGNsYXAgPSBzKCJbfiB%2BIH4gfl1bY3AgfiB%2BIH5dW34gfiB%2BIH5dW2NwIH4gfiB%2BXSIpCgovLyBTdGFjayB0aGVtIHRvZ2V0aGVyCnN0YWNrKG9wZW5IYXQsIGNsb3NlZEhhdCwgY2xhcCwga2ljaykuYmFuaygiUm9sYW5kVFI5MDkiKQo%3D)
    
    Take note that we need to convert bpm to cpm. We use 4 beats per cycle so we need to divide by 4.
    
    You can also simplify the syntax using $ like this
    
    [https://strudel.cc/#c2V0Y3BtKDk4LzQpCgovLyBEZWZpbmUgZWFjaCBpbnN0cnVtZW50IHBhdHRlcm4KJGtpY2s6IHMoIltiZCB%2BIH4gfl1bfiB%2BIH4gYmRdW34gfiBiZCB%2BXVt%2BIH4gfiBiZF0iKS5iYW5rKCJSb2xhbmRUUjkwOSIpCiRjbG9zZWRIYXQ6IHMoIltoaCBoaCB%2BIH5dWyBoaCB%2BIGhoIH5dW2hoIH4gaGggfl1baGggfiBoaCB%2BXSIpLmJhbmsoIlJvbGFuZFRSOTA5IikKJG9wZW5IYXQ6IHMoIlt%2BIH4gb2ggfl1bfiB%2BIH4gfl1bfiB%2BIH4gfl1bfiB%2BIH4gfl0iKS5iYW5rKCJSb2xhbmRUUjkwOSIpCiRjbGFwOiBzKCJbfiB%2BIH4gfl1bY3AgfiB%2BIH5dW34gfiB%2BIH5dW2NwIH4gfiB%2BXSIpLmJhbmsoIlJvbGFuZFRSOTA5IikK](https://strudel.cc/#c2V0Y3BtKDk4LzQpCgovLyBEZWZpbmUgZWFjaCBpbnN0cnVtZW50IHBhdHRlcm4KJGtpY2s6IHMoIltiZCB%2BIH4gfl1bfiB%2BIH4gYmRdW34gfiBiZCB%2BXVt%2BIH4gfiBiZF0iKS5iYW5rKCJSb2xhbmRUUjkwOSIpCiRjbG9zZWRIYXQ6IHMoIltoaCBoaCB%2BIH5dWyBoaCB%2BIGhoIH5dW2hoIH4gaGggfl1baGggfiBoaCB%2BXSIpLmJhbmsoIlJvbGFuZFRSOTA5IikKJG9wZW5IYXQ6IHMoIlt%2BIH4gb2ggfl1bfiB%2BIH4gfl1bfiB%2BIH4gfl1bfiB%2BIH4gfl0iKS5iYW5rKCJSb2xhbmRUUjkwOSIpCiRjbGFwOiBzKCJbfiB%2BIH4gfl1bY3AgfiB%2BIH5dW34gfiB%2BIH5dW2NwIH4gfiB%2BXSIpLmJhbmsoIlJvbGFuZFRSOTA5IikK)
    
    Notice that if we use $ notation, we don’t even need to write the stack() function.
    
    Check out https://strudel.cc/learn/mondo-notation/#multiple-patterns
    
    ## Reading Recommendations
    
    https://strudel.cc/workshop/getting-started/ to get started
    
    https://strudel.cc/learn/samples/#default-samples for notation of drum sounds in Strudel
    
    https://strudel.cc/learn/mini-notation/ to understand the mini-notation
    
    https://strudel.cc/understand/cycles/#setting-cpm to understand how a cycle (or a bar) works in Strudel
    
    Next, let’s dive deeper into these sounds
    
    [What are these sounds?](Making%20Beats%20in%20Strudel/What%20are%20these%20sounds%202ac98431b24181d9aadaf47fc07aa50f.md)
    

- Table of Contents
    
    [Beat and Tempo](Making%20Beats%20in%20Strudel/Beat%20and%20Tempo%202ac98431b24181c091e8c66c8662fa75.md)
    
    [Tempo and Genre](Making%20Beats%20in%20Strudel/Tempo%20and%20Genre%202ac98431b24181e8a60ce9dc8d2250d3.md)
    
    [Backbeats](Making%20Beats%20in%20Strudel/Backbeats%202ac98431b24181779622d572bfaead4c.md)
    
    [Bars](Making%20Beats%20in%20Strudel/Bars%202ac98431b24181d7882ff34bc652a7ce.md)
    
    [Rock and house](Making%20Beats%20in%20Strudel/Rock%20and%20house%202ac98431b24181068186e91eae54d656.md)
    
    [“We Will Rock You”](Making%20Beats%20in%20Strudel/%E2%80%9CWe%20Will%20Rock%20You%E2%80%9D%202ac98431b24181b3b8dde349cade9f68.md)
    
    [“Single Ladies”](Making%20Beats%20in%20Strudel/%E2%80%9CSingle%20Ladies%E2%80%9D%202ac98431b24181c59d83f7e3831c02e6.md)
    
    [More Drum Patterns](Making%20Beats%20in%20Strudel/More%20Drum%20Patterns%202ac98431b24181f5b04ce656f381a232.md)
    
    [Macy’s Day Parade](Making%20Beats%20in%20Strudel/Macy%E2%80%99s%20Day%20Parade%202ac98431b2418127bc7ac9b0ea8cb0fc.md)
    
    [Play With Beats](Making%20Beats%20in%20Strudel/Play%20With%20Beats%202ac98431b24181fca297c7edfc266de6.md)