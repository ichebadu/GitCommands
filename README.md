# GitCommands
Git basics
decag@Decagons-MacBook-Pro-3 piPay % git fetch origin main
From https://github.com/ichebadu/piPay
 * branch            main       -> FETCH_HEAD
decag@Decagons-MacBook-Pro-3 piPay % git pull origin main --allow-unrelated-histories
From https://github.com/ichebadu/piPay
 * branch            main       -> FETCH_HEAD
hint: You have divergent branches and need to specify how to reconcile them.
hint: You can do so by running one of the following commands sometime before
hint: your next pull:
hint: 
hint:   git config pull.rebase false  # merge
hint:   git config pull.rebase true   # rebase
hint:   git config pull.ff only       # fast-forward only
hint: 
hint: You can replace "git config" with "git config --global" to set a default
hint: preference for all repositories. You can also pass --rebase, --no-rebase,
hint: or --ff-only on the command line to override the configured default per
hint: invocation.
fatal: Need to specify how to reconcile divergent branches.
decag@Decagons-MacBook-Pro-3 piPay % git config pull.rebase false
decag@Decagons-MacBook-Pro-3 piPay % git pull origin main --allow-unrelated-histories
From https://github.com/ichebadu/piPay
 * branch            main       -> FETCH_HEAD
fatal: Could not read from '.git/MERGE_MSG': No such file or directory
decag@Decagons-MacBook-Pro-3 piPay % 
