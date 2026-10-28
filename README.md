# INCONCLUSIVE: you reached the real GitHub

This README belongs in the real repository at
https://github.com/galadran/emudhra-git-test. You are reading it because your
git connected to the real github.com, not to our test server, so the test did
not run.

The usual cause is a git older than 2.37, which silently ignores the
`http.curloptResolve` setting the test command uses to reach the test server. Check
with:

    git --version

The test only shows a result when the README in your clone starts with
**INTERCEPTED** (your git accepted a fake github.com) or when git refuses the
clone with a certificate error (your git is protected).

Instructions: https://emudhra.we-have-a-problem.com/apple.html
