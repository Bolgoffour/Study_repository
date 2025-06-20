Прореживание всей истории (оставляя только определенный коммит):
git reset --hard <desired-first-commit-hash>
git reset --hard HEAD~n (n - кол-во удаляемых коммитов)
git push origin <branch-name> --force