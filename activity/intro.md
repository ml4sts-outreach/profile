# Introduction

```{important}
Today's activity will require that you [create a github account](https://github.com/signup) work on this during the introduction. If you have not yet have an account, or make sure you can log in to your existing one. 
```


## Intro


My approach to presenting: 
- conversational, open, active
- **not** cram in as much as possible
- my prep is to cut back, decide what I can skip, not make pretty visuals
- *key ideas* so that you can learn more later

While we get started, I invite you to: 
- close your email
- turn off messaging
- put down your phone

We will have 4 parts to this workshop:
- setup (me talking)
- guided work (I do & you follow)
- self-paced work ( you work & I help; take breaks as you need)
- wrap up (I will summarize and answer big questions)

## Motivation and content


Learning goals:
- core ideas of version control
- basic idea of a static site generator
- 

Key Takeaways: 
- github flow knowledge
- a working profile website
  
### Version Control is worth it

![phd comics notfinal.doc](http://www.phdcomics.com/comics/archive/phd101212s.gif)

[source](https://phdcomics.com/comics/archive.php?comicid=1531)

- git keeps track of versions of your work
- currently the norm; other version control systems are increasingly irrelevant
- GitHub is the most popular host, but there are others

```{mermaid}
flowchart TD
    ghp[Github Pages] --> |is| h[web host]
    ghp --> |is a feature of| gh[GitHub]
    ghost[git host] --> |owned by MSFT| gh
    git[git] --> |most useful with| ghost
    ghost --> |by Atlassian| bb[BitBucket]
    vcs[Version control system] --> |examples include| git & cvs  & svn
    git --> |tracks changes with | commit
    commit --> |contains| sn[snapshot of files] & ms[descriptive message]
    commit --> |identified by| hash[alphanumeric hash] 
```

### Why this is a good way to make a website

- static sites have fast page load times
- static sites have low security risks (cannot hack what does not exist)
- using a generator separates content from style (mostly)
- someone else writes the HTML/CSS/Javascript
- you can change the theme in ~100 characters or less
- responsive (adapts to mobile screens) site without doing the work
- common accessibility built in with no effort
- GitHub pages is free!
- **very** little of this site is GitHub specific, you can move to a different host pretty easily, with just a little understanding

```{mermaid}
flowchart TD
    website --> |address| url
    url --> |before the last .| d[domain]
    url --> |after the last .| tld[top level domain]
    tld --> |for example| com & org & gov
    d--> |for example| github & google & brownsarahm
    website --> |files stored at | host
    host --> |for example| dreamhost & ghp[GitHub pages] & nc[Name Cheap]
```



