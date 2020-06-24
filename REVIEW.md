# review items

## how do we fork a repo? 

    We fork a repo from github itself, it copies it into our github profile, and we then clone it from our account onto our local. This sets the remote address on our machine as well.

## how do clone a repo to be available on our local?

    We copy the github target address and then go to our parent directory on our local (something like ~user/Code) and then type "git clone git-address-here"

## how do we move changes from working folder to staging?
    
    "git add ." where . means all modified files, or "git add specific-file-here"

## how do we move changes from staging folder to the local repo?
    
    "git commit -m "Write concise commit message here" "

## how do we confirm what is in the local repo

    After the git commit command, you can type "git log" which will show you a record of local commited changes that have been written to the index.

## how do we confirm what is in the remote repo

    After committing changes, and most importantly "git push --all origin", which pushes all of the local commits to the remote, you can use "git log" to verify that your local branches have been pushed to your remote branches.

## how do we confirm the url of our git remotes?

    "git remote -v" where -v shows you a verbose listing of the remote addresses

## how many and what sections are in an html document

    There are two main sections of an HTML document: the head, which contains metadata/document/script data, and the body which contains the structural HTML information tags.

## there are two ways to reference css in the header - show examples of two tags that are used for styling

    You can link to a css style sheet either locally or externally (bootstrap.css), you can also reference styles by id, class, or improperly inline. <div class = "header"> </div> 



## 3 - how many ways can you declare a variable
## hint - 1 old school way - the new ways
## provide a few samples

    You can use: 
        --var: globally set 
            var computer = broken

        --let: not globally set
            let car = subaru

        --const: variable that cannot be reassigned
            const a = 4