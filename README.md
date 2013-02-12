http://rosylilly.hatenablog.com/entry/2013/02/11/183115
が便利そうだったので

# 使い方

適当な場所に clone して

    $ cat [username].pub [username2].pub > ~/.ssh/authorized_keys
    $ chmod 600 ~/.ssh/authorized_keys
    
後から追加するならこうかな
    
    $ cat [username3].pub >> ~/.ssh/authorized_keys
