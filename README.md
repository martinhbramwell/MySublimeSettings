# MySublimeSettings
How I synch my Sublime Text 3 settings between all machine

Replaces the directory 

    /home/you/.config/sublime-text-3/Packages/User/

Depends on

    npm install -g eslint 
    npm install -g babel-eslint 
    npm install -g eslint-plugin-react

Set up

    pushd ${HOME}/.config/sublime-text-3/Packages;
    mv User User_$(date +%Y%m%d%H%M%S);
    git clone git@github.com:martinhbramwell/MySublimeSettings.git User;
    popd;
    
