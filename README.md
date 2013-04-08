RSpec Git Pre-commit Hook
=========

This pre-commit hook will run when you attempt to commit to your git repository. It will invoke your rspec tests and not allow you to commit unless they are all passing/pending. If any failures occur then it will stop the commit from going through to allow you to fix your tests.

Usage
-----

1. Copy the pre-commit hook file into your .git/hooks directory.
2. Try to perform a git commit -m with a failing Rspect test.

If the hook is not getting executed, call ```chmod +x .git/hooks/rspec-precommit``` to make it so!
