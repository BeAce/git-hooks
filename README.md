# git-hooks
nodejs git hooks 

## Usage
Copy `commit-msg` file to `.git/hooks/commit-msg`

```bash
$ chmod 777 .git/hooks/commit-msg
$ git add file
$ git commmit -m "message"
```

## ERROR

> 你的 commit message 是:  直太短了，我有点忍受不了。请尽可能详尽地描述你解决的问题 

> ❌  ERROR: 不合法的 commit message, 请遵守 commit message 提交规范。  请仔细阅读规范：xxxxx

## SUCCESS

> 😁  SUCCESS: 太赞了，commit message 通过了检查
> [feature-commit f9341ed] feat(test): 直太短了，我有点忍受不了。请尽可能详尽地描述你解决的问题fasdfsafsdfasdfasdf
> 1 file changed, 1 insertion(+), 1 deletion(-)
